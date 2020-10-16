<template>
	<div>
		<v-toolbar dark >
			<v-toolbar-title><v-list-item link text to="/" id="index">Sri Kamakshi Amman
			</v-list-item></v-toolbar-title>
			<v-spacer></v-spacer>
			<v-toolbar-items class="hidden-sm-and-down">
				
				<v-menu offset-y open-on-hover>
					<template v-slot:activator="{ on, attrs }">
						<v-btn v-bind="attrs" v-on="on">
							Temple
						</v-btn>
					</template>
					<v-list>
						<v-list-item
						v-for="(item, index) in ['About Kamakshi','Temple Legend','History','About Kanchi','Other Temple','Other Districts','Methology & Legend','About Priest Family']"
						:key="item"
						>
						<v-btn text block link to="/data/about"><v-list-item-title>{{ item }}</v-list-item-title></v-btn>
					</v-list-item>
				</v-list>
			</v-menu>

			<v-menu offset-y open-on-hover>
				<template v-slot:activator="{ on, attrs }">
					<v-btn v-bind="attrs"v-on="on">
						Pilgrim Service
					</v-btn>
				</template>
				<v-list>
					<v-list-item
					v-for="(item, index) in ['Darshan','Sevas','Prasad & Sovereign','Picture','Gifts']"
					:key="item"
					>
					<v-btn text block><v-list-item-title>{{ item }}</v-list-item-title></v-btn>
				</v-list-item>
			</v-list>
		</v-menu>

		<v-menu offset-y open-on-hover>
			<template v-slot:activator="{ on, attrs }">
				<v-btn v-bind="attrs"v-on="on">
					Online Service
				</v-btn>
			</template>
			<v-list>
				<v-list-item
				v-for="(item, index) in ['Booking for Seva','Booking for Darshan','Publication','Donation','Marriage Booking','Webinars']"
				:key="item"
				>
				<v-btn text block><v-list-item-title>{{ item }}</v-list-item-title></v-btn>
			</v-list-item>
		</v-list>
	</v-menu>

	<v-menu offset-y open-on-hover>
		<template v-slot:activator="{ on, attrs }">
			<v-btn v-bind="attrs"v-on="on">
				News & Events
			</v-btn>
		</template>
		<v-list>
			<v-list-item
			v-for="(item, index) in ['Print','Media','Blog','Youtube Channel','Past Event','Future Event']"
			:key="item"
			>
			<v-btn text block><v-list-item-title>{{ item }}</v-list-item-title></v-btn>
		</v-list-item>
	</v-list>
</v-menu>

<v-menu offset-y open-on-hover>
	<template v-slot:activator="{ on, attrs }">
		<v-btn v-bind="attrs"v-on="on">
			Photo Gallery
		</v-btn>
	</template>
	<v-list>
		<v-list-item
		v-for="(item, index) in ['Temple Photos','Festival Photos']"
		:key="item"
		>
		<v-btn text block link to="/gallery"><v-list-item-title>{{ item }}</v-list-item-title></v-btn>
	</v-list-item>
</v-list>
</v-menu>

<v-menu offset-y open-on-hover>
	<template v-slot:activator="{ on, attrs }">
		<v-btn v-bind="attrs"v-on="on">
			General Info
		</v-btn>
	</template>
	<v-list>
		<v-list-item
		v-for="(item, index) in ['Accomadation','Transport','Plan a triplyatra','Facilities','Help Desk','Do\'s & Don\'t','Contact Us','Timings']"
		:key="item"
		>
		<v-btn text block><v-list-item-title>{{ item }}</v-list-item-title></v-btn>
	</v-list-item>
</v-list>
</v-menu>

</v-toolbar-items>
<v-toolbar-items class="hidden-md-and-up" @click.stop="drawer = !drawer">
	<v-icon color="white">mdi-menu</v-icon>
</v-toolbar-items>
</v-toolbar>

<v-navigation-drawer v-model="drawer" absolute temporary style="overflow-y: scroll;" >
<v-list
nav
dense
style="overflow-y: scroll;"
>
<v-list-item-group
v-model="group"
active-class="deep-purple--text text--accent-4"
style="overflow-y: scroll;"
>
<v-list-item>
	<v-list-item-title link to="/data/about"><strong>Temple</strong></v-list-item-title>
</v-list-item>
<v-divider></v-divider>
<!-- SubNav1 -->
<v-list-item>
	<v-list-item-title><v-list-item  link to="/data/about#section1">About Kamakshi</v-list-item></v-list-item-title>
</v-list-item>
<v-list-item>
	<v-list-item-title> <v-list-item link to="/data/about#section2">Temple Legend</v-list-item></v-list-item-title>
</v-list-item>
<v-list-item>
	<v-list-item-title> <v-list-item link to="/data/about#section3">History</v-list-item></v-list-item-title>
</v-list-item>
<v-list-item>
	<v-list-item-title> <v-list-item link to="/data/about#section4">About Kanchi</v-list-item></v-list-item-title>
</v-list-item>
<v-list-item>
	<v-list-item-title> <v-list-item link to="/data/about#section5">Other Temple</v-list-item></v-list-item-title>
</v-list-item>
<v-list-item>
	<v-list-item-title> <v-list-item link to="/data/about#section6">Other Districts</v-list-item></v-list-item-title>
</v-list-item>
<v-list-item>
	<v-list-item-title> <v-list-item link to="/data/about#section7">Methology & Legend</v-list-item></v-list-item-title>
</v-list-item>
<v-list-item>
	<v-list-item-title> <v-list-item link to="/data/about#section8">About Priest Family</v-list-item></v-list-item-title>
</v-list-item>

<v-list-item>
	<v-list-item-title><strong><v-list-item link to="/data/pilgrim">Pilgrim Service</v-list-item></strong></v-list-item-title>
</v-list-item>
<v-divider></v-divider>
<!-- Subnav2 -->
<v-list-item>
	<v-list-item-title><v-list-item link to="/data/pilgrim#section1">Darsha</v-list-item></v-list-item-title>
</v-list-item>
<v-list-item>
	<v-list-item-title><v-list-item link to="/data/pilgrim#section2">Sevas</v-list-item></v-list-item-title>
</v-list-item>
<v-list-item>
	<v-list-item-title><v-list-item link to="/data/pilgrim#section3">Prasad & Soverign</v-list-item></v-list-item-title>
</v-list-item>
<v-list-item>
	<v-list-item-title><v-list-item link to="/data/pilgrim#section4">Picture & Gifts</v-list-item></v-list-item-title>
</v-list-item>

<v-list-item>
	<v-list-item-title><strong><v-list-item link to="/data/online">Online Service</v-list-item> </strong></v-list-item-title>
</v-list-item>
<v-divider></v-divider>
<!-- Subnav3 -->
<v-list-item>
	<v-list-item-title><v-list-item link to="/data/online#section1">Booking for Seva</v-list-item></v-list-item-title>
</v-list-item>
<v-list-item>
	<v-list-item-title><v-list-item link to="/data/online#section2">Booking for Darshan</v-list-item></v-list-item-title>
</v-list-item>
<v-list-item>
	<v-list-item-title><v-list-item link to="/data/online#section3">Publication</v-list-item></v-list-item-title>
</v-list-item>
<v-list-item>
	<v-list-item-title><v-list-item link to="/data/online#section4">Donation</v-list-item></v-list-item-title>
</v-list-item>
<v-list-item>
	<v-list-item-title><v-list-item link to="/data/online#section5">Marriage Booking</v-list-item></v-list-item-title>
</v-list-item>
<v-list-item>
	<v-list-item-title><v-list-item link to="/data/online#section6">Webinars</v-list-item></v-list-item-title>
</v-list-item>


<v-list-item>
	<v-list-item-title><strong><v-list-item link to="/data/news">News & Events</v-list-item></strong></v-list-item-title>
</v-list-item>
<v-divider></v-divider>
<!-- Subnav4 -->
<v-list-item>
	<v-list-item-title><v-list-item link to="/data/news#section1">Print</v-list-item></v-list-item-title>
</v-list-item>
<v-list-item>
	<v-list-item-title><v-list-item link to="/data/news#section2">Media</v-list-item></v-list-item-title>
</v-list-item>
<v-list-item>
	<v-list-item-title><v-list-item link to="/data/news#section3">Blog</v-list-item></v-list-item-title>
</v-list-item>
<v-list-item>
	<v-list-item-title><v-list-item link to="/data/news#section4">Past Event</v-list-item></v-list-item-title>
</v-list-item>
<v-list-item>
	<v-list-item-title><v-list-item link to="/data/news#section5">Future Event</v-list-item></v-list-item-title>
</v-list-item>

<v-list-item>
	<v-list-item-title><strong><v-list-item link to="/gallery">Future Event</v-list-item>PhotoGallery</strong></v-list-item-title>
</v-list-item>
<v-divider></v-divider>
<!-- Subnav5 -->
<!-- <v-list-item>
	<v-list-item-title>Temple Photos</v-list-item-title>
</v-list-item>
<v-list-item>
	<v-list-item-title>Festival Photos</v-list-item-title>
</v-list-item> -->


<v-list-item>
	<v-list-item-title><strong><v-list-item link to="/data/general">General Info</v-list-item></strong></v-list-item-title>
</v-list-item>
<v-divider></v-divider>
<!-- Subnav6 -->
<v-list-item>
	<v-list-item-title> <v-list-item link to="/data/general#section1">Accomadation</v-list-item></v-list-item-title>
</v-list-item>
<v-list-item>
	<v-list-item-title> <v-list-item link to="/data/general#section2">Travel Plan</v-list-item></v-list-item-title>
</v-list-item>
<v-list-item>
	<v-list-item-title> <v-list-item link to="/data/general#section4">Do & Don't</v-list-item></v-list-item-title>
</v-list-item>

</v-list-item-group>
</v-list>
</v-navigation-drawer>

</div>
</template>

<script type="text/javascript">

	export default{
		data(){
			return{
				drawer:false,
				group:null,

			}
		},
		watch: {
			group () {
				this.drawer = false
			}
		}
	}
	</script>

	<style lang="css" scoped>
	button.v-btn.v-btn--block.v-btn--flat.v-btn--text.theme--light.v-size--default{
		text-align: left;
	}
	aside.v-navigation-drawer.v-navigation-drawer--absolute.v-navigation-drawer--is-mobile.v-navigation-drawer--open.v-navigation-drawer--temporary.theme--light{
		height: 100vh !important;
		overflow-y: scroll !important;
	}
	.theme--dark.v-list-item--active:hover::before, .theme--dark.v-list-item--active::before{
		opacity: 0;
	}
	#index{
		color: white;
	}
</style>

