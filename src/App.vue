<template>
  <div id="app">
    <NavBar/>
    <router-view/>
  </div>
</template>

<script>
  import NavBar from '@/components/NavBar.vue'
  export default {
    name:'App',
    components:{
      NavBar,
    }
  }
</script>

<style>
@import url('https://fonts.googleapis.com/css2?family=Spartan:wght@700&display=swap');


  /* box model normalization */   
*,*:before,*:after{-webkit-box-sizing:border-box;-moz-box-sizing:border-box;box-sizing:border-box}

/* reset */  
html,body,div,applet,object,iframe, h1,h2,h3,h4,h5,h6,p,blockquote,pre,a,abbr,acronym,address,big,cite,code,del,dfn,em,font,ins,kbd,q,s,samp,small,strike,strong,sub,sup,tt,var,b,u,i,center,span,img,dl,dt,dd,ol,ul,li,fieldset,form,label,legend{margin:0;padding:0;border:0;outline:0;font-size:100%;font-weight:normal;background:transparent;text-decoration:none; color:inherit;}body{line-height:1.4;}ul{list-style:none;}blockquote,q{quotes:none;}blockquote:before,blockquote:after,q:before,q:after{content:'';content:none;}:focus{outline:0;}button a,button a:hover,button a:visited{color:inherit;text-decoration:none;}

/*! normalize.css v3.0.3 | MIT License | github.com/necolas/normalize.css */   
html{font-family:Arial, Helvetica, sans-serif;-ms-text-size-adjust:100%;-webkit-text-size-adjust:100%}article,aside,details,figcaption,figure,footer,header,hgroup,main,menu,nav,section,summary{display:block}audio,canvas,progress,video{display:inline-block;vertical-align:baseline}audio:not([controls]){display:none;height:0}[hidden],template{display:none}a{background-color:transparent;}a:active,a:hover{outline:0;cursor:"pointer"}abbr[title]{border-bottom:1px dotted}b,strong{font-weight:bold}dfn{font-style:italic}mark{background:#ff0;color:#000}small{font-size:80%}sub,sup{font-size:75%;line-height:0;position:relative;vertical-align:baseline}sup{top:-0.5em}sub{bottom:-0.25em}svg:not(:root){overflow:hidden}figure{margin:0;margin-block-start:0;margin-block-end:0;margin-inline-start:0;margin-inline-end:0;}hr{height:0}pre{overflow:auto}code,kbd,pre,samp{font-family:monospace,monospace;}button,input,optgroup,select,textarea{color:inherit;font:inherit;margin:0}button{overflow:visible}button,select{text-transform:none}button,html input[type="button"],input[type="reset"],input[type="submit"]{-webkit-appearance:button;cursor:pointer}button[disabled],html input[disabled]{cursor:default}button::-moz-focus-inner,input::-moz-focus-inner{border:0;padding:0}input{line-height:normal}input[type="checkbox"],input[type="radio"]{padding:0}input[type="number"]::-webkit-inner-spin-button,input[type="number"]::-webkit-outer-spin-button{height:auto}input[type="search"]{-webkit-appearance:textfield;}input[type="search"]::-webkit-search-cancel-button,input[type="search"]::-webkit-search-decoration{-webkit-appearance:none}textarea{overflow:auto}optgroup{font-weight:bold}table{border-collapse:collapse;border-spacing:0}td,th{padding:0}

#app {
  font-family: "Spartan";
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  background-color: #ffe500;
}


</style>
