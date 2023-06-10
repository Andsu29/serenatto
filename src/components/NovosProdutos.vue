<template>
  <div>
    <section class="py-5">
      <h2 class="fw-bold text-center pb-1">Nossos Produtos</h2>
      <div class="row mx-auto">
        <div class="col-12 col-md-6 col-lg-4">
          <div
            class="card border-0 btn mx-auto"
            style="width: 18rem"
            data-bs-toggle="modal"
            data-bs-target="#modal-1"
          >
            <img
              src="../assets/imgs/produtos-cafe-tradicional.png"
              class="card-img-top"
              alt="Xícara de café preto"
            />
            <div class="card-body text-center">
              <h3 class="card-text fw-bold">Cafés tradicionais</h3>
            </div>
          </div>
        </div>
        <div class="col-12 col-md-6 col-lg-4">
          <div
            data-bs-toggle="modal"
            data-bs-target="#modal-2"
            class="card border-0 btn mx-auto"
            style="width: 18rem"
          >
            <img
              src="../assets/imgs/produtos-cafe-especial.png"
              class="card-img-top"
              alt="Xícara de café preto"
            />
            <div class="card-body text-center">
              <h3 class="card-text fw-bold">Cafés tradicionais</h3>
            </div>
          </div>
        </div>
        <div class="col-12 col-md-6 col-lg-4">
          <div class="card border-0 btn mx-auto" style="width: 18rem">
            <img
              src="../assets/imgs/produtos-vitaminas.png"
              class="card-img-top"
              alt="Xícara de café preto"
            />
            <div class="card-body text-center">
              <h3 class="card-text fw-bold">Cafés tradicionais</h3>
            </div>
          </div>
        </div>
        <div class="col-12 col-md-6 col-lg-4">
          <div class="card border-0 btn mx-auto" style="width: 18rem">
            <img
              src="../assets/imgs/produtos-paes.png"
              class="card-img-top"
              alt="Xícara de café preto"
            />
            <div class="card-body text-center">
              <h3 class="card-text fw-bold">Cafés tradicionais</h3>
            </div>
          </div>
        </div>
        <div class="col-12 col-md-6 col-lg-4">
          <div class="card border-0 btn mx-auto" style="width: 18rem">
            <img
              src="../assets/imgs/produtos-doces.png"
              class="card-img-top"
              alt="Xícara de café preto"
            />
            <div class="card-body text-center">
              <h3 class="card-text fw-bold">Cafés tradicionais</h3>
            </div>
          </div>
        </div>
        <div class="col-12 col-md-6 col-lg-4">
          <div class="card border-0 btn mx-auto" style="width: 18rem">
            <img
              src="../assets/imgs/produtos-salgados.png"
              class="card-img-top"
              alt="Xícara de café preto"
            />
            <div class="card-body text-center">
              <h3 class="card-text fw-bold">Cafés tradicionais</h3>
            </div>
          </div>
        </div>
      </div>
      <slot></slot>
      <!-- Modal 1 -->
      <div
        class="modal fade"
        id="modal-1"
        tabindex="-1"
        aria-labelledby="exampleModalLabel"
        aria-hidden="true"
      >
        <div class="modal-dialog">
          <div class="modal-content">
            <div class="modal-header">
              <h2 class="modal-title fs-5 fw-bold" id="exampleModalLabel">
                Cafés tradicionais
              </h2>
              <button
                type="button"
                class="btn-close"
                data-bs-dismiss="modal"
                aria-label="Close"
              ></button>
            </div>
            <div class="modal-body">
              <img
                class="w-100"
                src="../assets/imgs/produtos-cafe-tradicional.png"
                alt="Xícara de café preto"
              />
              <p>
                O café Serenatto é conhecido por seus blends tradicionais e
                saborosos, que agradam aos amantes da bebida. Nossos grãos são
                cuidadosamente selecionados e torrados para produzir um aroma
                rico e sabor equilibrado.
              </p>
              <p>
                Entre os cafés mais tradicionais da casa, destaca-se o "Café
                Serenatto", um blend exclusivo de grãos com notas de chocolate e
                caramelo. Outra opção popular é o "Café Italiano", um café
                expresso encorpado e intenso. Já o "Café Cappuccino" é uma
                escolha clássica para quem prefere uma bebida cremosa e suave.
              </p>
            </div>
            <div class="modal-footer mx-auto">
              <button
                type="button"
                class="btn btn-secondary botao-padrao border-0"
                data-bs-dismiss="modal"
              >
                Fechar janela
              </button>
            </div>
          </div>
        </div>
      </div>
      <!-- Modal 2 -->
      <div
        class="modal fade"
        id="modal-2"
        tabindex="-1"
        aria-labelledby="exampleModalLabel"
        aria-hidden="true"
      >
        <div class="modal-dialog">
          <div class="modal-content">
            <div class="modal-header">
              <h2 class="modal-title fs-5 fw-bold" id="exampleModalLabel">
                Cafés Especiais
              </h2>
              <button
                type="button"
                class="btn-close"
                data-bs-dismiss="modal"
                aria-label="Close"
              ></button>
            </div>
            <div class="modal-body">
              <img
                class="w-100"
                src="../assets/imgs/produtos-cafe-especial.png"
                alt="Xícara de café preto"
              />
              <p>
                Somos conhecidos também por nossos cafés especiais, que são
                cuidadosamente preparados com grãos selecionados de alta
                qualidade e técnicas de preparo precisas.
              </p>
              <p>
                Entre as opções de cafés especiais do Café & Bistrô Serenatto,
                destacamos o café aeropress, que é preparado com uma técnica de
                imersão e pressão, resultando em uma bebida de sabor intenso e
                aroma acentuado. Outra opção popular é o café Hario V60, que é
                preparado com um filtro de papel em formato de cone e resulta em
                uma bebida limpa e suave, ressaltando as notas sensoriais dos
                grãos. Além disso, oferecemos uma variedade de bebidas geladas,
                como o café gelado, que é preparado com grãos torrados escuros e
                servido com gelo e leite, resultando em uma bebida refrescante e
                saborosa.
              </p>
            </div>
            <div class="modal-footer mx-auto">
              <button
                type="button"
                class="btn btn-secondary botao-padrao border-0"
                data-bs-dismiss="modal"
              >
                Fechar janela
              </button>
            </div>
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
.botao-padrao {
  background-color: #b29463;
  color: black;
}
.botao-padrao:hover {
  background-color: #816d4f;
}
</style>
