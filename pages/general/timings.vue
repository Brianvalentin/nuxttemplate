<template>
	<div>
		<v-container>
			<h1 class="text-h2 text-center">Timings</h1>
			<v-row>
				<v-col class="mx-auto" cols="12" md="10">
					<strong><h1 class="text-h4 titletext">Abhishekam (Daily Three Times)</h1></strong>
					<p class="text-h6 pt-2 ">1. Morning: 5:30 AM</p>
					<p class="text-h6">2. Morning: 10:30 AM</p>
					<p class="text-h6">3. Evening: 4:00 PM</p>

					<strong><h1 class="text-h4  titletext">Chandana Alankara</h1></strong>
					<p class="text-h6 pt-2 ">1. Evening: 4:30 PM on all Wednesdays and Saturdays</p>

					<strong><h1 class="text-h4  titletext">Navavarana Pooja on Paurnamis</h1></strong>
					<p class="text-h6 pt-2 ">1. After 9:30 PM on all months</p>

					<strong><h1 class="text-h4  titletext">Sahasranaama Archana (Daily)</h1></strong>
					<p class="text-h6 pt-2 ">1. Morning: 9:00 AM - 10:00 AM </p>
					<p class="text-h6  ">2. Evening: 7:00 PM - 8:00 PM </p>

					<strong><h1 class="text-h4  titletext">Ashtotthara Archana</h1></strong>
					<p class="text-h6 pt-2 ">1. Morning: 7:00 AM - 12:00 Noon </p>
					<p class="text-h6  ">2. Evening: 6:00 PM - 8:00 PM </p>

					<strong><h1 class="text-h4  titletext">Swarna Ratha </h1></strong>
					<p class="text-h6 pt-2 ">1. All Fridays</p>
					<p class="text-h6  ">2. 1 day of Tamil Months, Amavasya Paurnami, Poora Nakshatra </p>

					<p class="text-h6 blue--text ">* The Above Timings will be changed in festival periods</p>
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