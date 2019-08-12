<template>
    <div id="header">
      <font-awesome-icon class="icon" icon="home"/>
      <font-awesome-icon class="icon" icon="users"/>
      <font-awesome-icon class="icon" icon="calendar-alt"/>
      <font-awesome-icon class="icon" icon="dollar-sign"/>
      <font-awesome-icon class="icon" icon="envelope"/>
    </div>
</template>

<script>
import { library } from '@fortawesome/fontawesome-svg-core'
import { faDollarSign, faUsers, faCalendarAlt, faHome, faEnvelope } from '@fortawesome/free-solid-svg-icons'

library.add(faDollarSign, faUsers, faCalendarAlt, faHome, faEnvelope)


export default {
  name: 'Header',
  components: {
  }
}
</script>

<style scoped>
#header {
    display: flex;
    justify-content: space-around;
    align-items: center;
    height: 8vh;
    width: 100%;
    background: #FFF;
    box-shadow: 0px 0px 15px rgba(0,0,0,.1);
}

.icon { 
    font-size: 16pt;
    cursor: pointer;
    transition: all 100ms ease
}

.icon:hover {
    color: #EBC634
}
</style>

