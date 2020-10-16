<template>
	<div data-aos="slide-up" data-aos-duration="1000">
		<v-container >
			<v-row>
				<v-col cols="12" md="4" v-for="(item,index) in contents" :key="index">
					<v-card elevation="15">
						<v-card-title class="pink--text">{{item.date}}</v-card-title>
						<v-card-title class="text-h5">{{item.title}}</v-card-title>
						<v-card-text>{{item.content}}</v-card-text>
						<v-card-actions>
							<v-btn tile text block>Learn More</v-btn>
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
					"date":"11-10-2020",
					"title":"Pownarmi pooja",
					"content":"Lorem ipsum dolor sit amet, consectetuer adipiscing elit. Praesent vestibulum molestie lacus. Aenean nonummy hendrerit mauris. Phasellus porta. Fusce suscip"
				},
				{
					"date":"11-10-2020",
					"title":"Pownarmi pooja",
					"content":"Lorem ipsum dolor sit amet, consectetuer adipiscing elit. Praesent vestibulum molestie lacus. Aenean nonummy hendrerit mauris. Phasellus porta. Fusce suscip"
				},
				{
					"date":"11-10-2020",
					"title":"Pownarmi pooja",
					"content":"Lorem ipsum dolor sit amet, consectetuer adipiscing elit. Praesent vestibulum molestie lacus. Aenean nonummy hendrerit mauris. Phasellus porta. Fusce suscip"
				}
				]
			}
		}
	}
</script>