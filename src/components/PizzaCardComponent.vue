<template>
  <div class="card">
    <img src="../assets/img/margherita.png" alt="pizza margherita" />

    <div class="info-pizza">
      <h3>MARGHERITA</h3>
      <div class="ingredients">
        <h4>Ingredienti:</h4>
        <ul>
          <li>pomodoro</li>
          <li>mozzarella</li>
          <li>basilico</li>
        </ul>
      </div>
      <p>6€</p>
    </div>
  </div>
</template>

<script>
import "/src/assets/styles/components/PizzaCardComponent.scss";
export default {
  name: "PizzaCardComponent",
};
</script>
