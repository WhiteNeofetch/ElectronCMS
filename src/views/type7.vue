<template>
  <div>
    <v-bottom-sheet></v-bottom-sheet>
    <Checkboxes/>
    <Combobox/>
    <File_inputs/>
    <Forms/>
    <Inputs/>
    <OTP_Input/>
    <Overflow_buttons/>
    <Radio_buttons/>
    <Range_Sliders/>
    <Selects/>
    <Sliders/>
    <Switches/>
    <Text_fields/>
  </div>
</template>

<script>
import Checkboxes from "../components/type7/Checkboxes.vue";
import Combobox from "../components/type7/Combobox.vue";
import File_inputs from "../components/type7/File_inputs.vue";
import Forms from "../components/type7/Forms.vue";
import Inputs from "../components/type7/Inputs.vue";
import OTP_Input from "../components/type7/OTP_Input.vue";
import Overflow_buttons from "../components/type7/Overflow_buttons.vue";
import Radio_buttons from "../components/type7/Radio_buttons.vue";
import Range_Sliders from "../components/type7/Range_Sliders.vue";
import Selects from "../components/type7/Selects.vue";
import Sliders from "../components/type7/Sliders.vue";
import Switches from "../components/type7/Switches.vue";
import Text_fields from "../components/type7/Text_fields.vue";

export default {
  name: "Home",

  components: {
    Checkboxes,
    Combobox,
    File_inputs,
    Forms,
    Inputs,
    OTP_Input,
    Overflow_buttons,
    Radio_buttons,
    Range_Sliders,
    Selects,
    Sliders,
    Switches,
    Text_fields
  },
};

</script>
