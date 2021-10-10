<template>
  <div class="main">
    <img alt="aps mockup" style="height: 400px" src="@/assets/mockup.png" />
    <div class="about">
      <h1>{{ msg }}</h1>
      <p>
        Android client for pass. Password Store aims to be a feature-complete
        client and implements most of its capabilities.
      </p>
    </div>
  </div>
</template>

<script>
export default {
  name: "HelloWorld",
  props: {
    msg: String,
  },
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.main {
  margin: 2rem 0;
  display: flex;
  flex-direction: row;
  justify-content: space-between;
  align-items: center;
}

.about {
  padding-left: 2rem;
}
</style>
