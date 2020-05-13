<template>
  <main class="m-3">
    <header>
      <nav>
        <inertia-link class="mr-3" href="/">Home</inertia-link>
        <inertia-link href="/about">About</inertia-link>
      </nav>
    </header>
    <content>
      <slot />
    </content>
    <footer></footer>
  </main>
</template>

<script>
export default {
  name: "layout"
};
</script>