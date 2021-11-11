<template>
  <header id="site_header">
    <Logo />
    <!-- /.logo -->
    <div class="main_menu">
      <a href="#">Home</a>
      <a href="#" class="active">Prodotti</a>
      <a href="#">Chi siamo</a>
      <a href="#">Contatti</a>
    </div>
    <!-- /.main_menu -->
  </header>
  <!-- /#site_header -->
</template>

<script>
import Logo from "@/components/Logo.vue";
export default {
  name: "App",
  components: {
    Logo,
  },
};
</script>

<style lang="scss">
#site_header {
  text-align: center;
  /* .logo {
  } */
  .main_menu {
    margin: 2rem 0;
    a {
      padding: 1rem;
      text-decoration: none;
      color: black;
      &.active {
        background-color: #dae9fe;
      }
      &:hover {
        text-decoration: underline;
        color: cornflowerblue;
      }
    }
  }
}
</style>