<template>
  <div>
    <div class="causes">
      <div class="heading flex flex-col items-center justify-center">
        <h1 class="mt-28 font-bold text-4xl">Recent Causes</h1>
        <p class="text-gray-400 mt-2">Lorem ipsum is a dummy text i wil use for subtitle here</p>
      </div> 
      <div class="cards flex gap-10 items-center justify-center mt-28">
        <div class="card1 border-solid border-[5px] border-gray-200">
          <img src="../assets/cause-img-1.jpg" alt="">
          <div class="writeup pl-4">
            <h1 class="mt-10 font-[500] uppercase text-[20px] mb-2">sponsor a child today</h1>
            <div class="target flex gap-2">
              <span class="text-gray-400 font-[500] text-[13px]">Rasied: $1890</span>
              <span class="text-[#f14b05] font-[500] text-[13px]">Goal: $2500</span>
            </div>
            <p class="text-gray-400 text-[15px] mt-2 mb-2">Lorem ipsum dolor sit amet consectetur <br/> adipisicing elit. Esse rem aspernatur ea saepe! <br/> Voluptate laudantium officia eveniet nesciunt?</p>
            <div class="btn flex gap-3 pb-8">
              <span class="text-xs font-bold border-2 border-[#f14b05] text-white px-5 py-2 rounded-full hover:text-[#f14b05] bg-[#f14b05] hover:bg-white hover:transition-all mr-2">Donate now</span>
              <span class="text-xs font-bold border-2 border-[#f14b05] text-[#f14b05] hover:text-white px-5 py-2 rounded-full hover:bg-[#f14b05] hover:transition-all">25 Donators</span>
            </div>
          </div>
        </div>
        <div class="card2 border-solid border-[5px] border-gray-200">
          <img src="../assets/cause-img-2.jpg" alt="">
          <div class="writeup pl-4">
            <h1 class="mt-10 font-[500] uppercase text-[20px] mb-2">sponsor a child today</h1>
            <div class="target flex gap-2">
              <span class="text-gray-400 font-[500] text-[13px]">Rasied: $1890</span>
              <span class="text-[#f14b05] font-[500] text-[13px]">Goal: $2500</span>
            </div>
            <p class="text-gray-400 text-[15px] mt-2 mb-2">Lorem ipsum dolor sit amet consectetur <br/> adipisicing elit. Esse rem aspernatur ea saepe! <br/> Voluptate laudantium officia eveniet nesciunt?</p>
            <div class="btn flex gap-3 pb-8">
              <span class="text-xs font-bold border-2 border-[#f14b05] text-white px-5 py-2 rounded-full hover:text-[#f14b05] bg-[#f14b05] hover:bg-white hover:transition-all mr-2">Donate now</span>
              <span class="text-xs font-bold border-2 border-[#f14b05] text-[#f14b05] hover:text-white px-5 py-2 rounded-full hover:bg-[#f14b05] hover:transition-all">25 Donators</span>
            </div>
          </div>
        </div>
        <div class="card3 border-solid border-[5px] border-gray-200">
          <img src="../assets/cause-img-3.jpg" alt="">
          <div class="writeup pl-4">
            <h1 class="mt-10 font-[500] uppercase text-[20px] mb-2">sponsor a child today</h1>
            <div class="target flex gap-2">
              <span class="text-gray-400 font-[500] text-[13px]">Rasied: $1890</span>
              <span class="text-[#f14b05] font-[500] text-[13px]">Goal: $2500</span>
            </div>
            <p class="text-gray-400 text-[15px] mt-2 mb-2">Lorem ipsum dolor sit amet consectetur <br/> adipisicing elit. Esse rem aspernatur ea saepe! <br/> Voluptate laudantium officia eveniet nesciunt?</p>
            <div class="btn flex gap-3 pb-8">
              <span class="cause-btn text-xs font-bold border-2 border-[#f14b05] text-white px-5 py-2 rounded-full hover:text-[#f14b05] bg-[#f14b05] hover:bg-white hover:transition-all mr-2">Donate now</span>
              <span class="cause-btn text-xs font-bold border-2 border-[#f14b05] text-[#f14b05] hover:text-white px-5 py-2 rounded-full hover:bg-[#f14b05] hover:transition-all">25 Donators</span>
            </div>
          </div>
        </div>
      </div> 
    </div>
  </div>
</template>

<script>
  export default {
    
  }
</script>

<style scoped>
  @media screen and (max-width: 1236px) {
    .cards {
      display: flex;
      gap: 20px;
      padding: 0 50px;
    }
  }

  @media screen and (max-width: 1005px) {
    .cards {
      display: flex;
      flex-direction: column;
    }
  }

  @media screen and (max-width: 370px) {
    .btn {
      display: flex;
      flex-direction: column;
      width: 150px;
    }

    .cause-btn {
      min-width: 100px;
    }
  }
</style>