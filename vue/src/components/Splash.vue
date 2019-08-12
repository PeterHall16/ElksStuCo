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
    height: 92vh;
    top: 0;
    background: #EEE
}

h1 {
    margin: 5vw;
    padding: 3vw;
    width: 100%;
    word-spacing: 9999rem;
    text-align: left;
    font-size: 35pt;
    font-family: 'Montserrat', sans-serif;
    font-weight: 800;
    color: #2c3e50;
    /* background: #FFF; */
    text-shadow: 0px 0px 10px rgba(0,0,0,.1)
    /* border: 1px solid red; */
}

@media (min-width: 800px) {
    h1 {
        width: 50%;
        font-size: 35pt;
    }
}

@media (min-width: 300px) {
    h1 {
        font-size: 30pt;
    }
}
    
</style>

