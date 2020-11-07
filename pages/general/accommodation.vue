<template>
	<div>
		<v-container>
			<h1 class="text-h4 mb-6 text-center">Accommodation</h1>
			<v-row>
				<v-col class="mx-auto" cols="12" md="10">
					<strong><h1 class="text-h4 titletext">Contact Information</h1></strong>
					<p class="text-h6 pt-2 ">1. Balaji Iyer Call:9790146700</p>

					<strong><h1 class="text-h4  titletext">Travel and Local other Temple Visit</h1></strong>
					<p class="text-h6 pt-2 ">1. Sivasankar call: 8072584458</p>

					<strong><h1 class="text-h4  titletext">Food</h1></strong>
					<p class="text-h5 pt-2 ">CK Mess & Catering (Pure Vegetarien)</p>
					<p class=" ml-6 ">Balaji Iyer Call:9790146700</p>
					<p class=" ml-6 ">Chitra Call:7010448558</p>
					<p class=" ml-6 ">No.18/21, North Mada Street,</p>
					<p class=" ml-6 ">Near Kamakshi Amman North Gopuram</p>
					<p class=" ml-6 ">Big Kanchipuram- 631 501.</p>

					
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