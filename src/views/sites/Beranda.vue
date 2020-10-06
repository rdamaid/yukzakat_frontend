<template>
  <div class="beranda">
    <Navbar />
    <Jumbotron />
  </div>
</template>

<script>
import Navbar from "@/components/sites/Navbar.vue";
import Jumbotron from "@/components/sites/Jumbotron.vue";

export default {
  name: "Beranda",
  components: {
    Navbar,
    Jumbotron,
  },
};
</script>
