<template>
  <div>
    <nuxt-link :to="{ name: 'index' }">
      <h1
        class="text-2xl font-semibold leading-6 transition ease-in-out duration-300 hover:bg-blue-100 py-2 pl-1 pr-5 inline-block"
      >
        ✍️ Awesome Blog
      </h1>
    </nuxt-link>
    <h2 class="text-xs text-gray-700 pl-1">The awesome description of my awesome blog</h2>
  </div>
</template>

<script>
export default {
  name: 'LayoutHeader',
}
</script>
