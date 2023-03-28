<script setup>
import { ref } from 'vue'

const step = 1;
</script>

<template>
  <h1>Bienvenue sur le guide de la PWA ! 🤩</h1>

  <div class="card">
    <p>
      Ce guide vous permettra d'en savoir plus et de vous expliquer comment installer une PWA.

      Tout d'abord, voici les prérequis :
      <ul>
        <li>Avoir un navigateur qui prends en charge les PWA comme Google Chrome, Firefox, Edge ou Safari.</li>
        <li>Il faut s'assurer qu'ils soient à jour.</li>
        <li>Il faut que le site en question permette l'installation d'une PWA.</li>
      </ul>
    </p>
    <p>
      Pour installer une PWA, cela depend de votre navigateur. Le plus souvent, il y a une flèche "Installer" et ensuite il y a juste à suivre les instructions.
    </p>
    <p>
      Si vous êtes sur cette page, c'est que vous avez déjà entendu parler des PWA. Ces applications ont plusieurs atouts :
      <ul >
        <li>Elles permettent d'avoir une application qui a le comportament d'une application native sans en être une. Elle est donc compatible avec toutes les plateformes</li>
        <li>Elles permettent d'avoir une application plus rapide</li>
        <li>Elles peuvent fonctionner sans internet (à part pour l'installation)</li>
        <li>Elles sont facile à installer : pas besoin d'aller dans le store d'application et de se rappeler du nom 😉</li>
        <li>Elles sont mise à jour automatiquement (pas comme une application du store - les mises à jour automatique désactivées 🙃)</li>
        <li>Elles permettent d'utiliser des fonctionnalités de l'appareil comme les notifications, le vibreur et autres.</li>
      </ul>
    </p>
    <p>
      En conclusion, les PWA c'est génial ! 😍
    </p>
  </div>
</template>

<style scoped>
</style>
