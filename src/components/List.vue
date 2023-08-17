<template>
  <div class="mt-24 flex flex-col-2">
    <div class="flex-col text-left w-2/4 mt-5">
      <li
        v-for="(item, index) in listItems"
        :key="index"
        @click="selectItem(index)"
        class="cursor-pointer transition-colors"
      >
        <span
          class="text-sm"
          :class="{
            'text-blue-600': selectedItem === index,
            'text-gray-600': selectedItem !== index,
          }"
          >{{ item.label }}</span
        >
        <p
          class="text-2xl font-medium px-5 py-2"
          :class="{
            'text-blue-950': selectedItem === index,
            'text-gray-600': selectedItem !== index,
          }"
        >
          {{ item.date }}
        </p>
      </li>
    </div>
    <div class="grid grid-cols-3 list-none cursor-pointer">
      <li
        v-for="x in 9"
        :key="x"
        class="bg-white rounded-lg flex flex-col m-4 justify-between border border-blue-500"
      >
        <div>
          <img
            class="rounded hover:scale-110"
            src="../assets/steven-mchail.png"
            alt="productimage"
          />
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
  data() {
    return {
      listItems: [
        { label: "Opening Day", date: "April 4" },
        { label: "Speakers & Workshop", date: "April 5" },
        { label: "Interview", date: "April 6" },
      ],
      selectedItem: null,
    };
  },
  methods: {
    selectItem(index) {
      this.selectedItem = index;
    },
  },
};
</script>

<style scoped>
li::marker {
  background-color: rgb(37, 99, 235);
}
</style>
