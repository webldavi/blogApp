<template>
	<button @click="backPage()">
		<svg xmlns="http://www.w3.org/2000/svg" class="h-10 w-10 text-white" fill="none" viewBox="0 0 24 24" stroke="currentColor" stroke-width="2">
  			<path stroke-linecap="round" stroke-linejoin="round" d="M11 15l-3-3m0 0l3-3m-3 3h8M3 12a9 9 0 1118 0 9 9 0 01-18 0z" />
		</svg>
	</button>
</template>

<script>
export default {

  name: 'BackButton',

  data () {
    return {

    }
  },
  methods:{
  	backPage(){
  		this.$router.go(-1 || '/')
  		
  	}
  }
}
</script>

<style lang="css" scoped>
</style>