<template>
  <div class="carousel">
    <div class="container py-4">

      <div class="p-5 text-dark mb-4 jumbotron-custom rounded-3">
        <div class="container-fluid py-5">
          <h1 class="display-5 fw-bold">Hi! my name is John Dale</h1>
          <p class=" col-md-8 fs-4">This is my website about... well, me.</p>
          <p class=" col-md-8 fs-4">In this this is my own personal website, here i've got a collection of things i enjoy to do.</p>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'InformationComponent',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>

.jumbotron-custom{
  background-color: #F2DD6E;
}

</style>
