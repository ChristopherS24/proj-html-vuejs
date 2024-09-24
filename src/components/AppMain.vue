<script>
export default {
  data() {
    return { 
      message: 'Online Marketing'
    }
  }
}
</script>

<template>
  <main>
    <div class="container-one">
      <div class="list-left">
        <div class="list-img">
          <img src="/img/24.png" alt="">
        </div>
        <h3>Online Marketing</h3>
        <p>It is a long established fact that a reader will be distracted by the readable</p>
        <nav class="main-links">
          <ul>
            <li>
              <a href="#">SEO</a>
            </li>
            <li>
              <a href="#">SEM</a>
            </li>
            <li>
              <a href="#">Website Strategy</a>
            </li>
            <li>
              <a href="#">Social management</a>
            </li>
          </ul>
        </nav>
      </div>
      <h1>
      {{ message }}
      </h1>
    </div>

      <div class="container-one">
        <h1>Get tips tricks on how to skyrocket yor sales.</h1>
        <p>Faff about only a quid blower i don't want no agro bleeding chimney pot burkw tosser cras nice one boot fanny.!</p>
      </div>
      <div class="container-two">
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
        <div class="main-img">
          <img src="/img/509.jpeg" alt="mainimg">
        </div>
      </div>

    <div class="main-three">
      <div class="container-popular">
        <div class="popular">
          <h1>Popular features that your business needs</h1>
          <p>Faff about only a quid blower i don't want no agro bleeding chimney pot burkw tosser cras nice one boot fanny.!</p>
        </div>
        <button>Explore More Feature</button>

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
  </main>
</template>

<style lang="scss" scoped>
@use '../assets/scss/partials/variables' as *;


main {
  max-width: 1000px;
  margin: 0 auto;
}

//main-two
.container-one {
  display: flex;
  flex-wrap: wrap;
  
}

.container-two {
  display: flex;
}

//main-three
.container-popular {
  display: flex;
}
  
//main-four
.main-four {
  background-color: skyblue;
  background-image: url(/img/15.png);
  
}




</style>
