<template>
	<div>
		<v-row>
			<v-col>

				<client-only>
				<pdf src="/test.pdf"></pdf>
				</client-only>
			</v-col>
		</v-row>
		
	</div>
</template>

<script>
	export default{

		layout:"page",
		components:{
			// pdf
		}
	}
</script>
