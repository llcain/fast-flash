<script setup>
import { CIcon } from '@coreui/icons-vue';
import { cilList, cilShieldAlt } from '@coreui/icons';
import HelloWorld from './components/HelloWorld.vue'
import TheWelcome from './components/TheWelcome.vue'
</script>

<template>
  <div class="container">

    <banner>
      <header>    
        <h1>Logo</h1>
        <ul>
          <li>Home</li>
          <li>About</li>
          <li>Contact</li>
        </ul>
        <div>
          <CIcon :icon="cilList" size="md"/>
          <CIcon :icon="cilShieldAlt" size="md"/>

          <button>Sign In</button>
        </div>
      </header>
    </banner>

  
    

    <main class="main-container">
    <h2>New Items</h2>
    <div class="new-items">
      <div class="card">
        <div>
          <img src="/photo1.jpg">
        </div>
        <div class="product-name">
          <h2>Sunny Candle</h2>
        </div>
        <div class="price">
          <h3>$25</h3>
        </div>
      </div>
      <div class="card">
        <div>
          <img src="/photo1.jpg">
        </div>
        <div class="product-name">
          <h2>Sunny Candle</h2>
        </div>
        <div class="price">
          <h3>$20</h3>
        </div>
        <span class="special-offer">Special Offer</span>
        <span class="special-offer-prie">$17.90</span>
      </div>
      <div class="card">
        <div>
          <img src="/photo1.jpg">
        </div>
        <div class="product-name">
          <h2>Sunny Candle</h2>
        </div>
        <div class="price">
          <h3>$20</h3>
        </div>
      </div>
    </div>   
    <h2>Deals</h2>
    <div class="deal-items">
      <div class="card">
        <div>
          <img src="/photo1.jpg">
        </div>
        <div class="product-name">
          <h2>Sunny Candle</h2>
        </div>
        <div class="price">
          <h3>$20</h3>
        </div>
      </div>
      <div class="card">
        <div>
          <img src="/photo1.jpg">
        </div>
        <div class="product-name">
          <h2>Sunny Candle</h2>
        </div>
        <div class="price">
          <h3>$20</h3>
        </div>
      </div>
      <div class="card">
        <div>
          <img src="/photo1.jpg">
        </div>
        <div class="product-name">
          <h2>Sunny Candle</h2>
        </div>
        <div class="price">
          <h3>$20</h3>
        </div>
      </div>
    </div>
    
    </main>

    <footer class="footer">
      <div class="column">
        <h3>Customer Service</h3>
        <h3>Shipping</h3>
        <h3>Delivery</h3>
      </div>
      <div class="column">
        <h3>Facebook, Instagram, LinkedIn, and Twitter Icons</h3>
        <h3>Privacy Terms</h3>
      </div>
    </footer>
  </div> 
</template>

<style scoped>
.main-container {
  width: 1500px;
}

img {
  width: 350px;
  height: 350px;
  object-fit: contain;
}
.new-items, .deal-items {
  display: flex;
}

.card {
  margin: 15px;
  width: 350px;
  border: 2px solid black;
}



.special-offer {
    color: salmon;
    position: relative;
    bottom: 20px;
    left: 65px;
    
}

.special-offer-price {
    color: green;
    position: relative;
    bottom: 20px;
    left: 65px;
}

</style>
