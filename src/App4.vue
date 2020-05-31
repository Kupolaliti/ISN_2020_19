<template>
  <div id="app">
<figure>
   <MyText msg="Оставьте нам свой номер телефона и, возможно, вам перезвонит наш шеф-повар"/>
   <MyTextBox/>
</figure>
    <MyButton msg="Понятно"/>
  </div>
</template>

<script>

import MyButton from './components/MyButton.vue'
import MyTextBox from './components/MyTextBox.vue'
import MyText from './components/MyText.vue'

export default {
  name: 'App',
  components: {
    MyButton,
	MyText,
	MyTextBox
  }
}

</script>

<style>
   figure {
   width: 280px; 
	height: 400px;
    float: center; 
    margin: 5%; 
	margin-top: 50px;
    background: #ffc107; 
    border-radius: 5px; 
    padding: 2%; 
	text-align: center;
   }
   </style>

