<template>
  <nav id="top-nav" class="navbar" role="navigation" aria-label="main navigation">
    <div class="container">
      <div class="navbar-brand">
        <a id="brand" class="navbar-item" href="https://bulma.io">
          <img src="https://bulma.io/images/bulma-logo.png" alt="Bulma: a modern CSS framework based on Flexbox" width="112" height="28">
        </a>
        <div class="navbar-burger">
          <span></span>
          <span></span>
          <span></span>
        </div>
      </div>
      <div class="navbar-menu">
        <div class="navbar-end">
          <a class="navbar-item">Home</a>
          <a class="navbar-item">About</a>
          <a class="navbar-item">News and Events</a>
        </div>
      </div>
    </div>
  </nav>
</template>

<script>
export default {
  name: 'TopNav'
}
</script>

<style scoped>
#top-nav {
  position: fixed;
  top: 0px;
  left: 0px;
  right: 0px;
  background-color: rgb(90,74,66);
}
.navbar-item {
  color: #fff;
  border-top: 3px solid transparent;
  font-weight: 600;
}
#brand:hover {
  border-top: 3px solid transparent;
}
.navbar-item:hover {
  background-color: transparent;
}
.navbar-end .navbar-item:hover {
  background-color: transparent;
  color: rgb(212,105,35)!important;
  border-top: 3px solid rgb(212,105,35)!important;
}
</style>
