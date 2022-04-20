<template>
  <div>
<TheNavBar />
<TheHeader />


  </div>

</template>

<script>

import TheHeader from './components/TheHeader.vue'
import TheNavBar from './components/TheNavBar.vue'

export default {
  name: 'App',
  components: {
    
    TheHeader,
    TheNavBar,
}
}
</script>

