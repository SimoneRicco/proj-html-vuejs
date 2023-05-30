<script>
export default {};
</script>

<template>
  <section>
    <div class="info">
      <h2>Subscribe now to our NewsLetter!</h2>
      <div class="input">
        <input type="text" placeholder="Email address..." />
        <div class="send">
          <font-awesome-icon icon="fa-solid fa-paper-plane" />
        </div>
      </div>
    </div>
  </section>
</template>

<style lang="scss" scoped>
$orange: #e56768;
$yellow: #e9d758;
section {
  background-color: $orange;
  color: white;
  .info {
    display: flex;
    align-items: center;
    justify-content: space-around;
    width: 1140px;
    margin: auto;
    padding: 2rem 0;
  }
  .input {
    display: flex;
    align-items: center;
    input {
      padding: 8px 16px;
    }
  }
  .send {
    background-color: $yellow;
    width: 50px;
    height: 50px;
    border-radius: 50%;
    display: flex;
    align-items: center;
    justify-content: center;
    margin-left: -10px;
  }
}
</style>
