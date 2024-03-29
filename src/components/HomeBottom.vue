<template>
  <div class="">
    <div class="container flex min-w-full">
      <div class="first bg-[#eb5310e6]">
        <div class="top flex py-12 px-12">
          <div class="top-left mr-8">
            <img class="h-20 w-20" src="../assets/currency-naira.svg" alt="" />
          </div>
          <div class="top-right">
            <h1 class="text-white font-bold text-[25px] mb-2">DONATION</h1>
            <p class="text-white mb-2">
              There are many ways to donate to this company available
            </p>
          </div>
        </div>
        <div class="btn text-white bottom pl-36 -mt-10 mb-8 pb-6">
          <button
            class="text-xs font-bold border-2 border-white px-5 py-2 rounded-full hover:text-[#f14b05] hover:bg-white hover:transition-all"
          >
            DONATE NOW
          </button>
        </div>
      </div>
      <div class="second bg-[#fa773de5]">
        <div class="top flex py-12 px-12">
          <div class="top-left mr-8">
            <img class="h-20 w-20" src="../assets/users.svg" alt="" />
          </div>
          <div class="top-right">
            <h1 class="text-white font-bold text-[25px] mb-2">VOLUNTEER</h1>
            <p class="text-white mb-2">
              There are many ways to donate to this company available
            </p>
          </div>
        </div>
        <div class="btn text-white bottom pl-36 -mt-10 mb-8 border-white">
          <button
            class="text-xs font-bold border-white border-2 px-5 py-2 rounded-full hover:text-[#f14b05] hover:bg-white hover:transition-all"
          >
            JOIN NOW
          </button>
        </div>
      </div>
      <div class="third bg-[#eb5310e6]">
        <div class="top flex py-12 px-12">
          <div class="top-left mr-8">
            <img
              class="h-20 w-20"
              src="../assets/alternate-medical-chat.svg"
              alt=""
            />
          </div>
          <div class="top-right">
            <h1 class="text-white font-bold text-[25px] mb-2">FUNDRAISER</h1>
            <p class="text-white mb-2">
              There are many ways to donate to this company available
            </p>
          </div>
        </div>
        <div class="btn text-white bottom pl-36 -mt-10 mb-8 border-white">
          <button
            class="text-xs font-bold border-white border-2 px-5 py-2 rounded-full hover:text-[#f14b05] hover:bg-white hover:transition-all"
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
@media screen and (min-width: 1312px) {
  .btn {
    padding-left: 135px;
  }
}

@media screen and (min-width: 1311px) {
  .btn {
    padding-left: 130px;
  }
}
</style>
