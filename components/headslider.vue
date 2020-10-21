<template>
	<div>
		<v-carousel
		cycle
		hide-delimiter-background
		hide-delimiters	
		show-arrows-on-hover
		height="440"
		>
		<v-carousel-item
		v-for="(slide, i) in slides"
		:key="i"
		:src="slide.src">

<!-- 		<v-row class="fill-height" align="center" justify="center">
			<div class="display-3 font-weight-black pa-3 text-center" style="text-shadow: 1px 1px 20px black" >
				
			</div>
		</v-row> -->

	</v-carousel-item>
</v-carousel>
</div>
</template>

<script>
	export default{
		data(){
			return{
				slides:[
				{
					'src':'/indeximg/banner1.jpeg'
				},
				{
					'src':'/indeximg/banner33.jpg'
				},
				{
					'src':'/indeximg/banner3.jpg'
				},
				]
			}
		},

	}
</script>