<script setup lang="ts">
import LogoBar from './components/LogoBar.vue'
</script>

<template>
  <div class="app-container">
    <!-- Sidebar -->
    <aside class="sidebar">
      <h2>Logo</h2>
      <ul>
        <li>Anime</li>
        <li>Book</li>
        <li>Anki</li>
        <li>Statistics</li>
      </ul>
    </aside>

    <!-- Main Content -->
    <main class="content">
      <h1>Hello!</h1>
      <section class="daily-checklist">
        <h2>Daily Checklist</h2>
        <p>This section will have daily tracking options.</p>
      </section>
      <section class="charts">
        <h2>Charts</h2>
        <p>Placeholder for charts.</p>
      </section>
    </main>
  </div>
</template>


<style scoped>
.logo {
  height: 6em;
  padding: 1.5em;
  will-change: filter;
  transition: filter 300ms;
}
.logo:hover {
  filter: drop-shadow(0 0 2em #646cffaa);
}
.logo.vue:hover {
  filter: drop-shadow(0 0 2em #42b883aa);
}
</style>
