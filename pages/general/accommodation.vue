<template>
	<div >
		<v-container class="pa-6">
		<div data-aos="fade-up" data-aos-duration="700">
			<h1 class="text-h2 text-center py-6 ">Accommodation</h1>
			<v-row>
				<v-col class="mx-auto" cols="12" md="10">
					<strong><h1 class="text-h4 purple--text">contact information:</h1></strong>
		
					<v-list>
						<v-list-item>
							1. Balaji 9790146700
						</v-list-item>
					</v-list>

					<strong><h1 class="text-h4 purple--text">Travel and local other temple visit: </h1></strong>
		
					<v-list>
						<v-list-item>
							1. Sivasankar 8072584458
						</v-list-item>
					</v-list>
				</v-col>
			</v-row>

			<v-row>
				<v-col class="mx-auto" cols="12" md="10">
					<strong><h1 class="text-h4 purple--text">Food:</h1></strong>
					<br>
					<v-img class="mx-auto" width="500" src="/contactus/food.jpeg"></v-img>
				</v-col>

			</v-row>
		</div>
	</v-container>
	</div>
</template>

<script type="text/javascript">

	export default{
		layout:"page",
		data(){
			return{
				content:"Content Will Be Updated here"
			}
		},
		mounted(){
			let audio = document.getElementsByTagName('audio')
			audio[0].play()
		}
	}
</script>