<template>
  <HeaderComponent />
  <MenuComponent />
  <FormComponent />
  <FooterComponent />
</template>

<script>
import HeaderComponent from "./components/HeaderComponent.vue";
import MenuComponent from "./components/MenuComponent.vue";
import FormComponent from "./components/FormComponent.vue";
import FooterComponent from "./components/FooterComponent.vue";
import "/src/assets/styles/global.scss";

export default {
  name: "App",
  components: {
    HeaderComponent,
    MenuComponent,
    FormComponent,
    FooterComponent,
  },
};
</script>
