<template>
  <div>
    <navbar />
    <!-- Bloco de acessibilidade -->
    <div class="accessibility-of-button">
      <!-- Bloco de acessibilidade que fica invisivel -->
      <div
        class="has-background-info py-2 px-2 is-flex coluna"
        :class="accessibilityVision"
      >
        <AccessibilityList
          :position="position"
          :backgroundColor="backgroundColor"
        />
      </div>
    </div>

    <!-- VLibras -->
    <VLibras :class="hiddenVLibrasAccessibility" />

      <Nuxt />


    <rodape />
  </div>
</template>

<script>
// Lista de acessibilidade: https://github.com/romulorodrigues/vue-accessibility-list
import AccessibilityList from "vue-accessibility-list/src/AccessibilityList.vue";
// VLibras: https://github.com/vue-a11y/vue-vlibras
import { VLibras } from "@vue-a11y/vlibras";
import navbar from "../components/navbar";
import rodape from "../components/rodape";
export default {
  components: {
    navbar,
    rodape,
    VLibras,
    AccessibilityList,
  },
  data: () => ({
    // Dados do componente acessibilidade
    accessibilityVisionBoolean: true,
    accessibilityVision: " is-hidden ",
    hiddenVLibrasAccessibility: "",
    // Dados do AccessibilityList
    position: "right",
    backgroundColor: "hsl(217, 71%, 53%)",
  }),
  methods: {
    // Método de abrir e fechar o componente de acessibilidade.
    openAccessibilityOptions() {
      this.accessibilityVisionBoolean = !this.accessibilityVisionBoolean;
      if (this.accessibilityVisionBoolean) {
        this.accessibilityVision = " is-hidden ";
        this.hiddenVLibrasAccessibility = "";
      } else {
        this.accessibilityVision = "";
        this.hiddenVLibrasAccessibility = "is-hidden";
      }
    },
  },
};
</script>

<style>
html {
  font-family: "Source Sans Pro", -apple-system, BlinkMacSystemFont, "Segoe UI",
    Roboto, "Helvetica Neue", Arial, sans-serif;
  font-size: 18px;
  word-spacing: 1px;
  -ms-text-size-adjust: 100%;
  -webkit-text-size-adjust: 100%;
  -moz-osx-font-smoothing: grayscale;
  -webkit-font-smoothing: antialiased;
  box-sizing: border-box;
}

*,
*::before,
*::after {
  box-sizing: border-box;
  margin: 0;
}

.coluna {
  flex-direction: column;
}

/* Posição do botão de acessibilidade */
.accessibility-of-button {
  z-index: 99999;
  position: fixed;
  right: 0;
  top: 7em;
}
/* Tira a altura padrão que os botões do Bulma tem */
.standard-size-button {
  height: auto;
}

</style>