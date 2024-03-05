<template>
    <main>

    <div class="grid grid-cols-3 gap-1 justify-evenly ">
          
            <div >
        <img src="https://static.vecteezy.com/system/resources/thumbnails/022/190/816/small/chicken-biryani-using-jeera-rice-arranged-in-bowl-generative-ai-photo.jpg" class="image1"/>
    <p  class="para">Biryani</p>    
    </div>
    <div >
        <img src="https://thumbs.dreamstime.com/b/veg-pulao-cooked-masala-spices-served-over-rustic-wooden-background-selective-focus-224434625.jpg" class="image2"/>
    <p class="para">pulao</p>    
    </div>
    <div >
        <img src="https://vaya.in/recipes/wp-content/uploads/2018/02/Idli-and-Sambar-1.jpg" class="image2"/>
    <p class="para">Idli and Sambar</p>    
    </div>
    <div >
        <img src="https://st.depositphotos.com/1003814/5052/i/450/depositphotos_50523105-stock-photo-pizza-with-tomatoes.jpg" class="image2"/>
    <p class="para">Pizza</p>    
    </div>
    <div >
        <img src="https://www.kitchensanctuary.com/wp-content/uploads/2022/09/Air-Fryer-Chicken-Curry-square-FS-36.jpg" class="image2"/>
    <p class="para">chicken Curry</p>    
    </div>
    <div >
        <img src="https://nishkitchen.com/wp-content/uploads/2015/12/PANEER-BUTTER-MASALA-1b.jpg" class="image2"/>
    <p class="para">Panner</p>    
    </div>
    <div >
        <img src="https://www.licious.in/blog/wp-content/uploads/2021/01/Mangalorean-Pomfret-Fish-Curry-750x750.jpg" class="image2"/>
    <p class="para">Fish Curry</p>    
    </div>
    <div >
        <img src="https://t4.ftcdn.net/jpg/02/57/02/67/360_F_257026750_ckdlvzplvocnCn8aGQhdD8tZ430O4hgX.jpg" class="image2"/>
    <p class="para">Kebabs</p>    
    </div>
    <div >
        <img src="https://e0.pxfuel.com/wallpapers/936/1016/desktop-wallpaper-chicken-65-chilli-chicken.jpg" class="image2"/>
    <p class="para">Chicken 65</p>    
    </div>
    <div >
        <img src="https://wallpapers.com/images/hd/tandoori-chicken-with-wasabi-1kku3uzwr5hyzh0q.jpg" class="image2"/>
    <p class="para">Tandoori </p>    
    </div>
    <div >
        <img src="https://e0.pxfuel.com/wallpapers/185/30/desktop-wallpaper-dosa-masala-dosa.jpg" class="image2"/>
    <p class="para">Dosa</p>    
    </div>
    <div >
        <img src="https://st2.depositphotos.com/5653638/11520/i/950/depositphotos_115207410-stock-photo-indian-thali-indian-food-thali.jpg" class="image2"/>
    <p class="para">Thali</p>    
    </div>
        </div>
        
    </main>
    </template>
    <script setup>
    definePageMeta({
      middleware:["auth"]
  })
    </script>
    <style>
    .image1{
        height: 400px;
        width: 400px;
        margin:5px;
        padding:5px;
    }
    .image2{
        height: 400px;
        width: 400px;
        margin:5px;
        padding:5px;
    }
    .para{
        text-align: center;
    }
    </style>