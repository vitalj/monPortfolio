<template>
  <div id="app">
    <div id="nav">
      <link rel="stylesheet" 
        href="https://use.fontawesome.com/releases/v5.2.0/css/all.css">
      <ul>
      <li>  <router-link to="/"><i class="fas fa-home"></i> </router-link> </li>
    <li>   <router-link to="/about"><i class="fas fa-user"></i></router-link> </li>
     <li>  <router-link to="/Project"><i class="fas fa-code"></i> </router-link> </li>
</ul>
<div></div>
    </div>
    <router-view/>
  </div>
</template>

<style>
body {
	width: 100wh;
	height: 90vh;
	color: #fff;
	background: linear-gradient(-45deg, #EE7752, #E73C7E, #23A6D5, #23D5AB);
	background-size: 400% 400%;
	-webkit-animation: Gradient 10s ease infinite;
	-moz-animation: Gradient 10s ease infinite;
	animation: Gradient 10s ease infinite;
}

@-webkit-keyframes Gradient {
	0% {
		background-position: 0% 50%
	}
	50% {
		background-position: 100% 50%
	}
	100% {
		background-position: 0% 50%
	}
}

@-moz-keyframes Gradient {
	0% {
		background-position: 0% 50%
	}
	50% {
		background-position: 100% 50%
	}
	100% {
		background-position: 0% 50%
	}
}

@keyframes Gradient {
	0% {
		background-position: 0% 50%
	}
	50% {
		background-position: 100% 50%
	}
	100% {
		background-position: 0% 50%
	}
}

#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-left: 230px; /* Same as the width of the sidenav */
  padding: 0px 10px;
}
#nav {
  height: 100%;
  width: 230px;
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
  font-size: 4rem;
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