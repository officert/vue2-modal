<template src="./template.html">
</template>

<script>
export default {
  name: 'examples-width',
  data() {
    return {
      width: 600
    }
  },
  methods: {
    showModal() {
      this.$showModal({
        component: 'modal-1',
        height: 600,
        width: this.width,
        openOn: 'left'
      });
    }
  }
};
</script>

<style lang="less">
</style>
