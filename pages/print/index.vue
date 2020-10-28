<template>
	<div>
		<v-container class="pa-3">
			<h1 class="title--h4 text-center">Print</h1>
			<v-row class="pa-3" wrap>
				<v-col class="mx-auto" cols="12" md="8" height="100vh">
					<v-carousel height="auto" cycle hide-delimiter-background  delimiter-icon="mdi-minus">
						<v-carousel-item >
							<v-img src="/print/1.jpeg"></v-img>
						</v-carousel-item>
						<v-carousel-item >
							<v-img src="/print/2.jpeg"></v-img>
						</v-carousel-item>
						<v-carousel-item >
							<v-img src="/print/3.jpeg"></v-img>
						</v-carousel-item>
						<v-carousel-item >
							<v-img src="/print/4.jpeg"></v-img>
						</v-carousel-item>
						<v-carousel-item >
							<v-img src="/print/5.jpeg"></v-img>
						</v-carousel-item>
						<v-carousel-item >
							<v-img src="/print/6.jpeg"></v-img>
						</v-carousel-item>
						<v-carousel-item >
							<v-img src="/print/7.jpeg"></v-img>
						</v-carousel-item>
						<v-carousel-item >
							<v-img src="/print/8.jpeg"></v-img>
						</v-carousel-item>
					</v-carousel>
				</v-col>
			</v-row>
</v-container>
</div>
</template>

<script type="text/javascript">
	export default{
		layout:"page",
		data:()=>({
			
		}),
		mounted(){
			let audio = document.getElementsByTagName('audio')
			audio[0].play()
		}
	}
</script>

<!-- <v-col cols="12">
					<v-card
					class="mx-auto"
					max-width="500"
					>
					<v-img
					src="https://cdn.vuetifyjs.com/images/cards/sunshine.jpg"
					height="200px"
					></v-img>

					<v-card-title>
						Top western road trips
					</v-card-title>

					<v-card-subtitle>
						1,000 miles of wonder
					</v-card-subtitle>

					<v-card-actions>
						<v-btn
						color="orange lighten-2"
						text
						>
						Explore
					</v-btn>

					<v-spacer></v-spacer>

					<v-btn icon @click="" >

					</v-btn>
				</v-card-actions>
			</v-card>
			</v-col> -->