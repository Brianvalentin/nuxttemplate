<template>
	<div>
		<v-container>
			<h1 class="text-h4 mb-6 text-center">Facilities for devotees</h1>
			<v-row>
				<v-col class="mx-auto" cols="12" md="10">
					<strong><h1 class="text-h4 titletext">New Facilities Provided For the Devotees</h1></strong>
					<p class="text-h6 pt-2 ">1.Place for devotess to sit in parkaras</p>
					<p class="text-h6  ">2. New Pratiksha Darshana Mandapa (Waiting Hall)</p>
					<p class="text-h6 ">2. New Pratiksha Darshana Mandapa (Waiting Hall)</p>
				</v-col>
			</v-row>
		</v-container>
	</div>
</template>

<script type="text/javascript">
	export default{
		layout: "page",
		mounted(){
			let audio = document.getElementsByTagName('audio')
			audio[0].play()
		}
	}
</script>

<style lang="css" scoped>
	.titletext{
		background-color: lightgrey;
		border-radius: 3px;
		padding: 10px;
	}
</style>