<template>
  <div id="app">
    <the-header />
    <div>
      <transition mode="out-in">
        <router-view class="container-view" />
      </transition>
    </div>
    <the-footer-vue />
  </div>
</template>

<script>
import TheFooterVue from "./components/TheFooter.vue";
import TheHeader from "./components/TheHeader.vue";

export default {
  data() {
    return {};
  },
  components: {
    TheHeader,
    TheFooterVue,
  },
};
</script>

<style>
@import url("https://cdn.jsdelivr.net/npm/bootstrap-icons@1.10.5/font/bootstrap-icons.css");
.botao-padrao {
  background-color: #b29463;
  color: black;
}
.botao-padrao:hover {
  background-color: #816d4f;
}
* {
  box-sizing: border-box;
}
.container-view {
  min-height: 100vh;
  flex: 1;
  margin-top: 100px;
}
input[type="checkbox"]:checked,
input[type="checkbox"]:focus {
  background-color: var(--marrom-claro);
  border-color: var(--marrom-claro);
  box-shadow: none;
  outline: none;
}
[data-bs-theme="dark"] {
  color: #f9f9f9;
}
[data-bs-theme="dark"] .card-body {
  --bs-card-color: #f9f9f9;
}
[data-bs-theme="dark"] .offcanvas {
  --bs-offcanvas-color: #f9f9f9;
}
[data-bs-theme="dark"] .accordion {
  --bs-body-color: #f9f9f9;
}
[data-bs-theme="dark"] .btn {
  --bs-body-color: #f9f9f9;
}
body {
  font-family: "Barlow", sans-serif;
  --bege: #e6e0d6;
  --marrom-escuro: #816d4f;
  --marrom-claro: #b29463;
}
body,
p,
a,
h1,
h2,
h3,
ul,
li {
  padding: 0px;
  margin: 0px;
}
ul {
  list-style: none;
}
a {
  text-decoration: none;
}
.v-enter,
.v-leave-to {
  opacity: 0;
}

.v-enter-active,
.v-leave-active {
  transition: all 0.3s;
}
</style>
