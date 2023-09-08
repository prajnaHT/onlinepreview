# Headline

> An awesome project.

 [docsify - 生成文档网站简单使用教程](https://segmentfault.com/a/1190000017576714)



<iframe src="http://www.chen-studio.com/index.php/code.html" style="height:500px"></iframe>

<img src="home-bg-2.jpg" width="70%" style="margin-left:20px"/>

* # **[home1](home1)**
* [home2](home2)

  * [home1](home1)
  * [home2](home2)


* 根目录
  * [home1](home1)
  * [home2](home2)
  * [guide](guide)


```javascript
var i=1

```

# Headline2

ddd 





# Vue 介绍

<details>
<summary>Title</summary>
content!!!
</details>


`v-for` 的用法

```html
<ul>
  <li v-for="i in 10">{{ i }}</li>
</ul>
``
<ul>
  <li v-for="i in 10">{{ i }}</li>
</ul>

# Vue 的基本用法
<div>hello {{ msg }}</div>
<script>
  new Vue({
    el: '#main',
    data: { msg: 'Vue' }
  })
</script>
```

# Vuep 使用

 <vuep  template="#example" :options="{ theme: 'the-matrix' }" ></vuep>

<script v-pre type="text/x-template"  id="example">
<template>
<div>
<el-button class="el-icon-edit"></el-button>
<el-button class="el-icon-share"></el-button>
<el-button class="el-icon-delete"></el-button>
<el-button class="el-icon-search"></el-button>
<br><br>
<el-button type="info" class="el-icon-edit" circle></el-button>
<el-button type="primary" class="el-icon-share"  circle></el-button>
<el-button class="el-icon-delete"  circle></el-button>
<el-button type="success" class="el-icon-search" circle></el-button>
</div>
</template>
<style scoped>
  el-button{
   padding: 20px 20px 20px 20px;
  }
</style>
  <script>
    module.exports = {
      data: function () {
        return { name: 'V2123ue' }
      }
    }
</script>
</script>





<vuep template="#example2"></vuep>

<script v-pre type="text/x-template" id="example2">
<template>
  <div>
    <el-card class="box-card">
      <div slot="header" class="clearfix">
      <el-alert
    title="INCOME STATEMENT 收支表"
    type="success"
    effect="dark">
  </el-alert>
     <el-tag type="success" style="margin-top: 10px;margin-left: 15%">INCOME-收入</el-tag>
     <el-tag type="info" style="margin-left: 15%">EXPENSES-支出</el-tag>
     </div>
     <el-row>
  <el-col :span="12">
    <div v-for="(income, index) in incomes" :key="index" class="text item">
    {{ income }}
    <input type="text" />
    </div>
  </el-col>
  <el-col :span="12">
    <div v-for="(expense, index)  in expenses" :key="index" class="text item">
    {{ expense }}
    </div>
  </el-col>
</el-row>
    </el-card>
    <el-card class="box-card">
      <div slot="header" class="clearfix">
      <el-alert
    title="BALANCE SHEET 资产负债表"
    type="success"
    effect="dark">
  </el-alert>
      <el-tag type="success" style="margin-top: 10px;margin-left: 15%">ASSETS-资产</el-tag>
      <el-tag type="info" style="margin-left: 15%">LIABILITIES-负债</el-tag>
     </div>
     <el-row>
  <el-col :span="12">
    <div v-for="(asset, index)  in assets" :key="index" class="text item">
    {{ asset }}
    </div>
  </el-col>
  <el-col :span="12"><div v-for="o in 4" :key="o" class="text item">
    {{'列表内容 ' + o }}
  </div></el-col>
      </el-row>
    </el-card>
    <el-card class="box-card">
      <div slot="header" class="clearfix">
  <el-alert
    title="BUDGET 预算"
    type="success"
    show-icon>
  </el-alert>
     </div>
     <el-row>
    <el-table
      :data="tableData"
      style="width: 100%">
      <el-table-column
        prop="name"
        label="名称"
        width="150">
      </el-table-column>
      <el-table-column
        prop="money"
        label="金额">
      </el-table-column>
    </el-table>
      </el-row>
    </el-card>
  </div>
</template>
<style>
  .text {
    font-size: 14px;
  }
  .item {
    margin-bottom: 15px;
  }

  .clearfix:before,
  .clearfix:after {
    display: table;
    content: "";
  }
  .clearfix:after {
    clear: both
  }

  .box-card {
    width: 480px;
    margin-top: 12px;
    margin-right: 40px;
    float: left;
  }
  .litem {
    margin-right: 40px;
    float: left;
    margin-bottom: 18px;
  }
</style>
<script>
export default {
  name: 'ProjectManage',
  data () {
    return {
      tableData: [{
        name: '王小虎',
        money: 10.00
      }, {
        name: '王小虎',
        money: 13.00
      }, {
        name: '王小虎',
        money: 14.00
      }, {
        name: '王小虎',
        money: 13.00
      }],
      incomes: {
        label1: '房租',
        label2: '薪水',
        label3: '利息',
        label4: '版税'
      },
      expenses: {
        label1: '日用',
        label2: '房贷',
        label3: '已到期保险',
        label4: '信用'
      },
      assets: {
        label1: '房产',
        label2: '车辆',
        label3: '预付保险'
      }
    }
  }
}
</script>
</script>



 Attributes

| 参数   | 说明                                      | 类型    | 可选值         | 默认值 |
| ------ | ----------------------------------------- | ------- | -------------- | ------ |
| name   | 图标名称                                  | string  | -              | -      |
| color  | 图标颜色                                  | string  | -              | -      |
| size   | 图标大小                                  | number  | -              | -      |
| symbol | 是否多色（开启将以`svg`标签方式引入图标） | boolean | `true`,`false` | `true` |



### Form events

 

\#

| 事件名            | 说明                                                        | 返回值              |
| ----------------- | ----------------------------------------------------------- | ------------------- |
| on-validate 4.0.0 | 任一表单项被校验后触发，返回表单项 prop、校验状态、错误消息 | prop, status, error |





> **Important** notice with `inline code` and additional placeholder text used
> to force the content to wrap and span multiple lines.

> **Important** notice with `inline code` and additional placeholder text used to
> force the content to wrap and span multiple lines.


