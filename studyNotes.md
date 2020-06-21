# Vue
- 1.指令：带有`v-`前缀的特殊属性，用于在表达式的值改变时，将某些行为应用到DOM上。  
&emsp; `v-html`用于输出 html 代码(如v-html='msg'，在组件data里定义msg内容)。  
&emsp; `v-bind`用于响应地更新HTML属性，参数在指令后以冒号指明。  
&emsp; `v-on`用于监听DOM事件，参数是监听的事件名。  
&emsp; `v-model`用来在 input、select、textarea、checkbox、radio 等表单控件元素上创建双向数据绑定，根据表单上的值，自动更新绑定的元素的值。  
&emsp; `v-if` `v-else`条件判断。  
&emsp; `v-show`根据条件来展示元素(如 v-show=Math.random()>0.5 )。  
&emsp; `v-for`循环(如v-for='site in sites'，sites为源数据数组，site为数组元素的迭代别名)。  
&emsp; 缩写：`@click` = `v-on:click`，`:href='url'` = `v-bind:href='url'`。
- 2.数据绑定`{{}}`用于输出对象属性和函数返回值。
- 3.全局组件`Vue.component('组件名', {options})`。(PS: 单数而不是components)  
- 4.ref属性用来给DOM元素或子组件注册引用信息，引用信息会根据父组件的$refs属性进行注册。DOM元素上使用，引用信息就是元素，组件上使用，引用信息就是组件实例。
