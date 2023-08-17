<template>
  <div class="grid grid-cols-2 flex-wrap rounded-xl border border-black py-20">
    <div class="gap-x-32 gap-y-14 ml-32">
      <p class="text-blue-600 text-5xl text-left">Stay up to date</p>
      <p class="text-blue-950 text-sm mt-5 text-left">
        Get updates on all of our events and be the first to get notified when
        tickets go on sale.
      </p>
    </div>
    <div class="ml-10">
      <p class="text-left mb-5 font-medium text-blue-950">
        Sign up to our newsletter ↓
      </p>
      <div class="border border-gray-400 rounded-2xl w-3/4 justify-between">
        <input
          type="text"
          class="rounded-2xl py-6 px-20"
          placeholder="Email Address"
        />
        <button class="bg-blue-600 px-5 py-4 rounded-2xl text-white">
          Signup Here
        </button>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "LowerContent",
};
</script>
