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
            "Lorem, ipsum dolor sit amet consectetur adipisicing elit. Mollitia aut doloribus recusandae iusto voluptas est reprehenderit et sit, minima voluptatum facilis voluptatem maiores aliquam animi adipisci pariatur reiciendis iste eius?",
          imgPath: "../../edu/img/Economy.png",
        },
        {
          name: "Medicine",
          description:
            "Lorem ipsum dolor sit amet consectetur adipisicing elit. Iure laborum libero aliquid temporibus commodi, quam saepe culpa id perferendis laboriosam dolorem quod a tempore fuga eligendi eius dolorum blanditiis. Optio.",
          imgPath: "../../edu/img/Medicine.png",
        },
        {
          name: "Computer Science",
          description:
            "Lorem ipsum dolor sit amet consectetur adipisicing elit. Voluptatem iste velit magnam est nesciunt, placeat optio odio ullam atque quas ipsam ipsum excepturi expedita totam debitis eius quisquam nulla aliquam.",
          imgPath: "../../edu/img/Computer-Science.png",
        },
        {
          name: "Graphic Design",
          description:
            "Lorem ipsum dolor sit, amet consectetur adipisicing elit. Similique adipisci aut dolorem quia minus reiciendis officia quasi. Repellat et, dolorem doloribus nemo quasi dignissimos dolores rem placeat ullam provident quibusdam? Animi odit facere corrupti perspiciatis tempora. Quae in, porro a deleniti obcaecati esse blanditiis. Aliquid reprehenderit dolorem doloremque repellendus quia, necessitatibus ut neque excepturi illum aut iusto corrupti quo voluptatum!",
          imgPath: "../../edu/img/Graphic-Design.png",
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
      <span
        >A single university with a load of courses, tailored to satisfy any
        student's needs.
      </span>
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
      <div class="image">
        <img :src="facultiesList[activeIntex].imgPath" alt="" />
      </div>
      <div class="description-text">
        <h1>{{ facultiesList[activeIntex].name }}</h1>
        <p>{{ facultiesList[activeIntex].description }}</p>
        <button class="read-more-btn">Read more</button>
      </div>
    </div>
  </section>
</template>

<style lang="scss" scoped>
$orange: #e56768;
.text {
  text-align: center;
}
.read-more-btn {
  background-color: $orange;
  border: 0;
  padding: 1rem 2rem;
  border-radius: 50px;
  color: white;
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
.description {
  display: flex;
  justify-content: center;
}
.description-text {
  width: 400px;
}
</style>
