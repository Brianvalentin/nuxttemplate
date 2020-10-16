<template>
	<div data-aos="fade-up-right" data-aos-duration="1000">
		<v-container >
			<h1 class="text-h3 text-center py-2">Gallery</h1>
			<v-row wrap>
				<v-col id="image" cols="6" md="3" v-for=" i in 8" :key="i">
					<v-img src="/profile.jpg">
				</v-img>
				<div class="text-center">Caption Content</div>
			</v-col>
		</v-row>
	</v-container>
</div>
</template>

<script type="text/javascript">
	export default{
		data(){
			return{

			}
		}
	}
</script>

<style lang="css" scoped>
/*#overlay{
	color: white;
	position: absolute;
	bottom:10px;
	display: none;
}
#overlay:hover{

	display: block;
}*/
#image{
	padding: 10px
}
#image:hover{
	transition: 300ms;
	padding: 5px;
}
</style>