<template>
  <nav class="navigation-links-nav" v-bind:class="rootClassName">
    <nuxt-link to="/about" class="navigation-links-navlink">{{ text }}</nuxt-link>
    <nuxt-link to="/post" class="navigation-links-navlink1">
      {{ text1 }}
    </nuxt-link>
    <nuxt-link to="/contact" class="navigation-links-navlink2">
      {{ text4 }}
    </nuxt-link>
  </nav>
</template>

<script>
export default {
  name: 'NavigationLinks',
  props: {
    text2: {
      type: String,
      default: 'Pricing',
    },
    rootClassName: String,
    text4: {
      type: String,
      default: 'Contacto',
    },
    text3: {
      type: String,
      default: 'Team',
    },
    text1: {
      type: String,
      default: 'Artículo',
    },
    text: {
      type: String,
      default: 'Sobre nosotros',
    },
  },
}
</script>

<style scoped>
.navigation-links-nav {
  flex: 0 0 auto;
  display: flex;
  align-items: center;
  flex-direction: row;
}
.navigation-links-navlink {
  text-decoration: none;
}
.navigation-links-navlink1 {
  margin-left: var(--dl-space-space-twounits);
  text-decoration: none;
}
.navigation-links-navlink2 {
  margin-left: var(--dl-space-space-twounits);
  text-decoration: none;
}














@media(max-width: 767px) {
  .navigation-links-nav {
    align-items: flex-start;
    flex-direction: column;
  }
  .navigation-links-navlink {
    margin-bottom: var(--dl-space-space-unit);
  }
  .navigation-links-navlink1 {
    margin-left: 0;
    margin-bottom: var(--dl-space-space-unit);
  }
  .navigation-links-navlink2 {
    margin-left: 0;
    margin-bottom: var(--dl-space-space-unit);
  }
}
</style>
