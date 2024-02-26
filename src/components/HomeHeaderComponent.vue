<template>
  <nav>
    <div class="header pt-4" >
    <header class="header-custom-style d-flex flex-wrap align-items-start justify-content-start  pt-4 border-bottom">
      <div class="col-md-3 mb-2 mb-md-0">
        <a href="/" class="d-inline-flex link-body-emphasis text-decoration-none">
          <img src="../assets/penguinbearsolid.png" class="bi" width="75" height="70">
        </a>
      </div>

      <ul class="nav col-12 col-md-auto mb-2 justify-content-center mb-md-0">
        <li><router-link class="nav-link text-light px-3" to="/">Home</router-link></li>
        <li><router-link class="nav-link text-light px-3" to="/about">About</router-link></li>
        <li><router-link class="nav-link text-light px-3" to="/more">More</router-link></li>
      </ul>
      <div class="col-md-3 text-end">
      </div>

      <div class="px-4 py-5 my-5 text-center d-flex flex-wrap align-items-center justify-content-center">
    <h1 class="display-5 fw-bold text-body-emphasis courgette-regular">Welcome to my page!</h1>
    <div class="col-lg-6 mx-auto">
      <p class="lead mb-4 courgette-regular">I've got a lot of friendly content here</p>
      <div class="d-grid gap-2 d-sm-flex justify-content-sm-center">
      </div>
    </div>
  </div>

    </header>

  </div>
  </nav>



</template>

<script>
export default {
  name: 'HomeHeaderComponent',
  props: {
    msg: String
  }
}
</script>
<!--https://placehold.co/600x400-->
<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>

  .header-custom-style{
  max-width: 1000px;
  margin: auto; 
  background-image: url("../assets/background.png");
  background-position: center;
  background-size:cover;
  border-radius: 8px;
}

nav li{
  background-color: #808F87;
  margin-left: 40px;
  line-height: 20px;
  border-radius: 5px;
}

</style>
