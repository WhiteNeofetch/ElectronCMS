<template>
  <div>
    <v-bottom-sheet></v-bottom-sheet>
    <Expansion_panels/>
    <Footers/>
    <Grid_system/>
    <Button_groups/>
    <Chip_groups/>
    <Item_groups/>
    <List_item_groups/>
    <Slide_groups/>
    <Windows/>
    <Hover/>
  </div>
</template>

<script>
import Expansion_panels from "../components/type3/Expansion_panels.vue";
import Footers from "../components/type3/Footers.vue";
import Grid_system from "../components/type3/Grid_system.vue";
import Button_groups from "../components/type3/Button_groups.vue";
import Chip_groups from "../components/type3/Chip_groups.vue";
import Item_groups from "../components/type3/Item_groups.vue";
import List_item_groups from "../components/type3/List_item_groups.vue";
import Slide_groups from "../components/type3/Slide_groups.vue";
import Windows from "../components/type3/Windows.vue";
import Hover from "../components/type3/Hover.vue";


export default {
  name: "Home",

  components: {
    Expansion_panels,
    Footers,
    Grid_system,
    Button_groups,
    Chip_groups,
    Item_groups,
    List_item_groups,
    Slide_groups,
    Windows,
    Hover
  },
};

</script>
