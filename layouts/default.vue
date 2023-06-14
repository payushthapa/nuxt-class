<template>
    <div>
        <nuxt-link to="/home">Home</nuxt-link>
        <nuxt-link to="/about">About Us</nuxt-link>
        <nuxt-link to="/contact">Contact us</nuxt-link>
        <nuxt-link to="/services">service</nuxt-link>
        <main>
            <slot></slot>
        </main>

        <footer>
      <section>
        <div class="container">
          <div class="row">
            <div class="col-md-3">
            <img src="https://codeit.com.np/images/1642171339codeIT%20logo.png" alt="" height="60px">
            <p>9862130505, 025-525163</p>
            <p>info@codeit.com.np</p>
            <p>Prithvi Path,Dharan</p>
            </div>
            <div class="col-md-3">
              <h1>Quick link</h1>
              <p>About Us</p>
             <p>Contact Us</p>
             <p>Gallery</p> 
             <p>Blog</p>
            </div>
          </div>
        </div>
      </section> 
      <section>
        <div class="container">
          <div class="row">
            
          </div>
        </div>
      </section>
        </footer>
    </div>
</template>