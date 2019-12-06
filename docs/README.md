# Headline

> An awesome project.

```vue
<template>
  <div>工具管理
<div class="block">
  <span class="demonstration">区分颜色</span>
  <el-rate v-model="value1" :colors="['#99A9BF', '#F7BA2A', '#FF9900']">
  </el-rate>
</div>
<el-button type="primary" icon="el-icon-edit"></el-button>
<el-row>
  <el-button icon="el-icon-search" circle></el-button>
  <el-button type="primary" icon="el-icon-edit" circle></el-button>
  <el-button type="success" icon="el-icon-check" circle></el-button>
  <el-button type="info" icon="el-icon-message" circle></el-button>
  <el-button type="warning" icon="el-icon-star-off" circle></el-button>
  <el-button type="danger" icon="el-icon-delete" circle></el-button>
</el-row>
  </div>
</template>

<script>
export default {
  name: 'ToolManage'
}
</script>

<style>
</style>

```

