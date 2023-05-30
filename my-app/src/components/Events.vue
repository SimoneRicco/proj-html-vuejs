<script>
export default {};
</script>

<template>
  <section>
    <div class="color">
      <div class="title">
        <img src="../../edu/img/upcoming-events-calendar-icon.png" alt="" />
        <h2>Upcoming Events</h2>
      </div>
      <div class="all-sessions">
        <div class="session">
          <h3>Coaching Session</h3>
          <div class="date">
            <font-awesome-icon icon="fa-regular fa-calendar-days" />20 May 21:30
            PM
          </div>
          <div class="text">
            Lorem ipsum dolor, sit amet consectetur adipisicing elit. Amet, nam
            incidunt praesentium rerum facere nobis asperiores porro iusto
            impedit esse recusandae soluta? Repudiandae aliquid perferendis
            ducimus delectus nisi enim earum?
          </div>
          <button class="find-more">
            <font-awesome-icon icon="fa-solid fa-plus" />Find More
          </button>
        </div>
        <div class="session">
          <h3>Coaching Session</h3>
          <div class="date">
            <font-awesome-icon icon="fa-regular fa-calendar-days" />24 Mar 18:00
            PM
          </div>
          <div class="text">
            Lorem ipsum dolor, sit amet consectetur adipisicing elit. Amet, nam
            incidunt praesentium rerum facere nobis asperiores porro iusto
            impedit esse recusandae soluta? Repudiandae aliquid perferendis
            ducimus delectus nisi enim earum?
          </div>
          <button class="find-more">
            <font-awesome-icon icon="fa-solid fa-plus" />Find More
          </button>
        </div>
        <div class="session">
          <h3>Coaching Session</h3>
          <div class="date">
            <font-awesome-icon icon="fa-regular fa-calendar-days" />12 Feb 13:30
            PM
          </div>
          <div class="text">
            Lorem ipsum dolor, sit amet consectetur adipisicing elit. Amet, nam
            incidunt praesentium rerum facere nobis asperiores porro iusto
            impedit esse recusandae soluta? Repudiandae aliquid perferendis
            ducimus delectus nisi enim earum?
          </div>
          <button class="find-more">
            <font-awesome-icon icon="fa-solid fa-plus" />Find More
          </button>
        </div>
      </div>
      <button class="view-events">View all events</button>
    </div>
    <img src="../../edu/svg/svg-1.svg" alt="" class="bot-wave" />
  </section>
</template>

<style lang="scss" scoped>
$orange: #e56768;
$yellow: #e9d758;
section {
  color: white;
  text-align: center;
}
.color {
  padding-top: 3rem;
  background-color: $orange;
}
.title {
  img {
    width: 50px;
  }
}
.all-sessions {
  display: flex;
  justify-content: center;
  gap: 2rem;
  padding-top: 2rem;
  .session {
    background-color: white;
    width: 300px;
    padding: 1rem;
    border-radius: 15px;
    text-align: center;
    color: gray;
    margin-bottom: 5rem;
    position: relative;
    .text {
      height: 50px;
      overflow: hidden;
      text-overflow: ellipsis;
    }
    h3 {
      color: black;
    }
    .date {
      font-size: 0.7rem;
      padding: 0.5rem 0;
    }
    .find-more {
      background-color: $orange;
      border: 0;
      padding: 8px 16px;
      border-radius: 50px;
      color: white;
      position: absolute;
      box-shadow: 0 0 5px rgb(147, 38, 38);
      right: 50%;
      transform: translateX(50%);
    }
  }
}
.view-events {
  background-color: $yellow;
  border: 0;
  padding: 1rem;
  border-radius: 50px;
  color: white;
}
.bot-wave {
  width: 100%;
}
</style>
