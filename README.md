1.安装vue-loader

cnpm install vue-loader --save-dev
2.loader配置

npm install sass-loader node-sass --save-dev
3.使用

<style scoped lang="scss">
	$primary-color: #666; 
	$width:100px;
	
	.box{
		width:$width;height:$width;
		background:$primary-color;
	}
 
