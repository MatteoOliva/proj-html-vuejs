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
      <div class="header-logo"><img src="../../images/logo.png" alt=""></div>
      <div class="nav">
        <ul>
          <li>Home</li>
          <li>Games <span><img src="../../images/svg/c-down-arrow.svg" alt=""></span></li>
          <li>Shop <span><img src="../../images/svg/c-down-arrow.svg" alt=""></span></li>
          <li>Pages <span><img src="../../images/svg/c-down-arrow.svg" alt=""></span></li>
          <li>Blog <span><img src="../../images/svg/c-down-arrow.svg" alt=""></span></li>
          <li>Contact <span><img src="../../images/svg/c-down-arrow.svg" alt=""></span></li>
        </ul>
      </div>
      <div class="header-action">
        <div class="chart"><img src="../../images/icon/cart-icon.png" alt="">
        <span class="chart-count">03</span>
        </div>
        <div class="header-btn"> <span id="header-btn">LIVE STREAMING</span></div>
      </div>

    </div>
  </header>
</template>

<style lang="scss" scoped>
@use "../styles/partials/variables.scss" as *;
@use '../styles/partials/mixins.scss' as *;

header {
  max-width: 100%;
  background-image: url(../../images/index-banner-bg.png);
  
  
  
  .nav ul li {
    display: inline-block;
    color: $text-color;
    margin-right: 15px;
  }

  ul li:first-child{
    color: $primary-color;
    
  }
  .header-top {
    @include spaceAround;
    padding-top: 40px
  }
  .header-action {
    @include center;
    .chart-count {
    border-radius: 50%;
    width: 20px;
    height: 20px;
    color: black;
    background-color: $button-color;
  }
  .header-btn {
    margin-left: 40px;
    width: 200px;
    height: 50px;
    border: 1px solid $button-color;
    border-radius: 20px;
    @include center;

  }
    #header-btn {
      border-radius: 20px;
      color: $secondary-color;
      background-color: $button-color;
      padding: 12.7px 28px;
    }
  }

  
  
}

</style>
