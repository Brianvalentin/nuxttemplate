<template>
	<div data-aos="fade-up" data-aos-duration="700">
		<v-container >
			<h1 class="text-h4 pa-3 text-center">Upcoming Events</h1>
			<v-row>

				<v-col cols="12" md="4" v-for="(item,index) in contents" :key="index">
					<v-card elevation="15">
						<v-card-title class="pink--text">{{item.date}}</v-card-title>
						<v-card-title class="text-h5">{{item.title}}</v-card-title>
						<v-card-text>{{item.content}}</v-card-text>
						<v-card-actions>
							<v-btn link :to="item.location" tile text block>Know More</v-btn>
						</v-card-actions>
					</v-card>
				</v-col>
			</v-row>
		</v-container>
	</div>
</template>

<script type="text/javascript">
	export default{
		data(){
			return{
				contents:[
				{
					"date":"Bilakasam",
					"title":"upcoming",
					"content":"Kamakshi devi is said to have come to Kanchipuram Temple though this Bilakasam on Poora Nakshatram dayis located near Goddess Kamakshi..",
					"location":"/events/event"
				},
				{
					"date":"Will be Updated",
					"title":"25 October",
					"content":"Vasant Panchami is the festival dedicated to goddess Saraswati who is their goddess of knowledge, language, music and all arts.",
					"location":"/about/futureevents#section2"
				},
				{
					"date":"Will be Updated",
					"title":" 26 October",
					"content":"Vijayadashami also known as Dussehra, Dasara or Dashain is a major Hindu festival celebrated at the end of Navaratri every year.",
					"location":"/about/futureevents#section3"
				}
				]
			}
		}
	}
</script>