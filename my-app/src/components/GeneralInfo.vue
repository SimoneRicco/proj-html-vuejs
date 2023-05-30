<script>
export default {};
</script>

<template>
  <section>
    <div class="latest-courses">
      <h2>Latest Courses</h2>
      <div class="cards">
        <div class="card">
          <div class="image">
            <img
              src="../../edu/img/Decisions-icon.png"
              alt=""
              class="top-icon"
            />
          </div>
          <h3 class="black">Make Better Decisions</h3>
          <div class="teacher">
            <font-awesome-icon icon="fa-solid fa-user" />Teacher:
            <span class="black">James Colins</span>
          </div>
          <div class="price">
            <font-awesome-icon icon="fa-solid fa-money-bill-1" />Price:
            <span class="black">$21.00</span>
          </div>
          <button class="v-course">
            <font-awesome-icon icon="fa-solid fa-eye" />View Course
          </button>
        </div>
        <div class="card">
          <div class="image">
            <img src="../../edu/img/Speaker-icon.png" alt="" class="top-icon" />
          </div>
          <h3 class="black">How to be a Speaker</h3>
          <div class="teacher">
            <font-awesome-icon icon="fa-solid fa-user" />Teacher:
            <span class="black">James Colins</span>
          </div>
          <div class="price">
            <font-awesome-icon icon="fa-solid fa-money-bill-1" />Price:
            <span class="black">Free</span>
          </div>
          <button class="v-course">
            <font-awesome-icon icon="fa-solid fa-eye" />View Course
          </button>
        </div>
        <div class="card">
          <div class="image">
            <img src="../../edu/img/Network-icon.png" alt="" class="top-icon" />
          </div>
          <h3 class="black">Network Introduction</h3>
          <div class="teacher">
            <font-awesome-icon icon="fa-solid fa-user" />Teacher:
            <span class="black">James Colins</span>
          </div>
          <div class="price">
            <font-awesome-icon icon="fa-solid fa-money-bill-1" />Price:
            <span class="black">Free</span>
          </div>
          <button class="v-course">
            <font-awesome-icon icon="fa-solid fa-eye" />View Course
          </button>
        </div>
        <div class="card">
          <div class="image">
            <img src="../../edu/img/Brand-icon.png" alt="" class="top-icon" />
          </div>
          <h3 class="black">Brand Management</h3>
          <div class="teacher">
            <font-awesome-icon icon="fa-solid fa-user" />Teacher:
            <span class="black">James Colins</span>
          </div>
          <div class="price">
            <font-awesome-icon icon="fa-solid fa-money-bill-1" />Price:
            <span class="black">Free</span>
          </div>
          <button class="v-course">
            <font-awesome-icon icon="fa-solid fa-eye" />View Course
          </button>
        </div>
      </div>
    </div>
    <div class="row">
      <div class="description">
        <img src="../../edu/img/Exam-icon.png" alt="" class="row-icon" />
        <h2>The most efficient examination method</h2>
        <p>
          EduPrime has gathered teachers from around the globe to brainstorm in
          order to facilitate the evaluation of our students. Every teacher from
          our university has an influence on how students are evaluated at
          his/her subject
        </p>
        <button class="btn">Descover the Method</button>
      </div>
      <div class="side-img">
        <img src="../../edu/img/Exam-Illustration.png" alt="" />
      </div>
    </div>
    <div class="row reverse">
      <div class="description">
        <img src="../../edu/img/Exam-icon-1.png" alt="" class="row-icon" />
        <h2>Variable fees for international students</h2>
        <p>
          EduPrime has gathered teachers from around the globe to brainstorm in
          order to facilitate the evaluation of our students. Every teacher from
          our university has an influence on how students are evaluated at
          his/her subject
        </p>
        <button class="btn">Descover the Method</button>
      </div>
      <div class="side-img">
        <img src="../../edu/img/Girl-Illustration.png" alt="" />
      </div>
    </div>
  </section>
</template>

<style lang="scss" scoped>
$orange: #e56768;
section {
  width: 1140px;
  margin: auto;
}
.top-icon {
  width: 50px;
}
.image {
  text-align: center;
}
.cards {
  display: flex;
  justify-content: space-around;
  .card {
    box-shadow: 0 0 5px rgb(199, 199, 199);
    color: grey;
    padding: 1rem 0.5rem;
    position: relative;
    .v-course {
      background-color: $orange;
      border: 0;
      padding: 4px 8px;
      border-radius: 50px;
      color: white;
      position: absolute;
      bottom: 0;
      transform: translate(35%, 50%);
    }
  }
  .black {
    color: black;
  }
}
.row {
  margin-top: 5rem;
  display: flex;
  h2 {
    margin: 1rem 0;
  }
  .row-icon {
    width: 50px;
  }
  .description {
    width: 50%;
  }
  .side-img {
    width: 50%;
    img {
      width: 100%;
    }
  }
  .btn {
    background-color: $orange;
    padding: 1rem;
    color: white;
    border: 0;
    border-radius: 50px;
    margin-top: 3rem;
  }
}
.reverse {
  flex-direction: row-reverse;
}
</style>
