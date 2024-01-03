<template>
  <div>
    <nav class="">
      <div id="body" class="bg-[#262F36] flex justify-between h-20  px-40">
        <div id="sub-body" class="flex">
          <div class="hamburger hidden">
            <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24"><path fill="none" stroke="#ffffff" stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M5 17h14M5 12h14M5 7h14"/></svg>
          </div>
          <ul id="text-items" class="flex flex-row items-center space-x-8">
            <li><a href="" class="text-sm font-bold uppercase text-white transition-all duration-300 ease-in-out hover:text-[#f14b05]">Home</a></li>
            <li><a href="" class="text-sm font-bold uppercase text-white transition-all duration-300 ease-in-out hover:text-[#f14b05]">About</a></li>
            <li><a href="" class="text-sm font-bold uppercase text-white transition-all duration-300 ease-in-out hover:text-[#f14b05]">Causes</a></li>
            <li><a href="" class="text-sm font-bold uppercase text-white transition-all duration-300 ease-in-out hover:text-[#f14b05]">Events</a></li>
            <li><a href="" class="text-sm font-bold uppercase text-white transition-all duration-300 ease-in-out hover:text-[#f14b05]">Volunteer</a></li>
            <li><a href="" class="text-sm font-bold uppercase text-white transition-all duration-300 ease-in-out hover:text-[#f14b05]">Gallery</a></li>
            <li><a href="" class="text-sm font-bold uppercase text-white transition-all duration-300 ease-in-out hover:text-[#f14b05]">Pages</a></li>
            <li><a href="" class="text-sm font-bold uppercase text-white transition-all duration-300 ease-in-out hover:text-[#f14b05]">Blog</a></li>
            <li><a href="" class="text-sm font-bold uppercase text-white transition-all duration-300 ease-in-out hover:text-[#f14b05]">Contact</a></li>
          </ul>
        </div>
        <div id="input-style" class="flex">
          <input id="input" type="text" placeholder="Search..." class="bg-[#303940] text-white h-full outline-none caret-white px-6">
          <div id="search" class="flex items-center justify-center bg-[#303940] px-6">
            <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24"><path fill="#ffffff" d="m19.6 21l-6.3-6.3q-.75.6-1.725.95T9.5 16q-2.725 0-4.612-1.888T3 9.5q0-2.725 1.888-4.612T9.5 3q2.725 0 4.613 1.888T16 9.5q0 1.1-.35 2.075T14.7 13.3l6.3 6.3zM9.5 14q1.875 0 3.188-1.312T14 9.5q0-1.875-1.312-3.187T9.5 5Q7.625 5 6.313 6.313T5 9.5q0 1.875 1.313 3.188T9.5 14"/></svg>
          </div>
        </div>
      </div>
    </nav>
  </div>
</template>

<script>
  export default {
    
  }
</script>

<style scoped>
  @media screen and (max-width: 1374px) {
    #body {
      padding: 0 30px;
    }
  }

  @media screen and (max-width: 1135px) {
    #body {
      display: flex;
      flex-direction: column;
      height: 140px;
    }

    #text-items {
      margin-top: 20px;
    }

    #input-style {
      margin-top: 20px;
    }

    #input {
      height: 70px;
      width: 100%;
    }
  }

  @media screen and (max-width: 768px) {
    #body {
      display: flex;
      flex-direction: row;
      height: 60px;
    }

    #text-items {
      display: none;
    }

    #sub-body {
      width: 0;
    }

    .hamburger {
      display: flex;
      justify-content: center;
      align-items: center;
      background-color: #f14b05;
      padding: 10px;
      margin: 10px 0;
    }

    #input-style {
      display: flex;
      justify-content: center;
      align-items: center;
    }

    #input {
      height: 50px;
      margin-bottom: 20px;
    }

    #search {
      height: 50px;
      margin-bottom: 20px;
    }
  }
  @media screen and (max-width: 425px) {
    #input {
      width: 200px;
      padding-right: 0;
    }

    #search {
      padding-right: 10px;
      padding-left: 0;
    }
  }
  @media screen and (max-width: 345px) {
    #body {
      padding: 5px;
    }
  }
</style>