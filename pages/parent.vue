<template>
  <div>
    <h1>parent</h1>
    <NuxtLink to="/">Home</NuxtLink>
    <NuxtLink to="/menu">Menu</NuxtLink>
    <NuxtLink to="/parent">Parent</NuxtLink>
    <NuxtLink to="/1parent/child">child</NuxtLink>
    <NuxtLink to="/1parent/child2">child 2</NuxtLink>
    <NuxtChild />
  </div>
</template>