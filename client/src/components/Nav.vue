/* eslint-disable */
<template>
  <b-navbar toggleable="lg" type="dark" variant="info">
    <b-navbar-brand href="#">Markdown editor</b-navbar-brand>

    <b-navbar-toggle target="nav-collapse"></b-navbar-toggle>

    <b-collapse id="nav-collapse" is-nav>
      <b-navbar-nav>
        <b-nav-item href="/">Create new markdown</b-nav-item>
        <b-nav-item href="/list">Edit saved documents</b-nav-item>
        <b-nav-item href="/preview">Preview</b-nav-item>
      </b-navbar-nav>
    </b-collapse>
  </b-navbar>
</template>

<script>
    export default {
        name: "Nav"
    }
</script>

<style scoped>

</style>
