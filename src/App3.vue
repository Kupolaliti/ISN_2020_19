<template>
  <div id="app">
	<h>"Хлепница"<MyButton msg="Заходи!"/></h>


    

  </div>
</template>

<script>

import MyButton from './components/MyButton.vue'

export default {
  name: 'App',
  components: {
    MyButton
  }
}

</script>

<style>
    h{
	position: absolute;
	width: 283px;
	height: 105px;
	left: 22px;
	top: 250px;
	font-family: Suranna;
	font-style: normal;
	font-weight: normal;
	font-size: 48px;
	line-height: 105px;
	text-align: center;
	letter-spacing: 0.04em;
	text-shadow: white 0 0 7px;
   }
   
</style>

