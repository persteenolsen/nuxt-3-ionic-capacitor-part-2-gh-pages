<template>
  <IonPage>
  
    <IonHeader :translucent="true">
      <IonToolbar>
	  
       <IonToolbar>
        <IonTitle>
		     <a href="#" @click="router.push('/')" target="_top">Home</a> | 
		     <a href="#" @click="router.push('/about')" target="_top">About</a>
		    </IonTitle>
      </IonToolbar>

      </IonToolbar>
	  
    </IonHeader>
	
    <IonContent class="ion-padding">
	
      <h1>This is the HOME Page</h1>
	  
	   <IonButton @click="router.push('/about')">
        About Page
      </IonButton>
	  
	    <h4>Nuxt 3 Ionic using Capacitor and ready for IOS and Android</h4>
	      
	  
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