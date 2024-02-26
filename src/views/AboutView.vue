<template>
  <div class="about">
    <HeaderComponent/>
    <div class="card mb-3 custom-card p-3" style="max-width: 740px; margin: auto;">
  <div class="row g-0">
    <div class="col-md-4">
      <img src="../assets/mypfp.jpg" class="img-fluid rounded-start mt-3" alt="image" style="min-height: 300px; max-width: 200px;">
    </div>
    <div class="col-md-8">
      <div class="card-body">
        <div class="container-fluid py-5 card-text">
          <h2 class="display-5 fw-bold courgette-regular" style="font-size: 50px;">Hello!</h2>
          <h2 class="col-md-8 fs-4 courgette-regular">My name is John</h2>
          <h4 class="courgette-regular mt-5" style="text-decoration: underline;"><span style="font-size: 50px;">&#8592;</span> This is me</h4>
      </div>
      </div>
    </div>
  </div>
</div>

<!--dirty code-->
<br>
<br>
<br>
<!--end of dirty code-->


  <div class="container mt-5 mb-5">
    <div class="container text-div-about ">
      <h2 class="comfortaa-uniquifier">I am 22 years old</h2>
    <h3 class="comfortaa-uniquifier" style="font-size: 20px">i currently am studying webmaster in Trollhättan</h3>

    <p class="mt-5 comfortaa-uniquifier" style="text-align:start;">Since i was young i've always been interested in arts of all kinds <br> In all diffent shapes and forms i've tried and tested a lot of things
     what fascinates me the most about art is creativity, the freedom and the reactions you get from the stuff you make. It's always entertaining to see someone have
     a fun reaction to something you make or even intrigued by how it was made or even works. <br> <br> it started off when i was a young kid living in england.
    At home i was inspired by a tv show called mr maker, in his show he used scraps and junk to make fun toys and art of all kinds. i also was inspired by a show
    called let's get squiggling where a monster would draw art and it i would come to life.<br>
    since then i've been into art, slowly getting more advanced. I started off with woodworking, creating statues, masks and figures out of wood. then i got interested in
    sculpting with plants by making bonsai and aftewards making pots with clay. for me i enjoy the process of art, working with your hands and creating things. <br><br>
    art for me takes shape in all kinds of forms and i am interested in experiencing them all, if it be comedy, drawing, sculpting, cutting hair or singing & playing music. 
    I enjoy being able to work with my hands, learn techniques and experience art in all of its glory.
    </p><br><br><p class="comfortaa-uniquifier">Oh yeah, i like the color orange</p>
    <br><br>
    <h2 class="courgette-regular">take a quick break, here's a fun random chuck norris quote: </h2>
    <p class="courgette-regular">(reload the page for a new one)</p>
    <ChuckNorrisQuote/>
    </div>
    
  </div>

  <!--dirty code-->
<br>
<br>
<br>
<!--end of dirty code-->

  <div class="container my-5 py-5 custom-card">
    <div class="container d-flex card-content p-5 my-3 ">
      <div class="row">
        <h2 class="col col-mg-5 comfortaa-uniquifier"> Bonsai</h2>
        <p class="col comfortaa-uniquifier" style="text-align:start;" > I started with bonsai because i thought it seemed like a fun entertaining hobby which seemed very calm and freeing. looking after
        a living organism which changes endlessly and requires good maintenance is a lot of fun.   
        </p>
      </div>
      </div>
      <div class="container d-flex card-content p-5 my-3">
        <div class="row">
        <h2 class="col comfortaa-uniquifier"> Pottery</h2>
        <p class="col col-mg-5 comfortaa-uniquifier" style="text-align:start;"> Pottery has always been cool and interesting but since i wasn't interested in buying clay i never started it.
        Until one day i was at my mother's house and found out that there was a whole mountain of clay by the river and i got the opportunity to start making
        bonsai pots and other stuff out of clay!
        </p>
      </div>
      </div>
      <div class="container d-flex card-content p-5 my-3">
        <div class="row">
        <h2 class="col col-mg-5 comfortaa-uniquifier"> Leatherwork</h2>
        <p class="col comfortaa-uniquifier" style="text-align:start;"> I had lost my wallet one day and thought it was a shame to have to buy a new one, so i thought it would be more fun to 
          try to make a wallet. I started off by buying some very cheap tools and extremely cheap leather scraps and managed to make my first wallet.
        </p>
      </div>
      </div>
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
import ChuckNorrisQuote from '@/components/FetchApi.vue'
import FooterComponent from '@/components/FooterComponent.vue'

export default {
  name: 'GalleryView',
  components: {
   HeaderComponent, ChuckNorrisQuote, FooterComponent
  }
}
</script>

<style scoped>
nav >>> ul li:nth-child(2) {
  background-color: #5B6761;
}

.card-content{
  background-color: rgba(226, 239, 222, 0.5);
  max-width: 800px;
}

.card-text{
  text-align: start;
  white-space: nowrap;
}
.custom-card{
  background-color: #F4B266;
  border-radius: 9px;
}


img{
  object-fit: cover;
}
</style>