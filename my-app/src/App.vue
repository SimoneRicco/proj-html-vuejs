<script>
import Header from "./components/Header.vue";
export default {
  data() {
    return {
      headerOptions: [
        "Home",
        "Courses",
        "About Us",
        "News",
        "Pages",
        "Contact",
        "Purchase",
      ],
    };
  },
  components: {
    Header,
  },
};
</script>

<template>
  <div class="container">
    <Header :options="headerOptions"></Header>
  </div>
</template>

<style></style>
