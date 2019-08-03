<template>
  <div>
    <nav class="w-full mb-4 p-4 bg-gray-700 text-white">
      <router-link to="/" class="hover:text-blue-500">Home</router-link>
      <router-link to="/about" class="ml-4 hover:text-blue-500">About</router-link>
    </nav>

    <router-view></router-view>
  </div>
</template>
<script>
export default {};
</script>
