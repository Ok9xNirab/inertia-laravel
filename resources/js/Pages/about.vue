<template>
  <layout>
    <div class="m-3">{{message}}</div>
  </layout>
</template>

<script>
import layout from "../components/layout";
export default {
  name: "about",
  props: ["message"],
  components: {
    layout
  }
};
</script>