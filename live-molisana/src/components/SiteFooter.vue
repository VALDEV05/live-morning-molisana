<template>
  <footer id="site_footer">
    <div class="container">
      <div class="row">
        <div class="col-4">
          <Logo />
        </div>
        <div class="col-4">
          <ul>
            <h3>Pastificio</h3>
            <li><a href="#">Lorem</a></li>
            <li><a href="#">Eius</a></li>
            <li><a href="#">Mollitia</a></li>
            <li><a href="#">Quidem</a></li>
            <li><a href="#">Ratione</a></li>
          </ul>
        </div>
        <div class="col-4">
          <h3>prodotti</h3>
          <ul>
            <li><a href="#">Lorem</a></li>
            <li><a href="#">Eius</a></li>
            <li><a href="#">Mollitia</a></li>
            <li><a href="#">Quidem</a></li>
            <li><a href="#">Ratione</a></li>
          </ul>
        </div>
      </div>
    </div>
  </footer>
</template>
<script>
import Logo from "@/components/Logo.vue";
export default {
  components: {
    Logo,
  },
};
</script>
<style lang="scss">
//molisana_primary_color
@import "../assets/scss/variables.scss";

#site_footer {
  height: 450px;
  padding-top: 2rem;
  background-image: url("../assets/footer-montagne-bottom.jpg");
  background-position-y: bottom;
  background-repeat: no-repeat;
  h3 {
    padding: 1rem 0;
    text-transform: uppercase;
    color: $molisana_primary_color;
  }
  ul {
    list-style: none;
    a {
      text-decoration: none;
      color: black;
    }
  }
}
</style>