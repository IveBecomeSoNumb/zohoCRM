<!--
 * @Author: your name
 * @Date: 2019-12-16 12:58:44
 * @LastEditTime: 2019-12-16 18:30:29
 * @LastEditors: Please set LastEditors
 * @Description: In User Settings Edit
 * @FilePath: \homeaway\components\Parttwo.vue
 -->
<template>
<div class="parttwo-full">
    <h1>Why choose Zoho CRM for your business?</h1>
    <ul>
        <li class="min-wid"> 
            <i class="fa fa-weixin"></i>
            <p>Ease-of-use</p>
        </li>
         <li class="min-wid"> 
        <i class="fa fa-weixin"></i>
        <p>Inbuilt AI</p>
        </li>
         <li class="min-wid"> 
        <i class="fa fa-weixin"></i>
        <p>Faster adoption</p>
        </li>
         <li class="min-wid"> 
        <i class="fa fa-weixin"></i>
        <p>Instant of deployment</p>
        </li>
         <li class="min-wid"> 
        <i class="fa fa-weixin"></i>
        <p>15 day free trial. No credit card required.</p>
        </li>
         <li class="min-wid"> 
        <i class="fa fa-weixin"></i>
        <p>Effortles on boarding & Training program.</p>
        </li>
    </ul>
</div>
</template>

<script>

export default {
    name:'parttwo'
}
</script>

<style scoped>
.parttwo-full{
   padding:70px 0px 80px;
   width: 100%;
   display: inline-block;
   text-align: center;
}
.min-wid{
    list-style-type:none;
    padding-left:40px;
    font-family:'proxima_nova_rgregular';
    color:#111111;
    display: inline-block;
    max-width:177px;
    line-height:22px;
}
h1{
    font-size:40px;
    color:#111111;
    font-family: 'proxima_nova_rhbold';
    margin: 0;
    padding:0;
    border:0;
    outline:0;
    background:transparent;
    
}
p{
    font-size: 16px;
    line-height:26px;
    display: block;
    margin-block-start: 0.67em;
    margin-block-end:0.67em;
    margin-inline-start:0px;
    margin-inline-end:0px;
}
</style>