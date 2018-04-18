<template>
    <div>
        this is test
    </div>
</template>
<script>
export default {
  data() {
    return {};
  },
  components: {},
  mounted() {
    // this.initMap();
    this.init();
  },
  methods: {
    init: function() {
      this.$http.post("/api").then(ret => {
        console.log(ret);
      });
    }
  }
};
</script>
<style>

</style>

