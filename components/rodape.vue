
<template>
  <footer class="footer">
    <div>
      <b-container fluid class="footer">
        <b-row class="">
          <b-col>
            <div class="mapaSite">
              <h2>Vilo Vincenzzi</h2>
              <p><a href="sobre">Sobre</a></p>
              <p><a href="metodologia">Metodologia</a></p>
              <p><a href="nossaequipe">Nossa equipe</a></p>
              <p>
                <a href="https://vilovicenzzi.wordpress.com/" target="_blank"
                  >Blog</a
                >
              </p>
              <p><a href="fale-conosco">Fale conosco</a></p>
            </div>
          </b-col>

          <b-col>
            <div>
              <h3>Informações de contato</h3>
              <p class="margem">
                <b-icon icon="house" />
                Av Cap. José Camargo Lima, 341, Jardim São Sebastião
                Taquaritinga/SP
              </p>

              <p>
                <b-icon icon="telephone" />
                (16) 3252-7799
              </p>

              <p>
                <b-icon icon="clock" />
                Horário de funcionamento: 07h às 17h
              </p>
              <p>
                <b-icon icon="mailbox" />
                vilovicenzzi@gmail.com
              </p>
              <a href="https://www.facebook.com/profile.php?id=100009453482303" target="_blank">
              <img
                class="faceIcon"
                src="~/assets/faceWhite.png"
                alt="Ícone do Facebook">
              </a>
              <a href="https://www.youtube.com/channel/UCu9JyneukfRcBSCuiJHQ3LA" target="_blank">
              <img
                class="youtubeIcon"
                src="~/assets/youtubeBlack.png"
                alt="Ícone do youtube">
              </a>
              
            </div>
          </b-col>
        </b-row>
      </b-container>
    </div>

    <div
      style="background-color: rgb(40, 40, 40)"
      class="d-flex justify-content-center"
    >
      Fatec - Taquaritinga {{ new Date().getFullYear() }}
    </div>
  </footer>
</template>

<style lang="scss" scoped>
.footer {
  background-color: #333;
  color: #fff;
  font-size: 18px;
  margin-top: 50px;
  padding-top: 10px;
}

.faceIcon {
  width: 4%;
}

.youtubeIcon {
  width: 4%;
  margin-left: 10px;
}


.mapaSite {
  a {
    color: white;
  }

  display: flex;
  justify-content: center;
  flex-direction: column;
  align-content: center;
}

.col {
  display: flex;
  justify-content: center;
}
</style>