<template>
  <div class="edrea_tm_section animated" id="home">
    <div class="section_inner">
      <div class="edrea_tm_home">
        <h3 class="name">Supremacy <span class="coloring">Culture</span></h3>
        <h3 class="job">
          <AnimationText />
        </h3>
        <div class="edrea_tm_button transition_link">
          <a href="#contact" @click="navFuntions.activeSection('contact')"
            >START BUSINESS</a
          >
        </div>
      </div>
    </div>
  </div>
</template>

<script>
import { navFuntions } from "@/navFuntions";
import AnimationText from "./AnimationText.vue";

export default {
  name: `HomeComponent`,
  data() {
    return {
      navFuntions,
    };
  },
  components: { AnimationText },
};
</script>
