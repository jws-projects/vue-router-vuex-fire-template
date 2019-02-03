<template>
  <header class="header">
    <div class="header__wrap">
      <h1 class="header__logo">{{siteName}}</h1>
      <nav class="header__nav">
        <ul>
          <li>
            <router-link to="/">Home</router-link>
          </li>
          <li>
            <router-link to="/about">About</router-link>
          </li>
        </ul>
      </nav>
    </div>
  </header>
</template>

<script>
export default {
  name: 'CommonHeader',
  props: {
    siteName: String
  }
}
</script>

<style lang="scss">

</style>
