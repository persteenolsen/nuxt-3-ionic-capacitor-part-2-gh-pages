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
	    Home
      </IonButton>
	  
	  <br /> <br />Last updated: <b>01-12-2023</b><br /><br /><br />
	  
	  
	  Some usefull links for building this application:
   <ion-list>
   
   <ion-item>
      <ion-label>
	   <a target="_blank" rel="noopener noreferrer" href="https://nuxt.com">Nuxt 3 - The Intuitive Vue Framework</a>
	   </ion-label>
    </ion-item>
		
	
    <ion-item>
      <ion-label>
	   <a target="_blank" rel="noopener noreferrer" href="https://vuejs.org">Vue 3 - The Progressive JavaScript Framework</a>
	   </ion-label>
    </ion-item>
	
	
    <ion-item>
      <ion-label>
	   <a target="_blank" rel="noopener noreferrer" href="https://ionicframework.com/">The Ionic Framework</a>
	   </ion-label>
    </ion-item>
   
   
    <ion-item>
      <ion-label>
	   <a target="_blank" rel="noopener noreferrer" href="https://ionic.nuxtjs.org">Nuxt / Ionic</a>
	   </ion-label>
    </ion-item>
	
	
    <ion-item>
      <ion-label>
	   <a target="_blank" rel="noopener noreferrer" href="https://capacitorjs.com">Capacitor - Runtime for Native Web Apps</a>
	   </ion-label>
    </ion-item>
	   
	
    <ion-item>
      <ion-label>
	   <a target="_blank" rel="noopener noreferrer" href="https://nitro.unjs.io">Nitro.js - Web server that runs everywhere</a>
	   </ion-label>
    </ion-item>
	
	
    <ion-item>
      <ion-label>
	   <a target="_blank" rel="noopener noreferrer" href="https://vitejs.dev">Vite - Next Generation Frontend Tooling</a>
	   </ion-label>
    </ion-item>
	
	
    <ion-item>
      <ion-label>
	   <a target="_blank" rel="noopener noreferrer" href="https://marketplace.visualstudio.com/items?itemName=ionic.ionic">The Ionic Visual Studio Code Extention</a>
	   </ion-label>
    </ion-item>
	
	
	
  </ion-list>	  
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
  IonButton,
  IonItem, 
  IonLabel, 
  IonList
} from "@ionic/vue"

const router = useRouter();
</script>