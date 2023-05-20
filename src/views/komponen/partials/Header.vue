<template>
    <nav class=" absolute top-0 left-0 right-0 py-14 px-20 flex justify-between items-center">
        <div class=" text-3xl flex gap-2">
        <p class=" bg-[#b3e2dc] rounded-full px-2 font-bold text-white">T</p>
        <p class=" text-gray-500">anjung</p>
        
        </div>
        <div class=" mt-1 flex gap-16 text-gray-300">
            <RouterLink to="/">About Me</RouterLink>
            <RouterLink to="/a">Resume</RouterLink>
            <RouterLink to="/a">Blog</RouterLink>
            <RouterLink to="/a">Contact</RouterLink>
        </div>
    </nav>
</template>

<style scoped>

    a{
        transition: color 0.5s ease;
    }

    a:hover{
        color: black;  
    }
    a.router-link-exact-active{
        color: black;
    }
</style>