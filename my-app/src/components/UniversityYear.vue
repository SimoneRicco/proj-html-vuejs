<script>
export default {};
</script>

<template>
  <section>
    <img src="../../edu/svg/svg-0.svg" alt="" class="wave" />
    <div class="contents">
      <img src="../../edu/img/Clock-and-Bell.png" alt="" class="clock-n-bell" />
      <h1>University Years</h1>
      <div class="time-line-containe">
        <div class="top-items items">
          <div class="item">
            <h3>Demo Classes</h3>
            <p>
              In the first week, students try to accomodate with the teaching
              style and choose their oprional courses.
            </p>
          </div>
          <div class="item">
            <h3>Graduation Day</h3>
            <p>
              On the day of graduation, all students gather of the cerimony and
              then network and party among others.
            </p>
          </div>
        </div>
        <img src="../../edu/img/Timeline-Item.png" alt="" />
        <div class="bottom-items items">
          <div class="item">
            <h3>Orientation</h3>
            <p>
              First day of the university year, all students gather for the
              opening cerimony and then network with others
            </p>
          </div>
          <div class="item">
            <h3>Evaluation</h3>
            <p>
              At the end of a semester, students take a general evaluation test
              for every subject they're learning.
            </p>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>

<style lang="scss" scoped>
$orange: #e56768;
.contents {
  background-color: $orange;
  text-align: center;
  color: white;
}
.wave {
  display: block;
  width: 100%;
}
.clock-n-bell {
  width: 50px;
}
.items {
  display: flex;
  h3 {
    margin-bottom: 1rem;
  }
}
.time-line-containe {
  width: 1090px;
  margin: auto;
}
.bottom-items:last-child {
  margin-right: 200px;
}
.top-items:first-child {
  margin-left: 200px;
}
h1 {
  margin-bottom: 3rem;
}
.top-items {
  padding-bottom: 1rem;
}
.bottom-items {
  padding-top: 1rem;
}
</style>
