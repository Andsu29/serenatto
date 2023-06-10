<template>
  <div>
    <section class="py-5">
      <h2 class="text-center fw-bold pb-1">Nossos serviços</h2>

      <div class="container d-flex justify-content-around flex-wrap">
        <div class="card m-4" style="width: 20rem">
          <img
            src="../assets/imgs/cafe-card.png"
            class="card-img-top"
            alt="Balcão de padaria tradicional com alimentos diversos"
          />
          <div class="card-body">
            <h5 class="card-title py-2 fw-bold">Café & Bistrô</h5>
            <p class="card-text">
              Nosso bistrô oferece uma ampla variedade de cafés, smoothies,
              deliciosos salgados e sobremesas. Uma excelente opção para quem
              busca um lugar tranquilo e aconchegante.
            </p>
            <a
              href="#"
              class="btn botao-padrao w-100 fw-bold"
              data-bs-toggle="offcanvas"
              data-bs-target="#canvas-1"
              aria-controls="offcanvasRight"
              >Quero detalhes</a
            >
          </div>
        </div>

        <div class="card m-4" style="width: 20rem">
          <img
            src="../assets/imgs/buffet-card.png"
            class="card-img-top"
            alt="Mesa de buffet com alimentos diversos"
          />
          <div class="card-body">
            <h5 class="card-title fw-bold">Buffet</h5>
            <p class="card-text">
              Buffet e catering personalizado para eventos, produções e
              celebrações. Com um menu variado e adaptável às preferências do
              cliente, atendimento atencioso e profissional.
            </p>
            <a
              href="#"
              class="btn botao-padrao w-100 fw-bold mt-3"
              data-bs-toggle="offcanvas"
              data-bs-target="#canvas-2"
              aria-controls="offcanvasRight"
              >Quero detalhes</a
            >
          </div>
        </div>

        <div class="card m-4" style="width: 20rem">
          <img
            src="../assets/imgs/delivery-card.png"
            class="card-img-top"
            alt="Caixa aberta armazenando comidas diversas"
          />
          <div class="card-body">
            <h5 class="card-title fw-bold">Delivery</h5>
            <p class="card-text">
              Para quem deseja desfrutar no conforto de casa, oferecemos
              delivery dos produtos. Com o mesmo cardápio variado de sempre, sem
              perder nosso sabor e padrão de qualidade.
            </p>
            <a
              href="#"
              class="btn botao-padrao w-100 fw-bold mt-3"
              data-bs-toggle="offcanvas"
              data-bs-target="#canvas-3"
              aria-controls="offcanvasRight"
              >Quero detalhes</a
            >
          </div>
        </div>
      </div>
    </section>
    <!-- Canvas 1 -->
    <div
      class="offcanvas offcanvas-end"
      tabindex="-1"
      id="canvas-1"
      aria-labelledby="offcanvasRightLabel"
    >
      <div class="offcanvas-header">
        <h5 class="offcanvas-title" id="offcanvasRightLabel">Café & Bistrô</h5>
        <button
          type="button"
          class="btn-close"
          data-bs-dismiss="offcanvas"
          aria-label="Close"
        ></button>
      </div>
      <div class="offcanvas-body">
        <div class="accordion" id="accordionExample">
          <div class="accordion-item">
            <h2 class="accordion-header">
              <button
                class="accordion-button botao-padrao"
                type="button"
                data-bs-toggle="collapse"
                data-bs-target="#collapseOne"
                aria-expanded="true"
                aria-controls="collapseOne"
              >
                Café
              </button>
            </h2>
            <div
              id="collapseOne"
              class="accordion-collapse collapse show"
              data-bs-parent="#accordionExample"
            >
              <div class="accordion-body">
                Temos um excelente espaço para alimentação e descanso, com a
                vitrine recheada de doces, salgados, cafés tradicionais e
                especiais para desfrutar seus melhores momentos.
              </div>
            </div>
          </div>
          <div class="accordion-item">
            <h2 class="accordion-header">
              <button
                class="accordion-button collapsed botao-padrao"
                type="button"
                data-bs-toggle="collapse"
                data-bs-target="#collapseTwo"
                aria-expanded="false"
                aria-controls="collapseTwo"
              >
                Bistrô
              </button>
            </h2>
            <div
              id="collapseTwo"
              class="accordion-collapse collapse"
              data-bs-parent="#accordionExample"
            >
              <div class="accordion-body">
                Além de cafés o dia todo, oferecemos refeições em horário de
                almoço (11 às 15h) com pratos deliciosos de bistrô!
              </div>
            </div>
          </div>
          <div class="accordion-item">
            <h2 class="accordion-header">
              <button
                class="accordion-button collapsed botao-padrao"
                type="button"
                data-bs-toggle="collapse"
                data-bs-target="#collapseThree"
                aria-expanded="false"
                aria-controls="collapseThree"
              >
                Coworking
              </button>
            </h2>
            <div
              id="collapseThree"
              class="accordion-collapse collapse"
              data-bs-parent="#accordionExample"
            >
              <div class="accordion-body">
                Temos espaço adequado para trabalho, com conexão de internet de
                alta velocidade e instalações confortáveis para reuniões.
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
    <!-- Canvas 2 -->
    <div
      class="offcanvas offcanvas-end"
      tabindex="-1"
      id="canvas-2"
      aria-labelledby="offcanvasRightLabel"
    >
      <div class="offcanvas-header">
        <h5 class="offcanvas-title" id="offcanvasRightLabel">Buffet</h5>
        <button
          type="button"
          class="btn-close"
          data-bs-dismiss="offcanvas"
          aria-label="Close"
        ></button>
      </div>
      <div class="offcanvas-body">
        <div class="accordion" id="accordionExample">
          <div class="accordion-item">
            <h2 class="accordion-header">
              <button
                class="accordion-button botao-padrao"
                type="button"
                data-bs-toggle="collapse"
                data-bs-target="#collapseOne"
                aria-expanded="true"
                aria-controls="collapseOne"
              >
                Eventos
              </button>
            </h2>
            <div
              id="collapseOne"
              class="accordion-collapse collapse show"
              data-bs-parent="#accordionExample"
            >
              <div class="accordion-body">
                Organizamos buffet com cardápios variados e personalizados para
                casamentos, festas de aniversário e outros eventos!
              </div>
            </div>
          </div>
          <div class="accordion-item">
            <h2 class="accordion-header">
              <button
                class="accordion-button collapsed botao-padrao"
                type="button"
                data-bs-toggle="collapse"
                data-bs-target="#collapseTwo"
                aria-expanded="false"
                aria-controls="collapseTwo"
              >
                Catering
              </button>
            </h2>
            <div
              id="collapseTwo"
              class="accordion-collapse collapse"
              data-bs-parent="#accordionExample"
            >
              <div class="accordion-body">
                Oferecemos serviço de alimentação variada para coffee breaks,
                produções e bastidores.
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
    <!-- Canvas 3 -->
    <div
      class="offcanvas offcanvas-end"
      tabindex="-1"
      id="canvas-3"
      aria-labelledby="offcanvasRightLabel"
    >
      <div class="offcanvas-header">
        <h5 class="offcanvas-title" id="offcanvasRightLabel">Delivery</h5>
        <button
          type="button"
          class="btn-close"
          data-bs-dismiss="offcanvas"
          aria-label="Close"
        ></button>
      </div>
      <div class="offcanvas-body">
        <div class="accordion" id="accordionExample">
          <div class="accordion-item">
            <h2 class="accordion-header">
              <button
                class="accordion-button botao-padrao"
                type="button"
                data-bs-toggle="collapse"
                data-bs-target="#collapseOne"
                aria-expanded="true"
                aria-controls="collapseOne"
              >
                Encomendas para eventos
              </button>
            </h2>
            <div
              id="collapseOne"
              class="accordion-collapse collapse show"
              data-bs-parent="#accordionExample"
            >
              <div class="accordion-body">
                Produzimos e entregamos os itens de café de nosso cardápio em
                grandes quantidades para seus eventos! Basta entrar em contato e
                fazer a reserva com 72h de antecedência.
              </div>
            </div>
          </div>
          <div class="accordion-item">
            <h2 class="accordion-header">
              <button
                class="accordion-button collapsed botao-padrao"
                type="button"
                data-bs-toggle="collapse"
                data-bs-target="#collapseTwo"
                aria-expanded="false"
                aria-controls="collapseTwo"
              >
                Entrega por aplicativo
              </button>
            </h2>
            <div
              id="collapseTwo"
              class="accordion-collapse collapse"
              data-bs-parent="#accordionExample"
            >
              <div class="accordion-body">
                Entregamos pelos aplicativos Ifood e Rappi. Consulte nosso
                cardápio por lá e faça seu pedido!
              </div>
            </div>
          </div>
          <div class="accordion-item">
            <h2 class="accordion-header">
              <button
                class="accordion-button collapsed botao-padrao"
                type="button"
                data-bs-toggle="collapse"
                data-bs-target="#collapseThree"
                aria-expanded="false"
                aria-controls="collapseThree"
              >
                Coworking
              </button>
            </h2>
            <div
              id="collapseThree"
              class="accordion-collapse collapse"
              data-bs-parent="#accordionExample"
            >
              <div class="accordion-body">
                Temos espaço adequado para trabalho, com conexão de internet de
                alta velocidade e instalações confortáveis para reuniões.
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style scoped>
.botao-padrao {
  background-color: var(--marrom-claro);
}
.botao-padrao:hover {
  background-color: var(--marrom-escuro);
}
</style>
