<template>
  <div class="">
    <div class="container flex min-w-full">
      <div class="first flex items-center justify-center px-2 py-2 bg-[#eb5310e6]">
        <div class="top">
          <div class="top-left px-10">
            <img class="h-28 w-28" src="../assets/currency-naira.svg" alt="" />
          </div>
        </div>
        <div class="btn text-white bottom">
          <div class="top-right">
            <h1 class="text-white font-bold text-3xl pb-3 pt-20">DONATION</h1>
            <p class="text-white pb-6 mr-[2px]">
              There are many ways to donate to this company available
            </p>
          </div>
          <button
            class="text-xs font-bold border-2 border-white px-5 mb-20 py-2 rounded-full hover:text-[#f14b05] hover:bg-white hover:transition-all"
          >
            DONATE NOW
          </button>
        </div>
      </div>
      <div class="first flex items-center justify-center px-2 py-2 bg-[#fa773de5]">
        <div class="top">
          <div class="top-left px-10">
            <img class="h-28 w-28" src="../assets/users.svg" alt="" />
          </div>
        </div>
        <div class="btn text-white bottom">
          <div class="top-right">
            <h1 class="text-white font-bold text-3xl pb-3 pt-20">VOLUNTEER</h1>
            <p class="text-white pb-6 mr-[2px]">
              There are many ways to donate to this company available
            </p>
          </div>
          <button
            class="text-xs font-bold border-2 border-white px-5 mb-20 py-2 rounded-full hover:text-[#f14b05] hover:bg-white hover:transition-all"
          >
            JOIN NOW
          </button>
        </div>
      </div>
      <div class="first flex items-center justify-center px-2 py-2 bg-[#eb5310e6]">
        <div class="top">
          <div class="top-left px-10">
            <img class="h-28 w-28" src="../assets/alternate-medical-chat.svg" alt="" />
          </div>
        </div>
        <div class="btn text-white bottom">
          <div class="top-right">
            <h1 class="text-white font-bold text-3xl pb-3 pt-20">FUNDRAISER</h1>
            <p class="text-white pb-6 mr-[2px]">
              There are many ways to donate to this company available
            </p>
          </div>
          <button
            class="text-xs font-bold border-2 border-white px-5 mb-20 py-2 rounded-full hover:text-[#f14b05] hover:bg-white hover:transition-all"
          >
            READ MORE
          </button>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style scoped>
@media screen and (max-width: 1102px) {
  .container {
    display: flex;
    flex-direction: column;
  }
}
</style>
