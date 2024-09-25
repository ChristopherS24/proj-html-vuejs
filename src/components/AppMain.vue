<script>
export default {
  data() {
    return { 
      MainLinks: [
        {
          label: 'SEO',
          url: '#'
        },
        {
          label: 'SEM',
          url: '#'
        },
        {
          label: 'Web Strategy',
          url: '#'
        },
        {
          label: 'Social Management',
          url: '#'
        }
      ]
    }
  }
}
</script>

<template>
  <main>
    <div class="main-one">

      <div class="list-left">
        <div class="list-img">
          <img src="/img/24.png" alt="">
        </div>
        <h3>Online Marketing</h3>
        <p>It is a long established fact that a reader will be distracted by the readable</p>
        <nav class="main-links">
          <ul>
              <h4>Menu</h4>
              <li v-for="(link, i) in MainLinks" :key="i">
                <a :href="link.url">
                  {{ link.label }}
                </a>
              </li>
            </ul>
        </nav>

        <div class="list-center">
        <div class="list-img">
          <img src="/img/24.png" alt="">
        </div>
        <h3>Online Marketing</h3>
        <p>It is a long established fact that a reader will be distracted by the readable</p>
        <nav class="main-links">
          <ul>
              <h4>Menu</h4>
              <li v-for="(link, i) in MainLinks" :key="i">
                <a :href="link.url">
                  {{ link.label }}
                </a>
              </li>
            </ul>
        </nav>
      </div>

      <div class="list-right">
        <div class="list-img">
          <img src="/img/24.png" alt="">
        </div>
        <h3>Online Marketing</h3>
        <p>It is a long established fact that a reader will be distracted by the readable</p>
        <nav class="main-links">
          <ul>
              <h4>Menu</h4>
              <li v-for="(link, i) in MainLinks" :key="i">
                <a :href="link.url">
                  {{ link.label }}
                </a>
              </li>
            </ul>
        </nav>
      </div>

    </div>
  </div>
    <div class="main-two">
      <div class="prova">
      <div class="container-left-top">
        <h1>Get tips tricks on how to skyrocket yor sales.</h1>
        <p>Faff about only a quid blower i don't want no agro bleeding chimney pot burkw tosser cras nice one boot fanny.!</p>
      </div>
      <div class="container-left-bottom">
        <div class="info-top">
          <img src="/img/510.png" alt="analysis">
          <h3>Reporting Analysis</h3>
          <p>It is a long established fact that a reader will be distracted by the readable content of a page when looking at its layout.</p>
        </div>
        <div class="info-bottom">
          <img src="/img/511.png" alt="Tech">
          <h3>Technical SEO Audit</h3>
          <p>It is a a long established fact that a reader will be distracted by the readable content of a page when looking at its layout.</p>
        </div>
      </div>
      </div>

      <div class="main-img">
          <img src="/img/509.jpeg" alt="mainimg">
        </div>
    </div>

    <div class="main-three">
      <div class="container-popular">
        <div class="popular">
          <h1>Popular features that your business needs</h1>
          <p>Faff about only a quid blower i don't want no agro bleeding chimney pot burkw tosser cras nice one boot fanny.!</p>
          <button type="submit" class="btn btn-primary">Explore more features</button>
        </div>
      </div>

      <div class="main-box">
          BOX
        </div>
    </div>

    <div class="main-four">
      <div class="info-testimonials">
        <h2>Our Testimonials</h2>
        <p>Faff about only a quid blower i don't want no agro bleeding chimney pot burkw tosser cras nice one boot fanny.!</p>
      </div>
      <div class="card-testimonial">

      </div>
    </div>

    <div class="main-five">
      <div class="posts">
        <div class="latest">
          <h2>Latest Posts</h2>
          <p>If you are planning on developing a product landing.</p>
        </div>
        <div class="posts-img">
          <div class="img-left">
            <img src="/img/19.jpg" alt="">
            <h3>Life Lack Meaning</h3>
            <p>It is a long established fact that a reader will be distracted by the readable</p>
          </div>
          <div class="img-center">
            <img src="/img/18.jpg" alt="">
            <h3>Life Lack Meaning</h3>
            <p>It is a long established fact that a reader will be distracted by the readable</p>
          </div>
          <div class="img-right">
            <img src="/img/20.jpg" alt="">
            <h3>Life Lack Meaning</h3>
            <p>It is a long established fact that a reader will be distracted by the readable</p>
          </div>
        </div>
      </div>
    </div>

  </main>
</template>

<style lang="scss" scoped>
@use '../assets/scss/partials/variables' as *;
@mixin simple-ul {
  list-style: none;
}

//general
main {
  max-width: 1000px;
  margin: 0 auto;

  ul {
    @include simple-ul;
  }
}


//main-one

//main-two
.main-two {
padding: 100px;
display: flex;
}



//main-three
.main-three {
  padding: 100px;
  background-image: url(/img/14.png);
}

.container-popular {
  padding: 50px;
  display: flex;
}
  
//main-four
.main-four {
  background-color: skyblue;
  background-image: url(/img/15.png);
  padding: 100px;
}

//main-five




</style>
