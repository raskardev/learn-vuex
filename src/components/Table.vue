<template>
  <table class="table table-bordered">
  <thead>
    <tr>
      <th scope="col">Plato</th>
      <th scope="col">Tipo de cocina</th>
      <th scope="col">Precio</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td scope="row">Macarrones</td>
      <td>Italiana</td>
      <td>5€</td>
      <td>
        <button class="btn btn-primary">Añadir</button>
      </td>
    </tr>
    <tr>
      <td scope="row">Paella</td>
      <td>Española</td>
      <td>7€</td>
      <td>
        <button class="btn btn-primary">Añadir</button>
      </td>
    </tr>
    <tr>
      <td scope="row">Pollo crujiente</td>
      <td>Hamburguesa</td>
      <td>4€</td>
      <td>
        <button class="btn btn-primary">Añadir</button>
      </td>
    </tr>
  </tbody>
</table>
</template>

<script>
export default {
  name: "Table"
};
</script>

<style>
</style>
