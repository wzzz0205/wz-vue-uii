<template>
  <svg
    class="icon"
    aria-hidden="true"
    @click="handlerClick"
  >
    <use :xlink:href="IconName"></use>
  </svg>
</template>

<script>
import './assets/js/iconfont.js';

export default {
  name: 'WzIcon',
  props: {
    name: {
      type: String,
      default: ''
    }
  },
  mounted() {

  },
  computed: {
    IconName() {
      return `#icon-${this.name}`;
    }
  },
  methods: {
    handlerClick() {
      this.$emit('click');
    }
  }
};
</script>

<style lang="scss" scoped>
.icon {
  width: 1em;
  height: 1em;
  vertical-align: -0.15em;
  fill: currentColor;
  overflow: hidden;
}
</style>
