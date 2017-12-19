<template>
<div>
	<mt-cell title="标题文字" icon="back" is-link value="描述文字"></mt-cell>
	<mt-cell title="标题文字" icon="back">
	   <div slot="value">描述文字啊哈</div>
	</mt-cell>
 </div>
</template>

<script>
import mtCell from "../lib/components/cell/src/cell.vue";
export default {
  name: 'cell-example',
  components:{
  	mtCell
  }
}
</script>
<style>
</style>