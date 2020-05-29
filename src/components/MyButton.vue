<template>

	<b-button block variant="warning">{{ msg }}</b-button>
	
</template>

<script>
export default {
  name: 'MyButton',
  props: {
    msg: String
  }
}
</script>

<style>
body {
  box-sizing: border-box;
}

}