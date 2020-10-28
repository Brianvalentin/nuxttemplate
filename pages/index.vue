<template>
	<div>

		<topbar />
		<headslider />
		<navbar v-intersect="onIntersect1"
		:class="{sticknav : isIntersecting1 }" class="hidden-sm-and-down"   /> 
		<navdialog class="hidden-md-and-up"/>
		<flashtimings />
		<sectioncards />
		<videosection/>
		<vissionsection />
		<events />
		<indexgallery />
		<addresssection />
		<footersection />
</div>
</template>

<script>
	export default{
		data(){
			return{
				isIntersecting1: false,
				offsetTop: 0,
			}
		},		
		methods:{
			onIntersect1 (entries, observer) {
				this.isIntersecting1 = true
			// this.isIntersecting = entries[0].isIntersecting
		},
		onScroll (e) {
        this.offsetTop = e.target.scrollTop
      },
	},
	mounted(){
		this.isIntersecting1 = false
		
	}
}
</script>

<style type="text/css" scoped>
.sticknav{
	position: sticky;
	width: 100%;
	top: 0px;
	z-index: 100;
}
@media only screen and (min-width: 768px){
	
}

</style>