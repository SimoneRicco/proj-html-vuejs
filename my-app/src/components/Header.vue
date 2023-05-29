<script>
export default {
  props: {
    options: Array,
  },
};
</script>

<template>
  <div class="container">
    <div class="bg-img">
      <header>
        <img src="../../edu/img/theme_eduprime_logo.png" alt="" />
        <nav>
          <ul>
            <li v-for="(item, i) in options" :key="i">
              {{ item }}
              <font-awesome-icon
                icon="fa-solid fa-sort-down"
                class="arrow-down"
              />
            </li>
            <li>
              <button class="course-btn btn bg-yellow">View Course</button>
            </li>
          </ul>
        </nav>
      </header>
      <div class="jumbo">
        <div class="text">
          <h1>Key to your success</h1>
          <p>
            EduPrime is the most versatile WordPress theme for educational
            purposes showcasing universities, courses, secondary schools etc.
          </p>
        </div>
        <div class="buttons">
          <button class="search-course btn bg-yellow">
            <font-awesome-icon
              icon="fa-solid fa-magnifying-glass"
              class="btn-icons"
            />Search course
          </button>
          <button class="btn apply-university">
            <font-awesome-icon
              icon="fa-solid fa-user-plus"
              class="btn-icons"
            />Apply for university
          </button>
        </div>
      </div>
      <img src="../../edu/img/Wave-1.png" alt="" class="wave" />
    </div>
  </div>
</template>

<style lang="scss" scoped>
$orange: #e56768;
$yellow: #e9d758;
.wave {
  display: block;
}
.bg-orange {
  background-color: $orange;
}
.bg-yellow {
  background-color: $yellow;
}
.btn-icons {
  margin-right: 7px;
}
.container {
  background-image: url("../../edu/img/theme_slider2_bg-1.jpg");
}
.btn {
  padding: 1rem;
  padding: 15px;
  border-radius: 50px;
  color: white;
  border: 0;
}
.bg-img {
  background-color: rgba($color: $orange, $alpha: 0.9);
}
header {
  padding-inline: 15px;
  display: flex;
  align-items: center;
  color: white;
  img {
    width: 250px;
  }
  nav {
    margin-left: auto;
    ul {
      list-style: none;
      display: flex;
      align-items: center;
      gap: 1rem;
    }
    li:first-child {
      color: $yellow;
    }
    .arrow-down {
      font-size: 0.7rem;
      vertical-align: inherit;
    }
  }
}
.jumbo {
  color: white;
  padding: 6rem 0 4rem 0;

  .text {
    width: 720px;
    margin: auto;
    text-align: center;
  }
  .buttons {
    text-align: center;
    margin-top: 2rem;
    .apply-university {
      color: $orange;
    }
  }
}
</style>
