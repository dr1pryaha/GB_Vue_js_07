<template>
  <div class="btn">ADD NEW +</div>
</template>

<script>
export default {
  name: "AddButton",
  // methods: {
  //   onBtnClick() {
  //     this.$store.commit("setIsPopupActive", !this.$store.state.isPopupActive);
  //   },
  // },
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
.btn {
  background-color: cadetblue;
  border: 1px solid cadetblue;
  border-radius: 3px;
  color: white;
  padding: 7px 25px;
  display: inline-block;
  cursor: pointer;
  transition: 0.3s;

  &:hover {
    background-color: transparent;
    color: cadetblue;
  }
}
</style>
