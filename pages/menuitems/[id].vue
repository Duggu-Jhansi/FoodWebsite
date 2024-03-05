<template>
<main>
    <div>
        <h1>Menu Items of Restaurent {{ id }}</h1>
        <div >
    <img src="https://static.vecteezy.com/system/resources/thumbnails/022/190/816/small/chicken-biryani-using-jeera-rice-arranged-in-bowl-generative-ai-photo.jpg" class="image1"/>
<p  class="para">Biryani</p>    
</div>

    </div>
</main>
</template>
<script setup>
const {id}=useRoute().params
definePageMeta({
        layout:'menuitems'
     })
</script>
<style>
.image1{
    height: 300px;
    width: 500px;
    margin:5px;
    padding:5px;
}
.image2{
    height: 300px;
    width: 500px;
    margin:5px;
    padding:5px;
}
</style>