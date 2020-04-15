<template>
  <div>
    <div>Download</div>
    <div class="back" @click="back">back home</div>
  </div>
</template>

<script>
export default {
  name: 'Download',
  methods: {
    back () {
      this.$router.push('/');
    }
  }
};
</script>

<style lang="scss">
$red: #f00;

.back {
  color: $red;
  cursor: pointer;
}
</style>
