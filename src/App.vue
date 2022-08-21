<template>

  <div class="mb-2">
    <img src="./assets/images/logo.png" />
  </div>

  <div class="w-full h-52 sm:h-450px mb-2 relative overflow-hidden">
    <img src="./assets/images/img1.png" class="w-full h-full object-cover object-bottom absolute" />

    <div
      class="bg-orange-600 bg-opacity-70 absolute w-1/2 sm:w-1/3 h-full right-5 sm:right-28 flex flex-col items-center justify-center text-white">
      <div class="text-2xl sm:text-6xl"> <span class=" text-orange-300 font-bold">ABOUT </span> US </div>
      <hr class="mt-2 mb-2 w-2/5">
      <p class="px-2 sm:text-center sm:text-3xl"> At ANIDA, we are individuals who believe that it takes more than
        passion and being intentional to create a world of difference.
      </p>
    </div>

  </div>

  <div class="sm:flex sm:h-450px">

    <div class="w-full h-56 sm:h-full mb-2 sm:m-2 flex items-center justify-center overflow-hidden relative">
      <img src="./assets/images/img2.png" class="scale-125 absolute" />
      <div class="bg-black bg-opacity-40 absolute w-full h-full flex flex-col items-center justify-center text-white">
        <div class="text-2xl sm:text-5xl font-bold"> VISION </div>
        <hr class="mt-2 mb-2 w-2/5 border border-orange-600">
        <p class="px-2 sm:text-2xl">
          Creating opportunity through access to education.
        </p>
      </div>
    </div>

    <div class="w-full h-56 sm:h-full mb-2 sm:m-2 flex items-center justify-center overflow-hidden relative">
      <img src="./assets/images/img3.png" class="scale-125 absolute" />
      <div class="bg-black bg-opacity-40 absolute w-full h-full flex flex-col items-center justify-center text-white">
        <div class="text-2xl sm:text-5xl font-bold"> MISSION </div>
        <hr class="mt-2 mb-2 w-2/5 border border-orange-600">
        <p class="px-2 sm:text-2xl text-center">
          An international organization rooted in Christian values that creates opportunities through community-based
          projects for individuals facing a difficult reality. </p>
      </div>
    </div>

  </div>

</template>

<script>

export default {
  name: 'App',
  components: {
  }
}
</script>

<style>
#app {
  font-family: system-ui, -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}
</style>
