<script>
export default {
  data() {
    return { 
      message: 'Contact with our team',
      messagetwo: 'if you are planning on developing a prodcut landing'
    }
  }
}
</script>

<template>
  <footer>
    <div class="footer-top">
      <h1>
        {{ message }}
      </h1>
      <p>
        {{ messagetwo }}
      </p>
    </div>

    <div class="footer-center">
      <div class="left">
        <div class="footer-img">
          <img src="/img/StaticMapService.GetMapIma.png" alt="map">
        </div>
      </div>
      <div class="right-top">
        <div class="right-logo">
          <img src="/img/35.png" alt="logo">
        </div>
        <h3>9840 Shore St. Fond Du Lac, WI 54935</h3>
        <p>0 1223 456 789</p>
        <p>mail@softbox.com</p>
      </div>
      <div class="right-bottom">
        <h3>Get in Touch</h3>
        <form>
          <div class="mb-3">
            <label for="exampleInputEmail1" class="form-label">your name</label>
            <input type="email" class="form-control" id="exampleInputEmail1" aria-describedby="emailHelp">
          </div>
          <div class="mb-3">
            <label for="exampleInputEmail1" class="form-label">your email</label>
            <input type="email" class="form-control" id="exampleInputEmail1" aria-describedby="emailHelp">
          </div>
          <button type="submit" class="btn btn-primary">Send message</button>
        </form>
      </div>
    </div>

    <div class="footer-bottom">
      <div class="bottom-left">
        <div class="bottom-logo">
          <img src="/img/35.png" alt="logo">
          <p>It is a long established fact that a reader will be distracted by the readable content</p>
          <p>Copyright @2018 Softbox</p>
        </div>

        <div class="bottom-right">
          <nav>
            <ul>
              <h4>Menu</h4>
              <li>
                <a href="#">About Us</a>
              </li>
              <li>
                <a href="#">Theme</a>
              </li>
              <li>
                <a href="#">Features</a>
              </li>
              <li>
                <a href="#">Pricing</a>
              </li>
              <li>
                <a href="#">Blog</a>
              </li>
            </ul>

            <ul>
              <h4>About Us</h4>
              <li>
                <a href="#">About Us</a>
              </li>
              <li>
                <a href="#">Theme</a>
              </li>
              <li>
                <a href="#">Features</a>
              </li>
              <li>
                <a href="#">Pricing</a>
              </li>
              <li>
                <a href="#">Blog</a>
              </li>
            </ul>

            <ul>
              <h4>Quick Links</h4>
              <li>
                <a href="#">About Us</a>
              </li>
              <li>
                <a href="#">Theme</a>
              </li>
              <li>
                <a href="#">Features</a>
              </li>
              <li>
                <a href="#">Pricing</a>
              </li>
              <li>
                <a href="#">Blog</a>
              </li>
            </ul>
          </nav>
        </div>
      </div>

    </div>
  </footer>
</template>

<style lang="scss" scoped>
@use '../assets/scss/partials/variables' as *;


</style>
