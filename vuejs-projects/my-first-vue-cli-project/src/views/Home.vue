<template>
  <div class="home">
    <HelloNuxt></HelloNuxt>
  </div>
</template>

<script>
// @ is an alias to /src
import HelloNuxt from "@/components/Hellonuxt.vue";
export default {
  name: "Home",
  components: {
    HelloNuxt
  }
};
</script>
