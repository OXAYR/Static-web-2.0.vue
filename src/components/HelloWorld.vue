<template>
  <div class="flex flex-col gap-4 px-20 font-serif">
    <Header />
    <Banner />
    <p class="text-5xl text-left text-blue-600">Speakers</p>
    <p class="text-left text-xl">
      Learn from the experts on the cutting-edge of deception at the most
      sinister companies.
    </p>
    <List />
    <p class="text-5xl text-left w-3/4 flex-wrap text-blue-600 mt-24">
      Our three day schedule is jam-packed with brilliant, creative, evil
      geniuses.
    </p>
    <p class="text-left text-xl w-3/4 flex-wrap">
      The worst people in our industry giving the best talks you’ve ever seen.
      Nothing will be recorded and every attendee has to sign an NDA to watch
      the talks.
    </p>
    <LowerList />
    <div class="text-5xl text-blue-600 p-32">
      <p>Current sponsorships for our workshops and speakers.</p>
      <div class="grid grid-cols-3 w-full m-20">
        <img class="m-5" src="../assets/transistor.a1e38d49.svg" />
        <img class="m-5" src="../assets/laravel.6faebf7c.svg" />
        <img class="m-5" src="../assets/mirage.e12f40ad.svg" />
        <img class="m-5" src="../assets/statickit.2e06fcea.svg" />
        <img class="m-5" src="../assets/transistor.a1e38d49.svg" />
        <img class="m-5" src="../assets/tuple.2f54ed03.svg" />
      </div>
    </div>

    <footer></footer>
  </div>
</template>

<script>
import Header from "./Header.vue";
import Banner from "./Banner.vue";
import List from "./List.vue";
import LowerList from "./LowerList.vue";
export default {
  name: "Home",
  components: {
    Header,
    Banner,
    List,
    LowerList,
  },
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped></style>
