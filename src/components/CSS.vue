<script setup>
import '../styles/css.css';
</script>

<template>
  <div class="css">
    <h1 class="css-title">Esse é um elemento estilizado em CSS</h1>

    <section class="css-hierarchy">
      <p>Essa div poderia usar hierarquia.</p>
      <p>Lorem ipsum dolor sit amet.</p>
      <p>Lorem ipsum dolor sit amet consectetur, adipisicing elit.</p>
    </section>

    <section class="css-image-wrapper">
      <img src="/assets/image.jpg" />
    </section>

    <section class="css-extend">
      <p>Essa div poderia usar um extend.</p>
    </section>

    <section class="css-mixin">
      <p>Essa div poderia usar um mixin.</p>
    </section>
  </div>
</template>
