<script>
export default {
  data() {
    return { 
      footerLinksOne: [
        {
          label: 'About us',
          url: '#'
        },
        {
          label: 'Theme',
          url: '#'
        },
        {
          label: 'Features',
          url: '#'
        },
        {
          label: 'Pricing',
          url: '#'
        },
        {
          label: 'Blog',
          url: '#'
        }
      ],
      footerLinksTwo: [
        {
          label: 'About Sofbox',
          url: '#'
        },
        {
          label: 'Roadmap',
          url: '#'
        },
        {
          label: 'How it Work',
          url: '#'
        },
        {
          label: 'Team',
          url: '#'
        },
        {
          label: 'News',
          url: '#'
        }
      ]
    }
  }
}
</script>

<template>
  <footer>
    <div class="footer-top">
      <h1>
        Contact with our team
      </h1>
      <p>
        if you are planning on developing a product landing.
      </p>
    </div>

    <div class="footer-center">
      <div class="left">
        <div class="footer-img">
          <img src="/img/StaticMapService.GetMapIma.png" alt="map">
        </div>
      </div>

      <div class="right">
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
              <input type="name" class="form-control" id="exampleInputname" placeholder="Your Name">
            </div>
            <div class="mb-3">
              <input type="email" class="form-control" id="exampleInputEmail1" aria-describedby="emailHelp" placeholder="Your Email">
            </div>
            <div class="mb-3">
              <input type="name" class="form-control" id="exampleInputname" placeholder="Your Subject">
            </div>
            <button type="submit" class="btn btn-primary">Send message</button>
          </form>
        </div>
      </div>
    </div>

    <div class="footer-bottom">
      <div class="bottom-left">
        <div class="bottom-logo">
          <img src="/img/35.png" alt="logo">
          <p>It is a long established fact that a reader will be distracted by the readable content</p>
          <p>Copyright @2018 Softbox</p>
        </div>
      </div>

        <div class="bottom-right">

            <ul>
              <h4>Menu</h4>
              <li v-for="(link, i) in footerLinksOne" :key="i">
                <a :href="link.url">
                  {{ link.label }}
                </a>
              </li>
            </ul>

            <ul>
              <h4>About Us</h4>
              <li v-for="(link, i) in footerLinksTwo" :key="i">
                <a :href="link.url">
                  {{ link.label }}
                </a>
              </li>
            </ul>

            <ul>
              <h4>Quick Links</h4>
              <li v-for="(link, i) in footerLinksOne" :key="i">
                <a :href="link.url">
                  {{ link.label }}
                </a>
              </li>
            </ul>

        </div>
    </div>
  </footer>
</template>

<style lang="scss" scoped>
@use '../assets/scss/partials/variables' as *;

footer {
  max-width: 1000px;
  margin: 0 auto;
}


//footer-top
.footer-top {
  padding: 100px;
  background-color: whitesmoke;
}

//footer-center
.footer-center {
  padding: 100px;
  display: flex;
}


//footer-bottom
.footer-bottom {
  display: flex;
}

.footer-bottom .bottom-right {
  display: flex;
  justify-content: space-between;
  width: 100%;
}

.footer-bottom > div:first-child {
  width: calc(100% / 4 - 10px);
}

.footer-bottom .bottom-right ul  {
  width: calc(100% / 4 - 10px);
}


.bottom-logo {
  width: 250px;
}


footer ul {
  list-style: none;
}

footer ul li a {
  color: black;
  text-decoration: none;
}



</style>
