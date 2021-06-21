<template>
  <div class="fluid-container">
     <div class="row bg-dark">
            <div class="col-lg-12">
              <p class="text-center text-light display-4 pt-2" style="font-size: 25px;">Crud Application</p>
            </div>
      </div>
      <div class="col-lg-6">
        <button class="btn btn-info float-right">
          <i class="fas fa-user"></i>&nbsp;&nbsp;Add New Car
        </button>
      </div>
    <div id="nav">
      <router-link to="/addnew">+Add New Car</router-link> |
      <router-link to="/">Home</router-link> |
      <router-link to="/about">About</router-link> |
      <router-link to="/contact">Contact</router-link>
    </div>
  </div>
  <router-view/>
</template>

<style lang="scss">
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}

#nav {
  padding: 30px;

  a {
    font-weight: bold;
    color: #2c3e50;

    &.router-link-exact-active {
      color: #42b983;
    }
  }
}
</style>
