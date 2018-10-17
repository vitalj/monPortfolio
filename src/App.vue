<template>
  <div id="app">
    <div id="nav">
      <ul>
      <li>  <router-link to="/">Home</router-link> </li>
    <li>   <router-link to="/about">About</router-link> </li>
     <li>  <router-link to="/Project">Projet</router-link> </li>
</ul>
    </div>
    <router-view/>
  </div>
</template>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-left: 20%; /* Same as the width of the sidenav */
  padding: 0px 10px;
}
#nav {
  height: 100%;
  width: 20%;
  position: fixed;
  z-index: 1;
  top: 0;
  left: 0;
  background-color: rgb(180, 179, 179);
  overflow-x: hidden;
  text-align: center;
  padding-top: 16px;

}

#nav a:hover{
    color: #f1f1f1;
}


#nav li {
  background-color: rgb(180, 179, 179);
 color: black; 
 list-style: none; 


}

#nav a {
  text-decoration: none;
  font-size: 2rem;
  color: #818181;
  display: block;
  width:100%;
  text-align: center;

}

#nav a.router-link-exact-active {
  color: #000000;
}

</style>
<script>


</script>