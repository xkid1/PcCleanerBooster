<template>
  <div id="app">
     <!-- Navigation -->
  <nav class="navbar navbar-expand-lg navbar-light  py-3" id="mainNav">
    <div class="container">
      <a class="navbar-brand js-scroll-trigger" href="#page-top">Your logo here </a>
      <button class="navbar-toggler navbar-toggler-right" type="button" data-toggle="collapse" data-target="#navbarResponsive" aria-controls="navbarResponsive" aria-expanded="false" aria-label="Toggle navigation">
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse" id="navbarResponsive">
        <ul class="navbar-nav ml-auto my-4 my-lg-0">
          <li class="nav-item ">
            <a class="nav-link js-scroll-trigger" href="#about"> About </a>
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
      <div class="row h-100 align-items-center justify-content-center">
        <div class="col-lg-12 align-self-end mb-3">
          <h1 class="text-uppercase text-dark font-weight-bold"> PC Cleaner Booster 8</h1>
          <h2>Enjoy a Faster and More Secure Mac</h2>
        </div>
        <div class="col-lg-12 align-self-baseline">
          <p class="text-white-75 font-weight-light mb-5">Your one-stop Mac maintenance tool to clean up 20 types of junk files and remove Mac malware and virus to protect your Mac, Besides, MacBooster can optimize Mac hard disk to boost your Mac to the peak performance.</p>
          <a class="btn btn-primary btn-xl js-scroll-trigger" href="#about">Buy Now</a>
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
  }
}
</script>

<style>
  @import './assets/style/style.css';
</style>