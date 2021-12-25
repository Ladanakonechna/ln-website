




/* Copyright 2008 Google. */ (function() { /*

Copyright The Closure Library Authors.
SPDX-License-Identifier: Apache-2.0
*/
(function(){function e(g){this.t={};this.tick=function(h,k,f){this.t[h]=[void 0!=f?f:(new Date).getTime(),k];if(void 0==f)try{window.console.timeStamp("CSI/"+h)}catch(m){}};this.getStartTickTime=function(){return this.t.start[0]};this.tick("start",null,g)}var a;if(window.performance)var d=(a=window.performance.timing)&&a.responseStart;var l=0<d?new e(d):new e;window.jstiming={Timer:e,load:l};if(a){var b=a.navigationStart;0<b&&d>=b&&(window.jstiming.srt=d-b)}if(a){var c=window.jstiming.load;0<b&&d>=
b&&(c.tick("\_wtsrt",void 0,b),c.tick("wtsrt\_","\_wtsrt",d),c.tick("tbsd\_","wtsrt\_"))}try{a=null,window.chrome&&window.chrome.csi&&(a=Math.floor(window.chrome.csi().pageT),c&&0<b&&(c.tick("\_tbnd",void 0,window.chrome.csi().startE),c.tick("tbnd\_","\_tbnd",b))),null==a&&window.gtbExternal&&(a=window.gtbExternal.pageT()),null==a&&window.external&&(a=window.external.pageT,c&&0<b&&(c.tick("\_tbnd",void 0,window.external.startE),c.tick("tbnd\_","\_tbnd",b))),a&&(window.jstiming.pt=a)}catch(g){}})(); })()



/* Copyright 2008 Google. */ (function() { function d(a){return document.getElementById(a)}window.byId=d;function g(a){return a.replace(/^\s+|\s+$/g,"")}window.trim=g;var h=[],k=0;window.JOT\_addListener=function(a,b,c){var f=new String(k++);a={eventName:a,handler:b,compId:c,key:f};h.push(a);return f};window.JOT\_removeListenerByKey=function(a){for(var b=0;b<h.length;b++)if(h[b].key==a){h.splice(b,1);break}};window.JOT\_removeAllListenersForName=function(a){for(var b=0;b<h.length;b++)h[b].eventName==a&&h.splice(b,1)};
window.JOT\_postEvent=function(a,b,c){var f={eventName:a,eventSrc:b||{},payload:c||{}};if(window.JOT\_fullyLoaded)for(b=h.length,c=0;c<b&&c<h.length;c++){var e=h[c];e&&e.eventName==a&&(f.listenerCompId=e.compId||"",(e="function"==typeof e.handler?e.handler:window[e.handler])&&e(f))}else window.JOT\_delayedEvents.push({eventName:a,eventSrc:b,payload:c})};window.JOT\_delayedEvents=[];window.JOT\_fullyLoaded=!1;
window.JOT\_formatRelativeToNow=function(a,b){a=((new Date).getTime()-a)/6E4;if(1440<=a||0>a)return null;var c=0;60<=a&&(a/=60,c=2);2<=a&&c++;return b?window.JOT\_siteRelTimeStrs[c].replace("\_\_duration\_\_",Math.floor(a)):window.JOT\_userRelTimeStrs[c].replace("\_\_duration\_\_",Math.floor(a))}; })()



 

 var breadcrumbs = [{"path":"/project","deleted":false,"title":"\u0420\u041e\u0411\u041e\u0422\u0418/WORKS selection","dir":"ltr"},{"path":"/project/mobilna-portativna-model-mobile-portable-model","deleted":false,"title":"\u041c\u043e\u0431\u0456\u043b\u044c\u043d\u0430 \u043f\u043e\u0440\u0442\u0430\u0442\u0438\u0432\u043d\u0430 \u043c\u043e\u0434\u0435\u043b\u044c/Mobile portable model","dir":"ltr"},{"path":"/project/mobilna-portativna-model-mobile-portable-model/ru","deleted":false,"title":"\u0410\u0432\u0442\u043e\u0440\u0441\u043a\u0438\u0439 \u0442\u0435\u043a\u0441\u0442","dir":"ltr"}];
 var JOT\_clearDotPath = 'http://www.gstatic.com/sites/p/f560b7/system/app/images/cleardot.gif';

 
 var JOT\_userRelTimeStrs = ["a minute ago","\_\_duration\_\_ minutes ago","an hour ago","\_\_duration\_\_ hours ago"];

 
 

 

 var webspace = {"gvizGstaticVersion":"current","enableAnalytics":false,"pageSharingId":"jotspot\_page","codeembeds":{"outerIframeSrc":"https://www.gstatic.com/jotspot/embeds/code/0f08d42392f2000e7e3f3daf5b427a43/outer\_iframe.html","innerIframeSrc":"https://8769012-jotspot-embeds.googleusercontent.com/code/8d87fa64604b2a11fae2ed06104c58d3/inner\_iframe.html"},"enableUniversalAnalytics":false,"sharingPolicy":"OPENED\_WITH\_INDICATOR","siteTitle":"ladanakonechna.com","experiments":{"enableSubpagesGadgetInTakeout":true,"overrideDisableDomainEditing":false,"DisableSiteEditingFeature\_\_disable\_site\_editing":true,"disableDomainEditing":false},"jot2atari":{"eligibility":"INELIGIBLE"},"onepickUrl":"https://docs.google.com/picker","adsensePublisherId":null,"features":{"moreMobileStyleImprovements":null,"subscriptionDataMigrationInProgress":null,"plusBadge":false},"configProperties":{"disableSiteEditing":null},"isPublic":true,"newSitesBaseUrl":"https://sites.google.com","isConsumer":false,"serverFlags":{"jot2AtariLearnMoreUrl":"https://support.google.com/sites/answer/7035197"},"domainAnalyticsAccountId":"","plusPageId":"","signInUrl":"https://accounts.google.com/AccountChooser?continue=http://sites.google.com/a/ladanakonechna.com/ladanakonechna-com/project/mobilna-portativna-model-mobile-portable-model/ru&service=jotspot","analyticsAccountId":"","scottyUrl":"/\_/upload","homePath":"/","siteNoticeUrlEnabled":null,"plusPageUrl":"","adsensePromoClickedOrSiteIneligible":true,"csiReportUri":"http://csi.gstatic.com/csi","sharingId":"jotspot","termsUrl":"//www.google.com/intl/en/policies/terms/","gvizVersion":1,"editorResources":{"sitelayout":["http://www.gstatic.com/sites/p/f560b7/system/app/css/sitelayouteditor.css"],"text":["http://www.gstatic.com/sites/p/f560b7/system/js/codemirror.js","http://www.gstatic.com/sites/p/f560b7/system/app/css/codemirror\_css.css","http://www.gstatic.com/sites/p/f560b7/system/js/trog\_edit\_\_en.js","http://www.gstatic.com/sites/p/f560b7/system/app/css/trogedit.css","/\_/rsrc/1638433988000/system/app/css/editor.css","http://www.gstatic.com/sites/p/f560b7/system/app/css/codeeditor.css","/\_/rsrc/1638433988000/system/app/css/camelot/editor-jfk.css"]},"sharingUrlPrefix":"/\_/sharing","isAdsenseEnabled":true,"domain":"ladanakonechna.com","baseUri":"","name":"ladanakonechna-com","siteTemplateId":false,"siteNoticeRevision":null,"siteNoticeUrlAddress":null,"siteNoticeMessage":null,"page":{"isRtlLocale":false,"canDeleteWebspace":null,"isPageDraft":null,"parentPath":"/project/mobilna-portativna-model-mobile-portable-model","parentWuid":"wuid:gx:580c45f9e3d0439","siteLocale":"uk","timeZone":"America/Los\_Angeles","type":"text","title":"\u0410\u0432\u0442\u043e\u0440\u0441\u043a\u0438\u0439 \u0442\u0435\u043a\u0441\u0442","locale":"en","wuid":"wuid:gx:7e626ee86516d03c","revision":15,"path":"/project/mobilna-portativna-model-mobile-portable-model/ru","isSiteRtlLocale":false,"pageInheritsPermissions":null,"name":"ru","canChangePath":true,"state":"","properties":{},"bidiEnabled":false,"currentTemplate":{"path":"/system/app/pagetemplates/text","title":"Web Page"}},"canPublishScriptToAnyone":true,"user":{"keyboardShortcuts":true,"sessionIndex":"","guest\_":true,"displayNameOrEmail":"guest","userName":"guest","uid":"","renderMobile":false,"domain":"","namespace":"","hasWriteAccess":false,"namespaceUser":false,"primaryEmail":"guest","hasAdminAccess":false,"isGoogleAdmin":false},"gadgets":{"baseUri":"/system/app/pages/gadgets"}};
 webspace.page.breadcrumbs = breadcrumbs;

 
 var JOT\_siteRelTimeStrs = ["\u0445\u0432\u0438\u043b\u0438\u043d\u0443 \u0442\u043e\u043c\u0443","\_\_duration\_\_ \u0445\u0432\u0438\u043b\u0438\u043d \u0442\u043e\u043c\u0443","\u0433\u043e\u0434\u0438\u043d\u0443 \u0442\u043e\u043c\u0443","\_\_duration\_\_ \u0433\u043e\u0434\u0438\u043d \u0442\u043e\u043c\u0443"];



 window.jstiming.load.tick('scl');
 









Авторский текст - ladanakonechna.com



 window.jstiming.load.tick('cl');
 



 








|  |  |
| --- | --- |
| [ladanakonechna.com](../../index.html) |  |
|  |







|  |  |  |
| --- | --- | --- |
| MENU* [НОВИНИ/NEWS](../../home/news)
* [РОБОТИ/WORKS selection](../../project)
	+ [2021](../2021)
		- [Дисципліноване бачення/ Disciplined Vision](../2021/disciplinovane-bacenna-disciplined-vision)
	+ [2020](../2020)
		- [Images from abroad](../2020/images-from-abroad)
		- [Bodies in the distance](../2020/bodies-in-a-distance)
		- [Ми зіткнемося з можливістю/We shall be confronted with the possibility](../2020/mi-zitknemosa-z-mozlivistu)
		- [Фотозона/Photozone](../2020/photozone)
		- [У листі та в камені (автопортрет)/In foliage and in stone (self-portrait)](../2020/u-listi-ta-v-kameni-avtoportret-in-foliage-and-in-stone-self-portrait)
		- [Без назви (присвячено виставкам)/ Untitled (dedicated to exhibitions)](../2020/bez-nazvi-prisvaceno-vistavkam-untitled-dedicated-to-exhibitions)
		- [Пакунок/Package](../2020/pakunok-package)
		- [The search of a proper sign for the monument to the Polish protests](../2020/posuk-naleznoie-viviski-dla-pam-atnika-polskim-protestam-the-search-of-a-proper-sign-for-the-monument-to-the-polish-protests)
	+ [2019](../2019)
		- [Прапори/Flags](../flags)
		- [Historical pictures of the contemporary ruins](../2019/historical-pictures-of-the-contemporary-ruins)
	+ [2018](../2018)
		- [Background mode](../background-mode)
		- [Demonstration](../demonstration)
		- [Some examples from the field of management](../some-examples-from-the-field-of-management)
	+ [2017](../2017)
		- [Учитель/Teacher](../ucitel-teacher)
	+ [2016](../2016)
		- [Виставка/The exhibition](../the-exhibition)
		- [The music stops. The guests are embarrassed. Pause](../the-music-stops-the-guests-are-embarrassed-pause)
		- [Чорний ящик/Black Box](../cornij-asik-black-box)
		- [artists` motto](../artists-motto)
	+ [2015](../2015)
		- [Merge Visible](../merge-visible)
		- [Град/Hail (Grad)](../grad-hail)
		- [Так звані/The so-called](../tak-zvani-the-so-called)
		- [War in Ukraine](../war-in-ukraine)
		- [Обман дистанції/The deception of distance](../obman-distanciie-the-deception-of-distance)
	+ [2014](../2014)
		- [Мобільна портативна модель/Mobile portable model](../mobilna-portativna-model-mobile-portable-model)
		- [Нерозпочатий діалог другорядних героїв/Unstarted dialogue of unnamed characters](../---unstarted-dialogue-of-unnamed-characters)
		- [Стіл переговорів/Negotiating table](../stil-peregovoriv-negotiation-table)
		- [Фотографії з мого альбому. Придністров'я, 1973/Photos from my album. Transnistria, 1973](../photos-from-my-album-transnistria-1973)
		- [Зарезервовано/Reserved](../reserved)
		- [Зліва направо/From left to right](../from-left-to-right)
	+ [2013](../2013)
		- [Наочний приклад моєї участі/Object lesson of my participation](../naocnij-priklad-moeie-ucasti-object-lesson-of-my-partisipation)
	+ [2012](../2012)
		- [Bad face of Ukraine](../bad-face-of-ukraine)
		- [Drinking a bottle of vodka alone in the park surrounding the CCA Ujazdowski Castle, opposite to the pavilion of Rikrit Tiravanija, during summer festival "Green Jazdów"](../drinking-alone)
		- [Майже теж саме/Almost the same](../majze-tez-same-almost-the-same)
		- [Welcome* if you can fit in](../welcome)
	+ [2011](../2011)
		- [Персональний щит/Personal shield](../personalnij-sit-personal-shield-1)
		- [Ще один день/One More Day](../se-odin-den-one-more-day)
		- [Ентузіазм/Enthusiasm](../entuziazm-enthusiasm)
		- [Поки я бачу/While I can see](../poki-a-bacu-while-i-can-see)
		- [Учні та освітлена площина/ Disciples and the illuminated plane](../-ucni-ta-osvitlena-plosina-disciples-and-the-illuminated-plane)
		- [Монумент для двох/Monument for 2](../monument-dla-dvoh-monument-for-2)
		- [Море/Sea](../more-sea)
	+ [2010](../2010)
		- [Листівки/Cards](../listivki-cards)
		- [Перспектива/Perspective](../perspektiva-perspective)
	+ [2009](../2009)
		- [Місце/Place](../misce-place)
		- [Дослідження систем маніпуляції/Investigation of manipulation mechanisms](../doslidzenna-sistem-manipuliciie-investigation-of-mechanisms-of-manipulation)
		- [Раніше. Тепер. Далі/Before. Now. Further](../ranise-teper-dali-before-now-further)
		- [Три точки зору на спільне поле та три можливості його придбати/Three points of view on common field and three possibilities to own it](../tri-tocki-zoru-na-spilne-pole-ta-tri-mozlivosti-jogo-pridbati-three-points-of-view-on-common-field-and-three-possibilities-to-own-it)
* [ПУБЛІКАЦІЇ/PUBLICATIONS](../../texts)
* [ІНФОРМАЦІЯ/INFO](../../info)

LINKS* [>> Metod Fund](http://www.methodfund.org)
* [>> Кураторське об'єднання ХУДРАДА/Сuratorial Union HUDRADA](http://www.hudrada.tumblr.com)
* [>> Course of Art](http://courseofcontemporaryart.tumblr.com/)
* [>> -ICTM](http://istmkyiv.wordpress.com/)
* [>>PROSTORY](http://prostory.net.ua/)
* [R.E.P. group](../../r-e-p)
	+ [R.E.P. CV](../../r-e-p/r-e-p-cv)
	+ [R.E.P. Projects](../../r-e-p/r-e-p-projects)
 | 
 

[РОБОТИ/WORKS selection](../../project)‎ > ‎[Мобільна портативна модель/Mobile portable model](../mobilna-portativna-model-mobile-portable-model)‎ > ‎
 

Авторский текст





| Лада Наконечна  конструирует свои многосоставные инсталляции, располагая
объекты определенным образом, так, чтобы они задействовали все
пространство и людей, находящихся в нем. Сама конструкция инсталляции остается
открытой к прочитыванию. Такое обнажение приема не позволяет зрителю полностью
попасть в ловушку, выстроенную автором, стать поглощенным спектаклем или событием, а дает
путь к отступу, «остранению». Для галереи Еigen+Аrt Berlin Лада Наконечна делает новую работу “Мобильная переносная модель". Интерес автора, как и прежде, направлен на структуру социальных отношений, взаимозависимость действия и типа
взгляда, восприятия и роли искусства в этом. Она создает «потенциальные пространства»
на территории искусства, в которых эти отношения разворачиваются - проявляются либо
акцентируются. На этот раз Лада Наконечна выстраивает репрессивное
пространство – вносит в галерею металлическую башню, источающую свет. Уподобляясь маяку,
башня ведет, во-первых, к ней самой. Но являясь также и сторожевой башней (watch tower) она, освещая прилегающую территорию, отводит наш взгляд от себя (вовне). Маяк указывает на определенное место. Такое место – место
желания, остров в море неуверенности, беспомощности и одиночества. Маяк ведет к
суше, манит, являет собой знак надежды людей в мире фрагментированном и
атомизированном, в мире, где правят страхи. Башня же – как обещание защитить от угроз личной
безопасности. Помещенный в центр галереи, маяк указывает и на это конкретное место, как
место стабильности. Кажется, что Европа еще способна гарантировать своим жителям  уверенность в завтрашнем дне, сохраняя остатки государства социальных гарантий,
поддерживать ощущение защищенности. Но свет маяка упирается в стены, указывая на явное присутствие
границ, вызывая подозрения в легитимности центра – не является ли он всего лишь
воображаемым, сконструированным и поддержанным желанием тех, кто его в этот центр водрузил?
Центр уже оккупирован самим маяком, там нет ничего кроме мечты и надежды. Благодаря не
критичности, поддержанной страхом, мы оказываемся замкнутыми  в четырех стенах, внутри созданной нами же ловушки. Кажется, зрителю не остается ничего, как следовать логике
системы. Но в то же время он волен не подчиняться ей. Вся эта конструкция в галерее
утрачивает свой смысл без присутствия человека – оставаясь просто набором
металлических предметов с присущими им свойствами. Ведь и сам механизм запускает в работу именно
человек. Те идеи, на которых базируется устройство социальных
отношений, служат подавлению и угнетению, пока дистрибуция ролей предопределена, пока центр
диктует свои правила, а границы так отчетливо формируют отношения, пока судьба  зависит от того, по какую сторону от границы находишься. Лада Наконечна проводит сравнительные
параллели между разным употреблением понятий границы, центра, точки зрения,
в зависимости от специфики их использования. Она задается вопросом: как механизмы,
инструменты, методы, используемые в сфере искусства, могут нам помочь понять
систему социальных отношений. В искусстве нет понятия одного стабильного центра и им
обусловленной периферии, искусство не привязывается к одной точке зрения как
основной, имеющей исключительное право. Каждая художественная единица – определенный
суверенный взгляд, который при этом имеет в виду множественность позиций и взглядов. Искусство имеет длительную историю расширения своих границ,
и теперь, когда, как кажется, искусство пронизывает все сферы жизнедеятельности, работа с
границами приобретает иной характер. Установление границ и центров как методологический прием
позволяет вычленять знание, концентрироваться на какой-то определенной отдельной
области, либо провоцировать в ней конфликт для проявления ее формирующих отношений. Также он позволяет
находить другие типы взглядов, например, отталкиваясь от пограничной ситуации. Тот инструментарий,
который разрабатывает искусство, невозможно отнести к какой-то определенной сфере с ее
компетенциями, это мышление вне предначертанных рамок и
понятий,  которое отказывается использовать сформированные социальными институтами шаблоны. Средства производства в сфере интеллектуального
труда неотчуждаемы и должны быть освобождены от служения полицейским целям. Освободительный
потенциал, кроющийся в искусстве, не желающем поддаться общепринятой системе конкуренции и
свободного рынка, может быть использован для выхода из замкнутого круга
властных отношений, всегда
субъектно-объектных, где угнетенный стремится занять место угнетателя и так до бесконечности. Речь
идет о новом типе отношений, возникающем вне привычной субординации властных отношений, не имеющем
центра и периферии.
 |





 



 |







  







[Sign in](https://accounts.google.com/ServiceLogin?continue=http://sites.google.com/a/ladanakonechna.com/ladanakonechna-com/project/mobilna-portativna-model-mobile-portable-model/ru&service=jotspot)|[Report Abuse](http://sites.google.com/a/ladanakonechna.com/ladanakonechna-com/system/app/pages/reportAbuse)|[Print Page](javascript:;)|Powered By **[Google Sites](http://sites.google.com/site)**






 window.jstiming.load.tick('sjl');
 


 window.jstiming.load.tick('jl');
 

 gsites.HoverPopupMenu.createSiteDropdownMenus('sites-header-nav-dropdown', false);
 

 JOT\_setupNav("2bd", "MENU", false);
 JOT\_addListener('titleChange', 'JOT\_NAVIGATION\_titleChange', 'COMP\_2bd');
 

 JOT\_setupNav("5938840112648904", "LINKS", false);
 JOT\_addListener('titleChange', 'JOT\_NAVIGATION\_titleChange', 'COMP\_5938840112648904');
 

 setTimeout(function() {
 var fingerprint = gsites.date.TimeZone.getFingerprint([1109635200000, 1128902400000, 1130657000000, 1143333000000, 1143806400000, 1145000000000, 1146380000000, 1152489600000, 1159800000000, 1159500000000, 1162095000000, 1162075000000, 1162105500000]);
 gsites.Xhr.send('http://www.ladanakonechna.com/\_/tz', null, null, 'GET', null, null, { afjstz: fingerprint });
 }, 500);


 window.onload = function() {
 if (false) {
 JOT\_setMobilePreview();
 }
 var loadTimer = window.jstiming.load;
 loadTimer.tick("ol");
 loadTimer["name"] = "load," + webspace.page.type + ",user\_page";
 window.jstiming.report(loadTimer, {}, 'http://csi.gstatic.com/csi');
 }
 

 JOT\_insertAnalyticsCode(false,
 false);
 

 var maestroRunner = new gsites.pages.view.SitesMaestroRunner(
 webspace, "uk");
 maestroRunner.initListeners();
 maestroRunner.installEditRender();
 

 JOT\_insertTranslateCode('en', 'uk');
 

 //<![CDATA[
 // Decorate any fastUI buttons on the page with a class of 'goog-button'.
 if (webspace.user.hasWriteAccess) {
 JOT\_decorateButtons();
 }

 // Fires delayed events.
 (function() {
 JOT\_fullyLoaded = true;
 var delayedEvents = JOT\_delayedEvents;
 for (var x = 0; x < delayedEvents.length; x++) {
 var event = delayedEvents[x];
 JOT\_postEvent(event.eventName, event.eventSrc, event.payload);
 }
 JOT\_delayedEvents = null;
 JOT\_postEvent('pageLoaded');
 })();
 //]]>


 JOT\_postEvent('decorateGvizCharts');
 

 JOT\_setupPostRenderingManager();
 

 JOT\_postEvent('renderPlus', null, 'sites-chrome-main');
 

 sites.codeembed.init();
 
 

 window.jstiming.load.tick('render');
 JOT\_postEvent('usercontentrendered', this);
 


