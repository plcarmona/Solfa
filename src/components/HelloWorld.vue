<script setup>
defineProps({
  msg: {
    type: String,
    required: true
  }
})
</script>

<template>
  <div class="greetings">
    <divv> 

        <img alt="Vue logo" class="logo" src="@/assets/turtlelogo.png" width="50" height="50" />
        <h1 class="green">
            SOLFA</h1>
        </divv>
    <h3>
      Servicio de contabilidad y remuneraciones
    </h3>
  </div>
</template>

<style scoped>
divv {
  display: flex;
  flex-direction: row;
  align-items: center;
  justify-content: center;
  height: 100%;
}
h1 {
  font-weight: 500;
  font-size: 2.6rem;
  top: 0px;
  font-family: 'Tilt Prism';

}

h3 {
  font-size: 1.2rem;
}

.greetings h1,
.greetings h3 {
  text-align: center;
}

@media (min-width: 1024px) {
  .greetings h1,
  .greetings h3 {
    text-align: left;
  }
}
</style>
