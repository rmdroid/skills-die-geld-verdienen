<script setup>
import { ref, computed, onMounted } from 'vue'
import { useData, withBase } from 'vitepress'
import DefaultTheme from 'vitepress/theme'
const { frontmatter } = useData()
const unlocked = ref(false), password = ref(''), error = ref('')
const restricted = computed(() => frontmatter.value.protected && !unlocked.value)
onMounted(() => { try { unlocked.value = sessionStorage.getItem('skills-book-access') === 'yes' } catch {} })
function unlock() {
  if (password.value === 'Skills_2026') {
    unlocked.value = true; error.value = ''; password.value = ''
    try { sessionStorage.setItem('skills-book-access', 'yes') } catch {}
  } else { error.value = 'Das Passwort stimmt noch nicht. Bitte prüfen Sie Groß- und Kleinschreibung.' }
}
</script>
<template>
  <main v-if="restricted" class="access-page">
    <a :href="withBase('/')" class="back-link">← Zur Buch-Website</a>
    <div class="access-panel">
      <p class="eyebrow">ROBERT MEYER · BEGLEITMATERIAL ZUM BUCH</p>
      <h1>Willkommen im Lesebereich</h1>
      <p>Das Passwort steht in Ihrem Buch auf der Seite „Mehr Informationen online“.</p>
      <form @submit.prevent="unlock">
        <label for="book-password">Zugangspasswort</label>
        <input id="book-password" v-model="password" type="password" autocomplete="current-password" required :aria-invalid="!!error" aria-describedby="password-error" />
        <p id="password-error" role="alert">{{ error }}</p>
        <button type="submit">Buch und Skills öffnen</button>
      </form>
      <a :href="withBase('/leseprobe.html')">Zuerst die kostenlose Leseprobe lesen →</a>
    </div>
    <p><a :href="withBase('/impressum.html')">Impressum</a> · <a :href="withBase('/datenschutz.html')">Datenschutz</a></p>
  </main>
  <DefaultTheme.Layout v-else />
</template>
