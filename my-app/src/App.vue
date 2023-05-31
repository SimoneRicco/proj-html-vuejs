<script>
import Browse from "./components/Browse.vue";
import Events from "./components/Events.vue";
import Faculties from "./components/Faculties.vue";
import GeneralInfo from "./components/GeneralInfo.vue";
import Header from "./components/Header.vue";
import Newsletter from "./components/Newsletter.vue";
import Partners from "./components/Partners.vue";
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
    GeneralInfo,
    Newsletter,
    Partners,
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
    <GeneralInfo></GeneralInfo>
    <Newsletter></Newsletter>
    <Partners></Partners>
  </div>
</template>

<style></style>
