<script setup>

</script>

<template>
  <div class="dphoneContainer">
    <a href="tel:+15864986935"><h1 class="dphoneNumber">586-498-6935</h1></a>
    <p>Schedule your dumpster today!</p>
  </div>
  <v-img
      class="junkRemovalImage"
      src="../assets/RemovalServicesPoster.Jpg"
      width="50%"
      height="auto"
      max-width="800"
      max-height="1500"
  />
</template>

<style scoped>

.dphoneContainer {
  display: flex;
  flex-direction: column;

}

.dphoneNumber {
  font-size: 5rem;
}

a {
  color: #68bd46;
  text-decoration: none;
}

@media screen and (max-width: 480px) {

  .dphoneNumber {
    display: flex;
    justify-content: center;
    font-size: xxx-large;
    margin-top: 5%;
  }

  .dphoneContainer p {
    font-size: x-large;

  }

}


</style>