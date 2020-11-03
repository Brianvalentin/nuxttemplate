<template>
	<div >
		<v-container class="pa-6">
		<div data-aos="fade-up" data-aos-duration="700">
			<!-- <v-img width="300" class="mx-auto pa-4"  aspect-ratio="" src="/profile.jpg"></v-img> -->
			<h1 class="text-h2 text-center py-6 ">Do's & Don't</h1>
			<v-row>
				<v-col class="mx-auto" cols="12" md="10">
					<strong><h1 class="text-h4 purple--text">Do’s in Kamakshi Ambal Temple are as follows:</h1></strong>
					<hr>
					<v-list>
						<v-list-item>
							1. Bathe and wear clean clothes before you enter the sanctum shrine of Lord Sri Kanchi Kamakshi.
						</v-list-item>
						<v-list-item>
							2. Concentrate on Lord Sri Kanchi Kamakshi inside the temple.
						</v-list-item>
						<v-list-item>
							3. Observe absolute silence and chant “mantra”, inside the temple.
						</v-list-item>
						<v-list-item>
							4. Respect ancient customs and usages while at Kamakshi Temple.
						</v-list-item>
						<v-list-item>
							6. Follow the procedures of the temple and wait for your turn for the darshan of the Lord.
						</v-list-item>
					</v-list>

					<strong><h1 class="text-h4 purple--text">Dont’s in Kamakshi Ambal Temple are as follows:</h1></strong>
					<hr>
					<v-list>
						<v-list-item>
							1.Don't Carry much jewellery and cash with you.
						</v-list-item>
						<v-list-item>
							2. Don't Wear footwear in and around the premises of the temple.
						</v-list-item>
						<v-list-item>
							3. Don't Approach touts for accommodation and darshan.
						</v-list-item>
						<v-list-item>
							4.Don't Throw away the prasadam and teertham given to you at the temple.
						</v-list-item>
						<v-list-item>
							5. Don't Rush in for darshan instead of waiting for your turn in the queue
						</v-list-item>
						<v-list-item>
							6. Don't Commit any act of violence or harshness in the temple premises.
						</v-list-item>
						<v-list-item>
							6. Carrying of weapons & ammunition to Temple is prohibited and pilgrims in possession of licensed weapons / ammunition should declare the same at  check point and submit all the concerned documents and failure to do so will invite legal action.
						</v-list-item>
					</v-list>
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