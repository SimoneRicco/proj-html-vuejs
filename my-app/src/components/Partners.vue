<script>
export default {};
</script>

<template>
  <section>
    <div class="contents">
      <h2>Partners</h2>
      <p>
        Leverage agile frameworks to provide a robust synopsis for high level
        overviews. Iterative approaches to corporate strategy
      </p>
      <div class="partner-list">
        <img src="../../edu/img/partner-2.png" alt="" />
        <img src="../../edu/img/partner-3.png" alt="" />
        <img src="../../edu/img/partner-4.png" alt="" />
        <img src="../../edu/img/partner-5.png" alt="" />
        <img src="../../edu/img/partner-6.png" alt="" />
        <img src="../../edu/img/partner-7.png" alt="" />
        <img src="../../edu/img/partner-1.png" alt="" />
        <img src="../../edu/img/partner-8.png" alt="" />
      </div>
    </div>
    <img src="../../edu/img/background-wave3.png" alt="" class="wave" />
  </section>
</template>

<style lang="scss" scoped>
.wave {
  background-color: rgb(242, 242, 242);
  width: 70%;
  display: block;
  margin-left: auto;
  height: 100px;
}
.contents {
  width: 1140px;
  margin: auto;
  text-align: center;
  padding-top: 3rem;
}
section {
  p {
    width: 400px;
    margin: auto;
    padding: 1rem 0;
  }
  .partner-list {
    display: flex;
    width: 100%;
    align-items: center;
    justify-content: center;
    img {
      width: 100px;
      opacity: 0.4;
    }
  }
}
</style>
