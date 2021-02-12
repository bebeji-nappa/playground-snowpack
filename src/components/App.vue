<template>
  <h1 class="red">Hello {{ snowpack }}</h1>
  <div class="blue"><p>Playground Snowpack</p></div>
</template>

<script>
export default {
  data() {
    return {
      snowpack: "Snowpack"
    }
  }
}
</script>
<style lang="scss" scoped>
.red {
  color: #ff0000;
}
.blue {
  color: #0000ff;
  p {
    font-size: small;
  }
}
</style>
