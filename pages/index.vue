<template>
  <main>
    <h1>Splittext bug</h1>
    <div ref="typewriter">Splittext bug typewriter</div>
  </main>
</template>

<script>
export default {
  name: "IndexPage",
  created() {
    const line = new this.$SplitText(this.$refs.typewriter, {
      type: "words",
      position: "absolute",
    });
    /*
    const line = new this.$SplitText(this.$refs.typewriter, {
      type: "words",
      position: "absolute",
    });
    */
  },
};
</script>
