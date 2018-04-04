<template>
  <div>
    <div id="land-page">
      <div class="columns">
        <div class="column">
          <h1 class="title is-3">Agriculture</h1>
        </div>
      </div>
    </div>
    <div class="hero">
      <div class="hero-body columns">
        <div class="column">Image</div>
        <div class="column">Available all over the region</div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'Home',
  data () {
    return {
      msg: ''
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
#land-page {
  background-image: url('../assets/home-bg.jpg');
  background-size: cover;
  min-height: 400px;
  height: 30vh;
}
</style>
