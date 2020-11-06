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
          caption="Nossa Equipe"
          img-src="~/assets/losa.jpg"
        ></b-carousel-slide>
      </b-carousel>

      <b-container fluid class="configuraçãoPadrao">
        <b-row cols="2">
          <b-col class="fundoVerde col-7">
            <h3>"Frase motivacional foda demais"</h3>
            <p>
              Lorem ipsum, dolor sit amet consectetur adipisicing elit. Ratione
              natus debitis magni ullam ad hic enim a id deserunt facilis
              officiis qui vitae dolor, veniam voluptates ipsum quis molestias
              in?
            </p>
          </b-col>

          <b-col class="fundoBranco col-5">
            <div
              class="d-flex flex-wrap align-items-center justify-content-center"
            >
              <img
                class="mt-3 card-colaborador"
                src="~/assets/Coordenadora.jpg"
                alt=""
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
                alt=""
              />
              <h3 class="mt-3 w-100 d-flex justify-content-center">
                Cléo - Berçarista
              </h3>
            </div>
          </b-col>

          <b-col class="fundoVermelho col-7">
            <h3>"Frase motivacional foda demais"</h3>
            <p>
              Lorem ipsum, dolor sit amet consectetur adipisicing elit. Ratione
              natus debitis magni ullam ad hic enim a id deserunt facilis
              officiis qui vitae dolor, veniam voluptates ipsum quis molestias
              in?
            </p>
          </b-col>
        </b-row>
      </b-container>

      <b-container fluid class="configuraçãoPadrao">
        <b-row cols="2">
          <b-col class="fundoAzul col-7">
            <h3>"Frase motivacional foda demais"</h3>
            <p>
              Lorem ipsum, dolor sit amet consectetur adipisicing elit. Ratione
              natus debitis magni ullam ad hic enim a id deserunt facilis
              officiis qui vitae dolor, veniam voluptates ipsum quis molestias
              in?
            </p>
          </b-col>

          <b-col class="fundoBranco col-5">
            <div
              class="d-flex flex-wrap align-items-center justify-content-center"
            >
              <img
                class="mt-3 card-colaborador"
                src="~/assets/prof2.jpg"
                alt=""
              />
              <h3 class="mt-3 w-100 d-flex justify-content-center">
                Sandra - Aux. Desenvolvimento Infantil
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
                alt=""
              />
              <h3 class="mt-3 w-100 d-flex justify-content-center">
                Rose - Profª Maternal 2
              </h3>
            </div>
          </b-col>

          <b-col class="fundoAmarelo col-7">
            <h3>"Frase motivacional foda demais"</h3>
            <p>
              Lorem ipsum, dolor sit amet consectetur adipisicing elit. Ratione
              natus debitis magni ullam ad hic enim a id deserunt facilis
              officiis qui vitae dolor, veniam voluptates ipsum quis molestias
              in?
            </p>
          </b-col>
        </b-row>
      </b-container>

      <b-container fluid class="configuraçãoPadrao">
        <b-row cols="2">
          <b-col class="fundoRosa col-7">
            <h3>"Frase motivacional foda demais"</h3>
            <p>
              Lorem ipsum, dolor sit amet consectetur adipisicing elit. Ratione
              natus debitis magni ullam ad hic enim a id deserunt facilis
              officiis qui vitae dolor, veniam voluptates ipsum quis molestias
              in?
            </p>
          </b-col>

          <b-col class="fundoBranco col-5">
            <div
              class="d-flex flex-wrap align-items-center justify-content-center"
            >
              <img
                class="mt-3 card-colaborador"
                src="~/assets/ludimila.jpg"
                alt=""
              />
              <h3 class="mt-3 w-100 d-flex justify-content-center">
                Ludimila - Profª Jardim Inf. I
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
                alt=""
              />
              <h3 class="mt-3 w-100 d-flex justify-content-center">
                Danilo - Profª Jardim de inf. II
              </h3>
            </div>
          </b-col>

          <b-col class="fundoMarrom col-7">
            <h3>"Frase motivacional foda demais"</h3>
            <p>
              Lorem ipsum, dolor sit amet consectetur adipisicing elit. Ratione
              natus debitis magni ullam ad hic enim a id deserunt facilis
              officiis qui vitae dolor, veniam voluptates ipsum quis molestias
              in?
            </p>
          </b-col>
        </b-row>
      </b-container>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style></style>

<script>
export default {};
</script>

<style lang="scss" scoped>
$borda: 2px solid #5e5e5e;

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
  }
}

.fundoBranco {
  background-color: #f3f3f3;
  color: #5e5e5e;
  border-bottom: $borda;
}

.fundoVerde {
  background-color: #13a18e;
  border-bottom: $borda;
}

.fundoVermelho {
  background-color: #a1132b;
  border-bottom: $borda;
}

.fundoAzul {
  background-color: #1374a1;
  border-bottom: $borda;
}

.fundoAmarelo {
  background-color: #797700;
  border-bottom: $borda;
}

.fundoRosa {
  background-color: #79005b;
  border-bottom: $borda;
}

.fundoMarrom {
  background-color: #612c1f;
  border-bottom: $borda;
}
</style>
