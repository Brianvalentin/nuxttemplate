<template>
	<div>
		<v-container class="pa-3">
			<h1 class="title--h4 text-center">Media</h1>
			<v-row class="pa-3" wrap>
				<v-col class="mx-auto" cols="12" md="8">
					<v-carousel height="auto" cycle hide-delimiter-background  delimiter-icon="mdi-minus">
						<v-carousel-item >
							<v-img src="/print/9.jpeg"></v-img>
						</v-carousel-item>
						<v-carousel-item >
							<v-img src="/print/10.jpeg"></v-img>
						</v-carousel-item>
						<v-carousel-item >
							<v-img src="/print/11.jpeg"></v-img>
						</v-carousel-item>
						<v-carousel-item >
							<v-img src="/print/12.jpeg"></v-img>
						</v-carousel-item>
						<v-carousel-item >
							<v-img src="/print/13.jpeg"></v-img>
						</v-carousel-item>
						<v-carousel-item >
							<v-img src="/print/14.jpeg"></v-img>
						</v-carousel-item>
						<v-carousel-item >
							<v-img src="/print/15.jpeg"></v-img>
						</v-carousel-item>
						<v-carousel-item >
							<v-img src="/print/16.jpeg"></v-img>
						</v-carousel-item>
						<v-carousel-item >
							<v-img src="/print/17.jpeg"></v-img>
						</v-carousel-item>
						<v-carousel-item >
							<v-img src="/print/18.jpeg"></v-img>
						</v-carousel-item>
						<v-carousel-item >
							<v-img src="/print/19.jpeg"></v-img>
						</v-carousel-item>
						<v-carousel-item >
							<v-img src="/print/20.jpeg"></v-img>
						</v-carousel-item>
						<v-carousel-item >
							<v-img src="/print/21.jpeg"></v-img>
						</v-carousel-item>
						<v-carousel-item >
							<v-img src="/print/22.jpeg"></v-img>
						</v-carousel-item>
						<v-carousel-item >
							<v-img src="/print/23.jpeg"></v-img>
						</v-carousel-item>
						<v-carousel-item >
							<v-img src="/print/24.jpeg"></v-img>
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
