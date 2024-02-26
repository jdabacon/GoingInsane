<template>
  <div class="home">
    <HomeHeaderComponent/>

    <div class="container custom-container my-5 px-5 py-5 comfortaa-uniquifier " style="font-size: 22px;">
      <p> Welcome to my personal website! i've got all the info you need to know about me available here.</p>
    </div>

    <div class="container text-center special-nav-container px-5 py-5">
  <div class="row custom-grid">
    <div class="col">
      <router-link class="nav-link text-dark py-5 comfortaa-uniquifier" style="text-shadow: 0px 0px 10px white;"  to="/about">About me ></router-link>
        
    </div>
    <div class="col">
      <router-link class="nav-link text-dark py-5 comfortaa-uniquifier" style="text-shadow: 0px 0px 10px white;" to="/more">Contact & social ></router-link>
    </div>
</div>
    </div>
    <FooterComponent/>
  </div>
</template>

<script>
// @ is an alias to /src
import HomeHeaderComponent from '@/components/HomeHeaderComponent.vue'
import FooterComponent from '@/components/FooterComponent.vue'

export default {
  name: 'HomeView',
  components: {
    HomeHeaderComponent, FooterComponent
  }
}
</script>

<style scoped>
nav >>> ul li:nth-child(1) {
  background-color: transparent;
  font-weight:bolder;
  font-size:24px; 
}

nav >>> ul li {
  background-color: transparent;
  font-size: 18px;
}

.custom-container{
  background-color: #F4B266;
  border-radius: 5px;
  max-width: 720px;
}

.special-nav-container{
  background-color: #AFD0BF;
  margin-top: 150px;
  margin-bottom: 150px;
}

.custom-grid .col{
  background-image: url("../assets/lowrestriangle.png");
  background-position: center;
  background-size: cover;
  margin: 30px;
  border-radius: 9px;
  font-size: 30px;
  font-weight: bold;
}


</style>