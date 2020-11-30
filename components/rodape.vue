
<template>
  <footer>
    <div>
      <b-container fluid class="footer d-flex justify-content-center">
        <b-row cols="1" cols-lg="2" class="w-100 justify-content-center">
          <b-col class="d-flex flex-column justify-content-center py-5 px-3">
            <div class="mapaSite">
              <h3>Vilo Vincenzzi</h3>
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

          <b-col class="d-flex flex-column justify-content-center py-5 px-3">
            <div>
              <h3>Contato</h3>
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
              <a
                href="https://www.facebook.com/profile.php?id=100009453482303"
                target="_blank"
              >
                <img
                  class="faceIcon bottomarg"
                  src="~/assets/faceWhite.png"
                  alt="Ícone do Facebook"
                />
              </a>
              <a
                href="https://www.youtube.com/channel/UCu9JyneukfRcBSCuiJHQ3LA"
                target="_blank"
              >
                <img
                  class="youtubeIcon bottomarg"
                  src="~/assets/youtubeBlack.png"
                  alt="Ícone do youtube"
                />
              </a>
            </div>
          </b-col>
        </b-row>
      </b-container>
    </div>

    <div
      style="background-color: rgb(30, 30, 30); color: white"
      class="d-flex justify-content-center"
    >
      Fatec - Taquaritinga {{ new Date().getFullYear() }}
    </div>
  </footer>
</template>

<style lang="scss" scoped>
a,
p {
  color: white;
}

.footer {
  background-color: #333;
  color: #fff;
  font-size: 18px;
}

.faceIcon {
  width: 30px;
}

.youtubeIcon {
  width: 30px;
  margin-left: 10px;
}
.col {
  display: flex;
  justify-content: center;
}

.bottomarg {
  margin-bottom: 20px;
}

@media screen and (max-width: 720px) {
  a,
  p {
    font-size: 20px;
    margin-top: 30px;
    margin-bottom: 40px;
  }

  h3 {
    font-size: 2.5em;
  }

  .faceIcon {
    width: 25px;
  }

  .youtubeIcon {
    width: 25px;
    margin-left: 10px;
  }
}
</style>