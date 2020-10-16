<template>
	<div data-aos="fade-up" data-aos-duration="700">
		<v-row class="pa-6">
			<v-col cols="12" md="4" v-for="i in content" :key="i.id">
				<v-card  class="mx-auto elevation-4" tile >
					<v-img
					:src="i.img"
					aspect-ratio=1.77
					></v-img>

					<v-card-title>
						{{i.title}}
					</v-card-title>
					<p class="text-center px-3">
						{{i.content}}
					</p>


					<v-card-actions>
						<v-btn color="blue lighten-2" text block >
						Explore
					</v-btn>

					<v-spacer></v-spacer>

				</v-card-actions>
			</v-card>
		</v-col>
	</v-row>

</div>
</template>

<script type="text/javascript">

	export default{
		name:"sectioncards",
		data(){
			return{
				content:[
				{	
					"id":1,
					"title":"About Kanchipuram - City Of Temples",
					"img":"/profile.jpg",
					"content":"Kanchipuram is one of the seven sacred cities in India. History proclaims that Kanchipuram was ruled by the Pallava Kings..."
				},
				{
					"id":2,
					"title":"About Goddess kamakshi",
					"img":"/profile.jpg",
					"content":"The Goddess Kamakshi is in a sitting posture in the temple. This posture is called the Padmasana posture. The Padmasana ..."
				},
				{
					"id":3,
					"title":"About Kanchi Kamakshi Temple",
					"img":"/profile.jpg",
					"content":"Kanchi Kamakshi temple is situated at about 5 acres of land and has four entrances. The main entrance of the temple..."
				}
				]
			}
		}

	}
</script>

