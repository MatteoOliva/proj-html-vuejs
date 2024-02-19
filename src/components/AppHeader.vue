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
      <div class="header-logo"></div>
      <div class="nav">
        <ul>
          <li>Home</li>
          <li>Games <span><i class="fa-solid fa-chevron-down"></i></span></li>
          <li>Shop <span><i class="fa-solid fa-chevron-down"></i></span></li>
          <li>Pages <span><i class="fa-solid fa-chevron-down"></i></span></li>
          <li>Blog <span><i class="fa-solid fa-chevron-down"></i></span></li>
          <li>Contact <span><i class="fa-solid fa-chevron-down"></i></span></li>
        </ul>
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
  
  ul li {
    display: inline-block;
    color: $text-color;
    margin-right: 15px;
  }

  ul li:first-child{
    color: $primary-color;
    
  }
  
}

</style>
