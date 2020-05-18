<template>
	<view>
		<!-- 话题介绍 -->
		<topicDetail :item="topinfo"></topicDetail>
	</view>
</template>

<script>
	import topicDetail from "../../components/topic/topic-detail.vue"; 
	export default {
		data() {
			return {
				topinfo:{
					titlepic:"../../static/datapic/36.jpg",
					titile:"标题标题",
					desc:"描述描述",
					totalnum:"200",
					todaynum:"300"
				}
			}
		},
		methods: {
			
		},
		components:{
			topicDetail
		}
	}
</script>

<style lang="scss">

</style>
