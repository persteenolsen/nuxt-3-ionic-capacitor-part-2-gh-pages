<template>
  <IonPage>
  
    <IonHeader :translucent="true">
      <IonToolbar>
	  
        <IonTitle>Home</IonTitle>


      </IonToolbar>
	  
    </IonHeader>
	
    <IonContent class="ion-padding">
	
      <h1>Nuxt 3 Ionic using Capacitor and ready for IOS and Android</h1>
      <IonButton @click="router.push('/about')">
        About Page
      </IonButton>
	  
    </IonContent>
	
  </IonPage>
</template>
<script type="module" setup lang="ts">
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