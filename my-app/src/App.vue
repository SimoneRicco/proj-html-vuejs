<script>
import Browse from "./components/Browse.vue";
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
    Browse,
  },
};
</script>

<template>
  <div class="container">
    <Header :options="headerOptions"></Header>
    <Browse></Browse>
  </div>
</template>

<style></style>
