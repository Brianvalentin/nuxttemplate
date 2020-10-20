<template>
	<div>
	<div data-aos="fade-down" data-aos-duration="700">
		<div data-aos="fade-in" data-aos-duration="700">
			<v-container id="section1">
				<h1 class="text-h3 text-center pa-3">Print</h1>
				<v-divider></v-divider>
				<v-row wrap>		
					<v-col cols="12" md="8">
						<p class="text-h6">	
							{{content}}			 
						</p>
					</v-col>

					<v-col cols="12" md="4">
						<v-img src="/profile.jpg" aspect-ratio="1.77"></v-img>
					</v-col>
				</v-row>
			</v-container>
		</div>

		<div data-aos="fade-in" data-aos-duration="700" id="section2">
			<v-container id="section1">
				<h1 class="text-h3 text-center pa-3">Media</h1>
				<v-divider></v-divider>
				<v-row wrap>
					<v-col cols="12" md="4">
						<v-img src="/profile.jpg" aspect-ratio="1.77"></v-img>
					</v-col>		
					<v-col cols="12" md="8">
						<p class="text-h6">	
							{{content}}			 
						</p>
					</v-col>				
				</v-row>
			</v-container>
		</div>

		<div data-aos="fade-in" data-aos-duration="700" id="section3">
			<v-container id="section1">
				<h1 class="text-h3 text-center pa-3">Blog</h1>
				<v-divider></v-divider>
				<v-row wrap>
					<v-col cols="12" md="8">
						<p class="text-h6">	
							{{content}}			 
						</p>
					</v-col>
					<v-col cols="12" md="4">
						<v-img src="/profile.jpg" aspect-ratio="1.77"></v-img>
					</v-col>		

				</v-row>
			</v-container>
		</div>

		<div data-aos="fade-in" data-aos-duration="700" id="section4">
			<v-container id="section1">
				<h1 class="text-h3 text-center pa-3">YouTube Channel</h1>
				<v-divider></v-divider>
				<v-row wrap>
					<v-col cols="12" md="4">
						<v-img src="/profile.jpg" aspect-ratio="1.77"></v-img>
					</v-col>	
					<v-col cols="12" md="8">
						<p class="text-h6">	
							{{content}}			 
						</p>
					</v-col>
				</v-row>
			</v-container>
		</div>

		<div data-aos="fade-in" data-aos-duration="700" id="section5">
			<v-container id="section1">
				<h1 class="text-h3 text-center pa-3">Past Event</h1>
				<v-divider></v-divider>

				<v-row wrap>
					<v-col cols="12" md="8">
						<p class="text-h6">	
							{{content}}			 
						</p>
					</v-col>
					<v-col cols="12" md="4">
						<v-img src="/profile.jpg" aspect-ratio="1.77"></v-img>
					</v-col>	

				</v-row>
			</v-container>
		</div>

		<div data-aos="fade-in" data-aos-duration="700" id="section6">
			<v-container id="section1">
				<h1 class="text-h3 text-center pa-3">Future Event</h1>
				<v-divider></v-divider>
				<v-row wrap>
					<v-col cols="12" md="4">
						<v-img src="/profile.jpg" aspect-ratio="1.77"></v-img>
					</v-col>	
					<v-col cols="12" md="8">
						<p class="text-h6">	
							{{content}}			 
						</p>
					</v-col>
				</v-row>		
				
				
			</v-container>
		</div>

		<div data-aos="fade-in" data-aos-duration="700" id="section7">
			<v-container id="section1">
				<h1 class="text-h3 text-center pa-3">Festival Link</h1>
				<v-divider></v-divider>
				<v-row wrap>
					<v-col cols="12" md="4">
						<v-img src="/profile.jpg" aspect-ratio="1.77"></v-img>
					</v-col>	
					<v-col cols="12" md="8">
						<p class="text-h6">	
							{{content}}			 
						</p>
					</v-col>
				</v-row>		
				
				
			</v-container>
		</div>
		</div>
	</div>
</template>

<script type="text/javascript">
	export default{
			layout:"page",
		data(){
			return{
				content:"Content Will Be Updated Here"
			}
		}
	}
</script>