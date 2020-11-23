<template>
  <div>
    <div>
      <b-navbar align-h="between" class="w-100 d-flex justify-content-between">
        <b-navbar-brand href="/"> Vilo Vincenzzi </b-navbar-brand>

        <div id="menuPequeno">
          <b-button
            v-b-toggle.sidebar-right
            class="menu"
            variant="outline-dark"
          >
            <b-icon icon="grid-fill"></b-icon>
          </b-button>
          <b-sidebar id="sidebar-right" title="Menu" right shadow>
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
a {
  color: rgb(70, 70, 70);
  border-bottom: 3px solid #f8f9fa;
  box-sizing: content-box;
  margin: 5px;
  font-weight: 600;

  &:hover {
    animation-name: simple-border;
    animation-duration: 0.5s;
    animation-iteration-count: 1;
    animation-timing-function: ease-in;
    border-bottom-color: black;
    color: black;
  }
}

@keyframes simple-border {
  from {
    border-bottom-color: #f8f9fa;
  }
  to {
    border-bottom-color: black;
  }
}

//cor do menu
.bg-info {
  background-color: #ffffff !important;
}

.navbar-dark .navbar-brand {
  color: rgb(0, 0, 0);
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

@media screen and (max-width: 720px) {
  #menuGrande {
    display: none;
  }

  #menuPequeno {
    display: inherit;
  }
}
</style>
