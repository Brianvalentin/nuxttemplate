<template>
	<div>
		<div data-aos="slide-up" data-aos-duration="1000">
			<v-container class="pa-3" >
				<h1 class="text--h3 text-center">Temple Photos</h1>
				<v-row wrap>	
					<v-col  cols="6" md="3">
						<v-img @click="openimage('/temple/2.jpeg')" src="/temple/2.jpeg" aspect-ratio="1.5"></v-img>
					</v-col>
					<v-col  cols="6" md="3">
						<v-img @click="openimage('/temple/3.jpeg')" src="/temple/3.jpeg" aspect-ratio="1.5"></v-img>
					</v-col>
					<v-col  cols="6" md="3">
						<v-img @click="openimage('/temple/4.jpeg')" src="/temple/4.jpeg" aspect-ratio="1.5"></v-img>
					</v-col>
					<v-col  cols="6" md="3">
						<v-img @click="openimage('/temple/5.jpeg')"src="/temple/5.jpeg" aspect-ratio="1.5"></v-img>
					</v-col>
					<v-col  cols="6" md="3">
						<v-img  @click="openimage('/temple/6.jpeg')"  src="/temple/6.jpeg" aspect-ratio="1.5"></v-img>
					</v-col>
					<v-col  cols="6" md="3">
						<v-img  @click="openimage('/temple/7.jpeg')" src="/temple/7.jpeg" aspect-ratio="1.5"></v-img>
					</v-col>
					<v-col  cols="6" md="3">
						<v-img  @click="openimage('/temple/8.jpeg')" src="/temple/8.jpeg" aspect-ratio="1.5"></v-img>
					</v-col>
					<v-col  cols="6" md="3">
						<v-img @click="openimage('/temple/9.jpeg')"  src="/temple/9.jpeg" aspect-ratio="1.5"></v-img>
					</v-col>
					<v-col  cols="6" md="3">
						<v-img  @click="openimage('/temple/10.jpeg')" src="/temple/10.jpeg" aspect-ratio="1.5"></v-img>
					</v-col>
					<v-col  cols="6" md="3">
						<v-img  @click="openimage('/temple/11.jpeg')" src="/temple/11.jpeg" aspect-ratio="1.5"></v-img>
					</v-col>
					<v-col  cols="6" md="3">
						<v-img  @click="openimage('/temple/12.jpeg')" src="/temple/12.jpeg" aspect-ratio="1.5"></v-img>
					</v-col>
					<v-col  cols="6" md="3">
						<v-img  @click="openimage('/temple/13.jpeg')" src="/temple/13.jpeg" aspect-ratio="1.5"></v-img>
					</v-col>
					<v-col  cols="6" md="3">
						<v-img  @click="openimage('/temple/16.jpeg')" src="/temple/16.jpeg" aspect-ratio="1.5"></v-img>
					</v-col>	
					<v-col  cols="6" md="3">
						<v-img  @click="openimage('/temple/14.jpeg')" src="/temple/14.jpeg" aspect-ratio="1.5"></v-img>
					</v-col>
					<v-col  cols="6" md="3">
						<v-img  @click="openimage('/temple/15.jpeg')" src="/temple/15.jpeg" aspect-ratio="1.5"></v-img>
					</v-col>
					<v-col  cols="6" md="3">
						<v-img  @click="openimage('/temple/17.jpeg')" src="/temple/17.jpeg" aspect-ratio="1.5"></v-img>
					</v-col>
					<v-col  cols="6" md="3">
						<v-img  @click="openimage('/temple/n1.jpeg')" src="/temple/n1.jpeg" aspect-ratio="1.5"></v-img>
					</v-col>
			
					<v-col  cols="6" md="3">
						<v-img  @click="openimage('/temple/n4.jpeg')" src="/temple/n4.jpeg" aspect-ratio="1.5"></v-img>
					</v-col>
					<v-col  cols="6" md="3">
						<v-img  @click="openimage('/temple/n5.jpeg')" src="/temple/n5.jpeg" aspect-ratio="1.5"></v-img>
					</v-col>
				</v-row>
			</v-container>

			<v-container class="pa-3">
				<h1 class="text--h2 text-center" >Festival Photos</h1>
				<v-row wrap>

					<v-col cols="6" md="3" >
						<v-img  @click="openimage('/data/festival.jpg')"  lazy-src src="/data/festival.jpg" aspect-ratio="1.5"></v-img>
					</v-col>
					<v-col cols="6" md="3" >
						<v-img @click="openimage('/data/pooja.jpg')"  lazy-src src="/data/pooja.jpg" aspect-ratio="1.5"></v-img>
					</v-col>
					<v-col cols="6" md="3" >
						<v-img @click="openimage('/data/festival2.jpg')"  lazy-src src="/data/festival2.jpg" aspect-ratio="1.5"></v-img>
					</v-col>
					<v-col cols="6" md="3" >
						<v-img @click="openimage('/data/festival3.jpg')"  lazy-src src="/data/festival3.jpg" aspect-ratio="1.5"></v-img>
					</v-col>
					<v-col cols="6" md="3" >
						<v-img @click="openimage('/fsimg/n1.jpeg')"  lazy-src src="/fsimg/n1.jpeg" aspect-ratio="1.5"></v-img>
					</v-col>
					<v-col cols="6" md="3" >
						<v-img @click="openimage('/fsimg/n2.jpeg')"  lazy-src src="/fsimg/n2.jpeg" aspect-ratio="1.5"></v-img>
					</v-col>
					<v-col cols="6" md="3" >
						<v-img @click="openimage('/fsimg/n3.jpeg')"  lazy-src src="/fsimg/n3.jpeg" aspect-ratio="1.5"></v-img>
					</v-col>
					<v-col cols="6" md="3" >
						<v-img  @click="openimage('/fsimg/n4.jpeg')" lazy-src src="/fsimg/n4.jpeg" aspect-ratio="1.5"></v-img>
					</v-col>
					<v-col cols="6" md="3" >
						<v-img  @click="openimage('/fsimg/n5.jpeg')" lazy-src src="/fsimg/n5.jpeg" aspect-ratio="1.5"></v-img>
					</v-col>
					<v-col cols="6" md="3" >
						<v-img @click="openimage('/fsimg/n6.jpeg')"  lazy-src src="/fsimg/n6.jpeg" aspect-ratio="1.5"></v-img>
					</v-col>
					<v-col cols="6" md="3" >
						<v-img @click="openimage('/fsimg/n7.jpeg')" lazy-src src="/fsimg/n7.jpeg" aspect-ratio="1.5"></v-img>
					</v-col><v-col cols="6" md="3" >
						<v-img  @click="openimage('/fsimg/n8.jpeg')" lazy-src src="/fsimg/n8.jpeg" aspect-ratio="1.5"></v-img>
					</v-col>
				</v-row>
			</v-container>

			<v-container class="pa-3">
				<h1 class="text--h2 text-center">Goddess Photos</h1>
				<v-row wrap>

					<v-col cols="6" md="3">
						<v-img @click="openimage('/fsimg/n7.jpeg')"lazy-src src="/fsimg/n7.jpeg"  aspect-ratio="1.5" ></v-img>
					</v-col>

					<v-col cols="6" md="3">
						<v-img@click="openimage('/data/goddes.jpg')" lazy-src src="/data/goddes.jpg" aspect-ratio="1.5" ></v-img>
					</v-col>

					<v-col cols="6" md="3">
						<v-img @click="openimage('/data/kamakshi.jpg')"lazy-src src="/data/kamakshi.jpg" aspect-ratio="1.5" ></v-img>
					</v-col>

					<v-col cols="6" md="3">
						<v-img @click="openimage('/data/goddes1.jpg')" lazy-src src="/data/goddes1.jpg" aspect-ratio="1.5"></v-img>
					</v-col>
				</v-row>
			</v-container>
		</div>

		<v-dialog v-model="dialog" max-width="800">
			<v-card class="pa-3" >
				<v-img contain aspect-ratio="1.5" v-if="imageurl" :src="imageurl"></v-img>

				<v-card-actions>
					<v-spacer></v-spacer>
				<v-btn color="black darken-1" text @click="closeimage()">
				Close
			</v-btn>
		</v-card-actions>
	</v-card>
</v-dialog>

</div>
</template>

<script type="text/javascript">
	export default{
		layout:"page",
		data(){
			return{
				dialog : false,
				imageurl: null
			}
		},
		methods:{
			openimage(e){
				this.imageurl = e
				this.dialog = !this.dialog
			},
			closeimage(){
				this.imageurl = null
				this.dialog = !this.dialog
			}
		},
		mounted(){
			let audio = document.getElementsByTagName('audio')
			audio[0].play()
		}
	}
</script>