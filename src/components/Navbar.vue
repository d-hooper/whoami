<script setup>
import { ref, watch } from 'vue';
import { loadState, saveState } from '../utils/Store.js';

const theme = ref(loadState('theme') || 'light')

watch(theme, () => {
  document.documentElement.setAttribute('data-bs-theme', theme.value)
  saveState('theme', theme.value)
}, { immediate: true })

</script>

<template>
  <nav class="navbar navbar-expand-md bg-light border-bottom border-secondary">
    <div class="container gap-2">
      <img class="navbar-brand" alt="Dallin Hooper logo" src="@/assets/img/Logo.png" height="50"
           title="Dallin Hooper" />
      <div class="d-flex fs-3">
        <a href="https://www.linkedin.com/in/dallin-hooper-b8208214a/" target="_blank"
           title="My LinkedIn profile page"><span class="mdi mdi-linkedin selectable px-1"></span></a>
        <a href="https://github.com/d-hooper" target="_blank" title="My GitHub profile"><span
                class="mdi mdi-github selectable px-1"></span></a>
      </div>

      <!-- collapse button -->
      <!-- <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbar-links"
              aria-controls="navbarText" aria-expanded="false" aria-label="Toggle navigation">
        <span class="mdi mdi-menu text-dark"></span>
      </button> -->
      <!-- collapsing menu -->
      <!-- <div class="collapse navbar-collapse " id="navbar-links">
        <ul class="navbar-nav">
          <li>
            <RouterLink :to="{ name: 'About' }" class="btn text-green selectable">
              About
            </RouterLink>
          </li>
        </ul>

      </div> -->
    </div>
  </nav>
</template>

<style lang="scss" scoped>
a {
  text-decoration: none;
}

.nav-link {
  text-transform: uppercase;
}

.navbar-nav .router-link-exact-active {
  border-bottom: 2px solid var(--bs-success);
  border-bottom-left-radius: 0;
  border-bottom-right-radius: 0;
}
</style>
