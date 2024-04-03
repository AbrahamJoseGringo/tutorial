<script setup>
  import LargeHeader from '@/components/templetes/large/LargeHeader.vue';
  import LargeAside from '@/components/templetes/large/LargeAside.vue';
  import LargeFooter from '@/components/templetes/large/LargeFooter.vue';
</script>
<template>
  <div id="layout-large">
    <header>
      <large-header />
    </header>
    <aside>
      <large-aside />
    </aside>
    <main>
      <router-view />
    </main>
    <footer>
      <large-footer />
    </footer>
  </div>
</template>