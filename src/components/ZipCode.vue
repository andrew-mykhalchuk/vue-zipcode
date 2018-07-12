<script>
	export default {
		name: 'ZipCode',
		data: function () {
			return {
				count: 0
			}
		},
		template: '<button v-on:click="count++">You clicked me {{ count }} times.</button>'
	}
</script>