<template>
  <div class="flex flex-col flex-wrap items-center p-32 gap-10">
    <div class="w-3/4">
      <p class="font-bold text-6xl text-blue-600 w-full text-left">
        A design conference for the dark side.
      </p>
    </div>
    <div class="text-left w-3/4 font-medium text-lg text-blue-950">
      <p>
        The next generation of web users are tech-savvy and suspicious. They
        know how to use dev tools, they can detect a phishing scam from a mile
        away , and they certainly aren’t accepting any checks from Western
        Union.
      </p>
      <p class="mt-4 text-blue-950">
        At DeceptiConf you’ll learn about the latest dark patterns being
        developed to trick even the smartest visitors, and you’ll learn how to
        deploy them without ever being detected.
      </p>
    </div>
    <div class="flex gap-x-32 flex-wrap list-none text-left">
      <li>
        <span class="text-sm text-blue-600">Speakers </span>
        <p class="text-2xl font-medium text-blue-950">18</p>
      </li>
      <li>
        <span class="text-sm text-blue-600">People Attending </span>
        <p class="text-2xl font-medium text-blue-950">2,091</p>
      </li>
      <li>
        <span class="text-sm text-blue-600">Venue </span>
        <p class="text-2xl font-medium text-blue-950">Staples Center</p>
      </li>
      <li>
        <span class="text-sm text-blue-600">Location </span>
        <p class="text-2xl font-medium text-blue-950">Los Angeles</p>
      </li>
    </div>
  </div>
</template>

<script>
export default {
  name: "Banner",
};
</script>
