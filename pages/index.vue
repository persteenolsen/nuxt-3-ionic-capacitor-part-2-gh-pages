<template>
  <IonPage>
    <IonHeader :translucent="true">
      <IonToolbar>
        <IonTitle>Home</IonTitle>
      </IonToolbar>
    </IonHeader>
    <IonContent class="ion-padding">
      <h1>Welcome HOME with Nuxt 3 Ionic Capacitor ready for IOS and Android</h1>
      <IonButton @click="router.push('/about')">
        Goto About Page
      </IonButton>
    </IonContent>
  </IonPage>
</template>
<script setup lang="ts">
import {
  IonPage,
  IonHeader,
  IonTitle,
  IonToolbar,
  IonContent,
  IonButton
} from "@ionic/vue"

const router = useRouter();
</script>