




/* Copyright 2008 Google. */ (function() { /*

Copyright The Closure Library Authors.
SPDX-License-Identifier: Apache-2.0
*/
(function(){function e(g){this.t={};this.tick=function(h,k,f){this.t[h]=[void 0!=f?f:(new Date).getTime(),k];if(void 0==f)try{window.console.timeStamp("CSI/"+h)}catch(m){}};this.getStartTickTime=function(){return this.t.start[0]};this.tick("start",null,g)}var a;if(window.performance)var d=(a=window.performance.timing)&&a.responseStart;var l=0<d?new e(d):new e;window.jstiming={Timer:e,load:l};if(a){var b=a.navigationStart;0<b&&d>=b&&(window.jstiming.srt=d-b)}if(a){var c=window.jstiming.load;0<b&&d>=
b&&(c.tick("\_wtsrt",void 0,b),c.tick("wtsrt\_","\_wtsrt",d),c.tick("tbsd\_","wtsrt\_"))}try{a=null,window.chrome&&window.chrome.csi&&(a=Math.floor(window.chrome.csi().pageT),c&&0<b&&(c.tick("\_tbnd",void 0,window.chrome.csi().startE),c.tick("tbnd\_","\_tbnd",b))),null==a&&window.gtbExternal&&(a=window.gtbExternal.pageT()),null==a&&window.external&&(a=window.external.pageT,c&&0<b&&(c.tick("\_tbnd",void 0,window.external.startE),c.tick("tbnd\_","\_tbnd",b))),a&&(window.jstiming.pt=a)}catch(g){}})(); })()



/* Copyright 2008 Google. */ (function() { function d(a){return document.getElementById(a)}window.byId=d;function g(a){return a.replace(/^\s+|\s+$/g,"")}window.trim=g;var h=[],k=0;window.JOT\_addListener=function(a,b,c){var f=new String(k++);a={eventName:a,handler:b,compId:c,key:f};h.push(a);return f};window.JOT\_removeListenerByKey=function(a){for(var b=0;b<h.length;b++)if(h[b].key==a){h.splice(b,1);break}};window.JOT\_removeAllListenersForName=function(a){for(var b=0;b<h.length;b++)h[b].eventName==a&&h.splice(b,1)};
window.JOT\_postEvent=function(a,b,c){var f={eventName:a,eventSrc:b||{},payload:c||{}};if(window.JOT\_fullyLoaded)for(b=h.length,c=0;c<b&&c<h.length;c++){var e=h[c];e&&e.eventName==a&&(f.listenerCompId=e.compId||"",(e="function"==typeof e.handler?e.handler:window[e.handler])&&e(f))}else window.JOT\_delayedEvents.push({eventName:a,eventSrc:b,payload:c})};window.JOT\_delayedEvents=[];window.JOT\_fullyLoaded=!1;
window.JOT\_formatRelativeToNow=function(a,b){a=((new Date).getTime()-a)/6E4;if(1440<=a||0>a)return null;var c=0;60<=a&&(a/=60,c=2);2<=a&&c++;return b?window.JOT\_siteRelTimeStrs[c].replace("\_\_duration\_\_",Math.floor(a)):window.JOT\_userRelTimeStrs[c].replace("\_\_duration\_\_",Math.floor(a))}; })()



 

 var breadcrumbs = [{"path":"/texts","deleted":false,"title":"\u041f\u0423\u0411\u041b\u0406\u041a\u0410\u0426\u0406\u0407/PUBLICATIONS","dir":"ltr"}];
 var JOT\_clearDotPath = 'http://www.gstatic.com/sites/p/f560b7/system/app/images/cleardot.gif';

 
 var JOT\_userRelTimeStrs = ["a minute ago","\_\_duration\_\_ minutes ago","an hour ago","\_\_duration\_\_ hours ago"];

 
 

 

 var webspace = {"gvizGstaticVersion":"current","enableAnalytics":false,"pageSharingId":"jotspot\_page","codeembeds":{"outerIframeSrc":"https://www.gstatic.com/jotspot/embeds/code/0f08d42392f2000e7e3f3daf5b427a43/outer\_iframe.html","innerIframeSrc":"https://1906416403-jotspot-embeds.googleusercontent.com/code/8d87fa64604b2a11fae2ed06104c58d3/inner\_iframe.html"},"enableUniversalAnalytics":false,"sharingPolicy":"OPENED\_WITH\_INDICATOR","siteTitle":"ladanakonechna.com","experiments":{"enableSubpagesGadgetInTakeout":true,"overrideDisableDomainEditing":false,"DisableSiteEditingFeature\_\_disable\_site\_editing":true,"disableDomainEditing":false},"jot2atari":{"eligibility":"INELIGIBLE"},"onepickUrl":"https://docs.google.com/picker","adsensePublisherId":null,"features":{"moreMobileStyleImprovements":null,"subscriptionDataMigrationInProgress":null,"plusBadge":false},"configProperties":{"disableSiteEditing":null},"isPublic":true,"newSitesBaseUrl":"https://sites.google.com","isConsumer":false,"serverFlags":{"jot2AtariLearnMoreUrl":"https://support.google.com/sites/answer/7035197"},"domainAnalyticsAccountId":"","plusPageId":"","signInUrl":"https://accounts.google.com/AccountChooser?continue=http://sites.google.com/a/ladanakonechna.com/ladanakonechna-com/texts&service=jotspot","analyticsAccountId":"","scottyUrl":"/\_/upload","homePath":"/","siteNoticeUrlEnabled":null,"plusPageUrl":"","adsensePromoClickedOrSiteIneligible":true,"csiReportUri":"http://csi.gstatic.com/csi","sharingId":"jotspot","termsUrl":"//www.google.com/intl/en/policies/terms/","gvizVersion":1,"editorResources":{"sitelayout":["http://www.gstatic.com/sites/p/f560b7/system/app/css/sitelayouteditor.css"],"text":["http://www.gstatic.com/sites/p/f560b7/system/js/codemirror.js","http://www.gstatic.com/sites/p/f560b7/system/app/css/codemirror\_css.css","http://www.gstatic.com/sites/p/f560b7/system/js/trog\_edit\_\_en.js","http://www.gstatic.com/sites/p/f560b7/system/app/css/trogedit.css","/\_/rsrc/1638433988000/system/app/css/editor.css","http://www.gstatic.com/sites/p/f560b7/system/app/css/codeeditor.css","/\_/rsrc/1638433988000/system/app/css/camelot/editor-jfk.css"]},"sharingUrlPrefix":"/\_/sharing","isAdsenseEnabled":true,"domain":"ladanakonechna.com","baseUri":"","name":"ladanakonechna-com","siteTemplateId":false,"siteNoticeRevision":null,"siteNoticeUrlAddress":null,"siteNoticeMessage":null,"page":{"isRtlLocale":false,"canDeleteWebspace":null,"isPageDraft":null,"parentPath":null,"parentWuid":null,"siteLocale":"uk","timeZone":"America/Los\_Angeles","type":"text","title":"\u041f\u0423\u0411\u041b\u0406\u041a\u0410\u0426\u0406\u0407/PUBLICATIONS","locale":"en","wuid":"wuid:gx:1ae99cce5643a002","revision":28,"path":"/texts","isSiteRtlLocale":false,"pageInheritsPermissions":null,"name":"texts","canChangePath":true,"state":"","properties":{},"bidiEnabled":false,"currentTemplate":{"path":"/system/app/pagetemplates/text","title":"Web Page"}},"canPublishScriptToAnyone":true,"user":{"keyboardShortcuts":true,"sessionIndex":"","guest\_":true,"displayNameOrEmail":"guest","userName":"guest","uid":"","renderMobile":false,"domain":"","namespace":"","hasWriteAccess":false,"namespaceUser":false,"primaryEmail":"guest","hasAdminAccess":false,"isGoogleAdmin":false},"gadgets":{"baseUri":"/system/app/pages/gadgets"}};
 webspace.page.breadcrumbs = breadcrumbs;

 
 var JOT\_siteRelTimeStrs = ["\u0445\u0432\u0438\u043b\u0438\u043d\u0443 \u0442\u043e\u043c\u0443","\_\_duration\_\_ \u0445\u0432\u0438\u043b\u0438\u043d \u0442\u043e\u043c\u0443","\u0433\u043e\u0434\u0438\u043d\u0443 \u0442\u043e\u043c\u0443","\_\_duration\_\_ \u0433\u043e\u0434\u0438\u043d \u0442\u043e\u043c\u0443"];



 window.jstiming.load.tick('scl');
 









ПУБЛІКАЦІЇ/PUBLICATIONS - ladanakonechna.com



 window.jstiming.load.tick('cl');
 



 








|  |  |
| --- | --- |
| [ladanakonechna.com](index.html) |  |
|  |







|  |  |  |  |
| --- | --- | --- | --- |
| MENU* [НОВИНИ/NEWS](home/news)
* [РОБОТИ/WORKS selection](project)
	+ [2021](project/2021)
		- [Дисципліноване бачення/ Disciplined Vision](project/2021/disciplinovane-bacenna-disciplined-vision)
	+ [2020](project/2020)
		- [Images from abroad](project/2020/images-from-abroad)
		- [Bodies in the distance](project/2020/bodies-in-a-distance)
		- [Ми зіткнемося з можливістю/We shall be confronted with the possibility](project/2020/mi-zitknemosa-z-mozlivistu)
		- [Фотозона/Photozone](project/2020/photozone)
		- [У листі та в камені (автопортрет)/In foliage and in stone (self-portrait)](project/2020/u-listi-ta-v-kameni-avtoportret-in-foliage-and-in-stone-self-portrait)
		- [Без назви (присвячено виставкам)/ Untitled (dedicated to exhibitions)](project/2020/bez-nazvi-prisvaceno-vistavkam-untitled-dedicated-to-exhibitions)
		- [Пакунок/Package](project/2020/pakunok-package)
		- [The search of a proper sign for the monument to the Polish protests](project/2020/posuk-naleznoie-viviski-dla-pam-atnika-polskim-protestam-the-search-of-a-proper-sign-for-the-monument-to-the-polish-protests)
	+ [2019](project/2019)
		- [Прапори/Flags](project/flags)
		- [Historical pictures of the contemporary ruins](project/2019/historical-pictures-of-the-contemporary-ruins)
	+ [2018](project/2018)
		- [Background mode](project/background-mode)
		- [Demonstration](project/demonstration)
		- [Some examples from the field of management](project/some-examples-from-the-field-of-management)
	+ [2017](project/2017)
		- [Учитель/Teacher](project/ucitel-teacher)
	+ [2016](project/2016)
		- [Виставка/The exhibition](project/the-exhibition)
		- [The music stops. The guests are embarrassed. Pause](project/the-music-stops-the-guests-are-embarrassed-pause)
		- [Чорний ящик/Black Box](project/cornij-asik-black-box)
		- [artists` motto](project/artists-motto)
	+ [2015](project/2015)
		- [Merge Visible](project/merge-visible)
		- [Град/Hail (Grad)](project/grad-hail)
		- [Так звані/The so-called](project/tak-zvani-the-so-called)
		- [War in Ukraine](project/war-in-ukraine)
		- [Обман дистанції/The deception of distance](project/obman-distanciie-the-deception-of-distance)
	+ [2014](project/2014)
		- [Мобільна портативна модель/Mobile portable model](project/mobilna-portativna-model-mobile-portable-model)
		- [Нерозпочатий діалог другорядних героїв/Unstarted dialogue of unnamed characters](project/---unstarted-dialogue-of-unnamed-characters)
		- [Стіл переговорів/Negotiating table](project/stil-peregovoriv-negotiation-table)
		- [Фотографії з мого альбому. Придністров'я, 1973/Photos from my album. Transnistria, 1973](project/photos-from-my-album-transnistria-1973)
		- [Зарезервовано/Reserved](project/reserved)
		- [Зліва направо/From left to right](project/from-left-to-right)
	+ [2013](project/2013)
		- [Наочний приклад моєї участі/Object lesson of my participation](project/naocnij-priklad-moeie-ucasti-object-lesson-of-my-partisipation)
	+ [2012](project/2012)
		- [Bad face of Ukraine](project/bad-face-of-ukraine)
		- [Drinking a bottle of vodka alone in the park surrounding the CCA Ujazdowski Castle, opposite to the pavilion of Rikrit Tiravanija, during summer festival "Green Jazdów"](project/drinking-alone)
		- [Майже теж саме/Almost the same](project/majze-tez-same-almost-the-same)
		- [Welcome* if you can fit in](project/welcome)
	+ [2011](project/2011)
		- [Персональний щит/Personal shield](project/personalnij-sit-personal-shield-1)
		- [Ще один день/One More Day](project/se-odin-den-one-more-day)
		- [Ентузіазм/Enthusiasm](project/entuziazm-enthusiasm)
		- [Поки я бачу/While I can see](project/poki-a-bacu-while-i-can-see)
		- [Учні та освітлена площина/ Disciples and the illuminated plane](project/-ucni-ta-osvitlena-plosina-disciples-and-the-illuminated-plane)
		- [Монумент для двох/Monument for 2](project/monument-dla-dvoh-monument-for-2)
		- [Море/Sea](project/more-sea)
	+ [2010](project/2010)
		- [Листівки/Cards](project/listivki-cards)
		- [Перспектива/Perspective](project/perspektiva-perspective)
	+ [2009](project/2009)
		- [Місце/Place](project/misce-place)
		- [Дослідження систем маніпуляції/Investigation of manipulation mechanisms](project/doslidzenna-sistem-manipuliciie-investigation-of-mechanisms-of-manipulation)
		- [Раніше. Тепер. Далі/Before. Now. Further](project/ranise-teper-dali-before-now-further)
		- [Три точки зору на спільне поле та три можливості його придбати/Three points of view on common field and three possibilities to own it](project/tri-tocki-zoru-na-spilne-pole-ta-tri-mozlivosti-jogo-pridbati-three-points-of-view-on-common-field-and-three-possibilities-to-own-it)
* ПУБЛІКАЦІЇ/PUBLICATIONS
* [ІНФОРМАЦІЯ/INFO](info)

LINKS* [>> Metod Fund](http://www.methodfund.org)
* [>> Кураторське об'єднання ХУДРАДА/Сuratorial Union HUDRADA](http://www.hudrada.tumblr.com)
* [>> Course of Art](http://courseofcontemporaryart.tumblr.com/)
* [>> -ICTM](http://istmkyiv.wordpress.com/)
* [>>PROSTORY](http://prostory.net.ua/)
* [R.E.P. group](r-e-p)
	+ [R.E.P. CV](r-e-p/r-e-p-cv)
	+ [R.E.P. Projects](r-e-p/r-e-p-projects)
 | 
 



ПУБЛІКАЦІЇ/PUBLICATIONS





| **UA >>****Статті онлайн**Текст Керолін Крал **"Деталізувати темряву"** про виставку Лади Наконечної "Фоновий режим", 2018 [>>](https://prostory.net.ua/ua/krytyka/336-detalizuvaty-temriavu)\_\_\_Авторський розділ «Академія. Підвалини» на Prostory [>>](https://prostory.net.ua/ua/avtorski-rozdily/sections/63-rozmovy-akademiia-pidvalyny)Cерія розмов проведених кураторками програми «Академія. Підвалини» Курсу мистецтва Катериною Бадяновою та Ладою Наконечною – практичного дослідження контексту, який визначає функціонування закладів мистецької освіти в Україні та принципів мистецької освіти**RU>>****Статьи онлайн**Cерия Лады Наконечной ***Merge visible.***Евгения Белорусец, 2017 [>>](https://prostory.net.ua/ua/mlp/mystetstvo/92-seriya-lady-nakonechnoj-merge-visible)**"Опыт привлечения тени. Рука, глаз, молния"**. Яна Волкова, 2017 [>>](https://prostory.net.ua/ua/krytyka/204-opyt-privlecheniya-teni-ruka-glaz-molniya) 

---

Academic articlesLada Nakonečna**Razvoj modernističkog umjetničkog obrazovanja u Ukrajini tijekom prve trećine 20. stoljeća****Shaping Modernist Art Education in Ukraine in the First Third of the 20th Century**Život umjetnosti, Zagrebpp. 46-63 [>>](https://www.ipu.hr/content/zivot-umjetnosti/ZU_103-2018_046-063_Nakonecna.pdf)TextsЛада Наконечна "Наприклад. Рецензія на книжку «Щасливі падіння» Євгенії Бєлорусець" PROSTORY [>>](https://prostory.net.ua/ua/krytyka/452-napryklad-retsenziia-na-knyzhku-shchaslyvi-padinnia-yevhenii-bielorusets?fbclid=IwAR2i1I1IR0N2wkuqVI4w3UgLwfefCI2d8KMb4bcKqXHEs6UfeW98gmja2oA)Лада Наконечна/Lada Nakonechna, **"Плани на майбутнє"/ "Plans for the Future"**Передмова/Preface, Метод Фонд, Київ/Method Fund, Kyiv, 2016ст./pp.112-117 (UA/ENG)також онлайн/ as well online on PROSTORY:UA[>> Лада Наконечна "Плани на майбутнє"](https://prostory.net.ua/ua/praktyka/144-plany-na-maibutnie)ENG[>> Lada Nakonechna "Plans for the Future"](https://prostory.net.ua/en/145-plans-for-the-future)
Лада
Наконечна “Учтель”, У *Соціалістичний реалізм. Здаватися іншим. Зошит №1,* за ред. Катерини Бадянової, Лади Наконечної, Дениса Панкратова (Київ: Адеф, 2017), 14-16.  
**Where Curating Is**(collection of essays and interviews with artists dedicated to curatorial practice in Ukraine)publishing house IST, Kharkiv 2018excerpts [>>](https://prostory.net.ua/en/11-publikatsii/praktyka/341-where-curating-is-excerpts)Лада Наконечна **"Місце зупинки: деякі невдачі при створенні "Події"/"Stopping Point: Some Missteps During the Creation of  'Event'"**"У пошуках форм взаємодії"/ "In Search of Spaces of Negotiation",SCM, Київ/Kyiv, 2014ст./pp. 38-43Lada Nakonechna **"In search of a recipient"/****"W poszukiwaniu odbiorcy"**Podroz na wschod – The Journey to the East, CataloguePublished by Galeria Arsenal, Bialystok, Poland, 2011ISBN: 978-83-89778-27-7pp. 122-126 (PL/ENG)Interviews | **ENG >>****Online articles**"Observing the Artist as Another Object". Mariana Matveichuk on the practice of Lada Nakonechna [>>](http://www.eigen-art.com/index.php?article_id=1274&clang=1)Alienation Effects. Lada Nakonechna’s Conceptual Drawings[DB Art Mag >>](https://dbartmag.de/en/88/feature/alienation-effects-lada-nakonechnas-conceptual-drawings/)"To detail darkness". Carolin Krahl (about the exhibition of Lada Nakonechna *Background Mode*), 2018 [>>](https://prostory.net.ua/en/9-publikatsii/krytyka/335-to-detail-darkness)**Articles in periodicals**

---

**ПУБЛІКАЦІЇ/ PUBLICATIONS****solo c****atalogues/publications****Lada Nakonechna** 2015**[>>](https://drive.google.com/file/d/0B6fQWLuDOtylNXR1ZmFUcDNrMW8/view?usp=sharing)**(ENG/DE)**Perspektive. Lada Nakonechna**Universitätsbibliothek Leipzig, 2013 ISBN: 978-3- 910108-76-9 (DE)**group exhibition****c****atalogues****The World on Paper**Deutsche Bank CollectionPalais Populaire, Berlin, 2018Kerber VerlagISBN: 978-3-7356-0516-0p. 206**Walk the Line. Neue Wege der Zeichnung**Kunstmuseum WolfsburgISBN: 978-3-9804827-9-0pp. 70-71 (De)**Festival International d`Art Toulouse, 2014**ISBN: 978-2-35290-137-2p.118 (FR/ENG)**4 Moskow Biennale of Contemporary Art "Rewriting Worlds"**Published by Institute of Contemporary Art, Moskow, 2011ISBN: 978-5-98833-010-3pp. 132-133 (ENG)**Назовні/Exteriors**Index– The Swedish Contemporary Art FoundationISBN: 978-91-633-2928-9pp.138-143**books/****publications****The Global Art Compass. New Directions in 21st- century Art.** Alistair HicksThames and Hudson, London, 2014ISBN: 978-0-500-23919-3pp.160-161**PROTOCOLLUM 2015/16**Publisher: Dickersbach KunstverlagISBN: 978-3-9816206-3-4pp. 268-271 (ENG)**Lada Nakonechna "Leipzig International Art Programme prä****sentiert "Perspektive"**. Anna -Louise Kratzsch.SpinArt, Leipzig, Frühjahr 2011pp. 90-94**Рухливий простір**за редакцією Катерини Міщенко та Сюзанни ШтретлінгАрт книга, Київ, 2018ISBN: 978-617-7242-51-1ст. 42-45 (UA) |





 



 |







  







[Sign in](https://accounts.google.com/ServiceLogin?continue=http://sites.google.com/a/ladanakonechna.com/ladanakonechna-com/texts&service=jotspot)|[Report Abuse](http://sites.google.com/a/ladanakonechna.com/ladanakonechna-com/system/app/pages/reportAbuse)|[Print Page](javascript:;)|Powered By **[Google Sites](http://sites.google.com/site)**






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
 


