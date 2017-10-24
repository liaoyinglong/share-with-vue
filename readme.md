# vue基础

-  ### 生命周期

-  ### `computed` 和 `watch` 的区别

   > `computed`是用于定义**基于数据之上的数据**。
   >
   > 而`watch`是你想在**某个数据变化时做一些事情**，如果做的事情是更新其他数据，那其实与把这个要更新的数据项定义成`computed`是一样的，这个时候用`computed`更有可读性，虽然技术上讲`watch`也可以实现。
   >
   > 但你也可以在被`watch`的数据变化时做其他事情啊，比如调用一个方法，这个是`computed`做不到也不应该做的。
   >
   > 总结一下：
   >
   > - 1.如果一个数据依赖于其他数据，那么把这个数据设计为`computed`的
   > - 2.如果你需要在某个数据变化时做一些事情，使用`watch`来观察这个数据变化

-  ### `v-model` 

   - `v-model`是一个语法糖
   - 简单实现组件的`v-model`

-  ### `.sync`修饰符

   `.sync`修饰符同样也是一个语法糖，与`v-model`不同的是：

   - `v-model`可以用在运行时。`.sync`在2.3.0版本后只是作为代码编译期的语法糖存在，它会被扩展为一个自动更新父组件属性的 `v-on` 监听器。
   - `v-model`一般用于表单控件。

-  ### slot
   > `<slot>` 标签中的任何内容都被视为备用内容。备用内容在子组件的作用域内编译，并且只有在宿主元素为空，且没有要插入的内容时才显示备用内容。

- ### 组件间通信

- ### render函数

## end 

- ### 推荐一个工具  `poi`
  - what? 一个快速编译vue文件的工具

  - why? 一个命令就能编译.vue文件

  - how? 有一个入口 main.js ，然后cd到当前目录，打开命令行 `poi main.js`， 

    更多说明请看 GitHub ：https://github.com/egoist/poi
---
- ps: 在线写ng/react的网站看这里 https://stackblitz.com/

- 再ps：关于翻墙最最最简单的方法就是 http://www.ggfwzs.com/ 

  （当然作为一个免费的软件，它有缺点，它只是给你提供了访问谷歌搜索、谷歌邮箱和谷歌商店等等小流量的网站，像YouTube还是上不了的）
