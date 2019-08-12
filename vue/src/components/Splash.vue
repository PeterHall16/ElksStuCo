<template>
    <div id="splash">
        <h1>{{ SplashText }}</h1>
    </div>
</template>

<script>

export default {
  name: 'Splash',
  components: {
  },
  props: {
      SplashText: String
  }
}
</script>

<style scoped>
#splash {
    display: flex;
    align-items: center;
    width: 100%;
    height: 92%;
    top: 0;
    background: #EEE
}

h1 {
    margin: 5vw;
    width: 60%;
    text-align: left;
    font-size: 35pt;
    font-family: 'Montserrat', sans-serif;
    font-weight: 800;
    color: #2c3e50;
    text-shadow: 0px 0px 10px rgba(0,0,0,.1)
    /* border: 1px solid red; */
}

</style>

