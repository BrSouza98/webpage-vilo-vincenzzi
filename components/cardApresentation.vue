<template>
    <b-container fluid id="my-container" class="h-75">
      <b-row  cols="1" cols-md="2" cols-lg="3" class="justify-content-center">
        <b-col>
          <card
            id="my-card"
            class="my-4"
            titulo="Berçário"
            alt="card de apresentacao"
            texto="Berçário é até qual idade? O berçário da escola Vilo Vicenzzi atende crianças 
            dos 4 meses aos 2 anos de idade. Nossa instituição se dedica ao acompanhamento e cuidados das crianças. 
            Berçários são como a segunda casa dos bebês e por isso contamos com uma ótima estrutura e com profissionais especializados para cuidar dos nossos alunos com muito amor e carinho, 
            na ausência momentânea de seus pais em suas atividades diárias de rotina."
          ></card>
        </b-col>

        <b-col>
          <card
            id="my-card"
            class="my-4"
            titulo="Maternal"
            alt="card de apresentacao"
            texto="Nosso maternal atende crianças de 2 a 3 anos de idade. 
            Contamos com 2 maternais um para cada ano de vida da criança, que são divididos por períodos 
            conforme a idade. Trabalhamos com músicas, cantigas de roda e dança para estimular o 
            desenvolvimento integral dos alunos. Desenvolvemos atividades lúdicas e trabalhamos com o corpo através de estímulos constantes.
            Nossas propostas estão todas de acordo com a nova Base Nacional Comum Curricular."
          ></card>
        </b-col>

        <b-col>
          <card
            id="my-card"
            class="my-4"
            titulo="Jardim de infância"
            alt="card de apresentacao"
            texto="O jardim de infância de nossa escola atende crianças a partir dos 4 anos de idade
            e está dividido em 1ª e 2ª Etapas. Contribuímos para o desenvolvimento da linguagem e do 
            vocabulário dos nossos alunos, pois é importante na aprendizagem da leitura e da escrita e
            na aquisição de muitos outros conhecimentos. Também trabalhamos com jogos e brincadeiras, 
            livres ou orientadas, de modo a promover o desenvolvimento integral das crianças."
          ></card>
        </b-col>
      </b-row>
    </b-container>
</template>

<script>
export default {
    name: "cardApresentation",
}
</script>
