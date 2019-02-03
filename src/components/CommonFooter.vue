<template>
  <footer class="footer">
    <div class="footer__wrap">
      <p>©{{ copy }}</p>
    </div>
  </footer>
</template>

<script>
export default {
  name: 'CommonFooter',
  props: {
    copy: String
  }
}
</script>

<style lang="scss">
  
</style>
