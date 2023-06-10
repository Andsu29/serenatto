<template>
  <div>
    <header>
      <nav class="navbar-expand-lg navbar bg-body-tertiary fixed-top">
        <div class="container-fluid">
          <router-link to="/" class="navbar-brand"
            ><img
              src="../assets/imgs/logo.png"
              alt="Logo da cafeteria Serenatto"
          /></router-link>
          <button
            class="navbar-toggler"
            type="button"
            data-bs-toggle="offcanvas"
            data-bs-target="#offcanvasNavbar"
            aria-controls="offcanvasNavbar"
            aria-label="Toggle navigation"
          >
            <span class="navbar-toggler-icon"></span>
          </button>
          <div
            class="offcanvas offcanvas-end"
            tabindex="-1"
            id="offcanvasNavbar"
            aria-labelledby="offcanvasNavbarLabel"
          >
            <div class="offcanvas-header">
              <h5 class="offcanvas-title" id="offcanvasNavbarLabel">
                <img
                  src="../assets/imgs/logo-mobile.png"
                  alt="Logo da cafeteria Serenatto"
                />
              </h5>
              <button
                type="button"
                class="btn-close"
                data-bs-dismiss="offcanvas"
                aria-label="Close"
              ></button>
            </div>
            <div class="offcanvas-body">
              <ul class="navbar-nav justify-content-end flex-grow-1 pe-3">
                <li class="nav-item">
                  <router-link
                    to="/"
                    class="nav-link active"
                    aria-current="page"
                    >Início</router-link
                  >
                </li>
                <li class="nav-item">
                  <router-link class="nav-link" to="/sobre">Sobre</router-link>
                </li>
                <li class="nav-item">
                  <a
                    data-bs-toggle="modal"
                    data-bs-target="#ModalForm"
                    class="nav-link"
                    href="/"
                    >Contato</a
                  >
                </li>
                <li class="nav-item">
                  <a class="nav-link" href="#"
                    ><div class="form-check form-switch">
                      <input
                        @click="modoNoturno"
                        class="form-check-input"
                        type="checkbox"
                        role="switch"
                        id="modo-noturno"
                      />
                      <label class="form-check-label" for="modo-noturno"
                        >Modo Noturno</label
                      >
                    </div></a
                  >
                </li>
              </ul>
            </div>
          </div>
        </div>
      </nav>
    </header>
    <!-- ModalForm -->
    <div
      class="modal fade"
      id="ModalForm"
      tabindex="-1"
      aria-labelledby="exampleModalLabel"
      aria-hidden="true"
    >
      <div class="modal-dialog">
        <div class="modal-content">
          <div class="modal-header">
            <h1 class="modal-title fs-5" id="exampleModalLabel">Contato</h1>
            <button
              type="button"
              class="btn-close"
              data-bs-dismiss="modal"
              aria-label="Close"
            ></button>
          </div>
          <div class="modal-body">
            <the-form-vue />
          </div>
          <div class="modal-footer">
            <button
              type="button"
              class="btn btn-secondary"
              data-bs-dismiss="modal"
            >
              Fechar
            </button>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
import TheFormVue from "@/components/TheForm.vue";

export default {
  name: "HomeView",
  data() {
    return {
      modalForm: false,
    };
  },
  components: {
    TheFormVue,
  },
  methods: {
    modoNoturno() {
      const inputCheck = document.querySelector("#modo-noturno");
      const elemento = document.querySelector("body");
      const modo = inputCheck.checked ? "dark" : "light";
      elemento.setAttribute("data-bs-theme", modo);
    },
  },
};
</script>

<style scoped>
#flexSwitchCheckDefault {
  background-color: var(--marrom-claro);
  border-color: var(--marrom-claro);
  box-shadow: none;
  outline: none;
}
</style>
