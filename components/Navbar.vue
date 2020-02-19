<template>
<nav class="flex items-center justify-between flex-wrap bg-green-600 p-6">
  <div class="flex items-center flex-no-shrink text-white mr-6">
    <img src="@/assets/img/ssc.png" width="50px"/>
    <span class="font-semibold text-xl tracking-tight"><nuxt-link to="/home">Supreme Student Council</nuxt-link></span>
  </div>
  <div class="block lg:hidden">
    <button class="flex items-center px-3 py-2 border rounded text-teal-lighter border-teal-light hover:text-white hover:border-white">
      <svg class="h-3 w-3" viewBox="0 0 20 20" xmlns="http://www.w3.org/2000/svg"><title>Menu</title><path d="M0 3h20v2H0V3zm0 6h20v2H0V9zm0 6h20v2H0v-2z"/></svg>
    </button>
  </div>
  <div class="w-full block flex-grow lg:flex lg:items-center lg:w-auto">
    <div class="text-sm lg:flex-grow">
      <a class="block mt-4 lg:inline-block lg:mt-0 text-white mr-4">
        |
      </a>
      <div class="dropdown inline-block relative hover:text-white">
        <a class=" font-semibold py-2 px-4 rounded inline-flex items-center ">
          <span class="mr-1">Executive Chamber</span>
          <svg class="fill-current h-4 w-4" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 20 20"><path d="M9.293 12.95l.707.707L15.657 8l-1.414-1.414L10 10.828 5.757 6.586 4.343 8z"/> </svg>
        </a>
        <ul class="dropdown-menu absolute hidden text-gray-700 pt-1">
          <li class=""><a class="rounded-t bg-gray-200 hover:bg-green-200 py-2 px-4 block whitespace-no-wrap" href="#">The Officials</a></li>
          <li class=""><a class="rounded-t bg-gray-200 hover:bg-green-200 py-2 px-4 block whitespace-no-wrap" href="#">Documents</a></li>
          <li class=""><a class="bg-gray-200 hover:bg-green-200 py-2 px-4 block whitespace-no-wrap" href="#">Campus Events</a></li>
          <li class=""><a class="rounded-b bg-gray-200 hover:bg-green-200 py-2 px-4 block whitespace-no-wrap" href="#">Funds</a></li>
        </ul>
      </div>

      <div class="dropdown inline-block relative hover:text-white">
        <a class=" font-semibold py-2 px-4 rounded inline-flex items-center ">
          <span class="mr-1">Legislative Chamber</span>
          <svg class="fill-current h-4 w-4" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 20 20"><path d="M9.293 12.95l.707.707L15.657 8l-1.414-1.414L10 10.828 5.757 6.586 4.343 8z"/> </svg>
        </a>
        <ul class="dropdown-menu absolute hidden text-gray-700 pt-1">
          <li class=""><a class="rounded-t bg-gray-200 hover:bg-green-200 py-2 px-4 block whitespace-no-wrap" href="#">The Officials</a></li>
          <li class=""><a class="rounded-t bg-gray-200 hover:bg-green-200 py-2 px-4 block whitespace-no-wrap" href="#">Documents</a></li>
        </ul>
      </div>

<div class="dropdown inline-block relative hover:text-white">
        <a class=" font-semibold py-2 px-4 rounded inline-flex items-center ">
          <span class="mr-1">Judicial Chamber</span>
          <svg class="fill-current h-4 w-4" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 20 20"><path d="M9.293 12.95l.707.707L15.657 8l-1.414-1.414L10 10.828 5.757 6.586 4.343 8z"/> </svg>
        </a>
        <ul class="dropdown-menu absolute hidden text-gray-700 pt-1">
          <li class=""><a class="rounded-t bg-gray-200 hover:bg-green-200 py-2 px-4 block whitespace-no-wrap" href="#">The Officials</a></li>
          <li class=""><a class="bg-gray-200 hover:bg-green-200 py-2 px-4 block whitespace-no-wrap" href="#">Documents</a></li>
        </ul>
      </div>
      <a class="block mt-4 lg:inline-block lg:mt-0 text-white mr-4">
        |
      </a>
      <a href="#responsive-header" class="block mt-4 lg:inline-block lg:mt-0 text-teal-lighter hover:text-white mr-4">
        Announcements
      </a>
      <a href="#responsive-header" class="block mt-4 lg:inline-block lg:mt-0 text-teal-lighter hover:text-white mr-4">
        Transparency
      </a>
      <a class="block mt-4 lg:inline-block lg:mt-0 text-teal-lighter hover:text-white">
        <nuxt-link to="/about">
        About
        </nuxt-link>
      </a>
      
    </div>
    <div>
      <a href="#" class="inline-block text-sm px-4 py-2 leading-none border rounded text-white border-white hover:border-transparent hover:text-black hover:bg-green-200 mt-4 lg:mt-0">Sign In</a>
    </div>
  </div>
</nav>
</template>


<style>
.dropdown:hover .dropdown-menu {
  display: block;
}
</style>