<template lang="pug">
  .nav-bar-main
    nav
      a( href='#' ) Home
      a( href='#' ) About  
      a( href='#' ) Product
      a( href='#' ) Contact
</template>

<script setup>

</script>

<style>
  .nav-bar-main { 
    nav a { 
      font-size: 1.1rem;
      color: grey;
      padding: 6px 20px;
    }

    & { 
      color: #1F51FF;
    }
  }
</style>