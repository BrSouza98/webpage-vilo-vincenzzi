<template>
  <div class="configuracoes-globais">
    <div>
      <img src="~/assets/nossaequipe.png" alt="" class="bannersConteudo" />

      <b-container fluid class="Apresentacao fundopadrao">
        <b-row>
          <b-col>
            <h1 class="margemupdown1">APRESENTAÇÃO</h1>
            <p class="margemupdown1">
              Nos primeiros passos, nas descobertas... A gente aprova seus
              sonhos. A Educação Infantil do Colégio Vilo Vincenzzi Taquaritinga
              foi inaugurada em 2005 após um intenso planejamento entre a
              direção do colégio, coordenadores e professores. O sucesso
              alcançado com a implantação desse projeto só foi possível graças à
              credibilidade que o Vilo Vincenzzi conquistou em Taquaritinga ao
              longo de sua história marcada por uma educação de qualidade. A
              Educação Infantil do Sistema Vilo Vincenzzi de Ensino dá à criança
              a oportunidade de aprender a conhecer o mundo que a rodeia e
              amplia a sua capacidade de trabalhar com uma variedade de
              assuntos. A unidade da Educação Infantil do Vilo Vincenzzi
              Taquaritinga possui um espaço amplo onde as crianças desenvolvem
              suas habilidades, além de toda estrutura necessária para garantir
              o aprendizado cognitivo dos nossos alunos. A Educação Infantil do
              Colégio Vilo Vincenzzi Taquaritinga oferece as seguintes turmas:
            </p>

            <ul>
              <li v-for="turma in turmas" :key="turma.message">
                {{ turma.message }}
              </li>
            </ul>
          </b-col>
        </b-row>
      </b-container>

      <b-container fluid class="configuraçãoPadrao">
        <b-row cols="2">
          <b-col class="fundoVerde col-7">
            <h3>
              "Feliz aquele que transfere o que sabe e aprende o que ensina."
              Cora Coralina.
            </h3>
            <p>
              Daniela Mara Henriques é coordenadora pedagógica da EMEB
              Engenheiro Vilo Vincenzzi.
              <br>
              <br>
              Atualmente também exerce a função temporária de diretora de nossa
              escola.
              <br>
              <br>
              Iniciou sua trajetória concluindo o 2°grau com habilitação para o
              Magistério.
              <br>
              <br>
              É licenciada em Ciências Biológicas e Pedagogia com especialização
              em Psicopedagogia.
            </p>
          </b-col>

          <b-col class="fundoBranco col-5">
            <div
              class="d-flex flex-wrap align-items-center justify-content-center"
            >
              <img
                class="mt-3 card-colaborador"
                src="~/assets/Coordenadora.jpg"
                alt="Foto da coordenadora Daniela"
              />
              <h3 class="mt-3 w-100 d-flex justify-content-center">
                Daniela - Coordenadora
              </h3>
            </div>
          </b-col>
        </b-row>
      </b-container>

      <b-container fluid class="configuraçãoPadrao">
        <b-row cols="2">
          <b-col class="fundoBranco col-5">
            <div
              class="d-flex flex-wrap align-items-center justify-content-center"
            >
              <img
                class="mt-3 card-colaborador"
                src="~/assets/prof1.jpg"
                alt="Foto da berçarista Cléo"
              />
              <h3 class="mt-3 w-100 d-flex justify-content-center">
                Cléo - Berçarista
              </h3>
            </div>
          </b-col>

          <b-col class="fundoVermelho col-7">
            <h3>
              "Ninguém é tão grande que não possa aprender, nem tão pequeno que
              não possa ensina." Esopo.
            </h3>
            <p>
              Cleonice Rezende da Silva é berçarista responsável pelos berçários
              I e II.
              <br>
              <br>
              Tem formação tecnológica em Marketing, é graduada em Pedagogia e
              possui especialização em Educação Especial.
            </p>
          </b-col>
        </b-row>
      </b-container>

      <b-container fluid class="configuraçãoPadrao">
        <b-row cols="2">
          <b-col class="fundoAzul col-7">
            <h3>
              "Educação é aquilo que fica depois que você esquece o que a escola
              ensinou." Albert Einstein.
            </h3>
            Sandra Ruy Bruno Bota é Auxiliar de Desenvolvimento Infantil
            responsável pelo Maternal I.
            <br>
            <br>
              Possui formação tecnológica em Produção Industrial pela FATEC e
              licenciatura plena em Pedagogia.
            <br>
          </b-col>

          <b-col class="fundoBranco col-5">
            <div
              class="d-flex flex-wrap align-items-center justify-content-center"
            >
              <img
                class="mt-3 card-colaborador"
                src="~/assets/prof2.jpg"
                alt="Foto da auxiliar infantil Sandra"
              />
              <h3 class="mt-3 w-100 d-flex justify-content-center">
                Sandra - Aux. Infantil
              </h3>
            </div>
          </b-col>
        </b-row>
      </b-container>

      <b-container fluid class="configuraçãoPadrao">
        <b-row cols="2">
          <b-col class="fundoBranco col-5">
            <div
              class="d-flex flex-wrap align-items-center justify-content-center"
            >
              <img
                class="mt-3 card-colaborador"
                src="~/assets/prof4.jpg"
                alt="Foto da professora do Maternal 2 Rose"
              />
              <h3 class="mt-3 w-100 d-flex justify-content-center">
                Rose - Profª Maternal 2
              </h3>
            </div>
          </b-col>

          <b-col class="fundoAmarelo col-7">
            <h3>
              "Educação não é preparação para a vida, é a própria vida."John
              Dewey.
            </h3>
            <p>
              Rosemeire Aparecida Colla é professora do Maternal II.
              <br>
              <br>
              Formada pela Faculdade ITES em Pedagogia.
              <br>
              <br>
              Possui pós-graduação em Educação e Sociedade pela Faculdade São
              Luís.
              <br>
              <br>
              Atualmente está cursando pós-graduação em Educação e Meio Ambiente
              também pela Faculdade São Luís.
            </p>
          </b-col>
        </b-row>
      </b-container>

      <b-container fluid class="configuraçãoPadrao">
        <b-row cols="2">
          <b-col class="fundoRosa col-7">
            <h3>"Não se pode falar de educação sem amor." Paulo Freire.</h3>
            <p>
              Ludmila Carvalho Gambogi é professora do Jardim I - 1° Etapa.
              <br>
              <br>
              Licenciatura em Pedagogia e atualmente graduanda em Letras (Português e Inglês).
              <br>
              <br>
              Pós-graduada em Alfabetização e Letramento, Neuroaprendizagem e
              Psicopedagogia Clínica, Institucional e Educação Especial.
              <br>
              <br>
              Possui também formação em nível Master Business Administration em
              Gestão Escolar pela USP/ESALQ.
            </p>
          </b-col>

          <b-col class="fundoBranco col-5">
            <div
              class="d-flex flex-wrap align-items-center justify-content-center"
            >
              <img
                class="mt-3 card-colaborador"
                src="~/assets/ludimila.jpg"
                alt="Foto da professora do Jardim de Infacia 1 Ludmila Gambogi"
              />
              <h3 class="mt-3 w-100 d-flex justify-content-center">
                Ludmila Gambogi - Profª Jardim Inf. I
              </h3>
            </div>
          </b-col>
        </b-row>
      </b-container>

      <b-container fluid class="configuraçãoPadrao">
        <b-row cols="2">
          <b-col class="fundoBranco col-5">
            <div
              class="d-flex flex-wrap align-items-center justify-content-center"
            >
              <img
                class="mt-3 card-colaborador"
                src="~/assets/prof3.jpg"
                alt="Foto do professor do Jardim de Infancia 2"
              />
              <h3 class="mt-3 w-100 d-flex justify-content-center">
                Danilo - Profª Jardim de inf. II
              </h3>
            </div>
          </b-col>

          <b-col class="fundoMarrom col-7">
            <h3>
              "A função da educação é ensinar a pensar criticamente e
              intensamento." Martin Luther King.
            </h3>
            <p>
              Danilo Augusto Reinol é professor do Jardim II - 2° Etapa.
              <br />
              <br>
              Possui graduações nas áres de Sistemas de Informação, Pedagogia e
              Letras (Português e Inglês). É pós-graduado em nível lato sensu em
              Educação Especial e Inclusiva,
              <br />
              <br>
              Psicopedagogia Institucional e atualmente cursa Compreensão de
              textos e tradução da Língua Espanhola. É também mestrando em
              Educação pela Ufscar.
            </p>
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
      turmas: [{ message: "Berçario" }, { message: "Maternal I" }, { message: "Maternal II" }],
    };
  },
};
</script>

<style lang="scss" scoped>
$borda: 2px solid #5e5e5e;

.configuracoes-globais {
  font-size: 1em;
  padding: 0;
  margin: 0;
  height: 100%;
}

.Apresentacao {
  h1 {
    font-weight: bolder;
    margin-bottom: 10px;
    border-bottom: $borda;
    text-align: center;
  }
}

b-container {
  margin-top: 10px;
}

.configuraçãoPadrao {
  color: white;
  font-weight: bolder;
  img {
    border-radius: 3px;
    width: 32%;
  }

  h3 {
    font-weight: bolder;
    margin-top: 10px;
    text-align: center;
    font-style: italic;
  }

  p{
    margin: 20px;
  }
}

.fundoBranco {
  background-color: #f3f3f3;
  color: #5e5e5e;
  border-bottom: $borda;
}

.fundoVerde {
  background-color: #019682;
  border-bottom: $borda;
}

.fundoVerde:hover {
  background-color: #03473e;
  border-bottom: $borda;
  transition: 1s;
}

.fundoVermelho {
  background-color: #b81530;
  border-bottom: $borda;
}

.fundoVermelho:hover {
  background-color: #810a1e;
  border-bottom: $borda;
  transition: 1s;
}

.fundoAzul {
  background-color: #0c78aa;
  border-bottom: $borda;
}

.fundoAzul:hover {
  background-color: #004768;
  border-bottom: $borda;
  transition: 1s;
}

.fundoAmarelo {
  background-color: #797700;
  border-bottom: $borda;
}

.fundoAmarelo:hover {
  background-color: #555400;
  border-bottom: $borda;
  transition: 1s;
}

.fundoRosa {
  background-color: #961475;
  border-bottom: $borda;
}

.fundoRosa:hover {
  background-color: #6b0050;
  border-bottom: $borda;
  transition: 1s;
}

.fundoMarrom {
  background-color: #6e382b;
  border-bottom: $borda;
}

.fundoMarrom:hover {
  background-color: #532419;
  border-bottom: $borda;
  transition: 1s;
}

@media (max-width: 768px) {
  .configuracoes-globais {
    font-size: 0.9em;

    .configuraçãoPadrao {
      img {
        border-radius: 3px;
        width: 90%;
      }

      h3 {
        font-weight: bolder;
        font-size: 1.8em;
      }
    }
  }
}

.margemupdown1 {
  margin-top: 40px;
  margin-bottom: 40px;
}

.bannersConteudo {
  width: 100%;
  padding: 0;
  margin: 0;
  max-height: 650px;
}
</style>
