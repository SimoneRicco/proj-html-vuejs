<script>
export default {};
</script>

<template>
  <section>
    <div class="text">
      <img src="../../edu/img/Books-icon.png" alt="" class="books" />
      <h2>Thousands of courses for any type of student</h2>
      <p>
        At EduPrime, it doesn't matter what domain you wish to pursue a career
        in. Here you an find a course that satisfies ypur needs within a click
        away and applies foor a course in a matter of minutes. EduPrime is
        ranked as the most versatile university in the world, thanks to the
        number of courses it provides.
        <button class="browse btn">Browse through courses</button>
      </p>
    </div>
    <div class="side-image">
      <img src="../../edu/img/Graduation-Illustration.png" alt="" />
    </div>
  </section>
</template>

<style lang="scss" scoped>
$yellow: #e9d758;
.browse {
  background-color: $yellow;
}
.btn {
  padding: 1rem;
  padding: 15px;
  border-radius: 50px;
  color: white;
  border: 0;
}
.books {
  width: 50px;
}
section {
  display: flex;
  justify-content: space-between;
  padding-inline: 10rem;
  background-image: url("../../edu/img/home-background.png");
  background-position: center;
}
.text {
  width: 50%;
}
.side-image {
  width: 50%;
  img {
    width: 500px;
  }
}
</style>
