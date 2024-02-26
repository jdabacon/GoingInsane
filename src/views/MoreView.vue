<template>
  <div class="home">
    <HeaderComponent/>
    
    <!--dirty code-->
<br>
<br>
<br>
<!--end of dirty code-->

    <div class="container rounded custom-container p-5 courgette-regular mt-5">
      <h2 class="text-light" style="margin-right: 60px;">contact me here</h2>

      <h3 class="courgette-regular text-light" style="font-size: 24px">Gmail@gmail.com</h3>
    </div>


    <div class="container py-5 mt-5">
      <h2 class="comfortaa-uniquifier" style="font-size: 50px">my social media</h2>
      <div class="container row my-5" style="max-width: 540px; margin: auto;">
        <img src="../assets/facebook.png" alt="twitter logo" class="col, col-mg-5 rounded-circle" style="background-color: grey; height: 100px; width: 100px;">
        <h2 class="col align-middle pt-4 comfortaa-uniquifier" style="font-size: 40px">Facebook</h2>
      </div>
      <div class="container row my-5" style="max-width: 540px; margin: auto;">
        <img src="../assets/instagram.png" alt="twitter logo" class="col, col-mg-5 rounded-circle" style="background-color: grey; height: 100px; width: 100px;">
        <h2 class="col align-middle pt-4 comfortaa-uniquifier" style="font-size: 40px">Instagram</h2>
      </div>
      <div class="container row my-5" style="max-width: 540px; margin: auto;">
        <img src="../assets/twitter.png" alt="twitter logo" class="col, col-mg-5 rounded-circle" style="background-color: grey; height: 100px; width: 100px;">
        <h2 class="col align-middle pt-4 comfortaa-uniquifier" style="font-size: 40px">Twitter</h2>
      </div>
    </div>

    <div class="container custom-container p-5 courgette-regular my-5">
      <h2 >Check out my youtube channel !</h2>
      <iframe width="560" height="315" src="https://www.youtube.com/embed/JBA4hhARHV8?si=fwvHJbWDQaF0eY64" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

      <h3 class="courgette-regular mt-3 text-light" style="font-size: 24px">On my free time i play a dinosaur game called "The Isle"
      i record and edit fights & moments that me and my friends have in the game. 
      </h3>
    </div>
    <!--dirty code-->
    <br>
    <br>
    <br>
<!--end of dirty code-->
    <FooterComponent/>
  </div>

</template>

<script>
// @ is an alias to /src
import HeaderComponent from '@/components/HeaderComponent.vue'
import FooterComponent from '@/components/FooterComponent.vue'

export default {
  name: 'MoreView',
  components: {
    HeaderComponent, FooterComponent
  }
}
</script>

<style scoped>
nav >>> ul li:nth-child(3) {
  background-color: #5B6761;
}

.custom-container{
  background-image: url("../assets/layeredwave.png");
  background-position: bottom;
  background-size: cover;
  border-radius: 5px;
  max-width: 720px;
}
</style>