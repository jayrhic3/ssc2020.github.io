<template>
<nav class="bg-green-800 p-2 mt-0 fixed w-full z-10 top-0">
        <div class="container mx-auto flex flex-wrap items-center">
		    <div class="flex w-full md:w-1/2 justify-center md:justify-start text-white font-extrabold">
        <img src="@/assets/img/ssc.png" width="40px"/>
					<span class="text-2xl pl-2"> <nuxt-link to="/">Supreme Student Council</nuxt-link></span>
        </div>
       <div class="dropdown inline-block relative text-white hover:text-yellow-600">
        <a class=" font-semibold py-2 px-4 rounded inline-flex items-center ">
          <span class="mr-1">The Chambers</span>
          <svg class="fill-current h-4 w-4" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 20 20"><path d="M9.293 12.95l.707.707L15.657 8l-1.414-1.414L10 10.828 5.757 6.586 4.343 8z"/> </svg>
        </a>
        <ul class="dropdown-menu absolute hidden text-gray-700 pt-1">
          <li class=""><a class="rounded-t bg-gray-200 hover:bg-yellow-400 py-2 px-4 block whitespace-no-wrap" ><nuxt-link to="/exec">Executive Chamber</nuxt-link></a></li>
          <li class=""><a class="rounded-t bg-gray-200 hover:bg-yellow-400 py-2 px-4 block whitespace-no-wrap" href="#">Legislative Chamber</a></li>
          <li class=""><a class="bg-gray-200 hover:bg-yellow-400 py-2 px-4 block whitespace-no-wrap" href="#">Judiciary Chamber</a></li>
          <li class=""><hr></li>
          <li class=""><hr></li>
          <li class=""><hr></li>
          <li class=""><hr></li>
          <li class=""><a class="rounded-b bg-gray-200 hover:bg-yellow-400 py-2 px-4 block whitespace-no-wrap" href="#">Major Organizations</a></li>
        </ul>
      </div>
      <a class="block mt-4 lg:inline-block lg:mt-0 text-white mr-4">
        |
      </a>
      <a href="#responsive-header" class="block mt-4 lg:inline-block lg:mt-0 text-white hover:text-yellow-600 mr-4">
        <nuxt-link to="/announcement">
        Announcement
        </nuxt-link>
      </a>
      <a href="#responsive-header" class="block mt-4 lg:inline-block lg:mt-0 text-white hover:text-yellow-600 mr-4">
        Transparency
      </a>
      <a class="block mt-4 lg:inline-block lg:mt-0 text-white hover:text-yellow-600">
        <nuxt-link to="/about">
        About
        </nuxt-link>
      </a>
      
    </div>
    </nav>
</template>


<style>
.dropdown:hover .dropdown-menu {
  display: block;
}
</style>