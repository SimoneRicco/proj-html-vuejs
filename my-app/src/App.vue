<script>
import Browse from "./components/Browse.vue";
import Faculties from "./components/Faculties.vue";
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
    Faculties,
  },
};
</script>

<template>
  <div class="container">
    <Header :options="headerOptions"></Header>
    <Browse></Browse>
    <Faculties></Faculties>
  </div>
</template>

<style></style>
