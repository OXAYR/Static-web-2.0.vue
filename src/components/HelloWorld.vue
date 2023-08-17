<template>
  <div class="flex flex-col gap-4 px-20 font-serif">
    <Header />
    <Banner />
    <p class="text-5xl text-left text-blue-600">Speakers</p>
    <p class="text-left text-xl">
      Learn from the experts on the cutting-edge of deception at the most
      sinister companies.
    </p>
    <div class="mt-24">
      <div class="flex">
        <div class="flex-col gap-x-32 flex-wrap text-left">
          <li class="m-4">
            <span class="text-sm text-blue-600">Opening Day </span>
            <p class="text-2xl font-medium px-5 py-2 text-blue-950">April 4</p>
          </li>
          <li class="m-4">
            <span class="text-sm text-gray-600">Speakers & Workshop </span>
            <p class="text-2xl font-medium px-5 py-2 text-blue-950">April 5</p>
          </li>
          <li class="m-4">
            <span class="text-sm text-gray-600">Interview</span>
            <p class="text-2xl font-medium px-5 py-2 text-blue-950">April 6</p>
          </li>
        </div>
      </div>
      <div class="grid grid-cols-3 list-none">
        <li
          v-for="x in 9"
          :key="x"
          class="p-4 bg-white shadow-md rounded-lg flex flex-col justify-between"
        >
          <div><img src="" alt="productimage" /></div>
          <div class="p-2">
            <h2 class="text-lg font-semibold">Steven McHail</h2>
            <p class="text-gray-500 text-sm line-clamp-2">
              Designer at Globex Corporation
            </p>
          </div>
        </li>
      </div>
    </div>
  </div>
</template>

<script>
import Header from "./Header.vue";
import Banner from "./Banner.vue";
export default {
  name: "Home",
  components: {
    Header,
    Banner,
  },
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped></style>
