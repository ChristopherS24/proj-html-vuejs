<script>
export default {
  data() {
    return { 
      message: 'sb-marketing'
    }
  }
}
</script>

<template>
  <header>
    <div class="header-top">
      <div class="header-logo">
        <img src="/img/logo-2.png" alt="logo">
      </div>
      <div class="header-right">
        <h2>
          {{ message }}
        </h2>
      </div>
    </div>


    <div class="header-bottom">
      <div class="header-bottom-left">
        <div class="jumbotron-left">
          <img src="/hover-button.png" alt="left">
        </div>
      </div>

      <div class="header-bottom-right">
        <div class="jumbotron-right">
          <img src="/img/27-1.png" alt="right">
        </div>
      </div>
    </div>

  </header>
</template>

<style lang="scss" scoped>
@use '../assets/scss/partials/variables' as *;

header {
  background-color: $mainBgColor;
  text-align: center;
  padding: 20px 0;
  max-width: 1100px;
  margin: 0 auto;
}

//header-top
.header-top {
  display: flex;
  justify-content: space-between;
}

.header-logo {
  width: 5%;
}

img {
  max-width: 100%;
}

//header-bottom

.header-bottom {
  display: flex;
}

</style>
