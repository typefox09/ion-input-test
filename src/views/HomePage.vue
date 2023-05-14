<template>
  <ion-page>
    <ion-header :translucent="true">
      <ion-toolbar>
        <ion-title>Blank</ion-title>
      </ion-toolbar>
    </ion-header>

    <ion-content :fullscreen="true">
      <ion-header collapse="condense">
        <ion-toolbar>
          <ion-title size="large">Blank</ion-title>
        </ion-toolbar>
      </ion-header>

      <div id="container">
        <strong>Ready to create an app?</strong>
        <p>Start with Ionic <a target="_blank" rel="noopener noreferrer" href="https://ionicframework.com/docs/components">UI Components</a></p>
      </div>
      <ion-modal :is-open="true">
        <ion-header>
            <ion-toolbar>
              <ion-title size="large">Modal</ion-title>
            </ion-toolbar>
        </ion-header>
        <ion-content  class="ion-padding">
          <div class="">
            <h1>Section 1</h1>
            <p class="">Lorem ipsum dolor sit amet consectetur adipisicing elit. At voluptatum, maiores enim et voluptatibus eius, quo ratione, amet placeat saepe laboriosam similique nam. Cum quasi similique quidem distinctio, rem maiores.</p>
            <h1>Section 2</h1>
            <p class="">Lorem ipsum dolor sit amet consectetur adipisicing elit. At voluptatum, maiores enim et voluptatibus eius, quo ratione, amet placeat saepe laboriosam similique nam. Cum quasi similique quidem distinctio, rem maiores.</p>
            <div class="">
              <ion-input  mode="md" label="Hashtags (optional)"   placeholder="#laptop #green"></ion-input>
            </div>
           <h1>Section 3</h1>
            <p class="">Lorem ipsum dolor sit amet consectetur adipisicing elit. At voluptatum, maiores enim et voluptatibus eius, quo ratione, amet placeat saepe laboriosam similique nam. Cum quasi similique quidem distinctio, rem maiores.</p>
          </div>
        </ion-content>
      </ion-modal>
    </ion-content>
  </ion-page>
</template>

<script setup lang="ts">
import { IonContent, IonHeader, IonPage, IonTitle, IonToolbar, IonModal, IonInput } from '@ionic/vue';
</script>

<style scoped>
#container {
  text-align: center;
  
  position: absolute;
  left: 0;
  right: 0;
  top: 50%;
  transform: translateY(-50%);
}

#container strong {
  font-size: 20px;
  line-height: 26px;
}

#container p {
  font-size: 16px;
  line-height: 22px;
  
  color: #8c8c8c;
  
  margin: 0;
}

#container a {
  text-decoration: none;
}
</style>