<template>
  <!--<img id="banner" src="../assets/img/banner.jpg" alt="persone che mangiano">-->
  <div class="conteniner-menu">
    <h1>IT'S PIZZA TIME!</h1>
    <div class="menu">
      <h2>Sfoglia il nostro menù</h2>
      <PizzaCardComponent />
      <PizzaCardComponent />
      <PizzaCardComponent />
      <PizzaCardComponent />
      <PizzaCardComponent />
      <PizzaCardComponent />
    </div>
  </div>
</template>

<script>
import "/src/assets/styles/components/MenuComponent.scss";
import PizzaCardComponent from "./PizzaCardComponent.vue";

export default {
  name: "MenuComponent",
  components: {
    PizzaCardComponent,
  },
};
</script>
