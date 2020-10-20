<template>
    <div id="app" class="container-fluid">
        <div class="site-info">
            <h1>CRUD Data Customers</h1>
        </div>
        <nav style="float:center;margin:30px;">
            <router-link class="btn btn-primary" to="/">Daftar Customers</router-link>
            <router-link class="btn btn-primary" to="/add">Tambah Customer</router-link>
            <router-link class="btn btn-primary" to="/search">Search Customer</router-link>
        </nav>
        <br/>
        <router-view/>
    </div>
</template>
 
<script>
export default {
  name: "app"
};
</script>
 
<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 50px;
}

.btn-primary {
  margin-right: 5px;
  color:cyan;

}
 
.container-fluid {
  text-align: center;
}
</style>