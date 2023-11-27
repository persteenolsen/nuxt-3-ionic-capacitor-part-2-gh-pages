<template>
  <IonPage>
    <IonHeader :translucent="true">
      <IonToolbar>
        <IonTitle>Home</IonTitle>
      </IonToolbar>
    </IonHeader>
    <IonContent class="ion-padding">
      <h1>This is the about page</h1>
      <IonButton @click="router.back()">
	    Go Home
      </IonButton>
	  <br /> <br />Last updated: <b>27-11-2023</b><br />
		  
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