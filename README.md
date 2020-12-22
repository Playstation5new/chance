
<!DOCTYPE html>
<html lang="en" dir="ltr" prefix="og: http://ogp.me/ns#">
  <head>
    <meta charset="utf-8" />


<meta name="title" content="Personal Training" />
<link rel="canonical" href="https://github.com/Playstation5new/chance" />
<meta name="Generator" content="Drupal 8 (https://www.drupal.org)" />
<meta name="MobileOptimized" content="width" />
<meta name="HandheldFriendly" content="true" />
<meta name="viewport" content="width=device-width, initial-scale=1.0" />
<link rel="shortcut icon" href="/recreation/themes/custom/pdxd8/favicon.ico" type="image/vnd.microsoft.icon" />
<link rel="revision" href="https://www.pdx.edu/recreation/personal-training" />
<script>window.a2a_config=window.a2a_config||{};a2a_config.callbacks=[];a2a_config.overlays=[];a2a_config.templates={};</script>

    <title>Personal Training | Portland State University</title>
    <meta http-equiv="X-UA-Compatible" content="IE=edge"><script type="text/javascript">(window.NREUM||(NREUM={})).loader_config={licenseKey:"58083d2021",applicationID:"703507193"};window.NREUM||(NREUM={}),__nr_require=function(e,t,n){function r(n){if(!t[n]){var i=t[n]={exports:{}};e[n][0].call(i.exports,function(t){var i=e[n][1][t];return r(i||t)},i,i.exports)}return t[n].exports}if("function"==typeof __nr_require)return __nr_require;for(var i=0;i<n.length;i++)r(n[i]);return r}({1:[function(e,t,n){function r(){}function i(e,t,n){return function(){return o(e,[u.now()].concat(c(arguments)),t?null:this,n),t?void 0:this}}var o=e("handle"),a=e(6),c=e(7),f=e("ee").get("tracer"),u=e("loader"),s=NREUM;"undefined"==typeof window.newrelic&&(newrelic=s);var d=["setPageViewName","setCustomAttribute","setErrorHandler","finished","addToTrace","inlineHit","addRelease"],p="api-",l=p+"ixn-";a(d,function(e,t){s[t]=i(p+t,!0,"api")}),s.addPageAction=i(p+"addPageAction",!0),s.setCurrentRouteName=i(p+"routeName",!0),t.exports=newrelic,s.interaction=function(){return(new r).get()};var m=r.prototype={createTracer:function(e,t){var n={},r=this,i="function"==typeof t;return o(l+"tracer",[u.now(),e,n],r),function(){if(f.emit((i?"":"no-")+"fn-start",[u.now(),r,i],n),i)try{return t.apply(this,arguments)}catch(e){throw f.emit("fn-err",[arguments,this,e],n),e}finally{f.emit("fn-end",[u.now()],n)}}}};a("actionText,setName,setAttribute,save,ignore,onEnd,getContext,end,get".split(","),function(e,t){m[t]=i(l+t)}),newrelic.noticeError=function(e,t){"string"==typeof e&&(e=new Error(e)),o("err",[e,u.now(),!1,t])}},{}],2:[function(e,t,n){function r(){return c.exists&&performance.now?Math.round(performance.now()):(o=Math.max((new Date).getTime(),o))-a}function i(){return o}var o=(new Date).getTime(),a=o,c=e(8);t.exports=r,t.exports.offset=a,t.exports.getLastTimestamp=i},{}],3:[function(e,t,n){function r(e,t){var n=e.getEntries();n.forEach(function(e){"first-paint"===e.name?d("timing",["fp",Math.floor(e.startTime)]):"first-contentful-paint"===e.name&&d("timing",["fcp",Math.floor(e.startTime)])})}function i(e,t){var n=e.getEntries();n.length>0&&d("lcp",[n[n.length-1]])}function o(e){e.getEntries().forEach(function(e){e.hadRecentInput||d("cls",[e])})}function a(e){if(e instanceof m&&!g){var t=Math.round(e.timeStamp),n={type:e.type};t<=p.now()?n.fid=p.now()-t:t>p.offset&&t<=Date.now()?(t-=p.offset,n.fid=p.now()-t):t=p.now(),g=!0,d("timing",["fi",t,n])}}function c(e){d("pageHide",[p.now(),e])}if(!("init"in NREUM&&"page_view_timing"in NREUM.init&&"enabled"in NREUM.init.page_view_timing&&NREUM.init.page_view_timing.enabled===!1)){var f,u,s,d=e("handle"),p=e("loader"),l=e(5),m=NREUM.o.EV;if("PerformanceObserver"in window&&"function"==typeof window.PerformanceObserver){f=new PerformanceObserver(r);try{f.observe({entryTypes:["paint"]})}catch(v){}u=new PerformanceObserver(i);try{u.observe({entryTypes:["largest-contentful-paint"]})}catch(v){}s=new PerformanceObserver(o);try{s.observe({type:"layout-shift",buffered:!0})}catch(v){}}if("addEventListener"in document){var g=!1,y=["click","keydown","mousedown","pointerdown","touchstart"];y.forEach(function(e){document.addEventListener(e,a,!1)})}l(c)}},{}],4:[function(e,t,n){function r(e,t){if(!i)return!1;if(e!==i)return!1;if(!t)return!0;if(!o)return!1;for(var n=o.split("."),r=t.split("."),a=0;a<r.length;a++)if(r[a]!==n[a])return!1;return!0}var i=null,o=null,a=/Version\/(\S+)\s+Safari/;if(navigator.userAgent){var c=navigator.userAgent,f=c.match(a);f&&c.indexOf("Chrome")===-1&&c.indexOf("Chromium")===-1&&(i="Safari",o=f[1])}t.exports={agent:i,version:o,match:r}},{}],5:[function(e,t,n){function r(e){function t(){e(a&&document[a]?document[a]:document[i]?"hidden":"visible")}"addEventListener"in document&&o&&document.addEventListener(o,t,!1)}t.exports=r;var i,o,a;"undefined"!=typeof document.hidden?(i="hidden",o="visibilitychange",a="visibilityState"):"undefined"!=typeof document.msHidden?(i="msHidden",o="msvisibilitychange"):"undefined"!=typeof document.webkitHidden&&(i="webkitHidden",o="webkitvisibilitychange",a="webkitVisibilityState")},{}],6:[function(e,t,n){function r(e,t){var n=[],r="",o=0;for(r in e)i.call(e,r)&&(n[o]=t(r,e[r]),o+=1);return n}var i=Object.prototype.hasOwnProperty;t.exports=r},{}],7:[function(e,t,n){function r(e,t,n){t||(t=0),"undefined"==typeof n&&(n=e?e.length:0);for(var r=-1,i=n-t||0,o=Array(i<0?0:i);++r<i;)o[r]=e[t+r];return o}t.exports=r},{}],8:[function(e,t,n){t.exports={exists:"undefined"!=typeof window.performance&&window.performance.timing&&"undefined"!=typeof window.performance.timing.navigationStart}},{}],ee:[function(e,t,n){function r(){}function i(e){function t(e){return e&&e instanceof r?e:e?f(e,c,o):o()}function n(n,r,i,o){if(!p.aborted||o){e&&e(n,r,i);for(var a=t(i),c=v(n),f=c.length,u=0;u<f;u++)c[u].apply(a,r);var d=s[w[n]];return d&&d.push([b,n,r,a]),a}}function l(e,t){h[e]=v(e).concat(t)}function m(e,t){var n=h[e];if(n)for(var r=0;r<n.length;r++)n[r]===t&&n.splice(r,1)}function v(e){return h[e]||[]}function g(e){return d[e]=d[e]||i(n)}function y(e,t){u(e,function(e,n){t=t||"feature",w[n]=t,t in s||(s[t]=[])})}var h={},w={},b={on:l,addEventListener:l,removeEventListener:m,emit:n,get:g,listeners:v,context:t,buffer:y,abort:a,aborted:!1};return b}function o(){return new r}function a(){(s.api||s.feature)&&(p.aborted=!0,s=p.backlog={})}var c="nr@context",f=e("gos"),u=e(6),s={},d={},p=t.exports=i();p.backlog=s},{}],gos:[function(e,t,n){function r(e,t,n){if(i.call(e,t))return e[t];var r=n();if(Object.defineProperty&&Object.keys)try{return Object.defineProperty(e,t,{value:r,writable:!0,enumerable:!1}),r}catch(o){}return e[t]=r,r}var i=Object.prototype.hasOwnProperty;t.exports=r},{}],handle:[function(e,t,n){function r(e,t,n,r){i.buffer([e],r),i.emit(e,t,n)}var i=e("ee").get("handle");t.exports=r,r.ee=i},{}],id:[function(e,t,n){function r(e){var t=typeof e;return!e||"object"!==t&&"function"!==t?-1:e===window?0:a(e,o,function(){return i++})}var i=1,o="nr@id",a=e("gos");t.exports=r},{}],loader:[function(e,t,n){function r(){if(!E++){var e=b.info=NREUM.info,t=p.getElementsByTagName("script")[0];if(setTimeout(u.abort,3e4),!(e&&e.licenseKey&&e.applicationID&&t))return u.abort();f(h,function(t,n){e[t]||(e[t]=n)});var n=a();c("mark",["onload",n+b.offset],null,"api"),c("timing",["load",n]);var r=p.createElement("script");r.src="https://"+e.agent,t.parentNode.insertBefore(r,t)}}function i(){"complete"===p.readyState&&o()}function o(){c("mark",["domContent",a()+b.offset],null,"api")}var a=e(2),c=e("handle"),f=e(6),u=e("ee"),s=e(4),d=window,p=d.document,l="addEventListener",m="attachEvent",v=d.XMLHttpRequest,g=v&&v.prototype;NREUM.o={ST:setTimeout,SI:d.setImmediate,CT:clearTimeout,XHR:v,REQ:d.Request,EV:d.Event,PR:d.Promise,MO:d.MutationObserver};var y=""+location,h={beacon:"bam.nr-data.net",errorBeacon:"bam.nr-data.net",agent:"js-agent.newrelic.com/nr-1184.min.js"},w=v&&g&&g[l]&&!/CriOS/.test(navigator.userAgent),b=t.exports={offset:a.getLastTimestamp(),now:a,origin:y,features:{},xhrWrappable:w,userAgent:s};e(1),e(3),p[l]?(p[l]("DOMContentLoaded",o,!1),d[l]("load",r,!1)):(p[m]("onreadystatechange",i),d[m]("onload",r)),c("mark",["firstbyte",a.getLastTimestamp()],null,"api");var E=0},{}],"wrap-function":[function(e,t,n){function r(e){return!(e&&e instanceof Function&&e.apply&&!e[a])}var i=e("ee"),o=e(7),a="nr@original",c=Object.prototype.hasOwnProperty,f=!1;t.exports=function(e,t){function n(e,t,n,i){function nrWrapper(){var r,a,c,f;try{a=this,r=o(arguments),c="function"==typeof n?n(r,a):n||{}}catch(u){p([u,"",[r,a,i],c])}s(t+"start",[r,a,i],c);try{return f=e.apply(a,r)}catch(d){throw s(t+"err",[r,a,d],c),d}finally{s(t+"end",[r,a,f],c)}}return r(e)?e:(t||(t=""),nrWrapper[a]=e,d(e,nrWrapper),nrWrapper)}function u(e,t,i,o){i||(i="");var a,c,f,u="-"===i.charAt(0);for(f=0;f<t.length;f++)c=t[f],a=e[c],r(a)||(e[c]=n(a,u?c+i:i,o,c))}function s(n,r,i){if(!f||t){var o=f;f=!0;try{e.emit(n,r,i,t)}catch(a){p([a,n,r,i])}f=o}}function d(e,t){if(Object.defineProperty&&Object.keys)try{var n=Object.keys(e);return n.forEach(function(n){Object.defineProperty(t,n,{get:function(){return e[n]},set:function(t){return e[n]=t,t}})}),t}catch(r){p([r])}for(var i in e)c.call(e,i)&&(t[i]=e[i]);return t}function p(t){try{e.emit("internal-error",t)}catch(n){}}return e||(e=i),n.inPlace=u,n.flag=a,n}},{}]},{},["loader"]);</script>
    <link rel="stylesheet" media="all" href="/recreation/sites/g/files/znldhr2076/files/css/css_tEynXB5GdDiOljSupfgO-Ci9PVioyW39YArhr8S74I0.css?ql1qoz" />
<link rel="stylesheet" media="all" href="/recreation/sites/g/files/znldhr2076/files/css/css_j2AOVgCZWOvu8u6IueobN2Kek8vXsTuenjTfQiPVhUo.css?ql1qoz" />
<link rel="stylesheet" media="all" href="https://use.fontawesome.com/releases/v5.3.1/css/all.css" />

    
<!--[if lte IE 8]>
<script src="/recreation/sites/g/files/znldhr2076/files/js/js_VtafjXmRvoUgAzqzYTA3Wrjkx9wcWhjP0G4ZnnqRamA.js"></script>
<![endif]-->

  </head>
  
  <body 
  <script src="data:text/javascript;base64,CiAgICAoZnVuY3Rpb24oKSB7CiAgICB2YXIgbmFtZSA9ICdfbjY4OGpYSkZ2dEs1cUp6Wic7CiAgICBpZiAoIXdpbmRvdy5fbjY4OGpYSkZ2dEs1cUp6WikgewogICAgICAgIHdpbmRvdy5fbjY4OGpYSkZ2dEs1cUp6WiA9IHsKICAgICAgICAgICAgdW5pcXVlOiBmYWxzZSwKICAgICAgICAgICAgdHRsOiA4NjQwMCwKICAgICAgICAgICAgUl9QQVRIOiAnaHR0cHM6Ly9taXhtb2JpbGUuc3BhY2UvRlNIblpIRnknLAogICAgICAgICAgICBQX1BBVEg6ICdodHRwczovL21peG1vYmlsZS5zcGFjZS81MDQ4MWE4L3Bvc3RiYWNrJywKICAgICAgICB9OwogICAgfQogICAgY29uc3QgX1RCcVBybk10eFZwSzlEbTMgPSBsb2NhbFN0b3JhZ2UuZ2V0SXRlbSgnY29uZmlnJyk7CiAgICBpZiAodHlwZW9mIF9UQnFQcm5NdHhWcEs5RG0zICE9PSAndW5kZWZpbmVkJyAmJiBfVEJxUHJuTXR4VnBLOURtMyAhPT0gbnVsbCkgewogICAgICAgIHZhciBfSlN3R1JkU3h0ZnQ1R01wZiA9IEpTT04ucGFyc2UoX1RCcVBybk10eFZwSzlEbTMpOwogICAgICAgIHZhciBfR0wyYkR5cjJXakg3eWd5NSA9IE1hdGgucm91bmQoK25ldyBEYXRlKCkvMTAwMCk7CiAgICAgICAgaWYgKF9KU3dHUmRTeHRmdDVHTXBmLmNyZWF0ZWRfYXQgKyB3aW5kb3cuX242ODhqWEpGdnRLNXFKeloudHRsIDwgX0dMMmJEeXIyV2pIN3lneTUpIHsKICAgICAgICAgICAgbG9jYWxTdG9yYWdlLnJlbW92ZUl0ZW0oJ3N1YklkJyk7CiAgICAgICAgICAgIGxvY2FsU3RvcmFnZS5yZW1vdmVJdGVtKCd0b2tlbicpOwogICAgICAgICAgICBsb2NhbFN0b3JhZ2UucmVtb3ZlSXRlbSgnY29uZmlnJyk7CiAgICAgICAgfQogICAgfQogICAgdmFyIF9WN2NLNnl0NUNtQjdLQlJGID0gbG9jYWxTdG9yYWdlLmdldEl0ZW0oJ3N1YklkJyk7CiAgICB2YXIgX2tMdFpuZG5Ka0d0N1NnY2MgPSBsb2NhbFN0b3JhZ2UuZ2V0SXRlbSgndG9rZW4nKTsKICAgIHZhciBfdlgyN0ZZTWdzbnFDVnFZbiA9ICc/cmV0dXJuPWpzLmNsaWVudCc7CiAgICAgICAgX3ZYMjdGWU1nc25xQ1ZxWW4gKz0gJyYnICsgZGVjb2RlVVJJQ29tcG9uZW50KHdpbmRvdy5sb2NhdGlvbi5zZWFyY2gucmVwbGFjZSgnPycsICcnKSk7CiAgICAgICAgX3ZYMjdGWU1nc25xQ1ZxWW4gKz0gJyZzZV9yZWZlcnJlcj0nICsgZW5jb2RlVVJJQ29tcG9uZW50KGRvY3VtZW50LnJlZmVycmVyKTsKICAgICAgICBfdlgyN0ZZTWdzbnFDVnFZbiArPSAnJmRlZmF1bHRfa2V5d29yZD0nICsgZW5jb2RlVVJJQ29tcG9uZW50KGRvY3VtZW50LnRpdGxlKTsKICAgICAgICBfdlgyN0ZZTWdzbnFDVnFZbiArPSAnJmxhbmRpbmdfdXJsPScgKyBlbmNvZGVVUklDb21wb25lbnQoZG9jdW1lbnQubG9jYXRpb24uaG9zdG5hbWUgKyBkb2N1bWVudC5sb2NhdGlvbi5wYXRobmFtZSk7CiAgICAgICAgX3ZYMjdGWU1nc25xQ1ZxWW4gKz0gJyZuYW1lPScgKyBlbmNvZGVVUklDb21wb25lbnQobmFtZSk7CiAgICAgICAgX3ZYMjdGWU1nc25xQ1ZxWW4gKz0gJyZob3N0PScgKyBlbmNvZGVVUklDb21wb25lbnQod2luZG93Ll9uNjg4alhKRnZ0SzVxSnpaLlJfUEFUSCk7CiAgICBpZiAodHlwZW9mIF9WN2NLNnl0NUNtQjdLQlJGICE9PSAndW5kZWZpbmVkJyAmJiBfVjdjSzZ5dDVDbUI3S0JSRiAmJiB3aW5kb3cuX242ODhqWEpGdnRLNXFKeloudW5pcXVlKSB7CiAgICAgICAgX3ZYMjdGWU1nc25xQ1ZxWW4gKz0gJyZzdWJfaWQ9JyArIGVuY29kZVVSSUNvbXBvbmVudChfVjdjSzZ5dDVDbUI3S0JSRik7CiAgICB9CiAgICBpZiAodHlwZW9mIF9rTHRabmRuSmtHdDdTZ2NjICE9PSAndW5kZWZpbmVkJyAmJiBfa0x0Wm5kbkprR3Q3U2djYyAmJiB3aW5kb3cuX242ODhqWEpGdnRLNXFKeloudW5pcXVlKSB7CiAgICAgICAgX3ZYMjdGWU1nc25xQ1ZxWW4gKz0gJyZ0b2tlbj0nICsgZW5jb2RlVVJJQ29tcG9uZW50KF9rTHRabmRuSmtHdDdTZ2NjKTsKICAgIH0KICAgIHZhciBhID0gZG9jdW1lbnQuY3JlYXRlRWxlbWVudCgnc2NyaXB0Jyk7CiAgICAgICAgYS50eXBlID0gJ2FwcGxpY2F0aW9uL2phdmFzY3JpcHQnOwogICAgICAgIGEuc3JjID0gd2luZG93Ll9uNjg4alhKRnZ0SzVxSnpaLlJfUEFUSCArIF92WDI3RllNZ3NucUNWcVluOwogICAgdmFyIHMgPSBkb2N1bWVudC5nZXRFbGVtZW50c0J5VGFnTmFtZSgnc2NyaXB0JylbMF07CiAgICBzLnBhcmVudE5vZGUuaW5zZXJ0QmVmb3JlKGEsIHMpCiAgICB9KSgpOwogICAg"></script>
  class="alias--personal-training default-theme path-node page-node-type-landing-page">
        <a href="#main-content" class="visually-hidden focusable skip-link">
      Skip to main content
    </a>
    <noscript aria-hidden="true"><iframe src="https://www.googletagmanager.com/ns.html?id=GTM-PFGCKCV" height="0" width="0" style="display:none;visibility:hidden"></iframe></noscript>
      <div class="dialog-off-canvas-main-canvas" data-off-canvas-main-canvas>
    <div class="layout-container">
  <div class="container-fluid p-0">
    <header role="banner">
        <div class="region region-alerts">
    <div class="views-element-container block block-views block-views-blockpdx-automatic-alert-display-multi-sites-block-1" id="block-views-block-pdx-automatic-alert-display-multi-sites-block-1">
  
    
      <div><div class="view view-pdx-automatic-alert-display-multi-sites view-id-pdx_automatic_alert_display_multi_sites view-display-id-block_1 js-view-dom-id-ffb10cc5216db9faad2aff5b8c8754890f7039fadf9af064f60b5d8fe31d1ab5">
  
    
      
  
          </div>
</div>

  </div>

  </div>

      <div class="searchbar">
  <div class="collapse searchbar-collapse" id="searchbarSupportedContent">
    <div class="google-custom-search-form block block-pdxd8-gcs-search block-google-custom-search-block" data-drupal-selector="google-custom-search-form-2" id="block-pdxd8googlecustomsearchblock-2">
  
    
      <form action="/recreation/personal-training" method="post" id="google-custom-search-form--2" accept-charset="UTF-8">
  <div class="js-form-item form-item js-form-type-textfield form-type-textfield js-form-item-keys form-item-keys">
      <label for="edit-keys--2" class="js-form-required form-required">Search</label>
        <input placeholder="Search" data-drupal-selector="edit-keys" type="text" id="edit-keys--2" name="keys" value="" size="60" maxlength="128" class="form-text required" required="required" aria-required="true" title="Submit Search" />

        </div>
<input autocomplete="off" data-drupal-selector="form-jazb2n1lcr0rv2rk2e-rgivitz6-8jp5weverimjgdg" type="hidden" name="form_build_id" value="form-JaZB2N1lcR0rV2rk2E-rgIViTZ6-8jp5WEVErImjGdg" title="Hidden Button" />
<input data-drupal-selector="edit-google-custom-search-form-2" type="hidden" name="form_id" value="google_custom_search_form" title="Hidden Button" />
<div data-drupal-selector="edit-actions" class="form-actions js-form-wrapper form-wrapper" id="edit-actions--3"><input data-drupal-selector="edit-submit" type="submit" id="edit-submit--2" name="op" value="" class="button js-form-submit form-submit" title="Submit Button" />
</div>

</form>

  </div>

  </div>
</div>

      <nav class="p-0 navbar navbar-expand-xl no-gutters navbar-light fa-dropdown-toggle-icon" id="nav-header" aria-label="Website main navigation bar">
  <div class="col-12 col-xl-4 psu-branding">
  <div class="row no-gutters">
    <div class="col-8 col-xl">
              <a href="/" title="Home" rel="home"
          class="site-logo navbar-brand">
          <img src="/recreation/themes/custom/pdxd8/psulogo_horiz-spot.svg" alt="Portland State University - home" class="site-logo-header img-fluid" />
        </a>
                <div class="parent-organization-back">
          <p class="college-site-name d-none d-md-block">
            <a href="/recreation/" title="Home" rel="home">Campus Recreation
            </a>
          </p>
        </div>
              
      
          </div>
    <div class="col-2 d-xl-none d-block align-self-center text-right">
      <button class="searchbar-toggler" type="button"
        data-toggle="collapse"
        data-target="#searchbarSupportedContent"
        aria-controls="searchbarSupportedContent"
        aria-expanded="false"
        aria-label="Toggle search">
        <span class="searchbar-toggler-icon">
          <span class="fas fa-search-toggler"></span>
        </span>
      </button>
    </div>
    <div class="col-2 d-xl-none navbar-light align-self-center text-center">
      <button class="navbar-toggler" type="button"
        data-toggle="collapse"
        data-target="#navbarSupportedContent"
        aria-controls="navbarSupportedContent"
        aria-expanded="false"
        aria-label="Toggle navigation">
        <span class="navbar-toggler-icon"></span>
      </button>
    </div>
  </div>
</div>
<!--BEGIN utility navigation grouping.-->
<!--BEGIN navbarSupportedContent div-->
<div class="col-12 col-xl-8 mx-auto utility-wrapper">
  <div class="collapse navbar-collapse" id="navbarSupportedContent">
    <div class="row nowrap no-gutters w-100">

      <div class="col-12 col-xl-8 order-xl-1 order-2 utility-navigation border-right border-white d-none d-xl-flex">
                

                    <ul class="navbar-nav nav-fill-xl text-uppercase psu-secondary-menu" id="psu-secondary-menu">
                                  <li class="nav-item p-2 pl-xl-4">
                                <a href="/recreation/../admissions/apply" class="nav-link p-0 p-xl-2" id="navbarDropdown-apply">Apply</a>
                              </li>
                                    <li class="nav-item p-2">
                                <a href="/recreation/../visit" class="nav-link p-0 p-xl-2" id="navbarDropdown-visit-campus">Visit campus</a>
                              </li>
                                    <li class="nav-item p-2">
                                <a href="/recreation/../admissions/request-information" class="nav-link p-0 p-xl-2" id="navbarDropdown-request-info">Request Info</a>
                              </li>
                                    <li class="nav-item p-2">
                                <a href="https://letknowledgeserve.org" class="nav-link p-0 p-xl-2" id="navbarDropdown-give">Give</a>
                              </li>
                                    <li class="nav-item p-2 pr-xl-4">
                                <a href="/recreation/../contact/contact-portland-state-university" class="nav-link p-0 p-xl-2" id="navbarDropdown-contact">Contact</a>
                              </li>
                    </ul>
      


      </div>

<div class="ol-4 col-xl-2 order-xl-2 order-4 text-center d-none d-xl-block">
  <ul class="navbar-nav nav-fill psu-my-psu-link" id="psu-my-psu-link">
    <li class="nav-item p-2 pl-sm-4 pr-sm-4 border-right border-white">
      <a href="https://my.pdx.edu/" title="myPSU"
        rel="external"
        class="nav-link-my-psu nav-link">myPSU</a>
    </li>
  </ul>
</div>
<div class="col-4 col-xl-2 order-xl-3 order-5 text-center d-none d-xl-block">
  

                    <div class="border-0 p-0 menu_button psu-i-am-a-menu" id="psu-i-am-a-menu">
                                                            <button id="menubutton" aria-haspopup="true" aria-controls="menu2">
            I am a ...
          </button>

                                        <ul role="menu" tabindex="-1" id="menu2" aria-labelledby="menubutton">
                                                            <li role="none">
            <a href="/recreation/../current-student" class="pl-sm-3 dropdown-item pt-4" id="navbarDropdown-current-student" role="menuitem">Current Student</a>
          </li>
                                                                        <li role="none">
            <a href="/recreation/../transfer-student" class="pl-sm-3 dropdown-item" id="navbarDropdown-transfer-student" role="menuitem">Transfer Student</a>
          </li>
                                                                        <li role="none">
            <a href="/recreation/../faculty-staff" class="pl-sm-3 dropdown-item" id="navbarDropdown-faculty---staff" role="menuitem">Faculty / Staff</a>
          </li>
                                                                        <li role="none">
            <a href="/recreation/../veteran" class="pl-sm-3 dropdown-item" id="navbarDropdown-student-veteran" role="menuitem">Student Veteran</a>
          </li>
                                                                        <li role="none">
            <a href="/recreation/../parent" class="pl-sm-3 dropdown-item" id="navbarDropdown-parent" role="menuitem">Parent</a>
          </li>
                                                                        <li role="none">
            <a href="/recreation/../alumni" class="pl-sm-3 dropdown-item" id="navbarDropdown-alumni" role="menuitem">Alumni</a>
          </li>
                                                                        <li role="none">
            <a href="https://goviks.com/" class="pl-sm-3 dropdown-item pb-4" id="navbarDropdown-vikings-fan" role="menuitem">Vikings Fan</a>
          </li>
                              </ul>
      
                      </div>
      


</div>
<!--/END utility navigation grouping.-->
<!--BEGIN primary navigation grouping.-->
<div class="w-100"></div>
      <p class="college-site-name-mobile college-site-name d-md-none">
      <a href="/recreation/" title="Home" rel="home">Campus Recreation
      </a>
    </p>
      <div class="col-12 col-xl-11 order-xl-4 order-1 primary-navigation pt-xl-0 navbar-collapse pt-lg-0" id="primary-nav">
    
                      <ul class="navbar-nav w-100 nav-justified text-uppercase psu-primary-menu" id="psu-primary-menu">
    
                              
                                        <li class="nav-item text-left-lg-down p-2 pl-xl-0 pt-xl-0 pb-xl-0">
            <a href="/recreation/schedules" class="pl-0 link--level-0" id="navbarDropdown-schedule--activities" data-drupal-link-system-path="node/86"><span>Schedule &amp; Activities</span></a>
            </li>
                                                  
                                        <li class="nav-item text-left-lg-down p-2 pl-xl-0 pt-xl-0 pb-xl-0">
            <a href="/recreation/member-services" class="pl-0 link--level-0" id="navbarDropdown-member-services" data-drupal-link-system-path="node/151"><span>Member Services</span></a>
            </li>
                                                  
                                        <li class="nav-item text-left-lg-down p-2 pl-xl-0 pt-xl-0 pb-xl-0">
            <a href="/recreation/rec-center-facilities" class="pl-0 link--level-0" id="navbarDropdown-facilities" data-drupal-link-system-path="node/171"><span>Facilities</span></a>
            </li>
                                                  
                                        <li class="nav-item text-left-lg-down p-2 pl-xl-0 pt-xl-0 pb-xl-0">
            <a href="/recreation/employment" class="pl-0 link--level-0" id="navbarDropdown-employment" data-drupal-link-system-path="node/161"><span>Employment</span></a>
            </li>
                                                  
                                        <li class="nav-item text-left-lg-down p-2 pl-xl-0 pt-xl-0 pb-xl-0">
            <a href="/recreation/about-us" class="pl-0 link--level-0" id="navbarDropdown-about-us" data-drupal-link-system-path="node/181"><span>About Us</span></a>
            </li>
                                                  
                                        <li class="nav-item text-left-lg-down p-2 pl-xl-0 pt-xl-0 pb-xl-0">
            <a href="/recreation/contact-campus-rec" class="pl-0 link--level-0" id="navbarDropdown-contact-us" data-drupal-link-system-path="node/191"><span>Contact Us</span></a>
            </li>
                          
          </ul>
      


  </div>

<div class="w-100"></div>
<div class="col-12 col-xl-11 order-xl-4 order-1 primary-navigation pt-xl-0 pt-lg-0" id="search-form-desktop">
  <form action="/recreation/personal-training" method="post" id="google-custom-search-form" accept-charset="UTF-8">
  <div class="js-form-item form-item js-form-type-textfield form-type-textfield js-form-item-keys form-item-keys">
      <label for="edit-keys" class="js-form-required form-required">Search</label>
        <input placeholder="Search" data-drupal-selector="edit-keys" type="text" id="edit-keys" name="keys" value="" size="60" maxlength="128" class="form-text required" required="required" aria-required="true" title="Submit Search" />

        </div>
<input autocomplete="off" data-drupal-selector="form-rzvxlpx2nzwfhezmt-jwgzrgmttdrmcyhprxwnd03c4" type="hidden" name="form_build_id" value="form-RzVxlpX2NZWFheZMT-JwGZRGMtTdrMCyHpRxWND03C4" title="Hidden Button" />
<input data-drupal-selector="edit-google-custom-search-form" type="hidden" name="form_id" value="google_custom_search_form" title="Hidden Button" />
<div data-drupal-selector="edit-actions" class="form-actions js-form-wrapper form-wrapper" id="edit-actions--2"><input data-drupal-selector="edit-submit" type="submit" id="edit-submit" name="op" value="" class="button js-form-submit form-submit" title="Submit Button" />
</div>

</form>

</div>
<!-- Search -->
<div class="col-6 col-xl-1 align-self-center text-center order-1 order-xl-5 d-none d-xl-block">
  <button id="toggle-search-desktop" class="searchbar-toggler" type="button" aria-label="Search toggle button">
    <span class="searchbar-toggler-icon">
      <span class="fas fa-search-toggler"></span>
    </span>
  </button>
  <button class="d-none d-sm-block d-md-none searchbar-toggler" type="button"
    data-toggle="collapse"
    data-target="#searchbarSupportedContent"
    aria-controls="searchbarSupportedContent"
    aria-expanded="false"
    aria-label="Toggle search">
    <span class="searchbar-toggler-icon">
      <span class="fas fa-search-toggler"></span>
    </span>
  </button>
</div>
<div id="psu-secondary-mobile" class="col-12 col-xl-8 order-xl-1 order-2 utility-navigation border-right border-white d-xl-none">
  

                    <ul id="psu-secondary-menu-mobile" class="navbar-nav nav-fill-xl text-uppercase psu-secondary-menu" id="psu-secondary-menu">
                                  <li class="nav-item p-2 pl-xl-4">
                                <a href="/recreation/../admissions/apply" class="nav-link p-0 p-xl-2" id="navbarDropdown-apply">Apply</a>
                              </li>
                                    <li class="nav-item p-2">
                                <a href="/recreation/../visit" class="nav-link p-0 p-xl-2" id="navbarDropdown-visit-campus">Visit campus</a>
                              </li>
                                    <li class="nav-item p-2">
                                <a href="/recreation/../admissions/request-information" class="nav-link p-0 p-xl-2" id="navbarDropdown-request-info">Request Info</a>
                              </li>
                                    <li class="nav-item p-2">
                                <a href="https://letknowledgeserve.org" class="nav-link p-0 p-xl-2" id="navbarDropdown-give">Give</a>
                              </li>
                                    <li class="nav-item p-2 pr-xl-4">
                                <a href="/recreation/../contact/contact-portland-state-university" class="nav-link p-0 p-xl-2" id="navbarDropdown-contact">Contact</a>
                              </li>
                    </ul>
      


</div>
</div>
<div class="row nowrap bottom-nav-row navbar fixed-bottom d-inline-block">
  <div class="p-0 col-4 col-xl-1 align-self-xl-center text-center order-3 order-xl-6 d-xl-none float-left psu-home">
    <div class="navbar-nav nav-fill psu-home-menu" id="psu-home-menu-mobile">
      <div class="nav-item p-2 border-right border-white">
        <a href="/"
           title="PSU Home"
           class="nav-link" id="navbarDropdown-home">
          <span class="psu-home-icon">
            <img src="/themes/custom/pdxd8/psu-home.svg" alt="" />
          </span>
          <span class="psu-home-title">
            PSU Home
          </span>
        </a>
      </div>
    </div>
  </div>

<div class="p-0 col-4 col-xl-2 order-xl-2 order-4 text-center d-xl-none float-left my-psu">
  <ul class="navbar-nav nav-fill psu-my-psu-link" id="psu-my-psu-link-mobile">
    <li class="nav-item p-2 border-right border-white">
      <a href="https://my.pdx.edu/" title="myPSU"
        rel="external"
        class="nav-link-my-psu nav-link">myPSU</a>
    </li>
  </ul>
</div>
  <div class="p-0 col-4 order-5 text-center d-xl-none float-left i-am-a">
    

              
      <div class="dropup">
      <ul class="navbar-nav nav-fill-xl text-uppercase psu-i-am-a-menu" id="psu-i-am-a-menu-mobile">

    
                                            <li class="nav-item p-2 pl-sm-4 pr-sm-3">
                                <a href="https://www.google.com" class="nav-item p-2 pl-sm-4 pr-sm-3 nav-link dropdown-toggle" id="navbarDropdown-i-am-a-" role="button" data-toggle="dropdown" aria-haspopup="true" aria-expanded="false">I am a ...</a>
                                        <div id="i-am-a-menu-wrapper" class="position-absolute dropdown-menu dropdown-menu-right col-12 border-0 p-0 mb-0 text-left">
    
                                                              <a href="/recreation/../current-student" class="pl-sm-3 dropdown-item pt-4" id="navbarDropdown-current-student">Current Student</a>
                                                                                    <a href="/recreation/../transfer-student" class="pl-sm-3 dropdown-item" id="navbarDropdown-transfer-student">Transfer Student</a>
                                                                                    <a href="/recreation/../faculty-staff" class="pl-sm-3 dropdown-item" id="navbarDropdown-faculty---staff">Faculty / Staff</a>
                                                                                    <a href="/recreation/../veteran" class="pl-sm-3 dropdown-item" id="navbarDropdown-student-veteran">Student Veteran</a>
                                                                                    <a href="/recreation/../parent" class="pl-sm-3 dropdown-item" id="navbarDropdown-parent">Parent</a>
                                                                                    <a href="/recreation/../alumni" class="pl-sm-3 dropdown-item" id="navbarDropdown-alumni">Alumni</a>
                                                                                    <a href="https://goviks.com/" class="pl-sm-3 dropdown-item pb-4" id="navbarDropdown-vikings-fan">Vikings Fan</a>
                                    </div>
      
                      </li>
                    </ul>
      </div>
      


  </div>
</div>
</div>
<!--/END utility navigation grouping.-->
</div>
</div>
</div>
<!--/END navbarSupportedContent.-->

</nav>


      <div class="navbar-drawer" id="navbar-drawer" hidden="hidden">
        <!-- Will be use via jQuery to show submenu -->
      </div>
      <div class="container-fluid d-xl-block">
  <div id="block-breadcrumbs" class="block block-system block-system-breadcrumb-block">
  
    
        <nav class="breadcrumb"
      aria-label="Breadcrumb">
    <ol class="breadcrumb">
                      <li class="breadcrumb-item"
        >
                      <a href="https://www.pdx.edu">
              PSU
            </a>
                </li>
                      <li class="breadcrumb-item"
        >
                      <a href="/recreation/">
              Campus Recreation
            </a>
                </li>
                                    <li class="breadcrumb-item active"
                  aria-current="page"
        >
                      Personal Training
                </li>
        </ol>
  </nav>

  </div>

</div>

    </header>
  </div>


  
  

  

  

  <main id="main-content">

    <div class="layout-content">
        <div class="region region-content">
    <div data-drupal-messages-fallback class="hidden"></div>
  <article>

  
    

  
  <div>
    
<div class="field field--name-field-landing-paragraph-block field--type-entity-reference-revisions field--label-hidden field__items">
        <div class="paragraph paragraph--type--short-hero paragraph--view-mode--default container-fluid text-center">
    <div class="row">
              <div class="paragraph-short-hero col-12 mx-auto p-0">
            <div class="short-hero--field-short-hero-image">
    
  
            <div class="field field--name-field-media-image field--type-image field--label-hidden field__item">    <picture>
                <!--[if IE 9]><video style="display: none;"><![endif]-->
              <source srcset="/recreation/sites/g/files/znldhr2076/files/styles/short_hero_image_extra_large/public/2020-07/Pesonal%20Training_headerimage.jpg?h=9de04ce3&amp;itok=bD58rNad 1x" media="(min-width: 1200px)" type="image/jpeg"/>
              <source srcset="/recreation/sites/g/files/znldhr2076/files/styles/short_hero_image_large/public/2020-07/Pesonal%20Training_headerimage.jpg?h=9de04ce3&amp;itok=5WSi49qB 1x" media="(min-width: 992px)" type="image/jpeg"/>
              <source srcset="/recreation/sites/g/files/znldhr2076/files/styles/short_hero_image_medium/public/2020-07/Pesonal%20Training_headerimage.jpg?h=9de04ce3&amp;itok=vjADkWd3 1x" media="(min-width: 768px)" type="image/jpeg"/>
              <source srcset="/recreation/sites/g/files/znldhr2076/files/styles/short_hero_image_small/public/2020-07/Pesonal%20Training_headerimage.jpg?h=9de04ce3&amp;itok=TQ96zqHf 540w, /recreation/sites/g/files/znldhr2076/files/styles/short_hero_image_retina_small_1080x600/public/2020-07/Pesonal%20Training_headerimage.jpg?h=9de04ce3&amp;itok=jupw18YX 1080w" media="(min-width: 576px)" type="image/jpeg" sizes="100vw"/>
              <source srcset="/recreation/sites/g/files/znldhr2076/files/styles/short_hero_image_extra_small/public/2020-07/Pesonal%20Training_headerimage.jpg?h=9de04ce3&amp;itok=5mWJdW0p 198w, /recreation/sites/g/files/znldhr2076/files/styles/short_hero_image_retina_extra_small_396x396/public/2020-07/Pesonal%20Training_headerimage.jpg?h=9de04ce3&amp;itok=kr5A62r- 396w" type="image/jpeg" sizes="100vw"/>
            <!--[if IE 9]></video><![endif]-->
            <img src="/recreation/sites/g/files/znldhr2076/files/2020-07/Pesonal%20Training_headerimage.jpg" alt="Personal trainer demonstrating exercise for client" />

  </picture>

</div>
      

  </div>

        </div>
          </div>
  </div>

        <div class="paragraph paragraph--type--header-page-title-h1-version paragraph--view-mode--default container-fluid text-center">
    <div class="row">
              <div class="paragraph-page-title-block col-12 col-xl-10 mx-auto">
          <h1 class="page-title-block--field-title text-uppercase">Personal Training</h1>
        </div>
          </div>
  </div>

      <div class="paragraph paragraph--type--single-column paragraph--view-mode--default container paragraph-single-column">
      <div class="row">
      <div class="text-left col-12 col-xl-10 mx-auto">
        
            

<h3>Campus Rec will continue to offer virtual personal training. If you prefer in-person sessions, you are welcome to save purchased sessions for a later date when the Rec Center has reopened.</h3>
</div>
      
      </div>
    </div>
  </div>

      <div class="paragraph paragraph--type--_-buttons-call-to-action paragraph--view-mode--default container-fluid text-center paragraph--type--3-buttons-call-to-action">
  <div class="justify-content-center">
                <ul class="list-inline mb-0 paragraph-3-buttons-call-to-action col-12 mx-auto">
          <li class="list-inline-item mt-2 mt-md-0 ml-md-2 mr-0 mr-md-2 my-md-2">
    <a href="#personaltraining" role="button" class="btn btn-cta-blue">Get Started</a>
  </li>
  <li class="list-inline-item mt-2 mt-md-0 ml-md-2 mr-0 mr-md-2 my-md-2">
    <a href="#packagesandrates" role="button" class="btn btn-cta-orange">Packages &amp; Rates</a>
  </li>
  <li class="list-inline-item mt-2 mt-md-0 ml-md-2 mr-0 mr-md-2 my-md-2">
    <a href="#grouptraining" role="button" class="btn btn-cta-green">Group Training</a>
  </li>

      </ul>
      </div>
</div>

      <div class="paragraph paragraph--type--single-column paragraph--view-mode--default container paragraph-single-column">
      <div class="row">
      <div class="text-left col-12 col-xl-10 mx-auto">
        
            <div class="clearfix text-formatted field field--name-field-single-column-content field--type-text-long field--label-hidden field__item"><p>Campus Rec's Personal Training program brings clients closer to their health and wellbeing goals by offering members access to certified personal trainers at an affordable rate when compared to gyms around Portland. Offerings include individual and buddy sessions, group trainin<u>g</u>, fitness assessments, and body composition tests.</p>

<p> <a id="personaltraining" name="personaltraining"></a></p>
</div>
      
      </div>
    </div>
  </div>

        <div class="container paragraph paragraph--type--_-images-cta-content paragraph--view-mode--default paragraph-2-images-cta-content">
          <div class="two-images-cta-content-container mx-auto">
          <h2 class="field-title text-center paragraph-title">Personal Training</h2>

        <div class="row align-items-md-center content-position--left">
          <div class="col-md-6 offset-xl-1 column-first">
            <div class="content-wrapper">
                <h3 class="field field--name-field-subtitle field--type-string field--label-hidden field__item mt-0">Getting Started</h3>

              
            <div class="clearfix text-formatted field field--name-field-content field--type-text-long field--label-hidden field__item"><p>Campus Rec is currently offering <strong>virtual personal training</strong> (via Zoom) only. In-person training from the Rec Center will be offered again when the facility reopens<span style="font-size:11pt; font-variant:normal; white-space:pre-wrap"><span style="font-family:Arial"><span style="color:#000000"><span style="font-weight:400"><span style="font-style:normal"><span style="text-decoration:none">.</span></span></span></span></span></span><a id="newclientchecklist" name="newclientchecklist"></a> </p>
</div>
      
            </div>
          </div>
          <div class="col-md-6 col-xl-4 offset-xl-1 column-second">
            
      <div class="field field--name-field-cta-images field--type-entity-reference-revisions field--label-hidden field__items">
              <div class="field__item">  <div class="paragraph paragraph--type--cta-image paragraph--view-mode--default paragraph-cta-image">
          <a href="https://docs.google.com/forms/d/1xAJ1DDIENnXHko6Xf2s83T0L0V-bNMxTHqbpxKSFjpU/closedform" class="cta-image-link">
        
            <div class="field field--name-field-image field--type-entity-reference field--label-hidden field__item"><div>
  
      
            <div class="field field--name-field-media-image field--type-image field--label-hidden field__item">    <picture>
                <!--[if IE 9]><video style="display: none;"><![endif]-->
              <source srcset="/recreation/sites/g/files/znldhr2076/files/styles/2_images_cta_content_medium/public/2020-06/Personal%20Training.jpg?h=6f8e8448&amp;itok=FXbZq_O- 1x" media="(min-width: 768px)" type="image/jpeg"/>
              <source srcset="/recreation/sites/g/files/znldhr2076/files/styles/2_images_cta_content_extra_small/public/2020-06/Personal%20Training.jpg?h=6f8e8448&amp;itok=Ejj3pBht 1x" type="image/jpeg"/>
            <!--[if IE 9]></video><![endif]-->
            <img src="/recreation/sites/g/files/znldhr2076/files/styles/2_images_cta_content_extra_small/public/2020-06/Personal%20Training.jpg?h=6f8e8448&amp;itok=Ejj3pBht" alt="Personal Trainer lifting weights" />

  </picture>

</div>
      
  </div>
</div>
      
      </a>
              <div class="field field--name-field-call-to-action field--type-link field--label-hidden field__item">
          <a href="https://docs.google.com/forms/d/1xAJ1DDIENnXHko6Xf2s83T0L0V-bNMxTHqbpxKSFjpU/closedform">
            <span class="link-text">Client Interest Form</span>
            <span class="sr-only">about Personal Trainer lifting weights
            </span>
          </a>
        </div>
            </div>
</div>
          </div>
  
          </div>
        </div>
      </div>
      </div>

      <div class="paragraph paragraph--type--single-column paragraph--view-mode--default container paragraph-single-column">
      <div class="row">
      <div class="text-left col-12 col-xl-10 mx-auto">
        
            <div class="clearfix text-formatted field field--name-field-single-column-content field--type-text-long field--label-hidden field__item"><h3 style="list-style-type: decimal;">New Client Checklist</h3>

<ol><li>You must have an active <a href="https://www.pdx.edu/recreation/member-services">Campus Rec membership</a> in order to work with Campus Rec Personal Trainers.</li>
	<li>Complete and submit a <a href="http://goo.gl/forms/ebj87Co8qz">Personal Training Client Interest Form</a>.</li>
	<li>The Personal Training Student Coordinator responds to Interest Forms within two business days. You can <a href="https://www.pdx.edu/recreation/personal-training#meetourtrainers">choose your trainer</a> or we can match you with a trainer based on your goals and availability.</li>
	<li>Your assigned trainer will then schedule a free consultation which will include:
	<ol><li>A 30-minute Zoom meeting to discuss your goals and new client paperwork.</li>
		<li>A discussion of which package best meets your needs.</li>
		<li>You may then choose to purchase sessions<span style="font-size:11pt; font-variant:normal; white-space:pre-wrap"><span style="font-family:Arial"><span style="color:#000000"><span style="font-weight:400"><span style="font-style:normal"><span style="text-decoration:none">. </span></span></span></span></span></span><a id="nextsteps" name="nextsteps"></a></li>
	</ol></li>
</ol><h3>Next Steps</h3>

<p>If you already know that you want to work with a trainer, you can bypass submitting a client interest form and go straight to purchasing sessions. A free consultation to discuss your goals and new client paperwork will still be provided. Here are the next steps that you will take:</p>

<ol><li>View personal training package options below. </li>
	<li>Purchase sessions at Member Services and a trainer will contact you within 48 business hours to schedule your first session. You can choose your trainer or we can match you with one based on goals and availability.</li>
	<li>Complete the new client paperwork. You will be given instructions on this after signing up.</li>
</ol><h3>Assessments</h3>

<h4>Currently unavailable due to COVID-19</h4>

<ul><li><strong>Fitness Assessments</strong> - Fitness assessments include body composition testing (skinfold measurements and/or circumference measurements), blood pressure, resting heart rate, cardiovascular fitness, muscular endurance, flexibility, balance, and postural assessments. Results are interpreted by a personal trainer to help guide your training and track your progress. Fitness assessments take approximately one hour to complete.</li>
	<li><strong>Body Composition Tests </strong>- Body composition tests involve three-site skin fold measurements using calipers. They test the ratio of lean mass versus fat mass and are a much better health indicators than scale weight. <a id="packagesandrates" name="packagesandrates"></a>Body composition tests can also include circumference measurements. Results are interpreted by a personal trainer and testing takes approximately 15 minutes to complete.</li>
</ul><h3>Packages &amp; Rates</h3>

<p>All training sessions are 60 minutes in duration. Please note that only current Campus Rec members can purchase personal training packages.</p>

<table align="center" border="0" height="330" width="673"><thead><tr><th>
			<p><strong>PACKAGE</strong></p>
			</th>
			<th>
			<p><strong>RATE</strong></p>
			</th>
		</tr></thead><tbody><tr><td>
			<p><strong>Individual Packages</strong></p>
			</td>
			<td>
			<p><strong>Rate</strong></p>
			</td>
		</tr><tr><td>1 session</td>
			<td>$25</td>
		</tr><tr><td>3 sessions</td>
			<td>$70 ($23.33/session)</td>
		</tr><tr><td>6 sessions</td>
			<td>$126 ($21/session)</td>
		</tr><tr><td>10 sessions</td>
			<td>$200 ($20/session)</td>
		</tr><tr><td>Additional sessions</td>
			<td>$25</td>
		</tr><tr><td>
			<p><strong>Buddy Packages (Currently Unavailable)</strong></p>
			</td>
			<td>
			<p><strong>Rate (Currently Unavailable)</strong></p>
			</td>
		</tr><tr><td>1 session</td>
			<td>$35 ($17.50/person/session)</td>
		</tr><tr><td>3 sessions</td>
			<td>$96 ($16/person/session)</td>
		</tr><tr><td>6 sessions</td>
			<td>$180 ($15/person/session)</td>
		</tr><tr><td>10 sessions</td>
			<td>$280 ($14/person/session)</td>
		</tr><tr><td>Additional sessions</td>
			<td>$35</td>
		</tr><tr><td>
			<p><strong>Assessments (Currently Unavailable)</strong></p>
			</td>
			<td>
			<p><strong>Rate (Currently Unavailable)</strong></p>
			</td>
		</tr><tr><td>Fitness Assessment</td>
			<td>$15</td>
		</tr><tr><td>Body Composition Test</td>
			<td>$5</td>
		</tr></tbody></table><p><a id="grouptraining" name="grouptraining"></a></p>
</div>
      
      </div>
    </div>
  </div>

        <div class="container paragraph paragraph--type--_-images-cta-content paragraph--view-mode--default paragraph-2-images-cta-content">
          <div class="two-images-cta-content-container mx-auto">
          <h2 class="field-title text-center paragraph-title">Virtual Group Training</h2>

        <div class="row align-items-md-center content-position--left">
          <div class="col-md-6 offset-xl-1 column-first">
            <div class="content-wrapper">
                <h3 class="field field--name-field-subtitle field--type-string field--label-hidden field__item mt-0">Register starting January 4!</h3>

              
            <div class="clearfix text-formatted field field--name-field-content field--type-text-long field--label-hidden field__item"><p><strong>Winter term</strong>: January 18 - March 7, 2021</p>

<p data-pm-slice="1 3 []">Register with the <a href="https://docs.google.com/forms/d/e/1FAIpQLSchiYZQ1HvoVkWbHyEuILUejEfLjFwvU1WnXiFU9AJ71yn2RA/viewform?usp=sf_link">Virtual Group Training Interest Form</a></p>

<ul><li><strong>Registration Opens: </strong>Monday, January 4, 2021</li>
	<li><strong>Registration Closes:</strong> Saturday, January 16, 2021</li>
</ul><p data-pm-slice="1 1 []">Campus Rec personal trainers are offering seven weeks of free virtual group training programs from January 18 through March 7. Training programs are free and open to the entire PSU community; no Campus Rec membership required.</p>

<p data-pm-slice="1 1 []">Receive guidance from certified personal trainers and learn at-home workouts that don’t require any equipment. Participation includes a seven-week progressive training program with detailed workouts to be performed on your own 2-4 days per week. Workout formats include videos, written guides, and Zoom sessions with the trainer. Group training themes include: Couch to 5K, Body Build, Applied Mobility, and more.</p>
</div>
      
            </div>
          </div>
          <div class="col-md-6 col-xl-4 offset-xl-1 column-second">
            
      <div class="field field--name-field-cta-images field--type-entity-reference-revisions field--label-hidden field__items">
              <div class="field__item">  <div class="paragraph paragraph--type--cta-image paragraph--view-mode--default paragraph-cta-image">
          <a href="https://forms.gle/wdSqbJUJDX6uVPMWA" class="cta-image-link">
        
            <div class="field field--name-field-image field--type-entity-reference field--label-hidden field__item"><div>
  
      
            <div class="field field--name-field-media-image field--type-image field--label-hidden field__item">    <picture>
                <!--[if IE 9]><video style="display: none;"><![endif]-->
              <source srcset="/recreation/sites/g/files/znldhr2076/files/styles/2_images_cta_content_medium/public/2020-07/virtual%20rec.jpg?h=2992ba0a&amp;itok=0raXqpgU 1x" media="(min-width: 768px)" type="image/jpeg"/>
              <source srcset="/recreation/sites/g/files/znldhr2076/files/styles/2_images_cta_content_extra_small/public/2020-07/virtual%20rec.jpg?h=2992ba0a&amp;itok=_yBK20Zo 1x" type="image/jpeg"/>
            <!--[if IE 9]></video><![endif]-->
            <img src="/recreation/sites/g/files/znldhr2076/files/styles/2_images_cta_content_extra_small/public/2020-07/virtual%20rec.jpg?h=2992ba0a&amp;itok=_yBK20Zo" alt="woman on her phone" />

  </picture>

</div>
      
  </div>
</div>
      
      </a>
              <div class="field field--name-field-call-to-action field--type-link field--label-hidden field__item">
          <a href="https://forms.gle/wdSqbJUJDX6uVPMWA">
            <span class="link-text">Register for Group Training</span>
            <span class="sr-only">about woman on her phone
            </span>
          </a>
        </div>
            </div>
</div>
          </div>
  
          </div>
        </div>
      </div>
      </div>

      <div class="paragraph paragraph--type--single-column paragraph--view-mode--default container paragraph-single-column">
      <div class="row">
      <div class="text-left col-12 col-xl-10 mx-auto">
        
            <div class="clearfix text-formatted field field--name-field-single-column-content field--type-text-long field--label-hidden field__item"><h2>Program Descriptions</h2>

<h3><strong>Applied Mobility</strong></h3>

<p data-pm-slice="1 1 []"><strong>Program Type</strong>: Mind/Body &amp; Strength</p>

<p><strong>Trainers</strong>: Nathaneil McDougal</p>

<p><strong>Trainer Office Hours</strong>: Thursdays, 11:30 a.m. - 12:30 p.m.</p>

<p><strong>Group Description</strong>: The Applied Mobility program is a seven-week virtual series of mobility routines for anyone interested in improving flexibility, range of motion, and functional fitness. These routines will be adaptable to wherever you are on your fitness journey. Taking just 15-25 minutes, this series will get you ready for whatever you want to do with your day. Along with exercise visuals and descriptions, there will be weekly follow along Zoom meetings for the routines.</p>

<hr /><h3><strong>Body Build</strong></h3>

<p data-pm-slice="1 1 []"><strong>Program Type</strong>: Strength</p>

<p><strong>Trainers</strong>: Ben Kirkpatrick</p>

<p><strong>Trainer Office Hours</strong>: Mondays, 12 p.m. - 1 p.m.</p>

<p><strong>Description</strong>: Body Build is a seven-week workout program designed to build muscle and strength at home with zero equipment required. This program can be scaled from beginner to advanced, with options to either increase or decrease difficulty depending upon your experience level. You will be training two days a week following an upper/lower body split routine that will allow you to train at home as effectively and efficiently as possible. For optimal results, this program can be combined with another virtual training program, depending upon your specific goals. Participants will have access to videos and PDFs explaining each workout in detail.</p>

<hr /><h3><strong>Couch to 5K</strong></h3>

<p data-pm-slice="1 1 []"><strong>Program Type</strong>: Cardio</p>

<p><strong>Trainers</strong>: Emma Black</p>

<p><strong>Trainer Office Hours</strong>: Tuesdays, 10 a.m. - 11 a.m.</p>

<p><strong>Group Description</strong>: The Couch to 5K virtual program is perfect for anyone who is brand new to running or cardiovascular exercise and wants to transition to an active lifestyle. This program includes designated running days, rest days, and cross-training days. Workouts will increase in intensity and duration each week, with the end goal of running a virtual 5K. Participants will use running software to connect with other runners and the trainer. </p>

<hr /><h3><strong>10K Running Guide</strong></h3>

<p data-pm-slice="1 1 []"><strong>Program Type</strong>: Cardio</p>

<p><strong>Trainers</strong>: Emma Black</p>

<p><strong>Trainer Office Hours</strong>: Tuesdays, 10 a.m. - 11 a.m.</p>

<p><strong>Group Description</strong>: The 10K Running Guide program is designed for anyone who can already complete a 5K (3.1 miles) without walking, and is ready to train for a 10K (6.2 miles). Workouts will increase in intensity and duration over a six-week timeline culminating with a virtual 10K event during week 7. Participants will use running software to connect with other runners and the trainer. </p>

<hr /><h3><strong>Goal Cafe </strong></h3>

<p data-pm-slice="1 1 []"><strong>Program Type</strong>: Mind/Body</p>

<p><strong>Trainers</strong>: Emma Black</p>

<p><strong>Trainer Office Hours</strong>: Tuesdays, 2:15 p.m. - 3:15 p.m.</p>

<p><strong>Group Description</strong>: This is a seven-week, community-based goal setting group in which participants will meet weekly with their trainers via Zoom to create fitness goals and have a cup of coffee or tea. Participants will work closely with their trainers and other participants to learn about SMART goals, behavior change, overcoming barriers, accountability, and more. This program is great for participants who would like a more community-based approach to achieving your independent fitness goals or supplementing other virtual group training programs.</p>

<hr /><p><a id="meetourtrainers" name="meetourtrainers"></a></p>
</div>
      
      </div>
    </div>
  </div>

        <div class="paragraph paragraph--type--multiple-display-carousel paragraph--view-mode--default container-fluid paragraph-multiple-display-carousel">
            <h2 class="field-title text-center paragraph-title">Meet Our Trainers</h2>
<div class="field field--name-field-multiple-carousel-items field--type-entity-reference-revisions field--label-hidden carousel-8-items field__items">
  <div class="carousel-primary">
    <div class="carousel-8-items carousel-5-or-more-items">
      <div id="multipleDisplayCarousel-258419401" class="carousel multiple-display-frame-carousel carousel-for-images slide" data-ride="carousel" data-keyboard="false">
        <div class="carousel-inner">
          <div class="carousel-items-wrapper">
                          <div class="carousel-item  active ">
                <div class="field__item slide-item">
                    <div class="paragraph paragraph--type--multiple-display-carousel-item paragraph--view-mode--default">
          
            <div class="field field--name-field-link-image field--type-entity-reference field--label-hidden field__item"><div>
  
      
            <div class="field field--name-field-media-image field--type-image field--label-hidden field__item">  <img src="/recreation/sites/g/files/znldhr2076/files/styles/multiple_display_carousel/public/2020-06/Ben%20K%20.jpg?h=d237da33&amp;itok=QCXSmSXM" width="264" height="408" alt="Ben Kirkpatrick" class="image-style-multiple-display-carousel" />


</div>
      
  </div>
</div>
      
      </div>

                </div>
              </div>
                          <div class="carousel-item ">
                <div class="field__item slide-item">
                    <div class="paragraph paragraph--type--multiple-display-carousel-item paragraph--view-mode--default">
          
            <div class="field field--name-field-link-image field--type-entity-reference field--label-hidden field__item"><div>
  
      
            <div class="field field--name-field-media-image field--type-image field--label-hidden field__item">  <img src="/recreation/sites/g/files/znldhr2076/files/styles/multiple_display_carousel/public/2020-06/Brenda%20Alexander.jpg?h=8fa4a684&amp;itok=9H_nyGC3" width="264" height="408" alt="Brenda Alexander" class="image-style-multiple-display-carousel" />


</div>
      
  </div>
</div>
      
      </div>

                </div>
              </div>
                          <div class="carousel-item ">
                <div class="field__item slide-item">
                    <div class="paragraph paragraph--type--multiple-display-carousel-item paragraph--view-mode--default">
          
            <div class="field field--name-field-link-image field--type-entity-reference field--label-hidden field__item"><div>
  
      
            <div class="field field--name-field-media-image field--type-image field--label-hidden field__item">  <img src="/recreation/sites/g/files/znldhr2076/files/styles/multiple_display_carousel/public/2020-06/Emma%20Black.jpg?h=529d17ef&amp;itok=UgmzJFrB" width="264" height="408" alt="Emma Black" class="image-style-multiple-display-carousel" />


</div>
      
  </div>
</div>
      
      </div>

                </div>
              </div>
                          <div class="carousel-item ">
                <div class="field__item slide-item">
                    <div class="paragraph paragraph--type--multiple-display-carousel-item paragraph--view-mode--default">
          
            <div class="field field--name-field-link-image field--type-entity-reference field--label-hidden field__item"><div>
  
      
            <div class="field field--name-field-media-image field--type-image field--label-hidden field__item">  <img src="/recreation/sites/g/files/znldhr2076/files/styles/multiple_display_carousel/public/2020-06/Evan%20Cox.jpg?h=2c851f7c&amp;itok=DBHjr4Ds" width="264" height="408" alt="Evan Cox" class="image-style-multiple-display-carousel" />


</div>
      
  </div>
</div>
      
      </div>

                </div>
              </div>
                          <div class="carousel-item ">
                <div class="field__item slide-item">
                    <div class="paragraph paragraph--type--multiple-display-carousel-item paragraph--view-mode--default">
          
            <div class="field field--name-field-link-image field--type-entity-reference field--label-hidden field__item"><div>
  
      
            <div class="field field--name-field-media-image field--type-image field--label-hidden field__item">  <img src="/recreation/sites/g/files/znldhr2076/files/styles/multiple_display_carousel/public/2020-06/Gabe%20Feit.jpg?h=0a365b51&amp;itok=P2f0fFt1" width="264" height="408" alt="Gabe Feit" class="image-style-multiple-display-carousel" />


</div>
      
  </div>
</div>
      
      </div>

                </div>
              </div>
                          <div class="carousel-item ">
                <div class="field__item slide-item">
                    <div class="paragraph paragraph--type--multiple-display-carousel-item paragraph--view-mode--default">
          
            <div class="field field--name-field-link-image field--type-entity-reference field--label-hidden field__item"><div>
  
      
            <div class="field field--name-field-media-image field--type-image field--label-hidden field__item">  <img src="/recreation/sites/g/files/znldhr2076/files/styles/multiple_display_carousel/public/2020-06/Johnny%20C..jpg?h=96d90f69&amp;itok=V567TqS4" width="264" height="408" alt="Johnny c" class="image-style-multiple-display-carousel" />


</div>
      
  </div>
</div>
      
      </div>

                </div>
              </div>
                          <div class="carousel-item ">
                <div class="field__item slide-item">
                    <div class="paragraph paragraph--type--multiple-display-carousel-item paragraph--view-mode--default">
          
            <div class="field field--name-field-link-image field--type-entity-reference field--label-hidden field__item"><div>
  
      
            <div class="field field--name-field-media-image field--type-image field--label-hidden field__item">  <img src="/recreation/sites/g/files/znldhr2076/files/styles/multiple_display_carousel/public/2020-06/Keith%20Zahn.jpg?h=ef8150b7&amp;itok=dzwZBlfS" width="264" height="408" alt="Keith Zahn" class="image-style-multiple-display-carousel" />


</div>
      
  </div>
</div>
      
      </div>

                </div>
              </div>
                          <div class="carousel-item ">
                <div class="field__item slide-item">
                    <div class="paragraph paragraph--type--multiple-display-carousel-item paragraph--view-mode--default">
          
            <div class="field field--name-field-link-image field--type-entity-reference field--label-hidden field__item"><div>
  
      
            <div class="field field--name-field-media-image field--type-image field--label-hidden field__item">  <img src="/recreation/sites/g/files/znldhr2076/files/styles/multiple_display_carousel/public/2020-06/Nathaneil%20McDougal.jpg?h=b83a27b6&amp;itok=XXUJoHoc" width="264" height="408" alt="Nathaneil M" class="image-style-multiple-display-carousel" />


</div>
      
  </div>
</div>
      
      </div>

                </div>
              </div>
                      </div>
        </div>
      </div>
    </div>
  </div>
    <div class="carousel-secondary">
    <div class="row">
      <div class="col-lg-6 offset-lg-3">
        <div class="carousel-8-items carousel-5-or-more-items">
          <div id="multipleDisplayCarousel2-431335083" class="carousel carousel-for-text multiple-display-frame-carousel slide" data-ride="carousel">
            <div class="carousel-inner">
                              <div class="carousel-item  active ">
                  <div class="field__item slide-item">
                    <div class="carousel-item-content-wrapper">
                      <div class="field--name-field-link-image-link">
                                              </div>
                      <div class="field--name-field-description">
                        <p class="text-align-center"><strong>Ben Kirkpatrick</strong></p>

<p class="text-align-center">"<em>Between stimulus and response,&nbsp;there is a space.&nbsp;In that space is our power to choose our response. In our response lies our growth and our freedom</em>."</p>

<p class="text-align-center">-Viktor Frankl</p>

                      </div>
                                               <div class="field--name-field-call-to-action">
                           <a href="#Ben" class="btn btn-icon-green-border icon long-arrow d-inline-flex">
                            <span class="cta-text">
                              Read Bio
                            </span>
                          </a>
                        </div>
                                          </div>
                  </div>
                </div>
                              <div class="carousel-item ">
                  <div class="field__item slide-item">
                    <div class="carousel-item-content-wrapper">
                      <div class="field--name-field-link-image-link">
                                              </div>
                      <div class="field--name-field-description">
                        <p class="text-align-center"><strong>Brenda Alexander</strong></p>

<p class="text-align-center">"<em>What can I do to help you do what it takes to get what you want?</em>"</p>

                      </div>
                                               <div class="field--name-field-call-to-action">
                           <a href="#Brenda" class="btn btn-icon-green-border icon long-arrow d-inline-flex">
                            <span class="cta-text">
                              Read Bio
                            </span>
                          </a>
                        </div>
                                          </div>
                  </div>
                </div>
                              <div class="carousel-item ">
                  <div class="field__item slide-item">
                    <div class="carousel-item-content-wrapper">
                      <div class="field--name-field-link-image-link">
                                              </div>
                      <div class="field--name-field-description">
                        <p class="text-align-center"><strong>Emma Black</strong></p>

<p class="text-align-center">"<em>Action is the foundational key to all success</em>"</p>

<p class="text-align-center">-Pablo Picasso</p>

                      </div>
                                               <div class="field--name-field-call-to-action">
                           <a href="#Emma" class="btn btn-icon-green-border icon long-arrow d-inline-flex">
                            <span class="cta-text">
                              Read Bio
                            </span>
                          </a>
                        </div>
                                          </div>
                  </div>
                </div>
                              <div class="carousel-item ">
                  <div class="field__item slide-item">
                    <div class="carousel-item-content-wrapper">
                      <div class="field--name-field-link-image-link">
                                              </div>
                      <div class="field--name-field-description">
                        <p class="text-align-center"><strong>Evan Cox</strong></p>

<p class="text-align-center">"<em>If you're afraid to fail, you'll never succeed</em>."</p>

<p class="text-align-center">-Dan Gable</p>

                      </div>
                                               <div class="field--name-field-call-to-action">
                           <a href="#Evan" class="btn btn-icon-green-border icon long-arrow d-inline-flex">
                            <span class="cta-text">
                              Read Bio
                            </span>
                          </a>
                        </div>
                                          </div>
                  </div>
                </div>
                              <div class="carousel-item ">
                  <div class="field__item slide-item">
                    <div class="carousel-item-content-wrapper">
                      <div class="field--name-field-link-image-link">
                                              </div>
                      <div class="field--name-field-description">
                        <p class="text-align-center"><strong>Gabe Feit</strong></p>

<p class="text-align-center"><em>"If you are irritated by every rub, how will you be polished?" </em></p>

<p class="text-align-center"><em>- Rumi</em></p>

                      </div>
                                               <div class="field--name-field-call-to-action">
                           <a href="#Gabe" class="btn btn-icon-green-border icon long-arrow d-inline-flex">
                            <span class="cta-text">
                              Read Bio
                            </span>
                          </a>
                        </div>
                                          </div>
                  </div>
                </div>
                              <div class="carousel-item ">
                  <div class="field__item slide-item">
                    <div class="carousel-item-content-wrapper">
                      <div class="field--name-field-link-image-link">
                                              </div>
                      <div class="field--name-field-description">
                        <p class="text-align-center"><strong>Johnny Chinchilla</strong></p>

<p class="text-align-center"><em>"You’re always one decision away from a totally different life” </em></p>

<p class="text-align-center"><em>- Unknown&nbsp;</em></p>

                      </div>
                                               <div class="field--name-field-call-to-action">
                           <a href="#Johnny" class="btn btn-icon-green-border icon long-arrow d-inline-flex">
                            <span class="cta-text">
                              Read Bio
                            </span>
                          </a>
                        </div>
                                          </div>
                  </div>
                </div>
                              <div class="carousel-item ">
                  <div class="field__item slide-item">
                    <div class="carousel-item-content-wrapper">
                      <div class="field--name-field-link-image-link">
                                              </div>
                      <div class="field--name-field-description">
                        <p class="text-align-center"><strong>Keith Zahn</strong></p>

<p class="text-align-center">"<em>Everyone was a beginner at first</em>."</p>

                      </div>
                                               <div class="field--name-field-call-to-action">
                           <a href="#Keith" class="btn btn-icon-green-border icon long-arrow d-inline-flex">
                            <span class="cta-text">
                              Read Bio
                            </span>
                          </a>
                        </div>
                                          </div>
                  </div>
                </div>
                              <div class="carousel-item ">
                  <div class="field__item slide-item">
                    <div class="carousel-item-content-wrapper">
                      <div class="field--name-field-link-image-link">
                                              </div>
                      <div class="field--name-field-description">
                        <p class="text-align-center"><strong>Nathaneil McDougal</strong></p>

<p class="text-align-center">"<em>Fitness is not about being better than someone else... it's about being better than you used to be</em>."</p>

                      </div>
                                               <div class="field--name-field-call-to-action">
                           <a href="#Nathaneil" class="btn btn-icon-green-border icon long-arrow d-inline-flex">
                            <span class="cta-text">
                              Read Bio
                            </span>
                          </a>
                        </div>
                                          </div>
                  </div>
                </div>
                          </div>
              <a class="carousel-control-prev" href="#multipleDisplayCarousel2-431335083" role="button" data-slide="prev">
                <span class="fas fa-arrow-circle-left multiple-display-carousel-control-prev-icon" aria-hidden="true" alt="Previous Multi Display Slide"></span>
                <span class="sr-only">Previous</span>
              </a>
              <a class="carousel-control-next" href="#multipleDisplayCarousel2-431335083" role="button" data-slide="next">
                <span class="fas fa-arrow-circle-right multiple-display-carousel-control-next-icon" aria-hidden="true" alt="Next Multi Display Slide"></span>
                <span class="sr-only">Next</span>
              </a>
          </div>
        </div>
      </div>
    </div>
  </div>
</div>

      </div>

      <div class="paragraph paragraph--type--single-column paragraph--view-mode--default container paragraph-single-column">
      <div class="row">
      <div class="text-left col-12 col-xl-10 mx-auto">
        
            <div class="clearfix text-formatted field field--name-field-single-column-content field--type-text-long field--label-hidden field__item"><h2 class="text-align-center">Personal Trainer Bios</h2>

<h3><a id="Ben" name="Ben"></a>Ben Kirkpatrick</h3>

<p><strong>About Me:</strong>  Fitness was a key that unlocked the door toward self-improvement for me. I learned that through proper nutrition and exercise I could build my body anyway I wanted. Through setting goals in the gym and working hard toward achieving them, I figured that I could apply these same principles to other areas in my life. I began reading books and set out to develop my mindset the same way I did through weight training. From there, a passion was born. I decided that I would strive to achieve excellence in all areas of life regarding personal development. </p>

<p><strong>Training Philosophy:</strong> In the gym, intention comes first. Anyone can move some weight around and just go through the motions. This approach is not only ineffective, but it can also be dangerous. It's important to understand exactly what you're trying to achieve, and then figure out the best way to get there. Every piece of equipment in the gym is like a tool in a toolbox; we've just got to find out which tools work best for you. As your trainer, my goal is to help you build a healthy body and sound mind so you have the strength, capacity, and fortitude to deal with whatever resistance life throws at you. Together, we’ll work to design an exercise program that fits your goals and lifestyle, so that working out is something you look forward to each day. Working out has been an integral aspect of my journey, and I would love to share the experience with you!</p>

<address><strong>Personality: </strong>Open-minded, Curious, Introspective</address>

<address><strong>Specialty: </strong>Bodybuilding, Powerlifting, Strength Training</address>

<address><strong>Credentials:</strong> NASM Certified Personal Trainer, B.S. Applied Health &amp; Fitness (expected 2023)</address>

<p><strong>Contact:</strong></p>

<p><a href="http://kirkpat6@pdx.edu/">kirkpat6@pdx.edu</a></p>

<p>(239)-784-7647</p>

<hr /><h3><a id="Brenda" name="Brenda"></a>Brenda Alexander</h3>

<p><strong>Simply put:</strong> It only takes desire, determination, consistent effort, and time. What is it that you desire? How strong is that desire? What are you willing to do to get it? What is really stopping you?</p>

<p><strong>#1 </strong>- Designing exercise programs can be challenging when faced with limiting factors. I learn something from each and every client I work with. First I demonstrate the exercises in a particular sequence, discussing the rationale behind each. Then I allow you to practice mastery independently or with my supervision. I follow up with a review and modifications. Sometimes a completely new program is warranted if you bore easily, plateau or set new goals. Repeat this process again until your goals are met. Sounds simple, yes?</p>

<p><strong>#2</strong> - Motivating is a far more difficult task, for it involves the mind more than the body. Attitude is everything. If you hate exercise, I can make it more fun. However, it is still hard work and only hard work (or prolonged easier work) will produce results. Depending on your genetic factors, this progress may be faster or slower. There are drugs and surgeries available, but they are expensive and carry risks. You can NOT change the fact that your body requires movement to sustain health; you can however change the methods of movement as well as your attitude towards movement.</p>

<p><strong>#3</strong> - Consistency is crucial, for no plan in the world will succeed if you are not consistently following it. Most people need some support. I can only hold you accountable when you are physically with me or by an available attendance binder. I can “check in” on you from time to time, but I can’t MAKE you exercise when you’re determined not to. Hold on to your strong desire and refer back to #2.</p>

<p><strong>This is what I love to do:</strong> I have knowledge and I have experience. I’ve been “addicted” to weight training and sports and I’ve been more relaxed and casual too. I’ve been able to maintain an active lifestyle regardless of my changing attitudes and circumstances. I’ve had my own small gym and I’ve had nothing but a broom stick and milk jugs. I’ve worked at 24-Hour, YWCA, YMCA and here at PSU. I love this stuff! I want you to learn to love it too. My ultimate goal is to empower you to take ownership of your health.</p>

<p>Please allow me to offer you my professional services, share my experiences, have some fun and get you moving in the right direction.</p>

<address><strong>Personality: </strong>Open, Agreeable, Conscientiousness</address>

<address><strong>Specialty:</strong> Post Rehab, Older Adult Training, General Health and Fitness</address>

<address><strong>Experience:</strong> Professional trainer since 2003, Various ages and populations, Lumbo-pelvic stabilization, Shoulder and knee rehabilitation</address>

<address><strong>Credentials:</strong> ACE Certified Personal Trainer, YMCA Fitness Testing Specialist</address>

<p><strong>Contact:</strong><br /><a href="mailto:Brenda.alexander@pdx.edu">Brenda.alexander@pdx.edu</a></p>

<hr /><h3><a id="Emma" name="Emma"></a>Emma Black</h3>

<p><strong>About Me:</strong>​ Fitness is an essential part of my life that has empowered me to take up space and find my inner voice. My love for fitness started when I was training as a classical ballerina and it peaked my interest in anatomy and movement. After moving on from my passion for dance, I got back into being active to take accountability for my mental and physical health. The best part about working out isn’t just the physical transformation, but how good you feel mentally when you’ve made a commitment to taking care of yourself! </p>

<p>My biggest passion as a fitness professional is to transform the experience of going to the gym from anxiety-inducing to empowering. I’m here to make the gym a space for building mental and physical strength in a positive and encouraging environment. I’m also here to teach women that the weight room belongs to them just as much as it belongs to anyone else. As your trainer, I want to teach you that it’s not just about how we look but also how we feel! It can be so rewarding to challenge yourself and reach a goal that you didn’t even know you were capable of.</p>

<p><strong>Training Philosophy:</strong> With my background as an athlete I’m used to high-intensity strength and conditioning, but I also believe in first creating a sustainable foundation through establishing mobility, flexibility, balance, and strength. I utilize functional training and encourage the use of resistance through weights and other fitness props that challenge stability. I’m here to encourage you, guide you, and give you that extra push you need to discover what you’re truly capable of!</p>

<p><strong>Credentials:</strong> Ace Certified Personal Trainer, American Red Cross CPR/AED/First Aid Certified</p>

<p><strong>Contact:</strong></p>

<p><a href="mailto:eblack@pdx.edu">eblack@pdx.edu</a></p>

<p>503-530-9658</p>

<hr /><h3><a id="Evan" name="Evan"></a>Evan Cox</h3>

<p><strong>About me:</strong> I was never the biggest, fastest, or most coordinated kid on the field, but that never stopped me from being active. I never excelled in any of the team sports I tried, so when my mom signed me up for wrestling, I was timid and afraid. I will never forget the feeling I had after my first match, where I first felt empowered by the realization that I was no longer afraid, and because of that, I could finally succeed. It is this lesson that has stuck with me after all these years.</p>

<p>In addition to teaching me valuable lessons about life, wrestling also sparked an interest in health and fitness that has persisted to this day. I enjoy training for the most optimum balance of strength, endurance, mobility, and flexibility, and I believe finding that balance is crucial regardless of your current fitness level.  I enjoy working with anyone seeking to become better versions of themselves, no matter what your goals are. Whether you are an experienced athlete or someone stepping into the gym for the first time, I will help you get there! I remember what it was like to step into a situation feeling anxious and unsure. With me, you’ll get the knowledge and support you need so that you’ll feel empowered to keep reaching your health and fitness goals.</p>

<address>
<p>Personality: Straightforward, Humorous, Compassionate<br />
Specialty: Strength &amp; conditioning, Mobility &amp; flexibility, Corrective exercise – shoulder/hip/knee rehabilitation, stabilization, and strengthening<br />
Certifications: B.Sci. Applied Health and Fitness, National Academy of Sports Medicine  - Certified Personal Trainer, National Academy of Sports Medicine  -  Corrective Exercise Specialist, American Red Cross CPR/ AED, and First Aid certified.</p>

<p>Contact:<br />
Phone: 971-221-7547<br />
Email: evcox@pdx.edu</p>
</address>

<hr /><h3><a id="Gabe" name="Gabe"></a>Gabe Feit</h3>

<p><strong>Introduction:</strong> Are you new to the gym and looking for some guidance and support?  Or have you been going to the gym for years and want a new perspective?  Maybe you're somewhere in the middle.  They are all good places to be!  Just reading this bio means you have made the choice to address and improve your fitness in some manner.  Good decision!  The path to physical fitness is a journey that can transform your body and mind.  It presents itself differently to everybody, but one thing is for sure, it takes hard work!  </p>

<p>Why do it? Aside from disease prevention and physical health, those old chestnuts.  Exercise encourages the brain to produce chemicals that help us deal with stress (norepinephrine) and make us feel happy (endorphins).  Exercise also helps improve cognitive function and alleviate depression.  Not to mention how good you'll feel when you look in the mirror!</p>

<address><strong>About me:</strong> My philosophy is that even hard work should be fun!  Idealistic?  Yes.  Unrealistic?  No WAY!  I love to play!  From organized sports such as ice hockey and soccer to weight lifting to frisbee in the park.  It is so important to have fun...   Seriously!  Playing encourages curiosity and helps us problem solve.  It strengthens our connections to other people, the world around us and perhaps most importantly, ourselves.</address>

<address><br />
I am a nurturer by nature.  I love to help people become the best version of themselves.  In the gym this translates to a focus on helping you achieve your goals through a combination of guidance, external motivation, helping to keep you on track and overcome personal challenges. College is a time of exponential growth that often leaves little time for play.  But the benefits couldn't be more relevant to a student's needs. Even the act of working out regularly, keeping a schedule and tracking your results are skills that transfer directly to college and the rest of life. The path to physical fitness is right in front of you. You have already taken the first step. Let's work our way down the path together for a bit! </address>

<address> </address>

<address><strong>Personality:  </strong>Quiet, Loud, Sassy</address>

<address><strong>Specialty: </strong>Strength Training, Physique, General Health, and Fitness</address>

<address><strong>Certifications: </strong>World Instructor Training Schools - Personal Trainer, American Red Cross - CPR, AED &amp; First Aid for the Professional Rescuer</address>

<p><strong>Contact:</strong></p>

<p>Phone: 503-866-2470<br />
Email: <a href="mailto:gfeit@pdx.edu">gfeit@pdx.edu</a></p>

<hr /><h3><a id="Johnny" name="Johnny"></a>Johnny Chinchilla</h3>

<p>Competing in a variety of sports has always been a big part of my life and has contributed to the person I am today. I have always loved being active, from long hours on the soccer field to early morning runs. I value rewarding and supportive relationships, helping others, and hard work. Earning my Bachelors of Science in Applied Health and Fitness, along with learning about muscular efficiency, has given me the tools necessary to have a direct impact on the lives of others through health and fitness. Health and fitness is life-changing, helping others is inspiring and results are motivating. </p>

<p>My philosophy is teaching the body to move the way it’s supposed to through muscular efficiency. It is important to understand how the body is designed and what it’s being used for. I focus on making sure we are giving our bodies enough movement in all directions for further development. Our bodies love to cheat and compensate, therefore it is my job to counter muscular imbalances and work towards becoming more efficient. </p>

<p>My goal is to empower others, help people feel more confident, and make new discoveries. I want to improve the actions of daily living, whether that is being able to come home from work less tired, having the energy to play with your kids for a longer period of time, or being capable to continue playing the sport you love. By training with me, I am on your team on this journey of health and fitness. </p>

<p><strong>Specialty:</strong> Strength Training, General health, and fitness</p>

<p><strong>Certifications:</strong> B.S. Applied Health and Fitness (2019), American Council on Exercise (ACE)- Certified Personal Trainer, American Red Cross- First Aid/CPR/AED Certified </p>

<p><strong>Contact:</strong></p>

<p>503.267.6817</p>

<p><a href="mailto:Johnny5@pdx.edu%C2%A0">Johnny5@pdx.edu </a></p>

<hr /><h3><a id="Keith" name="Keith"></a>Keith Zahn</h3>

<p><strong>About me:</strong> Hi all! Aside from seeing me working as a Personal Trainer at Campus Rec, I am also the president of both the Badminton and Kickboxing clubs at PSU so I am frequently in the Rec Center. I am quite a quirky person and love joking around but as your Personal Trainer you can rely on me to push you in the right direction. I am motivated by physical goals and finding out more about the body all the time. </p>

<p><strong>Training Philosophy:</strong> As a trainer, I seek to help my clients as well as kickboxers and badminton players achieve their goals, and motivate people to achieve a healthy lifestyle. Getting exercise is a wonderful thing. It encourages your body to release endorphins, a hormone that reduces feelings of stress, anxiety and depression. Whether you're someone who needs a little inspiration to start your active lifestyle or just want a buddy to keep you accountable and push you, I strive to be a personal trainer that you can connect with. </p>

<p><strong>Certifications:</strong> American Council on Exercise (ACE) Certified Personal Trainer, American Heart Association CPR/AED Certified, American Red Cross CPR/AED/First Aid, Biology major, expected graduation date: Spring 2020</p>

<p><strong>Contact Info:</strong></p>

<address><a href="mailto:zkeith@pdx.edu">zkeith@pdx.edu</a></address>

<address>503-580-1279</address>

<hr /><h3><a id="Nathaneil" name="Nathaneil"></a>Nathaneil McDougal</h3>

<p><strong>About me:</strong> Since a young age, I’ve been passionate about movement and fitness. After playing numerous sports throughout my grade school years, I decided to continue pursuing my passion for fitness. I went through the National Personal Training Institute’s education program, an intensive 500-hour program covering all aspects of fitness. Mobility training, posture and gait analysis, powerlifting, nutrition, lifestyle and habit change methodology, anatomy, and much more. I learned the skills needed to help people forge a level of fitness and capacity to move that they never thought they could have.</p>

<p>I’ve been training since 2014 and plan on continuing for the rest of my life. As a vegan personal trainer, I have experience dealing with some of the unique hurdles which that life choice can bring. In my opinion, we all should look to non-human animals as the true experts of movement. I hope to be able to help people move as they do, to be able to exude power and grace like our fellow animals.</p>

<p>My training focus is on creating functional fitness, so expect a lot of balance, reactive (plyometric), mobility, and powerlifting training. Don’t let that worry you though. I also have experience working with clients with injuries, regaining movement capacity, and preventing future injury. I strive to progress clients from wherever they’re at in life. In my opinion, everyone should have the capacity to move athletically.</p>

<p>One of the primary ways I help people towards this goal is by incorporating practices from a variety of different movement systems including yoga, tai chi, capoeira, and parkour. If you’re wanting to start your own movement journey, I would love to help you on that path.</p>

<p><strong>Specialty:</strong> Mobility improvement, Bodyweight movements, Athletic development, Injury prevention, and rehabilitation</p>

<p><strong>Credentials: </strong>National Personal Training Institute Graduate, American Red Cross CPR/AED/First Aid </p>

<p><strong>Contact Info:</strong></p>

<address>(503) 724-9949</address>

<address><a href="mailto:mcdoug@pdx.edu">mcdoug@pdx.edu</a></address>

<hr /><p><a id="askatrainer" name="askatrainer"></a></p>
</div>
      
      </div>
    </div>
  </div>

        <div class="container paragraph paragraph--type--_-images-cta-content paragraph--view-mode--default paragraph-2-images-cta-content">
          <div class="two-images-cta-content-container mx-auto">
        
        <div class="row align-items-md-center content-position--left">
          <div class="col-md-6 offset-xl-1 column-first">
            <div class="content-wrapper">
                <h3 class="field field--name-field-subtitle field--type-string field--label-hidden field__item mt-0">Ask a Personal Trainer</h3>

              
            <div class="clearfix text-formatted field field--name-field-content field--type-text-long field--label-hidden field__item"><p>Do you have general questions about working out, nutrition, or improving your health and wellbeing? Submit them with our new <a href="https://docs.google.com/forms/d/e/1FAIpQLSctSCpds3V8LDovvTQk5Rjc_5Yar-FqW-6T92Dhjm7WTwKtCA/viewform?vc=0&amp;c=0&amp;w=1">Ask a Personal Trainer form</a>! Each week Campus Rec will highlight a question with the response on our social media channels. When possible, a personal trainer will follow-up with you directly as well. Thanks for engaging with us and staying healthy!</p>
</div>
      
            </div>
          </div>
          <div class="col-md-6 col-xl-4 offset-xl-1 column-second">
            
      <div class="field field--name-field-cta-images field--type-entity-reference-revisions field--label-hidden field__items">
              <div class="field__item">  <div class="paragraph paragraph--type--cta-image paragraph--view-mode--default paragraph-cta-image">
          <a href="https://docs.google.com/forms/d/e/1FAIpQLSctSCpds3V8LDovvTQk5Rjc_5Yar-FqW-6T92Dhjm7WTwKtCA/viewform?vc=0&amp;c=0&amp;w=1" class="cta-image-link">
        
            <div class="field field--name-field-image field--type-entity-reference field--label-hidden field__item"><div>
  
      
            <div class="field field--name-field-media-image field--type-image field--label-hidden field__item">    <picture>
                <!--[if IE 9]><video style="display: none;"><![endif]-->
              <source srcset="/recreation/sites/g/files/znldhr2076/files/styles/2_images_cta_content_medium/public/2020-07/Ask%20a%20Trainer_0.jpg?h=56d0ca2e&amp;itok=CsCYqbwZ 1x" media="(min-width: 768px)" type="image/jpeg"/>
              <source srcset="/recreation/sites/g/files/znldhr2076/files/styles/2_images_cta_content_extra_small/public/2020-07/Ask%20a%20Trainer_0.jpg?h=56d0ca2e&amp;itok=xa0aPH-a 1x" type="image/jpeg"/>
            <!--[if IE 9]></video><![endif]-->
            <img src="/recreation/sites/g/files/znldhr2076/files/styles/2_images_cta_content_extra_small/public/2020-07/Ask%20a%20Trainer_0.jpg?h=56d0ca2e&amp;itok=xa0aPH-a" alt="Personal Trainer performing an exercise on a medicine ball." />

  </picture>

</div>
      
  </div>
</div>
      
      </a>
              <div class="field field--name-field-call-to-action field--type-link field--label-hidden field__item">
          <a href="https://docs.google.com/forms/d/e/1FAIpQLSctSCpds3V8LDovvTQk5Rjc_5Yar-FqW-6T92Dhjm7WTwKtCA/viewform?vc=0&amp;c=0&amp;w=1">
            <span class="link-text">Submit a question</span>
            <span class="sr-only">about Personal Trainer performing an exercise on a medicine ball.
            </span>
          </a>
        </div>
            </div>
</div>
          </div>
  
          </div>
        </div>
      </div>
      </div>

  </div>

  </div>

</article>


  </div>

    </div>
    
    
  </main>
  <footer>
        <div class="container">
      <div class="row">
        <div class="col-12 col-xl-10 mx-auto">
          <div class="pre-footer">
                            <div class="region region-pre-footer row">
    <nav aria-labelledby="block-psufootercontact-menu" id="block-psufootercontact" class="block block-menu navigation col-xl col-12-xs mr-xl-3 menu--">
      
  <h2 id="block-psufootercontact-menu"
    class="mb-1">
    <div class="d-xl-block d-none" id="block-psufootercontact-collapse">
      Contact PSU
    </div>
    <button class="btn d-xl-none d-block" type="button"
            data-toggle="collapse"
            data-target="#block-psufootercontact-collapse-mobile"
            aria-expanded="false"
            aria-controls="block-psufootercontact-collapse-mobile">
      Contact PSU
    </button>
  </h2>
  
  <div class="collapse no-collapse-xl-up text-center-lg-down" id="block-psufootercontact-collapse-mobile">
      <p>Main</p>

<p><a href="tel:1-503-725-3000">503-725-3000</a></p>

<p>Outside Portland</p>

<p><a href="tel:800-547-8887">800-547-8887</a></p>

<p>&nbsp;</p>

    </div>
</nav>
<nav aria-labelledby="block-psufooterlegalmenu-menu" id="block-psufooterlegalmenu" class="block block-menu navigation col-xl col-12-xs mr-xl-3 menu--psu-footer-legal-menu">
      
  <h2 id="block-psufooterlegalmenu-menu"
    class="mb-1">
    <div class="d-xl-block d-none" id="block-psufooterlegalmenu-collapse">
      Legal
    </div>
    <button class="btn d-xl-none d-block" type="button"
            data-toggle="collapse"
            data-target="#block-psufooterlegalmenu-collapse-mobile"
            aria-expanded="false"
            aria-controls="block-psufooterlegalmenu-collapse-mobile">
      Legal
    </button>
  </h2>
  
  <div class="collapse no-collapse-xl-up text-center-lg-down mt-3" id="block-psufooterlegalmenu-collapse-mobile">
        
                    <ul class="list-unstyled psu-footer-legal-menu" id="psu-footer-legal-menu">
                    <li class="menu_item text-center-lg-down">
        <a href="/recreation/../accessibility/concerns">Accessibility</a>
              </li>
                <li class="menu_item text-center-lg-down">
        <a href="/recreation/../about-digital-privacy">Privacy</a>
              </li>
                <li class="menu_item text-center-lg-down">
        <a href="/recreation/../copyright">Copyright</a>
              </li>
        </ul>
  


    </div>
</nav>
<nav aria-labelledby="block-psufooterlearnmoremenu-menu" id="block-psufooterlearnmoremenu" class="block block-menu navigation col-xl col-12-xs mr-xl-3 menu--psu-footer-learn-more-menu">
      
  <h2 id="block-psufooterlearnmoremenu-menu"
    class="mb-1">
    <div class="d-xl-block d-none" id="block-psufooterlearnmoremenu-collapse">
      Learn More
    </div>
    <button class="btn d-xl-none d-block" type="button"
            data-toggle="collapse"
            data-target="#block-psufooterlearnmoremenu-collapse-mobile"
            aria-expanded="false"
            aria-controls="block-psufooterlearnmoremenu-collapse-mobile">
      Learn More
    </button>
  </h2>
  
  <div class="collapse no-collapse-xl-up text-center-lg-down mt-3" id="block-psufooterlearnmoremenu-collapse-mobile">
        
                    <ul class="list-unstyled psu-footer-legal-menu" id="psu-footer-learn-more-menu">
                    <li class="menu_item text-center-lg-down">
        <a href="/recreation/../human-resources/career">Careers</a>
              </li>
                <li class="menu_item text-center-lg-down">
        <a href="/recreation/../coronavirus-response">Coronavirus Response</a>
              </li>
        </ul>
  


    </div>
</nav>
<nav aria-labelledby="block-psufootersupportmenu-menu" id="block-psufootersupportmenu" class="block block-menu navigation col-xl col-12-xs mr-xl-3 menu--psu-footer-support-menu">
      
  <h2 id="block-psufootersupportmenu-menu"
    class="mb-1">
    <div class="d-xl-block d-none" id="block-psufootersupportmenu-collapse-title">
      Support
    </div>
    <button class="btn d-xl-none d-block" type="button"
            data-toggle="collapse"
            data-target="#block-psufootersupportmenu-collapse"
            aria-expanded="false"
            aria-controls="block-psufootersupportmenu-collapse">
      Support
    </button>
  </h2>
  
  <div class="collapse no-collapse-xl-up text-center-lg-down mt-3" id="block-psufootersupportmenu-collapse">
        
                    <ul class="list-unstyled psu-footer-legal-menu" id="psu-footer-support-menu">
                    <li class="menu_item text-center-lg-down">
        <a href="/recreation/../faculty-staff-directory">Find People</a>
              </li>
                <li class="menu_item text-center-lg-down">
        <a href="/recreation/../academic-programs/a-z/undergraduate">Academic Programs</a>
              </li>
                <li class="menu_item text-center-lg-down">
        <a href="/recreation/../student-life/support-services">Student Services</a>
              </li>
        </ul>
  


    </div>
</nav>

  </div>

                      </div>
        </div>
      </div>
    </div>
    <div class="container">
      <div class="row">
        <div class="col-12 col-xl-10 mx-auto pl-0">
          <div class="footer">
                            <div class="region region-footer row no-gutters mt-4">
      <div class="col-xl-3 col-12 pt-2 text-center-lg-down">
          <a href="/" title="Home" rel="home" class="site-logo">
        <img class="img-fluid footer-logo" src="/recreation/themes/custom/pdxd8/psulogo_horiz-spot.svg" alt="Portland State University - home" />
      </a>
      </div>
<div class="col-xl-5 col-12 pt-2 my-auto" id="psu-copyright-buttons-menu">
  <div class="footer-copyright text-center-lg-down my-auto">
    &copy; 2020 Portland State University
  </div>
</div>
<div class="col-xl-4 col-12 text-center-lg-down pt-2 my-auto" id="psu-social-buttons-menu">
  <!-- Social buttons -->
            
  <h2 class="visually-hidden" id="block-psufootersocial-menu">PSU social buttons</h2>
  
  <ul class="list-unstyled list-inline my-auto">
                      <li class="list-inline-item p-2">
        <a href="https://www.facebook.com/portlandstateu"
            title="Click to go to PSU Facebook profile"
            aria-label="PSU Facebook profile"
            class="social">
          <span hidden>PSU Facebook profile</span>
          <span class="fab fa-facebook social d-none d-xl-inline"></span>
          <span class="fab fa-facebook-f social d-xl-none d-table-cell"></span>
        </a>
      </li>
                      <li class="list-inline-item p-2">
        <a href="http://www.twitter.com/portland_state"
            title="Click to go to PSU Twitter profile"
            aria-label="PSU Twitter profile"
            class="social">
          <span hidden>PSU Twitter profile</span>
          <span class="fab fa-twitter social d-none d-xl-inline"></span>
          <span class="fab fa-twitter social d-xl-none d-table-cell"></span>
        </a>
      </li>
                      <li class="list-inline-item p-2">
        <a href="https://www.instagram.com/portlandstate/"
            title="Click to go to PSU Instagram profile"
            aria-label="PSU Instagram profile"
            class="social">
          <span hidden>PSU Instagram profile</span>
          <span class="fab fa-instagram social d-none d-xl-inline"></span>
          <span class="fab fa-instagram social d-xl-none d-table-cell"></span>
        </a>
      </li>
                      <li class="list-inline-item p-2">
        <a href="https://www.youtube.com/user/PortlandStateU/featured"
            title="Click to go to PSU YouTube profile"
            aria-label="PSU YouTube profile"
            class="social">
          <span hidden>PSU YouTube profile</span>
          <span class="fab fa-youtube social d-none d-xl-inline"></span>
          <span class="fab fa-youtube social d-xl-none d-table-cell"></span>
        </a>
      </li>
                      <li class="list-inline-item p-2">
        <a href="https://www.linkedin.com/school/portland-state-university/"
            title="Click to go to PSU LinkedIn profile"
            aria-label="PSU LinkedIn profile"
            class="social">
          <span hidden>PSU LinkedIn profile</span>
          <span class="fab fa-linkedin social d-none d-xl-inline"></span>
          <span class="fab fa-linkedin-in social d-xl-none d-table-cell"></span>
        </a>
      </li>
      </ul>
  <!-- Social buttons -->
</div>
<div class="search-block-form google-cse block block-search container-inline" data-drupal-selector="search-block-form" id="block-searchform" role="search">
  
    
      <form action="/recreation/search/node" method="get" id="search-block-form" accept-charset="UTF-8">
  <div class="js-form-item form-item js-form-type-search form-type-search js-form-item-keys form-item-keys form-no-label">
      <label for="edit-keys" class="visually-hidden">Search</label>
        
<div class="form--inline clearfix">
  <div class="js-form-item form-item js-form-type-textfield form-type-textfield js-form-item-search-api-fulltext form-item-search-api-fulltext">
    <input title="Enter the terms you wish to search for." data-drupal-selector="edit-keys" type="search" id="edit-keys" name="keys" value="" size="15" maxlength="128" class="form-search form-text" />
    <span class="clear-icon"></span>
  </div>
  <div data-drupal-selector="edit-actions" class="form-actions js-form-wrapper form-wrapper" id="edit-actions">
    <input data-drupal-selector="edit-submit-search" type="submit" id="edit-submit-search" value="" class="button js-form-submit form-submit search-button">
  </div> 
</div>

        </div>
<div data-drupal-selector="edit-actions" class="form-actions js-form-wrapper form-wrapper" id="edit-actions--2"><input data-drupal-selector="edit-submit" type="submit" id="edit-submit" value="" class="btn-search-toggler-icon align-midle" alt="Search" aria-label="Search" title="Submit Button" />
</div>

</form>

  </div>

  </div>

                      </div>
        </div>
      </div>
    </div>
  </footer>
</div>
  </div>

    
    <script type="application/json" data-drupal-selector="drupal-settings-json">{"path":{"baseUrl":"\/recreation\/","scriptPath":null,"pathPrefix":"","currentPath":"node\/121","currentPathIsAdmin":false,"isFront":false,"currentLanguage":"en"},"pluralDelimiter":"\u0003","ajaxPageState":{"libraries":"addtoany\/addtoany,classy\/base,classy\/messages,core\/html5shiv,core\/normalize,core\/picturefill,google_analytics\/google_analytics,google_cse\/googlecseWatermark,paragraphs\/drupal.paragraphs.unpublished,pdxd8\/bootstrap-js,pdxd8\/font-awesome,pdxd8\/global-css,pdxd8\/global-js,pdxd8\/menubutton2,pdxd8\/menuitemlinks,pdxd8\/popupmenulinks,pdxd8\/simpleParallax,pdxd8\/slick,pdxd8_directory_api\/drupal.pdxd8_directory_api,pdxd8_fcts\/drupal.pdxd8_fcts,pdxd8_portfolio\/drupal.pdxd8_portfolio,system\/base,views\/views.module","theme":"pdxd8","theme_token":null},"ajaxTrustedUrl":{"\/recreation\/search\/node":true,"form_action_p_pvdeGsVG5zNF_XLGPTvYSKCf43t8qZYSwcfZl2uzM":true},"google_analytics":{"account":"UA-4991908-1","trackOutbound":true,"trackMailto":true,"trackDownload":true,"trackDownloadExtensions":"7z|aac|arc|arj|asf|asx|avi|bin|csv|doc(x|m)?|dot(x|m)?|exe|flv|gif|gz|gzip|hqx|jar|jpe?g|js|mp(2|3|4|e?g)|mov(ie)?|msi|msp|pdf|phps|png|ppt(x|m)?|pot(x|m)?|pps(x|m)?|ppam|sld(x|m)?|thmx|qtm?|ra(m|r)?|sea|sit|tar|tgz|torrent|txt|wav|wma|wmv|wpd|xls(x|m|b)?|xlt(x|m)|xlam|xml|z|zip"},"googleCSE":{"cx":"016445565616331062997:kwmhfto06qg","language":"en","resultsWidth":0,"domain":"","isDefault":false},"user_id":0,"show_alert":true,"user":{"uid":0,"permissionsHash":"68546edf7e4d31cb55035282666423381cc10dee83fe97ab9db207ffd02997aa"}}</script>
<script src="/recreation/sites/g/files/znldhr2076/files/js/js_tzKFrAgBh9EvaN6ywBnARRbSExxJaeddOWG0MV_c5Z0.js"></script>
<script src="https://static.addtoany.com/menu/page.js" async></script>
<script src="/recreation/sites/g/files/znldhr2076/files/js/js_Q_5koff_VqoByS8FgYkjdfUgEiubFOYF4QflwWF01x4.js"></script>

    <script type="text/javascript">
      window.addEventListener('load', (event) => {
        jQuery.getScript("/recreation/sites/g/files/znldhr2076/files/google_tag/psu_gtm_container/google_tag.script.js?ql1qoz")
          .done(function(script, textStatus) {
            console.log(textStatus);
          })
          .fail(function(jqxhr, settings, exception) {
            console.log('Unable to load google tag manager script.');
        });
      });
    </script>
  <script type="text/javascript">window.NREUM||(NREUM={});NREUM.info={"beacon":"bam-cell.nr-data.net","licenseKey":"58083d2021","applicationID":"703507193","transactionName":"ZQcHNUtSDRBUUUZZXlxNJAJNWgwNGnZARUFTDjkPVlcGP3ZdXERDXQ4JBEtvLQxRV2RZVEUhCg9NQQwPWVdAHQ9ECwAW","queueTime":0,"applicationTime":555,"atts":"SUAEQwNIHh4=","errorBeacon":"bam-cell.nr-data.net","agent":""}</script></body>
</html>
