<template>
  <div>
    <h1>Switch 组件</h1>
    <Demo :src="SwitchDemo1"/>
    <Demo :src="SwitchDemo2"/>
  </div>
</template>
<script lang="ts">
import SwitchDemo1 from "../demo/switch/demo1.vue";
import SwitchDemo2 from "../demo/switch/demo2.vue";
import { ref } from "vue";
export default {
  setup() {
    return { SwitchDemo1, SwitchDemo2 };
  },
};
</script>
