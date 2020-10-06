<template>
  <div class="rekening">
    <Navbar />
    <Jumbotron />
  </div>
</template>

<script>
// @ is an alias to /src
import Navbar from "@/components/sites/Navbar.vue";
import Jumbotron from "@/components/sites/Jumbotron.vue";

export default {
  name: "Rekening",
  components: {
    Navbar,
    Jumbotron,
  },
};
</script>
