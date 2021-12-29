<template>
  <div>
    <v-bottom-sheet></v-bottom-sheet>
    <Subheaders/>
    <Data_iterators/>
    <Simple_tables/>
    <Data_tables/>
    <Tabs/>
    <Timelines/>
    <Tooltips/>
    <Treeview/>
    <Virtual_scroller/>
    <Autocompletes/>
  </div>
</template>

<script>
import Subheaders from "../components/type6/Subheaders.vue";
import Data_iterators from "../components/type6/Data_iterators.vue";
import Simple_tables from "../components/type6/Simple_tables.vue";
import Data_tables from "../components/type6/Data_tables.vue";
import Tabs from "../components/type6/Tabs.vue";
import Timelines from "../components/type6/Timelines.vue";
import Tooltips from "../components/type6/Tooltips.vue";
import Treeview from "../components/type6/Treeview.vue";
import Virtual_scroller from "../components/type6/Virtual_scroller.vue";
import Autocompletes from "../components/type6/Autocompletes.vue";

export default {
  name: "Home",

  components: {
    Subheaders,
    Data_iterators,
    Simple_tables,
    Data_tables,
    Tabs,
    Timelines,
    Tooltips,
    Treeview,
    Virtual_scroller,
    Autocompletes
  },
};

</script>
