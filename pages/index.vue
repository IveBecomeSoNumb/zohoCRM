<!--
 * @Author: your name
 * @Date: 2019-12-14 19:50:05
 * @LastEditTime: 2019-12-17 18:47:04
 * @LastEditors: Please set LastEditors
 * @Description: In User Settings Edit
 * @FilePath: \homeaway\pages\index.vue
 -->
<template>
   <div>
     <partone></partone>
     <parttwo></parttwo>
     <partthree></partthree>
     <partfour></partfour>
   </div>
</template>

<script>
import Partone from '~/components/Partone'
import Parttwo from '~/components/Parttwo'
import Partthree from '~/components/Partthree'
import Partfour from '~/components/Partfour'





export default{
  components:{
    "partone":Partone, "parttwo":Parttwo,"partthree":Partthree,"partfour":Partfour,
  },
  
}
</script>
<style>
body{
  line-height: 26px;
}
</style>>

