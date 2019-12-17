<!--
 * @Author: your name
 * @Date: 2019-12-14 19:50:05
 * @LastEditTime: 2019-12-15 18:03:04
 * @LastEditors: Please set LastEditors
 * @Description: In User Settings Edit
 * @FilePath: \homeaway\components\Head.vue
 -->
<template>
<div class="full">
<div class="partone-full">
 <div class="content">
   <div class="ban_lft">
<h3>Looking for a Salesforce alternative?</h3>
<h1>Try out the Smarter, Better, Faster CRM Software</h1>
<p>Reach prospects across every channel with a solution that's as committed to closing deals as you are. From small businesses to large enterprises, Zoho CRM helps businesses of all sizes close more deals in less time.</p>
   </div>
   <div class="signup">
     <p class="signup-p">Sign up for a free trial.</p>
     <div class="label">
      <input autofocus type="text" name="name" class="input-field" placeholder="Full Name">
      <input autofocus type="text" name="email" class="input-field" placeholder="Email Address">
      <input autofocus type="text" name="password" class="input-field" placeholder="Password">
      <input autofocus type="text" name="phone" class="input-field" placeholder="Phone">
     <p class="input-p">Base on your IP, you are in United States<span class="spanchange">Change</span></p>
     <p class="input-p">You data will be in US data center</p>
     <b-form-checkbox size="sm">I agree with the <span class="spanchange"> Terms of Service</span> and<span class="spanchange"> Privacy Policy</span></b-form-checkbox>
     <input id="signupbutton" value="CREATE ACCOUNT" type="submit" class="btn" style="opacity:1;">
     </div>
   </div>
 </div>
</div>
</div>
</template>

<script>
export default {
    name:'partone'
}
</script>

<style scoped>
.full{
width:100%;
display: inline-block;
background:#03A9F5;
padding:80px 0 90px;
text-align: center;
position: relative;
}
.partone-full{
max-width:1140px;
margin: 0 auto;
width: 100%;
color:#fff;
padding:50px 0px 40px;
position: relative; 
}
.ban_lft{
  display: block;
  float: left;
  width: 60%;
  padding:80px 5% 0px 0%;
  box-sizing: border-box;
  text-align: left;
}
.ban_lft h1{
  font-size: 45px;
  font-family: 'proxima_nova_rgbold';
  margin: 15px 0;

}
p,h3{
  font-family: 'proxima_nova_rgregular', Arial, Helvetica, sans-serif;
}
.signup{
  float: right;
  position: relative;
  width: 39%;
  text-align: left;
}
.input-field{
  height:35px;
  width:400px;
  padding:20px 10px;
  margin:5px;
  border:0px;
  
}
.signup-p{
  font-size:30px;
  padding-bottom: 2px;
  text-transform: unset;
  font-family: proxima_novasemibold;
}
.input-p{
  font-family: proxima_nova_rgregular;
  font-size:12px;
  margin-top:2px;
}
.spanchange{
  color:inherit;
  cursor:pointer;
  text-decoration: underline;
  margin-left: 3px;
}
.btn{
  font-size:16px;
  line-height:normal;
  background: #f0483e;
  text-align:center;
  text-transform:uppercase;
  width: 100%;
  font-weight: 600;
  color:#fff;
  -webkit-appearance: none;
  margin: 20px 0;
}
</style>