<template>
    <div class="">
        <header class="border-b-2 bg-none">
            <nav class="flex gap-11 text-[20px] py-5   h-[80px] border-2 border-black w-fit m-auto">

                <NuxtLink to="/"  class="mt-3"><img src="~/assets/Logo.png" alt="" ></NuxtLink>
        
                <ul class="flex gap-8 mt-3 ">

                    <li><NuxtLink to="">Home</NuxtLink></li>
                    <li><NuxtLink to="">Nos services </NuxtLink></li>
                    <li><NuxtLink to="">Resources</NuxtLink></li>
                    <li><NuxtLink to="">Nos tarifs</NuxtLink></li>
                </ul>
                <div class="ml-44">
                    <button class="py-[10px] px-[18px]">Creer un compte</button>
                    <button class="bg-[#2D9737] rounded-[8px] py-[10px] px-[18px] text-white">Se Connecter</button>
                </div>
                
            </nav>
        </header>
    </div>
    <!--Output the page content-->
    <div>
        <slot />
    </div>
</template>

