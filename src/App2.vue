<template>
  <div id="app">
	
<figure>
   <MyText msg="У нас только свежая выпечка, которую делаем мы сами своими, прямо вот да, руками!"/>
</figure>

    <MyButton msg="Понятно"/>

  </div>
</template>

<script>

import MyButton from './components/MyButton.vue'
import MyText from './components/MyText.vue'

export default {
  name: 'App',
  components: {
    MyButton,
	MyText
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
	text-top: 50px;
   }

   </style>

