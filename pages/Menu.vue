<template>
    <main>
   
    <div class="img shadow-2xl">
      <h1>One cannot think well, love well, 
        <br/>sleep well, if one has not dined well</h1>
    </div>
</main>
</template>

<style>
.img{
background-image: url('https://marketplace.canva.com/EAFwRADHMsM/1/0/1035w/canva-orange-and-black-bold-geometric-restaurant-menu-AX4bhelWqNA.jpg');
height:100vh;
background-size: cover;
text-align:center;
font-size:40px;
color:white;
}
</style>
<script setup>
definePageMeta({
      middleware:["auth"]
  })
  </script>