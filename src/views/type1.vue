<template>
  <div>
    <v-bottom-sheet></v-bottom-sheet>
    <Alerts />
    <Application />
    <Aspect_ratios />
    <Avatars />
    <Badges />
    <Banners />
    <App_bars />
    <System_Bars />
    <Bottom_navigation />
    <Toolbars />
  </div>
</template>

<script>
import Alerts from "../components/type1/Alerts.vue";
import Aspect_ratios from "../components/type1/Aspect_ratios.vue";
import Avatars from "../components/type1/Avatars.vue";
import Badges from "../components/type1/Badges.vue";
import Banners from "../components/type1/Banners.vue";
import App_bars from "../components/type1/App_bars.vue";
import System_Bars from "../components/type1/System_Bars.vue";
import Bottom_navigation from "../components/type1/Bottom_navigation.vue";
import Toolbars from "../components/type1/Toolbars.vue";
import Application from "../components/type1/Application.vue";

export default {
  name: "Home",

  components: {
    Alerts,
    Application,
    Aspect_ratios,
    Avatars,
    Badges,
    Banners,
    App_bars,
    System_Bars,
    Bottom_navigation,
    Toolbars,
  },
};
</script>
