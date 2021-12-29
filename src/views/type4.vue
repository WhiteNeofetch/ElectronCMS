<template>
  <div>
    <v-bottom-sheet></v-bottom-sheet>
    <Images/>
    <Lazy/>
    <Icons/>
    <Lists/>
    <Menus/>
    <Navigation_drawers/>
    <Overlays/>
    <Parallax/>
    <Color_pickers/>
    <Date_pickers/>
  </div>
</template>

<script>
import Icons from "../components/type4/Icons.vue";
import Images from "../components/type4/Images.vue";
import Lazy from "../components/type4/Lazy.vue";
import Lists from "../components/type4/Lists.vue";
import Menus from "../components/type4/Menus.vue";
import Navigation_drawers from "../components/type4/Navigation_drawers.vue";
import Overlays from '../components/type4/Overlays.vue';
import Parallax from '../components/type4/Parallax.vue';
import Color_pickers from '../components/type4/Color_pickers.vue';
import Date_pickers from '../components/type4/Date_pickers.vue';

export default {
  name: "Home",

  components: {
    Icons,
    Images,
    Lazy,
    Lists,
    Menus,
    Navigation_drawers,
    Overlays,
    Parallax,
    Color_pickers,
    Date_pickers
  },
};

</script>
