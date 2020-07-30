<!--  -->
<template>
<div class>
    <div class="home-header">
        <span>头条</span>
    </div>
    <div class="home-contnet">
        <div class="home-left">
         <Navigator></Navigator>
        </div>
        <div class="home-middle">
          zong
        </div>
        <div class="home-right">
          zyou
        </div>
    </div>
</div>
</template>

<script>
//这里可以导入其他文件（比如：组件，工具js，第三方插件js，json文件，图片文件等等）
//例如：import 《组件名称》 from '《组件路径》';
import Navigator from '@/components/Navigator.vue'
export default {
//import引入的组件需要注入到对象中才能使用
components: {
  Navigator
},
data() {
//这里存放数据
return {

};
},
//监听属性 类似于data概念
computed: {},
//监控data中的数据变化
watch: {},
//方法集合
methods: {

},
//生命周期 - 创建完成（可以访问当前this实例）
created() {

},
//生命周期 - 挂载完成（可以访问DOM元素）
mounted() {

},
beforeCreate() {}, //生命周期 - 创建之前
beforeMount() {}, //生命周期 - 挂载之前
beforeUpdate() {}, //生命周期 - 更新之前
updated() {}, //生命周期 - 更新之后
beforeDestroy() {}, //生命周期 - 销毁之前
destroyed() {}, //生命周期 - 销毁完成
activated() {}, //如果页面有keep-alive缓存功能，这个函数会触发
}
</script>
<style lang='less' scoped>
 .home-header {
   height: 30px;
   background-color: black;
  span {
      color: white;
  }
}
.home-contnet {
  width: 80vw;
  margin: 0 auto;
  display: flex;
  .home-left {
    background-color: turquoise;
    flex: 1;
  }

  .home-middle {
      flex: 3;
      background-color: wheat;
  }

  .home-right {
      flex: 2;
      background-color: violet;
  }
}
</style>