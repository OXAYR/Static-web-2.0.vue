<template>
  <div class="grid grid-cols-3 gap-10">
    <div v-for="x in 3" :key="x">
      <div class="text-left mt-10">
        <p class="text-xl text-blue-900">April4</p>
        <p class="text-blue-950 mt-5">
          The first day of the conference is focused on dark patterns for
          ecommerce.
        </p>
      </div>
      <div class="card mt-10">
        <ul class="divide-y divide-y-gray-400">
          <li v-for="y in 7" :key="y" class="p-10">
            <p class="text-blue-600">Steven Machail</p>
            <p class="text-blue-950">Not so one time payment</p>
            <p class="text-sm text-gray-400">9:00AM - 10:00AM PST</p>
          </li>
        </ul>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "LowerList",
};
</script>
