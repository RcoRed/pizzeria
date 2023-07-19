<template>
    <form>
        <div>
            <input type="text" id="name" name="name" placeholder="Nome">
            <input type="text" id="surname" name="surname" placeholder="Cognome">
        </div>
        <div>
            <input type="email" id="email" name="email" placeholder="email@email.email">
            <input type="tel" id="phone" name="phone" placeholder="Numero di contatto">
            <input type="text" id="address" name="address" placeholder="Indirizzo">
        </div>
        <div>
            <textarea name="order" id="order" placeholder="Inserisci qui il tuo ordine!"></textarea>
        </div>
        <div>
            <button type="submit">Ordina ora!</button>
            <button type="reset">cancella</button>
        </div>
    </form>
  </template>

  <script>
  import "/src/assets/styles/components/FormComponent.scss";

  export default {
    name: "FormComponent",
  };
  </script>