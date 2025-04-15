<!doctype html><html lang=es><style>body{overflow-y:hidden;margin:0;background-color:#333633;background-image:url(background.avif);background-attachment:fixed;background-position:50%;background-repeat:no-repeat;background-size:cover;font-family:inter;font-weight:500;font-size:16px;color:#fff}*{box-sizing:border-box!important;user-select:none!important;list-style-type:none!important}*::selection{background-color:rgba(59,117,114,.67)}body>img{opacity:0;position:absolute;top:-32px;left:-64px}main{position:absolute;top:50%;left:50%;transform:translate(-50%,-50%);width:320px;display:flex;flex-direction:column}.box{width:100%;padding:8px;background-color:rgba(20,31,30,.5);border-style:solid;border-color:rgba(0,0,0,.29);border-width:3px;border-radius:11px;box-shadow:0 4px 8px 2px rgba(0,0,0,.33)}section.list{height:392px;margin-bottom:16px}.boxTitle{display:flex;align-items:center;padding-top:2px;padding-left:4px;padding-bottom:8px}.boxTitle span{margin-left:9px}ul.items{display:flex;background-color:rgba(0,0,0,.33);border-radius:4px;width:100%;height:calc(100% - 34px);margin:0;padding:3px;padding-bottom:0;flex-direction:column;overflow-y:auto;scrollbar-width:thin;scrollbar-color:#666 transparent}ul.items li{margin-bottom:3px;display:flex;width:100%;min-height:26px;border-radius:2px;font-size:14px;align-items:center;padding-left:8px;padding-bottom:1px}ul.items li:hover{background-color:rgba(85,85,85,8%)}ul.items li.selected{background-color:rgba(85,85,85,.25)}li .tag{background-color:rgba(58,117,114,.33);border-radius:2px;font-size:10px;font-weight:400;padding-left:4px;padding-right:4px;margin-left:6px;margin-top:1px;pointer-events:none}li .vtag{background-color:rgba(255,255,255,.75);color:#000!important;font-weight:600}section.downloads .downloadButtons{display:flex;height:30px}.downloadButtons a,#overlay article div a{font-size:14px;padding-bottom:1px;color:#fff;text-decoration:none;width:100%;display:flex;align-items:center;justify-content:center;border-radius:3px;min-width:0;cursor:pointer;height:30px}.downloadButtons a.turquoise{background-color:rgba(59,117,114,.67)}.downloadButtons a.turquoise:hover{background-color:rgba(59,117,114,.39)}.downloadButtons a.turquoise:active{background-color:rgba(59,117,114,.2);outline:3px solid rgba(59,117,114,.67)}.downloadButtons a.dark{margin-right:8px;margin-left:8px;background-color:rgba(0,0,0,.29)}.downloadButtons a.dark:last-child{margin-right:0;margin-left:8px}.downloadButtons a.dark:hover{background-color:rgba(0,0,0,.2)}.downloadButtons a.dark:active{background-color:rgba(0,0,0,.15);outline:3px solid rgba(0,0,0,.29)}aside{pointer-events:none}aside *{pointer-events:auto}aside.left{position:absolute;top:0;left:0;height:100vh;padding:12px}aside.left .box{width:180px;border-radius:8px}aside.left img{filter:drop-shadow(0 4px 4px rgba(0,0,0,.33));margin-bottom:12px}aside.left .search{display:flex;gap:6px;padding:6px}.search #optiSearch{width:136px;background:0 0;border:none;outline:none;color:#fff;font-family:Inter;font-size:14px;font-family:500}aside.left .categories{margin-top:8px;display:flex;flex-direction:column;padding:4px;padding-bottom:0}ul.categories li{margin-bottom:4px;height:30px;display:flex;align-items:center;justify-content:center;padding-bottom:1px;border-radius:3px}ul.categories li:hover{background-color:rgba(59,117,114,.2)}ul.categories li.selected{background-color:rgba(59,117,114,.67)}aside.left .bottom{position:absolute;bottom:12px}aside article.box{padding-left:12px;padding-right:12px}aside article.box *{margin:0;font-size:14px;font-weight:400}aside article.box h1{margin-bottom:10px;text-align:center;font-size:16px;font-weight:500}aside article.box b{font-weight:600}aside.left .social{padding:0;padding-left:4px;padding-right:4px;margin:0;margin-top:10px;display:flex;justify-content:center}.social a{margin-left:6px;margin-right:6px;width:32px;height:32px;display:flex;align-items:center;justify-content:center;filter:drop-shadow(0 4px 4px rgba(0,0,0,.33))}.social a:hover{opacity:.66}aside.right{display:flex;flex-direction:column;position:absolute;bottom:0;right:0;padding:12px}aside.right .box{margin-top:12px;width:auto;align-self:flex-end;border-radius:8px;padding:4px;display:flex;gap:4px}aside.right .ad{width:140px;height:290px}.ad img{border-radius:6px;width:100%;height:100%;filter:drop-shadow(0 4px 4px rgba(0,0,0,.33))}aside.right .chat{display:none;border:none;border-radius:8px;filter:drop-shadow(0 4px 4px rgba(0,0,0,.33));height:460px}aside.right button{width:48px;height:32px;border:none;background:0 0;border-radius:3px;display:flex;align-items:center;justify-content:center}aside.right button:hover{background-color:rgba(59,117,114,.25)}aside.right button:active{transform:none}aside.right button.selected{background-color:rgba(59,117,114,.67)}#overlay{display:none;flex-direction:column;justify-content:center;align-items:center;position:absolute;background:#0007;width:100vw;height:100vh;z-index:1}#overlay .title{width:620px;font-size:24px;margin-bottom:12px;display:flex;justify-content:space-between}.title button{width:24px;height:24px;border:none;background:0 0;border-radius:3px;cursor:pointer}#overlay article{width:660px;height:90vh;padding:0 24px;margin-right:-8px;padding-bottom:40px;overflow-y:scroll;scrollbar-width:thin;scrollbar-color:#666 transparent}#overlay article *{user-select:text!important}#overlay .throbber{position:absolute;top:50%;left:50%;animation:spin 1.5s linear infinite}@keyframes spin{from{transform:translate(-50%,-50%)rotate(0)}to{transform:translate(-50%,-50%)rotate(360deg)}}#overlay article div{display:flex;justify-content:center;margin-top:8px}#overlay article div a{max-width:200px;margin:0 4px;-webkit-user-drag:none}#overlay article div img{margin:0 4px}#overlay article h1{font-size:36px;text-align:center;margin-bottom:16px}#overlay article h2{font-size:24px;text-align:center;margin-top:38px;margin-bottom:12px}#overlay article p{font-weight:400;margin:8px 0}#overlay article a{font-weight:600;color:#3b7572}#overlay article code{background-color:rgba(51,68,68,.6);padding-left:6px;padding-right:6px;border-radius:4px}.huggingface{background-color:rgba(252,212,28,.75);color:#000!important;font-weight:600}.huggingface:hover{background-color:rgba(252,212,28,.4)}.huggingface:active{background-color:rgba(252,212,28,.2);outline:3px solid rgba(252,212,28,.5)}.mediafire{background-color:rgba(0,119,255,.75)}.mediafire:hover{background-color:rgba(0,119,255,.4)}.mediafire:active{background-color:rgba(0,119,255,.2);outline:3px solid rgba(0,119,255,.5)}.torrent{background-color:rgba(118,184,63,.75)}.torrent:hover{background-color:rgba(118,184,63,.4)}.torrent:active{background-color:rgba(118,184,63,.2);outline:3px solid rgba(118,184,63,.5)}.archive{background-color:rgba(0,0,0,.75)}.archive:hover{background-color:rgba(0,0,0,.4)}.archive:active{background-color:rgba(0,0,0,.2);outline:3px solid rgba(0,0,0,.5)}.drive{background-color:rgba(66,133,244,.75)}.drive:hover{background-color:rgba(66,133,244,.4)}.drive:active{background-color:rgba(66,133,244,.2);outline:3px solid rgba(66,133,244,.5)}.mega{background-color:rgba(221,20,5,.75)}.mega:hover{background-color:rgba(221,20,5,.4)}.mega:active{background-color:rgba(221,20,5,.2);outline:3px solid rgba(221,20,5,.5)}.other{background-color:rgba(66,66,66,.75)}.other:hover{background-color:rgba(66,66,66,.4)}.other:active{background-color:rgba(66,66,66,.2);outline:3px solid rgba(66,66,66,.5)}@media(max-height:600px){aside article.box{display:none!important}}@media(max-height:494px){section.list{height:calc(100dvh - 102px)!important}}@media(orientation:portrait) or (max-width:705px){main{top:calc(50dvh - 30px);width:calc(100vw - 24px)}section.list{height:calc(100dvh - 290px)!important}aside.right{display:none}aside.left{width:100vw}aside article.box{display:none!important}aside.left img{margin-top:4px;margin-left:4px}aside.left .categories{flex-direction:row;overflow-x:auto;width:calc(100vw - 24px);scrollbar-width:thin;scrollbar-color:#666 transparent;position:absolute;top:calc(100dvh - 68px)}ul.categories li{padding-left:8px;padding-right:8px}aside.left .search{width:calc(100vw - 24px);position:absolute;top:calc(100dvh - 110px);padding:0;padding-left:8px;align-items:center}.search #optiSearch{height:38px;width:100%;font-size:16px}aside.left .bottom{position:absolute;top:18px;right:12px;height:32px}aside.left .social{margin-top:0}#overlay article{width:calc(100vw - 32px)}#overlay .title{width:calc(100vw - 52px)}}@media(max-width:410px){aside.left img{opacity:.5}}</style><title>OptiProjects</title><link href="https://fonts.bunny.net/css2?family=Inter:wght@400..700" rel=stylesheet><link rel=icon href=favicon.png><meta name=darkreader-lock><meta charset=UTF-8><meta property="og:title" content="OptiProjects"><meta property="og:description" content="Página oficial de OptiJuegos. Acá están todos mis proyectos, desde OptiCraft hasta sistemas operativos optimizados."><meta name=description content="Página oficial de OptiJuegos. Acá están todos mis proyectos, desde OptiCraft hasta sistemas operativos optimizados."><meta property="og:url" content="https://optijuegos.github.io"><meta property="theme-color" content="#3B7572"><meta name=viewport content="width=device-width,initial-scale=1"><meta name=google-adsense-account content="ca-pub-7626037243619661"><script async src="https://pagead2.googlesyndication.com/pagead/js/adsbygoogle.js?client=ca-pub-7626037243619661" crossorigin=anonymous></script><div id=overlay><div class=title><span></span>
<button onpointerdown=closeOverlay()><svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="#ffffff" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="lucide lucide-x"><path d="M18 6 6 18"/><path d="m6 6 12 12"/></svg></button></div><article class=box></article><svg class="throbber" xmlns="http://www.w3.org/2000/svg" width="48" height="48" viewBox="0 0 24 24" fill="none" stroke="#ffffff" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="lucide lucide-loader"><path d="M12 2v4"/><path d="m16.2 7.8 2.9-2.9"/><path d="M18 12h4"/><path d="m16.2 16.2 2.9 2.9"/><path d="M12 18v4"/><path d="m4.9 19.1 2.9-2.9"/><path d="M2 12h4"/><path d="m4.9 4.9 2.9 2.9"/></svg></div><main><section class="list box"><div class=boxTitle><svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="#ffffff" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="lucide lucide-list"><path d="M3 12h.01"/><path d="M3 18h.01"/><path d="M3 6h.01"/><path d="M8 12h13"/><path d="M8 18h13"/><path d="M8 6h13"/></svg>
<span></span></div><ul class=items></ul></section><section class="downloads box"><div class=boxTitle><svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="#ffffff" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="lucide lucide-arrow-down"><path d="M12 5v14"/><path d="m19 12-7 7-7-7"/></svg>
<span>Descargas</span></div><div class=downloadButtons></div></section></main><aside class=left><img src=logo.png draggable=false width=208 height=32 alt=OptiProjects><nav><div class="search box"><svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="#ffffffAA" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="lucide lucide-search"><circle cx="11" cy="11" r="8"/><path d="m21 21-4.3-4.3"/></svg>
<input id=optiSearch placeholder=Buscar...></div><ul class="categories box"></ul></nav><div class=bottom><article class=box><h1>Servidores</h1><span><b>Bedrock (1.7 - 1.21):<br>- IP:</b> 209.25.140.223<br><b>- PUERTO:</b> 33216</span></article><div class=social><a href=https://discord.gg/QMa4Yw5mRB draggable=false><svg width="32" height="32" viewBox="0 0 32 32" fill="none" xmlns="http://www.w3.org/2000/svg"><g clip-path="url(#clip0_107_5)"><path d="M27.1071 5.63707C25.0357 4.66791 22.8208 3.96356 20.5051 3.5625C20.2208 4.07665 19.8886 4.76818 19.6595 5.31831C17.1979 4.94812 14.7591 4.94812 12.3429 5.31831C12.1138 4.76818 11.7741 4.07665 11.4872 3.5625C9.16907 3.96356 6.95167 4.6705 4.88025 5.6422C0.702191 11.9558 -0.430415 18.1126 0.135889 24.1819C2.90701 26.2513 5.59255 27.5085 8.23277 28.3311C8.88465 27.4339 9.46605 26.4801 9.9669 25.4751C9.01301 25.1126 8.09937 24.6653 7.2361 24.1459C7.46512 23.9763 7.68914 23.799 7.90558 23.6165C13.171 26.0792 18.8919 26.0792 24.0943 23.6165C24.3133 23.799 24.5373 23.9763 24.7638 24.1459C23.8979 24.6678 22.9818 25.1151 22.0279 25.4776C22.5288 26.4801 23.1077 27.4365 23.7621 28.3336C26.4048 27.511 29.0929 26.2539 31.864 24.1819C32.5285 17.1461 30.7289 11.0458 27.1071 5.63707ZM10.6842 20.4494C9.10363 20.4494 7.80741 18.9737 7.80741 17.1769C7.80741 15.38 9.07595 13.9018 10.6842 13.9018C12.2926 13.9018 13.5888 15.3774 13.561 17.1769C13.5635 18.9737 12.2926 20.4494 10.6842 20.4494ZM21.3157 20.4494C19.7351 20.4494 18.4389 18.9737 18.4389 17.1769C18.4389 15.38 19.7073 13.9018 21.3157 13.9018C22.9239 13.9018 24.2201 15.3774 24.1925 17.1769C24.1925 18.9737 22.9239 20.4494 21.3157 20.4494Z" fill="white"/></g><defs><clipPath id="clip0_107_5"><rect width="32" height="32" fill="white"/></clipPath></defs></svg></a>
<a href=https://www.youtube.com/@OptiProjects draggable=false><svg width="28" height="20" viewBox="0 0 28 20" fill="none" xmlns="http://www.w3.org/2000/svg"><g id="YouTube_play_buttom_dark_icon_(2013-2017) 1" clip-path="url(#clip0_232_5)"><g id="Lozenge"><g id="Group"><path id="Vector" d="M27.6992 4.27974C27.6992 4.27974 27.4258 2.35207 26.5891 1.50324C25.5281 0.388807 24.3359 0.383331 23.7918 0.317615C19.8816 0.0355835 14.0191 0.0355835 14.0191 0.0355835H14.0082C14.0082 0.0355835 8.1457 0.0355835 4.23555 0.317615C3.6914 0.383331 2.49922 0.388807 1.43828 1.50324C0.601561 2.35207 0.328123 4.27974 0.328123 4.27974C0.328123 4.27974 0.0492172 6.54147 0.0492172 8.80593V10.928C0.0492172 13.1925 0.328123 15.4542 0.328123 15.4542C0.328123 15.4542 0.601561 17.3819 1.43828 18.2307C2.50195 19.3451 3.89648 19.3095 4.51719 19.4273C6.75117 19.6409 14.0137 19.7093 14.0137 19.7093C14.0137 19.7093 19.8816 19.7011 23.7918 19.4163C24.3387 19.3506 25.5281 19.3451 26.5891 18.2307C27.4258 17.3819 27.6992 15.4542 27.6992 15.4542C27.6992 15.4542 27.9781 13.1897 27.9781 10.928V8.80593C27.9781 6.54147 27.6992 4.27974 27.6992 4.27974ZM11.1289 13.4991V5.64061L18.6758 9.58357L11.1289 13.4991Z" fill="white"/></g></g></g><defs><clipPath id="clip0_232_5"><rect width="28" height="19.7422" fill="white"/></clipPath></defs></svg></a>
<a href=https://whatsapp.com/channel/0029VaPsMbL1nozCW1GyG03a draggable=false><svg width="26" height="26" viewBox="0 0 26 26" fill="none" xmlns="http://www.w3.org/2000/svg"><path fill-rule="evenodd" clip-rule="evenodd" d="M22.1708 3.77837C19.7376 1.34316 16.5017 0.00136875 13.0541 0C5.9506 0 0.169192 5.7792 0.166349 12.8828C0.165402 15.1535 0.758876 17.37 1.88662 19.3237L0.0582886 26L6.8903 24.2085C8.77264 25.2348 10.892 25.7757 13.049 25.7766H13.0543C20.1571 25.7766 25.939 19.9967 25.9419 12.8931C25.9433 9.45056 24.604 6.21358 22.1708 3.77837ZM13.0543 23.6006H13.0499C11.1278 23.5999 9.24258 23.0837 7.59797 22.108L7.20679 21.8759L3.15264 22.9391L4.23479 18.9876L3.98006 18.5824C2.90781 16.8775 2.34146 14.9069 2.3423 12.8836C2.34466 6.97938 7.14997 2.17596 13.0585 2.17596C15.9196 2.17704 18.6091 3.29236 20.6315 5.31642C22.6539 7.34048 23.7671 10.0309 23.766 12.8922C23.7635 18.7969 18.9583 23.6006 13.0543 23.6006ZM18.9299 15.5807C18.6079 15.4196 17.0247 14.6407 16.7295 14.5333C16.4343 14.4259 16.2197 14.3722 16.005 14.6945C15.7903 15.0167 15.1732 15.7418 14.9853 15.9567C14.7975 16.1715 14.6096 16.1984 14.2876 16.0372C13.9656 15.8761 12.928 15.5362 11.698 14.4395C10.7408 13.5859 10.0944 12.5316 9.90659 12.2094C9.71876 11.8871 9.88662 11.7129 10.0478 11.5524C10.1927 11.4081 10.3698 11.1764 10.5308 10.9884C10.6918 10.8004 10.7455 10.6661 10.8528 10.4513C10.9602 10.2365 10.9065 10.0485 10.826 9.88733C10.7455 9.7262 10.1015 8.14169 9.83314 7.49715C9.57178 6.86942 9.30627 6.95435 9.10861 6.94453C8.92099 6.93519 8.7061 6.93319 8.49145 6.93319C8.27677 6.93319 7.92791 7.01377 7.63272 7.33602C7.33756 7.65831 6.50571 8.43713 6.50571 10.0216C6.50571 11.6061 7.65957 13.1368 7.82059 13.3517C7.98157 13.5666 10.0913 16.8182 13.3216 18.2126C14.0899 18.5442 14.6897 18.7423 15.1573 18.8907C15.9288 19.1357 16.6308 19.1011 17.1857 19.0182C17.8043 18.9258 19.0908 18.2395 19.3592 17.4875C19.6276 16.7355 19.6276 16.091 19.5471 15.9567C19.4666 15.8224 19.2519 15.7418 18.9299 15.5807Z" fill="white"/></svg></a></div></div></aside><aside class=right><a href=https://youtu.be/bUMDjDpg2F0 class=ad draggable=false><img src=host/ad.png draggable=false width=140 height=290>
</a><iframe class=chat src=https://www.chatbro.com/es/18y6a/></iframe><div class=box><button class=selected id=adButton onpointerdown=selectAd()>
<svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="#ffffff" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="lucide lucide-megaphone"><path d="m3 11 18-5v12L3 14v-3z"/><path d="M11.6 16.8a3 3 0 1 1-5.8-1.6"/></svg>
</button>
<button id=chatButton onpointerdown=selectChat()>
<svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="#ffffff" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="lucide lucide-message-square"><path d="M21 15a2 2 0 0 1-2 2H7l-4 4V5a2 2 0 0 1 2-2h14a2 2 0 0 1 2 2z"/></svg></button></div></aside><img src=https://hits.sh/github.com/OptiJuegos/optijuegos.github.io.svg>
<script>var params,defaultCategory=4,showServersIn=4,hug="https://littletest-sorryplease.hf.space/",med="https://www.mediafire.com/file/",go="https://gofile.io/d/",down="https://optijuegos.github.io/?t=Link%20no%20disponible&a=down?game=%22",content=[{title:"Emuladores",description:"Emuladores optimizados",items:[{name:"Citra",tag:"3DS",links:[med+"u03w1u1rxgya2jt"]},{name:"Dolphin",tag:"WII",links:[hug+"Dolphin%20Lite.7z?
