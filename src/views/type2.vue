<template>
  <div>
    <v-bottom-sheet></v-bottom-sheet>
    <Bottom_sheets />
    <Breadcrumbs/>
    <Buttons/>
    <Buttons_Floating_Action_Button/>
    <Calendars/>
    <Cards/>
    <Carousels/>
    <Chips/>
    <Dialogs/>
    <Dividers/>
  </div>
</template>

<script>
import Bottom_sheets from "../components/type2/Bottom_sheets.vue";
import Breadcrumbs from "../components/type2/Breadcrumbs.vue"
import Buttons from "../components/type2/Buttons.vue"
import Buttons_Floating_Action_Button from "../components/type2/Buttons_Floating_Action_Button.vue"
import Calendars from "../components/type2/Calendars.vue"
import Cards from "../components/type2/Cards.vue"
import Carousels from "../components/type2/Carousels.vue"
import Chips from "../components/type2/Chips.vue"
import Dialogs from "../components/type2/Dialogs.vue"
import Dividers from "../components/type2/Dividers.vue"
   


export default {
  name: "Home",

  components: {
   Bottom_sheets,
   Breadcrumbs,
   Buttons,
   Buttons_Floating_Action_Button,
   Calendars,
   Cards,
   Carousels,
   Chips,
   Dialogs,
   Dividers
  },
};

</script>
