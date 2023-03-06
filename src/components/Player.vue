<template>
  <!-- 这里访问stream目录下的第一个分段 -->
  <video id="player" src="http://localhost:3000/stream/1" controls autoplay></video>
</template>

<script>
export default {
  name: "Player",
  async created() {
    console.log(this.$route.params.id);
  }
};
</script>