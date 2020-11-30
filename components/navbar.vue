<template>
  <div>
    <header class="">
      <b-navbar
        align-h="between"
        class="w-100 d-flex justify-content-between Cor-navbar"
      >
        <b-navbar-brand href="/" id="paginaInicial"
          ><img src="@/assets/vilo-icone.png" alt=""
        /></b-navbar-brand>

        <div id="menus">
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
                    <b-nav-item href="../about/">About</b-nav-item>
                    <b-nav-item href="../sobre/">Sobre</b-nav-item>
                    <b-nav-item href="../metodologia/">Metodologia</b-nav-item>
                    <b-nav-item href="../nossaequipe/">Nossa equipe</b-nav-item>
                    <b-nav-item
                      href="https://vilovicenzzi.wordpress.com/"
                      target="_blank"
                      >Blog</b-nav-item
                    >
                    <b-nav-item href="../fale-conosco/"
                      >Fale conosco</b-nav-item
                    >
                  </b-nav>
                </b-nav>
              </div>
            </b-sidebar>
          </div>

          <div id="menuGrande">
            <div class="px-3 py-2">
              <b-nav class="ml-auto">
                <b-nav class="d-flex">
                  <b-nav-item href="../about/">About</b-nav-item>
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
        </div>
      </b-navbar>
    </header>
  </div>
</template>

<script>
import Vue from "vue";
import { BootstrapVue, BootstrapVueIcons } from "bootstrap-vue";

Vue.use(BootstrapVue);
Vue.use(BootstrapVueIcons);

export default {
  data() {
    return {};
  },
};
</script>

<style lang="scss" scoped>
@import "@/assets/css/_variaveis.scss";
//regras do menu e interações
header {
  background-color: $cor-primaria;
}

#paginaInicial {
  a {
    color: $cor-secundaria;
    border-bottom: 3px solid $cor-primaria;
    box-sizing: content-box;
    margin: 5px;
    font-weight: none;

    &:hover {
      animation-name: none !important;
      animation-duration: none !important;
      animation-iteration-count: none !important;
      animation-timing-function: none !important;
      border-bottom-color: none !important;
      color: none !important;
    }
  }
}

#menus {
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
}

.overlay {
  position: fixed; /* Sit on top of the page content */
  display: none; /* Hidden by default */
  width: 100%; /* Full width (cover the whole page) */
  height: 100%; /* Full height (cover the whole page) */
  top: 0;
  left: 0;
  right: 0;
  bottom: 0;
  background-color: rgba(0, 0, 0, 0.5); /* Black background with opacity */
  z-index: 2; /* Specify a stack order in case you're using a different order for other elements */
  cursor: pointer; /* Add a pointer on hover */
}
</style>
