1. 变量 => 响应式 数据更新 改变页面
2. 声明式渲染 表达式 => className | fn() | a >90 ? '及格' : '不及格'
3. 指令 => 标签上使用 v-xxx  指令里可以使用vue变量
    v-text v-html
    条件判断 
    v-if  v-else-if  v-else => 删除添加元素
    v-show => 改变css样式
    列表渲染
    v-for => Array | Object | String | Number
    表单绑定
    v-model  => 双向绑定

    绑定属性
    v-bind
    v-bind:src="" v-bind:href="href"  
    v-bind:class="{active: 条件}" v-bind:style="[]" 
    简写 :


    绑定事件
    v-on:click scroll
    简写 @
