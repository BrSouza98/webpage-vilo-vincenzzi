<template>
    <b-container fluid class="updown">
      <b-row  col sm="12" md="4" sg="4">
        <b-col>
          <card
            titulo="Berçário"
            alt="card de apresentacao"
            texto="Berçário é até qual idade? O berçário da escola Vilo Vicenzzi atende crianças 
            dos 4 meses aos 2 anos de idade. Nossa instituição se dedica ao acompanhamento e cuidados das crianças. 
            Com profissionais especializados para cuidar dos nossos alunos com muito amor e carinho, 
            na ausência momentânea de seus pais."
          ></card>
        </b-col>

        <b-col>
          <card
            titulo="Maternal"
            alt="card de apresentacao"
            texto="Nosso maternal atende crianças de 2 a 3 anos de idade. 
            Contamos com 2 maternais um para cada ano de vida da criança, que são divididos por períodos 
            conforme a idade. Trabalhamos com músicas, cantigas de roda e dança para estimular o 
            desenvolvimento integral dos alunos. Contamos histórias infantis, 
            desenvolvemos atividades lúdicas e trabalhamos com o corpo através de estímulos constantes.
            Nossas propostas estão todas de acordo com a nova Base Nacional Comum Curricular."
          ></card>
        </b-col>

        <b-col>
          <card
            titulo="Jardim de infância"
            alt="card de apresentacao"
            texto="O jardim de infância de nossa escola atende crianças a partir dos 4 anos de idade
            e está dividido em 1ª e 2ª Etapas. Contribuímos para o desenvolvimento da linguagem e do 
            vocabulário dos nossos alunos, pois é importante na aprendizagem da leitura e da escrita e
            na aquisição de muitos outros conhecimentos. Também trabalhamos com jogos e brincadeiras, 
            livres ou orientadas, de modo a promover o desenvolvimento integral das crianças. 
            Os objetivos para essa fase são baseados nos campos de experiência e direitos de 
            aprendizagem descritos na Base Nacional Comum Curricular."
          ></card>
        </b-col>
      </b-row>
    </b-container>
</template>

<script>
export default {
    name: "cardApresentation",

    data(){
        return {
            titulo: "Berçário",
            alt: "card de apresentacao",
            texto: "Berçário é até qual idade? O berçário da escola Vilo Vicenzzi atende crianças dos 4 meses aos 2 anos de idade. Nossa instituição se dedica ao acompanhamento e cuidados das crianças. Com profissionais especializados para cuidar dos nossos alunos com muito amor e carinho, na ausência momentânea de seus pais."
        }
    }
}
</script>

<style>

</style>