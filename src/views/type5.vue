<template>
  <div>
    <v-bottom-sheet></v-bottom-sheet>
    <Date_pickers_month/>
    <Time_pickers/>
    <Progress_circular/>
    <Progress_linear/>
    <Ratings/>
    <Sheets/>
    <Skeleton_loaders/>
    <Snackbars/>
    <Sparklines/>
    <Steppers/>
  </div>
</template>

<script>
import Date_pickers_month from "../components/type5/Date_pickers_month.vue";
import Time_pickers from "../components/type5/Time_pickers.vue";
import Progress_circular from "../components/type5/Progress_circular.vue";
import Progress_linear from "../components/type5/Progress_linear.vue";
import Ratings from "../components/type5/Ratings.vue";
import Sheets from "../components/type5/Sheets.vue";
import Skeleton_loaders from "../components/type5/Skeleton_loaders.vue";
import Snackbars from "../components/type5/Snackbars.vue";
import Sparklines from "../components/type5/Sparklines.vue";
import Steppers from "../components/type5/Steppers.vue";


export default {
  name: "Home",

  components: {
    Date_pickers_month,
    Time_pickers,
    Progress_circular,
    Progress_linear,
    Ratings,
    Sheets,
    Skeleton_loaders,
    Snackbars,
    Sparklines,
    Steppers
  },
};

</script>
