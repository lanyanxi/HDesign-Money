<script>
export default {
	onLaunch: function() {
		console.log('App Launch');
	},
	onShow: function() {
		console.log('App Show');
	},
	onHide: function() {
		console.log('App Hide');
	}
};
</script>

<style lang="scss">
@import '@/common/css/colorui/main.css';
@import '@/common/css/colorui/icon.css';

/* button样式改写 */
button {
	font-size: 34rpx;
	font-weight: normal;

	&.no-border:before,
	&.no-border:after {
		border: 0;
	}
}

button[type='default'] {
	color: #303133;
}

uni-button:after {
	border: 0;
}
</style>
