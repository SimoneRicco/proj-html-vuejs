<script>
export default {};
</script>

<template>
  <footer>
    <div class="f-width">
      <div class="f-left">
        <div class="theme">
          <img src="../../edu/svg/svg-3.svg" alt="" />
          Purchase Themes
        </div>
        <div class="theme">
          <img src="../../edu/svg/svg-2.svg" alt="" />
          Related Themes
        </div>
      </div>
      <div class="f-center">
        <div class="edu-info">
          <img src="../../edu/img/theme_eduprime_logo.png" alt="" />
          <p>
            EduPrime is the most versatile WordPress The,e for educational
            purposes, showcasing universities, courses, secondary schools etc.
          </p>
          <div class="socials">
            <div class="social">
              <font-awesome-icon icon="fa-brands fa-facebook-f" />
            </div>
            <div class="social">
              <font-awesome-icon icon="fa-brands fa-twitter" />
            </div>
            <div class="social">
              <font-awesome-icon icon="fa-brands fa-instagram" />
            </div>
          </div>
        </div>
        <ul>
          <li><span class="title">Get EduPrime</span></li>
          <li>Request a website</li>
          <li>Browse Themes</li>
          <li>Payment options</li>
          <li>Support System</li>
          <li>Checkout</li>
          <li>Purchase Theme</li>
        </ul>
        <ul>
          <li><span class="title">Networking</span></li>
          <li>Purchase Theme</li>
          <li>Our Benefits</li>
          <li>Our Team</li>
          <li>Our Services</li>
          <li>Other Products</li>
          <li>My account</li>
        </ul>
        <div class="search">
          <div class="input">
            <input type="text" placeholder="Email address..." />
            <div class="send">
              <font-awesome-icon icon="fa-solid fa-paper-plane" />
            </div>
          </div>
          <h3>Search Categories</h3>
          <div class="cat-list">
            <div class="cat">Economy</div>
            <div class="cat">Design</div>
            <div class="cat">Coaching</div>
            <div class="cat">Business</div>
            <div class="cat">Medicine</div>
            <div class="cat">Law</div>
            <div class="cat">Fitness</div>
          </div>
          <p class="copyright">ModelTheme. All rights reserved.</p>
        </div>
      </div>
      <div class="f-right">
        <div class="top-arrow">
          <img src="../../edu/img/back-to-top-arrow.svg" alt="" />
        </div>
      </div>
    </div>
  </footer>
</template>

<style lang="scss" scoped>
$orange: #e56768;
$yellow: #e9d758;
footer {
  background-color: $orange;
  .f-width {
    width: 1140px;
    display: flex;
    margin: auto;
    padding: 5rem 0;
  }
  .edu-info {
    color: white;
    p {
      padding: 1rem 0;
    }
    img {
      width: 200px;
    }
  }
}
.theme {
  background-color: rgb(64, 64, 64);
  padding: 5px 10px;
  color: white;
  display: flex;
  gap: 5px;
  border-radius: 10px;
  box-shadow: 0 2px 5px black;
  img {
    width: 15px;
  }
}
.socials {
  display: flex;
  .social {
    width: 40px;
    height: 40px;
    border: 2px solid $yellow;
    border-radius: 50%;
    display: flex;
    align-items: center;
    justify-content: center;
  }
}
.f-center {
  display: flex;
  padding-inline: 4rem;
  ul {
    list-style: none;
    color: white;
    text-align: center;
    .title {
      font-weight: bold;
      font-size: 1.1rem;
    }
  }
}
.input {
  display: flex;
  align-items: center;
  justify-content: flex-end;
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
  color: white;
}
.search {
  color: white;
  text-align: right;
  h3 {
    text-align: right;
    margin: 1rem 0;
  }
}
.cat-list {
  display: flex;
  flex-wrap: wrap;
  gap: 10px;
  justify-content: flex-end;
  .cat {
    padding: 4px 8px;
    border: 1px solid white;
    border-radius: 50px;
  }
}
.edu-info,
ul,
.search {
  flex: 0 0 calc(100% / 4);
}
.copyright {
  color: $yellow;
  margin-top: 1rem;
}
.top-arrow {
  height: 50px;
  width: 50px;
  border-radius: 50%;
  background-color: $yellow;
  display: flex;
  align-items: center;
  justify-content: center;
}
.f-right {
  display: flex;
  align-items: flex-end;
}
.f-left {
  display: flex;
  justify-content: flex-end;
  flex-direction: column;
  gap: 1rem;
}
</style>
