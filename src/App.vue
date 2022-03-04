<template>
<body>
    <div class="nav">
    <link href="https://cdn.jsdelivr.net/npm/daisyui@2.4.0/dist/full.css" rel="stylesheet" type="text/css" />
      <div class="navbar bg-base-100">
        <div class="flex-1">
          <a class="btn btn-ghost normal-case text-xl">Pim Code</a>
        </div>
        <div class="flex-none">
          <ul class="menu menu-horizontal p-0">
            <li><a><router-link to="/">Home</router-link></a></li>
            <li><a><router-link to="/about">About</router-link></a></li>
            <li><a>Logout</a></li>
            
          </ul>
        </div>
      </div>
  </div>
  <router-view/>
</body>
  
  

</template>

<style>

#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}

#nav {
  padding: 30px;
}

#nav a {
  font-weight: bold;
  color: #2c3e50;
  
}

</style>
