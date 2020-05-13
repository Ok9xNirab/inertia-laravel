<template>
  <layout>
    <div class="m-3">
      <h3>{{ message }}</h3>
    </div>
  </layout>
</template>

<script type="text/javascript">
import layout from "../components/layout";
export default {
  name: "welcome",
  props: ["message"],
  components: {
    layout
  }
};
</script>