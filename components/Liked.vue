<template>
	<div class="w-full h-12 flex flex-row gap-2 ">
		<div class="flex flex-1 flex-row items-center justify-center gap-2 cursor-pointer transition-all bg-red-100 text-red-400 rounded hover:bg-red-300 hover:text-red-600">
			<svg xmlns="http://www.w3.org/2000/svg" class="h-8 w-8" fill="none" viewBox="0 0 24 24" stroke="currentColor" stroke-width="2">
				<path stroke-linecap="round" stroke-linejoin="round" d="M10 14H5.236a2 2 0 01-1.789-2.894l3.5-7A2 2 0 018.736 3h4.018a2 2 0 01.485.06l3.76.94m-7 10v5a2 2 0 002 2h.096c.5 0 .905-.405.905-.904 0-.715.211-1.413.608-2.008L17 13V4m-7 10h2m5-10h2a2 2 0 012 2v6a2 2 0 01-2 2h-2.5" />
			</svg>
			<span>Não Gostei</span>
		</div>
		<div class="flex flex-1 flex-row items-center justify-center gap-2 cursor-pointer transition-all bg-green-100 text-green-400 rounded hover:bg-green-300 hover:text-green-600">
			<svg xmlns="http://www.w3.org/2000/svg" class="h-8 w-8" fill="none" viewBox="0 0 24 24" stroke="currentColor" stroke-width="2">
				<path stroke-linecap="round" stroke-linejoin="round" d="M14 10h4.764a2 2 0 011.789 2.894l-3.5 7A2 2 0 0115.263 21h-4.017c-.163 0-.326-.02-.485-.06L7 20m7-10V5a2 2 0 00-2-2h-.095c-.5 0-.905.405-.905.905 0 .714-.211 1.412-.608 2.006L7 11v9m7-10h-2M7 20H5a2 2 0 01-2-2v-6a2 2 0 012-2h2.5" />
			</svg>
			<span>Gostei</span>
		</div>
	</div>
</template>

<script>
export default {

  name: 'Liked',

  data () {
    return {

    }
  }
}
</script>

<style lang="css" scoped>
</style>