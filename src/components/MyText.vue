<template>

	 <p>{{msg}}</p>
	
</template>

<script>
export default {
  name: 'MyText',
  props: {
    msg: String
  }
}
</script>

<style>
p{
font-family: Suranna;
font-style: normal;
font-weight: normal;
font-size: 24px;
line-height: 53px;
text-align: center;
letter-spacing: 0.04em;
color: #FFFAFA;
}
</style>
}