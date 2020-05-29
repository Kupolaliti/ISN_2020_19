<template>
  <div id="app">
	
<figure>

   <MyPicture/>
   <MyText msg="За кис-кис отвечаю!" />
   
</figure>

    <MyButton msg="Хорошо"/>

  </div>
</template>

<script>

import MyButton from './components/MyButton.vue'
import MyPicture from './components/MyPicture.vue'
import MyText from './components/MyText.vue'

export default {
  name: 'App',
  components: {
    MyButton,
	MyPicture,
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
   }

   </style>

