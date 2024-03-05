<template>
    <main>
   
    <div class="imge">
  <h1 class=" head  shadow-2xl  text-center bg-black">
Foodie Finder: Where Your Taste Buds Take the Lead</h1>
<p class="text-left text-2xl">Embark on a culinary journey like never before with Foodie Finder, your ultimate destination for all things delicious! Explore a world of flavors, tantalize your taste buds, and discover hidden gastronomic gems near and far. Whether you crave sizzling street food, crave-worthy comfort dishes, or gourmet delights fit for royalty, our curated platform connects you with the hottest eateries, trendiest cafes, and top-rated restaurants in town.</p>
<div class=" grid grid-cols-2">

</div>
</div>
  
    </main>
</template>

<style>
.imge{
background-image: url('https://img.freepik.com/premium-photo/food-table-top-view-free-space-your-text_187166-25767.jpg');
height:100vh;
background-size: cover;
text-align:center;
font-size:40px;
color:white;
display:flex;
flex-direction:column;
justify-content: center;
}
.head{
  color:white;
  text-align:center;
}
.image11{
  height:500px;
  width:500px;
}
.image12{
  height:500px;
  width:500px;

}
</style>
<script setup>
definePageMeta({
      middleware:["auth"]
  })
  </script>