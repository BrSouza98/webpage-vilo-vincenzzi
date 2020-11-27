<template>
  <div>
    <div>
      <b-navbar
        align-h="between"
        class="w-100 d-flex justify-content-between Cor-navbar"
      >
        <b-navbar-brand href="/" id="paginaInicial"
          ><img src="@/assets/vilo-icone.png" alt=""
        /></b-navbar-brand>

        <div id="menuPequeno">
          <b-button
            v-b-toggle.sidebar-right
            class="menu"
            variant="outline-dark"
          >
            <b-icon icon="grid-fill"></b-icon>
          </b-button>

          <b-sidebar
            id="sidebar-right"
            class="my-sidebar"
            title="Menu"
            right
            shadow
          >
            <div class="px-3 py-2">
              <b-nav class="ml-auto">
                <b-nav class="d-block">

                  <b-nav-item href="../sobre/">Sobre</b-nav-item>
                  <b-nav-item href="../metodologia/">Metodologia</b-nav-item>
                  <b-nav-item href="../nossaequipe/">Nossa equipe</b-nav-item>
                  <b-nav-item
                    href="https://vilovicenzzi.wordpress.com/"
                    target="_blank"
                    >Blog</b-nav-item
                  >
                  <b-nav-item href="../fale-conosco/">Fale conosco</b-nav-item>
                </b-nav>
              </b-nav>
            </div>
          </b-sidebar>
        </div>

        <div id="menuGrande">
          <div class="px-3 py-2">
            <b-nav class="ml-auto">
              <b-nav class="d-flex">

                <b-nav-item href="../sobre/">Sobre</b-nav-item>
                <b-nav-item href="../metodologia/">Metodologia</b-nav-item>
                <b-nav-item href="../nossaequipe/">Nossa equipe</b-nav-item>
                <b-nav-item
                  href="https://vilovicenzzi.wordpress.com/"
                  target="_blank"
                  >Blog</b-nav-item
                >
                <b-nav-item href="../fale-conosco/">Fale conosco</b-nav-item>
              </b-nav>
            </b-nav>
          </div>
        </div>
      </b-navbar>
    </div>
  </div>
</template>

<script>
import Vue from "vue";
import { BootstrapVue, BootstrapVueIcons } from "bootstrap-vue";

Vue.use(BootstrapVue);
Vue.use(BootstrapVueIcons);

export default {};
</script>

<style lang="scss" scoped>
//regras do menu e interações
$cor-primaria: rgb(240, 240, 240);
$cor-secundaria: rgb(70, 70, 70);
$preto: rgb(29, 29, 29);

.Cor-navbar {
  background-color: $cor-primaria;
}

a {
  color: $cor-secundaria;
  border-bottom: 3px solid $cor-primaria;
  box-sizing: content-box;
  margin: 5px;
  font-weight: 600;

  &:hover {
    animation-name: simple-border;
    animation-duration: 0.3s;
    animation-iteration-count: 1;
    animation-timing-function: ease-in;
    border-bottom-color: rgb(29, 29, 29);
    color: $preto;
  }
}

@keyframes simple-border {
  from {
    border-bottom-color: $cor-primaria;
  }
  to {
    border-bottom-color: $preto;
  }
}

.navbar-dark .navbar-brand {
  color: $preto;
}

.menu {
  border-radius: 10px;
}

#menuPequeno {
  display: none;
}

#menuGrande {
  display: flex;
  flex-direction: initial;
}

@media screen and (max-width: 790px) {
  #menuGrande {
    display: none;
  }

  #menuPequeno {
    display: inherit;
    a {
      font-size: 21px;
      padding: 10px;
      margin: 10px;
      &:hover {
        margin-left: 15px;
      }
    }

    @keyframes simple-border {
      from {
        border-bottom-color: $cor-primaria;
        margin-left: 10px;
      }
      to {
        border-bottom-color: $preto;
        margin-left: 15px;
      }
    }
  }
}
</style>
