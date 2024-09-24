<script>
export default {
  data() {
    return { 
      headerLinksOne: [
        {
          label: 'Home',
          url: '#'
        },
        {
          label: 'About Us',
          url: '#'
        },
        {
          label: 'Feature',
          url: '#'
        },
        {
          label: 'Testimonials',
          url: '#'
        },
        {
          label: 'Contact Us',
          url: '#'
        }
      ]
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
      <div class="header-top-right">
        <ul>
          <li v-for="(link, i) in headerLinksOne" :key="i">
            <a :href="link.url">
              {{ link.label }}
            </a>
          </li>
          <button type="submit" class="btn btn-primary">Get Started</button>
        </ul>
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
@mixin simple-ul {
  list-style: none;
}

header {
  text-align: center;
  padding: 20px 0;
  max-width: 1000px;
  margin: 0 auto;

    ul {
    @include simple-ul;
    display: flex;
    align-items: center;
    justify-content: center;
    
    li {
      a {
        display: inline-block;
        margin: 5px;
        padding: 10px;
        color: black;
        text-decoration: none;

        &:hover {
          color: rgb(26, 94, 242);
        }

      }
    }
  }
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
  background-color: $mainBgColor;
  display: flex;
}

</style>
