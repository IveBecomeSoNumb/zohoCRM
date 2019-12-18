<!--
 * @Author: your name
 * @Date: 2019-12-16 12:58:44
 * @LastEditTime: 2019-12-17 19:08:32
 * @LastEditors: Please set LastEditors
 * @Description: In User Settings Edit
 * @FilePath: \homeaway\components\Parttwo.vue
 -->
<template>
<div class="partthree-full">
    <h1 class="three">Compare Features</h1>
        <div class="inner">
            <b-table striped hover :items="items" :fields="fields"></b-table>
            <input id="signupbutton" value="TRY ZOHO CRM" type="submit" class="btn" style="opacity:1;">
        </div>
</div>
</template>

<script>

export default {
    name:'partthree',
    data() {
      return {
        // Note `isActive` is left out and will not appear in the rendered table
        fields: ['Features', 'Zoho_CRM', 'salesforce'],
        items: [
          { isActive: true, salesforce: 'No', Features: 'Inbuilt AI ', Zoho_CRM: 'Yes' },
          { isActive: true, salesforce: 'No', Features: 'Inbuilt AI ', Zoho_CRM: 'Yes' },
          { isActive: true, salesforce: 'No', Features: 'Inbuilt AI ', Zoho_CRM: 'Yes' },
          { isActive: true, salesforce: 'No', Features: 'Inbuilt AI ', Zoho_CRM: 'Yes' },
          { isActive: true, salesforce: 'No', Features: 'Inbuilt AI ', Zoho_CRM: 'Yes' },
          { isActive: true, salesforce: 'No', Features: 'Inbuilt AI ', Zoho_CRM: 'Yes' },
          { isActive: true, salesforce: 'No', Features: 'Inbuilt AI ', Zoho_CRM: 'Yes' },
          { isActive: true, salesforce: 'No', Features: 'Inbuilt AI ', Zoho_CRM: 'Yes' },
          { isActive: true, salesforce: 'No', Features: 'Inbuilt AI ', Zoho_CRM: 'Yes' },
          
         
        ]
      }
    }
}

</script>

<style scoped>
.partthree-full{
    padding:50px 0 90px;
    width: 100%;
    text-align:center;
    background:#fff;
}
.three{
    margin-top:20px;
}
h1{
    font-size:40px;
    color:#111111;
    font-family: 'proxima_nova_rgbold';
    font-weight:inherit;
    margin-bottom: 15px;
    line-height: 1.2;
}
.inner{
    width: 100%;
    margin:40px auto 0;
    text-align:center;
    padding:40px 40px;
   
}
.btn{
  font-size:18px;
  color:#fff;
  padding:12px 30px;
  background: #f0483e;
  outline:none;
  cursor:pointer;
  margin-top:40px;
  display: inline-block !important;
  text-decoration:none;
  font-family: 'proxima_novasemibold';
  
}
</style>