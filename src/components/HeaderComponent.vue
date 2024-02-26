<template>
  <nav>
    <div class="header pt-3" >
    <header class="header-custom-style d-flex flex-wrap align-items-center justify-content-center justify-content-md-between py-4 pt-4 mb-4 border-bottom">
      <div class="col-md-3 mb-2 mb-md-0">
        <a href="/" class="d-inline-flex link-body-emphasis text-decoration-none">
          <img src="../assets/penguinbearsolid.png" class="bi" width="75" height="70">
        </a>
      </div>

      <ul class="nav col-12 col-md-auto mb-2 justify-content-center mb-md-0">
        <li><router-link class="nav-link text-light px-3 comfortaa-uniquifier" to="/">Home</router-link></li>
        <li><router-link class="nav-link text-light px-3 comfortaa-uniquifier" to="/about">About</router-link></li>
        <li><router-link class="nav-link text-light px-3 comfortaa-uniquifier" to="/more">More</router-link></li>
      </ul>

      <div class="col-md-3 text-end">
      </div>
    </header>
  </div>
  </nav>
</template>

<!--<router-link :to="someUrl" exact-path>{{title}}</router-link>-->

<script>
export default {
  name: 'HeaderComponent',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.header-custom-style{
  max-width: 1000px;
  margin: auto;
  background-color: #AFD0BF ;
  border-radius: 8px;
}

nav li{
  background-color: #808F87;
  margin-left: 40px;
  line-height: 20px;
  border-radius: 5px;
}

</style>
