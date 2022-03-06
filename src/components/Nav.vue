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
  <transition
        mode = "out-in"
        enter-active-class="animate__animated animate__fadeIn"
        leave-active-class="animate__animated animate__gadeOut">
    <router-view/>
  </transition>

</body>
  
</template>

<script>
export default {

}
</script>

<style>

</style>