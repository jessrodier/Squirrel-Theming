<template>
  <header>
    <nav class="wrapper">
      <div id="nav-container">
        <div class="brand">
          <a href="/">Wilson Style Guide</a>
        </div>
        <div id="nav-links">
          <router-link to="/">Home</router-link>
          <router-link to="/assets">Assets</router-link>
          <router-link to="/cheatsheet">Cheatsheet</router-link>
        </div>
        <div></div>
      </div>
    </nav>
  </header>
</template>

<script>
export default {
  name: 'globalHeader'
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
header {
  width: 100%;
  background: #001E52;
  position: fixed;
  z-index: 5;
}
#nav-container {
  display: flex;
  justify-content: space-between;
  align-items: center;
  font-size: 1rem;
}
.brand {
  font-weight: 600;
  text-transform: uppercase;
  font-size: 1.25rem;
  a {
    color: white;
    text-decoration: none;
  }
}
#nav-links {
  width: 25%;
  display: flex;
  justify-content: space-around;
  a {
    color: white;
    text-decoration: none;
    &:hover {
      text-decoration: underline;
    }
  }
}
</style>
