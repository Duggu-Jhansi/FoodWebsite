<template>
    <main>
    
   
    <div class="image">
      <h1>One cannot think well, love well, 
        <br/>sleep well, if one has not dined well</h1>
    </div>


</main>
    </template>
    <script setup>
    definePageMeta({
      middleware:["auth"]
  })
    </script>
    
    <style>
.image{
background-image: url('https://as2.ftcdn.net/v2/jpg/01/05/59/47/1000_F_105594745_L4LOLXVKO3whdNjio9I1ZImAUqzlyMR9.jpg');
height:100vh;
background-size: cover;
text-align:center;
font-size:40px;
color:black;
}
</style>