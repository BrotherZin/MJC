<template>
  <div class="header">
    <v-layout
      ><div class="logo" @click="moveMain">
        이랏샤이마세 ~ 고레와 안형진 게시판 데스 !
      </div>
      <v-spacer></v-spacer>
      <div>안형진</div></v-layout
    >
  </div>
</template>

<script>
export default {
  methods: {
    moveMain() {
      this.$router.push("/board");
    },
  },
};
</script>

<style scoped>
.header {
  padding: 10px 20px;
  box-shadow: 0 6px #eee;
}
.header .logo {
  cursor: pointer;
}
</style>