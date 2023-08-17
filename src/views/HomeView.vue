<template>
  <div class="flex min-h-full">
    <div class="flex w-full flex-col">
      <Navbar />
      <HeroComponent />
      <Footbar />
    </div>
  </div>
</template>

<script>
import Navbar from '@/components/Nav.vue'
import Footbar from '@/components/Foot.vue'
import HeroComponent from '@/components/Hero.vue'

export default {
  name: "HomeView",

  components: {
    Navbar,
    Footbar,
    HeroComponent,
  },
};
</script>
