<!--
 * @Author: your name
 * @Date: 2019-12-16 22:29:33
 * @LastEditTime: 2019-12-17 19:53:10
 * @LastEditors: Please set LastEditors
 * @Description: In User Settings Edit
 * @FilePath: \homeaway\components\Partfive.vue
 -->

<template>
<div class="five-full">
    <div class="foot">
    <h3>Get ready for an all-new CRM experience.</h3>
    <a class="btn">TRY ZOHO CRM</a>
    <p class="support-txt">Need assistance switching to Zoho CRM? Contact us at <span>support@zohocrm.com</span></p>
    <p class="foot-txt">The names and logos for Zoho are trademarks of Zoho Corp. All other trademarks, brand names, or product names
<br>
belong to their respective holders. Comparison information as of 16.05.2018
</p>
<div class="footer">© 2019, Zoho Corporation Pvt. Ltd. All Rights Reserved.</div>
</div>
</div>
</template>

<script>

export default {
    name:'partfive',
    
}
</script>

<style scoped>
.five-full{
    padding:70px 0px 80px;
    width: 100%;
    display: inline-block;
    text-align: center;
}
.foot{
    max-width: 940px;
    width: 100%;
    margin: 0px auto;
}
.btn{
    font-size:18px;
    color:#fff;
    padding:12px 30px;
    background:#f0483e;
    outline: none;
    cursor:pointer;
    display: inline-block;
    text-decoration: none;
    font-family: 'proxima_novasemibold';
}
.support-txt{
    font-size:18px;
    font-family: 'proxima_nova_rgregular';
    color:#111111;
    margin-top:40px;
}
.foot-txt{
    font-size:12px;
    font-family: 'proxima_nova_rgregular';
    color:#111111;
    margin-top:40px;
    line-height: 20px;
}
.footer{
    font-size:12px;
    text-align: center;
    padding:25px 25px 0;
    font-family: proxima_nova_rgregular;
    color:#333;

}
</style>