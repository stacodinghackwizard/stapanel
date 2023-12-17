<template>
    <div>
      <section class="">

        <header class="container p-3">
          <div >
            <div class="d-flex flex-wrap align-items-center justify-content-center justify-content-lg-start">
              <a href="/" class="d-flex align-items-center mb-2 mb-lg-0 header-title text-decoration-none" style="padding-right: 25px;">
                <!-- <svg class="bi me-2" width="40" height="32" role="img" aria-label="Bootstrap"><use xlink:href="#bootstrap"/></svg> -->
                stapanel
              </a>

              <ul class="nav col-12 col-lg-auto me-lg-auto mb-2 header-menu justify-content-center mb-md-0">
                <li><a href="#" class="nav-link px-2">Products</a></li>
                <li><a href="#" class="nav-link px-2">Solutions</a></li>
                <li><a href="#" class="nav-link px-2">Services</a></li>
                <li><a href="#" class="nav-link px-2">Configure</a></li>
                
              </ul>

          

              <div class="text-end">
                <button type="button" class="btn btn-transparent me-2"><img src="/headset.svg"/><span class="headset-text">+234 8147635160</span></button>
                <button type="button" class="btn header-border"><span>Request a Quote</span> <img src="/public/arrow-right.svg" class="pl-1"/></button>
              </div>
            </div>
          </div>
        </header>
        <div class="container col-xxl-8 px-4 py-5">
          
          <div class="row flex-lg-row-reverse align-items-center g-5">

            <div class=" col-12 col-sm-12 col-lg-6" style="position: relative;">
              <svg xmlns="http://www.w3.org/2000/svg" width="149" class="eclipse" height="149" viewBox="0 0 149 149" fill="none">
                <circle cx="74.5" cy="74.5" r="74.5" fill="#F59E0B"/>
              </svg>
              
              <img src="/heroImg.jpeg" class="heroImg" alt="Bootstrap Themes"  loading="lazy">
              <!-- <div class="angle">

                <svg xmlns="http://www.w3.org/2000/svg" width="408" height="248" viewBox="0 0 408 248" fill="none">
                  <path d="M0.351318 239.671C2.78171 193.604 17.7609 149.079 43.6687 110.911C69.5765 72.7422 105.427 42.3838 147.342 23.1187C189.257 3.85363 235.642 -3.58475 281.48 1.60803C327.317 6.80085 370.862 24.4272 407.406 52.5806L321.616 163.937C305.376 151.426 286.025 143.593 265.656 141.285C245.286 138.978 224.674 142.283 206.047 150.844C187.421 159.405 171.489 172.896 159.976 189.858C148.463 206.819 141.807 226.605 140.727 247.077L0.351318 239.671Z" fill="#7DD3FC"/>
                </svg>
              </div> -->
            </div>
            <div class="col-lg-6">
              <h1 class="display-5 fw-bold text-body-emphasis  lh-1 mb-3">Get the Sun to <br/> Power Your Home</h1>
              <p class="lead">Quickly design and customize responsive mobile-first sites with Bootstrap, the world’s most popular front-end open</p>
              <div class="d-grid gap-2 d-md-flex justify-content-md-start">
                <button type="button" class="btn header-border"><span class="">Request a Quote</span> <img src="/public/arrow-right.svg" class="pl-1"/></button>
              </div>
            </div>
          </div>
          <div class="col-lg-6">
            <p class="lead">Quickly design and customize responsive mobile-first sites with Bootstrap, the world’s most popular front-end open</p>
              <div class="text-start" style="display: flex; align-items: center; gap: 16px; width: 600px;">
                <a href="#" class="d-block link-body-emphasis text-decoration-none"  >
                  <img src="https://github.com/mdo.png" alt="mdo" width="32" height="32" class="rounded-circle">
                </a>
                <div style="display: flex; flex-direction: column; gap: 0; width: 600px;">
                  <p class="p-0 m-0" style="font-size: 14px;font-weight: 400;">Sulaimon Taofeek</p>
                  <p class="p-0 m-0">sta.com</p>
                </div>
              </div>
               
            </div>
        </div>
      </section>
      
        <PickTheSun/>
      
    </div>
</template>
<script setup>
import PickTheSun from './pick-the-sun.vue'
</script>