<template>
  <div class="dizme_tm_all_wrap" data-magic-cursor="show">
    <MobileHeaderVue />
    <HeaderVue />
    <HomeComponent />
    <!-- HERO -->

    <!-- PROCESS -->
    <ProcessComponent />
    <!-- /PROCESS -->

    <!-- ABOUT -->
    <AboutComponent />
    <!-- /ABOUT -->

    <!-- PORTFOLIO -->
    <PortfolioComponent />
    <!-- /PORTFOLIO -->

    <!-- SKILLS -->
    <SkillComponent />
    <!-- /SKILLS -->

    <!-- SERVICES -->
    <ServiceCompoent />
    <!-- /SERVICES -->

    <!-- TESTIMONIALS -->
    <TestimonialsComponent />
    <!-- /TESTIMONIALS -->

    <!-- PARTNERS -->
    <PartnersComponent />
    <!-- /PARTNERS -->

    <!-- NEWS -->
    <NewsComponent />
    <!-- /NEWS -->

    <!-- SUBSCRIBE -->
    <SubscribeComponent />
    <!-- /SUBSCRIBE -->

    <!-- CONTACT -->
    <ContactComponent />
    <!-- /CONTACT -->

    <!-- COPYRIGHT -->
    <CopyrightComponent />
    <!-- /COPYRIGHT -->

    <ScrollTopVue />
  </div>
</template>

<script>
import HeaderVue from "@/components/layout/Header.vue";
import MobileHeaderVue from "@/components/layout/MobileHeader.vue";
import ScrollTopVue from "@/components/layout/ScrollTop.vue";
import { activeSkillProgress } from "@/utilits";
import CopyrightComponent from "../components/CopyrightComponent.vue";
import HomeComponent from "../components/HomeComponent.vue";
import NewsComponent from "../components/NewsComponent.vue";
import PortfolioComponent from "../components/PortfolioComponent.vue";
import ServiceCompoent from "../components/ServiceCompoent.vue";
import TestimonialsComponent from "../components/TestimonialsComponent.vue";

export default {
  name: "IndexView",
  components: {
    HomeComponent,
    PortfolioComponent,
    ServiceCompoent,
    TestimonialsComponent,
    NewsComponent,
    CopyrightComponent,
    HeaderVue,
    MobileHeaderVue,
    ScrollTopVue,
  },
  mounted() {
    window.addEventListener("scroll", activeSkillProgress);
  },
};
</script>
