<script>
import Browse from "./components/Browse.vue";
import Faculties from "./components/Faculties.vue";
import Header from "./components/Header.vue";
import UniversityYear from "./components/UniversityYear.vue";
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
    UniversityYear,
  },
};
</script>

<template>
  <div class="container">
    <Header :options="headerOptions"></Header>
    <Browse></Browse>
    <Faculties></Faculties>
    <UniversityYear></UniversityYear>
  </div>
</template>

<style></style>
