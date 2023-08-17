<template>
  <div class="flex flex-col gap-4 font-serif">
    <div class="relative bg-indigo-50">
      <div class="absolute inset-0 z-0">
        <img
          src="../assets/background.jpg"
          alt="background"
          class="w-full h-full max-w-md"
        />
      </div>
      <div class="relative px-20 z-10">
        <Header />
        <Banner />
      </div>
    </div>

    <p class="text-4xl text-left text-blue-600 px-20 pt-20">Speakers</p>
    <p class="text-left text-xl px-20">
      Learn from the experts on the cutting-edge of deception at the most
      sinister companies.
    </p>
    <List class="px-20" />
    <p class="text-4xl text-left w-3/4 flex-wrap text-blue-600 mt-24 px-20">
      Our three day schedule is jam-packed with brilliant, creative, evil
      geniuses.
    </p>
    <p class="text-left text-xl w-3/4 flex-wrap px-20 pb-10">
      The worst people in our industry giving the best talks you’ve ever seen.
      Nothing will be recorded and every attendee has to sign an NDA to watch
      the talks.
    </p>
    <div class="relative bg-indigo-50">
      <div class="absolute inset-0 z-0">
        <img
          src="../assets/background.jpg"
          alt="background"
          class="w-full h-full max-w-md"
        />
      </div>
      <div class="relative px-20 z-10 pb-20">
        <LowerList />
      </div>
    </div>
    <div class="px-20">
      <LowerBanner />
      <LowerContent />
    </div>
    <Footer class="px-20" />
  </div>
</template>

<script>
import Header from "./Header.vue";
import Banner from "./Banner.vue";
import List from "./List.vue";
import LowerList from "./LowerList.vue";
import LowerBanner from "./LowerBanner.vue";
import LowerContent from "./LowerContent.vue";
import Footer from "./Footer.vue";
export default {
  name: "Home",
  components: {
    Header,
    Banner,
    List,
    LowerList,
    LowerBanner,
    LowerContent,
    Footer,
  },
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped></style>
