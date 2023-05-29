<script>
export default {
  data() {
    return {
      paths: [
        "../../edu/img/Gavel-v2.png",
        "../../edu/img/Coins-tabs-v2.png",
        "../../edu/img/Medicine-tabs-v2.png",
        "../../edu/img/Computer-tabs-v2.png",
        "../../edu/img/Palette-tabs-v2.png",
      ],
      facultiesList: [
        {
          name: "Law Faculty",
          description:
            "Learning from world-leading academics and practitioners, you'll not only recieve an outstanding grounding in the theory of law, but you will be able to understand how those principles are applied in practice through a range of student-led activities and competitionist",
          imgPath: "../../edu/img/Gavel-Illustration-e1556884768193.png",
        },
        {
          name: "Economy",
          description:
            "Learning from world-leading academics and practitioners, you'll not only recieve an outstanding grounding in the theory of law, but you will be able to understand how those principles are applied in practice through a range of student-led activities and competitionist",
          imgPath: "../../edu/img/Gavel-Illustration-e1556884768193.png",
        },
        {
          name: "Medicine",
          description:
            "Learning from world-leading academics and practitioners, you'll not only recieve an outstanding grounding in the theory of law, but you will be able to understand how those principles are applied in practice through a range of student-led activities and competitionist",
          imgPath: "../../edu/img/Gavel-Illustration-e1556884768193.png",
        },
        {
          name: "Computer Science",
          description:
            "Learning from world-leading academics and practitioners, you'll not only recieve an outstanding grounding in the theory of law, but you will be able to understand how those principles are applied in practice through a range of student-led activities and competitionist",
          imgPath: "../../edu/img/Gavel-Illustration-e1556884768193.png",
        },
        {
          name: "Graphic Design",
          description:
            "Learning from world-leading academics and practitioners, you'll not only recieve an outstanding grounding in the theory of law, but you will be able to understand how those principles are applied in practice through a range of student-led activities and competitionist",
          imgPath: "../../edu/img/Gavel-Illustration-e1556884768193.png",
        },
      ],
      activeIntex: 0,
    };
  },
  methods: {
    active(i) {
      this.activeIntex = i;
    },
  },
};
</script>

<template>
  <section>
    <div class="text">
      <h2>Faculties</h2>
      <img src="../../edu/img/Gavel-Illustration-e1556884768193.png" alt="" />
      <span
        >A single university with a load of courses, tailored to satisfy any
        student's needs.</span
      >
    </div>
    <div class="faculties-row">
      <div
        class="fac"
        v-for="(item, i) in paths"
        :key="i"
        :class="activeIntex == i ? 'active' : ''"
        @click="active(i)"
      >
        <img :src="item" alt="" />
      </div>
    </div>
    <div class="description">
      <h1>{{ facultiesList[activeIntex].name }}</h1>
    </div>
  </section>
</template>

<style lang="scss" scoped>
$orange: #e56768;
.text {
  text-align: center;
}
.active {
  background-color: $orange;
  img {
    filter: brightness(0) invert(1);
  }
}
.faculties-row {
  width: 100%;
  display: flex;
  justify-content: center;
  box-shadow: 0 0 5px rgb(232, 232, 232);
  margin-bottom: 3rem;
  .fac {
    width: 200px;
    height: 200px;
    border: 1px solid rgb(230, 230, 230);
    display: flex;
    align-items: center;
    justify-content: center;
    img {
      width: 50%;
    }
  }
}
</style>
