<template>
  <div class="mt-24 flex flex-col-2">
    <div class="flex-col text-left w-2/4 mt-5">
      <li>
        <span class="text-sm text-blue-600">Opening Day </span>
        <p class="text-2xl font-medium px-5 py-2 text-blue-950">April 4</p>
      </li>
      <li>
        <span class="text-sm text-gray-600">Speakers & Workshop </span>
        <p class="text-2xl font-medium px-5 py-2 text-blue-950">April 5</p>
      </li>
      <li>
        <span class="text-sm text-gray-600">Interview</span>
        <p class="text-2xl font-medium px-5 py-2 text-blue-950">April 6</p>
      </li>
    </div>
    <div class="grid grid-cols-3 list-none">
      <li
        v-for="x in 9"
        :key="x"
        class="p-4 bg-white card rounded-lg flex flex-col m-4 justify-between"
      >
        <div>
          <img src="../assets/steven-mchail.png" alt="productimage" />
        </div>
        <div class="p-2">
          <h2 class="text-lg font-semibold">Steven McHail</h2>
          <p class="text-gray-500 text-sm line-clamp-2">
            Designer at Globex Corporation
          </p>
        </div>
      </li>
    </div>
  </div>
</template>
<script>
export default {
  name: "List",
};
</script>
