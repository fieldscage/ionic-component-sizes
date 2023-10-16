<template>
  <ion-app>
    <ion-router-outlet />
  </ion-app>
</template>

<script setup lang="ts">
import { IonApp, IonRouterOutlet } from '@ionic/vue';
</script>

<style lang="css">
html {
    font-size: 10px;
}

body {
    font-size: 1.6rem;
}

#example-size {
    width: 12rem;
    height: 12rem;
    margin: 2rem auto;
    background-color: var(--ion-color-secondary);
    border-radius: 6rem;
}
</style>
