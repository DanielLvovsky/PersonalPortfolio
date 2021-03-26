<script setup lang="ts">
import { isDark } from '/~/logics'
</script>

<template>
  <header class="header">
    <router-link
      class="w-10 h-10 absolute lg:fixed m-6 select-none outline-none"
      to="/"
      focusable="false"
    >
      <img v-show="isDark" src="/logo.png" alt="logo">
      <img v-show="!isDark" src="/logo-dark.png" alt="logo">
    </router-link>
    <nav class="nav">
      <div class="spacer" />
      <div class="right">
        <!-- Blog WIP 
        <router-link to="/posts">
          Blog
        </router-link>
        -->
        <router-link to="/projects">
          Projects
        </router-link>
        <!--  a(href='/notes')//  span.iconify.text-lg(data-icon='ri:chat-1-line') -->
        <router-link to="/resume" title="Resume">
          <ri-bookmark-line />
        </router-link>
        <!-- Blog WIP 
        <router-link to="/notes" title="Notes">
          <ri-sticky-note-line />
        </router-link>
        -->
        <a href="https://instagram.com/daniel_lvovsky" target="_blank" title="Instagram" class="hidden md:block">
          <feather-instagram />
        </a>
        <a href="https://www.youtube.com/channel/UC2b9MA7P_yaopMSdBT89iqQ" target="_blank" title="Youtube" class="hidden md:block">
          <feather-youtube />
        </a>
        <a href="https://github.com/DanielLvovsky" target="_blank" title="GitHub" class="hidden md:block">
          <uil-github-alt />
        </a>
        <a href="https://www.linkedin.com/in/daniellvovsky/" target="_blank" title="Linkedin" class="hidden md:block">
          <feather-linkedin />
        </a>
        <toggle-theme />
      </div>
    </nav>
  </header>
</template>

<style scoped>
.header h1 {
  margin-bottom: 0;
}

.logo {
  position: absolute;
  top: 1.5rem;
  left: 1.5rem;
}

.nav {
  padding: 2rem;
  width: 100vw;
  display: grid;
  grid-template-columns: auto max-content;
  box-sizing: border-box;
}

.nav > * {
  margin: auto;
}

.nav img {
  margin-bottom: 0;
}

.nav a {
  cursor: pointer;
  text-decoration: none;
  color: inherit;
  transition: opacity 0.2s ease;
  opacity: 0.6;
  outline: none;
}

.nav a:hover {
  opacity: 1;
  text-decoration-color: inherit;
}

.nav .right {
  display: grid;
  grid-gap: 1.2rem;
  grid-auto-flow: column;
}

.nav .right > * {
  margin: auto;
}
</style>
