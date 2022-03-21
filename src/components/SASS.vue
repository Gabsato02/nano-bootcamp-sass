<script setup>
import '../styles/sass.scss';
</script>

<template>
  <div class="sass">
    <h1 class="sass__title">Esse é um elemento estilizado em SASS</h1>

    <section class="sass__hierarchy">
      <p>Essa div poderia usar hierarquia.</p>
      <p>Lorem ipsum dolor sit amet.</p>
      <p>Lorem ipsum dolor sit amet consectetur, adipisicing elit.</p>
    </section>

    <section class="sass__image-wrapper">
      <img src="/assets/image2.jpg" />
    </section>

    <section class="sass__extend">
      <p>Essa div poderia usar um extend.</p>
    </section>

    <section class="sass__mixin">
      <p>Essa div poderia usar um mixin.</p>
    </section>
  </div>
</template>
