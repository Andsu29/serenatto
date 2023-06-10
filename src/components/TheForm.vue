<template>
  <div>
    <section class="py-2">
      <div class="row">
        <div class="mx-auto">
          <div class="border border-2 rounded p-3">
            <h3 class="fw-bold p-3">Entre em contato!</h3>
            <form id="contato">
              <div class="form-floating mb-3">
                <input
                  type="text"
                  class="form-control"
                  id="floatingNome"
                  placeholder="nome"
                />
                <label for="floatingNome">Nome</label>
              </div>
              <div class="form-floating mb-3">
                <input
                  type="email"
                  class="form-control"
                  id="floatingEmail"
                  placeholder="name@example.com"
                />
                <label for="floatingEmail">Email</label>
              </div>
              <div class="form-floating mb-3">
                <input
                  type="number"
                  class="form-control"
                  id="floatingTelefone"
                  placeholder="telefone"
                />
                <label for="floatingTelefone">Telefone</label>
              </div>
              <select
                class="form-select mb-3"
                aria-label="Default select example"
              >
                <option selected>Preferência de contato:</option>
                <option value="1">Email</option>
                <option value="2">WhatsApp</option>
                <option value="3">Ligação</option>
              </select>
              <label for="nivel-satisfacao" class="form-label"
                >Nível de satisfação</label
              >
              <input
                type="range"
                class="form-range input-range"
                id="nivel-satisfacao"
              />
              <div class="form-check">
                <input
                  class="form-check-input"
                  type="checkbox"
                  value=""
                  id="flexCheckDefault"
                />
                <label class="form-check-label" for="flexCheckDefault">
                  Deseja receber novidades por email?
                </label>
              </div>
              <button
                type="button"
                class="btn botao-padrao w-100 p-3 fw-bold mt-3 py-3"
              >
                Enviar
              </button>
            </form>
          </div>
        </div>
      </div>
    </section>
  </div>
</template>

<script>
export default {};
</script>

<style scoped>
.input-range::-webkit-slider-thumb {
  background-color: #b29463;
}
.botao-padrao {
  background-color: #b29463;
  color: black;
}
.botao-padrao:hover {
  background-color: #816d4f;
}
</style>
