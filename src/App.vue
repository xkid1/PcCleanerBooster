<template>
  <div id="app">
     <!-- Navigation -->
  <nav class="navbar navbar-expand-lg navbar-light fixed-top py-3" id="mainNav">
    <div class="container">
      <a class="navbar-brand js-scroll-trigger" href="#page-top"><img class="logo" src="./assets/images/SafeSoft.png" alt="" srcset=""></a>
      <button class="navbar-toggler navbar-toggler-right" type="button" data-toggle="collapse" data-target="#navbarResponsive" aria-controls="navbarResponsive" aria-expanded="false" aria-label="Toggle navigation">
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse" id="navbarResponsive">
        <ul class="navbar-nav ml-auto my-2 my-lg-0">
          <li class="nav-item">
            <a class="nav-link js-scroll-trigger" href="#about">About</a>
          </li>
          <li class="nav-item">
            <a class="nav-link js-scroll-trigger" href="#services">Services</a>
          </li>
          <li class="nav-item">
            <a class="nav-link js-scroll-trigger" href="#portfolio">Portfolio</a>
          </li>
          <li class="nav-item">
            <a class="nav-link js-scroll-trigger" href="#contact">Contact</a>
          </li>
        </ul>
      </div>
    </div>
  </nav>

  <!-- Masthead -->
  <header class="masthead">
    <div class="container h-100">
      <div class="row h-100 align-items-center justify-content-center text-center">
        <div class="col-lg-10 align-self-end">
          <h1 class="text-uppercase text-white font-weight-bold">Your headline here</h1>
          <hr class="divider my-4 ">
        </div>
        <div class="col-lg-8 align-self-baseline">
          <p class="text-white font-weight-light mb-5">Lorem, ipsum dolor sit amet consectetur adipisicing elit. Repellat distinctio, maiores eligendi nemo placeat libero officia. Officiis aperiam ea labore voluptatum vel error et reiciendis soluta accusantium? Quos illum quidem et debitis error assumenda minima consectetur.</p>
          <a class="btn btn-primary btn-xl js-scroll-trigger" href="#about">Free Download</a>
        </div>
      </div>
    </div>
  </header>

  <!-- slider -->
    <section>
      <slider />
    </section>

    <!-- footer -->
    <section>
       <Footer></Footer>
    </section>
    
  </div>
</template>

<script>
  import slider from './components/Slider'
  import Footer from './components/Footer'
 

export default {
  components: {
    slider,
    Footer
  },
  mounted() {
    console.log('ready');

  }
}
</script>

<style>
  @import './assets/style/style.css';
</style>