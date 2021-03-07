<template>
  <div class="item">
    <slot name="img">
		</slot>
    <slot name="text"> </slot>
  </div>
</template>

<script>
export default {};
</script>

<style lang="less" scoped>
 .item {
	 display: flex;
	 flex-direction: column;
	//  justify-content: center;
	align-items: center;

	 img {
		 height: 30px;
		 width: 40px;
		 margin-bottom: 4px;
	 }
 }
</style>