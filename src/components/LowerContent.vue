<template>
  <div>
    <div class="relative bg-indigo-50 rounded-xl">
      <div class="absolute inset-0 z-0 justify-end">
        <img
          src="../assets/background.jpg"
          alt="background"
          class="w-full h-full max-w-md rounded-xl"
        />
      </div>
      <div class="relative z-10">
        <div class="grid grid-cols-2 flex-wrap rounded-xl py-20">
          <div class="gap-x-32 gap-y-14 ml-32">
            <p class="text-blue-600 text-5xl text-left">Stay up to date</p>
            <p class="text-blue-950 text-sm mt-5 text-left">
              Get updates on all of our events and be the first to get notified
              when tickets go on sale.
            </p>
          </div>
          <div class="ml-10">
            <p class="text-left mb-5 font-medium text-blue-950">
              Sign up to our newsletter ↓
            </p>
            <div class="bg-white rounded-2xl w-3/4 justify-between">
              <input
                type="text"
                class="rounded-2xl py-6 w-80 outline-none"
                placeholder="Email Address"
              />
              <button class="bg-blue-600 px-5 py-4 rounded-2xl text-white">
                Signup Here
              </button>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "LowerContent",
};
</script>
