<template>

<section>
  <div class="front">
  
  </div>
<div class="grid-container">
<div>
    <div class="card">
    <img src="..\assets\images\1.png" alt="Avatar" style="width:100%">
    <div class="container">
      <h4><b>LukTung Esan</b></h4> 
      <p>Lest's guess the song !!!</p> 
          <router-link to="/LukTung1#ask">
            <button class="button">Play</button>
          </router-link>
    </div>
  </div>
</div>

  <div>

  <div class="card">
    <img src="https://www.brighttv.co.th/wp-content/uploads/2020/12/dream-leaf.png" alt="Avatar" style="width:100%">
    <div class="container">
      <h4><b>Plant</b></h4> 
      <p>โครงสร้างพืช</p> 
      <button class="button">Play</button>
    </div>
  </div>
  </div>
  <div>

  <div class="card">
    <img src="https://www.brighttv.co.th/wp-content/uploads/2020/12/dream-leaf.png" alt="Avatar" style="width:100%">
    <div class="container">
      <h4><b>Plant</b></h4> 
      <p>โครงสร้างพืช</p> 
      <button class="button">Play</button>
    </div>
  </div>
  </div>
  <div>

  <div class="card">
    <img src="https://www.brighttv.co.th/wp-content/uploads/2020/12/dream-leaf.png" alt="Avatar" style="width:100%">
    <div class="container">
      <h4><b>Plant</b></h4> 
      <p>โครงสร้างพืช</p> 
      <button class="button">Play</button>
    </div>
  </div>
  </div>
</div>

</section>
</template>

<script src="https://cdn.tailwindcss.com">
</script>
<script>
export default {
  name:"Home",

};

</script>

<style>
.grid-container  {
  display: grid;
  grid-template-columns: auto auto;
  gap: 50px;
  background-color:rgb(169, 160, 140);
  padding: 50px;
}
.card {
  box-shadow: 0 4px 8px 0 rgba(0,0,0,0.2);
  transition: 0.3s;
  width: 70%;
  border-radius: 5px;
}
.card:hover {
  box-shadow: 0 8px 16px 0 rgba(0,0,0,0.2);
}

img {
  border-radius: 5px 5px 0 0;
}
.container {
  padding: 15px 20px;
  color: white;
  background-color:rgb(163, 173, 184);
}

.button {
  position: relative;
  background-color: rgb(78, 97, 114);
  border: none;
  font-size: 15px;
  color: #FFFFFF;
  padding: 10px;
  width: 80px;
  text-align: center;
  -webkit-transition-duration: 0.4s; /* Safari */
  transition-duration: 0.4s;
  text-decoration: none;
  overflow: hidden;
  cursor: pointer;
  border-radius: 5px;
}
.button:after {
  content: "";
  background: rgb(70, 87, 102);
  display: block;
  position: absolute;
  padding-top: 300%;
  padding-left: 350%;
  margin-left: -20px!important;
  margin-top: -120%;
  opacity: 0;
  transition: all 0.8s
}
.button:active:after {
  padding: 0;
  margin: 0;
  opacity: 1;
  transition: 0s
}
</style>

