




/* Copyright 2008 Google. */ (function() { /*

Copyright The Closure Library Authors.
SPDX-License-Identifier: Apache-2.0
*/
(function(){function e(g){this.t={};this.tick=function(h,k,f){this.t[h]=[void 0!=f?f:(new Date).getTime(),k];if(void 0==f)try{window.console.timeStamp("CSI/"+h)}catch(m){}};this.getStartTickTime=function(){return this.t.start[0]};this.tick("start",null,g)}var a;if(window.performance)var d=(a=window.performance.timing)&&a.responseStart;var l=0<d?new e(d):new e;window.jstiming={Timer:e,load:l};if(a){var b=a.navigationStart;0<b&&d>=b&&(window.jstiming.srt=d-b)}if(a){var c=window.jstiming.load;0<b&&d>=
b&&(c.tick("\_wtsrt",void 0,b),c.tick("wtsrt\_","\_wtsrt",d),c.tick("tbsd\_","wtsrt\_"))}try{a=null,window.chrome&&window.chrome.csi&&(a=Math.floor(window.chrome.csi().pageT),c&&0<b&&(c.tick("\_tbnd",void 0,window.chrome.csi().startE),c.tick("tbnd\_","\_tbnd",b))),null==a&&window.gtbExternal&&(a=window.gtbExternal.pageT()),null==a&&window.external&&(a=window.external.pageT,c&&0<b&&(c.tick("\_tbnd",void 0,window.external.startE),c.tick("tbnd\_","\_tbnd",b))),a&&(window.jstiming.pt=a)}catch(g){}})(); })()



/* Copyright 2008 Google. */ (function() { function d(a){return document.getElementById(a)}window.byId=d;function g(a){return a.replace(/^\s+|\s+$/g,"")}window.trim=g;var h=[],k=0;window.JOT\_addListener=function(a,b,c){var f=new String(k++);a={eventName:a,handler:b,compId:c,key:f};h.push(a);return f};window.JOT\_removeListenerByKey=function(a){for(var b=0;b<h.length;b++)if(h[b].key==a){h.splice(b,1);break}};window.JOT\_removeAllListenersForName=function(a){for(var b=0;b<h.length;b++)h[b].eventName==a&&h.splice(b,1)};
window.JOT\_postEvent=function(a,b,c){var f={eventName:a,eventSrc:b||{},payload:c||{}};if(window.JOT\_fullyLoaded)for(b=h.length,c=0;c<b&&c<h.length;c++){var e=h[c];e&&e.eventName==a&&(f.listenerCompId=e.compId||"",(e="function"==typeof e.handler?e.handler:window[e.handler])&&e(f))}else window.JOT\_delayedEvents.push({eventName:a,eventSrc:b,payload:c})};window.JOT\_delayedEvents=[];window.JOT\_fullyLoaded=!1;
window.JOT\_formatRelativeToNow=function(a,b){a=((new Date).getTime()-a)/6E4;if(1440<=a||0>a)return null;var c=0;60<=a&&(a/=60,c=2);2<=a&&c++;return b?window.JOT\_siteRelTimeStrs[c].replace("\_\_duration\_\_",Math.floor(a)):window.JOT\_userRelTimeStrs[c].replace("\_\_duration\_\_",Math.floor(a))}; })()



 

 var breadcrumbs = [{"path":"/project","deleted":false,"title":"\u0420\u041e\u0411\u041e\u0422\u0418/WORKS selection","dir":"ltr"},{"path":"/project/misce-place","deleted":false,"title":"\u041c\u0456\u0441\u0446\u0435/Place","dir":"ltr"},{"path":"/project/misce-place/---\_ru","deleted":false,"title":"\u003E\u041d\u0438\u043a\u0438\u0442\u0430 \u041a\u0430\u0434\u0430\u043d \"\u041c\u0435\u0441\u0442\u043e \u0441\u043e\u043c\u043d\u0435\u043d\u0438\u0439\"\_RU","dir":"ltr"}];
 var JOT\_clearDotPath = 'http://www.gstatic.com/sites/p/f560b7/system/app/images/cleardot.gif';

 
 var JOT\_userRelTimeStrs = ["a minute ago","\_\_duration\_\_ minutes ago","an hour ago","\_\_duration\_\_ hours ago"];

 
 

 

 var webspace = {"gvizGstaticVersion":"current","enableAnalytics":false,"pageSharingId":"jotspot\_page","codeembeds":{"outerIframeSrc":"https://www.gstatic.com/jotspot/embeds/code/0f08d42392f2000e7e3f3daf5b427a43/outer\_iframe.html","innerIframeSrc":"https://577366228-jotspot-embeds.googleusercontent.com/code/8d87fa64604b2a11fae2ed06104c58d3/inner\_iframe.html"},"enableUniversalAnalytics":false,"sharingPolicy":"OPENED\_WITH\_INDICATOR","siteTitle":"ladanakonechna.com","experiments":{"enableSubpagesGadgetInTakeout":true,"overrideDisableDomainEditing":false,"DisableSiteEditingFeature\_\_disable\_site\_editing":true,"disableDomainEditing":false},"jot2atari":{"eligibility":"INELIGIBLE"},"onepickUrl":"https://docs.google.com/picker","adsensePublisherId":null,"features":{"moreMobileStyleImprovements":null,"subscriptionDataMigrationInProgress":null,"plusBadge":false},"configProperties":{"disableSiteEditing":null},"isPublic":true,"newSitesBaseUrl":"https://sites.google.com","isConsumer":false,"serverFlags":{"jot2AtariLearnMoreUrl":"https://support.google.com/sites/answer/7035197"},"domainAnalyticsAccountId":"","plusPageId":"","signInUrl":"https://accounts.google.com/AccountChooser?continue=http://sites.google.com/a/ladanakonechna.com/ladanakonechna-com/project/misce-place/---\_ru&service=jotspot","analyticsAccountId":"","scottyUrl":"/\_/upload","homePath":"/","siteNoticeUrlEnabled":null,"plusPageUrl":"","adsensePromoClickedOrSiteIneligible":true,"csiReportUri":"http://csi.gstatic.com/csi","sharingId":"jotspot","termsUrl":"//www.google.com/intl/en/policies/terms/","gvizVersion":1,"editorResources":{"sitelayout":["http://www.gstatic.com/sites/p/f560b7/system/app/css/sitelayouteditor.css"],"text":["http://www.gstatic.com/sites/p/f560b7/system/js/codemirror.js","http://www.gstatic.com/sites/p/f560b7/system/app/css/codemirror\_css.css","http://www.gstatic.com/sites/p/f560b7/system/js/trog\_edit\_\_en.js","http://www.gstatic.com/sites/p/f560b7/system/app/css/trogedit.css","/\_/rsrc/1638433988000/system/app/css/editor.css","http://www.gstatic.com/sites/p/f560b7/system/app/css/codeeditor.css","/\_/rsrc/1638433988000/system/app/css/camelot/editor-jfk.css"]},"sharingUrlPrefix":"/\_/sharing","isAdsenseEnabled":true,"domain":"ladanakonechna.com","baseUri":"","name":"ladanakonechna-com","siteTemplateId":false,"siteNoticeRevision":null,"siteNoticeUrlAddress":null,"siteNoticeMessage":null,"page":{"isRtlLocale":false,"canDeleteWebspace":null,"isPageDraft":null,"parentPath":"/project/misce-place","parentWuid":"wuid:gx:47c1d80fbdef656f","siteLocale":"uk","timeZone":"America/Los\_Angeles","type":"text","title":"\u003E\u041d\u0438\u043a\u0438\u0442\u0430 \u041a\u0430\u0434\u0430\u043d \"\u041c\u0435\u0441\u0442\u043e \u0441\u043e\u043c\u043d\u0435\u043d\u0438\u0439\"\_RU","locale":"en","wuid":"wuid:gx:4415f9269c0b37c","revision":5,"path":"/project/misce-place/---\_ru","isSiteRtlLocale":false,"pageInheritsPermissions":null,"name":"---\_ru","canChangePath":true,"state":"","properties":{},"bidiEnabled":false,"currentTemplate":{"path":"/system/app/pagetemplates/text","title":"Web Page"}},"canPublishScriptToAnyone":true,"user":{"keyboardShortcuts":true,"sessionIndex":"","guest\_":true,"displayNameOrEmail":"guest","userName":"guest","uid":"","renderMobile":false,"domain":"","namespace":"","hasWriteAccess":false,"namespaceUser":false,"primaryEmail":"guest","hasAdminAccess":false,"isGoogleAdmin":false},"gadgets":{"baseUri":"/system/app/pages/gadgets"}};
 webspace.page.breadcrumbs = breadcrumbs;

 
 var JOT\_siteRelTimeStrs = ["\u0445\u0432\u0438\u043b\u0438\u043d\u0443 \u0442\u043e\u043c\u0443","\_\_duration\_\_ \u0445\u0432\u0438\u043b\u0438\u043d \u0442\u043e\u043c\u0443","\u0433\u043e\u0434\u0438\u043d\u0443 \u0442\u043e\u043c\u0443","\_\_duration\_\_ \u0433\u043e\u0434\u0438\u043d \u0442\u043e\u043c\u0443"];



 window.jstiming.load.tick('scl');
 









>Никита Кадан "Место сомнений"\_RU - ladanakonechna.com



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
 

[РОБОТИ/WORKS selection](../../project)‎ > ‎[Місце/Place](../misce-place)‎ > ‎
 

>Никита Кадан "Место сомнений"\_RU





| 
**Место сомнений**
***Никита Кадан*** 
***Художник, член группы Р.Е.П., редактор (вместе с Ингой Цимприх и Зонке Хальманом) онлайн газеты про искусство "Зомби"***


***Лада Наконечная,***
***МЕСТО, Фундация Центр***
***современного искусства,***
***Киев,  03.03.2009***

***Новая работа Лады Наконечной «Место» балансирует между очевидностью показанного и комплексностью значения. Это значение словно собрано из частей и функционирует как машина, производящая вопросы. 
В течение двух недель художница наносила графитным карандашом вертикальные штрихи на стены просторного зала в Староакадемическом корпусе Киево-Могилянской Академии (НаУКМА). Этот зал неравномерно освещен восемью подвешенными к потолку софитами. Там, где луч софита создает на стене светлое пятно, штрихи наносятся с усилием, в затемненных местах они становятся легче и светлее, а там, где элементы интерьера отбрасывают друг на друга тени, штрихов нет вовсе. Таким образом, Лада Наконечная визуально «убирает», уравнивает между собой тени и свет, лишая человека, заходящего в помещение ряда визуальных ориентиров.
Зрителя встречает средне-серое марево, мешающее различать углы между стенами, изгибы сводов, выступающие настенные панели. В то же время перед ним тысячи и тысячи отдельных штрихов, разница между которыми, определяемая нажимом карандаша, заметна лишь вблизи и с трудом. И если акт уравнивания освещенного с затененным путем неравномерной штриховки тяготеет к игре со вниманием зрителя, к ускользанию, то все эти бесчисленные движения карандаша, «количество работы» предъявляют себя с обескураживающей безапелляционностью. То есть, наиболее несомненным из показанного является труд.
Но какого же рода этот предъявленный труд? Или, вернее, каким он пытается казаться?
Это именно однообразный ручной труд – тот, что подвергается в глобализированном мире наибольшей дискриминации. Такой труд является «непристойной изнанкой» товарного изобилия, уделом низкооплачиваемых и бесправных работников. Таким образом, прямое указание на труд, измеряемый количеством, всегда есть столь же прямое указание на оборотную сторону капиталистического благоденствия.
Тот факт, что затраченный на создание «Места» труд все же является квалифицированным (художница использовала опыт тональной моделировки рисунка), остается скрытым за самоочевидностью показанного: предъявленным усилием, утомительным повторением одинаковых движений руки. Эта кажущаяся самоочевидность поддерживается еще и тем, что цель этого труда вовсе не стремится быть выставленной на обозрение. Только большое усилие внимания, анализ того, «как это сделано» дает возможность понять что, собственно, видишь. А именно активизация сознания зрителя и отличает искусство, как производство критического знания от спекулятивного художественного entertainment-а.
Создание этой работы именно в этом пространстве симптоматично, и эта симптоматичность осознана. Художница производит образ «места вообще» именно в том месте, которое сейчас переживает кризис самоопределения.
«Место», в котором реализована работа, очевидно, подвергается тематизации. Упомянутая тональная моделировка в рисунке, используемая обычно для создания иллюзии объема в плоском изображении, здесь стала средством сокрытия реальных объемов частей интерьера. Таким образом, это помещение, многие годы служившее выставочным залом Центра современного искусства при НаУКМА, отчасти лишилось узнаваемости. Такая попытка пресечь узнавание, стереть визуальную характеристику места удивительно точно проецирует себя на сегодняшнюю неопределенность его общественного положения. Работавший с 1995 года в этом помещении Центр объявил в декабре 2008го о своем закрытии. Но через небольшое время, после всех ритуалов прощания, последовала отсрочка участи – еще в течение года Фундация «Центр современного искусства» может, не в полной мере и не самостоятельно, использовать помещение в Староакдемическом корпусе. Эта «посмертная» стадия работы Центра отличается ограниченной способностью к действию (Центр уже не может сам принимать решения об использовании бывшего своего выставочного пространства) и неясностью перспектив. Статус помещения, в котором реализована работа, сейчас пребывает в процессе своего пересмотра – оно может исполнять роли выставочной площадки как Фонда ЦСИ, так и недавно созданного Центра визуальных исследований и самой Академии, и в то же время  готовится к тому, чтобы стать новым пространством для библиотеки НаУКМА. Шаткость положения, неопределенность будущего, неразрешимые сомнения – вот что характеризует  это место сегодня.
Но в то же время эти сомнения продуктивны. Состояние этого места указывает на «другие места» для искусства, или, точнее, на необходимость таких мест. Время ЦСИ при НаУКМА, долго бывшего основным оплотом некоммерческого искусства на украинской сцене, уходит. Местное художественное сообщество остается перед выбором: или принять существование исключительно на территории частного владения (что, на первый взгляд, кажется сегодня безальтернативным), или создать новые формы институционализации и показа искусства. Какими будут эти формы – зависит от продуктивности дискуссии, которая сейчас, пока, идет лишь в ограниченном кругу молодых художников и теоретиков. Возможно, это будут мобильные микро-институции, способные вступать в партнерство с неповоротливыми институциями-тяжеловесами, или же сетевые сообщества, способные само-организовываться для реализации тех или иных проектов, возможно, что-либо иное. Так или иначе, именно уход Центра современного искусства становится отправной точкой для этой дискуссии, а полученная им отсрочка, «посмертный» период – возможностью эту дискуссию локализировать.
Дополнительным элементом к темам труда и места в работе Лады Наконечной становится тема времени. Долгий процесс трудоемкого производства завершается лишь одним вечером показа, после которого стены будут перекрашены. Вложение труда произошло не ради создания вещи. Или, вернее, получившаяся вещь, художественная работа  – лишь средство показа труда и времени, а также предоставления специального места сомнениям и вопросам, которые и происходят от пребывания людей в-месте.
http://www.zombie.ccc-k.net/

>[Місце/Place](../misce-place)*** |





 



 |







  







[Sign in](https://accounts.google.com/ServiceLogin?continue=http://sites.google.com/a/ladanakonechna.com/ladanakonechna-com/project/misce-place/---_ru&service=jotspot)|[Report Abuse](http://sites.google.com/a/ladanakonechna.com/ladanakonechna-com/system/app/pages/reportAbuse)|[Print Page](javascript:;)|Powered By **[Google Sites](http://sites.google.com/site)**






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
 


