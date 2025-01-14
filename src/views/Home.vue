<script setup lang="ts">

import { ref } from 'vue';
import Button from "primevue/button";
import Card from "primevue/card";

import TestCircle from "../assets/TestCircle.svg";







</script>


<template>
<div class=" bg-gray-600">
  <div class=" flex align-center justify-center y-9 ">
    <Card style="width: 25rem; overflow: hidden">
      <template #header>
          <img alt="user header" src="../assets/vue.svg" />
      </template>
      <template #title>Advanced Card</template>
      <template #subtitle>Card subtitle</template>
      <template #content>
          <p class="m-0">
              Lorem ipsum dolor sit amet, consectetur adipisicing elit. Inventore sed consequuntur error repudiandae numquam deserunt quisquam repellat libero asperiores earum nam nobis, culpa ratione quam perferendis esse, cupiditate neque
              quas!
          </p>
      </template>
      <template #footer>
          <div class="flex gap-4 mt-1">
              <Button label="Cancel" severity="secondary" outlined class="w-full" />
              <Button label="Save" class="w-full" />
          </div>
      </template>
    </Card>
  </div>

  
  <div class="w-64 h-64">
    <svg class="svg-icon w-full h-full" viewBox="0 0 317.46 321.73" xmlns="http://www.w3.org/2000/svg">
      <ellipse  id="Ellipse2" class="cls-1 color-white" cx="158.73" cy="160.87" rx="158.23" ry="160.37" />
      <circle id="Ellipse" class="cls-2 color-white" cx="158.73" cy="160.87" r="39.94"/>
    </svg>
  </div>

  <h1> TEST </h1>


</div>



  
</template>


<style scoped>
.cls-1 {
  fill: #ffffff;
  stroke: #231f20;
  stroke-width: 2;
  stroke-miterlimit: 10;
}

.cls-2 {
  fill: #231f20;
  stroke: #ffffff;
  stroke-width: 2;
  stroke-miterlimit: 10;
}

.svg-icon:hover #Ellipse {
  animation: jump 0.5s infinite alternate;
}

@keyframes jump {
  from {
    transform: translateY(0);
  }
  to {
    transform: translateY(-20px);
  }
}

</style>