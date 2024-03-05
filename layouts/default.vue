<template>
    <main>

        
        <header class="shadow-sm bg-white">
            <nav class="container mx-auto p-4 flex justify-between">
                <NuxtLink to="/" class="font-bold">Foodie Finder </NuxtLink>
                <ul class="flex gap-4">
                    <li><NuxtLink to="/">Foodie</NuxtLink>  </li>
                    <li> <NuxtLink to="/about">About</NuxtLink></li>
                    <li><NuxtLink to="/menu">Menu</NuxtLink></li>
                    <li><NuxtLink to="/menuitems" class="btn">Menu Items</NuxtLink></li>
                 
                </ul>
            </nav>
            </header>
        
    
    <div class="container mx-auto p-4">
        <slot/>
    </div>
    </main>

    </template>
    <style scoped>
    .router-link-exact-active{
        color:#2e1065;
    }
</style>