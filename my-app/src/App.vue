<script>
import Browse from "./components/Browse.vue";
import Events from "./components/Events.vue";
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
    Events,
  },
};
</script>

<template>
  <div class="container">
    <Header :options="headerOptions"></Header>
    <Browse></Browse>
    <Faculties></Faculties>
    <UniversityYear></UniversityYear>
    <Events></Events>
  </div>
</template>

<style></style>
