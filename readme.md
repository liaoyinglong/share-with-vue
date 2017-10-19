# vue基础

- ### 生命周期

- ### computed 和 watch 的区别

  > computed是用于定义**基于数据之上的数据**。
  >
  > 而watch是你想在**某个数据变化时做一些事情**，如果做的事情是更新其他数据，那其实与把这个要更新的数据项定义成computed是一样的，这个时候用computed更有可读性，虽然技术上讲watch也可以实现。
  >
  > 但你也可以在被watch的数据变化时做其他事情啊，比如调用一个方法，这个是computed做不到也不应该做的。
  >
  > 总结一下：
  >
  > - 1.如果一个数据依赖于其他数据，那么把这个数据设计为computed的
  > - 2.如果你需要在某个数据变化时做一些事情，使用watch来观察这个数据变化

- ### v-model 


  - v-model是一个语法糖
  - 简单实现组件的v-model

