<template>
  <footer class="container d-flex flex-wrap justify-content-around align-items-center py-4 px-5 mt-5 border-top">
    <div class=" ms-5 " >
      <h1 class="courgette-regular">John's personal site</h1>
      <hr class="line-through">
      <h4 class="courgette-regular text-light">this is where i have some text</h4>
    </div>
    
  <div class="col-md-4 d-flex align-items-center">
    <a href="/" class="mb-3 me-2 mb-md-0 text-body-secondary text-decoration-none lh-1">
      <svg class="bi" width="30" height="24"><use xlink:href="#bootstrap"></use></svg>
    </a>
  </div>

  <ul class="nav col-md-4 justify-content-end list-unstyled d-flex">
    <li class="ms-3"><a class="text-body-secondary mx-2" href="#"><img src="../assets/facebook.png" style="height:50px;;"></a></li>
    <li class="ms-3"><a class="text-body-secondary mx-2" href="#"><img src="../assets/instagram.png" style="height:50px"></a></li>
    <li class="ms-3"><a class="text-body-secondary mx-2" href="#"><img src="../assets/twitter.png" style="height:50px"></a></li>
  </ul>
</footer>
  </template>
  
  <script>

  export default {
    name: 'FooterComponent',
    props: {
        someUrl: String, 
      title: String
    }
  }
  </script>
  
  <!-- Add "scoped" attribute to limit CSS to this component only -->
  <style scoped>

    footer{
      background-color: #9B7E46;
    }

    .line-through{
      background-color: white;
      width: 300px;
      height: 2px;
      
    }

  </style>
  