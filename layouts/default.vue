<template>
  <div>
    <navbar />
    <!-- Bloco de acessibilidade -->
    <div class="acessibilidade">
      <!-- Bloco de acessibilidade que fica invisivel -->
      <div :class="accessibilityVision">
        <AccessibilityList
          :position="position"
          :backgroundColor="backgroundColor"
          :border-radius="borderRadius"
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
    backgroundColor: "rgb(230, 230, 230)",
    borderRadius: "20px"
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
html,body {
  font-family: "Source Sans Pro", -apple-system, BlinkMacSystemFont, "Segoe UI",
    Roboto, "Helvetica Neue", Arial, sans-serif;
  font-size: 18px;
  word-spacing: 1px;
  -ms-text-size-adjust: 100%;
  -webkit-text-size-adjust: 100%;
  -moz-osx-font-smoothing: grayscale;
  -webkit-font-smoothing: antialiased;
  box-sizing: border-box;
  background-color: rgba(184, 184, 184, 0.041);
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

</style>