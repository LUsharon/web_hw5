<template>
    <div class="header">
      <svg viewBox="140 140 520 520" xmlns="http://www.w3.org/2000/svg"><!--logo-->
        <path d="m617.24 354a126.36 126.36 0 0 0 -10.86-103.79 127.8 127.8 0 0 0 -137.65-61.32 126.36 126.36 0 0 0 -95.31-42.49 127.81 127.81 0 0 0 -121.92 88.49 126.4 126.4 0 0 0 -84.5 61.3 127.82 127.82 0 0 0 15.72 149.86 126.36 126.36 0 0 0 10.86 103.79 127.81 127.81 0 0 0 137.65 61.32 126.36 126.36 0 0 0 95.31 42.49 127.81 127.81 0 0 0 121.96-88.54 126.4 126.4 0 0 0 84.5-61.3 127.82 127.82 0 0 0 -15.76-149.81zm-190.66 266.49a94.79 94.79 0 0 1 -60.85-22c.77-.42 2.12-1.16 3-1.7l101-58.34a16.42 16.42 0 0 0 8.3-14.37v-142.39l42.69 24.65a1.52 1.52 0 0 1 .83 1.17v117.92a95.18 95.18 0 0 1 -94.97 95.06zm-204.24-87.23a94.74 94.74 0 0 1 -11.34-63.7c.75.45 2.06 1.25 3 1.79l101 58.34a16.44 16.44 0 0 0 16.59 0l123.31-71.2v49.3a1.53 1.53 0 0 1 -.61 1.31l-102.1 58.95a95.16 95.16 0 0 1 -129.85-34.79zm-26.57-220.49a94.71 94.71 0 0 1 49.48-41.68c0 .87-.05 2.41-.05 3.48v116.68a16.41 16.41 0 0 0 8.29 14.36l123.31 71.19-42.69 24.65a1.53 1.53 0 0 1 -1.44.13l-102.11-59a95.16 95.16 0 0 1 -34.79-129.81zm350.74 81.62-123.31-71.2 42.69-24.64a1.53 1.53 0 0 1 1.44-.13l102.11 58.95a95.08 95.08 0 0 1 -14.69 171.55c0-.88 0-2.42 0-3.49v-116.68a16.4 16.4 0 0 0 -8.24-14.36zm42.49-63.95c-.75-.46-2.06-1.25-3-1.79l-101-58.34a16.46 16.46 0 0 0 -16.59 0l-123.31 71.2v-49.3a1.53 1.53 0 0 1 .61-1.31l102.1-58.9a95.07 95.07 0 0 1 141.19 98.44zm-267.11 87.87-42.7-24.65a1.52 1.52 0 0 1 -.83-1.17v-117.92a95.07 95.07 0 0 1 155.9-73c-.77.42-2.11 1.16-3 1.7l-101 58.34a16.41 16.41 0 0 0 -8.3 14.36zm23.19-50 54.92-31.72 54.92 31.7v63.42l-54.92 31.7-54.92-31.7z"></path>
      </svg>
    </div>
    <div class="middle">
      <div class="middle_box">
        <div class="slogan">
          <h1>Welcome back</h1>
        </div>
        <div class="main">
          <div class="login">
            <input type="text" v-model="email" placeholder="Email address" @click="emailClick"><br>
            <button class="btn continue" @mouseover="buttonHover" @mouseout="buttonLeave">Continue</button>
            <p class="no_account">Don't have an account?
              <a class="sign_up" href="https://auth0.openai.com/u/signup/identifier?state=hKFo2SBwV3AyZHVXeDg5ZnJTTmVZQzJzU3ZhREpVYnozakZpY6Fur3VuaXZlcnNhbC1sb2dpbqN0aWTZIGRqWkMySlAxQi1yQV9qQTZ6b0FyTVkxbEJkemJxYmdro2NpZNkgVGRKSWNiZTE2V29USHROOTVueXl3aDVFNHlPbzZJdEc"> Sign up</a>
            </p>
          </div>
          <div class="line_or">
            <span style="">OR</span>
          </div>
          <div class="second_login">
            <a href="https://accounts.google.com/o/oauth2/auth/oauthchooseaccount?login_hint&prompt=login&response_type=code&redirect_uri=https%3A%2F%2Fauth0.openai.com%2Flogin%2Fcallback&scope=email%20profile&state=Gx47bH6gcaqANk7BhjNfRvo5o37h3oD_&client_id=799222349882-ne3i0s9jdm5s0p7ll2d7tlsi1vc1halt.apps.googleusercontent.com&service=lso&o2v=1&flowName=GeneralOAuthFlow">
              <button class="btn third">
                <img src="data:image/svg+xml;charset=utf-8,%3Csvg xmlns='http://www.w3.org/2000/svg' xmlns:xlink='http://www.w3.org/1999/xlink' viewBox='0 0 48 48'%3E%3Cdefs%3E%3Cpath id='a' d='M44.5 20H24v8.5h11.8C34.7 33.9 30.1 37 24 37c-7.2 0-13-5.8-13-13s5.8-13 13-13c3.1 0 5.9 1.1 8.1 2.9l6.4-6.4C34.6 4.1 29.6 2 24 2 11.8 2 2 11.8 2 24s9.8 22 22 22c11 0 21-8 21-22 0-1.3-.2-2.7-.5-4z'/%3E%3C/defs%3E%3CclipPath id='b'%3E%3Cuse xlink:href='%23a' overflow='visible'/%3E%3C/clipPath%3E%3Cpath clip-path='url(%23b)' fill='%23FBBC05' d='M0 37V11l17 13z'/%3E%3Cpath clip-path='url(%23b)' fill='%23EA4335' d='M0 11l17 13 7-6.1L48 14V0H0z'/%3E%3Cpath clip-path='url(%23b)' fill='%2334A853' d='M0 37l30-23 7.9 1L48 0v48H0z'/%3E%3Cpath clip-path='url(%23b)' fill='%234285F4' d='M48 48L17 24l-4-3 35-10z'/%3E%3C/svg%3E">
                <span>Continue with Google</span>
              </button>
            </a>
            <a href="https://login.live.com/oauth20_authorize.srf?client_id=7de44aed-c069-4216-a99c-45957f6c4f17&scope=openid+profile+email+https%3a%2f%2fgraph.microsoft.com%2fUser.Read+https%3a%2f%2fgraph.microsoft.com%2fUser.Read&redirect_uri=https%3a%2f%2fauth0.openai.com%2flogin%2fcallback&response_type=code&state=kHloZlSDPqY6p7iFMsx1XGaoln7ElC3m&prompt=login&uaid=6209d13b3b0f4992a63702a89187e854&msproxy=1&issuer=mso&tenant=consumers&ui_locales=zh-TW&epct=PAQABAAEAAAD--DLA3VO7QrddgJg7WevrZo2B_vKS9GhliNXjLWkvJkmbLkZPgFxrtjdEm3c5YsvV06_GL_covmctgmKmUlMarWj770pR5GMDQEH3a3AW_gCNfek6oHiuSpBAK6Hr6GQWK_ETaIYSQgYHVYlxvAukP6XKHOHL_3A6kWpqEqBzojz_fOBSuGzQaG0jGUm58kW2py6_8cN5GfVpZECe4KhzUzIyivGCa5-0XAsUhHNzByAA&jshs=0#">
              <button class="btn third">
                <img src="data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAOEAAADhCAMAAAAJbSJIAAAAVFBMVEX////yUCJ/ugAApO//uQDxOgBytADyShT2j3v/+/T/tAAAnO74+/R7uACpz3T0+f50wPTxMgD1hW//rgDwHABnrwDxQwD4s6ejzGgAle0Amu5ovPNVGgEPAAABAklEQVR4nO3biQnCQBRF0bhkceKWxGjU/vsUHKzgMyDh3AIenAJeVUmSJEmSJEmSJEmSJEmSpH/tVocaxu/KcW5CzQWF9SZU22Vhsw3VEBISEhISEhISEhISEhISEhISEhISEhISEhISEhISEhISEhISEhISEhISEhISEhISEhISEhKuSDi0oe4/4SlUSeHYxXpk4XIOtRQUSlL5LtHyzCFYQeGzD/V6Z+CUQk0Fhf0u1jUL0z5UIiQkJCQkJCQkJCQkJCQkJCQkJCQkJCQkJCQkJCQkJCQkJCQkJCQkJCQkJCQkJCQkJCQkJCRckXD97zxJkiRJkiRJkiRJkiRJkhTrA29gzkcc3y0uAAAAAElFTkSuQmCC">
                <span>Coutinue with Microsoft Account</span>
              </button>
            </a>
          </div>
        </div>
      </div>
    </div>
  <div class="footer">
        <span>
            <a href="https://openai.com/policies/terms-of-use">Terms of use</a>
            |
            <a href="https://openai.com/policies/privacy-policy">Privacy policy</a>
        </span>
  </div>
</template>

<script>
  // export default {
    function emailClick(){
      let input = document.getElementById("email");
      input.style.color = "black";
      input.value = "";
    }

    function buttonHover() {

      document.querySelector('.btn.continue').style.backgroundColor = "#1b7f65";
    }

    function buttonLeave() {
      document.querySelector('.btn.continue').style.backgroundColor = '';
    }
  // };

</script>

<style scoped>
*,*:before,*:after{
  box-sizing: border-box;
}

.header{
  height: 64px;
  margin: 0;
  padding: 32px 0 0;
  display: flex;
  justify-content: center;
  max-height: none;
  min-height: auto;
  max-width: none;
  min-width: auto;
}

svg{
  display: block;
  height: 32px;
  width: 32px;
  min-height: auto;
  min-width: auto;
  overflow: hidden;
}
.middle{
  height: 700px;
  padding: 80px 80px 80px 80px;
  min-width: auto;
  display: flex;
  justify-content: center;
}

.middle_box{
  height: 521px;
  width: 400px;
  min-height: auto;
  min-width: auto;
}
.slogan{
  height: 136px;
  width: 400px;
  padding: 40px 40px 24px 40px;
  min-height: auto;
  min-width: auto;
}
.slogan h1{
  font-family: ColfaxAI, -apple-system, BlinkMacSystemFont, Helvetica, sans-serif;
  font-size: 32px;
  font-weight: 700;
  line-height: 48px;
  text-decoration: none solid rgb(45, 51, 58);
  text-align: center;
  word-spacing: 0;
  display: block;
  height: 48px;
  width: 320px;
  margin: 24px 0 0 0;
}
.main{
  height: 385px;
  width: 400px;
  padding: 0 40px 40px 40px;
  min-height: auto;
  min-width: auto;
  display: block;
}
input{
  /* Font & Text */
  font-family: ColfaxAI, -apple-system, BlinkMacSystemFont, Helvetica, sans-serif;
  font-size: 16px;
  font-weight: 400;
  line-height: 17.6px;
  text-decoration: none;
  color: #7a7a83;
  /* Box */
  height: 52px;
  width: 320px;
  /*border: 1px solid  #C2C8D0;*/
  border: 1px solid  #7a7a83;
  padding: 0 16px 0 16px;
  max-height: none;
  min-height: auto;
  max-width: none;
  min-width: auto;
  border-radius: 3px;
  cursor: text;
  outline: none; /* 移除默认点击后的outline */
}

/* 新增 */
input:focus {
  border-color: #7a7a83; /* 点击后的固定颜色 */
}

.btn{
  /* Box */
  height: 52px;
  width: 320px;
  border-radius: 3px;
  text-align: center;
  max-width: none;
  min-width: 0;
  cursor: pointer;
}
.continue{
  /* Font & Text */
  font-family: ColfaxAI, -apple-system, BlinkMacSystemFont, Helvetica, sans-serif;
  font-size: 16px;
  font-weight: 400;
  color: rgb(255, 255, 255);
  /* Color & Background */
  background-attachment: scroll;
  background-color: rgb(38, 161, 130);
  /*讓外框不會有黑邊*/
  border: 0;
  margin: 24px 0 0;
  padding: 4px 16px;
  max-height: none;
  min-height: 52px;
  list-style-position: initial;
  /* Effects */
  transition: background-color 0.25s ease-in-out 0s, box-shadow 0.25s ease-in-out 0s;

}

.no_account{
  /* Font & Text */
  font-family: ColfaxAI, -apple-system, BlinkMacSystemFont, Helvetica, sans-serif;
  font-size: 14px;
  font-weight: 400;
  line-height: 14px;
  text-align: center;
  color: rgb(45, 51, 58);
  /* Box */
  height: 21px;
  width: 320px;
  border: 0;
  max-height: none;
  min-height: 0px;
  max-width: none;
  min-width: 0px;

}
.no_account a{
  line-height: 21px;
  text-decoration: none;
  color: rgb(16, 163, 127);
  padding: 4px;
}

.line_or{
  font-family: "ColfaxAI",-apple-system,BlinkMacSystemFont,Helvetica,sans-serif;
  width: 100%;
  display: flex;
  flex-direction: row;
  text-transform: uppercase;
  border: none;
  font-size: 12px;
  font-weight: 500;
  margin: 0;
  padding: 0 0 0 0;

  font: inherit;
  vertical-align: baseline;
  text-align: center;
}
.line_or:after, .line_or:before {
  font-size: 12px;
  font-weight: 500;
  font: inherit;
  -webkit-font-smoothing: antialiased;
  content: "";
  border-bottom: 1px solid rgb(194 200 208);
  flex: 1 0 auto;
  height: 0.5em;
  margin: 0;
  text-align: center;
  white-space: normal;
}

.line_or span {
  /* Font & Text */
  font-family: ColfaxAI, -apple-system, BlinkMacSystemFont, Helvetica, sans-serif;
  font-size: 12px;
  font-weight: 500;
  color: rgb(45, 51, 58);
  /* Box */
  height: 12px;
  width: 45px;
  max-width: none;
  min-width: auto;
}
.second_login{
  margin: 24px 0 0 0;
}
.second_login a{
  text-decoration: none solid;
}
.third{
  text-decoration: none solid rgb(45, 51, 58);
  /* Color & Background */
  background-color: rgb(255, 255, 255);
  color: rgb(45, 51, 58);
  /* Box */
  border: 0.666667px solid rgb(194, 200, 208);
  margin: 0 0 8px;
  padding: 0px 8px 0px 0px;
  /* Effects */
  transition: box-shadow 0.15s ease-in-out 0s, background-color 0.15s ease-in-out 0s;
  display: flex;
  align-items: center;
}
.third img{
  height: 20px;
  width: 20px;
  margin-right:16px;
  margin-left: 16px;
  display: block;
}
.second_login span{
  /* Font & Text */
  font-family: ColfaxAI, -apple-system, BlinkMacSystemFont, Helvetica, sans-serif;
  font-size: 16px;
  font-weight: 400;
  text-decoration: none solid rgb(45, 51, 58);
  text-align: left;
  display: block;

}
.footer{
  height: 57px;
  padding: 12px 0 24px 0;
  min-height: auto;
  max-width: none;
  min-width: auto;
  display: flex;
  justify-content: center;
  color: #6E6E80;
}
.footer a{
  font-family: ColfaxAI, -apple-system, BlinkMacSystemFont, Helvetica, sans-serif;
  font-size: 14px;
  line-height: 21px;
  text-decoration: none solid;
  color: #10A37F;
  height: 21px;
  width: 82.3125px;
  margin: 0 10px 0 10px;
  min-height: auto;
  min-width: auto;
}
</style>