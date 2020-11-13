<template>
  <div>
    <div>
      <b-carousel
        id="carousel-no-animation"
        style="text-shadow: 0px 0px 2px #000"
        no-animation
        indicators
        img-width="1024"
        img-height="480"
      >
        <b-carousel-slide
          caption="Sobre nós"
          img-src="https://i.imgur.com/RpegqeS.png"
        ></b-carousel-slide>
      </b-carousel>
    </div>
    <div class="cor">
    <h2 class="textocentro"><b>Somos uma escola de Educação Infantil da rede municipal de Taquaritinga.</b></h2>
<b-container fluid class="bv-example-row">
  <b-row>
    <b-col><h2>Nossa escola</h2>
    <p>A Escola Municipal de Educação Básica Engenheiro Vilo Vicenzzi foi criada em 20 de março de 2015.</p>
    <p>Contamos com uma equipe que ama o que faz, fazendo tudo com muito amor e carinho por nossos alunos..</p>
    <h2>Turmas</h2>
    <p><b>Educação infantil - Creche</b></p>
    <p>Aulas no período da <b>Manhã</b></p>
    <p>Números de turmas 3 / Média de alunos por turma: 15</p>
    <p><b>Educação infantil - Pré-escola</b></p>
    <p>Aulas no período da <b>Manhã</b></p>
    <p>Número de turmas 2 / Média de alunos por turma: 25</p>
    </b-col>
    <b-col><h2>Infraestrutura</h2>
    <p>• Alimentação escolar para os alunos.</p>
    <p>• Água filtrada.</p>
    <p>• Água da rede pública.</p>
    <p>• Energia da rede pública.</p>
    <p>• Esgoto da rede pública.</p>
    <p>• Lixo destinado à coleta periódica;</p>
    <p>• Acesso à Internet.</p>
    <p>• Banda larga.</p>
    </b-col>
    <b-col><h2>Instalação de ensino</h2>
    <p>• 7 salas de aulas.</p>
    <p>• Sala de diretoria.</p>
    <p>• Sala de professores.</p>
    <p>• Cozinha.</p>
    <p>• Banheiro adequado à educação infantil.</p>
    <p>• Banheiro adequado à alunos com deficiência ou mobilidade reduzida.</p>
    <p>• Sala de secretaria.</p>
    <p>• Refeitório.</p>
    <p>• Despensa.</p>
    <p>• Almoxarifado.</p>
    </b-col>
  </b-row>
</b-container>
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

<style>
.texto {
  text-align: right;
  color: red;
}



.textocentro{
  text-align: center;
}


</style>