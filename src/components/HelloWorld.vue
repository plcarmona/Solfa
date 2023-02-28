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

        <img alt="Vue logo" class="logo" src="@/assets/turtlelogoo.png" width="200" height="200" />
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
  flex-direction: column ;
  align-items: center;
  justify-content: center;
  height: 100%;
  background-color: rgb(82, 82, 82);
  border-radius: 10px;
  margin-left: 15vh;
    margin-right: 15vh;
}
h1 {
  font-weight: 500;
  font-size: 2.6rem;
  top: 0px;
  font-family: 'Roboto', sans-serif;
  color: #dadada;

}
/*align the text in h3 with divv*/

h3 {
    font-size: 0.7rem;
    font-weight: 500;
    font-family: 'Roboto', sans-serif;
  
  
}
.div{
    align-items: center;
    justify-content: center;
    display: flex;


}
.greetings h1,
.greetings h3 {
  text-align: center;
}

@media (min-width: 1024px) {
  .greetings h1,
  .greetings h3 {
    text-align: center;
  }
}
</style>
