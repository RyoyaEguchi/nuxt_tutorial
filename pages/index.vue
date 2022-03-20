<template>
  <div>
    <h1>Hello world!</h1>
    <NuxtLink to="/">Home</NuxtLink>
    <NuxtLink to="/menu">Menu</NuxtLink>
    <NuxtLink to="/parent">Parent</NuxtLink>
  </div>
</template>

<style lang="scss" scope>
a.nuxt-link-active {
  font-weight: bold;
}
/* exact link will show the primary color for only the exact matching link */
a.nuxt-link-exact-active {
  color: #00c58e;
}
</style>
