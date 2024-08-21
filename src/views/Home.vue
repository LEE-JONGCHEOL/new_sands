<!-- 메인 컴포넌트 -->
<template>
  <!-- <div class="bg-blue-500 text-white p-4"> -->
  <!-- hello world -->
  <!-- <Example /> -->
  <!-- </div> -->
  <mainslide />
  <sand />
  <!--<serviesolution />
  <technology />
  <issue />
  <inquiry /> -->
</template>

<script>
import Example from "@/components/common/Example.vue";
import Mainslide from "@/components/pages/home/mainslide.vue";
import Sand from "@/components/pages/home/sand.vue";
// import Serviesolution from "@/components/pages/home/serviesolution.vue";
// import Technology from "@/components/pages/home/technology.vue";
// import Issue from "@/components/pages/home/issue.vue";
// import Inquiry from "@/components/pages/home/inquiry.vue";

export default {
  name: "Home",

  components: {
    Example,
    Mainslide,
    Sand,
    // sand,
    // serviesolution,
    // technology,
    // issue,
    // inquiry,
  },
};
</script>
