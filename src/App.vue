<template>
  <NavBar/>
  <router-view />
</template>

<script lang="ts">
import NavBar from "./views/Nav_bar.vue";

export default {
  components: {
    NavBar,
  },
  data() {
    return {
      currentTheme: "light",
      isDark: false,
    };
  },
};
</script>
