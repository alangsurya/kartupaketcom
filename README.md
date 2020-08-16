<?xml version="1.0" encoding="UTF-8" ?>
<!DOCTYPE html>
<html b:version='2' class='v2' expr:dir='data:blog.languageDirection' lang='id' xmlns='http://www.w3.org/1999/xhtml' xmlns:b='http://www.google.com/2005/gml/b' xmlns:data='http://www.google.com/2005/gml/data' xmlns:expr='http://www.google.com/2005/gml/expr'>
<head>
<script async='async' data-ad-client='ca-pub-3743380332259935' src='https://pagead2.googlesyndication.com/pagead/js/adsbygoogle.js'/>
<meta content='width=device-width, initial-scale=1' name='viewport'/>
<b:include data='blog' name='all-head-content'/>
<b:if cond='data:blog.pageType == &quot;index&quot;'>
<title><data:blog.pageTitle/></title>
<b:else/>
<b:if cond='data:blog.pageType != &quot;error_page&quot;'>
<title><data:blog.pageName/> - <data:blog.title/></title>
</b:if></b:if>
<b:if cond='data:blog.pageType == &quot;error_page&quot;'>
<title>Page Not Found - <data:blog.title/></title>
</b:if>
<b:if cond='data:blog.pageType in {&quot;index&quot;} and data:blog.homepageUrl == data:blog.url'>
<meta expr:content='data:blog.title' name='keywords'/>
</b:if>    
<b:if cond='data:blog.pageType in {&quot;item&quot;,&quot;static_page&quot;}'>
<meta expr:content='data:blog.pageName' name='keywords'/>
</b:if>
<b:if cond='data:blog.pageType in {&quot;archive&quot;} or data:blog.searchLabel or data:blog.searchQuery'>
<meta content='noindex,nofollow' name='robots'/>
</b:if>
<b:if cond='data:blog.pageType == &quot;item&quot;'>
<meta expr:content='data:blog.pageName' property='og:title'/>
<meta content='article' property='og:type'/>
<b:else/>
<meta expr:content='data:blog.pageTitle' property='og:title'/>
<meta content='website' property='og:type'/>
</b:if>
<meta expr:content='data:blog.title' property='og:site_name'/>
<link href='https://www.blogger.com/profile/xxxxx' rel='publisher'/>
<link href='https://www.blogger.com/profile/xxxxx' rel='author'/>
<link href='https://www.blogger.com/profile/xxxxx' rel='me'/>
<meta content='xxxxx' name='google-site-verification'/>
<meta content='Indonesia' name='geo.placename'/>
<meta content='YOUR NAME' name='Author'/>
<meta content='id' name='geo.country'/>
<meta expr:content='data:blog.title' name='twitter:site'/>
<meta content='@xxxxx' name='twitter:creator'/>
<meta content='xxxxx' property='fb:admins'/>
<meta content='xxxxx' property='fb:app_id'/>
<!-- CHANGE PHONE BAR COLOR -->
<meta content='#1862de' name='theme-color'/>
<meta content='#1862de' name='msapplication-navbutton-color'/>
<meta content='yes' name='apple-mobile-web-app-capable'/>
<meta content='#1862de' name='apple-mobile-web-app-status-bar-style'/>
<b:skin><![CDATA[
/*
Theme Name       : Masign Asuka
Theme Version    : v2.0.0 (January 2020)
Designer         : Rhinokage Rio
URL Designer     : https://www.idblanter.com
Theme License    : Premium (Blanter Premium License 3.0)
*/
<Group description="New Comment Required - Dont edit">
<Variable name="body.background" description="Body Background" type="background" color="#000" default="#000 none repeat scroll top left" value="#000 none repeat scroll top left"/>
<Variable name="body.font" description="Font" type="font" default="normal normal 14px 'roboto', sans-serif" value="normal normal 14px &#39;roboto&#39;, sans-serif"/>
<Variable name="body.text.color" description="Text Color" type="color" default="#222" value="#222222"/>
<Variable name="body.text.font" description="2"
type="font"
default="normal normal 14px 'roboto', sans-serif" value="normal normal 14px &#39;roboto&#39;, sans-serif"/>
<Variable name="posts.background.color" description="6"
type="color"
default="#fff" value="#ffffff"/>
<Variable name="body.link.color" description="7"
type="color"
default="#2196f3" value="#2196f3"/>
<Variable name="body.link.visited.color" description="8"
type="color"
default="#2196f3" value="#2196f3"/>
<Variable name="body.link.hover.color" description="9"
type="color"
default="#2196f3" value="#2196f3"/>
<Variable name="blog.title.font" description="10"
type="font"
default="$(robotoBold45)" value="$(robotoBold45)"/>
<Variable name="blog.title.color" description="11"
type="color"
default="#fff" value="#ffffff"/>
<Variable name="header.icons.color"
description="12"
type="color"
default="#fff" value="#ffffff"/>
<Variable name="tabs.font" description="13"
type="font"
family="'roboto', sans-serif"
size="14px"
default="700 normal $(size) $(family)" value="700 normal $(size) $(family)"/>
<Variable name="tabs.color" description="14"
type="color"
default="#ccc" value="#cccccc"/>
<Variable name="tabs.selected.color" description="15"
type="color"
default="#fff" value="#ffffff"/>
<Variable name="tabs.overflow.background.color" description="16"
type="color"
default="#ffffff" value="#ffffff"/>
<Variable name="tabs.overflow.color" description="17"
type="color"
default="#222222" value="#222222"/>
<Variable name="tabs.overflow.selected.color" description="18"
type="color"
default="#212121" value="#212121"/>
<Variable name="posts.title.color" description="19"
type="color"
default="#212121" value="#212121"/>
<Variable name="posts.title.font" description="20"
type="font"
default="$(robotoBold22)" value="$(robotoBold22)"/>
<Variable name="posts.text.font" description="21"
type="font"
default="normal normal 14px 'roboto', sans-serif" value="normal normal 14px &#39;roboto&#39;, sans-serif"/>
<Variable name="posts.text.color" description="22"
type="color"
default="#222222" value="#222222"/>
<Variable name="posts.icons.color"
description="23"
type="color"
default="#707070" value="#707070"/>
<Variable name="labels.background.color"
description="24"
type="color"
default="$(sidebar.backgroundColorTopHD)" value="$(sidebar.backgroundColorTopHD)"/>
</Group>
/* Font Face */
@font-face{font-family:'Google Sans';font-style:normal;font-weight:400;src:local('Google Sans Regular'),local('GoogleSans-Regular'),url(https://fonts.gstatic.com/s/googlesans/v9/4UaGrENHsxJlGDuGo1OIlL3Kwp5MKg.woff2) format('woff2');unicode-range:U+0400-045F,U+0490-0491,U+04B0-04B1,U+2116}@font-face{font-family:'Google Sans';font-style:normal;font-weight:400;src:local('Google Sans Regular'),local('GoogleSans-Regular'),url(https://fonts.gstatic.com/s/googlesans/v9/4UaGrENHsxJlGDuGo1OIlL3Nwp5MKg.woff2) format('woff2');unicode-range:U+0370-03FF}@font-face{font-family:'Google Sans';font-style:normal;font-weight:400;src:local('Google Sans Regular'),local('GoogleSans-Regular'),url(https://fonts.gstatic.com/s/googlesans/v9/4UaGrENHsxJlGDuGo1OIlL3Awp5MKg.woff2) format('woff2');unicode-range:U+0100-024F,U+0259,U+1E00-1EFF,U+2020,U+20A0-20AB,U+20AD-20CF,U+2113,U+2C60-2C7F,U+A720-A7FF}@font-face{font-family:'Google Sans';font-style:normal;font-weight:400;src:local('Google Sans Regular'),local('GoogleSans-Regular'),url(https://fonts.gstatic.com/s/googlesans/v9/4UaGrENHsxJlGDuGo1OIlL3Owp4.woff2) format('woff2');unicode-range:U+0000-00FF,U+0131,U+0152-0153,U+02BB-02BC,U+02C6,U+02DA,U+02DC,U+2000-206F,U+2074,U+20AC,U+2122,U+2191,U+2193,U+2212,U+2215,U+FEFF,U+FFFD}@font-face{font-family:'Google Sans';font-style:normal;font-weight:500;src:local('Google Sans Medium'),local('GoogleSans-Medium'),url(https://fonts.gstatic.com/s/googlesans/v9/4UabrENHsxJlGDuGo1OIlLU94Yt3CwZ-Pw.woff2) format('woff2');unicode-range:U+0400-045F,U+0490-0491,U+04B0-04B1,U+2116}@font-face{font-family:'Google Sans';font-style:normal;font-weight:500;src:local('Google Sans Medium'),local('GoogleSans-Medium'),url(https://fonts.gstatic.com/s/googlesans/v9/4UabrENHsxJlGDuGo1OIlLU94YtwCwZ-Pw.woff2) format('woff2');unicode-range:U+0370-03FF}@font-face{font-family:'Google Sans';font-style:normal;font-weight:500;src:local('Google Sans Medium'),local('GoogleSans-Medium'),url(https://fonts.gstatic.com/s/googlesans/v9/4UabrENHsxJlGDuGo1OIlLU94Yt9CwZ-Pw.woff2) format('woff2');unicode-range:U+0100-024F,U+0259,U+1E00-1EFF,U+2020,U+20A0-20AB,U+20AD-20CF,U+2113,U+2C60-2C7F,U+A720-A7FF}@font-face{font-family:'Google Sans';font-style:normal;font-weight:500;src:local('Google Sans Medium'),local('GoogleSans-Medium'),url(https://fonts.gstatic.com/s/googlesans/v9/4UabrENHsxJlGDuGo1OIlLU94YtzCwY.woff2) format('woff2');unicode-range:U+0000-00FF,U+0131,U+0152-0153,U+02BB-02BC,U+02C6,U+02DA,U+02DC,U+2000-206F,U+2074,U+20AC,U+2122,U+2191,U+2193,U+2212,U+2215,U+FEFF,U+FFFD}

/* Framework */
a,abbr,acronym,address,applet,article,aside,audio,b,big,blockquote,body,canvas,caption,center,cite,code,dd,del,details,dfn,div,dl,dt,em,embed,fieldset,figcaption,figure,footer,form,h1,h2,h3,h4,h5,h6,header,hgroup,html,i,iframe,img,ins,kbd,label,legend,li,mark,menu,nav,object,ol,output,p,pre,q,ruby,s,samp,section,small,span,strike,strong,sub,summary,sup,table,tbody,td,tfoot,th,thead,time,tr,tt,u,ul,var,video{margin:0;padding:0;border:0;font:inherit;vertical-align:baseline}article,aside,details,figcaption,figure,footer,header,hgroup,menu,nav,section{display:block}body{line-height:1;display:block}*{margin:0;padding:0}html{display:block}blockquote,q{quotes:none}blockquote::after,blockquote::before,q::after,q::before{content:'';content:none}table{border-collapse:collapse;border-spacing:0}.section,.widget{margin:0;padding:0}#backlinks-container,.blog-feeds,.blog-mobile-link,.feed-links,.navbar,a.home-link{display:none}.edit-post,.item-control,.quickedit{display:none}.post-body .separator>a,.post-body .separator>span{margin-left:0!important}b,strong{font-weight:700}cite,em,i{font-style:italic}a:link{color:#1a73e8;text-decoration:none;outline:0}a:visited{color:#1a73e8;text-decoration:none}a:hover{color:#555;text-decoration:none}a img{border:none;border-width:0;outline:0}abbr,acronym{border-bottom:1px dotted;cursor:help}sub,sup{vertical-align:baseline;position:relative;top:-.4em;font-size:86%}sub{top:.4em}small{font-size:86%}kbd{font-size:80%;border:1px solid #777;padding:2px 5px;border-bottom-width:2px;border-radius:3px}mark{background-color:#ffce00;color:#000}blockquote,dl,figure,form,hr,ol,p,pre,table,ul{margin:0 0 1.5em}hr{height:1px;border:none;background-color:#666}h1{font-size:1.8rem}h2{font-size:1.6rem}h3{font-size:1.4rem}h4{font-size:1.2rem}h5{font-size:1rem}h6{font-size:.9rem}h1,h2,h3,h4,h5,h6{margin:0 0 .6em;font-weight:700}dl,ol,ul{margin:.5em 0 .5em 3em}li{margin:.5em 0}dt{font-weight:700}dd{margin:0 0 .5em 2em}select{font:inherit;font-size:100%;line-height:normal;vertical-align:baseline}textarea{display:block;-webkit-box-sizing:border-box;-moz-box-sizing:border-box;box-sizing:border-box}code,pre{font-family:"Courier New",Courier,Monospace;color:inherit}pre{white-space:pre;word-wrap:normal;overflow:auto}table[border="1"] td,table[border="1"] th{vertical-align:top;text-align:left;font-size:13px;padding:3px 5px;border:1px solid #f6f6f6}table[border="1"] th{background:#eee}img,table{max-width:100%;height:auto}iframe{max-width:100%}td.tr-caption{color:#444}.clear{clear:both}.clear::after{visibility:hidden;display:block;font-size:0;content:" ";clear:both;height:0}a:link{transition:all .2s;-moz-transition:all .2s;-webkit-transition:all .2s}i.material-icons{max-width:27px}

/* Content UI */
body{font-family:'Google Sans',Arial,sans-serif}.darkshadow{display:none;position:fixed;top:0;background:rgba(0,0,0,.4);left:0;right:0;bottom:0;margin:0;z-index:60;transition:all .4s ease-in-out}#showsearch,.descriptionmaterial,.blanter-back,input#menu-btn,#menu-widget h2,.displaynone,#responsive,#slidemenu h2,.license-code{display:none}#outer-material{margin:68px 0 0;position:relative;overflow:hidden}#content-material{width:1000px;max-width:100%;margin:0 auto;position:relative;padding:15px}.material,#material{width:1000px;max-width:100%;margin:0 auto;position:relative}#main-material{margin:10px auto}#header-material{position:absolute;background:#fff;z-index:60;top:0;left:0;right:0;height:70px}#header{float:left;color:#555;margin:18px 15px 10px 5px}#header h1,#header a{font-size:22px;font-weight:400;color:#555}a.toggleMenu{color:#555;float:left;padding:10px 12px;margin:10px;border-radius:100%}a.toggleMenu:hover,#showmenu:hover,a.dialogUi:hover{background:#eee}#showmenu,a.dialogUi{color:#555;float:right;padding:10px 12px;margin:10px 10px 0 0;border-radius:100%}blockquote{border-left:4px solid #673ab7!important;background:#eee;overflow:hidden;position:relative;margin:.5rem 0 1rem;border-radius:5px;color:#444;padding:20px}a.dialogUi{margin-right:0}.header img{max-width:210px;margin:-7px 0 0}

/* Search */
#searchblanterx{position:relative;overflow:hidden;float:left}#searchblanterx .blanter-icons{position:absolute;left:6%;top:30%;color:#555}#searchblanterx input#search-text{border:0;box-shadow:0 1px 2px 0 rgba(60,64,67,.30),0 1px 3px 1px rgba(60,64,67,.15);padding:12px 15px 12px 60px;margin:12px;border-radius:5px;width:400px;font-size:16px;font-family:'Google Sans',Arial;max-width:100%;outline:none}#searchblanterx input#search-text:focus{box-shadow:0 1px 5px 0 rgba(60,64,67,.30),0 2px 4px 1px rgba(60,64,67,.15)}.largebanner,.footerbanner{margin:0 auto;padding:0 0 15px;width:100%;max-width:970px;float:none;overflow:hidden;position:relative;clear:both}.footerbanner .widget,.largebanner .widget{padding:10px;transition:all .5s ease-in-out;max-height:90px}.largebanner img,.largebanner iframe,.footerbanner img,.footerbanner iframe{display:block;max-width:100%;border:none;overflow:hidden}.largebanner img,.footerbanner img{max-height:90px}.darkshadow.aktif{display:block}

/* Menu Navigasi */
#menu-blanter{position:relative;z-index:10;background:#fff;top:70px;border-bottom:2px solid #ddd;left:0;right:0;padding:0 20px;height:50px}#menu-blanter ul{padding:0;list-style:none}#menu-blanter ul li{float:left;line-height:1.3}#menu-blanter li a{display:block;padding:13px;margin:0 2px;font-size:14px;font-weight:500;color:#666;cursor:pointer;border-bottom:2px solid #fff}#menu-blanter li a:hover{background:transparent!important}#menu-blanter li a i{float:left;margin:-6px 8px 0 0;font-size:20px;width:20px;height:20px;color:#fff!important;padding:5px;border-radius:100%;background:#1f4c84;overflow:hidden}#menu-blanter .submenu:after,#slidemenu .submenu:after{content:"\f107";font-family:"Font Awesome 5 Free";font-style:normal;font-weight:600;text-decoration:inherit;padding-left:10px;color:#666}#menu-blanter li ul{background:#fff;display:none;position:absolute;width:180px;padding:2px 0;max-width:200px;box-shadow:0 1px 2px 0 rgba(60,64,67,.30),0 1px 3px 1px rgba(60,64,67,.15);border-radius:8px}#menu-blanter li ul li{float:none;line-height:1;padding:0}#menu-blanter li ul a{border:none;border-radius:5px}#menu-blanter li ul a:hover{background:#eee!important;color:#333}#menu-blanter li a.navhome{color:#1f4c84;border-color:#1f4c84}#menublanter li:nth-child(1) a i,#menublanter li:nth-child(1) a:hover{background:#1f4c84;color:#1f4c84;border-color:#1f4c84}#menublanter li:nth-child(2) a i,#menublanter li:nth-child(2) a:hover{background:#008000;color:#008000;border-color:#008000}#menublanter li:nth-child(3) a i,#menublanter li:nth-child(3) a:hover{background:#34a853;color:#34a853;border-color:#34a853}#menublanter li:nth-child(4) a i,#menublanter li:nth-child(4) a:hover{background:#d3177f;color:#d3177f;border-color:#d3177f}#menublanter li:nth-child(5) a i,#menublanter li:nth-child(5) a:hover{background:#ea4335;color:#ea4335;border-color:#ea4335}#menublanter li:nth-child(6) a i,#menublanter li:nth-child(6) a:hover{background:#f9ab00;color:#f9ab00;border-color:#f9ab00}#menublanter li:nth-child(7) a i,#menublanter li:nth-child(7) a:hover{background:#8462d8;color:#8462d8;border-color:#8462d8}#menublanter li:nth-child(8) a i,#menublanter li:nth-child(8) a:hover{background:#2aafbd;color:#2aafbd;border-color:#2aafbd}#menublanter ul#dark-myar{float:right}#menublanter #dark-myar li a i,#menublanter #dark-myar li a:hover{background:#222;color:#222;border-color:#222}

/* Slide Menu */
#slidemenu{position:fixed;visibility:hidden;opacity:0;transition:all .3s ease-in-out;z-index:61;background:#fff;box-shadow:0 8px 10px -5px rgba(0,0,0,.2),0 16px 24px 2px rgba(0,0,0,.14),0 6px 30px 5px rgba(0,0,0,.12);left:-350px;top:0;bottom:0;width:250px}#slidemenu ul{padding:0;list-style:none}#slidemenu li{padding:0}#slidemenu li a:hover{background:#f8f9fa;color:#1a73e8}#slidemenu li a{display:block;padding:12px 25px;font-weight:500;font-size:15px;color:#777;margin:3px 10px;cursor:pointer;border-radius:10px}#slidemenu li ul{display:none;margin:0 10px;padding:2px 0;border-radius:10px;background:#eee}#slidemenu li ul a{margin:3px 5px;font-size:14px}#slidemenu a i{float:left;font-size:23px;margin:-2px 10px 0 0}#headermenu{position:fixed;display:none;z-index:60;background:#fff;overflow:hidden;top:58px;right:30px;width:180px;border-radius:8px;box-shadow:0 1px 2px 0 rgba(60,64,67,.30),0 1px 3px 1px rgba(60,64,67,.15)}#headermenu li{margin:0;list-style:none}#headermenu li a{color:#555;display:block;font-size:16px;padding:12px}#headermenu li a:hover{background:#f8f9fa}#headermenu i{margin-right:10px}#slidemenu.aktif{left:0;visibility:visible;opacity:1}#headermenu i.fa-facebook{color:#4867aa}#headermenu i.fa-twitter{color:#1da1f2}#headermenu i.fa-youtube{color:#c82828}#headermenu i.fa-instagram{color:#650582}

/* Footer */
#footer-bottom p{margin:10px;float:left}.grid.one-half{margin:0 auto;width:85%;max-width:100%}#footer-bottom{text-align:center;font-size:14px;padding:20px;overflow:hidden;color:#444;border-top:1px solid #ddd}#footer-bottom a{color:#444}#footer-bottom a.feedcontact{float:right;color:#1a73e8;border:1px solid #ddd;padding:7px 15px;font-weight:500;border-radius:5px;line-height:1.8}#footer-bottom a i{float:left;margin-right:10px;width:25px;height:25px;overflow:hidden}a.feedcontact:hover{background:#f8f9fa}

/* Breadcrumbs */
.breadcrumbs{overflow:hidden;white-space:nowrap;text-overflow:ellipsis;line-height:1.6;font-size:20px;margin:-10px 0 10px}.breadcrumbs a{font-size:13.5px;color:#333;background:#f5f5f5;display:inline-block;padding:3px 10px;border-radius:20px}.breadcrumbs b{color:#777;font-weight:500}.breadcrumbs a:hover{background:#eee}.breadcrumbs a i{float:left;font-size:20px;margin-right:5px;line-height:1}.breadcrumbs span.judulb{font-size:13.5px;opacity:.9;background:#f5f5f5;padding:4px 10px;border-radius:20px}.labelb:nth-of-type(n+6),.breadcrumbs b:nth-of-type(n+6),h1.post-title.entry-title{display:none}#material-breadcrumbs{margin:15px 0 0}

/* Dark Mode */
.darkmode body,.darkmode #header-material{background:#111;color:#ddd}.darkmode a.dialogUi,.darkmode #header,.darkmode a.toggleMenu,.darkmode #showmenu,.darkmode #searchblanterx .blanter-icons,.darkmode #searchblanterx input::placeholder,.darkmode #menu-blanter .submenu:after,.darkmode #slidemenu .submenu:after,.darkmode #slidemenu li a,.darkmode #headermenu li a,.darkmode .box-body-deg h2 a,.darkmode a.g-profile,.darkmode .label-info a,.darkmode #header a,.darkmode #header h1,.darkmode #footer-bottom,.darkmode #footer-bottom a,.darkmode .banner970 .title970,.darkmode .footer-ui h2,.darkmode #showsearch,.darkmode td.tr-caption{color:#e8eaed}.darkmode a.toggleMenu:hover,.darkmode a.dialogUi:hover,.darkmode #showmenu:hover,.darkmode a.feedcontact:hover,.darkmode .banner970,.darkmode .blanternotif{background:#333}.darkmode #searchblanterx input#search-text,.darkmode #menu-blanter li ul,.darkmode #slidemenu,.darkmode #headermenu,.darkmode .post-outer{background:#222;color:#ddd}.darkmode #menu-blanter{background:#111;border-color:#333}.darkmode #menu-blanter li a{color:#ddd;border-color:#111}.darkmode #menu-blanter li ul a:hover,.darkmode #slidemenu li a:hover,.darkmode #slidemenu li ul,.darkmode #headermenu li a:hover{background:#333!important;color:#ddd}.darkmode #menublanter li a i,.darkmode #menublanter li a:hover{color:#e8eaed!important;border-color:#fff!important}.darkmode .post-outer,.darkmode .tanggalx,.darkmode .label-info a,.darkmode #footer-bottom a.feedcontact,.darkmode #footer-bottom,.darkmode #footer-material{border-color:#444}.darkmode .tanggal abbr,.darkmode .tanggal i{color:#ddd}.darkmode .mydark:after{content:'ON';background:#11a711;font-weight:700;padding:5px;margin-left:10px;border-radius:5px;font-size:13px}.darkmode #blog-pager span,.darkmode a.js-load,.darkmode a.js-load:hover{background:#333;border-color:#444;color:#ddd}.darkmode #blanter-loader{background:#111}.darkmode .input-field input,.darkmode .input-field textarea{background:#111;color:#ddd;border-color:#555}.darkmode .input-field label{background:#111!important}.darkmode .label-size a,.darkmode .label-size span{background:#222;border-color:#444;color:#ddd}.darkmode .blanternotif a.waves-light.close-sf{color:#fff;background:#444;border:1px solid #666;box-shadow:none}

/* E-Waves */
.e-waves{position:relative;cursor:pointer;display:inline-block;overflow:hidden;-webkit-user-select:none;-moz-user-select:none;-ms-user-select:none;user-select:none;-webkit-tap-highlight-color:transparent;vertical-align:middle;z-index:1;will-change:opacity,transform;-webkit-transition:all .3s ease-out;-moz-transition:all .1s ease-out;-o-transition:all .1s ease-out;-ms-transition:all .1s ease-out;transition:all .1s ease-out}.e-waves .waves-ripple{position:absolute;border-radius:50%;width:20px;height:20px;margin-top:-10px;margin-left:-10px;opacity:0;background:rgba(0,0,0,0.2);-webkit-transition:all .1s ease-out;-moz-transition:all .1s ease-out;-o-transition:all .1s ease-out;-ms-transition:all .1s ease-out;transition:all .1s ease-out;-webkit-transition-property:-webkit-transform,opacity;-moz-transition-property:-moz-transform,opacity;-o-transition-property:-o-transform,opacity;transition-property:transform,opacity;-webkit-transform:scale(0);-moz-transform:scale(0);-ms-transform:scale(0);-o-transform:scale(0);transform:scale(0);pointer-events:none}.e-waves.waves-light .waves-ripple{background-color:rgba(255,255,255,0.45)}.e-waves.waves-red .waves-ripple{background-color:rgba(244,67,54,0.7)}.e-waves.waves-yellow .waves-ripple{background-color:rgba(255,235,59,0.7)}.e-waves.waves-orange .waves-ripple{background-color:rgba(255,152,0,0.7)}.e-waves.waves-purple .waves-ripple{background-color:rgba(156,39,176,0.7)}.e-waves.waves-green .waves-ripple{background-color:rgba(76,175,80,0.7)}.e-waves.waves-teal .waves-ripple{background-color:rgba(0,150,136,0.7)}.waves-notransition{-webkit-transition:none!important;-moz-transition:none!important;-o-transition:none!important;-ms-transition:none!important;transition:none!important}.waves-circle{-webkit-transform:translateZ(0);-moz-transform:translateZ(0);-ms-transform:translateZ(0);-o-transform:translateZ(0);transform:translateZ(0);-webkit-mask-image:-webkit-radial-gradient(circle,white 100%,black 100%)}.waves-input-material{border-radius:.2em;vertical-align:bottom;width:100%}.waves-input-material .waves-button-input{position:relative;top:0;left:0;z-index:1}.waves-circle{text-align:center;width:2.5em;height:2.5em;line-height:2.5em;border-radius:50%;-webkit-mask-image:none}.waves-block{display:block}a.e-waves .waves-ripple{z-index:-1}.ripple{display:inline-block;text-decoration:none;overflow:hidden;position:relative;z-index:0}.ink{display:block;position:absolute;background:rgba(255,255,255,0.4);border-radius:100%;-webkit-transform:scale(0);-moz-transform:scale(0);-o-transform:scale(0);transform:scale(0)}.animate{-webkit-animation:ripple .55s linear;-moz-animation:ripple .55s linear;-ms-animation:ripple .55s linear;-o-animation:ripple .55s linear;animation:ripple .55s linear}@-webkit-keyframes ripple{100%{opacity:0;-webkit-transform:scale(2.5)}}@-moz-keyframes ripple{100%{opacity:0;-moz-transform:scale(2.5)}}@-o-keyframes ripple{100%{opacity:0;-o-transform:scale(2.5)}}@keyframes ripple{100%{opacity:0;transform:scale(2.5)}}

/* Loader dan Banner Ads */
#blanter-loader{position:fixed;z-index:999;background:#fff;top:0;left:0;right:0;bottom:0}#blanter-loader svg{position:relative;top:45%;left:48%}.qp-circular-loader{width:16px;height:16px}.qp-circular-loader-path{stroke-dasharray:32.4;stroke-dashoffset:32.4}.qp-circular-loader,.qp-circular-loader *{transform-origin:50% 50%}@keyframes rotate{from{transform:rotate(0deg)}to{transform:rotate(360deg)}}.qp-circular-loader{animation-duration:1568.63ms;animation-iteration-count:infinite;animation-name:rotate;animation-timing-function:linear}@keyframes fillunfill{from{stroke-dashoffset:32.3}50%{stroke-dashoffset:0}to{stroke-dashoffset:-31.9}}@keyframes rot{from{transform:rotate(0deg)}to{transform:rotate(-360deg)}}@keyframes colors{from{stroke:#008000}to{stroke:#008000}}.qp-circular-loader-path{animation-duration:1333ms,5332ms,5332ms;animation-fill-mode:forwards;animation-iteration-count:infinite,infinite,infinite;animation-name:fillunfill,rot,colors;animation-play-state:running,running,running;animation-timing-function:cubic-bezier(0.4,0.0,0.2,1),steps(4),linear}.banner970 a{float:right;margin:25px;padding:8px 18px;background:#fff;border:1px solid #ccc;border-radius:7px;font-weight:500;text-transform:uppercase}.banner970 .title970{font-weight:500;font-size:24px;color:#555;float:left;padding:28px}.banner970{background:#e3e3e3;padding:0;max-width:970px;width:100%;height:90px;overflow:hidden}.float_material{transition:all .3s ease-out;-webkit-transform:translateZ(0);transform:translateZ(0)}#header-material.scroll{position:fixed!important;top:-90px!important}#header-material.no-scroll{position:fixed!important;top:0!important}#header-material.scroll.no-scroll{box-shadow:0 1px 2px 0 rgba(60,64,67,.30), 0 1px 3px 1px rgba(60,64,67,.15)}#headermenu.scroll{opacity:0}#headermenu.no-scroll{opacity:1}

/* Tombol dan Material Input */
.buttonx,form input[type="button"]{background:#1a73e8;color:#fff!important;padding:12px 25px;text-transform:uppercase;border-radius:4px;border:none;outline:none;box-shadow:0 1px 2px 0 rgba(60,64,67,0.302),0 1px 3px 1px rgba(60,64,67,0.149);cursor:pointer;transition:all .3s ease-in-out!important;font-weight:500;font-family:'Google Sans',Roboto}.buttonx:hover{box-shadow:0 5px 11px 0 rgba(0,0,0,0.18),0 4px 15px 0 rgba(0,0,0,0.15)}.buttonx.subs{text-transform:none;letter-spacing:.5px;font-weight:500;padding:10px 18px}.post-body .buttonx{padding:8px 18px;margin:15px 5px 20px 0;display:inline-block}.input-field .buttonx{margin-top:15px}.input-field .buttonx i{margin-right:5px}.input-field{position:relative;margin:15px 0}.input-field input,.input-field textarea{font-size:15px;padding:15px 0 15px 15px;display:block;width:94%;border:1px solid #ddd;border-radius:7px}.input-field input:focus,.input-field textarea:focus{outline:none}.input-field label{color:#999;font-size:14px;font-weight:400;position:absolute;pointer-events:none;left:15px;top:15px;transition:.2s ease all}.input-field input:focus~label,.input-field input:valid~label,.input-field textarea:focus~label,.input-field textarea:valid~label{top:0;font-size:14px;color:#1a73e8;background:#fff;padding:1px 7px;margin:10px 0 0 -5px}.input-field input:focus,.input-field textarea:focus{border:2px solid #1a73e8}.indigox{background:#3f51b5}.orangex{background:#ff9800}.pinkx{background:#e91e63}.bluex{background:#2196F3}.purplex{background:#9c27b0}.redx{background:#ea4335}.greenx{background:#4CAF50}.highlight{position:absolute;height:50%;width:100px;top:25%;left:0;pointer-events:none;opacity:.5}.input-field input:focus~.highlight,.input-field textarea:focus~.highlight{animation:inputHighlighter .3s ease}.input-field input:focus~label,.input-field input:valid~label,.input-field textarea:focus~label,.input-field textarea:valid~label{top:-20px;font-size:13px;color:#1a73e8}.input-field textarea{width:96.5%}

/* Cloud Label, Footer Widgets, Sosmed, BackToTop */
.label-size-1,.label-size-2,.label-size-3,.label-size-4,.label-size-5{font-size:100%;filter:alpha(100);opacity:10}.cloud-label-widget-content{text-align:left}.label-size{display:block;float:left;font-family:'Google Sans',sans-serif;margin:0 3px 3px 0;font-size:12px;font-weight:500;transition:all .3s ease-in-out}.label-size a,.label-size span{background:#fff;display:inline-block;padding:8px 10px;color:#1a73e8;border:1px solid #ddd;border-radius:5px}.label-size a:hover{border-color:#1a73e8}.label-count{white-space:nowrap;padding-right:3px;margin-left:-3px}.label-size{line-height:1.2}#footer-material{display:grid;grid-template-columns:1fr 1fr 1fr;position:relative;overflow:hidden;grid-gap:25px;margin:15px 0;padding:20px 0 0;border-top:1px solid #ddd}.popular-posts .item-snippet{display:none}.PopularPosts .widget-content ul li{list-style:none;padding:0}.popular-posts ul{list-style:none;padding:0}.PopularPosts img{border-radius:100%}.footer-ui h2,.footer-ui h3{font-size:17px;color:#1a73e8;font-weight:500;margin:5px 0 20px;padding:0 15px;border-left:4px solid #1a73e8}.footer-ui .widget-content{font-size:15px}ul.sosmedimut{overflow:hidden;padding:10px 0}.sosmedimut li{list-style:none;padding:0;float:left}.sosmedimut li a{background:#fff;box-shadow:0 1px 2px 0 rgba(60,64,67,.30),0 1px 3px 1px rgba(60,64,67,.15);color:#444;margin:0 10px 0 0;width:30px;height:30px;line-height:32px;border-radius:100%;display:block;text-align:center}.sosmedimut li a.fcb{color:#4867aa}.sosmedimut li a.twt{color:#1da1f2}.sosmedimut li a.joz{color:#650582}.sosmedimut li a.ytx{color:#c82828}#BackToTop{overflow:hidden;position:fixed;transform:scale(0);z-index:90;right:30px;bottom:31px;box-shadow:0 2px 5px 0 rgba(0,0,0,0.16),0 2px 10px 0 rgba(0,0,0,0.12);width:55px;height:55px;color:#fff;text-align:center;background-color:#1a73e8;font-size:22px;line-height:52px;cursor:pointer;border-radius:100%;transition:all .2s ease-in-out}#BackToTop:hover{opacity:.8}#BackToTop.active{transform:scale(1)}

/* Notif Box */
.blanternotif{visibility:hidden;opacity:0;background:#fff;position:fixed;padding:25px;top:20%;transform:scale(.5);transition:all .3s ease-in-out;max-width:450px;left:35%;z-index:99;border-radius:7px;box-shadow:0 9px 46px 8px rgba(0,0,0,.14),0 11px 15px -7px rgba(0,0,0,.12),0 24px 38px 3px rgba(0,0,0,.2)}.blanternotif button{border:none;position:absolute;margin-top:17px;right:30px;cursor:pointer;background:#e8e8e8;padding-left:7px;outline:0}.blanternotif a.waves-light{font-size:14px;color:#fff;background:#1a73e8;margin-left:5px;margin-top:25px;display:inline-block;padding:10px 15px;border-radius:4px;float:right;font-weight:500;border:1px solid #1a73e8}.blanternotif a.waves-light.close-sf{color:#1a73e8;background:#fff;border:1px solid #ddd;box-shadow:none}.blantertitle{margin-bottom:15px;text-align:left;font-weight:500}.flashlight{position:fixed;z-index:98;top:0;height:100%;width:100%;background:rgba(0,0,0,0.57);opacity:0;visibility:hidden;transition:all .3s ease-in-out}.blanternotif.aktif,.flashlight.aktif{visibility:visible;opacity:1}.blanternotif.aktif{transform:scale(1)}.notiftext{font-size:13.5px;line-height:1.6;text-align:left}.dialogUi:hover i{-webkit-transform-origin:top;-ms-transform-origin:top;transform-origin:top;-webkit-animation-name:example;-webkit-animation-duration:1s;animation-name:example;animation-duration:1s}@-webkit-keyframes example{0%{transform:rotate(0deg)}20%{transform:rotate(26deg)}40%{transform:rotate(-26deg)}60%{transform:rotate(26deg)}80%{transform:rotate(-26deg)}100%{transform:rotate(0deg)}}@keyframes example{0%{transform:rotate(0deg)}20%{transform:rotate(26deg)}40%{transform:rotate(-26deg)}60%{transform:rotate(26deg)}80%{transform:rotate(-26deg)}100%{transform:rotate(0deg)}}

/* MEDIA RESPONSIVE */
@media screen and (min-width:1024px) and (max-width:1100px){a.mydark{width:20px;height:16px;overflow:hidden}}@media screen and (max-width:900px){#searchblanterx .blanter-icons{left:3%}}@media screen and (max-width:768px){#slidemenu{width:80%}#header{margin:14px 15px 10px 5px}#header h1,#header a{font-size:18px}#content-material{padding:60px 0 0;max-width:90%}#outer-material{margin:0;width:100%}#content-material{padding-top:60px}#header-material{height:57px;box-shadow:0 1px 2px 0 rgba(60,64,67,.30),0 1px 3px 1px rgba(60,64,67,.15)!important;margin:10px;border-radius:10px}a.toggleMenu,#showmenu{padding:8px 10px;margin:7px}#menu-blanter{top:0;padding:0;height:auto;overflow:hidden}#menublanter ul#dark-myar{float:none}#menu-blanter ul li{width:90%}#menu-blanter li a{border:none;width:83%}#menu-blanter li ul{position:relative;box-shadow:none;width:100%;max-width:100%}#slidemenu nav{max-height:700px;height:100%;overflow-y:scroll}#showsearch{color:#555;position:absolute;right:7%;top:1%;padding:8px 10px;margin:7px 15px;border-radius:100%;display:block}#searchblanterx{width:100%}#searchblanterx input#search-text{width:90%;margin:0;box-shadow:none;height:30px;border-radius:10px}.blanter-back{display:block;position:absolute;right:15px;top:15px}#searchmaterial{display:none;position:absolute;left:0;right:0}.grid.one-half,#footer-bottom{width:98%}#footer-bottom p{line-height:1.8}#footer-bottom a.feedcontact{float:none;display:inline-block}#footer-material{grid-template-columns:1fr;padding:15px 10px 0}.banner970 .title970{font-size:16px}.banner970 a{margin:20px}a.dialogUi{position:fixed;background:#fff;bottom:-15px;left:5%;z-index:9;box-shadow:0 1px 2px 0 rgba(60,64,67,.30),0 1px 3px 1px rgba(60,64,67,.15);border-radius:20px 20px 0 0;padding-bottom:20px}.blanternotif{left:5%;right:5%}.darkmode #header-material,.darkmode #searchblanterx input#search-text{background:#333}.darkmode a.dialogUi{background:#444}}@media screen and (max-width:680px){#blanter-loader svg{left:45%}#searchblanterx .blanter-icons{left:6%}#searchblanterx input#search-text{width:82%}}@media screen and (max-width:480px){.banner970 a{margin:20px 20px 20px 0}.banner970 .title970{padding-right:0}}
]]></b:skin>
<b:if cond='data:view.isLayoutMode'>
<b:template-skin>
<![CDATA[
body#layout li{display:none}body#layout div.section{border-radius:10px;overflow:hidden}body#layout .section h4{margin-left:0!important}body#layout .draggable-widget .widget-wrap2{border-radius:20px}body#layout .widget-content{border:1px solid #ccc;border-radius:15px;color:#1a73e8;font-weight:600}body#layout a.editlink{color:#1a73e8!important;border:1px solid #ccc;padding:0 15px;border-radius:20px}body#layout div#header{width:35%;float:left}body#layout div#menu-widget{float:right;width:54%}body#layout div#main{float:left;width:50%}body#layout div.tab{width:17%;float:left;height:170px}body#layout .tab .widget-content{height:90px}body#layout div.footer-ui{width:28%;float:left}body#layout div.add_widget a{color:#fff;font-weight:700;letter-spacing:1px;font-size:14px}body#layout div.add_widget{background:#008000;border-radius:50px}#layout:before{content:'Masign Asuka Premium (Idblanter.com)';text-transform:uppercase;font-size:18px;color:#fff;background:#1a73e8;margin:0 0 20px;display:inline-block;font-weight:700;font-family:monospace;padding:20px;border-radius:20px}
]]></b:template-skin>
</b:if>
<b:if cond='data:view.isSingleItem'>
<style type='text/css'>
/* CSS Hanya Postingan */
.addcomment,.time-publish{float:right;color:#1a73e8;border:1px solid #ddd;background:#fff;padding:7px 15px;font-weight:500;border-radius:5px;line-height:1.8;font-size:14px;margin-left:10px}.addcomment:hover{color:#1a73e8;background:#f8f8f8}.addcomment i{background:#1a73e8;color:#fff;padding:4px 5px;border-radius:100%;margin:0 7px 0 0}ul.related-post-style-3{display:grid;padding:0;grid-template-columns:1fr 1fr 1fr;grid-gap:15px;margin:0 0 20px}li.related-post-item{transition:all .2s ease-in-out;border:1px solid #ddd;padding:0;list-style:none;border-radius:10px;overflow:hidden;text-align:center}img.related-post-item-thumbnail{height:140px;width:100%}.related-post-item-tooltip a{color:#444;font-size:14px;padding:5px 10px 15px;display:block;line-height:1.6}li.related-post-item:hover{box-shadow:0 1px 3px 0 rgba(60,64,67,.30),0 4px 8px 3px rgba(60,64,67,.15)}.related-post h4{font-weight:500;line-height:1.8;margin:1.5em 0 .6em}.related-post h4 i{float:left;background:#1a73e8;color:#fff;padding:4px;border-radius:100%;margin:0 10px 0 0}@media screen and (max-width:680px){ul.related-post-style-3{grid-template-columns:1fr 1fr}.avatar-container{float:none;width:100%;text-align:center}.authorboxwrap h5{text-align:center}}
</style>
</b:if>
<b:if cond='data:view.isPage'><style type='text/css'>/* CSS Hanya Static Pages */.widget.HTML.scroll{display:none!important}.breadcrumbs{margin:0 0 20px}.post-body{padding:15px 0}#comments{margin:20px 0 10px}</style></b:if>
<b:if cond='data:view.isMultipleItems'>
<style type='text/css'>
/* CSS Homepage and Index */
.blog-posts{display:grid;grid-template-columns:1fr 1fr 1fr;grid-gap:15px}.post-outer{padding:0;border:1px solid #ddd;overflow:hidden;border-radius:10px;transition:all .2s ease-in-out}.post-outer:hover{box-shadow:0 1px 3px 0 rgba(60,64,67,.30),0 4px 8px 3px rgba(60,64,67,.15)}.box-body-deg{padding:5px 15px 15px}.post-thumbnail{width:100%}.post-thumbnail img{width:100%;height:215px;object-fit:cover}.PopularPosts li a{font-size:14px}.box-body-deg h2.post-title{font-size:15px;font-weight:500;text-align:center;color:#444;height:45px;overflow:hidden;margin:5px 0 20px}.box-body-deg h2 a{color:#444}.snippet-material,#sidebar-blanter,.label_text,span.fi,.hfeed div.clear:nth-of-type(1){display:none}img.authoravatar{border-radius:100%;float:left;margin:0 10px 0 0}.tanggalx{padding:15px 15px 0;border-top:1px solid #ddd;margin:0 -15px;overflow:hidden}.tanggal abbr{color:#777;border-bottom:0;text-decoration:none;font-size:12px}.tanggal i{color:#777;font-size:13px;margin:0 5px 0 0}a.g-profile{color:#333;font-weight:500;font-size:14px}.blanterl{float:left;width:150px}.label-info{float:right;display:grid}.label-info a:nth-child(n+2){display:none}.label-info a{font-size:13px;margin:0 0 5px;padding:5px 7px;font-weight:500;border:1px solid #ddd;text-align:center;border-radius:5px}.overlayx{background:linear-gradient(0deg,rgba(0,0,0,0.76),rgba(255,255,255,0));position:absolute;width:100%;height:100%;z-index:1}#featuredblanter{margin:15px auto 20px;font-family:&#39;Roboto&#39;,sans-serif}#fancy *{-moz-box-sizing:border-box;-webkit-box-sizing:border-box;box-sizing:border-box}ul.randomnya{display:grid;grid-template-columns:1fr 1fr;grid-gap:20px;margin:0;list-style:none}#fancy li{background:#eee;position:relative;height:305px;overflow:hidden;border-radius:10px;box-shadow:0 25px 20px -20px rgba(0,0,0,.3),0 0 15px rgba(0,0,0,.06)}#fancy img{width:100%;transition:all .3s ease-in-out;height:100%}#fancy li:hover img{transform:scale(1.1)}#fancy h4{position:absolute;bottom:15px;text-align:center;left:20px;right:20px;z-index:1;color:#fff;font-family:&#39;Google Sans&#39;,Arial;font-weight:500}#blog-pager span,a.js-load{display:inline-block;background:#fff;color:#1a73e8;margin:15px 0;padding:8px 25px;border-radius:5px;font-weight:500;box-shadow:0 1px 2px 0 rgba(60,64,67,.30),0 2px 6px 2px rgba(60,64,67,.15)}a.js-load:hover{box-shadow:0 1px 3px 0 rgba(60,64,67,.30), 0 4px 8px 3px rgba(60,64,67,.15)}.js-load i{color:#1a73e8;line-height:20px;padding:5px 5px 5px 0;margin-right:7px}.darkmode .popular-box .PopularPosts .widget-content ul li{border-color:#444;background:#222}.darkmode .popular-box .PopularPosts .item-title a,.darkmode .popular-box h2{color:#fff}.popular-box .PopularPosts ul{display:grid;grid-template-columns:1fr 1fr 1fr 1fr 1fr;grid-gap:15px}.popular-box .PopularPosts .widget-content ul li{padding:10px;border:1px solid #ddd;border-radius:10px;transition:all .2s ease-in-out}.popular-box .PopularPosts .item-thumbnail{float:none;width:100%;margin:0}.popular-box .PopularPosts img{width:100%;height:118px;border-radius:7px;object-fit:cover}.popular-box .PopularPosts .widget-content ul li:hover{box-shadow:0 1px 3px 0 rgba(60,64,67,.30),0 4px 8px 3px rgba(60,64,67,.15)}.popular-box .PopularPosts .widget-content ul li{padding:10px;border:1px solid #ddd;border-radius:10px;transition:all .2s ease-in-out}.popular-box .PopularPosts .item-title{text-align:center;margin:5px 0}.popular-box .PopularPosts .item-title a{color:#444;font-size:13.5px;line-height:1.6}.popular-box{padding:10px 0 20px}.popular-box h2,.popular-box h3{font-size:17px;color:#1a73e8;font-weight:500;border-left:4px solid #1a73e8;margin:5px 0 20px;padding:0 15px}@media screen and (max-width:768px){.post-thumbnail img{height:150px}.blanterl{width:120px}.tanggal{display:none}img.authoravatar{width:25px}.label-info a{font-size:11px}.box-body-deg{padding-bottom:5px}.blog-posts{grid-template-columns:1fr 1fr}.popular-box .PopularPosts ul{grid-template-columns:1fr 1fr 1fr 1fr}.blanterimgthumb{width:100%}.popular-box .PopularPosts ul li:nth-child(5){display:none}#fancy li{height:auto}#fancy h4{font-size:15px;line-height:1.4}}@media screen and (max-width:680px){.popular-box .PopularPosts ul{grid-template-columns:1fr 1fr}}@media screen and (max-width:480px){.popular-box .PopularPosts img{height:110px}.blog-posts{grid-template-columns:1fr}#fancy h4{font-size:13px;bottom:5px}.post-thumbnail img{height:228px}}
</style>
</b:if>
<b:if cond='data:blog.pageType != &quot;index&quot;'>
<style type='text/css'>
/* CSS Post dan Halaman */
#content-material{padding:10px;width:1070px;max-width:100%}#material-breadcrumbs{margin:15px 0 0 15px}#main-material{width:65%;float:left;padding:0 10px 15px;border-radius:10px;color:#444;margin:10px;position:relative;overflow:hidden}#sidebar-blanter{width:30%;float:right;padding:0;margin:10px 0;position:relative;overflow:hidden}#sidebar-css h2,#sidebar-css h3{font-weight:500;color:#1a73e8;font-size:17px;margin:0 0 18px;padding:0 15px;border-left:4px solid #1a73e8}#img-pertamax img{width:100%;border-radius:10px}#img-pertamax{margin:0 0 10px;width:100%;overflow:hidden;position:relative}.post-body{font-family:&#39;Roboto&#39;,Google Sans,Arial;line-height:1.7;font-size:15px}#header-background{background:#008000;padding:40px;text-align:center;position:relative;overflow:hidden;margin:-11px 0 15px;box-shadow:0 1px 20px 0 rgba(60,64,67,.42),0 1px 5px 1px rgba(60,64,67,.32)}#header-background h3{font-size:24px;line-height:1.5;font-weight:500;color:#fff;margin:20px 5px 30px}.headwrap{max-width:950px;width:100%;margin:0 auto;text-align:left}img.author-avatar{border-radius:100%;float:left;border:3px solid #fff;margin:0 7px 0 0}.vcard a{color:#fff}.post-author.vcard{line-height:3;float:left;font-size:15px;font-weight:500;color:#fff}.time-publish i{float:left;margin:0 7px 0 0}.time-publish abbr{text-decoration:none;border:none}.post-body .separator:nth-of-type(1){display:none}#sidebar-css .PopularPosts,#sidebar-css .tab .widget{padding:0}.PopularPosts li a{font-size:13.5px;font-weight:500;color:#444}.PopularPosts .widget-content ul li{padding:4px 0}#sidebar1 .widget-content{padding:4px}.PopularPosts .item-title{position:static;vertical-align:middle;display:table-cell;height:65px}ul#recent-ui{padding:0;list-style:none}#recent-ui a{font-size:14px;color:#444;background:#eee;padding:12px 20px;display:block;border-radius:30px}#recent-ui a:hover{color:#1a73e8;background:#fff;box-shadow:0 1px 2px 0 rgba(60,64,67,.30),0 1px 3px 1px rgba(60,64,67,.15)}.post-body code{background:#eee;font-size:13px;padding:3px 7px;border-radius:20px}.m div{padding:4px 0}pre{display:block;background:#eee;padding:12px;border-radius:10px;border-top:5px solid #ddd}.post-body ol{margin-left:2.5em}.media{position:relative;padding-bottom:56.25%;height:0;overflow:hidden}.media embed,.media iframe,.media object{position:absolute;top:0;left:0;width:100%;height:100%}
/* Tabs Widget */
#sidebar1-material .widget,.tabs-1{border:1px solid #ddd;padding:15px;border-radius:10px;margin:0 0 15px}.tabs ul{list-style:none;padding:0;margin:0}.tab h2{font-size:12px;font-weight:700;padding:5px 15px;display:block;line-height:37px;transition:all .4s ease-out}.tabs .widget{border:none!important}.tabs,.tab{margin:0;overflow:hidden}.tabs .tab{padding:5px}.tabs-menu{padding:0;margin:0}.tabs-menu li{margin-bottom:0;margin-top:0;font-size:12px;font-weight:500;line-height:37px;width:50%;height:50px;list-style:none;text-align:center;display:inline-block;padding:5px 0;color:#666;border-bottom:2px solid #ddd;cursor:pointer;position:relative;transition:all .1s ease-out}.tabs-menu li:last-child{border-right:0}.tabs-menu .active-tab{border-color:#1a73e8!important;transition:all .4s ease-in-out}.tabs-content{padding:10px;border-top:none;margin-bottom:15px}.tabs-content .sidebar li{margin:0;padding:0}.tabs-content .widget li{color:#333;float:none!important;padding:0 20px}.tabs-content .widget ul{color:#333;overflow:visible}.tabs-menu li.tab-1:before{font-family:&quot;Font Awesome 5 Free&quot;;content:&quot;\f005&quot;;overflow:hidden;width:100%;float:left;margin:7px 0 0;font-size:20px}.tabs-menu li.tab-2:before{font-family:&quot;Font Awesome 5 Free&quot;;content:&quot;\f02c&quot;;overflow:hidden;width:100%;float:left;margin:7px 0 0;font-size:20px;font-weight:700}.tabs-menu li.active-tab span{opacity:1;bottom:-5px;color:#1a73e8}.tabs-menu li.active-tab:before{margin:0;color:#1a73e8!important}.tabs-menu li span{margin-left:2px;font-size:10px;letter-spacing:.7px;text-transform:uppercase;font-family:&#39;Roboto&#39;,Arial;position:absolute;width:100%;bottom:10px;opacity:0;left:0;font-weight:600;transition:all .4s ease-in-out}.tabs-1{margin:0 0 15px;padding:0}.tabs-menu li:before{transition:all .3s ease-in-out}#HTML6{width:100%;max-width:289px}#HTML6.scroll{top:20px}#HTML6.scroll.no-scroll{top:90px}
/* Share */
.share-post{text-align:center;overflow:hidden;border-top:1px solid #eee;margin-bottom:20px;margin-top:15px;padding:14px 0}.share-post ul{padding:0;margin:10px auto;display:grid;grid-template-columns:1fr 1fr 1fr 1fr 1fr;max-width:100%}.share-post li{margin:0;padding:0;list-style:none;position:relative}.share-post li a{padding:12px 5px;margin-right:4px;border-radius:50px;text-align:center;box-shadow:0 3px 4px 0 rgba(0,0,0,.08),0 2px 7px 0 rgba(0,0,0,.08),0 3px 2px -3px rgba(0,0,0,.09);color:#fff;display:block;font-size:13px;transition:all .6s ease-out}.share-post b{font-weight:500}.share-post li a:hover{box-shadow:0 2px 5px 0 rgba(0,0,0,.16),0 2px 10px 0 rgba(0,0,0,.12)}.share-post li .twitter{background-color:#1da1f2}.share-post li .facebook{background-color:#4867aa}.share-post li .xmail{background-color:#650582}.share-post li .pinterest{background-color:#c82828}.share-post li .wa{background:#0dc143}.share-post li .tumblr{background-color:rgba(48,78,108,.98)}.share-post li .facebook:hover,.share-post li .gplus:hover,.share-post li .pinterest:hover,.share-post li .tumblr:hover,.share-post li .twitter:hover{color:#fff}.share-post li:last-child{margin-right:0}.share-post li .fa:before{top:0;left:0;display:inline-block;padding:5.5px 12px;font-family:fontawesome;text-align:center;color:#fff;line-height:20px;font-size:17px;transition:all .6s ease-out}.share-post i{display:initial;font-size:18px;margin:0 -5px 0 20px;float:left}.spanshare{text-align:center;font-size:15px;text-transform:uppercase;font-weight:500}
/* Table */
.post-body table td,.post-body table caption{padding:10px;background:#f9f9f9;text-align:left;vertical-align:top}.post-body table th{background:#e6e6e6;padding:10px;text-align:left;vertical-align:top}.post-body td,.post-body th{vertical-align:top;text-align:left;font-size:13px;padding:3px 5px}.post-body table tr:nth-child(even) &gt; td{background-color:#f1f1f1}.post-body th{background:#fff;font-weight:400;text-transform:uppercase;font-size:14px}.post-body td a{font-size:85%;float:right;display:inline-block}.post-body td a[target=&quot;_blank&quot;]{background:#1a73e8;color:#fff;padding:2px 7px;border-radius:3px}.post-body table.tr-caption-container,.post-body table.tr-caption-container img,.post-body img{max-width:100%;width:auto;height:auto}.post-body td.tr-caption{font-size:80%;padding:8px!important}table{max-width:100%;width:100%;margin:1.5em auto}.authorboxwrap{box-shadow:0 1px 2px 0 rgba(60,64,67,.30),0 1px 3px 1px rgba(60,64,67,.15);padding:20px;border-radius:10px;margin:0 0 20px}.avatar-container{float:left;margin:0 15px 0 0}img.author_avatar{border-radius:100%}.authorboxwrap h5{font-weight:500;font-size:17px}.authorboxwrap p{font-size:14px;line-height:1.6}
/* Comments */
#comments{line-height:1.4em;margin:0;position:relative;border-radius:10px;border:1px solid #ddd;overflow:hidden}.menu-komentar{background:#1a73e8;overflow:hidden;padding:0 20px;height:50px;line-height:50px}#comments h3 i{line-height:1.7;padding:5px 15px 5px 0;float:left}#comments h3{float:left;font-size:14px;line-height:3.5;text-transform:uppercase;font-weight:500;font-family:&#39;Google Sans&#39;,Josefin Sans,Arial;color:#fff;margin:0}#showkomentarmenu{font-size:20px;padding:10px 20px;border-radius:100%;color:#fff;float:right;margin:-5px -25px 0 0}#komentarmenu{font-family:&#39;Google Sans&#39;,Arial;display:none;position:absolute;background:#fff;text-transform:none!important;list-style:none;right:35px;top:45px;width:160px;transition:all .5s cubic-bezier(0.07,0.68,0.35,1.04);z-index:9;overflow:hidden;box-shadow:0 5px 5px 0 rgba(0,0,0,0.16),0 2px 10px 0 rgba(0,0,0,0.12);border-radius:7px}#komentarmenu li{width:100%;margin:0;padding:0}#komentarmenu li a{padding:8px 15px;width:100%;font-weight:400;color:#666;font-size:13px!important}#komentarmenu li a:hover{background:#eee}#comments .avatar-image-container img{position:relative;width:42px;height:42px;max-width:42px;max-height:42px;background:#1a73e8}#comments .avatar-image-container:before{content:&#39;&#39;;position:absolute;width:20px;height:20px;background:url(&quot;data:image/svg+xml,<svg fill='white' height='24' viewBox='0 0 24 24' width='24' xmlns='http://www.w3.org/2000/svg'><path d='M12 12c2.21 0 4-1.79 4-4s-1.79-4-4-4-4 1.79-4 4 1.79 4 4 4zm0 2c-2.67 0-8 1.34-8 4v2h16v-2c0-2.66-5.33-4-8-4z'/><path d='M0 0h24v24H0z' fill='none'/></svg>&quot;) center center no-repeat;left:12px;top:10px}img[src=&#39;//resources.blogblog.com/img/blank.gif&#39;]{position:unset!important}#comments .avatar-image-container{position:relative;float:left;margin:15px 30px 15px 15px;width:42px;height:42px;max-width:42px;max-height:42px;padding:0;border-radius:100%;overflow:hidden}.comment-content{display:inline-block;max-width:80%;font-size:14px;padding:17px 17px 42px;margin:5px 0;border-radius:10px;position:relative;background:#eee;color:#444;border-top-left-radius:0}.comment-content:before{content:&quot;&quot;;width:0;height:0;position:absolute;top:0;left:-15px;border-width:8px;border-style:solid;border-color:#eee #eee transparent transparent;display:block}.comment-content:after{content:&quot;&quot;;width:0;height:0;position:absolute;top:0;right:100%;border-width:7px;border-style:solid;border-color:#eee #eee transparent transparent;display:block}.comment-actions a{color:#000;background:#fff;text-decoration:none;font-weight:400;font-size:12px;padding:2px 8px!important;margin:-10px 30px 0;display:table;border-radius:20px}a.comment-reply{position:absolute;bottom:20px;left:25px;display:inline-block}img.comment_emo{margin:0;padding:0;vertical-align:middle;width:24px;height:24px}.comment-thread .user a,.comment-thread cite.user{font-weight:500!important;color:#000;padding:0;font-size:13.5px;text-decoration:none;font-style:normal}.comment-thread .datetime a{font-size:12px;color:#555;display:none}.comments .comments-content .comment-thread ol{margin:0}.comment-replies .comment-content{padding:17px}li.comment{list-style:none;margin:0 0 0 15px !important;padding:0!important}span.thread-toggle{font-weight:500;border-radius:20px;border:1px solid #ddd;padding:5px 10px;margin:-10px 0 10px;font-size:14px}iframe#comment-editor,#top-ce iframe,.comment-replybox-single iframe{min-height:160px;width:100%;margin:15px 0}#comments .pencet{display:inline-block;color:#333;margin:0;padding:5px 13px;background-color:#fff;font-size:13px;line-height:2.2;border-radius:5px;margin-right:8px;font-weight:500;text-transform:none;text-decoration:none;outline:none;box-shadow:0 1px 2px 0 rgba(60,64,67,.302),0 1px 3px 1px rgba(60,64,67,.149);cursor:pointer}.pencet i{float:left;margin:0 7px 0 0;background:#1a73e8;color:#fff;padding:4px;border-radius:100%;font-size:20px}.google_emo .item{float:left;width:40px;text-align:center;height:40px;margin:10px 5px 0 0}.google_emo,span.bcm{background:#fff;padding:15px;display:block;margin:0 0 10px;border-radius:5px}.google_emo{overflow:hidden;padding:5px 15px 20px}.google_emo,.pesan-komentar{display:none;clear:both;height:auto}.google_emo span{display:block;font-weight:700;font-size:11px;letter-spacing:1px}#top-continue.hidden{display:block}.idbpesan{cursor:auto;position:relative;background:#eaeaea;padding:20px;border-radius:10px;color:#333;margin:0 20px;margin-top:50px;font-size:14px;font-family:&#39;Google Sans&#39;,Helvetica,Arial,sans-serif;line-height:1.5em;margin-bottom:20px;transition:all .3s ease-out}.comments .continue a{display:none}#comments .comments-content .icon.blog-author{width:18px;height:18px;margin-left:5px;vertical-align:0;display:inline-block;background:url(&quot;data:image/svg+xml,<svg height='24' viewBox='0 0 24 24' width='24' xmlns='http://www.w3.org/2000/svg'><path d='M12 5.9c1.16 0 2.1.94 2.1 2.1s-.94 2.1-2.1 2.1S9.9 9.16 9.9 8s.94-2.1 2.1-2.1m0 9c2.97 0 6.1 1.46 6.1 2.1v1.1H5.9V17c0-.64 3.13-2.1 6.1-2.1M12 4C9.79 4 8 5.79 8 8s1.79 4 4 4 4-1.79 4-4-1.79-4-4-4zm0 9c-2.67 0-8 1.34-8 4v3h16v-3c0-2.66-5.33-4-8-4z'/><path d='M0 0h24v24H0z' fill='none'/></svg>&quot;) center center no-repeat}.comments .comment-replybox-single{width:90%}.item-control.blog-admin{position:absolute;top:70px;left:-67px}.item-control.blog-admin a{background:#e21616;color:#fff;display:block!important}iframe#comment-editor{width:94%;margin:5px 20px}
/* Post Dark Mode */
.darkmode .tabs-menu li,.darkmode pre,.darkmode .share-post{border-color:#555}.darkmode #header-background{background:#222;box-shadow:none;border-bottom:2px solid #333}.darkmode #sidebar-css h2,.darkmode #sidebar-css h3,.darkmode .comment-thread .user a,.darkmode .comment-thread cite.user,.darkmode .post-author.vcard{color:#e8eaed}.darkmode .addcomment,.darkmode .comment-content,.darkmode .time-publish,.darkmode span.thread-toggle,.darkmode .idbpesan,.darkmode #recent-ui a,.darkmode blockquote{background:#444;color:#e8eaed;border-color:#555}.darkmode #sidebar-css .tabs-1,.darkmode #sidebar-css .widget{background:#222;border-color:#333;color:#ddd}.darkmode .input-field input,.darkmode .input-field label,.darkmode .input-field textarea{background:#222!important}.darkmode .post-outer{background:0 0}.darkmode .authorboxwrap,.darkmode li.related-post-item,.darkmode .google_emo,.darkmode span.bcm{background:#333;border:1px solid #555}.darkmode #related-post,.darkmode .post{background:#222;padding:10px 10px 15px;border:1px solid #333;border-radius:10px;margin:0 0 20px}.darkmode .menu-komentar,.darkmode .post-body table th,.darkmode .post-body code,.darkmode pre{background:#555}.darkmode .post-body table tr:nth-child(even)&gt;td{background-color:#444}.darkmode .post-body table td,.post-body table caption{background:#666}.darkmode #komentarmenu,.darkmode .breadcrumbs a,.darkmode span.judulb{background:#333;color:#e8eaed}.darkmode #komentarmenu li a,.darkmode .PopularPosts li a,.darkmode .comment-thread .datetime a,.darkmode .idb-pager li i,.darkmode .related-post-item-tooltip a,.darkmode .tabs-menu li:before{color:#e8eaed}.darkmode .related-post h4{margin:0 0 .6em}.darkmode #comments{background:#222;border-color:#333}.darkmode .comment-content:after,.darkmode .comment-content:before{border-color:#444 #444 transparent transparent}.darkmode .comment-actions a{background:#777;color:#fff}.darkmode #comments .pencet{background-color:#333;color:#eee}.darkmode #comments a{color:#eee}.darkmode .icon.blog-author{background-color:#fff!important;border-radius:100%}
/* Media Responsive */
@media screen and (min-width:1024px) and (max-width:1100px){#content-material{max-width:95%}}@media screen and (max-width:768px){.darkmode #related-post,.darkmode .post{background:#111;border-color:#111;padding:10px 0 15px}#HTML6{width:auto;max-width:100%}.share-post i{margin:0;float:none}.share-post b{display:none}#header-background h3{margin:70px 0 20px}#main-material,#sidebar-blanter{width:auto;float:none}.post-author.vcard{float:none;margin:0 0 20px;width:100%}#content-material{max-width:95%}#main-material{padding:10px 0 15px!important;background:transparent!important;border:none!important}}@media screen and (max-width:680px){a.addcomment,.time-publish,#comments .pencet.fbl{display:none}img.related-post-item-thumbnail{height:110px}.comment-content{max-width:67%}#HTML6.scroll,#HTML6.scroll.no-scroll{top:0}.post-body{font-size:16px}}
</style>
</b:if>
<script src='https://ajax.googleapis.com/ajax/libs/jquery/3.1.0/jquery.min.js'/>
</head>
<body itemscope='itemscope' itemtype='https://schema.org/WebPage'>
<b:section id='license' maxwidgets='1' name='License' showaddelement='false'>
  <b:widget id='HTML99' locked='true' title='License' type='HTML' version='2' visible='true'>
    <b:widget-settings>
      <b:widget-setting name='content'>NaRbNGZ8LGZ8NaN8NqRcMWRdMTgkynweAnUawDgs</b:widget-setting>
    </b:widget-settings>
    <b:includable id='main'>
<div class='license-code'><data:content/></div>
</b:includable>
  </b:widget>
</b:section>
<div id='blanter-loader'><svg height='50px' version='1' viewbox='0 0 16 16' width='50px' xmlns='http://www.w3.org/2000/svg'><g class='qp-circular-loader'><path class='qp-circular-loader-path' d='M 8,1.125 A 6.875,6.875 0 1 1 1.125,8' fill='none' stroke-linecap='round' stroke-width='2.25'/></g></svg></div>
<header class='float_material' id='header-material' itemscope='itemscope' itemtype='https://schema.org/WPHeader'>
<a class='toggleMenu ripple' href='javascript:;' title='Navigation'><i class='material-icons'>&#58834;</i></a>
<a class='ripple' href='javascript:;' id='showsearch' title='Search'><i class='material-icons'>&#59574;</i></a>
<a class='ripple' href='javascript:;' id='showmenu' title='Tiny Nav'><i class='material-icons'>&#58836;</i></a>
<a class='dialogUi ripple' href='javascript:;' id='dui' title='Notification'><i class='material-icons'>notifications</i></a>
<b:section class='header' id='header' maxwidgets='1' name='Header Title' showaddelement='no'>
  <b:widget id='Header1' locked='true' title='KARTUPAKET.COM (Header)' type='Header' version='1'>
    <b:widget-settings>
      <b:widget-setting name='displayUrl'/>
      <b:widget-setting name='displayHeight'>0</b:widget-setting>
      <b:widget-setting name='sectionWidth'>150</b:widget-setting>
      <b:widget-setting name='useImage'>false</b:widget-setting>
      <b:widget-setting name='shrinkToFit'>false</b:widget-setting>
      <b:widget-setting name='imagePlacement'>BEHIND</b:widget-setting>
      <b:widget-setting name='displayWidth'>0</b:widget-setting>
    </b:widget-settings>
    <b:includable id='main'>
  <b:if cond='data:useImage'>
    <b:if cond='data:imagePlacement == &quot;BEHIND&quot;'>
      <b:if cond='data:mobile'>
          <div id='header-inner'>
            <div class='titlematerial' style='background: transparent'>
              <h1 class='title' itemprop='headline' style='background: transparent; border-width: 0px'><b:include name='title'/></h1>
            </div>
            <b:include name='description'/>
          </div>
        <b:else/>
          <div expr:style='&quot;background-image: url(\&quot;&quot; + data:sourceUrl + &quot;\&quot;); &quot;                        + &quot;background-position: &quot;                        + data:backgroundPositionStyleStr + &quot;; &quot;                        + data:widthStyleStr                        + &quot;min-height: &quot; + data:height                        + &quot;_height: &quot; + data:height                        + &quot;background-repeat: no-repeat; &quot;' id='header-inner'>
            <div class='titlematerial' style='background: transparent'>
              <h1 class='title' itemprop='headline' style='background: transparent; border-width: 0px'><b:include name='title'/></h1>
            </div>
            <b:include name='description'/>
          </div>
        </b:if>
    <b:else/>
      <!--Show the image only-->
      <div id='header-inner'>
	    <b:if cond='data:blog.pageType != &quot;item&quot;'>
		  <b:if cond='data:blog.pageType != &quot;static_page&quot;'>
            <h1 style='text-indent:-9999px;margin:0 0 0 0;padding:0 0 0 0;height:0'><b:include name='title'/></h1>
          </b:if>
		</b:if>
        <a expr:href='data:blog.homepageUrl' style='display: block'>
          <img expr:alt='data:title' expr:height='data:height' expr:id='data:widget.instanceId + &quot;_headerimg&quot;' expr:src='data:sourceUrl' expr:width='data:width' style='display: block'/>
        </a>
        <!--Show the description-->
        <b:if cond='data:imagePlacement == &quot;description&quot;'>
          <b:include name='description'/>
		  <b:if cond='data:blog.pageType != &quot;item&quot;'>
		    <b:if cond='data:blog.pageType != &quot;static_page&quot;'>
              <h1 itemprop='headline' style='text-indent:-9999px;margin:0 0 0 0;padding:0 0 0 0;height:0'><b:include name='title'/></h1>
		    </b:if>
		  </b:if>
        </b:if>
      </div>
    </b:if>
  <b:else/>
    <!--No header image -->
    <div id='header-inner'>
      <div class='titlematerial'>  	
        <b:if cond='data:blog.pageType != &quot;item&quot;'>
		  <b:if cond='data:blog.pageType == &quot;static_page&quot;'>
             <p class='title' itemprop='headline'><b:include name='title'/></p>
		   <b:else/>
		     <h1 class='title' itemprop='headline'><b:include name='title'/></h1>
		   </b:if>
		<b:else/>
          <p class='title' itemprop='headline'><b:include name='title'/></p>
		</b:if>
	    <b:include name='description'/>
      </div>
	</div>
  </b:if>
</b:includable>
    <b:includable id='description'>
<div class='descriptionmaterial'><p class='description' itemprop='description'><span><data:description/></span></p></div>
</b:includable>
    <b:includable id='title'>
  <b:if cond='data:blog.url == data:blog.homepageUrl'>
    <data:title/>
  <b:else/>
    <a expr:href='data:blog.homepageUrl' expr:title='data:title' itemprop='url'><span itemprop='name'><data:title/></span></a>
  </b:if>
</b:includable>
  </b:widget>
</b:section>
<div id='searchmaterial'>
<div id='search-box' itemprop='mainEntity' itemscope='itemscope' itemtype='https://schema.org/WebSite'>
<meta expr:content='data:blog.homepageUrl' itemprop='url'/>
<form action='/search' id='searchblanterx' itemprop='potentialAction' itemscope='itemscope' itemtype='https://schema.org/SearchAction' method='get' onsubmit='return updateScript();' query-input='required'>
<meta content='/search?q={q}' itemprop='target'/>
<i class='blanter-icons material-icons'>&#59574;</i><a class='blanter-back' href='javascript:void;'><i class='material-icons'>close</i></a>
<input id='search-text' itemprop='query-input' name='q' placeholder='Pencarian' required='' type='text' value=''/></form></div>
</div>
</header>
<div id='menu-blanter' itemprop='mainEntity' itemscope='itemscope' itemtype='https://schema.org/SiteNavigationElement'>
<div id='menublanter'><input class='menu-btn' id='menu-btn' type='checkbox'/><label class='menu-icon' for='menu-btn'><span class='navicon'/></label>
<nav>
<b:section class='menu-widget' id='menu-widget' maxwidgets='1' name='Header Menu' showaddelements='none'>
  <b:widget id='HTML95' locked='true' title='Menu Items' type='HTML' version='2' visible='true'>
    <b:widget-settings>
      <b:widget-setting name='content'>&lt;ul class=&#39;blanterui&#39;&gt;
&lt;li&gt;&lt;a class=&#39;navhome&#39; href=&#39;/&#39; itemprop=&#39;url&#39; title=&#39;Home&#39;&gt;&lt;i class=&#39;material-icons&#39;&gt;home&lt;/i&gt;&lt;span itemprop=&#39;name&#39;&gt;Home&lt;/span&gt;&lt;/a&gt;&lt;/li&gt;
&lt;li&gt;&lt;a href=&#39;https://www.kartupaket.com/search/label/Paket Internet&#39; itemprop=&#39;url&#39; title=&#39;Tech News&#39;&gt;&lt;span itemprop=&#39;name&#39;&gt;Paket Internet&lt;/span&gt;&lt;/a&gt;&lt;/li&gt;
&lt;li&gt;&lt;a href=&#39;#&#39; itemprop=&#39;url&#39; title=&#39;World&#39;&gt;&lt;span itemprop=&#39;name&#39;&gt;World&lt;/span&gt;&lt;/a&gt;&lt;/li&gt;
&lt;li&gt;&lt;a href=&#39;#&#39; itemprop=&#39;url&#39; title=&#39;Friends&#39;&gt;&lt;span itemprop=&#39;name&#39;&gt;Friends&lt;/span&gt;&lt;/a&gt;&lt;/li&gt;
&lt;li&gt;&lt;a href=&#39;#&#39; itemprop=&#39;url&#39; title=&#39;Favorites&#39;&gt;&lt;span itemprop=&#39;name&#39;&gt;Favorites&lt;/span&gt;&lt;/a&gt;&lt;/li&gt;
&lt;li&gt;&lt;a href=&#39;#&#39; itemprop=&#39;url&#39; title=&#39;Developer&#39;&gt;&lt;span itemprop=&#39;name&#39;&gt;Developer&lt;/span&gt;&lt;/a&gt;&lt;/li&gt;
&lt;li&gt;&lt;a href=&#39;#&#39; itemprop=&#39;url&#39; title=&#39;More Menu&#39;&gt;&lt;span itemprop=&#39;name&#39;&gt;Lain-Lain&lt;/span&gt;&lt;/a&gt;
 &lt;ul&gt;
  &lt;li&gt;&lt;a href=&#39;/p/disclaimer-for-kartupaket.html&#39; itemprop=&#39;url&#39; title=&#39;Disclaimer&#39;&gt;&lt;span itemprop=&#39;name&#39;&gt;Disclaimer&lt;/span&gt;&lt;/a&gt;&lt;/li&gt;
  &lt;li&gt;&lt;a href=&#39;/p/sitemap.html&#39; itemprop=&#39;url&#39; title=&#39;Sitemap&#39;&gt;&lt;span itemprop=&#39;name&#39;&gt;Sitemap&lt;/span&gt;&lt;/a&gt;&lt;/li&gt;
 &lt;/ul&gt;
&lt;/li&gt;
&lt;ul id=&#39;dark-myar&#39; title=&#39;Dark Mode&#39;&gt;&lt;/ul&gt;
&lt;/ul&gt;</b:widget-setting>
    </b:widget-settings>
    <b:includable id='main'>
                    <!-- only display title if it's non-empty -->
                    <b:if cond='data:title != &quot;&quot;'>
                      <h2 class='title'><data:title/></h2>
                    </b:if>
                    <div class='widget-content'>
                      <data:content/>
                    </div>
                  </b:includable>
  </b:widget>
</b:section>
</nav></div></div>
<div id='slidemenu'><nav><div id='mobile-menu'/>
<b:section class='slide-widget' id='slide-widget' maxwidgets='1' name='Slide Menu' showaddelements='none'>
  <b:widget id='HTML96' locked='true' title='Menu Items' type='HTML' version='2' visible='true'>
    <b:widget-settings>
      <b:widget-setting name='content'><![CDATA[<p style="text-align: center;"><br /></p><p style="text-align: center;">Slot Iklan</p>]]></b:widget-setting>
    </b:widget-settings>
    <b:includable id='main'>
                    <!-- only display title if it's non-empty -->
                    <b:if cond='data:title != &quot;&quot;'>
                      <h2 class='title'><data:title/></h2>
                    </b:if>
                    <div class='widget-content'>
                      <data:content/>
                    </div>
                  </b:includable>
  </b:widget>
</b:section>
</nav></div>
<div id='headermenu'>
<li><a class='e-waves fbx' href='https://web.facebook.com/' itemprop='url' title='Facebook'><i class='fab fa-facebook'/><span itemprop='name'>Facebook</span></a></li>
<li><a class='e-waves twx' href='https://twitter.com/' itemprop='url' title='Twitter'><i class='fab fa-twitter'/><span itemprop='name'>Twitter</span></a></li>
<li><a class='e-waves ytx' href='https://www.youtube.com/' itemprop='url' title='Youtube'><i class='fab fa-youtube'/><span itemprop='name'>Youtube</span></a></li>
<li><a class='e-waves inx' href='https://www.instagram.com/' itemprop='url' title='Instagram'><i class='fab fa-instagram'/><span itemprop='name'>Instagram</span></a></li>
</div>
<div class='clear'/>
<div id='outer-material'>
<div itemscope='itemscope' itemtype='https://schema.org/Blog'>
<b:if cond='data:blog.pageType != &quot;index&quot;'>
<div id='header-background'>
  <h3><data:blog.pageName/></h3>
  <div class='headwrap'><div id='heretop'/></div>
</div>
</b:if>
<div id='content-material'>
<b:if cond='data:blog.pageType != &quot;error_page&quot;'>
<b:if cond='data:view.isHomepage'>

</b:if>
<b:if cond='data:view.isSearch'><b:else/>
<b:section class='largebanner' id='largebanner' maxwidgets='1' name='Banner Ads 970x90' showaddelement='yes'>
  <b:widget id='HTML1' locked='false' title='' type='HTML'>
    <b:widget-settings>
      <b:widget-setting name='content'>&lt;div&gt;&lt;br /&gt;&lt;/div&gt;&lt;div&gt;&lt;br /&gt;&lt;/div&gt;&lt;!-- Kartupaket.com --&gt;
&lt;div style=&quot;text-align: center;&quot;&gt;&lt;span style=&quot;color: green;&quot;&gt;Advertising&lt;/span&gt;&lt;/div&gt;&lt;ins class=&quot;adsbygoogle&quot;
     style=&quot;display:block&quot;
     data-ad-client=&quot;ca-pub-3743380332259935&quot;
     data-ad-slot=&quot;5943850498&quot;
     data-ad-format=&quot;auto&quot;
     data-full-width-responsive=&quot;true&quot;&gt;&lt;/ins&gt;
&lt;script&gt;
     (adsbygoogle = window.adsbygoogle || []).push({});
&lt;/script&gt;</b:widget-setting>
    </b:widget-settings>
    <b:includable id='main'>
  <!-- only display title if it's non-empty -->
  <b:if cond='data:title != &quot;&quot;'>
    <h2 class='title'><data:title/></h2>
  </b:if>
  <div class='widget-content'>
    <data:content/>
  </div>

  <b:include name='quickedit'/>
</b:includable>
  </b:widget>
</b:section>
</b:if></b:if>
<div class='clear'/>
<b:if cond='data:blog.pageType != &quot;error_page&quot;'>
<b:if cond='data:view.isPost'>
<div id='material-breadcrumbs'/>
</b:if>
<div id='main-material' itemscope='itemscope' itemtype='https://schema.org/Blog' role='main'>
<b:section class='main' id='main' maxwidgets='1' name='Post Settings' showaddelement='no'>
  <b:widget id='Blog1' locked='true' title='Posting Blog' type='Blog' version='1'>
    <b:widget-settings>
      <b:widget-setting name='showDateHeader'>true</b:widget-setting>
      <b:widget-setting name='style.textcolor'>#2196f3</b:widget-setting>
      <b:widget-setting name='showShareButtons'>true</b:widget-setting>
      <b:widget-setting name='authorLabel'>By</b:widget-setting>
      <b:widget-setting name='showCommentLink'>true</b:widget-setting>
      <b:widget-setting name='style.urlcolor'>#212121</b:widget-setting>
      <b:widget-setting name='showAuthor'>true</b:widget-setting>
      <b:widget-setting name='disableGooglePlusShare'>true</b:widget-setting>
      <b:widget-setting name='style.linkcolor'>#222222</b:widget-setting>
      <b:widget-setting name='style.unittype'>TextAndImage</b:widget-setting>
      <b:widget-setting name='style.bgcolor'>#ffffff</b:widget-setting>
      <b:widget-setting name='timestampLabel'>-</b:widget-setting>
      <b:widget-setting name='showAuthorProfile'>true</b:widget-setting>
      <b:widget-setting name='style.layout'>1x1</b:widget-setting>
      <b:widget-setting name='showLabels'>true</b:widget-setting>
      <b:widget-setting name='showLocation'>false</b:widget-setting>
      <b:widget-setting name='showTimestamp'>true</b:widget-setting>
      <b:widget-setting name='postsPerAd'>1</b:widget-setting>
      <b:widget-setting name='showBacklinks'>false</b:widget-setting>
      <b:widget-setting name='style.bordercolor'>#ffffff</b:widget-setting>
      <b:widget-setting name='showInlineAds'>false</b:widget-setting>
      <b:widget-setting name='showReactions'>false</b:widget-setting>
    </b:widget-settings>
    <b:includable id='main' var='top'>
<b:include data='posts' name='breadcrumb'/><div class='displaynone'>MASIGNASUKAv102</div><span id='responsive'><data:blog.blogId/></span><b:if cond='data:mobileindex'><div class='blog-posts hfeed'><b:loop values='data:posts' var='post'><div expr:onclick='data:post.indexOnclick'><b:include data='post' name='mobile-index-post'/></div><b:if cond='data:post.trackLatency'><data:post.latencyJs/></b:if></b:loop><b:if cond='data:numPosts != 0'/></div><b:else/><div class='blog-posts hfeed'><b:include data='top' name='status-message'/><data:defaultAdStart/><b:loop values='data:posts' var='post'><div class='post-outer'><b:include data='post' name='post'/><b:if cond='data:blog.pageType == &quot;static_page&quot;'><b:include data='post' name='comments'/></b:if><b:if cond='data:blog.pageType == &quot;item&quot;'><b:include data='post' name='comments'/></b:if></div><b:if cond='data:post.includeAd'><b:if cond='data:post.isFirstPost'><data:defaultAdEnd/><b:else/><data:adEnd/></b:if><b:if cond='data:mobile == &quot;false&quot;'><div class='inline-ad'><data:adCode/></div></b:if><data:adStart/></b:if><b:if cond='data:post.trackLatency'><data:post.latencyJs/></b:if></b:loop><b:if cond='data:numPosts != 0'/><data:adEnd/></div></b:if><b:if cond='data:blog.pageType == &quot;index&quot;'><b:include name='nextprev'/><b:else/><b:if cond='data:blog.pageType == &quot;archive&quot;'><b:include name='nextprev'/><b:else/><b:if cond='data:blog.homepageUrl != data:blog.url'><b:include name='nextprev'/></b:if></b:if></b:if><!-- DESIGN BY WWW.IDBLANTER.COM -->
</b:includable>
    <b:includable id='backlinkDeleteIcon' var='backlink'/>
    <b:includable id='backlinks' var='post'>
  <a name='links'/><h4><data:post.backlinksLabel/></h4>
  <b:if cond='data:post.numBacklinks != 0'>
    <dl class='comments-block' id='comments-block'>
      <b:loop values='data:post.backlinks' var='backlink'>
        <div class='collapsed-backlink backlink-control'>
          <dt class='comment-title'>
            <span class='backlink-toggle-zippy'>&#160;</span>
            <a expr:href='data:backlink.url' rel='dofollow'><data:backlink.title/></a>
            <b:include data='backlink' name='backlinkDeleteIcon'/>
          </dt>
          <dd class='comment-body collapseable'>
            <data:backlink.snippet/>
          </dd>
          <dd class='comment-footer collapseable'>
            <span class='comment-author'><data:post.authorLabel/> <data:backlink.author/></span>
            <span class='comment-timestamp'><data:post.timestampLabel/> <data:backlink.timestamp/></span>
          </dd>
        </div>
      </b:loop>
    </dl>
  </b:if>
  <p class='comment-footer'>
    <a class='comment-link' expr:href='data:post.createLinkUrl' expr:id='data:widget.instanceId + &quot;_backlinks-create-link&quot;' rel='external dofollow' target='_blank'><data:post.createLinkLabel/></a>
  </p>
</b:includable>
    <b:includable id='breadcrumb' var='posts'>
<br/><b:if cond='data:blog.pageType == &quot;item&quot;'>
<b:loop values='data:posts' var='post'>
<b:if cond='data:post.labels'>
<div class='breadcrumbs' itemscope='itemscope' itemtype='https://schema.org/BreadcrumbList'>
<span itemprop='itemListElement' itemscope='itemscope' itemtype='https://schema.org/ListItem'>
<a expr:href='data:blog.homepageUrl' itemprop='item' title='Home'>
<span itemprop='name'><i class='material-icons'>&#59530;</i> Home</span></a>
<meta content='1' itemprop='position'/>
</span>
<b:loop index='num' values='data:post.labels' var='label'>
<b>&#8250;</b><span class='labelb' itemprop='itemListElement' itemscope='itemscope' itemtype='https://schema.org/ListItem'><a expr:href='data:label.url + &quot;?&amp;max-results=9&quot;' expr:title='data:label.name' itemprop='item'><span itemprop='name'><data:label.name/></span>
</a><meta expr:content='data:num+2' itemprop='position'/>
</span>
<b:if cond='data:label.isLast != &quot;true&quot;'/>
</b:loop>
<b>&#8250;</b><span class='judulb'><data:post.title/></span>
</div>
</b:if>
</b:loop>
</b:if>
</b:includable>
    <b:includable id='comment-form' var='post'>
<div class='comment-form'>
    <a name='comment-form'/>
    <b:if cond='data:mobile'>
      <h4 id='comment-post-message'>
        <a expr:id='data:widget.instanceId + &quot;_comment-editor-toggle-link&quot;' href='javascript:void(0)'><data:postCommentMsg/></a></h4>
      <p><data:blogCommentMessage/></p>
      <data:blogTeamBlogMessage/>
      <a expr:href='data:post.commentFormIframeSrc' id='comment-editor-src'/>
      <iframe allowtransparency='true' class='blogger-iframe-colorize blogger-comment-from-post' frameborder='0' height='410' id='comment-editor' name='comment-editor' src='' style='display: none' width='100%'/>
    <b:else/>
      <h4 id='comment-post-message'><data:postCommentMsg/></h4>
<div id='threaded-comment-form'>
  <p><data:blogCommentMessage/>   </p>
      <data:blogTeamBlogMessage/>
      <a expr:href='data:post.commentFormIframeSrc' id='comment-editor-src'/>
      <iframe allowtransparency='true' class='blogger-iframe-colorize blogger-comment-from-post' frameborder='0' height='410' id='comment-editor' name='comment-editor' src='' width='100%'/>
      </div>
    </b:if>
    <data:post.cmtfpIframe/>
    <script type='text/javascript'>
      BLOG_CMT_createIframe(&#39;<data:post.appRpcRelayPath/>&#39;);
    </script>
<div class='comments-thanks'>Terima kasih atas komentar Anda</div>
<div class='clear'/> 
  </div>
</b:includable>
    <b:includable id='commentDeleteIcon' var='comment'/>
    <b:includable id='comment_count_picker' var='post'>
  <b:if cond='data:post.forceIframeComments'>
    <span class='cmt_count_iframe_holder' expr:data-count='data:post.numComments' expr:data-onclick='data:post.addCommentOnclick' expr:data-url='data:post.canonicalUrl'>
    </span>
  <b:else/>
    <b:if cond='data:post.commentSource == 1'>
      <span class='cmt_count_iframe_holder' expr:data-count='data:post.numComments' expr:data-onclick='data:post.addCommentOnclick' expr:data-url='data:post.canonicalUrl'>
      </span>
    <b:else/>
      <a class='comment-link' expr:href='data:post.addCommentUrl' expr:onclick='data:post.addCommentOnclick'>
        <data:post.commentLabelFull/>:
      </a>
    </b:if>
  </b:if>
</b:includable>
    <b:includable id='comment_picker' var='post'>
  <b:if cond='data:post.commentSource == 1'>
    <b:include data='post' name='iframe_comments'/>
  <b:else/>
    <b:if cond='data:post.showThreadedComments'>
      <b:include data='post' name='threaded_comments'/>
    <b:else/>
      <b:include data='post' name='comments'/>
    </b:if>
  </b:if>
</b:includable>
    <b:includable id='comments' var='post'>
<b:include data='post' name='threaded_comments'/>
</b:includable>
    <b:includable id='feedLinks'>
  <b:if cond='data:blog.pageType != &quot;item&quot;'> <!-- Blog feed links -->
    <b:if cond='data:feedLinks'>
      <div class='blog-feeds'>
        <b:include data='feedLinks' name='feedLinksBody'/>
      </div>
    </b:if>
    <b:else/>
    <div class='post-feeds'>
      <b:loop values='data:posts' var='post'>
        <b:if cond='data:post.allowComments'>
          <b:if cond='data:post.feedLinks'>
            <b:include data='post.feedLinks' name='feedLinksBody'/>
          </b:if>
        </b:if>
      </b:loop>
    </div>
  </b:if>
</b:includable>
    <b:includable id='feedLinksBody' var='links'>
</b:includable>
    <b:includable id='iframe_comments' var='post'>
  <b:if cond='data:post.allowIframeComments'>
    <script expr:src='data:post.iframeCommentSrc' type='text/javascript'/>
    <div class='cmt_iframe_holder' expr:data-href='data:post.url.canonical' expr:data-viewtype='data:post.viewType'/>

    <b:if cond='data:post.embedCommentForm == &quot;false&quot;'>
      <a expr:href='data:post.addCommentUrl' expr:onclick='data:post.addCommentOnclick'><data:postCommentMsg/></a>
    </b:if>
  </b:if>
</b:includable>
    <b:includable id='mobile-index-post' var='post'>
  <b:if cond='data:post.dateHeader'>
    <div class='mobile-index-date'>
      <div class='date-header'>
        <span><data:post.dateHeader/></span>
      </div>
    </div>
  </b:if>

  <div class='mobile-post-outer'>
    <div class='mobile-index-title-outer'>
      <h3 class='mobile-index-title entry-title'>
        <a href='javascript:void(0)'><data:post.title/></a>
      </h3>
    </div>

    <div>
      <div class='mobile-index-arrow'>
        <a href='javascript:void(0)'>&amp;rsaquo;</a>
      </div>

      <div class='mobile-post-contents'>
        <b:if cond='data:post.thumbnailUrl'>
          <div class='mobile-index-thumbnail'>
            <div class='Image'>
              <img expr:src='data:post.thumbnailUrl'/>
            </div>
          </div>
        </b:if>

        <div class='post-body'>
          <b:if cond='data:post.snippet'><data:post.snippet/></b:if>
        </div>
      </div>
      <div class='clear'/>
    </div>

    <div class='mobile-index-comment'>
      <b:if cond='data:blog.pageType != &quot;item&quot;'>
        <b:if cond='data:blog.pageType != &quot;static_page&quot;'>
          <b:if cond='data:post.allowComments'>
            <b:if cond='data:post.numComments != 0'>
              <a class='comment-link' expr:href='data:post.addCommentUrl' expr:onclick='data:post.addCommentOnclick'><b:if cond='data:post.numComments == 1'>1 <data:top.commentLabel/><b:else/><data:post.numComments/> <data:top.commentLabelPlural/></b:if></a>
            </b:if>
          </b:if>
        </b:if>
      </b:if>
    </div>
  </div>
</b:includable>
    <b:includable id='mobile-main' var='top'>
    <!-- posts -->
    <div class='blog-posts hfeed'>

      <b:include data='top' name='status-message'/>

      <b:if cond='data:blog.pageType == &quot;index&quot;'>
        <b:loop values='data:posts' var='post'>
          <b:include data='post' name='mobile-index-post'/>
        </b:loop>
      <b:else/>
        <b:loop values='data:posts' var='post'>
          <b:include data='post' name='mobile-post'/>
        </b:loop>
      </b:if>
    </div>

   <b:include name='mobile-nextprev'/>
</b:includable>
    <b:includable id='mobile-nextprev'>
  <div class='clear'/>
</b:includable>
    <b:includable id='mobile-post' var='post'>
  <div class='date-outer'>
    <b:if cond='data:post.dateHeader'>
      <h2 class='date-header'><span><data:post.dateHeader/></span></h2>
    </b:if>
    <div class='date-posts'>
      <div class='post-outer'>

        <div class='post hentry uncustomized-post-template'>
                    <b:if cond='data:post.title'>
            <h3 class='post-title entry-title'>
              <b:if cond='data:post.link'>
                <a expr:href='data:post.link'><data:post.title/></a>
              <b:else/>
                <b:if cond='data:post.url'>
                  <b:if cond='data:blog.url != data:post.url'>
                    <a expr:href='data:post.url'><data:post.title/></a>
                  <b:else/>
                    <data:post.title/>
                  </b:if>
                <b:else/>
                  <data:post.title/>
                </b:if>
              </b:if>
            </h3>
          </b:if>
          <div class='post-header'>
            <div class='post-header-line-1'/>
          </div>
          <div class='post-body entry-content' expr:id='&quot;post-body-&quot; + data:post.id'>
<data:post.body/>
            <div class='clear'/>
          </div>
<div class='post-info'>
<div class='post-info-icon admin'>
<a class='g-profile' expr:href='data:post.authorProfileUrl' rel='author' title='Author Profile'>
<span class='post-author vcard'><span class='fn' itemprop='name'><data:post.author/></span></span></a></div>
<b:if cond='data:blog.pageType != &quot;item&quot;'>
<b:if cond='data:blog.pageType != &quot;static_page&quot;'>
<div class='post-info-icon'>
<a class='updated' expr:href='data:post.url' rel='bookmark' title='permanent link'><abbr class='updated' expr:title='data:post.timestampISO8601' itemprop='datePublished dateModified'> <data:post.timestamp/></abbr></a></div> 
</b:if>
</b:if>
<b:if cond='data:blog.pageType == &quot;item&quot;'>
<div class='post-info-icon tanggal'>
<b:if cond='data:post.dateHeader'>
<a class='tanggal'><span><data:post.dateHeader/></span></a>
</b:if>     
</div> 
</b:if>
<div class='post-info-icon komentar'>
<b:if cond='data:post.allowComments'>
<a class='komentar' expr:href='data:post.addCommentUrl' expr:onclick='data:post.addCommentOnclick'><b:if cond='data:post.numComments == 1'>1 <data:top.commentLabel/><b:else/><data:post.numComments/> <data:top.commentLabelPlural/></b:if></a></b:if>
</div>
<b:if cond='data:blog.pageType == &quot;item&quot;'>
<span class='post-info-icon label'>
<b:if cond='data:post.labels'>
<data:postLabelsLabel/><b:loop values='data:post.labels' var='label'>
<a expr:href='data:label.url' rel='tag'><data:label.name/></a><b:if cond='data:label.isLast != &quot;true&quot;'>,</b:if>
</b:loop></b:if></span> 
</b:if>
<div class='clear'/>
</div>
</div>

        <b:if cond='data:blog.pageType == &quot;static_page&quot;'>
          <b:include data='post' name='comments'/>
        </b:if>
        <b:if cond='data:blog.pageType == &quot;item&quot;'>
         <b:include data='post' name='comments'/>
        </b:if>
      </div>
    </div>
  </div>
</b:includable>
    <b:includable id='nextprev'>
<b:if cond='data:blog.pageType != &quot;item&quot;'>
<b:if cond='data:blog.pageType != &quot;static_page&quot;'>
<div class='blog-pager' id='blog-pager'><b:if cond='data:newerPageUrl'><span id='blog-pager-newer-link'><a class='blog-pager-newer-link' expr:href='data:newerPageUrl' expr:id='data:widget.instanceId + &quot;_blog-pager-newer-link&quot;' expr:title='data:newerPageTitle'><data:newerPageTitle/></a></span></b:if><b:if cond='data:olderPageUrl'><span id='blog-pager-older-link'><a class='blog-pager-older-link' expr:href='data:olderPageUrl' expr:id='data:widget.instanceId + &quot;_blog-pager-older-link&quot;' expr:title='data:olderPageTitle'><data:olderPageTitle/></a></span></b:if><div class='mobile-link-button' id='blog-pager-home-link'><a class='home-link' expr:href='data:blog.homepageUrl' expr:title='data:homeMsg'><data:homeMsg/></a></div><div class='mobile-desktop-link'><a class='home-link' expr:href='data:desktopLinkUrl' expr:title='data:homeMsg'><data:desktopLinkMsg/></a></div></div></b:if></b:if><div class='clear'/>
</b:includable>
    <b:includable id='post' var='post'>
<article class='post hentry' expr:id='data:post.id' itemprop='blogPost' itemscope='itemscope' itemtype='https://schema.org/BlogPosting'>
<div itemType='https://schema.org/WebPage' itemprop='mainEntityOfPage' itemscope='itemscope'/><div itemprop='publisher' itemscope='itemscope' itemtype='https://schema.org/Organization'><div itemprop='logo' itemscope='itemscope' itemtype='https://schema.org/ImageObject'><meta content='https://4.bp.blogspot.com/-rmTjQDUOEHY/Wge2DnMAyPI/AAAAAAAAHxM/xObVDsgGbBwWmnCv4pL69vOIHldkqtKNACK4BGAYYCw/s1600/DuniaBlanterLogoNew.png' itemprop='url'/><meta content='600' itemprop='width'/><meta content='600' itemprop='height'/></div><meta expr:content='data:blog.title' itemprop='name'/></div>
<b:if cond='data:post.firstImageUrl'>
<div itemprop='image' itemscope='itemscope' itemtype='https://schema.org/ImageObject'><meta expr:content='data:post.firstImageUrl' itemprop='url'/><meta content='700' itemprop='width'/><meta content='700' itemprop='height'/></div>
<b:else/>
<div itemprop='image' itemscope='itemscope' itemtype='https://schema.org/ImageObject'><meta content='https://2.bp.blogspot.com/-LGfDcNv6jF0/Wm1S_ET-yyI/AAAAAAAAJFo/bOijmeJNpqsSoNTmPgwkQlKp0gjun9EKACLcBGAs/s340/blanterimage.png' itemprop='url'/><meta content='700' itemprop='width'/><meta content='700' itemprop='height'/></div>
</b:if>
<b:if cond='data:blog.pageType != &quot;item&quot;'><b:if cond='data:blog.pageType != &quot;static_page&quot;'/></b:if>
<b:if cond='data:blog.pageType == &quot;item&quot;'>
<b:if cond='data:post.title'>
<h1 class='post-title entry-title' itemprop='name headline'>
<b:if cond='data:post.link'>
<a expr:href='data:post.link' expr:title='data:post.title' itemprop='url'><data:post.title/></a>
<b:else/>
<b:if cond='data:post.url'>
<b:if cond='data:blog.url != data:post.url'>
<a expr:href='data:post.url' expr:title='data:post.title' itemprop='url'><data:post.title/></a>
<b:else/>
<data:post.title/>
</b:if>
<b:else/>
<data:post.title/>
</b:if>
</b:if>
</h1>
</b:if>
<div id='img-pertamax'>
<img class='firstimage lazy' expr:alt='data:post.title' expr:data-src='resizeImage(data:post.thumbnailUrl,600)' expr:title='data:post.title' itemprop='image' src='data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAAEAAAABCAYAAAAfFcSJAAAAAXNSR0IArs4c6QAAAARnQU1BAACxjwv8YQUAAAAJcEhZcwAADsQAAA7EAZUrDhsAAAANSURBVBhXYzh8+PB/AAffA0nNPuCLAAAAAElFTkSuQmCC'/>
<div class='whitecolumn' id='movetop'>
<div class='post-author vcard'>
<b:if cond='data:top.showAuthor'>
<b:if cond='data:post.authorProfileUrl'>
<span class='fn' itemprop='author' itemscope='itemscope' itemtype='https://schema.org/Person'>
<img class='author-avatar' expr:src='resizeImage(data:post.authorPhoto.url,40)' itemprop='image'/>
Posted by <a expr:href='data:post.authorProfileUrl' itemprop='url' rel='author' target='_blank' title='Author Profile'><span itemprop='name'><data:post.author/></span></a></span>
<b:else/>
<span class='fn' itemprop='name'><data:post.author/></span>
</b:if>
</b:if>
</div>
<a class='addcomment e-waves' href='#top-ce' title='Add Comments'><i class='fas fa-plus'/> Add Comments</a>
<div class='time-publish'>
<i class='material-icons'>&#59684;</i>
<abbr class='published updated timeago' expr:title='data:post.timestampISO8601' itemprop='datePublished dateModified'><data:post.dateHeader/></abbr>
</div>
</div></div><div class='clear'/>
</b:if>
<b:if cond='data:blog.pageType == &quot;static_page&quot;'>
<b:if cond='data:post.title'>
<h1 class='post-title entry-title' itemprop='name headline'>
<b:if cond='data:post.link'>
<a expr:href='data:post.link' expr:title='data:post.title' itemprop='url'><data:post.title/></a>
<b:else/>
<b:if cond='data:post.url'>
<b:if cond='data:blog.url != data:post.url'>
<a expr:href='data:post.url' expr:title='data:post.title' itemprop='url'><data:post.title/></a>
<b:else/>
<data:post.title/>
</b:if>
<b:else/>
<data:post.title/>
</b:if>
</b:if>
</h1>
</b:if></b:if>
<b:if cond='data:blog.pageType != &quot;item&quot;'>
<b:if cond='data:blog.pageType != &quot;static_page&quot;'>
<div class='post-body entry-content' expr:id='&quot;post-body-&quot; + data:post.id' itemprop='articleBody'>
<div class='box-deg'>
<b:if cond='data:post.url'>
<div class='post-thumbnail'>
<b:if cond='data:post.thumbnailUrl'>
<div class='blanterimgthumb e-waves waves-light'>
<a expr:href='data:post.url'><img class='lazy' expr:alt='data:post.title' expr:data-src='resizeImage(data:post.thumbnailUrl,340)' expr:title='data:post.title' height='74' src='data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAAEAAAABCAYAAAAfFcSJAAAAAXNSR0IArs4c6QAAAARnQU1BAACxjwv8YQUAAAAJcEhZcwAADsQAAA7EAZUrDhsAAAANSURBVBhXYzh8+PB/AAffA0nNPuCLAAAAAElFTkSuQmCC' width='74'/></a></div>
<b:else/>
<b:if cond='data:post.firstImageUrl'>
<div class='blanterimgthumb e-waves waves-light'><a expr:href='data:post.url'><img class='lazy' expr:alt='data:post.title' expr:data-src='resizeImage(data:post.firstImageUrl,340)' expr:title='data:post.title' height='74' src='data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAAEAAAABCAYAAAAfFcSJAAAAAXNSR0IArs4c6QAAAARnQU1BAACxjwv8YQUAAAAJcEhZcwAADsQAAA7EAZUrDhsAAAANSURBVBhXYzh8+PB/AAffA0nNPuCLAAAAAElFTkSuQmCC' width='74'/></a></div>
<b:else/>
<div class='blanterimgthumb e-waves waves-light'><a expr:href='data:post.url'><img class='lazy' data-src='https://2.bp.blogspot.com/-LGfDcNv6jF0/Wm1S_ET-yyI/AAAAAAAAJFo/bOijmeJNpqsSoNTmPgwkQlKp0gjun9EKACLcBGAs/s340/blanterimage.png' expr:alt='data:post.title' expr:title='data:post.title' height='74' src='data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAAEAAAABCAYAAAAfFcSJAAAAAXNSR0IArs4c6QAAAARnQU1BAACxjwv8YQUAAAAJcEhZcwAADsQAAA7EAZUrDhsAAAANSURBVBhXYzh8+PB/AAffA0nNPuCLAAAAAElFTkSuQmCC' width='74'/></a></div>
</b:if>
</b:if>
</div>
</b:if>
<div class='box-body-deg'>
<h2 class='post-title entry-title' itemprop='name headline'><b:if cond='data:post.link'>
<a expr:href='data:post.link' expr:title='data:post.title' itemprop='url'><data:post.title/></a>
<b:else/>
<b:if cond='data:post.url'>
<a expr:href='data:post.url' expr:title='data:post.title' itemprop='url'><data:post.title/></a>
<b:else/>
<data:post.title/>
</b:if>
</b:if>
</h2>
<div class='snippet-material' itemprop='description'><b:eval expr='snippet(data:post.snippet, {length: 90})'/></div>
<div class='tanggalx'><div class='blanterl'>
<b:if cond='data:top.showAuthor'>
<b:if cond='data:post.authorProfileUrl'>
<div class='fn madamx' itemprop='author' itemscope='itemscope' itemtype='https://schema.org/Person'>
<a expr:href='data:post.authorProfileUrl' target='blank' title='Author Profile'><meta expr:content='data:post.authorProfileUrl' itemprop='url'/><img alt='Author' class='authoravatar lazy' expr:data-src='resizeImage(data:post.authorPhoto.url,40)' itemprop='image' src='data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAAEAAAABCAYAAAAfFcSJAAAAAXNSR0IArs4c6QAAAARnQU1BAACxjwv8YQUAAAAJcEhZcwAADsQAAA7EAZUrDhsAAAANSURBVBhXYzh8+PB/AAffA0nNPuCLAAAAAElFTkSuQmCC'/><a class='g-profile' expr:href='data:post.authorProfileUrl' rel='author' target='_blank' title='Author Profile'><span itemprop='name'><data:post.author/></span></a></a></div>
<b:else/>
<span class='author-info'><span class='fn' itemprop='author' itemscope='itemscope' itemtype='https://schema.org/Person'><span itemprop='name'><data:post.author/></span></span></span></b:if>
</b:if>
<span class='dunia-blanter-info tanggal'><i class='far fa-clock'/><span itemprop='dateModified'><abbr class='published updated timeago' expr:title='data:post.timestampISO8601' itemprop='datePublished'><data:post.timestamp/></abbr></span></span></div>
<b:if cond='data:post.labels'>
<div class='label-info'><b:loop values='data:post.labels' var='label'><a expr:href='data:label.url + &quot;?max-results=6&quot;' rel='tag'><data:label.name/></a><b:if cond='data:label.isLast != &quot;true&quot;'/></b:loop></div></b:if></div></div></div><div class='clear'/></div>
</b:if>
</b:if>
<b:if cond='data:blog.pageType == &quot;item&quot;'>
<b:if cond='data:post.dateHeader'><div class='datex'/></b:if>
<div class='post-body entry-content' expr:id='&quot;post-body-&quot; + data:post.id'>
<!-- IKLAN ATAS POSTINGAN -->
<ins class='adsbygoogle' data-ad-client='ca-pub-3743380332259935' data-ad-format='link' data-ad-layout='in-article' data-ad-slot='9197407636' style='display:block; text-align:center;'/>
<script>
     (adsbygoogle = window.adsbygoogle || []).push({});
</script>  
<data:post.body/>
<!-- IKLAN BAWAH POSTINGAN -->
</div>
</b:if>
<b:if cond='data:blog.pageType == &quot;static_page&quot;'>
<b:if cond='data:post.dateHeader'><div class='datex'><div><data:post.dateHeader/></div></div></b:if>
<div class='post-body entry-content' expr:id='&quot;post-body-&quot; + data:post.id'>
<data:post.body/>
</div>
</b:if>
<b:if cond='data:blog.pageType == &quot;item&quot;'>
<div class='share-post'><div class='spanshare'>Share This</div><ul><li><a class='e-waves waves-light facebook' expr:href='&quot;https://www.facebook.com/sharer.php?u=&quot; + data:blog.url' rel='nofollow' target='_blank' title='Share To Facebook'><i class='fab fa-facebook'/> <b>Facebook</b></a></li><li><a class='e-waves waves-light twitter' expr:href='&quot;https://twitter.com/share?url=&quot; + data:post.url' rel='nofollow' target='_blank' title='Share To Twitter'><i class='fab fa-twitter'/> <b>Twitter</b></a></li><li><a class='e-waves waves-light xmail' expr:href='&quot;https://www.blogger.com/share-post.g?blogID=&quot; + data:blog.blogId + &quot;&amp;postID=&quot; + data:post.id + &quot;&amp;target=email&quot;' rel='nofollow' target='_blank' title='Share To Email'><i class='far fa-envelope'/> <b>Email</b></a></li><li><a class='e-waves waves-light pinterest' expr:href='&quot;https://pinterest.com/pin/create/button/?url=&quot; + data:post.url + &quot;&amp;amp;media=&quot; + data:post.thumbnailUrl + &quot;&amp;amp;description=&quot; + data:post.title' rel='nofollow' target='_blank' title='Share To Pinterest'><i class='fab fa-pinterest'/> <b>Pinterest</b></a></li><li><a class='e-waves waves-light wa' expr:href='&quot;https://api.whatsapp.com/send?text=&quot; + data:post.title + &quot; &quot; + data:post.url' target='_blank'><i aria-hidden='true' class='fab fa-whatsapp'/> <b>Whatsapp</b></a></li></ul>
</div><div class='clear'/>
<div class='authorboxwrap'><div class='authorboxfull'><div class='avatar-container'><a expr:href='data:post.authorPhoto.url' target='_blank'><img class='author_avatar img-circle lazy' expr:alt='data:post.author' expr:data-src='resizeImage(data:post.authorPhoto.url,110)' height='96' src='data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAAEAAAABCAYAAAAfFcSJAAAAAXNSR0IArs4c6QAAAARnQU1BAACxjwv8YQUAAAAJcEhZcwAADsQAAA7EAZUrDhsAAAANSURBVBhXYzh8+PB/AAffA0nNPuCLAAAAAElFTkSuQmCC' width='96'/></a></div><div class='author_description_container'><h5><a expr:href='data:post.authorPhoto.url' rel='author' target='_blank'><data:post.author/></a></h5><p><data:post.authorAboutMe/></p></div></div></div></b:if></article><div class='clear'/>
<b:if cond='data:blog.pageType == &quot;item&quot;'>
<!--RELATED POST AND PAGE NAV DESIGN BY WWW.IDBLANTER.COM-->
<div class='related-post' id='related-post'/>
<script type='text/javascript'>
var labelArray = [<b:if cond='data:post.labels'><b:loop values='data:post.labels' var='label'>&quot;<data:label.name/>&quot;<b:if cond='data:label.isLast != &quot;true&quot;'>,</b:if></b:loop></b:if>];
var relatedPostConfig={homePage:&quot;<data:blog.homepageUrl/>&quot;,widgetTitle:&quot;<h4><i class='material-icons'>&#57673;</i> Related Post</h4>&quot;,numPosts:6,summaryLength:370,titleLength:&quot;auto&quot;,thumbnailSize:220,noImage:&quot;https://2.bp.blogspot.com/-LGfDcNv6jF0/Wm1S_ET-yyI/AAAAAAAAJFo/bOijmeJNpqsSoNTmPgwkQlKp0gjun9EKACLcBGAs/s340/blanterimage.png&quot;,containerId:&quot;related-post&quot;,newTabLink:!1,moreText:&quot;Read More&quot;,widgetStyle:3,callBack:function(){}};
//<![CDATA[
var randomRelatedIndex,showRelatedPost;(function(a,c,h){var i={widgetTitle:"<h4>Related Post :</h4>",widgetStyle:1,homePage:"https://www.idblanter.com/",numPosts:7,summaryLength:370,titleLength:"auto",thumbnailSize:200,noImage:"data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAAEAAAABCAIAAACQd1PeAAAAA3NCSVQICAjb4U/gAAAADElEQVQImWOor68HAAL+AX7vOF2TAAAAAElFTkSuQmCC",containerId:"related-post",newTabLink:!1,moreText:"Baca Selengkapnya",callBack:function(){}};for(var b in relatedPostConfig)i[b]="undefined"==relatedPostConfig[b]?i[b]:relatedPostConfig[b];var d=function(d){var a=c.createElement("script");a.type="text/javascript",a.src=d,h.appendChild(a)},f=function(c,b){return Math.floor(Math.random()*(b-c+1))+c},j=function(d){var a,e,f=d.length;if(0===f)return!1;for(;--f;)a=Math.floor(Math.random()*(f+1)),e=d[f],d[f]=d[a],d[a]=e;return d},k="object"==typeof labelArray&&0<labelArray.length?"/-/"+j(labelArray)[0]:"",e=function(d){var e,f,g,h,k,l=document.getElementById(i.containerId),m=j(d.feed.entry),n=i.widgetStyle,o=i.widgetTitle+"<ul class=\"related-post-style-"+n+"\">",s=i.newTabLink?" target=\"_blank\"":"";if(l){for(var b=0;b<i.numPosts&&b!=m.length;b++){f=m[b].title.$t,g="auto"!==i.titleLength&&i.titleLength<f.length?f.substring(0,i.titleLength)+"&hellip;":f,h="media$thumbnail"in m[b]&&!1!==i.thumbnailSize?m[b].media$thumbnail.url.replace(/.*?:\/\//g,"//").replace(/\/s[0-9]+(\-c)?/,"/s"+i.thumbnailSize):i.noImage,k="summary"in m[b]&&0<i.summaryLength?m[b].summary.$t.replace(/<br ?\/?>/g," ").replace(/<.*?>/g,"").replace(/[<>]/g,"").substring(0,i.summaryLength)+"&hellip;":"";for(var x=0,y=m[b].link.length;x<y;x++)e="alternate"==m[b].link[x].rel?m[b].link[x].href:"#";o+=2==n?"<li><img alt=\"\" class=\"related-post-item-thumbnail\" src=\""+h+"\" width=\""+i.thumbnailSize+"\" height=\""+i.thumbnailSize+"\"><a class=\"related-post-item-title\" title=\""+f+"\" href=\""+e+"\""+s+">"+g+"</a><span class=\"related-post-item-summary\"><span class=\"related-post-item-summary-text\">"+k+"</span> <a href=\""+e+"\" class=\"related-post-item-more\""+s+">"+i.moreText+"</a></span><span style=\"display:block;clear:both;\"></span></li>":3==n||4==n?"<li class=\"related-post-item\" tabindex=\"0\"><a class=\"related-post-item-title\" href=\""+e+"\""+s+"><img alt=\"\" class=\"related-post-item-thumbnail\" src=\""+h+"\" width=\""+i.thumbnailSize+"\" height=\""+i.thumbnailSize+"\"></a><div class=\"related-post-item-tooltip\"><a class=\"related-post-item-title\" title=\""+f+"\" href=\""+e+"\""+s+">"+g+"</a></div><span style=\"display:block;clear:both;\"></span></li>":5==n?"<li class=\"related-post-item\" tabindex=\"0\"><a class=\"related-post-item-wrapper\" href=\""+e+"\" title=\""+f+"\""+s+"><img alt=\"\" class=\"related-post-item-thumbnail\" src=\""+h+"\" width=\""+i.thumbnailSize+"\" height=\""+i.thumbnailSize+"\"><span class=\"related-post-item-tooltip\">"+g+"</span></a><span style=\"display:block;clear:both;\"></span></li>":6==n?"<li><a class=\"related-post-item-title\" title=\""+f+"\" href=\""+e+"\""+s+">"+g+"</a><div class=\"related-post-item-tooltip\"><img alt=\"\" class=\"related-post-item-thumbnail\" src=\""+h+"\" width=\""+i.thumbnailSize+"\" height=\""+i.thumbnailSize+"\"><span class=\"related-post-item-summary\"><span class=\"related-post-item-summary-text\">"+k+"</span></span><span style=\"display:block;clear:both;\"></span></div></li>":"<li><a title=\""+f+"\" href=\""+e+"\""+s+">"+g+"</a></li>"}l.innerHTML=o+="</ul><span style=\"display:block;clear:both;\"></span>",i.callBack()}};randomRelatedIndex=function(e){var b=e.feed.openSearch$totalResults.$t-i.numPosts,c=f(1,0<b?b:1);d(i.homePage.replace(/\/$/,"")+"/feeds/posts/summary"+k+"?alt=json-in-script&orderby=updated&start-index="+c+"&max-results="+i.numPosts+"&callback=showRelatedPost")},showRelatedPost=e,d(i.homePage.replace(/\/$/,"")+"/feeds/posts/summary"+k+"?alt=json-in-script&orderby=updated&max-results=0&callback=randomRelatedIndex")})(window,document,document.getElementsByTagName("head")[0]);document.getElementById("heretop").appendChild(document.getElementById("movetop"));document.getElementById("material-breadcrumbs").appendChild(document.getElementById("breadcrumbs"));
//]]>
</script><!-- WWW. I D B L A N T E R .COM -->
<div class='clear'/>
</b:if>
</b:includable>
    <b:includable id='postQuickEdit' var='post'/>
    <b:includable id='shareButtons' var='post'>
<b:if cond='data:top.showEmailButton'><a class='goog-inline-block share-button sb-email' expr:href='data:post.sharePostUrl + &quot;&amp;target=email&quot;' expr:title='data:top.emailThisMsg' target='_blank'><span class='share-button-link-text'><data:top.emailThisMsg/></span></a></b:if><b:if cond='data:top.showBlogThisButton'><a class='goog-inline-block share-button sb-blog' expr:href='data:post.sharePostUrl + &quot;&amp;target=blog&quot;' expr:onclick='&quot;window.open(this.href, \&quot;_blank\&quot;, \&quot;height=270,width=475\&quot;); return false;&quot;' expr:title='data:top.blogThisMsg' target='_blank'><span class='share-button-link-text'><data:top.blogThisMsg/></span></a></b:if><b:if cond='data:top.showTwitterButton'><a class='goog-inline-block share-button sb-twitter' expr:href='data:post.sharePostUrl + &quot;&amp;target=twitter&quot;' expr:title='data:top.shareToTwitterMsg' target='_blank'><span class='share-button-link-text'><data:top.shareToTwitterMsg/></span></a></b:if><b:if cond='data:top.showFacebookButton'><a class='goog-inline-block share-button sb-facebook' expr:href='data:post.sharePostUrl + &quot;&amp;target=facebook&quot;' expr:onclick='&quot;window.open(this.href, \&quot;_blank\&quot;, \&quot;height=430,width=620\&quot;); return false;&quot;' expr:title='data:top.shareToFacebookMsg' target='_blank'><span class='share-button-link-text'><data:top.shareToFacebookMsg/></span></a></b:if><b:if cond='data:top.showOrkutButton'><a class='goog-inline-block share-button sb-orkut' expr:href='data:post.sharePostUrl + &quot;&amp;target=orkut&quot;' expr:title='data:top.shareToOrkutMsg' target='_blank'><span class='share-button-link-text'><data:top.shareToOrkutMsg/></span></a></b:if><b:if cond='data:top.showDummy'><div class='goog-inline-block dummy-container'><data:post.dummyTag/></div></b:if>
</b:includable>
    <b:includable id='status-message'>
<b:if cond='data:navMessage'><div class='clear'/></b:if>
</b:includable>
    <b:includable id='threaded-comment-form' var='post'>
<div class='comment-form' id='comment-form'>
<b:if cond='data:mobile'>
<div id='pesan-komentar'><div class='idbpesan'><div class='pesanbro'><span class='bcm'><data:blogCommentMessage/></span><div class='google_emo'/></div><div class='menupesan'><a class='tutup pencet' style='display:none'>https://www.idblanter.com/?assets/script/emoticon.xml</a><a class='show_emo pencet e-waves waves-light'><i class='material-icons'>&#57934;</i> Emoticon</a><a class='fbl pencet e-waves waves-light' href='#feedback-link'><i class='material-icons'>&#59519;</i> Feedback</a></div></div></div>
<data:blogTeamBlogMessage/>
<b:if cond='data:blog.pageType == &quot;static_page&quot;'><a expr:href='data:post.commentFormIframeSrc + &quot;&amp;skin=contempo&quot; + data:variantParam' id='comment-editor-src'/></b:if>
<b:if cond='data:blog.pageType == &quot;item&quot;'><a expr:href='data:post.commentFormIframeSrc + &quot;&amp;skin=contempo&quot; + data:variantParam' id='comment-editor-src'/></b:if>
<iframe class='blogger-iframe-colorize blogger-comment-from-post' height='410' id='comment-editor' name='comment-editor' style='display: none'/>
<b:else/>
<div id='pesan-komentar'><div class='idbpesan'><div class='pesanbro'><span class='bcm'><data:blogCommentMessage/></span><div class='google_emo'/></div><div class='menupesan'><a class='tutup pencet' style='display:none'>https://www.idblanter.com/?assets/script/emoticon.xml</a><a class='show_emo pencet e-waves waves-light'><i class='material-icons'>&#57934;</i> Emoticon</a><a class='fbl pencet e-waves waves-light' href='#feedback-link'><i class='material-icons'>&#59519;</i> Feedback</a></div></div></div>
<data:blogTeamBlogMessage/>
<b:if cond='data:blog.pageType == &quot;static_page&quot;'><a expr:href='data:post.commentFormIframeSrc + &quot;&amp;skin=contempo&quot; + data:variantParam' id='comment-editor-src'/></b:if>
<b:if cond='data:blog.pageType == &quot;item&quot;'><a expr:href='data:post.commentFormIframeSrc + &quot;&amp;skin=contempo&quot; + data:variantParam' id='comment-editor-src'/></b:if>
<iframe class='blogger-iframe-colorize blogger-comment-from-post' height='410' id='comment-editor' name='comment-editor'/>
</b:if>
<data:post.friendConnectJs/>
<data:post.cmtfpIframe/>
<script type='text/javascript'>BLOG_CMT_createIframe(&quot;<data:post.appRpcRelayPath/>&quot;,&quot;<data:post.communityId/>&quot;);</script>
</div>
</b:includable>
    <b:includable id='threaded_comment_js' var='post'>
<script async='async' expr:src='data:post.commentSrc' type='text/javascript'/>
<script type='text/javascript'>
(function() {
var items = <data:post.commentJso/>;
var msgs = <data:post.commentMsgs/>;
var config = <data:post.commentConfig/>;
// <![CDATA[
var cursor=null;items&&0<items.length&&(cursor=parseInt(items[items.length-1].timestamp)+1);var startThread,targetComment,bodyFromEntry=function(e){if(e.gd$extendedProperty)for(var t in e.gd$extendedProperty)if("blogger.contentRemoved"==e.gd$extendedProperty[t].name)return'<span class="deleted-comment">'+e.content.$t+"</span>";return e.content.$t},parse=function(e){cursor=null;var t=[];if(e&&e.feed&&e.feed.entry)for(var r,o=0;r=e.feed.entry[o];o++){var n={},a=/blog-(\d+).post-(\d+)/.exec(r.id.$t);if(n.id=a?a[2]:null,n.body=bodyFromEntry(r),n.timestamp=Date.parse(r.published.$t)+"",r.author&&r.author.constructor===Array){var d=r.author[0];d&&(n.author={name:d.name?d.name.$t:void 0,profileUrl:d.uri?d.uri.$t:void 0,avatarUrl:d.gd$image?d.gd$image.src:void 0})}if(r.link&&(r.link[2]&&(n.link=n.permalink=r.link[2].href),r.link[3])){var l=/.*comments\/default\/(\d+)\?.*/.exec(r.link[3].href);l&&l[1]&&(n.parentId=l[1])}if(n.deleteclass="item-control blog-admin",r.gd$extendedProperty)for(var i in r.gd$extendedProperty)"blogger.itemClass"==r.gd$extendedProperty[i].name?n.deleteclass+=" "+r.gd$extendedProperty[i].value:"blogger.displayTime"==r.gd$extendedProperty[i].name&&(n.displayTime=r.gd$extendedProperty[i].value);t.push(n)}return t},paginator=function(r){if(hasMore()){var e=config.feed+"?alt=json&v=2&orderby=published&reverse=false&max-results=50";cursor&&(e+="&published-min="+new Date(cursor).toISOString()),window.bloggercomments=function(e){var t=parse(e);cursor=t.length<50?null:parseInt(t[t.length-1].timestamp)+1,r(t),window.bloggercomments=null},e+="&callback=bloggercomments";var t=document.createElement("script");t.type="text/javascript",t.src=e,document.getElementsByTagName("head")[0].appendChild(t)}},hasMore=function(){return!!cursor},getMeta=function(e,t){return"iswriter"==e?t.author&&t.author.name==config.authorName&&t.author.profileUrl==config.authorUrl?"true":"":"deletelink"==e?config.baseUri+"/delete-comment.g?blogID="+config.blogId+"&postID="+t.id:"deleteclass"==e?t.deleteclass:""},replybox=null,replyUrlParts=null,replyParent=void 0,onReply=function(e,t){null==replybox&&null!=(replybox=document.getElementById("comment-editor"))&&(replybox.height="250px",replybox.style.display="block",replyUrlParts=replybox.src.split("#")),replybox&&e!==replyParent&&(document.getElementById(t).insertBefore(document.getElementById("threaded-comment-form"),null),replybox.src=replyUrlParts[0]+(e?"&parentID="+e:"")+"#"+replyUrlParts[1],replyParent=e)},hash=(window.location.hash||"#").substring(1);/^comment-form_/.test(hash)?startThread=hash.substring("comment-form_".length):/^c[0-9]+$/.test(hash)&&(targetComment=hash.substring(1));var configJso={maxDepth:config.maxThreadDepth},provider={id:config.postId,data:items,loadNext:paginator,hasMore:hasMore,getMeta:getMeta,onReply:onReply,rendered:!0,initComment:targetComment,initReplyThread:startThread,config:configJso,messages:msgs},render=function(){if(window.goog&&window.goog.comments){var e=document.getElementById("comment-holder");window.goog.comments.render(e,provider)}};window.goog&&window.goog.comments?render():(window.goog=window.goog||{},window.goog.comments=window.goog.comments||{},window.goog.comments.loadQueue=window.goog.comments.loadQueue||[],window.goog.comments.loadQueue.push(render));
})();
// ]]>
  </script>
</b:includable>
    <b:includable id='threaded_comments' var='post'>
  <div class='comments' id='comments'>
    <a name='comments'/>
<div class='menu-komentar'>
<h3><i class='material-icons'>comment</i> <b:if cond='data:post.numComments == 1'>
1 <data:commentLabel/>
<b:else/>
<data:post.numComments/> <data:commentLabelPlural/>
</b:if>
</h3>
<a class='e-waves waves-light' href='javascript:;' id='showkomentarmenu'><i class='material-icons'>more_vert</i></a></div>
<div id='komentarmenu'><li><a class='e-waves' href='#top-ce' title='Add Comments'>Add Comments</a></li><li><a class='showmore e-waves' href='javascript:;' title='More Settings'>More Settings</a></li></div>
    <p class='comment-footer'>
      <b:if cond='data:post.allowNewComments'>
        <b:include data='post' name='threaded-comment-form'/>
      <b:else/>
        <data:post.noNewCommentsText/>
      </b:if>
    </p>
    <div class='comments-content'>
      <b:include cond='data:post.embedCommentForm' data='post' name='threaded_comment_js'/>
      <div id='comment-holder'>
         <data:post.commentHtml/>
      </div>
    </div>
    <b:if cond='data:showCmtPopup'>
      <div id='comment-popup'>
        <iframe allowtransparency='true' frameborder='0' id='comment-actions' name='comment-actions' scrolling='no'>
        </iframe>
      </div>
    </b:if>
    <div id='backlinks-container'>
    <div expr:id='data:widget.instanceId + &quot;_backlinks-container&quot;'>
      <b:include cond='data:post.showBacklinks' data='post' name='backlinks'/>
    </div>
    </div>
  </div>
<script type='text/javascript'>
<b:if cond='data:post.numComments != 0'>
var Items = <data:post.commentJso/>;
var Msgs = <data:post.commentMsgs/>;
var Config = <data:post.commentConfig/>;
<b:else/>
var Items = {};
var Msgs = {};
var Config = {&#39;maxThreadDepth&#39;:&#39;0&#39;};
</b:if>
//<![CDATA[
$(function(){document.getElementById("top-continue").appendChild(document.getElementById("pesan-komentar"))});
function blockLinks(A,e){for(var o=document.getElementById(A).getElementsByTagName(e),t=0;t<o.length;t++)-1!==o[t].innerHTML.indexOf("</a>")&&(o[t].innerHTML=o[t].innerHTML.replace(/<a[^>]*>|<\/a>/g,""))}Config.maxThreadDepth=5,Display_Emo=!0,Replace_Youtube_Link=!0,Replace_Image_Link=!0,Replace_Force_Tag=!0,Replace_Image_Ext=["JPG","GIF","PNG","BMP"],Emo_List=[":)","https://lh3.googleusercontent.com/-cQugl5FMRuM/V1U_XbfQigI/AAAAAAAAEAU/_5Q9Hv4xAGo7Z_TUaGMyoch8vEPO1KnYgCLcB/h120/1.png",":(","https://lh3.googleusercontent.com/-nQpusekLOCY/V1U_XmFH4LI/AAAAAAAAEAY/TXKngRHW9go5Qrh9wkZR5QFCAEPPvVeeACLcB/h120/2.png","hihi","https://lh3.googleusercontent.com/-RqDpqWecyMw/V1U_j-B12EI/AAAAAAAAECc/s7jdJHYiDQogwTJGmkwO7H4m2JR5qvB6ACLcB/h120/3.png",":-)","https://lh3.googleusercontent.com/-LWEIDBVvX1c/V1U_lnGQezI/AAAAAAAAEC8/rjH9OARs2xEp48_v9Q4KaaBvwo6YMZ-ggCLcB/h120/4.png",":D","https://lh3.googleusercontent.com/-XxQdOt_KU0Q/V1U_mKKhA8I/AAAAAAAAEDA/bvjgNnnHctg9ueVNu5NFxQ18wQh-hqykACLcB/h120/5.png","=D","https://lh3.googleusercontent.com/-ecwUs8Iv7cE/V1U_maDI_uI/AAAAAAAAEDE/3VBplucPP9g3HRA-zyr_fwWPwlXpC9z9ACLcB/h120/6.png",":-d","https://lh3.googleusercontent.com/-cPixj9X9VU4/V1U_mRajeVI/AAAAAAAAEDI/rLjaySYljNY7ldS5KBJYinqcz5JsQwLKACLcB/h120/7.png",";(","https://lh3.googleusercontent.com/-QK49_cxX7Pg/V1U_m0Plu0I/AAAAAAAAEDQ/QgU1OQfknsgiV1o9rHPZHByL2eeVNxCTgCLcB/h120/8.png",";-(","https://lh3.googleusercontent.com/-OIvn-XD877c/V1U_m0TggsI/AAAAAAAAEDU/dfIUcK-mvzwcuBYgE93WdXp8nUiaax-kwCLcB/h120/9.png","@-)","https://lh3.googleusercontent.com/-5-xZ_iOFEWY/V1U_fgPr1qI/AAAAAAAAEAk/Fzil_Zga404bKRMUWBJcrYCdZG9WMoqwQCLcB/h120/10.png",":P","https://lh3.googleusercontent.com/-surwmy1xv7s/V1U_flVlhoI/AAAAAAAAEAs/UumewMQHQvQ0fF259J1pZPksuGkjt77UwCLcB/h120/11.png",":o","https://lh3.googleusercontent.com/-TbaqYWjix1Q/V1U_frVlWjI/AAAAAAAAEAo/blK4C7ldC6Me0rdC9yeC3UAs8L-K-oKSACLcB/h120/12.png","-_-","https://lh3.googleusercontent.com/-MXeJVgDtvm8/V1U_gT-pwFI/AAAAAAAAEA4/VHEw8D0J-igAMmlHQEo8-H0LofhPblsyACLcB/h120/13.png","(o)","https://lh3.googleusercontent.com/-Qh8qpbpfn5w/V1U_gd8Y37I/AAAAAAAAEA0/jrmxtwDbWkAo6OMc1dp81LJ_4rxq6QgEACLcB/h120/14.png","[-(","https://lh3.googleusercontent.com/-ydJg3pGdAu4/V1U_glYAGYI/AAAAAAAAEA8/9Bmt6TkY6qAev2PW-upGFKyfTM_neZ33ACLcB/h120/15.png",":-?","https://lh3.googleusercontent.com/-zvAWzR1cFqg/V1U_gwtpBEI/AAAAAAAAEBA/UwYwxwcPyRolYybeo2HM432aDEmoS7WKgCLcB/h120/16.png","(p)","https://lh3.googleusercontent.com/-P7z88ESwPbA/V1U_hOh1WhI/AAAAAAAAEBI/dIDLP1WItxQSmbJhxhpx0XmJ_HyzojQ7wCLcB/h120/17.png",":-s","https://lh3.googleusercontent.com/-TPpiEOnXnIY/V1U_hPHCZ0I/AAAAAAAAEBM/bdDzJnYqQlIjRTVaGpq31n95sZmbRKRIQCLcB/h120/18.png","(m)","https://lh3.googleusercontent.com/-6FrkT1JkhoI/V1U_hiPQnGI/AAAAAAAAEBY/BSr_6-K4NlwX1xfLljfIbFgx6ly7rJOvwCLcB/h120/19.png","8-)","https://lh3.googleusercontent.com/-7C1sLx9TYkg/V1U_hty1WFI/AAAAAAAAEBg/Hs27CyEGkLEWoT3N8wCBWo22PE5VuPwZQCLcB/h120/20.png",":-t","https://lh3.googleusercontent.com/-_FUqFhidqMA/V1U_h6O-u1I/AAAAAAAAEBc/57ERp1X4nYcIpGHJwdLCLpJidR-CqURGACLcB/h120/21.png",":-b","https://lh3.googleusercontent.com/-mvLRhY4f4Hg/V1U_iQ6ZUiI/AAAAAAAAEBo/sy2V-sOyFoQylKRQuZHxymrzTibYlNoLQCLcB/h120/22.png","b-(","https://lh3.googleusercontent.com/-xG1jATeYafQ/V1U_iY3K2rI/AAAAAAAAEBw/9siA8z5H7e0jv28K2d7Z3DpOn1Ioks9-gCLcB/h120/23.png",":-#","https://lh3.googleusercontent.com/-HICGf3jYH1Q/V1U_iTpgnOI/AAAAAAAAEBs/OTQXucr4SwQtYQ43-FJSQUA70V-HRcnkgCLcB/h120/24.png","=p~","https://lh3.googleusercontent.com/-rFE8c9kChSA/V1U_jAuFzwI/AAAAAAAAEB8/Uei-eeRYucsaX_b25oSUFSjeOr6AbK1wgCLcB/h120/25.png","$-)","https://lh3.googleusercontent.com/-Pzi_NyZB0CM/V1U_jCqzB-I/AAAAAAAAECA/86MgOeR0kGoylHserWnLU4-wEpro2oGmgCLcB/h120/26.png","(y)","https://lh3.googleusercontent.com/-DOR5NAJ7fag/V1U_jLkDwhI/AAAAAAAAECE/elfZGm0x7FoChkEsbK_UMuxvyO2dx2gpwCLcB/h120/27.png","(f)","https://lh3.googleusercontent.com/-JJCoISGDY-Q/V1U_j9Be1SI/AAAAAAAAECY/KHHRo2K5pPsne4BL4i-zsuM5CFjNGTyCgCLcB/h120/28.png","x-)","https://lh3.googleusercontent.com/-AvfZd1NTFfw/V1U_j0YjR7I/AAAAAAAAECU/Fm1730hyNxAHjX7U85ht6IpHoKQ6kZOpwCLcB/h120/29.png","(k)","https://lh3.googleusercontent.com/-Sf533Lx2XDo/V1U_khMZ9eI/AAAAAAAAECg/WOgTOgQB3D4RSYHCj9hfLrlOURjA3XEawCLcB/h120/30.png","(h)","https://lh3.googleusercontent.com/--Rzg7PE7FYQ/V1U_kpnrH0I/AAAAAAAAECo/XrBlEvaRaawUxgC-i_UC0uQf_0EEGwlfgCLcB/h120/31.png","(c)","https://lh3.googleusercontent.com/-q3xJUc8AM8Q/V1U_kniub3I/AAAAAAAAECk/qcB2jKeUbIAT0JxcC94SnPGcPMrUzrIMQCLcB/h120/32.png","cheer","https://lh3.googleusercontent.com/-Di2zHgE4USM/V1U_lBsZvUI/AAAAAAAAEC4/1jGglPj2FhIuP2ugYy173q9evtzd-NWdACLcB/h120/33.png","(li)","https://lh3.googleusercontent.com/-tg98vYaNbAM/V1U_lK3-GEI/AAAAAAAAECw/GSik9JCoRjwX5SRbCeYtkOOjguRN_j6lgCLcB/h120/34.png","(pl)","https://lh3.googleusercontent.com/-xyfPNlEkU8s/V1U_lWd8aMI/AAAAAAAAEC0/ZSjoYA3rTY4DhfflmKYRm__fz6UejeePwCLcB/h120/35.png"],Force_Tag=["[pre]","<pre>","[/pre]","</pre>",'<pre class="brush: plain; title: ; notranslate" title="">',"&lt;code&gt;","</pre>","</code>"],blockLinks("comments","p"),eval(function(A,e,o,t,n,c){if(n=function(A){return(A<62?"":n(parseInt(A/62)))+(35<(A%=62)?String.fromCharCode(A+29):A.toString(36))},!"".replace(/^/,String)){for(;o--;)c[n(o)]=t[o]||n(o);t=[function(A){return c[A]}],n=function(){return"\\w+"},o=1}for(;o--;)t[o]&&(A=A.replace(new RegExp("\\b"+n(o)+"\\b","g"),t[o]));return A}("3 q='.W';3 1a=$('#N-Y').B('y');u 1w(H){3 1h=' \\n\\r\\t\\f\\2p\\1S\\1T\\1U\\24\\25\\26\\27\\2e\\2h\\2k\\2m\\2n\\2u\\2y\\2z\\2A\\2F\\1L\\1N\\1O\\1P\\1Q';G(3 i=0;i<H.5;i++){b(1h.g(H.1V(i))!=-1){H=H.d(0,i);11}}C H}$('#28 .1B p').k(u(D,7){b(2r){3 m='1g://13.Z.X/1t?v=';3 8=7.g(m);F(8!=-1){1H=7.d(8);K=1w(1H);3 1c=K.g('&');3 T='';b(1c==-1){T=K.d(m.5)}1e{T=K.d(m.5,1c)}3 1j='<1k I=\"1W\" y=\"1g://13.Z.X/1X/'+T+'?1Y=1\" 20=\"0\" 21></1k>';7=7.d(0,8)+1j+7.d(8+K.5);8=7.g(m);b(8==-1){m='22://13.Z.X/1t?v=';8=7.g(m)}}}b(23){3 1d='';3 x=7;G(3 i=0;i<1z.5;i++){3 m='.'+1z[i];3 o=x.E();3 8=o.g(m);F(8!=-1){l=x.d(0,8+m.5);o=l.E();3 w='2j://';3 z=o.g(w);3 L='';F(z!=-1){L=w.R();l=l.d(z+w.5);o=l.E();z=o.g(w)}w='1K://';o=l.E();z=o.g(w);F(z!=-1){L=w.R();l=l.d(z+w.5);o=l.E();z=o.g(w)}b(L==''||l.5<6){11}l=L+l;1d+=x.d(0,8+m.5-l.5)+'<S y=\"'+l+'\" I=\"2s\"/>';x=x.d(8+m.5);o=x.E();8=o.g(m)}}7=1d+x}b(1m){3 5=A.5;b(5%2==1){5--}G(3 i=0;i<5;i+=2){3 V='<S y=\"'+A[i+1]+'\" I=\"1x\"/>';8=7.g(A[i]);F(8!=-1){7=7.d(0,8)+V+7.d(8+A[i].5);8=7.g(A[i])}}}b(2G){3 5=U.5;b(5%2==1){5--}G(3 i=0;i<5;i+=2){F(1){3 x=7.R();8=x.g(U[i]);b(8!=-1){7=7.d(0,8)+U[i+1]+7.d(8+U[i].5)}1e{11}}}}C 7});$('.1M').k(u(D,7){b(1m){3 5=A.5;b(5%2==1){5--}3 15='';G(3 i=0;i<5;i+=2){3 1C='<1F>'+A[i]+'</1F>';3 V='<S y=\"'+A[i+1]+'\" I=\"1x\"/>';15+='<M I=\"1R\">'+V+1C+'</M>'}C 15}});$('.1f .1B p').k(u(i,h){10=h.R();D=10.g('@<a 12=\"#c');b(D!=-1){14=10.g('</a>',D);b(14!=-1){h=h.d(0,D)+h.d(14+4)}}C h});u 1l(j){r=j.g('c');b(r!=-1)j=j.d(r+1);C j}u 1n(j){j='&1Z='+j+'#%1o';1p=1a.1q(/#%1o/,j);C 1p}u 1r(){k=$(q).k();$(q).k('');q='.W';$(q).k(k);$('#N-Y').B('y',1a)}u 1s(e){j=$(e).B('16');j=1l(j);k=$(q).k();b(q=='.W'){1u='<a 12=\"#1v\" 29=\"1r()\">'+2a.2b+'</a><a 2c=\"1v\"/>';$(q).k(1u)}1e{$(q).k('')}q='#2d'+j;$(q).k(k);$('#N-Y').B('y',1n(j))}17=2f.2g.12;18='#N-2i';19=17.g(18);b(19!=-1){1y=17.d(19+18.5);1s('#2l'+1y)}G(3 i=0;i<O.5;i++){b('1A'2o O[i]){3 j=O[i].1A;3 1b=2q($('#c'+j+':P').B('1D-1E'));$('#c'+j+' .2t:P').k(u(D,7){3 J=O[i].16;b(1b>=2v.2w){$('#c'+J+':P .2x').1G()}3 Q=$('#c'+J+':P').k();Q='<M I=\"1f\" 16=\"c'+J+'\" 1D-1E=\"'+(1b+1)+'\">'+Q+'</M>';$('#c'+J).1G();C(7+Q)})}}3 1I=$(\"#2B\");1I.2C('.2D S').2E(u(){3 1J=$(1i).B('y');$(1i).2H().B('y',1J.1q(/\\/s[0-9]+(\\-c)?\\//,\"/2I-c/\"))});",0,169,"|||var||length||oldhtml|check_index|||if||substring|||indexOf|||par_id|html|img_src|search_key||upper_html||Cur_Cform_Hdr||||function||http_search|temp_html|src|find_http|Emo_List|attr|return|index|toUpperCase|while|for|str|class|child_id|yt_link|save_http|div|comment|Items|first|child_html|toLowerCase|img|yt_code|Force_Tag|img_html|main|com|editor|youtube|temp|break|href|www|index_tail|newhtml|id|cur_url|search_formid|search_index|Cur_Cform_Url|par_level|yt_code_index|save_html|else|comment_wrap|http|whitespace|this|yt_video|iframe|Valid_Par_Id|Display_Emo|Cform_Ins_ParID|7B|n_cform_url|replace|Reset_Comment_Form|Display_Reply_Form|watch|reset_html|origin_cform|trim|comment_emo|ret_id|Replace_Image_Ext|parentId|comment-block|img_code|data|level|span|remove|ht|avatar|ava|HTTPS|u200a|google_emo|u200b|u2028|u2029|u3000|item|x5d|x7c|x7d|charAt|comment_youtube|embed|autohide|parentID|frameborder|allowfullscreen|https|Replace_Image_Link|x3c|x3e|x0b|xa0|top-ra|onclick|Msgs|addComment|name|r_f_c|u2000|window|location|u2001|form_|HTTP|u2002|rc|u2003|u2004|in|x5b|parseInt|Replace_Youtube_Link|comment_img|comment_child|u2005|Config|maxThreadDepth|comment_reply|u2006|u2007|u2008|comments|find|comment_avatar|each|u2009|Replace_Force_Tag|show|s45".split("|"),0,{}));
//]]>
</script>
</b:includable>
  </b:widget>
</b:section>
</div>
<b:if cond='data:blog.pageType != &quot;error_page&quot;'>
<div id='sidebar-blanter' itemprop='mainEntity' itemscope='itemscope' itemtype='https://schema.org/WPSideBar'>
<aside id='sidebar-css'>
<div class='tabs tabs-1'>
  <b:section class='tab tab1 section' cond='data:view.isSingleItem' id='tab1' maxwidgets='1' name='Tab One' showaddelement='yes'>
    <b:widget id='PopularPosts2' locked='true' title='Popular' type='PopularPosts' version='1'>
      <b:widget-settings>
        <b:widget-setting name='numItemsToShow'>5</b:widget-setting>
        <b:widget-setting name='showThumbnails'>true</b:widget-setting>
        <b:widget-setting name='showSnippets'>false</b:widget-setting>
        <b:widget-setting name='timeRange'>ALL_TIME</b:widget-setting>
      </b:widget-settings>
      <b:includable id='main'>
  <b:if cond='data:title != &quot;&quot;'><h2><i class='far fa-star'/><data:title/></h2></b:if>
  <div class='widget-content popular-posts'>
    <ul>
      <b:loop values='data:posts' var='post'>
      <li>
        <b:if cond='!data:showThumbnails'>
          <b:if cond='!data:showSnippets'>
            <!-- (1) No snippet/thumbnail -->
            <a expr:href='data:post.href'><data:post.title/></a>
          <b:else/>
            <!-- (2) Show only snippets -->
            <div class='item-title'><a expr:href='data:post.href'><data:post.title/></a></div>
            <div class='item-snippet'><data:post.snippet/></div>
          </b:if>
        <b:else/>
          <!-- (3) Show only thumbnails or (4) Snippets and thumbnails. -->
          <div expr:class='data:showSnippets ? &quot;item-content&quot; : &quot;item-thumbnail-only&quot;'>
            <b:if cond='data:post.featuredImage.isResizable or data:post.thumbnail'>
              <div class='item-thumbnail'>
                <a expr:href='data:post.href' target='_blank'>
                  <b:with value='data:post.featuredImage.isResizable                                  ? resizeImage(data:post.featuredImage, 72, &quot;1:1&quot;)                                  : data:post.thumbnail' var='image'>
                    <img alt='Popular' border='0' class='lazy' expr:data-src='data:image' src='data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAAEAAAABCAYAAAAfFcSJAAAAAXNSR0IArs4c6QAAAARnQU1BAACxjwv8YQUAAAAJcEhZcwAADsQAAA7EAZUrDhsAAAANSURBVBhXYzh8+PB/AAffA0nNPuCLAAAAAElFTkSuQmCC'/>
                  </b:with>
                </a>
              </div>
            </b:if>
            <div class='item-title'><a expr:href='data:post.href'><data:post.title/></a></div>
            <b:if cond='data:showSnippets'>
              <div class='item-snippet'><data:post.snippet/></div>
            </b:if>
          </div>
          <div class='clear'/>
        </b:if>
      </li>
      </b:loop>
    </ul>
  </div>
</b:includable>
    </b:widget>
  </b:section>
  <b:section class='tab tab2 section' cond='data:view.isSingleItem' id='tab2' maxwidgets='1' name='Tab Two' showaddelement='yes'>
    <b:widget id='Label2' locked='true' title='Labels' type='Label' version='1'>
      <b:widget-settings>
        <b:widget-setting name='sorting'>ALPHA</b:widget-setting>
        <b:widget-setting name='display'>CLOUD</b:widget-setting>
        <b:widget-setting name='selectedLabelsList'/>
        <b:widget-setting name='showType'>ALL</b:widget-setting>
        <b:widget-setting name='showFreqNumbers'>false</b:widget-setting>
      </b:widget-settings>
      <b:includable id='main'>
  <b:if cond='data:title != &quot;&quot;'>
    <h2><i class='fas fa-tags'/><data:title/></h2>
  </b:if>
  <div expr:class='&quot;widget-content &quot; + data:display + &quot;-label-widget-content&quot;'>
    <b:if cond='data:display == &quot;list&quot;'>
      <ul>
        <b:loop values='data:labels' var='label'>
          <li>
            <b:if cond='data:blog.url == data:label.url'>
              <span expr:dir='data:blog.languageDirection'><data:label.name/></span>
            <b:else/>
              <a expr:dir='data:blog.languageDirection' expr:href='data:label.url'><data:label.name/></a>
            </b:if>
            <b:if cond='data:showFreqNumbers'>
              <span dir='ltr'><data:label.count/></span>
            </b:if>
          </li>
        </b:loop>
      </ul>
    <b:else/>
      <b:loop values='data:labels' var='label'>
        <span expr:class='&quot;label-size label-size-&quot; + data:label.cssSize'>
          <b:if cond='data:blog.url == data:label.url'>
            <span expr:dir='data:blog.languageDirection'><data:label.name/></span>
          <b:else/>
            <a expr:dir='data:blog.languageDirection' expr:href='data:label.url'><data:label.name/></a>
          </b:if>
          <b:if cond='data:showFreqNumbers'>
            <span class='label-count' dir='ltr'><data:label.count/></span>
          </b:if>
        </span>
      </b:loop>
    </b:if>
  </div>
</b:includable>
    </b:widget>
  </b:section>
</div>
<div id='sidebar1-material'>
<b:section class='sidebar1' cond='data:view.isSingleItem' id='sidebar1' name='Sidebar Widget' showaddelement='yes'>
  <b:widget id='HTML4' locked='false' title='Newsletter' type='HTML' version='1'>
    <b:widget-settings>
      <b:widget-setting name='content'>&lt;div id=&#39;material-subscribe&#39;&gt;
&lt;form action=&quot;https://feedburner.google.com/fb/a/mailverify&quot; method=&quot;post&quot; target=&quot;popupwindow&quot; onsubmit=&quot;window.open(&#39;https://feedburner.google.com/fb/a/mailverify?uri=Kartupaket&#39;, &#39;popupwindow&#39;, &#39;scrollbars=yes,width=550,height=520&#39;);return true&quot;&gt;
&lt;div class=&quot;input-field&quot;&gt;
&lt;input class=&quot;inputfield&quot; name=&quot;email&quot; type=&quot;email&quot; required=&quot;&quot; class=&quot;validate&quot;/&gt;
&lt;span class=&quot;highlight&quot;&gt;&lt;/span&gt;
&lt;span class=&quot;bar&quot;&gt;&lt;/span&gt;
&lt;label&gt;Email&lt;/label&gt;
&lt;input type=&quot;hidden&quot; value=&quot;DuniaBlanter&quot; name=&quot;uri&quot;/&gt;&lt;input type=&quot;hidden&quot; name=&quot;loc&quot; value=&quot;en_US&quot;/&gt;
&lt;button class=&quot;buttonx subs e-waves waves-light&quot; type=&quot;submit&quot;/&gt;&lt;i class=&quot;fa fa-envelope&quot;&gt;&lt;/i&gt; Subscribe&lt;/button&gt;
&lt;/div&gt;
&lt;/form&gt;
&lt;/div&gt;</b:widget-setting>
    </b:widget-settings>
    <b:includable id='main'>
  <b:if cond='data:title != &quot;&quot;'>
    <h2 class='title'><data:title/></h2>
  </b:if>
  <div class='widget-content'>
    <data:content/>
  </div>
</b:includable>
  </b:widget>
</b:section>
</div><div class='clear'/>
</aside></div>
</b:if>
<div class='clear'/>
</b:if>
<b:if cond='data:blog.pageType == &quot;error_page&quot;'>
<!-- ERROR PAGE HTML -->
<style type='text/css'>
#error-material b{display:block;line-height:2}#error-material{border-radius:15px;box-shadow:0 1px 2px 0 rgba(60,64,67,.3),0 1px 3px 1px rgba(60,64,67,.15);padding:15px;text-align:center;color:#d81313;margin-top:-50px;background:#fff}#error-material .a404{background:#d81313;display:inline-block;font-weight:700;color:#fff;font-size:70px;padding:15px 30px;margin:0 0 10px;border-radius:20px}.darkmode #error-material{background:#333;color:#fff}
</style>
<span id='responsive'><data:blog.blogId/></span><div id='error-material'><div class='a404'>404</div><b>Sorry, the page you&#39;re looking for in this blog does not exist.</b><b>You will be redirected to homepage shortly.</b></div>
<script type='text/javascript'>
my_redirect = setTimeout(function() {
  window.location.href = &quot;<data:blog.homepageUrl/>&quot;;
}, 5000);
</script>
<!-- END ERROR PAGE -->
</b:if>
<div class='clear'/>
<b:if cond='data:blog.pageType != &quot;error_page&quot;'>
<b:if cond='data:view.isSearch'><b:else/>
<b:section class='footerbanner' id='footerbanner' maxwidgets='1' name='Footer Banner Ads 970x90' showaddelement='yes'/>
</b:if></b:if>
<b:if cond='data:view.isMultipleItems'>
<b:section class='popular-box' id='popular-box' maxwidgets='1' name='Homepage Popular Posts' showaddelement='no'>
  <b:widget id='PopularPosts1' locked='true' title='Populer Post' type='PopularPosts' version='1'>
    <b:widget-settings>
      <b:widget-setting name='numItemsToShow'>5</b:widget-setting>
      <b:widget-setting name='showThumbnails'>true</b:widget-setting>
      <b:widget-setting name='showSnippets'>false</b:widget-setting>
      <b:widget-setting name='timeRange'>LAST_MONTH</b:widget-setting>
    </b:widget-settings>
    <b:includable id='main'>
  <b:if cond='data:title != &quot;&quot;'><h2><data:title/></h2></b:if>
  <div class='widget-content popular-posts'>
<ul><b:loop values='data:posts' var='post'><li>
        <b:if cond='!data:showThumbnails'>
          <b:if cond='!data:showSnippets'>
            <!-- (1) No snippet/thumbnail -->
            <a expr:href='data:post.href'><data:post.title/></a>
          <b:else/>
            <!-- (2) Show only snippets -->
            <div class='item-title'><a expr:href='data:post.href'><data:post.title/></a></div>
            <div class='item-snippet'><data:post.snippet/></div>
          </b:if>
        <b:else/>
          <!-- (3) Show only thumbnails or (4) Snippets and thumbnails. -->
          <div expr:class='data:showSnippets ? &quot;item-content&quot; : &quot;item-thumbnail-only&quot;'>
            <b:if cond='data:post.featuredImage.isResizable or data:post.thumbnail'>
<div class='item-thumbnail'><a expr:href='data:post.href' target='_blank'>
<b:with value='data:post.featuredImage.isResizable                                  ? resizeImage(data:post.featuredImage, 150, &quot;1:1&quot;)                                  : data:post.thumbnail' var='image'><img alt='Popular' border='0' class='lazy' expr:data-src='data:image' src='data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAAEAAAABCAYAAAAfFcSJAAAAAXNSR0IArs4c6QAAAARnQU1BAACxjwv8YQUAAAAJcEhZcwAADsQAAA7EAZUrDhsAAAANSURBVBhXYzh8+PB/AAffA0nNPuCLAAAAAElFTkSuQmCC'/></b:with></a></div></b:if><div class='item-title'><a expr:href='data:post.href'><data:post.title/></a></div><b:if cond='data:showSnippets'><div class='item-snippet'><data:post.snippet/></div></b:if></div><div class='clear'/>
        </b:if>
</li></b:loop></ul></div>
</b:includable>
  </b:widget>
</b:section>
<div class='clear'/>
<div id='footer-material'>
  <b:section class='footer-ui' id='footer-ui1' name='Footer Widgets 1' showaddelement='yes'>
    <b:widget id='HTML5' locked='false' title='About Us' type='HTML' version='1'>
      <b:widget-settings>
        <b:widget-setting name='content'><![CDATA[<p style="text-align: justify;">Kartupaket Dot Com (kartupaket.com) adalah sebuah situs memberikan informasi seputar kartu paket internet dan informasi teknologi lainnya seputar Smartphone terbaru seperti Android, IOS maupun Smartphone terbaru disaat ini. Selain itu kami juga memberikan beberapa artikel yang bermanfaat bagi anda bisa berupa itu Tutorial maupun Berita Viral, semoga situs ini memberikan banyak manfaat kepada anda yang sudah membaca artikel-artikel yang telah ditulis didalamnya.</p>]]></b:widget-setting>
      </b:widget-settings>
      <b:includable id='main'>
  <!-- only display title if it's non-empty -->
  <b:if cond='data:title != &quot;&quot;'>
    <h2 class='title'><data:title/></h2>
  </b:if>
  <div class='widget-content'>
    <data:content/>
  </div>
</b:includable>
    </b:widget>
  </b:section>
  <b:section class='footer-ui' id='footer-ui2' name='Footer Widgets 2' showaddelement='yes'>
    <b:widget id='Label1' locked='false' title='Categories' type='Label' version='1'>
      <b:widget-settings>
        <b:widget-setting name='sorting'>ALPHA</b:widget-setting>
        <b:widget-setting name='display'>CLOUD</b:widget-setting>
        <b:widget-setting name='selectedLabelsList'>Aplikasi,Bisnis,By. U,Paket Internet,Telkomsel</b:widget-setting>
        <b:widget-setting name='showType'>USER_SELECTED</b:widget-setting>
        <b:widget-setting name='showFreqNumbers'>false</b:widget-setting>
      </b:widget-settings>
      <b:includable id='main'>
<b:if cond='data:title != &quot;&quot;'>
<h2><data:title/></h2>
</b:if>
<div expr:class='&quot;widget-content &quot; + data:display + &quot;-label-widget-content&quot;'>
<b:if cond='data:display == &quot;list&quot;'>
<ul>
<b:loop values='data:labels' var='label'>
<li><b:if cond='data:blog.url == data:label.url'><span expr:dir='data:blog.languageDirection'><data:label.name/></span>
<b:else/>
<a expr:dir='data:blog.languageDirection' expr:href='data:label.url'><data:label.name/></a>
</b:if>
<b:if cond='data:showFreqNumbers'>
<span dir='ltr'><data:label.count/></span>
</b:if>
</li>
</b:loop>
</ul>
<b:else/>
<b:loop values='data:labels' var='label'>
<span expr:class='&quot;label-size label-size-&quot; + data:label.cssSize'><b:if cond='data:blog.url == data:label.url'><span expr:dir='data:blog.languageDirection'><data:label.name/></span><b:else/><a expr:dir='data:blog.languageDirection' expr:href='data:label.url'><data:label.name/></a></b:if><b:if cond='data:showFreqNumbers'><span class='label-count' dir='ltr'><data:label.count/></span></b:if></span>
</b:loop>
</b:if>
</div>
</b:includable>
    </b:widget>
  </b:section>
  <b:section class='footer-ui' id='footer-ui3' name='Footer Widgets 3' showaddelement='yes'>
    <b:widget id='HTML3' locked='false' title='Langganan' type='HTML' version='1'>
      <b:widget-settings>
        <b:widget-setting name='content'>&lt;div id=&#39;subscribe-ui&#39;&gt;
&lt;form action=&quot;https://feedburner.google.com/fb/a/mailverify&quot; method=&quot;post&quot; target=&quot;popupwindow&quot; onsubmit=&quot;window.open(&#39;https://feedburner.google.com/fb/a/mailverify?uri=Kartupaket&#39;, &#39;popupwindow&#39;, &#39;scrollbars=yes,width=550,height=520&#39;);return true&quot;&gt;
&lt;div class=&quot;input-field&quot;&gt;
&lt;input class=&quot;inputfield&quot; name=&quot;email&quot; type=&quot;email&quot; required=&quot;&quot; class=&quot;validate&quot;/&gt;
&lt;span class=&quot;highlight&quot;&gt;&lt;/span&gt;
&lt;span class=&quot;bar&quot;&gt;&lt;/span&gt;
&lt;label&gt;Email&lt;/label&gt;
&lt;input type=&quot;hidden&quot; value=&quot;Kartupaket&quot; name=&quot;uri&quot;/&gt;&lt;input type=&quot;hidden&quot; name=&quot;loc&quot; value=&quot;en_US&quot;/&gt;
&lt;button class=&quot;buttonx subs e-waves waves-light&quot; type=&quot;submit&quot;/&gt;&lt;i class=&quot;fa fa-envelope&quot;&gt;&lt;/i&gt; Subscribe&lt;/button&gt;
&lt;/div&gt;
&lt;/form&gt;
&lt;/div&gt;</b:widget-setting>
      </b:widget-settings>
      <b:includable id='main'>
  <!-- only display title if it's non-empty -->
  <b:if cond='data:title != &quot;&quot;'>
    <h2 class='title'><data:title/></h2>
  </b:if>
  <div class='widget-content'>
    <data:content/>
  </div>
</b:includable>
    </b:widget>
  </b:section>
</div>
</b:if>
</div><div class='clear'/>
<footer id='footer-bottom' itemprop='mainEntity' itemscope='itemscope' itemtype='https://schema.org/WPFooter'>
<div class='grid one-half'>
<div id='copyright'>
<p>Copyright &#169; <span itemprop='copyrightYear'>2020</span> <span itemprop='copyrightHolder' itemscope='itemscope' itemtype='https://schema.org/Organization'><a expr:href='data:blog.homepageUrl' expr:title='data:blog.title' rel='noopener'><data:blog.title/></a></span> - All Rights Reserved</p>
<a class='feedcontact' href='https://www.kartupaket.com/p/kontak.html' target='_blank' title='Contact Us'><i class='material-icons'>feedback</i> Contact our Team</a>
</div></div></footer></div></div><a href='javascript:void' id='BackToTop' title='Back To Top'><i class='fa fa-angle-up'/></a><div class='darkshadow'/>
<!-- PENGATURAN NOTIFIKASI -->
<div class='blanternotif'>
<div class='blantertitle'>Postingan Terbaru</div>
<div class='notiftext'><style>#M566576ScriptRootC895379 {min-height: 350px;}</style>
<ul id='recent-ui'/></div>
<a class='waves-effect waves-light close-sf' href='javascript:void' title='Close'>Tutup</a>
<a class='waves-effect waves-light btn-sf' href='javascript:void' title='Got It'>Kartupaket.com</a>
</div><div class='flashlight'/><div id='dui2'/>
<div class='clear'/>
<script type='text/javascript'>
//<![CDATA[
// Full Settings (Pengaturan)
var load_more 		= 'Selanjutnya';
var loading_text 	= 'Memuat...';
var all_post_show   = 'All Post Show';
var error_text 		= 'Error Loading Feed';
var dark_text	    = 'Mode Malam'; // Dark Mode Menu Text
var recent_post 	= 'https://kartupaket.com/'; // Recent Post URL
var recent_count    = 7; // Recent Post Count
var sticky_tag	    = '#HTML6'; // Sticky Widget
var css1		    = 'https://use.fontawesome.com/releases/v5.8.2/css/all.css'; // CSS Font Awesome
var css2		    = 'https://fonts.googleapis.com/icon?family=Material+Icons'; // CSS Material Icons
var css3 			= 'https://fonts.googleapis.com/icon?family=Roboto'; // CSS Roboto
var _0x6c0f=["w7RWwpzCigArVcKSw4c=","WnlY","HMODPg==","XsOuRA==","NUTDsg==","w41UZg==","wpfCkSwmZMKQLMKvR8KcwofDiMKAwrhSL1zDksOBwrvDrhTDscORw7ZuDsKSwqlzGsOcw57DkW9tDx7CnMO+w5PDkEwASMKnZB3CqB/DoBN1wqABX8KDCMKmwovDosOiw6xZw44hw5fDo8KFwpJgOcONR8OvLsKjw6AiwoBHE8KkNF0A","w5jDvsOewqIUwoDCgFzCtg==","TsK2wolZwoREGRt9","J8Krw4I=","ZMKBcg==","ZAY+","asKmGA==","YQXDtw==","wqhobsKNw6LCizTDhA==","asKmHg==","wrbCimQ=","wrbCijo=","B8KDw4BVwozCpD9LbcK+","FB4Cw7o1wpI=","OsKWd8KLb8Kqw7TCnw==","w4/CmCNneMKYZcObSsKYwoI=","O8KOfcKLScKXw6vCmcOxUjAEAg==","wrfDuMKHw63CqEDCtVzCucKcw5Zow5Z2w77ChcO2S8OfwojDjA==","wolDIQ==","w6RbSlhfJxtzAS1D","ABsFw7s0wpHDrMO5w4o=","ecOdJCo=","ZcOZJTvDs8K6MBjDpWLDkA==","MhHDvMKxwpbDi1gWwozDpQ==","BsO3AcOdw47DlMOdwoc9w7HDmHnDnRk=","RFAfbMOzwotmX8KQdw==","w6Nbwo/CnhYR","X8OJacK/AcORcXfChkI=","JMKYYcKLVcKnw4HClsOhUjAEAg==","wqLDs8KlfMKrwqDDvw==","bFLCow0Lw4fCnA==","w5MqWkI=","wr/Ds8KHw4DCslbCs0vCpMKTw4Nf","w4A7CiZ2csOYUQ==","w7pHwoxT","w5zCvMKtwoF7woXDoyTDksK3Gg==","EMKRRB0bb1w=","w6LDo8K/w7XCtw3CjcO8wrcz","w7ZTQ1k=","DMKLVBwHSUlGw6Jgw4rDlT/Cv8OjwrI=","w70owqBQwo5B","w6vDpcK8","w6zDvsKvw6fCpgTCrcOxwqQ7O8OVKw==","EsOxw4fDtUl/wrvDksK8eMKTw6g=","MA3DpcKxwpbDm1cbwoPDvRg=","FQbDg8OXNQ==","HsO3FcO3w6E=","axwTa1XChg==","w6XCnmvDm1odwqLDqS0NwqM=","wpDCvsOKw79Aw4rCnw==","JMK8Ni3Clm5QRsK6","worCvsOI","H8OadsOnKsKZwo/DjXglw4BO","wplNJXDDocOyasO6w5jCvw==","w6liwpHDqsOCKA==","w7jDmMO9wrAUbA==","OAgTcVXDncOrcsKFw5TDvwE6QXfChDQawqg=","FhPDncOeCQ==","W8OafMKfHsKZcn3CnETDtMKJw4Jgw7/CscKXwo4=","F8O1w4HDvFsxwqw=","AcOMb8KYBsOdaD/CnETDtMKJw4Jvw6TCqsKV","wrHDlMOmwqsUYcO7wqh8w5pSRxFi","w5BBIjzCuMOzaMO1w4fCvDTCrjk=","CFNed8O2wq9+ScKYbC8s","QcKew5PDhUnCpk7DlXs=","w5skHiZ3Y8OP","AcOMb8KYBsOdaD/CnETDtMKJw4Jgw7/CscKXwo7DusOscEBTw5nCjlvCqQ==","ARLDlsOTGHlScQ==","SMO9w57DqhcmwrvDmsKie8KWw7nDpE9YA8O3w5rCmnHCnMKgw7YG","wobCkmhyf8KVf8O+SsKJwpzDjMKDw7pSPwzCjcKJwrPCoRk=","FsOmw7tgw6dWwpPCgVLDq0lIw6EEw5TCpSzDnsKb","SBDDgcOQB3lJMiDDhcKWw5wtZMKgbG9/w4orNMKAw69ewrERIxjCumlUw4LDisKa","BhLDhsObDz1fei7DnsKSw4B2PcO6NzUhw4t/bcODwrIGw6YQZV3Duj4VwpvCicOUwpTCpTfDpgHCog==","w73DsMKcw5XDqkHCqVnCvsKBw5hfw5Nww7XDhsO2cMOXwoLDlhHDjsO7OzPDn3x2w4XDoA==","T8O7wrd6w6ZewonCm1TDsQ1Dw7pbw4HCuCjDmMKbP0QYwrfCt8KNwqoCMcOr","FwUNw7ApwozDjMO/w5VrOsKdw4nChsKuJQ5zwoRMHcOUPR7CmMKk","A8KvwosnwpXCkcKM","w4zCmDFDYcKRfMOoTcKJwobDocKUwpRaKw3Cn8KzwrvCoxI=","G8KlwpAjwonCjA==","cMK2wo/Cuk7Cgl7CjkHCnQ8w","HsOab8OJKMKIwr7DjHM8w5A=","cRECckQ=","wr9oTMKWw7TChyjDtMO0BcOb","LsK/HE8QSDQ=","w4jDpS3CkMKEwofCv0PDmAc=","wqrDsjzDnlNffVVTw5fChwnCiMOjDQHCgH19UCY=","w7jDtMKyw65dwppHw7PDjsOYT8K2X8Kfwr1pwrAh","wqNVOMKwGCzDosO4w6HCl8OVNcOdJMKV","HsOacsOKP8KOwpjDp3I5w5hP","EQjDkcORBGNJfibDgw==","CcKHQQs=","wqrCscKnbsK4wqHDoxXCuA==","CsO/AcOiw5XDm8O0wrA0w6fDmGjDnQ==","K1nDqh8Sw77Cn8KA","wpPCo8Oew6xhw4HCnEDDvA==","w63Do8Kuw78=","w5UgCyR9fw==","wpzDicOSa8K+","w5ZhwqV1w5DCqxLDvRMTwqXDhzMUKwc=","w7hTQ1Y=","E8Kvwp0xwpDCgcKSw7Q=","wrjDi8OWZ8K9w6k=","wqxidMK8w6/ChzfDksO7AsONwoXCmwlWLzY3wogu","AMKVw4k=","wrjDnMOdYsKow65hw6k3Bg==","AnMOwoo=","wqnDiVrDqDI=","L8KzLjXCm34=","w7tAwptTw43CsSTDvRsIwpvDjQ==","IcKxLg==","QMOacMKD","aw0R","w7sWw797w41ow5HCsA==","d8OXNirDhMKY","w6ZTSlVy","w71UQ1h0IBh8FSBD","wqjDhMONa8Kjw6lBw6k7FXbCmg==","wrheO8K6HB7DisOow6HCjQ==","wqpzdMKYw6DCih/DgcOwGMOK","wqZZMcKrBg==","AsK0wo5Ywopd","TVkaZMOswro=","RgHDi8OdGHVPfTXDmcKZw5cs","wrTCvcKgcsKxwqnDmA3Cpg==","C8K7wpBOwos=","w4vCoMKr","w7bCnXHDl0AAwprDrg==","EcOgw7t6w71c","w6dZX1JqBA==","UFIEccOlwr4=","w5c7ETF7ecOCRg==","C8K7woZP","wrwUw6R3wo1+w43CpwTCpRE=","NsO6Iz3DgMKhOSrDuXc=","BMOzw4XDuUw3","woXCtcObw59Ew47Cn0Y=","w7VURFBnHBg=","ZcK2wpbClEzCk2/Ci0LCmwg=","MsKqFm1dRz4JwpM=","d1nCpgwK","OBE7cA==","wrzDssKSw4vCrljCul/CtQ==","wrs+w4pUw7wbQAPDrTnDkMKDWQ==","w70gwpo9wrUZGw==","eR11","w71bwpxTw43CjQPDsRoPwp0=","bsK7LiPDmnJgR8K/P8KJQyzCo0Y=","wo4kWVrCk8KuXMKYOcKowo7CrAEXwp1eUMKEJBNZw78AwrXDg8K2wrDCnsK+wrHCogTDmmw=","NMKxVnISVz4BwoY=","Jws4ecKLPMOZ","QcKDw5XDjFbCpWLDi3cNOg==","w6VfwpDClgUAdcKLw5bDpA==","excba1TDnMKjcg==","e8K6w4HCk1vChQTCkk/DgQ==","JlHCogYGwqXCmMKfwoAjfsKew7FwwpnDtw==","w7XCnmvDmlE9wprDpy4Vwq4=","wqzDuMKhw6VbwppHw6rDm8OCVMK9AMOWwr9ww789w53CmMKDWMKfMQ==","d8KKf8KHX8K2w6nCn8OqSnUfGg==","NsOLLjfDj8KQOxvDuHLChMO4HsO4wrTDtMOKcVEYHQ==","AhwYw7c8","wrwEw6dzwoR+w47CthnDsE3Ci1ItNhI9wpzDm8KCw4zDmg==","w5NYPnbCq8OtbMOWw5HCtC4=","w7lVwo/ClBIJ","wqzDvcKhw6pKw5JXw6vDn8OCVQ==","wrwEw6N1wpd2w4bCvQI=","w6h0ZcKYw7HCgTLDmsO0AsObwrXCizxb","ecKtE24GVjQMwpjCuT0=","wqHDt8Kow6pAw4NAw7TCl8OOQcK7GQ==","wrLDncOowqNSZsOhwqh2w4ZD","wo4gWVTCnMKuZsKHNsKzwp/Ctw5aw58UH8KNMhpRw7MVwrDDkg==","wrlewpTCmB8KU8Kqw4vCusKsZMOaMBt0w6rClcOS","U8KdXgMTf0Jewqp3w5bDiCjCn8Orw74Sw6dJwr8xcAk4w4kdw4d9d8OawrslbcKDWcKbUz4ZwooJw5piwrdMw6RMw4MuPEPDmA==","wrEEw6N1wpd2w4zCoRI=","UcKbw4oYwprCvjlDfMKnb8K0dA==","w6fDn1bDriRDwrEoD8OxP8OjwqnDiHDDrwU=","NMKgwpfCkl7Ck0HCgk3CnVs5wrw8wrkrYsOYwrM9w4Azw68B","w6jCqcOjKMOtw6jDpFPDozhv","dMOMNiw=","wo0kw67Cuw==","w4rCocOQw6xdw4PCjUfCpXfDh2QQw6kbw7I=","csKyecKo","wqjClW3DkVMFwpDDnywUwqQ=","K0/CrwcEw5fCn8Kewo4=","WMKJw5zDnhfCok3DhngKLBg=","w7g4wqBhwo1Kw7xcIsKDbmZYIQ==","SFMRasOowqs9V8KbbSg=","PsKrEg==","NQjDvMOm","wofCtcK9wod3wpXCrTrDnsKhAsKKwrEyBhTDtMOLAMKlwr9DLDBwUMK+w5HCrwUTwrly","w5lbVW1pGwk=","wo7CvMKqwoZ2wpTDoDPCjMKiA8Kbw7I/EBrDsMOaSsKiw7RPPzxwS8K1w4bCvxFa","wpokw6PCtwfDow==","SkwWbcOXwqtxSMKda3k1wqszEysGwqRlwqR7d1w=","NxjDsMKw","wrbDscKcw4DCtQ==","RMO1w7Z6wqlVwpTCh1PCqA1CwrkFw5bCoyzDgcKB","D8Ojw57Dvko=","IcK3IzQ=","ScOVfsKIFA==","w4EuQVDCgMK0YsKBPQ==","AMK3woxCwo4NAhdtw5PCohzDthvCmg==","LMO9w5DDt18BwqDDgcKp","wrLCrMK+","IT/DucK1wpbDlA==","wqTDtMKHw4PCog==","w6FbwopFw4vCtw/Dtho=","w68Cw6l2wolow4vCthM=","w5o1EiA=","wrBFIcK3ATs=","w6zDscKawpHDu1TDu0zCscKAw5ZOw44iwrnCtMOgdcObwoXDk1TDg8O1PDjDmjU9","TsKfdsOPKsKBwpjCmTg=","wrAQw5RSw5bCs0bDuxEGwprDm29SK05MwoDDvEZTf2UXw6NNw7MIY8Ogw5xlw6XDrMKQFBzChcKZw4vCuGvCkGfDqsOKDsKgwqtWw5NrwpTCsR3DthEbwqjCn8KQEMK7wrdPw5EAwroYw73DrMKow45jw74=","w7LCo8OPw4fDsws=","aFEyIMOQbsKDLsODwrzCksOBw6EWRQnCkTIXZm7CiMOGwovDg8KcX8OSIsOPw6nDrynCkAl1wpFbdBnDssKpVyQ9Bgo+DsKgBMOFw6USw5nCq8Krw4nCvCJLUsKcMcOwXcOuXMKh","KcKXMS7DisKbaF7CqnTDlMO1GcOiwr/DucOYKldJFsKJw59qwp8=","w4vCnWzDilwnwpTDrSwK","wqNYw7hqwoF1wp3Ds0vDthHDhFhsJxUvwofDicObwoHDicOlbEo=","wq4BwptGw57Cq1jCpFIUwpnDiTxObl9IwpHDq00APH4Xw6Zbwr0HbsO8w49jw7DCocKaQEc=","Vi4YwpzDp8KxCcKrw6HDkxdsw7nCmVZgw6VA","FsKwwo4hwpPCgA==","wqXClGfDn0AcwofDpS0JwqTDtHU=","w4wtVFHCm8K0ZMKNIA==","w6V3wpHDu8OVf2nCjsK+w77Dj8OLwqPCmsKAKhs1wrocwrNFwrRtw7jDlsKFwqzCkmBTw5VOwqnCqGZ3","w7LDpTE=","w6YnVw==","GR8o","L8OmAA==","wqnCsMOG","w6HCiCs=","EMKrFw==","w5Nbwo8=","wq5JIQ==","wp5TIQ==","w7o7CQ==","EBs5","woHCqcOLw7lGw4s=","wpRIMn7CosO1aMOyw5rCrg==","NsKVfMKJbsKBw4g=","w5jCocK3wpZ8woXDrSY=","w7MYw6h7wpRyw4zCvQ==","w5w7DDE=","CcO/w5DDtFM8wq7DuMKgacKMw74=","KcOcKyjCi8KcMkPCtGHDhcO6FMK7w77Cq8KFLEhUV8KBw5M7w5J6CsORwojDkX0decKzEsOpdsKCd8KBBHTDosKTQMOXwq3DmzDDgMKOCcO4HMKfw6fDhgTDjsKaXQDCnGHCkMKww6/Clm3CjsOOGsOgw6JAw5bDhRjCrcKnwpHDhMOVw7JCw5fCksOLVUF2LC/CkMOWRC3Dj8OjwodLw5zCnMOGJF1Gw53CpcKfTFAccDXCvsKMScOzwo9mwo1HwqYKwpNJwqkbDCwXwpnDv2klBMKGWStXUMKHw5hwwphUw7UOQ0bDm3I=","w4PCiShq","wrBww7s=","NxkXYlTDncOpbMKFw5PDuRN7VnvCljwAwqplw5gYJ8Opw7TDuhHCucOuHsOgw5LCocKlwpxhXcKPwoDDsW8vCz/Cnj8NJMOAw5/Cn8KQw6AUOg5Ha8OGPn7CpsKfXTJlwofCk8KKSXk=","dcK4HmQVVn4dwoXCqSHDjWQWBWTDi8KvXwg=","UcO7E8OqwpTDiMOowoYnw63DiXjClA==","wqzDqi/DjFNeMkUAw5fChx/DicOnHx3CgGsyUCZ4B3DDk8KGL2TDpGp3wo/DrcO2GsOzwpI=","RsO2w5DDvlkrw6nDl8KlMsKTw6zDvlQ=","OMK7HW4DQA==","dxg7esKNK8KMI8KUwrrCkMOBw6VFUg==","w7PDrcKBw4rCsU0=","NcKfZ8KLSQ==","wpc6Gj1qbw==","NcKMZ8KBS8K/w6XCgw==","wrnDs8KHw4rCtUPCulQ=","w67DlsO9wrBNcMKhw6A=","w79VwovCnAE=","wqzDqsKrw6jCsRg=","w5smFiJ3eQ==","w55KNHDCuMO0e8O+w5DCuDfCvTpBBRg=","wrlEIcKvHXPCjMKjwqfDi8OeJ8KGMsKcD1soIHMlw7s8MmNCakPClycZfsKvIwjCjcOjQi7DvcONfGTDqcKwCsKJb8Oiwr3CgUJuw7vDliPCoETDvMKwYsKnw7nCq8Kcw5NJblBdNMO4wrt2NwoieMKPeRrClgoHw7LDpsKgQsKJLcOvfC8SwpFAe0kfwrPCsHIxwpADDMOjw47DonfCtMO2wrjDnsKCNRwPMyMawoVTE8OC","NsOmWsOxCMK4wqnDt0gBw6Rkw7coHSJtw5PDrcK4dMOlw5EZw5rCr8K9worDukHClsOQw458VC7ChUsMw6R4AE3CuA3Dh1/ComHDsMO2w6JIG3bCmsKyd8OWWEnCisKmIzA=","AcO8w7t8w5dQwoPCjXzDsQ==","DsK6wolZwq5d","MsK5wo1SwrxdBA==","EcKywpEpwr7CjMKdw7LDvcOrwoDDpQ==","XwscZcOFw7kgVMK8QBB5wr5wJHo=","BxIPw7E+woA=","wrHDu8OtN8K1w45Hwr8dEC7DmMOxwq/Cn30vwpXDp8KOdDXCm0VJwrxuUydkwoU7GsK+WcKq","w7YzwrpBwpN7w7RBOA==","woMKYXjCvsOjOsOVdsKwwoLCvQ0YwoIXXsKPLhZY","QcOmw799w6RQwonCm1TDswE=","wrPDv8K+w7/CvgTDlsK+wq85KsOSOcOzwp9PwrjDtMOGw4ROOMOaw5HDhBvCnWPDhcOoasO0H8KHwr1ybyrCg8OGw4nCsRPDsMKPw781fcK1w40+wr5Iw7bDmSA+wqRSw69VwrZDShjDicKQO8OBe8O4D3HCnwnDtX4cwpgiwq9Jw4fCp0vCicOPwpbCuS7Dn1jCqMKnw4PDscKNw7wSw6x+wrnDisKLKn4hw6LCucKPP8OsfsOdw5tsw73Ci3rClEXCoVbDuMKKw5XCpCgOMCXCjMO0U1XCoCwxwqvCmxXCjcOrUWQ6w5jCrDPDghMIWwvDrcOaw4gEwpXDg8OWfm/CoyjDrDnDlMO0ZkDDnsKFEsKsw57CiW/DoU0Pw4UjXnHDo8OBwqfCm3rDo8OPw5TDuXTDr8Oywr0aw6Etw7kfwpHDpwMiKgpww49oOcKTZ8OGw5PDiUjDoGYDOMOLUcKXW8OMQA/DkEAKwoYuw7jDo8K6wozDmXLCj33DqcOqdhLDsQfDhCl6wr8qDMOiFi7DlVbDowjDmsKsS8KcwobCkcKkw75tCsKCw7ZKQQbDsVPCpMKLJidAwqvCnMK2w48Nw68PQcK9w5V2w7PDrcOuw6sww7ZDw7Qfw5s+wpnCkMKNw4PDskPDsEPClUxmw4YFwq8nGMKIccKjw5QZw7vCm1LCn2oSwrkEQsKEMmLDl8KBWEBnw5suwqhpw6V5w7VKwrLDhsO/FcOeRcOuVhEnw7rCqMKtHFsowofDmVLCmEbComI3w4MYwonCg27Dp2TDvBtKwrnCsMKlE8KsPl1/AsKqwpgLw5c0w6rDuMK7w4RzwqRJK1LDvcK8w7LCgihsPcKMwr5FfxnDt23CqEx8","FAUFw6o/","w7wywqFKwpUCw7xcP8KETXh0Ng==","w6zCo3fDm0YQ","D20OwoHDo8KxQw==","w6PCu8K+eMKwwqDDohY=","JRzDt8Kn","CsOgw4XDuVU8wro=","w7BfS1xzBAlm","N8KqGmMC","DcOjAMOgw5zDlMO5wqomw6DDnw==","w7tAwoFC","EwUDw6o1wpHDgcOmw58=","wp9ZOH3CqA==","FcK1wpcowpnCsMKdw6LDs8OhworDtQ==","JRzDt8KLwozDmmwHwrXDtBA=","exAcc1HDh8KoecKYw7/Drgw1QW0=","w6jDmMOrwo5XdMOkwqxh","w6DDm0zDoCNYwrs3","UsOyG8OkwpnDmcOhwpQhw7LCgCk=","wonDnWo4","w6vDi8OowqFwe8Onwqxg","w5QjV0bCrcK5bMKbLMK9woLCsA0Ewq4RH8KNMgE=","AMKywp80wrzCiMKQ","UVkLdw==","R8KYWBwNbg==","C8K7woRfwopb","CgnDtsOXDXRE","B8OlNMOnw5fDmcO5wpw9w68=","Nx82eA==","GcKzwopYwoJMGApHw5vCrA==","RQTDiMOTH2MAPQ==","w77DpD/Dm1tJPkliw4TCnhzDlsO9","NMK8ID/DlmNRX8KBP8KNUw==","YMK+esKw","wpzDsD7Cl8KZwqzCnEnDkhc=","wo1eNGHCqcOvbcOPw5s=","BG4PwonDiMK+WsOy","wqTDr8Kaw4jCoFDCqQ==","OBPDscKxwoA=","FsKjwootwovCgcKjw7TDn8OmwrvDozckw4XCnA==","w5Igw7zDuw==","w6JtwrHDqsKNAyPCkcK0w7vDjw==","BcKlwpMrwovCgQ==","wrbDiVPDriVNwpokHsO+","wrTDvMKHw44=","DcO2w7Brw7dL","H8OLcMOPMMKK","wolNM2LDocOiZsO1w4DCvzXCqA==","HMKdRQcIfwFew6Zh","TQ1fI8Osw7w8GsKWMHFhwqxzXmc8w7Q6w7F/NQ==","EQbDhsOBQX1YcSE=","S8Kswpdkwp7CiMKdw7PDjcK5w4bDpXYyw5fCmXVRw44jQ8OQwrjDgCBGByXDscOxw6ADwq/CvMKpwp7DuX7CuCXDrMObJcKGScOnK8KVaw==","WcK0wp8mwo7DicON","wps9w4tmw7YTQAfCkynDkMKPaMKx","w7rDjMOnwrJNfMOmwqc=","w5TDqz7CkcKDwp3Clg==","ZsOMIyrDjg==","E8KUw4E=","w5vCkjZy","NcKXcMKGVMKhw7c=","dMOWITbDhMKH","DMK0wpxOwp1MGBs=","WcOjw4HDsVRywqrDl8Kte8KMwrDCr0ZfDMKzw4bCjC3DisOqw78Bwo4=","dsOHL8OBSMKjw6XClMK6","BMK8wptOwp1dNxtyw5/CoxfDuQbCvsOrwqzCvg==","w7nDi8O7wr5L","NsKxGmUUQQ==","EsKQUgIXeUc=","BR4ew60uwqbDkMO/w5Zh","BcORZMOPMMKEwonDgTcjw5dZw5YJPURUw67DhMKLV8KN","fw3DusKnwozDjA==","wqjCgm3DjUA=","bsK8LC/Dk2lNWQ==","w5NNP3LCpMOuew==","wr/Du8KV","w5VOwqnDg8KbJDbCr8K0w6nDjsOJwrzCjw==","w7tUQVJnDA==","ZcK2wojCi1XCmF/CgnfCjQMh","w4jDkMKQ","SkwWbQ==","AcKVw4sR","DcKRQhoN","wqjCuMK0bsK4wrHDmA3Cpg==","w7hcwpvCihYRfMKaw4vDscOqcw==","TcOdfsKfH8OWeXXCgVg=","woTDty/ClMKEw5PCkkDDnRFkwqVoUMOtw7h/esK9w71hw44+w4ELwo/CicKMDsKawq8uwrnDnTY=","w4jCkSBnf8KgeMOgRsKSwoDDlw==","Z8K2fsKIHDFfdEYk","wqHDrsKmw6nCtUzCmMOywrIiLQ==","w5NcPmLCuMKsZsOuw4DCvyk=","U8KcXQEZN1xLw6Bmw4w=","QMO0HsO9w57Cl8O9wpQ1w6TDjybDhgxSw7HDqBp3HcOowqE=","GV1TYMOowq9jScODITcyw6krHSYww6Fzw7xgYllFw5cDw4U+wrbDvSNvesO/wq9YZ8ORwp7DocOMwpBaNMKqe8OJwqDCqifCisOlwprDvTpPwoxCDcOzaGvDjMO/LMOwT2zCmCxgwo3Dnk7CpmbDosO2w54=","woh7Hns=","wqDDisO5wrBXNcOqwqVzw5pHFUFlP0HDrhLDpsKXBsOfLcOdw5xCd8ObwpfCu29Uw6jDksOTw7HDtMOyTMKWOcOKDsObR1s=","wqgVXk1nBkM=","XwQcw780w4XDm8O6w5t2ZMOUwoLCgcK0ZgUxwoNdFsOTa0k=","wrPDrcOqw6XCvgDCm8Ouw7x0NMOIcsK7woFUwrTDo8KKwpdDasOMw4fCmFfCjGTDnMOnbcK6HsKHwrdjbyTCkcKI","YlMcZMOowqswasKfZDhhwpc3FyIww6Ffwr9kakhIw5BS","H3IOwp7Dh8K4UsO5wro=","w57DpTvCkMKlwobChQ==","TcO0HsOzw5fDjsOowod/w63DkmrDjQVE","w7Newphaw4Y=","IxjDocKhworDkTRbwozDpBJyKQUuZhnDhSU=","wr/DkRDDojxGwq0xGMOqKMO2wrTDlz3CowJQMMKcw5fCqxlsAQ7CtRFEI8Ovw7M=","HsKRXx0Rdkk=","ZlPCqRscw6TCnw==","w5g7GA==","w6NbX1M=","w6vDqcKow7PCtQ==","fsK9wp3ClA==","F8KCw5cawo0=","D3kIwonDtsKrXsO4wqA=","w5zCocK5woF2","I8KyLD/DlGpa","wrzDssKU","FMKvwpA3wpLCiMKZ","w7piwpfDpQ==","w65swovDuMKAPCM=","NRjDt8Khwp8=","wrJfO8KsASXDhg==","NxE0Z8KBPsOJ","w6hxwpfDpMKd","w7/DlsOnwqJWecOs","w7oPw6h/wpBvw4rCvBk=","bA0TZFU=","w6fDsSvCk8OSwqzClELDnw1zw70=","wrvCpMOLw7oQw7DCiFDDq3rDjHk=","RsOjw6hvw6RPwoLCmg==","w7YZw6V/wpJTw7fCnjs=","wokhw6nClh7Dq8O4BgDDqnkOYyt+GQ==","w4vCv8KxwoF4","IQ/DsMKiwp3DkWA3wo/Dtx1kMRg=","w4vCv8K5wpFgwqrDqznDhQ==","w5zCvMK/woV/woM=","SMOaeMKRAMObeHc=","axoGTkTDi8Kr","w5rCtsK1wo1lwoPDiz7DlMK/","PRLDtsK1wpTDrGAcwpjDsBt0","w7BfwonCsAcAWQ==","w7IkwpBFwpNEw5xWKMKS","BsO7w7l7w7lawonCnHjDqQFBw7EYw4E=","esK6GnMaSD4Jwo8=","JQs/ZsKXAcOJI8KYw6PCgsOHw6U=","wqnDoTzDml0BPUVcw5U=","DsKWWAgK","HMOKccOO","R8K4w44=","WnlZ","HMODOw=="];(function(a,b){(function(b){for(;--b;)a.push(a.shift())})(++b)})(_0x6c0f,410);var _0x1947=function(a,b){a-=0;var c=_0x6c0f[a];if(void 0===_0x1947.ePKuAk){(function(){var a;try{var b=Function("return (function() {}.constructor(\"return this\")( ));");a=b()}catch(b){a=window}a.atob||(a.atob=function(a){for(var b,c,d=(a+"").replace(/=+$/,""),e=0,f=0,g="";c=d.charAt(f++);~c&&(b=e%4?64*b+c:c,e++%4)?g+=String.fromCharCode(255&b>>(6&-2*e)):0)c="ABCDEFGHIJKLMNOPQRSTUVWXYZabcdefghijklmnopqrstuvwxyz0123456789+/=".indexOf(c);return g})})();var d=function(a,b){var c,d=[],e=0,f="",g="";a=atob(a);for(var h=0,i=a.length;h<i;h++)g+="%"+("00"+a.charCodeAt(h).toString(16)).slice(-2);a=decodeURIComponent(g);for(var j=0;256>j;j++)d[j]=j;for(j=0;256>j;j++)e=(e+d[j]+b.charCodeAt(j%b.length))%256,c=d[j],d[j]=d[e],d[e]=c;j=0,e=0;for(var k=0;k<a.length;k++)j=(j+1)%256,e=(e+d[j])%256,c=d[j],d[j]=d[e],d[e]=c,f+=String.fromCharCode(a.charCodeAt(k)^d[(d[j]+d[e])%256]);return f};_0x1947.wVJIzY=d,_0x1947.mVBQBC={},_0x1947.ePKuAk=!0}var e=_0x1947.mVBQBC[a];return void 0===e?(void 0===_0x1947.XjUmsN&&(_0x1947.XjUmsN=!0),c=_0x1947.wVJIzY(c,b),_0x1947.mVBQBC[a]=c):c=e,c},_0x3573b5=[_0x1947("0x0","DKMC"),_0x1947("0x1","Rg[e"),_0x1947("0x2","gPxX"),_0x1947("0x3","o]Lz"),_0x1947("0x4","gPxX"),_0x1947("0x5","gPxX"),_0x1947("0x6","e)!@"),_0x1947("0x7","wb[s"),_0x1947("0x8","gPxX"),_0x1947("0x9","o]Lz"),_0x1947("0xa","Pj*]"),_0x1947("0xb","ek$n"),_0x1947("0xc","B$xf"),_0x1947("0xd","%D6Q"),_0x1947("0xe","RVbg"),_0x1947("0xf","YnFb"),_0x1947("0x10","EyTj"),_0x1947("0x11","(ly]"),_0x1947("0x12","VdXJ"),_0x1947("0x13","hmgB"),_0x1947("0x14","e)!@"),_0x1947("0x15","Pj*]"),_0x1947("0x16","hmgB"),_0x1947("0x17","e)!@"),_0x1947("0x18","O9xQ"),_0x1947("0x19","a#zF"),_0x1947("0x1a","PN#I"),_0x1947("0x1b","#jD]"),_0x1947("0x1c","dSXL"),_0x1947("0x1d","0oyh"),_0x1947("0x1e","gD65"),_0x1947("0x1f","Hwkr"),_0x1947("0x20","RVbg"),_0x1947("0x21","%D6Q"),_0x1947("0x22","o]Lz"),_0x1947("0x23","&gjx"),_0x1947("0x24","%D6Q"),_0x1947("0x25","qKZy"),_0x1947("0x26","qKZy"),_0x1947("0x27","qN2t"),_0x1947("0x28","AoCN"),_0x1947("0x29","Hwkr"),_0x1947("0x2a","#jD]"),_0x1947("0x2b","Hwkr"),_0x1947("0x2c","IQhz"),_0x1947("0x2d","PN#I"),_0x1947("0x2e","153B"),_0x1947("0x2f","AoCN"),_0x1947("0x30","3@%U"),_0x1947("0x31","3@%U"),_0x1947("0x32","o]Lz"),"",_0x1947("0x33","O9xQ"),":",";",_0x1947("0x34","yVOu"),_0x1947("0x35","Pj*]"),_0x1947("0x36","e)!@"),_0x1947("0x37","Hwkr"),_0x1947("0x38","t2*J"),_0x1947("0x39","a#zF"),_0x1947("0x3a","Egwn"),_0x1947("0x3b","IQhz"),_0x1947("0x3c",")9[$"),_0x1947("0x3d","!fh@"),_0x1947("0x3e","gPxX"),_0x1947("0x3f","EyTj"),_0x1947("0x40","[3o^"),_0x1947("0x41","153B"),_0x1947("0x42","EyTj"),_0x1947("0x43","ek$n"),_0x1947("0x44","[3o^"),_0x1947("0x45","[3o^"),_0x1947("0x46","yv2g"),_0x1947("0x47","o]Lz"),_0x1947("0x48","j7en"),_0x1947("0x49","O9xQ"),_0x1947("0x4a","wb[s"),_0x1947("0x4b","qKZy"),")",_0x1947("0x4c","dSXL"),_0x1947("0x4d","4(nd"),_0x1947("0x4e","dSXL"),_0x1947("0x4f","(ly]"),_0x1947("0x50","PN#I"),_0x1947("0x51","ZZ61"),_0x1947("0x52","v6CM"),"px",_0x1947("0x53","wb[s"),_0x1947("0x54","j7en"),_0x1947("0x55","e)!@"),_0x1947("0x56","yv2g"),_0x1947("0x57","e)!@"),_0x1947("0x58","v6CM"),_0x1947("0x59","PN#I"),_0x1947("0x5a","yVOu"),_0x1947("0x5b","x0b%"),_0x1947("0x5c",")9[$"),"1",_0x1947("0x5d","e)!@"),_0x1947("0x5e","j7en"),"ms",_0x1947("0x5f","yv2g"),_0x1947("0x60","#jD]"),_0x1947("0x61","B$xf"),_0x1947("0x62","j7en"),_0x1947("0x63","j7en"),_0x1947("0x64","IQhz"),_0x1947("0x65","B$xf"),_0x1947("0x66","AoCN"),_0x1947("0x67","VdXJ"),_0x1947("0x68","#jD]"),_0x1947("0x69","VdXJ"),_0x1947("0x6a","gD65"),"0",_0x1947("0x6b","(ly]"),_0x1947("0x6c","wb[s"),_0x1947("0x6d","&gjx"),_0x1947("0x6e","%D6Q"),_0x1947("0x6f","HSoF"),"i",_0x1947("0x70","YnFb"),_0x1947("0x71","0v*k"),_0x1947("0x72","h5qi"),_0x1947("0x73","(ly]"),_0x1947("0x74","j7en"),_0x1947("0x75","EyTj"),_0x1947("0x76","t2*J"),_0x1947("0x77","O9xQ"),_0x1947("0x78","a#zF"),_0x1947("0x79","dSXL"),_0x1947("0x7a","[3o^"),_0x1947("0x7b",")9[$"),_0x1947("0x7c","mo&e"),_0x1947("0x7d","!fh@"),_0x1947("0x7e","153B"),_0x1947("0x7f","VdXJ"),_0x1947("0x80","mo&e"),_0x1947("0x81","&gjx"),_0x1947("0x82","qN2t"),_0x1947("0x83","mo&e"),_0x1947("0x84","hmgB"),_0x1947("0x85","[yQ)"),_0x1947("0x86","4(nd"),_0x1947("0x87","!fh@"),_0x1947("0x88","4(nd"),_0x1947("0x89","e)!@"),_0x1947("0x8a","wb[s"),_0x1947("0x8b","DKMC"),_0x1947("0x8c","3@%U"),_0x1947("0x8d","153B"),_0x1947("0x8e","153B"),_0x1947("0x8f","mo&e"),_0x1947("0x90","h5qi"),"on",_0x1947("0x91","&gjx"),_0x1947("0x92","h5qi"),_0x1947("0x93","0oyh"),_0x1947("0x94","yVOu"),_0x1947("0x95","j7en"),_0x1947("0x96","t2*J"),_0x1947("0x97","0oyh"),_0x1947("0x98","gPxX"),_0x1947("0x99","qKZy"),_0x1947("0x9a","B$xf"),_0x1947("0x9b","153B"),_0x1947("0x9c","yVOu"),_0x1947("0x9d",")9[$"),"a",_0x1947("0x9e","0oyh"),_0x1947("0x9f","DKMC"),_0x1947("0xa0","3@%U"),_0x1947("0xa1","yv2g"),_0x1947("0xa2","dSXL"),_0x1947("0xa3","153B"),_0x1947("0xa4","gD65"),_0x1947("0xa5","%D6Q"),_0x1947("0xa6","a#zF"),_0x1947("0xa7","RVbg"),_0x1947("0xa8","IQhz"),_0x1947("0xa9","3#8e"),_0x1947("0xaa","3#8e"),"/w","-h",_0x1947("0xab","RVbg"),_0x1947("0xac","!fh@"),_0x1947("0xad","4(nd"),_0x1947("0xae","Egwn"),_0x1947("0xaf","%D6Q"),_0x1947("0xb0","RVbg"),_0x1947("0xb1","x0b%"),_0x1947("0xb2","Pj*]"),_0x1947("0xb3","wb[s"),_0x1947("0xb4","gD65"),_0x1947("0xb5","a#zF"),_0x1947("0xb6","qKZy"),"ul",_0x1947("0xb7","0v*k"),_0x1947("0xb8","Hwkr"),_0x1947("0xb9","3@%U"),_0x1947("0xba","AoCN"),_0x1947("0xbb","DKMC"),_0x1947("0xbc","PN#I"),_0x1947("0xbd","Pj*]"),_0x1947("0xbe","0v*k"),_0x1947("0xbf","DKMC"),_0x1947("0xc0","&gjx"),_0x1947("0xc1","%D6Q"),_0x1947("0xc2","0v*k"),_0x1947("0xc3","v6CM"),_0x1947("0xc4","Egwn"),_0x1947("0xc5","Pj*]"),_0x1947("0xc6","EyTj"),_0x1947("0xc7","DKMC"),_0x1947("0xc8","qN2t"),_0x1947("0xc9","[yQ)"),_0x1947("0xca","gD65"),_0x1947("0xcb","t2*J"),_0x1947("0xcc","3@%U"),_0x1947("0xcd","Rg[e"),_0x1947("0xce","dSXL"),_0x1947("0xcf","^N(e"),_0x1947("0xd0","qKZy"),_0x1947("0xd1","a#zF"),_0x1947("0xd2","x0b%"),_0x1947("0xd3","ek$n"),_0x1947("0xd4","yVOu"),_0x1947("0xd5","%D6Q"),_0x1947("0xd6","o]Lz"),_0x1947("0xd7","gPxX"),_0x1947("0xd8","153B"),_0x1947("0xd9","gPxX"),_0x1947("0xda","Rg[e"),"$t",_0x1947("0xdb","yVOu"),_0x1947("0xdc","o]Lz"),_0x1947("0xdd","IQhz"),_0x1947("0xde","B$xf"),_0x1947("0xdf","yv2g"),_0x1947("0xe0","4(nd"),_0x1947("0xe1","e)!@"),_0x1947("0xe2","Egwn"),_0x1947("0xe3","0oyh"),"/s",_0x1947("0xe4","yv2g"),_0x1947("0xe5","t2*J"),"$1",_0x1947("0xe6","o]Lz"),_0x1947("0xe7","IQhz"),_0x1947("0xe8","!fh@"),_0x1947("0xe9","DKMC"),_0x1947("0xea",")9[$"),_0x1947("0xeb","h5qi"),_0x1947("0xec","IQhz"),_0x1947("0xed","(ly]"),_0x1947("0xee","!fh@"),_0x1947("0xef","IQhz"),_0x1947("0xf0","RVbg"),_0x1947("0xf1","3@%U"),_0x1947("0xf2","qKZy"),_0x1947("0xf3","DKMC"),_0x1947("0xf4","!fh@"),_0x1947("0xf5","hmgB"),_0x1947("0xf6","VdXJ"),_0x1947("0xf7","qKZy"),_0x1947("0xf8","Egwn"),_0x1947("0xf9","ZZ61"),_0x1947("0xfa","HSoF"),_0x1947("0xfb","Egwn"),_0x1947("0xfc","RVbg"),_0x1947("0xfd","O9xQ"),_0x1947("0xfe","dSXL"),_0x1947("0xff","#jD]"),_0x1947("0x100","%D6Q"),_0x1947("0x101","!fh@"),_0x1947("0x102","PN#I"),_0x1947("0x103","h5qi"),_0x1947("0x104",")9[$"),_0x1947("0x105","RVbg"),_0x1947("0x106","dSXL"),_0x1947("0x107","PN#I"),_0x1947("0x108","Hwkr"),_0x1947("0x109","gPxX"),_0x1947("0x10a","DKMC"),"//",_0x1947("0x10b",")9[$"),_0x1947("0x10c","yv2g"),_0x1947("0x10d","3@%U"),_0x1947("0x10e","#jD]"),_0x1947("0x10f","ek$n"),_0x1947("0x110","wb[s"),_0x1947("0x111","%D6Q"),_0x1947("0x112","O9xQ"),_0x1947("0x113","YnFb"),_0x1947("0x114","yv2g"),_0x1947("0x115","%D6Q"),_0x1947("0x116","RVbg"),_0x1947("0x117","IQhz"),_0x1947("0x118","Hwkr"),_0x1947("0x119",")9[$"),_0x1947("0x11a","Hwkr"),_0x1947("0x11b","IQhz"),_0x1947("0x11c","v6CM"),_0x1947("0x11d","Pj*]"),_0x1947("0x11e","[3o^"),_0x1947("0x11f",")9[$"),_0x1947("0x120","PN#I"),_0x1947("0x121","h5qi"),_0x1947("0x122","(ly]"),_0x1947("0x123","B$xf"),_0x1947("0x124","0oyh"),_0x1947("0x125","0oyh"),_0x1947("0x126","VdXJ"),"\n",_0x1947("0x127","yVOu"),_0x1947("0x128","AoCN"),_0x1947("0x129","mo&e"),_0x1947("0x12a","ek$n"),_0x1947("0x12b","Egwn"),_0x1947("0x12c","B$xf"),_0x1947("0x12d","[3o^"),_0x1947("0x12e","AoCN"),_0x1947("0x12f","ek$n"),_0x1947("0x130","qKZy"),_0x1947("0x131","hmgB"),_0x1947("0x132","t2*J"),_0x1947("0x133","o]Lz"),_0x1947("0x134","yv2g"),_0x1947("0x135","153B"),_0x1947("0x136","%D6Q"),"fn",_0x1947("0x137","O9xQ"),_0x1947("0x138","!fh@"),_0x1947("0x139","AoCN"),_0x1947("0x13a","PN#I"),_0x1947("0x13b","VdXJ"),_0x1947("0x13c","o]Lz"),_0x1947("0x13d","wb[s"),_0x1947("0x13e","v6CM"),_0x1947("0x13f","[yQ)"),".",_0x1947("0x140","O9xQ"),_0x1947("0x141","#jD]"),_0x1947("0x142","v6CM"),_0x1947("0x143","Egwn"),_0x1947("0x144","VdXJ"),_0x1947("0x145","yVOu"),_0x1947("0x146","EyTj"),_0x1947("0x147","0oyh"),_0x1947("0x148","j7en"),_0x1947("0x149","O9xQ"),_0x1947("0x14a","RVbg"),_0x1947("0x14b","0oyh"),"<",_0x1947("0x14c","j7en"),_0x1947("0x14d","YnFb"),"\">",_0x1947("0x14e","4(nd"),_0x1947("0x14f","^N(e"),"</",">",_0x1947("0x150","HSoF"),_0x1947("0x151","PN#I"),_0x1947("0x152","hmgB"),_0x1947("0x153","IQhz"),_0x1947("0x154","o]Lz"),_0x1947("0x155","VdXJ"),_0x1947("0x156","Rg[e"),_0x1947("0x157","ZZ61"),_0x1947("0x158","VdXJ"),_0x1947("0x159","[yQ)"),_0x1947("0x15a","IQhz"),_0x1947("0x15b","B$xf"),_0x1947("0x15c","(ly]"),_0x1947("0x15d","PN#I"),_0x1947("0x15e","EyTj"),_0x1947("0x15f","yVOu"),_0x1947("0x160","j7en"),_0x1947("0x161","VdXJ"),_0x1947("0x162","VdXJ"),_0x1947("0x163","3#8e"),_0x1947("0x164","v6CM"),_0x1947("0x165","HSoF"),_0x1947("0x166","3@%U"),_0x1947("0x167","qN2t")," ",_0x1947("0x168","#jD]"),_0x1947("0x169","Hwkr"),_0x1947("0x16a","3@%U"),_0x1947("0x16b","0oyh"),_0x1947("0x16c","yv2g"),_0x1947("0x16d","Hwkr"),_0x1947("0x16e","0oyh"),_0x1947("0x16f","v6CM"),_0x1947("0x170","%D6Q"),_0x1947("0x171","EyTj"),_0x1947("0x172","AoCN"),_0x1947("0x173","(ly]"),_0x1947("0x174","o]Lz"),_0x1947("0x175","qKZy"),_0x1947("0x176","4(nd"),_0x1947("0x177","PN#I"),"%s",_0x1947("0x178","IQhz"),_0x1947("0x179","ZZ61"),_0x1947("0x17a","153B"),_0x1947("0x17b","gD65"),_0x1947("0x17c","0v*k"),_0x1947("0x17d","yVOu"),_0x1947("0x17e","qN2t"),_0x1947("0x17f","EyTj"),_0x1947("0x180","t2*J"),_0x1947("0x181","Pj*]"),_0x1947("0x182","e)!@"),_0x1947("0x183","HSoF"),_0x1947("0x184","#jD]"),_0x1947("0x185","^N(e"),_0x1947("0x186","[3o^"),_0x1947("0x187","PN#I"),_0x1947("0x188","EyTj"),_0x1947("0x189","O9xQ"),_0x1947("0x18a","yVOu"),_0x1947("0x18b",")9[$"),_0x1947("0x18c","v6CM"),_0x1947("0x18d","153B"),_0x1947("0x18e","AoCN"),_0x1947("0x18f","[3o^"),_0x1947("0x190","yVOu"),_0x1947("0x191","hmgB"),_0x1947("0x192","HSoF"),_0x1947("0x193","O9xQ")],_0x5809b1=[_0x3573b5[0],_0x3573b5[1],_0x3573b5[2],_0x3573b5[3],_0x3573b5[4],_0x3573b5[5],_0x3573b5[6],_0x3573b5[7],_0x3573b5[8],_0x3573b5[9],_0x3573b5[10],_0x3573b5[11],_0x3573b5[12],_0x3573b5[13],_0x3573b5[14],_0x3573b5[15]];(function(a,b){(function(b){for(;--b;)a[_0x3573b5[17]](a[_0x3573b5[16]]())})(++b)})(_0x5809b1,169);var _0x1b0072=function(a){a-=0;var b=_0x5809b1[a];return b};(function(a,b){var c=function(){var a=!0;return function(b,c){var d=a?function(){if(c){var a=c[_0x1947("0x194","!fh@")](b,arguments);return c=null,a}}:function(){};return a=!1,d}}(),d=c(this,function(){var a,b=function(){};try{var c=Function(_0x1947("0x195","o]Lz")+_0x1947("0x196","[yQ)")+");");a=c()}catch(b){a=window}a[_0x1947("0x197","EyTj")]?(a[_0x1947("0x1a0","4(nd")][_0x1947("0x1a1","IQhz")]=b,a[_0x1947("0x1a2","VdXJ")][_0x1947("0x1a3","ZZ61")]=b,a[_0x1947("0x1a4","ZZ61")][_0x1947("0x1a5","o]Lz")]=b,a[_0x1947("0x1a6","h5qi")][_0x1947("0x19c","gD65")]=b,a[_0x1947("0x1a7","RVbg")][_0x1947("0x1a8","ZZ61")]=b,a[_0x1947("0x1a9","v6CM")][_0x1947("0x1aa","DKMC")]=b,a[_0x1947("0x1a4","ZZ61")][_0x1947("0x1ab","wb[s")]=b):a[_0x1947("0x198","a#zF")]=function(a){var b={};return b[_0x1947("0x199",")9[$")]=a,b[_0x1947("0x19a","153B")]=a,b[_0x1947("0x19b","[3o^")]=a,b[_0x1947("0x19c","gD65")]=a,b[_0x1947("0x19d","qN2t")]=a,b[_0x1947("0x19e","hmgB")]=a,b[_0x1947("0x19f","gPxX")]=a,b}(b)});if(d(),_0x1b0072(_0x3573b5[18])in a){var e=localStorage[_0x1b0072(_0x3573b5[20])](_0x1b0072(_0x3573b5[19]));e&&(b[_0x1b0072(_0x3573b5[22])][_0x3573b5[21]]+=_0x1b0072(_0x3573b5[23]))}})(window,document),function(a,b){if(_0x3573b5[9]in a){var c=b[_0x1b0072(_0x3573b5[25])](_0x1b0072(_0x3573b5[24]));if(c){c[_0x1b0072(_0x3573b5[26])]+=_0x3573b5[27]+dark_text+_0x3573b5[28];var d=b[_0x1b0072(_0x3573b5[25])](_0x3573b5[29]);d&&d[_0x1b0072(_0x3573b5[38])](_0x1b0072(_0x3573b5[30]),function(a){return a[_0x1b0072(_0x3573b5[31])](),b[_0x1b0072(_0x3573b5[22])][_0x1b0072(_0x3573b5[34])][_0x1b0072(_0x3573b5[33])](_0x1b0072(_0x3573b5[32])),b[_0x3573b5[12]][_0x1b0072(_0x3573b5[34])][_0x3573b5[35]](_0x1b0072(_0x3573b5[32]))?void localStorage[_0x1b0072(_0x3573b5[36])](_0x1b0072(_0x3573b5[19]),!0):void localStorage[_0x1b0072(_0x3573b5[37])](_0x1b0072(_0x3573b5[19]))},!1)}}}(window,document),!function(a){function b(a){return null!==a&&a===a[_0x3573b5[40]]}function c(a){return b(a)?a:9===a[_0x3573b5[41]]&&a[_0x3573b5[42]]}function d(a){var b,d,e={top:0,left:0},f=a&&a[_0x3573b5[43]];return b=f[_0x3573b5[12]],void 0!==a[_0x3573b5[44]]&&(e=a[_0x3573b5[44]]()),d=c(f),{top:e[_0x3573b5[45]]+d[_0x3573b5[46]]-b[_0x3573b5[47]],left:e[_0x3573b5[48]]+d[_0x3573b5[49]]-b[_0x3573b5[50]]}}function e(a){var b=_0x3573b5[51];for(var c in a)a[_0x3573b5[52]](c)&&(b+=c+_0x3573b5[53]+a[c]+_0x3573b5[54]);return b}function f(a){if(!1===k[_0x3573b5[55]](a))return null;for(var b=null,c=a[_0x3573b5[56]]||a[_0x3573b5[57]];null!==c[_0x3573b5[58]];){if(!(c instanceof SVGElement||-1===c[_0x3573b5[21]][_0x3573b5[60]](_0x3573b5[59]))){b=c;break}if(c[_0x3573b5[4]][_0x3573b5[35]](_0x3573b5[59])){b=c;break}c=c[_0x3573b5[58]]}return b}function g(b){var c=f(b);null!==c&&(j[_0x3573b5[61]](b,c),_0x3573b5[62]in a&&(c[_0x3573b5[1]](_0x3573b5[63],j[_0x3573b5[64]],!1),c[_0x3573b5[1]](_0x3573b5[65],j[_0x3573b5[64]],!1)),c[_0x3573b5[1]](_0x3573b5[66],j[_0x3573b5[64]],!1),c[_0x3573b5[1]](_0x3573b5[67],j[_0x3573b5[64]],!1))}_0x3573b5[39];var h=h||{},i=document[_0x3573b5[69]][_0x3573b5[68]](document),j={duration:750,show:function(a,b){if(2===a[_0x3573b5[70]])return!1;var c=b||this,f=document[_0x3573b5[72]](_0x3573b5[71]);f[_0x3573b5[21]]=_0x3573b5[73],c[_0x3573b5[74]](f);var g=d(c),h=a[_0x3573b5[75]]-g[_0x3573b5[45]],i=a[_0x3573b5[76]]-g[_0x3573b5[48]],k=_0x3573b5[77]+10*(c[_0x3573b5[78]]/100)+_0x3573b5[79];_0x3573b5[80]in a&&(h=a[_0x3573b5[80]][0][_0x3573b5[75]]-g[_0x3573b5[45]],i=a[_0x3573b5[80]][0][_0x3573b5[76]]-g[_0x3573b5[48]]),f[_0x3573b5[83]](_0x3573b5[81],Date[_0x3573b5[82]]()),f[_0x3573b5[83]](_0x3573b5[84],k),f[_0x3573b5[83]](_0x3573b5[85],i),f[_0x3573b5[83]](_0x3573b5[86],h);var l={top:h+_0x3573b5[87],left:i+_0x3573b5[87]};f[_0x3573b5[21]]+=_0x3573b5[88],f[_0x3573b5[83]](_0x3573b5[89],e(l)),f[_0x3573b5[21]]=f[_0x3573b5[21]][_0x3573b5[91]](_0x3573b5[90],_0x3573b5[51]),l[_0x3573b5[92]]=k,l[_0x3573b5[93]]=k,l[_0x3573b5[94]]=k,l[_0x3573b5[95]]=k,l[_0x3573b5[96]]=k,l[_0x3573b5[97]]=_0x3573b5[98],l[_0x3573b5[99]]=j[_0x3573b5[100]]+_0x3573b5[101],l[_0x3573b5[102]]=j[_0x3573b5[100]]+_0x3573b5[101],l[_0x3573b5[103]]=j[_0x3573b5[100]]+_0x3573b5[101],l[_0x3573b5[104]]=j[_0x3573b5[100]]+_0x3573b5[101],l[_0x3573b5[105]]=_0x3573b5[106],l[_0x3573b5[107]]=_0x3573b5[106],l[_0x3573b5[108]]=_0x3573b5[106],l[_0x3573b5[109]]=_0x3573b5[106],f[_0x3573b5[83]](_0x3573b5[89],e(l))},hide:function(a){k[_0x3573b5[110]](a);var b=this,c=(b[_0x3573b5[78]],null),d=b[_0x3573b5[111]](_0x3573b5[73]);if(!(0<d[_0x3573b5[112]]))return!1;var f=(c=d[d[_0x3573b5[112]]-1])[_0x3573b5[113]](_0x3573b5[85]),g=c[_0x3573b5[113]](_0x3573b5[86]),h=c[_0x3573b5[113]](_0x3573b5[84]),i=350-(Date[_0x3573b5[82]]()-+c[_0x3573b5[113]](_0x3573b5[81]));0>i&&(i=0),setTimeout(function(){var a={top:g+_0x3573b5[87],left:f+_0x3573b5[87],opacity:_0x3573b5[114],"-webkit-transition-duration":j[_0x3573b5[100]]+_0x3573b5[101],"-moz-transition-duration":j[_0x3573b5[100]]+_0x3573b5[101],"-o-transition-duration":j[_0x3573b5[100]]+_0x3573b5[101],"transition-duration":j[_0x3573b5[100]]+_0x3573b5[101],"-webkit-transform":h,"-moz-transform":h,"-ms-transform":h,"-o-transform":h,transform:h};c[_0x3573b5[83]](_0x3573b5[89],e(a)),setTimeout(function(){try{b[_0x3573b5[115]](c)}catch(a){return!1}},j[_0x3573b5[100]])},i)},wrapInput:function(a){for(var b,c=0;c<a[_0x3573b5[112]];c++)if(b=a[c],_0x3573b5[116]===b[_0x3573b5[118]][_0x3573b5[117]]()){var d=b[_0x3573b5[119]];if(_0x3573b5[120]===d[_0x3573b5[118]][_0x3573b5[117]]()&&-1!==d[_0x3573b5[21]][_0x3573b5[60]](_0x3573b5[59]))continue;var e=document[_0x3573b5[72]](_0x3573b5[120]);e[_0x3573b5[21]]=b[_0x3573b5[21]]+_0x3573b5[121];var f=b[_0x3573b5[113]](_0x3573b5[89]);f||(f=_0x3573b5[51]),e[_0x3573b5[83]](_0x3573b5[89],f),b[_0x3573b5[21]]=_0x3573b5[122],b[_0x3573b5[123]](_0x3573b5[89]),d[_0x3573b5[124]](e,b),e[_0x3573b5[74]](b)}}},k={touches:0,allowEvent:function(a){var b=!0;return _0x3573b5[125]===a[_0x3573b5[126]]?k[_0x3573b5[80]]+=1:_0x3573b5[63]===a[_0x3573b5[126]]||_0x3573b5[65]===a[_0x3573b5[126]]?setTimeout(function(){0<k[_0x3573b5[80]]&&(k[_0x3573b5[80]]-=1)},500):_0x3573b5[127]===a[_0x3573b5[126]]&&0<k[_0x3573b5[80]]&&(b=!1),b},touchup:function(a){k[_0x3573b5[55]](a)}};h[_0x3573b5[128]]=function(b){_0x3573b5[100]in(b=b||{})&&(j[_0x3573b5[100]]=b[_0x3573b5[100]]),j[_0x3573b5[130]](i(_0x3573b5[129])),_0x3573b5[62]in a&&document[_0x3573b5[131]][_0x3573b5[1]](_0x3573b5[125],g,!1),document[_0x3573b5[131]][_0x3573b5[1]](_0x3573b5[127],g,!1)},h[_0x3573b5[132]]=function(b){_0x3573b5[116]===b[_0x3573b5[118]][_0x3573b5[117]]()&&(j[_0x3573b5[130]]([b]),b=b[_0x3573b5[58]]),_0x3573b5[62]in a&&b[_0x3573b5[1]](_0x3573b5[125],g,!1),b[_0x3573b5[1]](_0x3573b5[127],g,!1)},a[_0x3573b5[133]]=h,document[_0x3573b5[1]](_0x3573b5[134],function(){h[_0x3573b5[128]]()},!1)}(window);function _0x25c527(){function a(a,b,c){_0x3573b5[39];var d=window[_0x3573b5[136]][_0x3573b5[72]](_0x3573b5[135]),e=b||window[_0x3573b5[136]][_0x3573b5[138]](_0x3573b5[137])[0];d[_0x3573b5[139]]=_0x3573b5[140],d[_0x3573b5[141]]=a,d[_0x3573b5[142]]=_0x3573b5[143],e[_0x3573b5[119]][_0x3573b5[144]](d,e),setTimeout(function(){d[_0x3573b5[142]]=c||_0x3573b5[145]})}function b(){for(var a=document[_0x3573b5[111]](_0x3573b5[146]),b=0;b<a[_0x3573b5[112]];b++)c(a[b])&&(a[b][_0x3573b5[147]]=a[b][_0x3573b5[113]](_0x3573b5[148]))}function c(a){var b=a[_0x3573b5[44]]();return 0<=b[_0x3573b5[149]]&&0<=b[_0x3573b5[150]]&&b[_0x3573b5[45]]<=(window[_0x3573b5[151]]||document[_0x3573b5[12]][_0x3573b5[152]])&&b[_0x3573b5[48]]<=(window[_0x3573b5[153]]||document[_0x3573b5[12]][_0x3573b5[78]])}function d(a,b){window[_0x3573b5[1]]?window[_0x3573b5[1]](a,b):window[_0x3573b5[155]](_0x3573b5[154]+a,b)}for(768<=screen[_0x3573b5[156]]&&$(function(){if($(_0x3573b5[51]+sticky_tag)[_0x3573b5[112]]){var a=$(_0x3573b5[51]+sticky_tag),b=$(_0x3573b5[51]+sticky_tag)[_0x3573b5[157]]()[_0x3573b5[45]],c=$(_0x3573b5[51]+sticky_tag)[_0x3573b5[158]]();$(window)[_0x3573b5[165]](function(){var d=$(_0x3573b5[159])[_0x3573b5[157]]()[_0x3573b5[45]]-c-20,e=$(window)[_0x3573b5[160]]();(b<e?a[_0x3573b5[162]]({position:_0x3573b5[161]}):a[_0x3573b5[162]](_0x3573b5[163],_0x3573b5[164]),d<e)&&a[_0x3573b5[162]]({top:d-e})})}}),$(function(){$(_0x3573b5[170])[_0x3573b5[169]](_0x3573b5[168])[_0x3573b5[167]]()[_0x3573b5[166]]()}),jQuery(document)[_0x3573b5[177]](function(a){var b=a(_0x3573b5[171]);a(window)[_0x3573b5[165]](function(){200<=a(this)[_0x3573b5[160]]()?b[_0x3573b5[61]](10)[_0x3573b5[174]](_0x3573b5[171])[_0x3573b5[173]](_0x3573b5[172]):b[_0x3573b5[174]](_0x3573b5[171])[_0x3573b5[175]](_0x3573b5[172])}),b[_0x3573b5[2]](function(b){b[_0x3573b5[3]](),a(_0x3573b5[176])[_0x3573b5[174]]({scrollTop:0},400)})}),a(_0x3573b5[51]+css1+_0x3573b5[51]),a(_0x3573b5[51]+css2+_0x3573b5[51]),a(_0x3573b5[51]+css3+_0x3573b5[51]),d(_0x3573b5[178],b),d(_0x3573b5[165],b),e=0;1>e;e++)b();window[_0x3573b5[179]]=function(){for(var a=document[_0x3573b5[69]](_0x3573b5[180]),b=0;b<a[_0x3573b5[112]];b++){var c=a[b][_0x3573b5[156]],d=a[b][_0x3573b5[158]];a[b][_0x3573b5[147]]=a[b][_0x3573b5[113]](_0x3573b5[148])[_0x3573b5[91]](_0x3573b5[181],_0x3573b5[182]+c+_0x3573b5[183]+d+_0x3573b5[184])}},loadimage(),$(function(){var a=$(document)[_0x3573b5[160]](),b=$(_0x3573b5[186])[_0x3573b5[185]]();$(window)[_0x3573b5[165]](function(){var c=$(document)[_0x3573b5[160]]();1<=$(document)[_0x3573b5[160]]()&&(c>b?$(_0x3573b5[187])[_0x3573b5[173]](_0x3573b5[165]):$(_0x3573b5[187])[_0x3573b5[175]](_0x3573b5[165])),c>a?$(_0x3573b5[187])[_0x3573b5[175]](_0x3573b5[188]):$(_0x3573b5[187])[_0x3573b5[173]](_0x3573b5[188]),a=$(document)[_0x3573b5[160]]()})}),$(_0x3573b5[194])[_0x3573b5[169]](_0x3573b5[193])[_0x3573b5[192]](_0x3573b5[168])[_0x3573b5[191]](_0x3573b5[141])[_0x3573b5[190]](_0x3573b5[189]),$(_0x3573b5[197])[_0x3573b5[2]](function(){$(this)[_0x3573b5[192]](_0x3573b5[196])[_0x3573b5[195]]()}),$(_0x3573b5[198])[_0x3573b5[169]](_0x3573b5[193])[_0x3573b5[192]](_0x3573b5[168])[_0x3573b5[191]](_0x3573b5[141])[_0x3573b5[190]](_0x3573b5[189]),$(_0x3573b5[199])[_0x3573b5[2]](function(){$(this)[_0x3573b5[192]](_0x3573b5[196])[_0x3573b5[195]]()}),$(document)[_0x3573b5[177]](function(){$(_0x3573b5[202])[_0x3573b5[2]](function(){$(_0x3573b5[201])[_0x3573b5[190]](_0x3573b5[200])})}),$(document)[_0x3573b5[177]](function(){$(_0x3573b5[205])[_0x3573b5[2]](function(){$(_0x3573b5[204])[_0x3573b5[195]](_0x3573b5[203])})}),$(document)[_0x3573b5[177]](function(){$(_0x3573b5[207])[_0x3573b5[2]](function(){$(_0x3573b5[206])[_0x3573b5[195]](_0x3573b5[203])})}),$(document)[_0x3573b5[177]](function(){$(_0x3573b5[208])[_0x3573b5[2]](function(){$(_0x3573b5[206])[_0x3573b5[195]](_0x3573b5[203])})}),$(document)[_0x3573b5[177]](function(){$(_0x3573b5[209])[_0x3573b5[2]](function(){$(_0x3573b5[201])[_0x3573b5[175]](_0x3573b5[200])})}),$(document)[_0x3573b5[177]](function(){$(_0x3573b5[211])[_0x3573b5[2]](function(){$(_0x3573b5[210])[_0x3573b5[190]](_0x3573b5[200])})}),$(document)[_0x3573b5[177]](function(){$(_0x3573b5[213])[_0x3573b5[2]](function(){$(_0x3573b5[212])[_0x3573b5[195]](_0x3573b5[203])})}),$(document)[_0x3573b5[177]](function(){$(_0x3573b5[215])[_0x3573b5[2]](function(){$(_0x3573b5[214])[_0x3573b5[195]](_0x3573b5[203])})}),$(document)[_0x3573b5[177]](function(){$(_0x3573b5[216])[_0x3573b5[190]](_0x3573b5[59])}),$(_0x3573b5[220])[_0x3573b5[219]](function(){$(this)[_0x3573b5[218]](_0x3573b5[147],$(this)[_0x3573b5[218]](_0x3573b5[147])[_0x3573b5[91]](/\/w150-h150+(\-p-k-no-nu)?\//,_0x3573b5[217]))}),$(document)[_0x3573b5[177]](function(){$(_0x3573b5[223])[_0x3573b5[2]](function(){$(_0x3573b5[222])[_0x3573b5[5]](_0x3573b5[221])})}),768>=screen[_0x3573b5[156]]&&(document[_0x3573b5[225]](_0x3573b5[226])[_0x3573b5[74]](document[_0x3573b5[225]](_0x3573b5[224])),document[_0x3573b5[225]](_0x3573b5[228])[_0x3573b5[74]](document[_0x3573b5[225]](_0x3573b5[227]))),$(document)[_0x3573b5[177]](function(){var a;a=h,function(b){function c(a){b[_0x3573b5[239]]({url:g+_0x3573b5[229]+e[_0x3573b5[230]]+_0x3573b5[231]+(Math[_0x3573b5[236]](Math[_0x3573b5[232]]()*(a[_0x3573b5[235]][_0x3573b5[234]][_0x3573b5[233]]-e[_0x3573b5[230]]-1+1))+1)+_0x3573b5[237],success:d,dataType:_0x3573b5[238],cache:!0})}function d(a){var c=_0x3573b5[51],d=(a=a[_0x3573b5[235]][_0x3573b5[240]])[_0x3573b5[112]];if(0===d)a=!1;else for(;--d;){var g=Math[_0x3573b5[236]](Math[_0x3573b5[232]]()*(d+1)),h=a[d];a[d]=a[g],a[g]=h}for(d=0;d<a[_0x3573b5[112]];d++){for(g=0;g<a[d][_0x3573b5[135]][_0x3573b5[112]];g++)if(_0x3573b5[241]==a[d][_0x3573b5[135]][g][_0x3573b5[139]]){var i=a[d][_0x3573b5[135]][g][_0x3573b5[141]];break}var j=_0x3573b5[242]in a[d]?a[d][_0x3573b5[242]][_0x3573b5[245]][_0x3573b5[91]](/\/s[0-9]+\-c/g,_0x3573b5[243]+e[_0x3573b5[244]]):e[_0x3573b5[247]][_0x3573b5[91]](/\/s[0-9]+(\-c|\/)/,_0x3573b5[243]+e[_0x3573b5[244]]+_0x3573b5[246]);g=a[d][_0x3573b5[248]][_0x3573b5[233]];var k=a[d][_0x3573b5[250]][_0x3573b5[233]][_0x3573b5[249]](0,10);h=a[d][_0x3573b5[252]][0][_0x3573b5[251]][_0x3573b5[233]];var l=k[_0x3573b5[249]](0,4),m=k[_0x3573b5[249]](5,7);c+=_0x3573b5[253]+i+_0x3573b5[254]+g+_0x3573b5[255]+j+_0x3573b5[254]+g+_0x3573b5[256]+g+_0x3573b5[257]+(k=k[_0x3573b5[249]](8,10))+_0x3573b5[258]+(m=e[_0x3573b5[259]][parseInt(m,10)-1])+_0x3573b5[260]+l+_0x3573b5[261]+h+_0x3573b5[262]}b(_0x3573b5[196],f)[_0x3573b5[263]](c)}var e={blogURL:_0x3573b5[51],MaxPost:2,idcontaint:_0x3573b5[264],ImageSize:420,interval:1e4,autoplay:!1,loadingClass:_0x3573b5[265],pBlank:_0x3573b5[266],MonthNames:[_0x3573b5[267],_0x3573b5[268],_0x3573b5[269],_0x3573b5[270],_0x3573b5[271],_0x3573b5[272],_0x3573b5[273],_0x3573b5[274],_0x3573b5[275],_0x3573b5[276],_0x3573b5[277],_0x3573b5[278]],tagName:!1};e=b[_0x3573b5[279]]({},e,a);var f=b(e[_0x3573b5[280]]),g=e[_0x3573b5[281]],h=200*e[_0x3573b5[230]];_0x3573b5[51]===e[_0x3573b5[281]]&&(g=window[_0x3573b5[283]][_0x3573b5[282]]+_0x3573b5[284]+window[_0x3573b5[283]][_0x3573b5[285]]),f[_0x3573b5[288]](_0x3573b5[287])[_0x3573b5[173]](e[_0x3573b5[286]]),b(document)[_0x3573b5[177]](function(){var a=_0x3573b5[289]+e[_0x3573b5[118]];!1===e[_0x3573b5[118]]?b[_0x3573b5[239]]({url:g+_0x3573b5[290],success:c,dataType:_0x3573b5[238],cache:!0}):b[_0x3573b5[239]]({url:g+_0x3573b5[291]+a+_0x3573b5[292]+e[_0x3573b5[230]]+_0x3573b5[293],success:d,dataType:_0x3573b5[238],cache:!0}),setTimeout(function(){if(b(_0x3573b5[297])[_0x3573b5[2]](function(){return b(_0x3573b5[296])[_0x3573b5[295]](b(_0x3573b5[294])),!1}),b(_0x3573b5[299])[_0x3573b5[2]](function(){return b(_0x3573b5[294])[_0x3573b5[298]](b(_0x3573b5[296])),!1}),e[_0x3573b5[300]]){var a=e[_0x3573b5[301]],c=setInterval(_0x3573b5[302],a);b(_0x3573b5[296])[_0x3573b5[295]](b(_0x3573b5[294])),b(_0x3573b5[304])[_0x3573b5[303]](function(){clearInterval(c)},function(){c=setInterval(_0x3573b5[302],a)})}f[_0x3573b5[175]](e[_0x3573b5[286]])},h)})}(jQuery)});var e,f,g,h={blogURL:window[_0x3573b5[283]][_0x3573b5[305]],MaxPost:2,idcontaint:_0x3573b5[306],ImageSize:420,interval:4e3,autoplay:!1,loadingClass:_0x3573b5[265],pBlank:_0x3573b5[307],MonthNames:[_0x3573b5[267],_0x3573b5[268],_0x3573b5[269],_0x3573b5[270],_0x3573b5[271],_0x3573b5[272],_0x3573b5[273],_0x3573b5[274],_0x3573b5[275],_0x3573b5[276],_0x3573b5[277],_0x3573b5[278]],tagName:!1},i={_keyStr:_0x3573b5[308],encode:function(a){var b,c,d,e,f,g,h,j=_0x3573b5[51],k=0;for(a=i[_0x1947("0x1ac","HSoF")](a);k<a[_0x3573b5[112]];)e=(b=a[_0x3573b5[309]](k++))>>2,f=(3&b)<<4|(c=a[_0x3573b5[309]](k++))>>4,g=(15&c)<<2|(d=a[_0x3573b5[309]](k++))>>6,h=63&d,isNaN(c)?g=h=64:isNaN(d)&&(h=64),j=j+this[_0x3573b5[311]][_0x3573b5[310]](e)+this[_0x3573b5[311]][_0x3573b5[310]](f)+this[_0x3573b5[311]][_0x3573b5[310]](g)+this[_0x3573b5[311]][_0x3573b5[310]](h);return j},decode:function(a){var b,c,d,e,f,g,h=_0x3573b5[51],j=0;for(a=a[_0x3573b5[91]](/[^A-Za-z0-9\+\/\=]/g,_0x3573b5[51]);j<a[_0x3573b5[112]];)b=this[_0x3573b5[311]][_0x3573b5[60]](a[_0x3573b5[310]](j++))<<2|(e=this[_0x3573b5[311]][_0x3573b5[60]](a[_0x3573b5[310]](j++)))>>4,c=(15&e)<<4|(f=this[_0x3573b5[311]][_0x3573b5[60]](a[_0x3573b5[310]](j++)))>>2,d=(3&f)<<6|(g=this[_0x3573b5[311]][_0x3573b5[60]](a[_0x3573b5[310]](j++))),h+=String[_0x3573b5[312]](b),64!=f&&(h+=String[_0x3573b5[312]](c)),64!=g&&(h+=String[_0x3573b5[312]](d));return i[_0x1947("0x1ad","dSXL")](h)},_utf8_encode:function(a){a=a[_0x3573b5[91]](/\r\n/g,_0x3573b5[313]);for(var b,c=_0x3573b5[51],d=0;d<a[_0x3573b5[112]];d++)b=a[_0x3573b5[309]](d),128>b?c+=String[_0x3573b5[312]](b):(127<b&&2048>b?c+=String[_0x3573b5[312]](192|b>>6):(c+=String[_0x3573b5[312]](224|b>>12),c+=String[_0x3573b5[312]](128|63&b>>6)),c+=String[_0x3573b5[312]](128|63&b));return c},_utf8_decode:function(a){for(var b=_0x3573b5[51],c=0,d=c1=c2=0;c<a[_0x3573b5[112]];)128>(d=a[_0x3573b5[309]](c))?(b+=String[_0x3573b5[312]](d),c++):191<d&&224>d?(c2=a[_0x3573b5[309]](c+1),b+=String[_0x3573b5[312]]((31&d)<<6|63&c2),c+=2):(c2=a[_0x3573b5[309]](c+1),c3=a[_0x3573b5[309]](c+2),b+=String[_0x3573b5[312]]((15&d)<<12|(63&c2)<<6|63&c3),c+=3);return b}};!function(){try{var a=18,b=i[_0x3573b5[315]](_0x3573b5[314]),c=i[_0x3573b5[315]](_0x3573b5[316]),d=document[_0x3573b5[14]](_0x3573b5[318])[_0x3573b5[317]],e=document[_0x3573b5[14]](_0x3573b5[319])[_0x3573b5[317]]+b;if(i[_0x3573b5[315]](d)==e)return;document[_0x3573b5[321]](_0x3573b5[320]),setInterval(function(){1>=a?window[_0x3573b5[283]][_0x3573b5[141]]=c:document[_0x3573b5[225]](_0x3573b5[322])[_0x3573b5[0]]=--a},1e3)}catch(a){window[_0x3573b5[283]][_0x3573b5[141]]=c}}(),!function(a){_0x3573b5[39];var b=function(b,c){var d=this;d[_0x3573b5[324]]=b,d[_0x3573b5[325]]=a(b),d[_0x3573b5[326]]=d[_0x3573b5[325]][_0x3573b5[192]](),d[_0x3573b5[327]]=a[_0x3573b5[279]]({},a[_0x3573b5[330]][_0x3573b5[329]][_0x3573b5[328]],c),d[_0x3573b5[331]]=0,d[_0x3573b5[332]]()};b[_0x3573b5[333]]={init:function(){var a=this;a[_0x3573b5[326]][_0x3573b5[112]]&&(a[_0x3573b5[334]](),a[_0x3573b5[335]]())},build:function(){var b=this,c=b[_0x3573b5[327]],d=c[_0x3573b5[336]],e=c[_0x3573b5[337]];b[_0x3573b5[338]]=[],b[_0x3573b5[339]]=b[_0x3573b5[325]][_0x3573b5[343]](_0x3573b5[341]+e+_0x3573b5[342])[_0x3573b5[169]](_0x3573b5[340]+e),b[_0x3573b5[326]][_0x3573b5[345]](_0x3573b5[341]+c[_0x3573b5[344]]+_0x3573b5[342]),b[_0x3573b5[326]][_0x3573b5[219]](function(c,e){var f,g=a(e);f=g[_0x3573b5[169]](d)[_0x3573b5[348]](_0x3573b5[347])[_0x3573b5[64]]()[_0x3573b5[346]](),b[_0x3573b5[338]][_0x3573b5[17]](f)}),a[_0x3573b5[350]](c[_0x3573b5[349]])&&c[_0x3573b5[349]][_0x3573b5[351]](b[_0x3573b5[324]])},buildTabMenu:function(){for(var b,c=this,d=c[_0x3573b5[327]],e=d[_0x3573b5[352]],f=c[_0x3573b5[338]],g=_0x3573b5[353]+e+_0x3573b5[354]+d[_0x3573b5[355]]+_0x3573b5[356],h=0,i=f[_0x3573b5[112]],j=function(){var a=arguments;return d[_0x3573b5[358]][_0x3573b5[357]][_0x3573b5[91]](/\{[0-9]\}/g,function(b){var c=+b[_0x3573b5[91]](/\D/g,_0x3573b5[51]);return a[c]||_0x3573b5[51]})};i>h;h++)g+=j(h+1,f[h]);g+=_0x3573b5[359]+e+_0x3573b5[360],c[_0x3573b5[361]]=a(g)[_0x3573b5[362]](c[_0x1947("0x1ae","B$xf")]),b=c[_0x3573b5[361]][_0x3573b5[169]](_0x3573b5[347])[0][_0x3573b5[363]][_0x3573b5[117]](),c[_0x3573b5[361]][_0x3573b5[154]](_0x3573b5[2],b,function(b){var d=a(this),e=d[_0x3573b5[365]]();c[_0x3573b5[61]](e),b[_0x3573b5[3]]()})[_0x3573b5[169]](_0x3573b5[347])[_0x3573b5[364]](_0x3573b5[2])},show:function(b){var c=this,d=c[_0x3573b5[327]],e=d[_0x3573b5[366]];c[_0x3573b5[326]][_0x3573b5[64]]()[_0x3573b5[348]](_0x3573b5[367]+b+_0x3573b5[79])[_0x3573b5[61]](),c[_0x3573b5[361]][_0x3573b5[192]]()[_0x3573b5[175]](e)[_0x3573b5[348]](_0x3573b5[367]+b+_0x3573b5[79])[_0x3573b5[173]](e),a[_0x3573b5[350]](d[_0x3573b5[368]])&&b!==c[_0x3573b5[331]]&&d[_0x3573b5[368]][_0x3573b5[351]](c[_0x3573b5[324]],b),c[_0x3573b5[331]]=b},destroy:function(){var a=this,b=a[_0x3573b5[327]][_0x3573b5[336]];a[_0x3573b5[361]][_0x3573b5[369]](),a[_0x3573b5[326]][_0x3573b5[166]]()[_0x3573b5[166]](),a[_0x3573b5[326]][_0x3573b5[191]](_0x3573b5[89]),a[_0x3573b5[326]][_0x3573b5[192]](b+_0x3573b5[347])[_0x3573b5[191]](_0x3573b5[89]),a[_0x3573b5[325]][_0x3573b5[370]](_0x3573b5[329])}},a[_0x3573b5[330]][_0x3573b5[329]]=function(c,d){return this[_0x3573b5[219]](function(){var e,f=a(this),g=f[_0x3573b5[371]](_0x3573b5[329]);e=_0x3573b5[372]==typeof c&&c,g||f[_0x3573b5[371]](_0x3573b5[329],g=new b(this,e)),_0x3573b5[373]==typeof c&&g[c](d)})},a[_0x3573b5[330]][_0x3573b5[329]][_0x3573b5[328]]={container_class:_0x3573b5[326],tabs_container_class:_0x3573b5[374],active_tab_class:_0x3573b5[375],tab_text_el:_0x3573b5[376],tabsmenu_class:_0x3573b5[377],tabsmenu_el:_0x3573b5[196],tmpl:{tabsmenu_tab:_0x3573b5[378]},onTabSelect:null}}(window[_0x3573b5[323]],window,document),$(function(){$(_0x3573b5[379])[_0x3573b5[329]]()}),f=window,g=document,f[_0x3573b5[380]]=function(a){function b(a,b){return(b=b||g)[_0x3573b5[69]](a)}function c(a){return _0x3573b5[381]==typeof a}function d(a,b){if(void 0!==k[a])for(var c in k[a])k[a][c](b)}function e(){return p[_0x3573b5[0]]=j[_0x3573b5[346]][_0x3573b5[382]],n=!0,q?(s[_0x3573b5[4]][_0x3573b5[384]](j[_0x3573b5[383]][_0x3573b5[382]]),d(_0x3573b5[382],[j]),void i(q,function(a,c){s[_0x3573b5[21]]=t+_0x3573b5[385]+j[_0x3573b5[383]][_0x3573b5[178]],(l=g[_0x3573b5[72]](_0x3573b5[71]))[_0x3573b5[0]]=a;var e=b(_0x3573b5[248],l),f=b(j[_0x3573b5[56]][_0x3573b5[386]],l),i=b(j[_0x3573b5[56]][_0x3573b5[387]]+_0x3573b5[385]+j[_0x3573b5[56]][_0x3573b5[388]],l),k=b(j[_0x3573b5[56]][_0x3573b5[386]],o);if(e=e&&e[0]?e[0][_0x3573b5[0]]:_0x3573b5[51],f[_0x3573b5[112]]&&k[_0x3573b5[112]]){k=k[k[_0x3573b5[112]]-1],g[_0x3573b5[248]]=e,k[_0x3573b5[392]](_0x3573b5[389],_0x3573b5[390]+y+_0x3573b5[391]),l=g[_0x3573b5[72]](_0x3573b5[71]),e=0;for(var m=f[_0x3573b5[112]];e<m;++e)l[_0x3573b5[74]](f[e]);k[_0x3573b5[392]](_0x3573b5[389],l[_0x3573b5[0]]),h(),q=!!i[_0x3573b5[112]]&&i[0][_0x3573b5[141]],n=!1,y++,d(_0x3573b5[178],[j,a,c]),loadimage()}},function(a,b){s[_0x3573b5[4]][_0x3573b5[384]](j[_0x3573b5[383]][_0x3573b5[393]]),n=!1,h(1),d(_0x3573b5[393],[j,a,b])})):(s[_0x3573b5[4]][_0x3573b5[384]](j[_0x3573b5[383]][_0x3573b5[394]]),p[_0x3573b5[0]]=j[_0x3573b5[346]][_0x3573b5[394]],d(_0x3573b5[394],[j]))}function h(a){p[_0x3573b5[0]]=_0x3573b5[51],m&&(l[_0x3573b5[0]]=j[_0x3573b5[346]][a?_0x3573b5[393]:_0x3573b5[178]],(a=l[_0x3573b5[396]])[_0x3573b5[395]]=function(){return 2===j[_0x3573b5[126]]&&(m=!1),e(),!1},p[_0x3573b5[74]](a))}var i=_0x3573b5[397],j={target:{posts:_0x3573b5[398],post:_0x3573b5[399],anchors:_0x3573b5[400],anchor:_0x3573b5[401]},text:{load:_0x3573b5[402],loading:_0x3573b5[402],loaded:_0x3573b5[402],error:_0x3573b5[402]},state:{load:i+_0x3573b5[178],loading:i+_0x3573b5[382],loaded:i+_0x3573b5[394],error:i+_0x3573b5[393]}},k={load:[],loading:[],loaded:[],error:[]};(j=function a(b,c){for(var d in b=b||{},c)b[d]=_0x3573b5[372]==typeof c[d]?a(b[d],c[d]):c[d];return b}(j,a||{}))[_0x3573b5[154]]=function(a,b,c){return void 0===a?k:void 0===b?k[a]:void(void 0===c?k[a][_0x3573b5[17]](b):k[a][c]=b)},j[_0x3573b5[403]]=function(a,b){void 0===b?k[a]=[]:delete k[a][b]};var l=null;i=function(a,b){if(f[_0x3573b5[404]]){var c=new XMLHttpRequest;c[_0x3573b5[405]]=function(){b(c[_0x3573b5[406]],c)},c[_0x3573b5[408]](_0x3573b5[407],a),c[_0x3573b5[409]]()}};var m=1!==j[_0x3573b5[126]],n=!1,o=b(j[_0x3573b5[56]][_0x3573b5[410]])[0],p=b(j[_0x3573b5[56]][_0x3573b5[387]])[0],q=b(j[_0x3573b5[56]][_0x3573b5[388]],p),r=g[_0x3573b5[131]],s=g[_0x3573b5[12]],t=s[_0x3573b5[21]]||_0x3573b5[51],u=o[_0x3573b5[411]]+o[_0x3573b5[412]],v=f[_0x3573b5[151]],w=0,x=null,y=1;return q[_0x3573b5[112]]&&(q=q[0][_0x3573b5[141]],o[_0x3573b5[392]](_0x3573b5[413],_0x3573b5[414]),l=g[_0x3573b5[72]](_0x3573b5[71]),h(),0!==j[_0x3573b5[126]]&&(2===j[_0x3573b5[126]]&&(u=o[_0x3573b5[411]]+o[_0x3573b5[412]],v=f[_0x3573b5[151]],w=r[_0x3573b5[160]]||s[_0x3573b5[160]],n||w+v<u||e()),f[_0x3573b5[1]](_0x3573b5[165],function(){m||(x&&f[_0x3573b5[415]](x),x=f[_0x3573b5[416]](c,500))},!1))),j},new InfiniteScroll({type:0,target:{posts:_0x3573b5[417],post:_0x3573b5[418],anchors:_0x3573b5[419],anchor:_0x3573b5[420]},text:{load:_0x3573b5[421]+load_more+_0x3573b5[422],loading:_0x3573b5[423]+loading_text+_0x3573b5[424],loaded:_0x3573b5[425]+all_post_show+_0x3573b5[424],error:_0x3573b5[426]+error_text+_0x3573b5[422]}})}-1==navigator[_0x3573b5[428]][_0x3573b5[60]](_0x3573b5[427])&&(window[_0x3573b5[1]]?window[_0x3573b5[1]](_0x3573b5[178],_0x25c527,!1):window[_0x3573b5[155]]?window[_0x3573b5[155]](_0x3573b5[405],_0x25c527):window[_0x3573b5[405]]=_0x25c527),$(window)[_0x3573b5[68]](_0x3573b5[178],function(){$(_0x3573b5[430])[_0x3573b5[429]](1e3)});var _0x7d1a=["recent-ui","getElementById","entry","feed","","alternate","rel","link","href","<li class=\"recent-ui\"><a href=\"","\" title=\"","$t","title","\" target=\"_blank\" rel=\"nofollow\">","</a></li>","innerHTML","length","script","createElement","src","feeds/posts/summary?alt=json-in-script&orderby=published&max-results=","&callback=MaterialUIRecent","appendChild","head","getElementsByTagName"];function MaterialUIRecent(a){if(document[_0x7d1a[1]](_0x7d1a[0])){for(var b,c=a[_0x7d1a[3]][_0x7d1a[2]],d=_0x7d1a[4],e=document[_0x7d1a[1]](_0x7d1a[0]),f=0;f<recent_count;f++){for(var g=0;g<recent_count;g++)if(_0x7d1a[5]==c[f][_0x7d1a[7]][g][_0x7d1a[6]]){b=c[f][_0x7d1a[7]][g][_0x7d1a[8]];break}var h;d+=_0x7d1a[9]+b+_0x7d1a[10]+(h=c[f][_0x7d1a[12]][_0x7d1a[11]])+_0x7d1a[13]+h+_0x7d1a[14]}e[_0x7d1a[15]]=d}}$(function(){var a=document[_0x7d1a[1]](_0x7d1a[0]);if(0==a[_0x7d1a[16]]);else{var b=document[_0x7d1a[18]](_0x7d1a[17]);b[_0x7d1a[19]]=recent_post+_0x7d1a[20]+recent_count+_0x7d1a[21],document[_0x7d1a[24]](_0x7d1a[23])[0][_0x7d1a[22]](b)}});
//]]>
</script>
<b:include data='blog' name='google-analytics'/>
</body>
</html>
