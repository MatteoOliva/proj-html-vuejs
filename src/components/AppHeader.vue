<script>
export default {
  data() {
    return {};
  },
};
</script>

<template>
  <header>
    <div class="header-top">
      <img class="background-header" src="../../images/index-banner-bg.png" alt="">
      <div class="header-logo"><img src="../../images/logo.png" alt="" /></div>
      <div class="nav">
        <ul>
          <li>Home</li>
          <li class="dropdown">
            Games<img src="../../images/svg/c-down-arrow.svg" alt="" />
            <div class="dropdown-content">
              <a href="#">Games</a>
              <a href="#">Games Details</a>
              <a href="#">Match Details</a>
            </div>
          </li>
          <li>
            Shop
            <span><img src="../../images/svg/c-down-arrow.svg" alt="" /></span>
          </li>
          <li>
            Pages
            <span><img src="../../images/svg/c-down-arrow.svg" alt="" /></span>
          </li>
          <li>
            Blog
            <span><img src="../../images/svg/c-down-arrow.svg" alt="" /></span>
          </li>
          <li>
            Contact
            <span><img src="../../images/svg/c-down-arrow.svg" alt="" /></span>
          </li>
        </ul>
      </div>
      <div class="header-action">
        <div class="chart">
          <img src="../../images/icon/cart-icon.png" alt="" />
          <span class="chart-count">03</span>
        </div>
        <div class="header-btn">
          <a href="#livestreaming"><button id="header-btn">LIVE STREAMING</button></a>
        </div>
      </div>
    </div>
    <!-- future of Esports -->
    <div class="header-bottom">
      <div class="header-bot-left">
        <div class="futureofesports">
          <div><h4>Game with Live Streaming</h4></div>
          <div><h2>Future of Esports</h2></div>
          <div>
            <p>
              Lorem ipsum dolor sit amet consectetur adipisicing elit. Deserunt
              eligendi dolores vero adipisci quae dolorem natus
            </p>
          </div>
          <div class="headerbottom-btnsleft">
            <div class="headerbottom-btnleft">
              <span id="headerbottom-btnleft"
                >EXPLORE GAMES
                <img src="../../images/svg/e-double-right-arrow.svg" alt=""
              /></span>
            </div>
            <div class="play-icon">
              <div id="play-icon">
                <img src="../../images/icon/play-icon.png"/>
              </div>
            </div>
          </div>
        </div>

        <div class="img-left">
          <img src="../../images/game-controler.png" alt=""/>
        </div>
      </div>
      <div class="header-bot-right">

        <div class="img-right">
          <img src="../../images/index-banner-illus.png" alt=""/>

        </div>
      </div>
    </div>
    
  </header>
</template>

<style lang="scss" scoped>
@use "../styles/partials/variables.scss" as *;
@use "../styles/partials/mixins.scss" as *;

header {
  // background-image: url(../../images/index-banner-bg.png);
  // background-repeat: no-repeat;
  width: 100%;
  
  position: relative;
  .background-header {
    position:absolute;
    z-index: -1;
    width: 100%;
    height: 1700px;
  
  }

  .nav ul li {
    display: inline-block;
    text-decoration: none;
    color: $text-color;
    margin-right: 15px;
    &:hover {
      cursor: pointer;
      color: $primary-color;
    }
    img {
      &:hover {
        cursor: pointer;
      }
    }
  }
  .nav {
    z-index: 1;
  }
  

  ul li:first-child {
    color: $primary-color;
  }
  .header-top {
    @include spaceAround;
    margin-top: 40px;
  }
  .header-action {
    @include center;
    .chart {
      position: relative;
      &:hover {
        cursor: pointer;
      }
    }
    .chart-count {
      border-radius: 50%;
      width: 20px;
      height: 20px;
      color: black;
      background-color: $button-color;
      padding: 2px;
      position: absolute;
      left: 50%;
      bottom: 50%;
    }
  }
  .header-btn {
    margin-left: 40px;
    width: 200px;
    height: 50px;
    border: 1px solid $button-color;
    border-radius: 20px;
    @include center;
    z-index: 1;
  }
  #header-btn {
    width: 190px;
    height: 40px;
    border-radius: 20px;
    color: $secondary-color;
    background-color: $button-color;
    text-align: center;
    line-height: 40px;
    &:hover {
      cursor: pointer;
      background-color: $primary-color;
    }
  }
  .dropdown:hover .dropdown-content {
    display: flex;
    flex-direction: column;
    left: 37%;
  }

  .dropdown-content {
    position: absolute;
    padding: 10px;
    background-color: $secondary-color;
    display: none;
    a {
      color: $text-color;
      text-decoration: none;
      &:hover {
        color: $primary-color;
      }
    }
  }
  .header-bottom {
    display: flex;
    max-width: 100%;
    margin-top: -40px;
    height: 865px;
  }
  .header-bot-left {
    width: 50%;
    position: relative;
    @include center;
    margin-top: -220px;
  }

  .header-bot-right {
    width: 50%;
    img {
      width: 100%
    }
    
  }

  .futureofesports {
    @include center;
    flex-direction: column;
    max-width: 50%;
    margin-top: 100px;
    margin-left: 200px;

    h4 {
      
      color: $primary-color;
      margin-right: 90px;
    }
    h2 {
      
      color: $text-color;
      margin-top: 10px;
    }
    p {
      color: $underText-color;
      margin-top: 10px;
  
    }
  }
  .headerbottom-btnsleft {
    display: flex;
    align-items: center;
    width: 500px;
    margin-top: 25px;
  }

  .headerbottom-btnleft {
    width: 220px;
    height: 50px;
    border: 1px solid $button-color;
    border-radius: 20px;
    @include center;
    margin-left: 45px;
  }
  #headerbottom-btnleft {
    height: 40px;
    line-height: 40px;
    border-radius: 20px;
    color: $secondary-color;
    background-color: $button-color;
    z-index: 1;
    width: 200px;
    text-align: center;
    &:hover {
      cursor: pointer;
      background-color: $primary-color;
    }
  }
  .play-icon {
    margin-left: 20px;
    height: 60px;
    width: 60px;
    border-radius: 50%;
    border: 1px solid $primary-color;
    @include center;
  }
  #play-icon {
    height: 40px;
    width: 40px;
    background-color: $text-color;
    border-radius: 50%;
    @include center;
    &:hover{
      cursor: pointer;
    }
  }
  .img-left {
    position: absolute;
    left: 7%;
    top: 60%;
  }
}
</style>
