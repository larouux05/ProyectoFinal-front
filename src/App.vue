<template>
  <div class="app">
    <ul>
      <li>
        <router-link to="/auth/login">LOGIN</router-link>
      </li>
      <li>
        <router-link to="/auth/register">REGISTER</router-link>
      </li>
      <li>
        <router-link to="/">HOME</router-link>
      </li>
      <li>
        <router-link to="/detalle">DETALLE HOME</router-link>
      </li>
      <li>
        <router-link to="/pago/checkout">PAGO / CHECKOUT</router-link>
      </li>
      <li>
        <router-link to="/pago/tarjeta-de-credito">PAGO / TARJETA DE CREDITO</router-link>
      </li>
      <li>
        <router-link to="/pago/tarjeta-de-debito">PAGO / TARJETA DE DEBITO</router-link>
      </li>
      <li>
        <router-link to="/pago/efectivo">PAGO / PAGO EFECTIVO</router-link>
      </li>
      <li>
        <router-link to="/pago/resumen">PAGO / COMPRA RESUMEN</router-link>
      </li>
    </ul>
    <router-view></router-view>
  </div>
</template>
<script>
export default {
  name: "App",
};
</script>
<style lang="scss" scoped>
</style>