<template>

<div id="good-stuff">
  <h1 class="center">Hello Family!</h1>
  <message></message>
  <calendar></calendar>
</div>
</template>

<script>
import Calendar from './Calendar'
import Message from './Message'
export default {
name: 'good-stuff',
components:{Calendar,Message},
data () {
  return {

  }
}
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style>
#good-stuff {

  display: flex;
  min-height: 100vh;
  flex-direction: column;
}
h1 {
  color: #656565;
}


</style>
