<template>
  <div id="app">
    <pagefirst />
    <pagesecond msg="this is props value" />
    <Events/>
    <Conditional/>
  </div>
</template>

<script>
import pagefirst from "./components/props/pagefirst.vue";
import pagesecond from "./components/props/pagesecond.vue";
 import Events from "./components/3/Events.vue"
import Conditional from "./components/4/Conditional.vue"
export default {
  name: "app",
  components: {
    pagefirst,
    pagesecond,
    Events, 
    Conditional
  },

};
</script>