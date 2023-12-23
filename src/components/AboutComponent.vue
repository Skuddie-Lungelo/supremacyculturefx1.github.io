<template>
  <div class="edrea_tm_section" id="about">
    <div class="section_inner">
      <div class="edrea_tm_about">
        <div class="left">
          <div class="image">
            <img src="img/thumbs/1-1.jpg" alt="" />
            <div class="main" data-img-url="img/about/1.jpg"></div>
          </div>
        </div>
        <div class="right">
          <div class="short">
            <h3 class="name">Supremacy <span class="coloring">Culture</span></h3>
            <h3 class="job">
              <AnimationText />
            </h3>
          </div>
          <div class="text">
            <p>
              Welcome to <span>Supremacy Culture Fx.</span> Our community believes that <span class="coloring">Trading</span>
              not just a hobby or a casual pursuit, instead it is a serious business tha demands the right knowledge,skillset 
              and strategy. We are here to guide you on your journey from a novice trader to a professional trader, running your Trading
              endevavors as a thriving business.
            </p>
          </div>
          <div class="edrea_tm_button" id="aboutPopup">
            <a href="#">Start Business</a>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
import AnimationText from "./AnimationText.vue";
export default {
  name: `AboutComponent`,
  data() {
    return {
      open: false,
    };
  },
  components: {
    AnimationText,
  },
};
</script>

<style scoped>
.edrea_tm_modalbox {
  top: -90px;
}
</style>
