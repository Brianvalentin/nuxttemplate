<template>
	<v-app id="root">
		<v-main>
			<navbar class="hidden-sm-and-down"/>
			<navdialog class="hidden-md-and-up"/>
			
			<nuxt/>
			<audio :src="require('@/assets/bell.mp3')"></audio>
			<footersection />
		</v-main>
	</v-app>

</template>

<script type="text/javascript">
	export default{
	}
</script>