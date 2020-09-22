<template>
  <footer class="second-footer">
    <div class="columns">
      <div class="column has-text-white">
        <ul class="underline">
          <li class="footer-links">Legal</li>
          <li class="footer-links">Privacy</li>
          <li class="footer-links">Terms & condition</li>
          <li class="footer-links">Cookies</li>
          <li class="footer-links">Accessebility</li>
          <li class="footer-links">Sitemap</li>
        </ul>
      </div>
      <div class="column has-text-white">
        <ul class="underline">
          <li class="footer-links">Legal</li>
          <li class="footer-links">Privacy</li>
          <li class="footer-links">Terms & condition</li>
        </ul>
      </div>
    </div>
  </footer>
</template>
<script>
export default {
  name: "Footer",
};
</script>
<style scoped>
.footer {
  background-color: #086858;
}
.input {
  background-color: #085838;
  border: 0px;
}
.line {
  margin: 20px;
  width: 95%;
  background-color: darkgrey;
}
.columns {
  padding-left: 20px;
  padding-top: 60px;
}
li {
  line-height: 45px;
  font-size: 14px;
}
.links {
  font-size: 25px;
  font-weight: 100;
}
.second-footer {
  background-color: #024731;
  height: 29vh;
}
.underline {
  float: left;
}
.footer-links {
  display: inline-block;
  padding: 1.2rem;
}
</style>
