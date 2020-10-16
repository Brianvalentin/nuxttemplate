<template>
	<div data-aos="slide-up" data-aos-duration="1000">
		<v-container class="pa-3" >
			<h1 class="text--h2 text-center">Section 1</h1>
			<v-row wrap  >

				<v-col  cols="6" md="3" v-for="(i,index) in 8" :key="index" >
					<v-img lazy-src src="/profile.jpg"></v-img>
				</v-col>
			</v-row>
		</v-container>

		<v-container class="pa-3">
			<h1 class="text--h2 text-center">Section 2</h1>
			<v-row wrap>

				<v-col cols="6" md="3" v-for="(i,index) in 8" :key="index" >
					<v-img lazy-src src="profile.jpg"></v-img>
				</v-col>
			</v-row>
		</v-container>

		<v-container class="pa-3">
			<h1 class="text--h2 text-center">Section 3</h1>
			<v-row wrap>

				<v-col cols="6" md="3" v-for="(i,index) in 8" :key="index" >
					<v-img lazy-src src="profile.jpg"></v-img>
				</v-col>
			</v-row>
		</v-container>
	</div>
</template>

<script type="text/javascript">
	export default{
		data(){
			return{
				section1:[
				{
					"id":1,
					"img":"https://wiredstore.now.sh/img1.jpeg"
				},
				{
					"id":1,
					"img":"https://wiredstore.now.sh/img1.jpeg"
				},
				{
					"id":1,
					"img":"https://wiredstore.now.sh/img1.jpeg"
				},
				{
					"id":1,
					"img":"https://wiredstore.now.sh/img1.jpeg"
				},
				]
			}
		}
	}
</script>