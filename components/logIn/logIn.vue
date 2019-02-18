<template>
    <div>
      <div id="cboxOverlay" style="opacity: 0.9; cursor: pointer; visibility: visible; display: block;"></div>
      <div id="colorbox" class="" role="dialog" tabindex="-1" style="display: block; visibility: visible; top: 0px; left: 564px; position: fixed; width: 392px; height: 503px; opacity: 1; cursor: auto;"><div id="cboxWrapper" style="height: 503px; width: 392px;"><div><div id="cboxTopLeft" style="float: left;"></div><div id="cboxTopCenter" style="float: left; width: 372px;"></div><div id="cboxTopRight" style="float: left;"></div></div><div style="clear: left;"><div id="cboxMiddleLeft" style="float: left; height: 483px;"></div><div id="cboxContent" style="float: left; width: 372px; height: 483px;"><div id="cboxLoadedContent" style="width: 372px; overflow: auto; height: 483px;"><div id="formLoginRegis">
        <div class="formLoginRegis-tab-bg transtion"><em></em></div>
        <div class="formLoginRegis-tab">
          <span class="cur transtion">登录到车蚂蚁</span>
          <!-- <span class="transtion">注册车蚂蚁帐号</span> -->
        </div>

        <div class="formLoginRegis-logo"></div>
        <div class="formLoginRegis-box transtion">
          <div class="form-Login">
<!--登录的表单-->
            <div class="formBox">
            	<span class="inputbox" id="formLoginUser">
                	<input type="text" name="formLoginUser" ref="formLoginUser" error="手机帐号不存在" tip="手机号码格式错误" normal="手机号码" value="手机号码">
                    <i></i>
                </span>
              <span class="inputbox" id="formLoginPsw">
                	<input type="text" name="formLoginPsw" error="密码错误" tip="请输入密码" normal="密码" value="密码">
                    <input type="password" style="display:none;" ref="formLoginPsw" name="formLoginPsw" error="密码长度不能小于6位" tip="请输入密码" normal="密码">
                    <i></i>
                </span>
              <button class="formLoginBtn transtion" @click="logIn">立即登录</button>
              <div class="remember">
                <em class="fl"><input type="checkbox" name="loginauto"></em>
                <span class="fl">两周内自动登录</span>
                <span class="fr"><a href="http://www.chemayi.com/login/forget.html">忘记密码</a></span>
              </div>
            </div>
          </div>
          <div class="form-Regis">
            <div class="formBox">
            	<span class="inputbox" id="formRegisUser">
                	<input type="text" name="formRegisUser" error="手机号码已被注册" tip="手机号码格式错误" normal="手机号码" value="手机号码">
                    <i></i>
                </span>
              <span class="inputbox" id="formRegisPsw">
                	<input type="text" name="formRegisPsw" error="密码长度不能小于6位" tip="请输入密码" normal="密码" value="密码">
                    <i></i>
                </span>
              <button class="formRegisBtn transtion">立即注册</button>
              <div class="remember">
                <em class="fl cur"><input type="checkbox" name="userdeal" checked="checked"></em>
                <span class="fl">同意车蚂蚁<a class="userdeal" href="agreement.html" target="_blank">用户协议</a></span>
              </div>
            </div>
          </div>
        </div>

        <a class="formLoginRegis-close transtion" href="reg.html">没有账号？立即免费注册</a>
      </div></div><div id="cboxTitle" style="float: left; display: block;"></div><div id="cboxCurrent" style="float: left; display: none;"></div><button type="button" id="cboxPrevious" style="display: none;"></button><button type="button" id="cboxNext" style="display: none;"></button><button id="cboxSlideshow" style="display: none;"></button><div id="cboxLoadingOverlay" style="float: left; display: none;"></div><div id="cboxLoadingGraphic" style="float: left; display: none;"></div><button type="button" id="cboxClose">close</button></div><div id="cboxMiddleRight" style="float: left; height: 483px;"></div></div><div style="clear: left;"><div id="cboxBottomLeft" style="float: left;"></div><div id="cboxBottomCenter" style="float: left; width: 372px;"></div><div id="cboxBottomRight" style="float: left;"></div></div></div><div style="position: absolute; width: 9999px; visibility: hidden; max-width: none; display: none;"></div></div>
    </div>
</template>

<script>
    export default {
        data:function () {
          return {

          }
        },
      methods:{
          // 登录的方法
        logIn(){

        }
      }
    }
</script>

<style scoped>

</style>
