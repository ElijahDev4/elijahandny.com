<template>
  <div class="">
    <div
      id="headerimg"
      class="bg-no-repeat bg-fixed"
      :style="{
        'background-image': `url(${require('@/assets/headerimg.jpg')})`
      }"
    >
      <div class="container">
        <div class="row">
          <div class="col-xl-12 col-lg-12 col-md-12 col-sm-12 col-12">
            <div class="hero"></div>
          </div>
        </div>
      </div>
    </div>
    <!-- /.page-header-->
  </div>
</template>

<script>
export default {
  name: "MainHeader"
};
</script>

<style scoped>
body {
  -webkit-font-smoothing: antialiased;
  text-rendering: optimizeLegibility;
}
#headerimg {
  position: relative;
  background-size: cover;
}
.hero {
  padding-top: 246px;
  padding-bottom: 380px;
}
h1 {
  font-family: "Exo 2", sans-serif;
}
</style>
