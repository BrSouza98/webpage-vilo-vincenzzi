<template>
  <div>
    <div>
      <img src="~/assets/sobrenos.png" alt="" class="bannersConteudo" />
    </div>
    <div>
      <b-container fluid id="titulo">
        <h2 class="textocentro">
          <b
            >Somos uma escola de Educação Infantil da rede municipal de
            Taquaritinga</b
          >
        </h2>
      </b-container>

      <b-container
        fluid
        id="nossa-escola"
        class="d-flex justify-content-around"
      >
        <b-row cols="1" cols-lg="2">
          <b-col class="d-flex justify-content-center">
            <img src="@/assets/ui/School512px.png" alt="" />
          </b-col>

          <b-col class="my-5 w-50 text-justify">
            <h2>
              <b>Nossa Escola</b>
            </h2>
            <p>
              A Escola Municipal de Educação Básica Engenheiro Vilo Vicenzzi foi
              criada em 20 de março de 2015.
            </p>
            <p>
              Contamos com uma equipe que ama o que faz, fazendo tudo com muito
              amor e carinho por nossos alunos..
            </p>
          </b-col>
        </b-row>
      </b-container>

      <b-container
        id="turmas-container"
        fluid
        class="d-flex flex-column juscontent-center"
      >
        <b-container
          fluid
          id="turmas"
          class="d-flex flex-column justify-content-center align-items-center"
        >
          <h2 class="">
            <b>Turmas</b>
          </h2>
          <b-container class="d-flex justify-content-center">
            <b-row
              cols="1"
              cols-lg="2"
              class="d-flex justify-content-center py-5 flex-lg-nowrap"
            >
              <b-col
                class="bordaArredondada my-3 mx-5 justify-content-md-start"
                order-lg="1"
              >
                <p>Educação infantil - Creche</p>
                <p>Aulas no período da Manhã</p>
                <p>Número de turmas 3</p>
                <p>Média de alunos por turma: 15</p>
              </b-col>

              <b-col class="bordaArredondada my-3 mx-5">
                <p>Educação infantil - Pré-escola</p>
                <p>Aulas no período da Manhã</p>
                <p>Número de turmas 2</p>
                <p>Média de alunos por turma: 25</p>
              </b-col>
            </b-row>
          </b-container>
        </b-container>

        <b-container fluid id="infraestrutura-container">
          <h2 class="textocentro">
            <b>Infraestrutura</b>
          </h2>

          <b-container fluid>
            <b-row id="infraestrutura" cols="1" cols-lg="3" class="mx-2">
              <b-col class="text-justify">
                <p>Alimentação escolar para os alunos.</p>
                <p>Água filtrada.</p>
                <p>Água da rede pública.</p>
              </b-col>

              <b-col order-lg="2" order-md="1">
                <p>Sala de secretaria.</p>
                <p>Energia da rede pública.</p>
                <p>Almoxarifado.</p>
              </b-col>

              <b-col>
                <p>Esgoto da rede pública.</p>
                <p>Lixo destinado à coleta periódica;</p>
                <p>Acesso à Internet.</p>
              </b-col>

              <b-col>
                <p>Banda larga.</p>
                <p>
                  Banheiro adequado à alunos com deficiência ou mobilidade
                  reduzida.
                </p>
                <p>Despensa.</p>
              </b-col>

              <b-col>
                <p>7 salas de aulas.</p>
                <p>Sala de diretoria.</p>
                <p>Sala de professores.</p>
              </b-col>

              <b-col>
                <p>Cozinha.</p>
                <p>Banheiro adequado à educação infantil.</p>
                <p>Refeitório.</p>
              </b-col>
            </b-row>
          </b-container>
        </b-container>
      </b-container>
    </div>
    <div class="textocentro margemupdown">
      <h2><b>Fotos da nossa escola</b></h2>
    </div>

    <div class="card-header1 corpadrao1">
      <b-card
        title=""
        img-src="@/assets/foto1.jpg"
        img-alt="Refeitorio com duas meses e uma cadeirinha"
        img-top
        tag="article"
        style="max-width: 20rem"
        class="mb-2 align"
      >
        <b-card-text class="text-center">
          <a
            class="corpreta"
            href="http://localhost:3000/_nuxt/assets/foto1.jpg"
            target="_blank"
            >Refeitório</a
          >
        </b-card-text>
      </b-card>

      <b-card
        title=""
        img-src="~/assets/foto2.jpg"
        img-alt="Refeitorio com 3 mesas "
        img-top
        tag="article"
        style="max-width: 20rem"
        class="mb-2 align"
      >
        <b-card-text class="text-center">
          <a
            class="corpreta"
            href="http://localhost:3000/_nuxt/assets/foto2.jpg"
            target="_blank"
            >Refeitório</a
          >
        </b-card-text>
      </b-card>

      <b-card
        title=""
        img-src="~/assets/foto3.jpg"
        img-alt="Sala de aulas com diversa carteiras incluindo a do professor"
        img-top
        tag="article"
        style="max-width: 20rem"
        class="mb-2 align"
      >
        <b-card-text>
          <a
            class="corpreta"
            href="http://localhost:3000/_nuxt/assets/foto3.jpg"
            target="_blank"
            >Jardim de infância 1</a
          >
        </b-card-text>
      </b-card>

      <b-card
        title=""
        img-src="~/assets/foto4.jpg"
        img-alt="Brinquedoteca super colorida com diversas cores e com varos lugares com brinquedos guardados"
        img-top
        tag="article"
        style="max-width: 20rem"
        class="mb-2 align"
      >
        <b-card-text>
          <a
            class="corpreta"
            href="http://localhost:3000/_nuxt/assets/foto4.jpg"
            target="_blank"
            >Brinquedoteca</a
          >
        </b-card-text>
      </b-card>
    </div>

    <div class="card-header1 corpadrao1">
      <b-card
        title=""
        img-src="~/assets/foto5.jpg"
        img-alt="Brinquedoteca com diversas cores, uma estante de livros e a porta de vidro"
        img-top
        tag="article"
        style="max-width: 20rem"
        class="mb-2 align"
      >
        <b-card-text>
          <a
            class="corpreta"
            href="http://localhost:3000/_nuxt/assets/foto5.jpg"
            target="_blank"
            >Brinquedoteca</a
          >
        </b-card-text>
      </b-card>

      <b-card
        title=""
        img-src="~/assets/foto6.jpg"
        img-alt="Brinquedoteca com diversas cores,alguns cochonetes e uma janela"
        img-top
        tag="article"
        style="max-width: 20rem"
        class="mb-2 align"
      >
        <b-card-text>
          <a
            class="corpreta"
            href="http://localhost:3000/_nuxt/assets/foto6.jpg"
            target="_blank"
            >Brinquedoteca</a
          >
        </b-card-text>
      </b-card>

      <b-card
        title=""
        img-src="~/assets/foto7.jpg"
        img-alt="Sala com diveros berçarios brancos"
        img-top
        tag="article"
        style="max-width: 20rem"
        class="mb-2 align"
      >
        <b-card-text>
          <a
            class="corpreta"
            href="http://localhost:3000/_nuxt/assets/foto7.jpg"
            target="_blank"
            >Sala do berçário</a
          >
        </b-card-text>
      </b-card>

      <b-card
        title=""
        img-src="~/assets/foto8.jpg"
        img-alt="Sala com diveros berçarios brancos e uma janela"
        img-top
        tag="article"
        style="max-width: 20rem"
        class="mb-2 align"
      >
        <b-card-text>
          <a
            class="corpreta"
            href="http://localhost:3000/_nuxt/assets/foto8.jpg"
            target="_blank"
            >Sala do berçário</a
          >
        </b-card-text>
      </b-card>
    </div>
    <div class="card-header1 corpadrao1">
      <b-card
        title=""
        img-src="~/assets/foto9.jpg"
        img-alt="Banheiro do berçario com foco nos lavatorios"
        img-top
        tag="article"
        style="max-width: 20rem"
        class="mb-2 align"
      >
        <b-card-text>
          <a
            class="corpreta"
            href="http://localhost:3000/_nuxt/assets/foto9.jpg"
            target="_blank"
            >Banheiro do berçário</a
          >
        </b-card-text>
      </b-card>

      <b-card
        title=""
        img-src="~/assets/foto10.jpg"
        img-alt="Banheiro do berçario com o foco nas privadas"
        img-top
        tag="article"
        style="max-width: 20rem"
        class="mb-2 align"
      >
        <b-card-text>
          <a
            class="corpreta"
            href="http://localhost:3000/_nuxt/assets/foto10.jpg"
            target="_blank"
            >Banheiro do berçário</a
          >
        </b-card-text>
      </b-card>

      <b-card
        title=""
        img-src="~/assets/foto11.jpg"
        img-alt="Banheiro do berçario com foco na pia"
        img-top
        tag="article"
        style="max-width: 20rem"
        class="mb-2 align"
      >
        <b-card-text>
          <a
            class="corpreta"
            href="http://localhost:3000/_nuxt/assets/foto11.jpg"
            target="_blank"
            >Banheiro do berçário</a
          >
        </b-card-text>
      </b-card>

      <b-card
        title=""
        img-src="~/assets/foto12.jpg"
        img-alt="Playground com diveros cavalinhos e um escorregador,alem de bancos"
        img-top
        tag="article"
        style="max-width: 20rem"
        class="mb-2 align"
      >
        <b-card-text>
          <a
            class="corpreta"
            href="http://localhost:3000/_nuxt/assets/foto12.jpg"
            target="_blank"
            >Playground</a
          >
        </b-card-text>
      </b-card>
    </div>
    <div class="card-header1 corpadrao1">
      <b-card
        title=""
        img-src="~/assets/foto13.jpg"
        img-alt="Playground com cavalinhos, piscina de bolinhas, e dois escorregadores"
        img-top
        tag="article"
        style="max-width: 20rem"
        class="mb-2 align"
      >
        <b-card-text>
          <a
            class="corpreta"
            href="http://localhost:3000/_nuxt/assets/foto13.jpg"
            target="_blank"
            >Playground</a
          >
        </b-card-text>
      </b-card>

      <b-card
        title=""
        img-src="~/assets/foto14.jpg"
        img-alt="Playground com o foco num grande circuito de escorregadores"
        img-top
        tag="article"
        style="max-width: 20rem"
        class="mb-2 align"
      >
        <b-card-text>
          <a
            class="corpreta"
            href="http://localhost:3000/_nuxt/assets/foto14.jpg"
            target="_blank"
            >Playground</a
          >
        </b-card-text>
      </b-card>
      <b-card
        title=""
        img-src="~/assets/foto17.jpg"
        img-alt="Playground com foco em duas arvores"
        img-top
        tag="article"
        style="max-width: 20rem"
        class="mb-2 align"
      >
        <b-card-text>
          <a
            class="corpreta"
            href="http://localhost:3000/_nuxt/assets/foto17.jpg"
            target="_blank"
            >Playground</a
          >
        </b-card-text>
      </b-card>

      <b-card
        title=""
        img-src="~/assets/foto16.jpg"
        img-alt="Playground com o foco num grande circuito de escorregadores"
        img-top
        tag="article"
        style="max-width: 20rem"
        class="mb-2 align"
      >
        <b-card-text>
          <a
            class="corpreta"
            href="http://localhost:3000/_nuxt/assets/foto16.jpg"
            target="_blank"
            >Playground</a
          >
        </b-card-text>
      </b-card>
    </div>
  </div>
</template>

<script>
export default {
  data() {
    return {
      slide: 0,
      sliding: null,
    };
  },
  methods: {
    onSlideStart(slide) {
      this.sliding = true;
    },
    onSlideEnd(slide) {
      this.sliding = false;
    },
  },
};
</script>

<script>
export default {};
</script>

<style lang="scss" scoped>
@import "@/assets/css/_variaveis.scss";

h2 {
  padding: 10px;
  margin: 10px;
  font-size: 40px;
  text-align: center;
}

p {
  font-size: 25px;
}

* {
  margin: 0;
  padding: 0;
  text-align: justify;
}

#titulo {
  background-color: rgb(64, 145, 123);
  color: $cor-primaria;
  padding: 40px;
}

#nossa-escola {
  background-color: $cor-primaria;
  color: $cor-secundaria;
  padding: 45px;
  text-align: center;
}

#turmas {
  background-color: rgb(77, 139, 190);
  color: $cor-primaria;

  padding: 45px;
  text-align: center;
}

#infraestrutura-container {
  background-color: rgb(255, 255, 205);
  color: rgb(52, 3, 145);
  #infraestrutura {
    div {
      @extend .bordaArredondada;
    }
  }
}

.bordaArredondada {
  border: solid rgba(240, 240, 240, 0.26) 0.5px;
  border-radius: 25px;
  background-color: rgba(0, 0, 0, 0.050);
  padding: 20px;
  width: 100%;
}

.texto {
  text-align: right;
}

.textocentro {
  text-align: center;
}

.margemupdown {
  margin-bottom: 40px;
  margin-top: 40px;
}

.bannersConteudo {
  width: 100%;
  padding: 0;
  margin: 0;
  max-height: 500px;
}

.card-header1 {
  padding: 1.75rem 1.25rem;
  margin-bottom: 0;
  font-weight: bold;
  display: flex;
  justify-content: space-evenly;
  text-align: center;
}

.corpreta {
  color: black;
}

.bannersConteudo {
  width: 100%;
  padding: 0;
  margin: 0;
  max-height: 650px;
}

.corpadrao1 {
  p {
    text-align: center;
  }
}
</style>

<style lang="scss" scoped>
@media screen and (max-width: 600px) {
  p {
    font-size: 20px;
  }
}
</style>
