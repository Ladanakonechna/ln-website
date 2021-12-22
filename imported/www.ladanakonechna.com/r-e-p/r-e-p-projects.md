




/* Copyright 2008 Google. */ (function() { /*

Copyright The Closure Library Authors.
SPDX-License-Identifier: Apache-2.0
*/
(function(){function e(g){this.t={};this.tick=function(h,k,f){this.t[h]=[void 0!=f?f:(new Date).getTime(),k];if(void 0==f)try{window.console.timeStamp("CSI/"+h)}catch(m){}};this.getStartTickTime=function(){return this.t.start[0]};this.tick("start",null,g)}var a;if(window.performance)var d=(a=window.performance.timing)&&a.responseStart;var l=0<d?new e(d):new e;window.jstiming={Timer:e,load:l};if(a){var b=a.navigationStart;0<b&&d>=b&&(window.jstiming.srt=d-b)}if(a){var c=window.jstiming.load;0<b&&d>=
b&&(c.tick("\_wtsrt",void 0,b),c.tick("wtsrt\_","\_wtsrt",d),c.tick("tbsd\_","wtsrt\_"))}try{a=null,window.chrome&&window.chrome.csi&&(a=Math.floor(window.chrome.csi().pageT),c&&0<b&&(c.tick("\_tbnd",void 0,window.chrome.csi().startE),c.tick("tbnd\_","\_tbnd",b))),null==a&&window.gtbExternal&&(a=window.gtbExternal.pageT()),null==a&&window.external&&(a=window.external.pageT,c&&0<b&&(c.tick("\_tbnd",void 0,window.external.startE),c.tick("tbnd\_","\_tbnd",b))),a&&(window.jstiming.pt=a)}catch(g){}})(); })()



/* Copyright 2008 Google. */ (function() { function d(a){return document.getElementById(a)}window.byId=d;function g(a){return a.replace(/^\s+|\s+$/g,"")}window.trim=g;var h=[],k=0;window.JOT\_addListener=function(a,b,c){var f=new String(k++);a={eventName:a,handler:b,compId:c,key:f};h.push(a);return f};window.JOT\_removeListenerByKey=function(a){for(var b=0;b<h.length;b++)if(h[b].key==a){h.splice(b,1);break}};window.JOT\_removeAllListenersForName=function(a){for(var b=0;b<h.length;b++)h[b].eventName==a&&h.splice(b,1)};
window.JOT\_postEvent=function(a,b,c){var f={eventName:a,eventSrc:b||{},payload:c||{}};if(window.JOT\_fullyLoaded)for(b=h.length,c=0;c<b&&c<h.length;c++){var e=h[c];e&&e.eventName==a&&(f.listenerCompId=e.compId||"",(e="function"==typeof e.handler?e.handler:window[e.handler])&&e(f))}else window.JOT\_delayedEvents.push({eventName:a,eventSrc:b,payload:c})};window.JOT\_delayedEvents=[];window.JOT\_fullyLoaded=!1;
window.JOT\_formatRelativeToNow=function(a,b){a=((new Date).getTime()-a)/6E4;if(1440<=a||0>a)return null;var c=0;60<=a&&(a/=60,c=2);2<=a&&c++;return b?window.JOT\_siteRelTimeStrs[c].replace("\_\_duration\_\_",Math.floor(a)):window.JOT\_userRelTimeStrs[c].replace("\_\_duration\_\_",Math.floor(a))}; })()



 

 var breadcrumbs = [{"path":"/r-e-p","deleted":false,"title":"R.E.P. group","dir":"ltr"},{"path":"/r-e-p/r-e-p-projects","deleted":false,"title":"R.E.P. Projects","dir":"ltr"}];
 var JOT\_clearDotPath = 'http://www.gstatic.com/sites/p/f560b7/system/app/images/cleardot.gif';

 
 var JOT\_userRelTimeStrs = ["a minute ago","\_\_duration\_\_ minutes ago","an hour ago","\_\_duration\_\_ hours ago"];

 
 

 

 var webspace = {"gvizGstaticVersion":"current","enableAnalytics":false,"pageSharingId":"jotspot\_page","codeembeds":{"outerIframeSrc":"https://www.gstatic.com/jotspot/embeds/code/0f08d42392f2000e7e3f3daf5b427a43/outer\_iframe.html","innerIframeSrc":"https://262448135-jotspot-embeds.googleusercontent.com/code/8d87fa64604b2a11fae2ed06104c58d3/inner\_iframe.html"},"enableUniversalAnalytics":false,"sharingPolicy":"OPENED\_WITH\_INDICATOR","siteTitle":"ladanakonechna.com","experiments":{"enableSubpagesGadgetInTakeout":true,"overrideDisableDomainEditing":false,"DisableSiteEditingFeature\_\_disable\_site\_editing":true,"disableDomainEditing":false},"jot2atari":{"eligibility":"INELIGIBLE"},"onepickUrl":"https://docs.google.com/picker","adsensePublisherId":null,"features":{"moreMobileStyleImprovements":null,"subscriptionDataMigrationInProgress":null,"plusBadge":false},"configProperties":{"disableSiteEditing":null},"isPublic":true,"newSitesBaseUrl":"https://sites.google.com","isConsumer":false,"serverFlags":{"jot2AtariLearnMoreUrl":"https://support.google.com/sites/answer/7035197"},"domainAnalyticsAccountId":"","plusPageId":"","signInUrl":"https://accounts.google.com/AccountChooser?continue=http://sites.google.com/a/ladanakonechna.com/ladanakonechna-com/r-e-p/r-e-p-projects&service=jotspot","analyticsAccountId":"","scottyUrl":"/\_/upload","homePath":"/","siteNoticeUrlEnabled":null,"plusPageUrl":"","adsensePromoClickedOrSiteIneligible":true,"csiReportUri":"http://csi.gstatic.com/csi","sharingId":"jotspot","termsUrl":"//www.google.com/intl/en/policies/terms/","gvizVersion":1,"editorResources":{"sitelayout":["http://www.gstatic.com/sites/p/f560b7/system/app/css/sitelayouteditor.css"],"text":["http://www.gstatic.com/sites/p/f560b7/system/js/codemirror.js","http://www.gstatic.com/sites/p/f560b7/system/app/css/codemirror\_css.css","http://www.gstatic.com/sites/p/f560b7/system/js/trog\_edit\_\_en.js","http://www.gstatic.com/sites/p/f560b7/system/app/css/trogedit.css","/\_/rsrc/1638433988000/system/app/css/editor.css","http://www.gstatic.com/sites/p/f560b7/system/app/css/codeeditor.css","/\_/rsrc/1638433988000/system/app/css/camelot/editor-jfk.css"]},"sharingUrlPrefix":"/\_/sharing","isAdsenseEnabled":true,"domain":"ladanakonechna.com","baseUri":"","name":"ladanakonechna-com","siteTemplateId":false,"siteNoticeRevision":null,"siteNoticeUrlAddress":null,"siteNoticeMessage":null,"page":{"isRtlLocale":false,"canDeleteWebspace":null,"isPageDraft":null,"parentPath":"/r-e-p","parentWuid":"wuid:gx:242d1b707563f44b","siteLocale":"uk","timeZone":"America/Los\_Angeles","type":"text","title":"R.E.P. Projects","locale":"en","wuid":"wuid:gx:22c7f07158b1e93a","revision":26,"path":"/r-e-p/r-e-p-projects","isSiteRtlLocale":false,"pageInheritsPermissions":null,"name":"r-e-p-projects","canChangePath":true,"state":"","properties":{},"bidiEnabled":false,"currentTemplate":{"path":"/system/app/pagetemplates/text","title":"Web Page"}},"canPublishScriptToAnyone":true,"user":{"keyboardShortcuts":true,"sessionIndex":"","guest\_":true,"displayNameOrEmail":"guest","userName":"guest","uid":"","renderMobile":false,"domain":"","namespace":"","hasWriteAccess":false,"namespaceUser":false,"primaryEmail":"guest","hasAdminAccess":false,"isGoogleAdmin":false},"gadgets":{"baseUri":"/system/app/pages/gadgets"}};
 webspace.page.breadcrumbs = breadcrumbs;

 
 var JOT\_siteRelTimeStrs = ["\u0445\u0432\u0438\u043b\u0438\u043d\u0443 \u0442\u043e\u043c\u0443","\_\_duration\_\_ \u0445\u0432\u0438\u043b\u0438\u043d \u0442\u043e\u043c\u0443","\u0433\u043e\u0434\u0438\u043d\u0443 \u0442\u043e\u043c\u0443","\_\_duration\_\_ \u0433\u043e\u0434\u0438\u043d \u0442\u043e\u043c\u0443"];



 window.jstiming.load.tick('scl');
 









R.E.P. Projects - ladanakonechna.com



 window.jstiming.load.tick('cl');
 



 








|  |  |
| --- | --- |
| [ladanakonechna.com](../index.html) |  |
|  |







|  |  |  |  |
| --- | --- | --- | --- |
| MENU* [НОВИНИ/NEWS](../home/news)
* [РОБОТИ/WORKS selection](../project)
	+ [2021](../project/2021)
		- [Дисципліноване бачення/ Disciplined Vision](../project/2021/disciplinovane-bacenna-disciplined-vision)
	+ [2020](../project/2020)
		- [Images from abroad](../project/2020/images-from-abroad)
		- [Bodies in the distance](../project/2020/bodies-in-a-distance)
		- [Ми зіткнемося з можливістю/We shall be confronted with the possibility](../project/2020/mi-zitknemosa-z-mozlivistu)
		- [Фотозона/Photozone](../project/2020/photozone)
		- [У листі та в камені (автопортрет)/In foliage and in stone (self-portrait)](../project/2020/u-listi-ta-v-kameni-avtoportret-in-foliage-and-in-stone-self-portrait)
		- [Без назви (присвячено виставкам)/ Untitled (dedicated to exhibitions)](../project/2020/bez-nazvi-prisvaceno-vistavkam-untitled-dedicated-to-exhibitions)
		- [Пакунок/Package](../project/2020/pakunok-package)
		- [The search of a proper sign for the monument to the Polish protests](../project/2020/posuk-naleznoie-viviski-dla-pam-atnika-polskim-protestam-the-search-of-a-proper-sign-for-the-monument-to-the-polish-protests)
	+ [2019](../project/2019)
		- [Прапори/Flags](../project/flags)
		- [Historical pictures of the contemporary ruins](../project/2019/historical-pictures-of-the-contemporary-ruins)
	+ [2018](../project/2018)
		- [Background mode](../project/background-mode)
		- [Demonstration](../project/demonstration)
		- [Some examples from the field of management](../project/some-examples-from-the-field-of-management)
	+ [2017](../project/2017)
		- [Учитель/Teacher](../project/ucitel-teacher)
	+ [2016](../project/2016)
		- [Виставка/The exhibition](../project/the-exhibition)
		- [The music stops. The guests are embarrassed. Pause](../project/the-music-stops-the-guests-are-embarrassed-pause)
		- [Чорний ящик/Black Box](../project/cornij-asik-black-box)
		- [artists` motto](../project/artists-motto)
	+ [2015](../project/2015)
		- [Merge Visible](../project/merge-visible)
		- [Град/Hail (Grad)](../project/grad-hail)
		- [Так звані/The so-called](../project/tak-zvani-the-so-called)
		- [War in Ukraine](../project/war-in-ukraine)
		- [Обман дистанції/The deception of distance](../project/obman-distanciie-the-deception-of-distance)
	+ [2014](../project/2014)
		- [Мобільна портативна модель/Mobile portable model](../project/mobilna-portativna-model-mobile-portable-model)
		- [Нерозпочатий діалог другорядних героїв/Unstarted dialogue of unnamed characters](../project/---unstarted-dialogue-of-unnamed-characters)
		- [Стіл переговорів/Negotiating table](../project/stil-peregovoriv-negotiation-table)
		- [Фотографії з мого альбому. Придністров'я, 1973/Photos from my album. Transnistria, 1973](../project/photos-from-my-album-transnistria-1973)
		- [Зарезервовано/Reserved](../project/reserved)
		- [Зліва направо/From left to right](../project/from-left-to-right)
	+ [2013](../project/2013)
		- [Наочний приклад моєї участі/Object lesson of my participation](../project/naocnij-priklad-moeie-ucasti-object-lesson-of-my-partisipation)
	+ [2012](../project/2012)
		- [Bad face of Ukraine](../project/bad-face-of-ukraine)
		- [Drinking a bottle of vodka alone in the park surrounding the CCA Ujazdowski Castle, opposite to the pavilion of Rikrit Tiravanija, during summer festival "Green Jazdów"](../project/drinking-alone)
		- [Майже теж саме/Almost the same](../project/majze-tez-same-almost-the-same)
		- [Welcome* if you can fit in](../project/welcome)
	+ [2011](../project/2011)
		- [Персональний щит/Personal shield](../project/personalnij-sit-personal-shield-1)
		- [Ще один день/One More Day](../project/se-odin-den-one-more-day)
		- [Ентузіазм/Enthusiasm](../project/entuziazm-enthusiasm)
		- [Поки я бачу/While I can see](../project/poki-a-bacu-while-i-can-see)
		- [Учні та освітлена площина/ Disciples and the illuminated plane](../project/-ucni-ta-osvitlena-plosina-disciples-and-the-illuminated-plane)
		- [Монумент для двох/Monument for 2](../project/monument-dla-dvoh-monument-for-2)
		- [Море/Sea](../project/more-sea)
	+ [2010](../project/2010)
		- [Листівки/Cards](../project/listivki-cards)
		- [Перспектива/Perspective](../project/perspektiva-perspective)
	+ [2009](../project/2009)
		- [Місце/Place](../project/misce-place)
		- [Дослідження систем маніпуляції/Investigation of manipulation mechanisms](../project/doslidzenna-sistem-manipuliciie-investigation-of-mechanisms-of-manipulation)
		- [Раніше. Тепер. Далі/Before. Now. Further](../project/ranise-teper-dali-before-now-further)
		- [Три точки зору на спільне поле та три можливості його придбати/Three points of view on common field and three possibilities to own it](../project/tri-tocki-zoru-na-spilne-pole-ta-tri-mozlivosti-jogo-pridbati-three-points-of-view-on-common-field-and-three-possibilities-to-own-it)
* [ПУБЛІКАЦІЇ/PUBLICATIONS](../texts)
* [ІНФОРМАЦІЯ/INFO](../info)

LINKS* [>> Metod Fund](http://www.methodfund.org)
* [>> Кураторське об'єднання ХУДРАДА/Сuratorial Union HUDRADA](http://www.hudrada.tumblr.com)
* [>> Course of Art](http://courseofcontemporaryart.tumblr.com/)
* [>> -ICTM](http://istmkyiv.wordpress.com/)
* [>>PROSTORY](http://prostory.net.ua/)
* [R.E.P. group](../r-e-p)
	+ [R.E.P. CV](r-e-p-cv)
	+ R.E.P. Projects
 | 
 

[R.E.P. group](../r-e-p)‎ > ‎
 

R.E.P. Projects





| 






---

REVOLUTIONARY
EXPERIMENTAL SPACE     *2004-2005,**Actions in public space, open studio and exhibition in Centre for contemporary art at NaUKMA, Kyiv, Ukraine*

---






OPEN LABORATORY     *2005, Residence in Centre for Contemporary Art at NaUKMA, Kyiv, Ukraine*
**Projects and** **exhibitions****:****Disappointed**, **Ukrainian Hermitage**, **The Oracle,****Kontrol**

---




INTERVENTION     *2005 – 2012*


HEAVENLY
MESSENGERS  


R.E.P. PARTY 2006 [>>](https://vimeo.com/17226090) *video*R.E.P. GALLERY
FAST ARTBROADENING OF MIND WEST-EASTWE WILL R.E.P. YOU! [>>](https://vimeo.com/22308743)*video***UNTITLED ACTION** **[>>](https://vimeo.com/16919274)***video*

---




MEDIATORS     2006 – 2008 

LIRNYK *2006,**Performance, Kyiv, Ukraine*[>>](https://vimeo.com/27596046)*video**documentation 12’45”*ASHUG *2008, Performance, Gyumri , Armenia, video documentation - 11’44”***AKYN** *2009,**Performance, Almaty , Kazahstan, video documentation -  5’53”*YODLER *2011, Performance, Schwaz , Austria, video documentation - 27’08”**Produced by Stadtgalerie Schwaz music, vocal: Barbara Camenzind and Markus
Kluibenschädl
curator: Anna Artaker
audio/video documentation: Johannes* 









*Felder*TRESENE *2011, Performance, Plovdiv, Bulgaria, video documentation - 06’21”**Produced by Art Today Association, PlovdivPerformer: Sonya Ankova GeorgievaLyrics: Diana BotevaCamera: Emil MirazchievProduction: Jakob Racek***PESNIAR** *2011,**Performance,**Białystok**, Poland, video documentation - 27’06”**Produced by**Arsenal gallery, Białystok, Poland*MUSICIANS *2012, First Kyiv Biennale, Ukraine*


---



PATRIOTISM     *2006 ongoing  [>>](https://drive.google.com/file/d/1ujIVbVdMbiBNC2Td5o-yEE36UwVrfTrs/view?usp=sharing) all*PATRIOTISM. HYMN PATRIOTISM. INDELIBLE TRACKS PATRIOTISM. MUSEUM PATRIOTISM. COMMUNITIES PATRIOTISM. THE LETTERPATRIOTISM. CHECKPOINT PATRIOTISM. ART AS A PRESENTPATRIOTISM. POLICY OF CARE PATRIOTISM (FOR “DECISION MAKER”) PATRIOTISM. VERTICAL, HORIZONTAL PATRIOTISM (FOR “CHTO DELAT?”)PATRIOTISM. TYPES OF COMMUNITY PATRIOTISM. COMMON SPACEPATRIOTISM. DREAMS COME TRUEPATRIOTISM. HORIZONPATRIOTISM. CHOICEPATRIOTISM. THE RESOURCES AND COMMON RESOURCESPATRIOTISM. STATE EMBLEM PATRIOTISM. THE LINEPATRIOTISM. AFTER THE FUTURE – TODAY FOREVER 



PATRIOTISM. CHRONOLOGYPATRIOTISM. CHRONOLOGY II PATRIOTISM. REVOLUTIONARY MOMENTPATRIOTISM. UKRAINIAN ART SINCE INDEPENDENCEPATRIOTISM. IMAGE OF AN ENEMY PATRIOTISM. TRICKPATRIOTISM. ON METHOD PATRIOTISM. FENCEPATRIOTISM. INTERNAL UNITY REQUIRES AN OUTSIDE ENEMY PATRIOTISM. IMPARTING KNOWLEDGE PATRIOTISM. SHORT-TERM HOLIDAY PATRIOTISM. HERFORD STORY PATRIOTISM. WAITING SLOGANS PATRIOTISM. SUN OF THE POOR 
**PATRIOTISM. THE PARADE OF HEROES**





---

PRESENTATION OF UKRAINIAN OFFICIAL CULTURE


**R.E.P. – CORRESPONDENT.
ART ACADEMY** *2006*[>>](https://vimeo.com/308190840)*vi**deo,**duration – 40’72”**With support of Institution of Unstable Thoughts, Kyiv, Ukraine/ Munich, Germany. Special thanks to: Lesja Z.*PRESENTATION OF KYIV ART
ACADEMY IN VIENNA ART
ACADEMY *2006, performance, Akademie der bildenden Künste Wien, Post Conceptual Study Program, Austria*R.E.P. – CORRESPONDENT. ARTISTS’ UNION**PRESENTATION OF NATIONAL UNION OF ARTISTS OF UKRAINE IN GALLERY OF ESTONIAN ARTISTS’ UNION** *2006, performance,*Tallinn, Estonia
PRESENTATION OF KYIV ART ACADEMY ANDNATIONAL UNION OF ARTISTS OF UKRAINE *2008, performance, Centre for Contemporary art Zamek Ujazdowski, Warsaw, Poland*

---

**DO YOU?!***2006*RED DOTS 2007– 2008**EXCURSION***2007,**Union of Artists of Ukraine, Odessa*PARTNER CITY *2008, h**appening*KVASS *2008*

---





HEADQUARTERS **Communities project COMMUNITIES PROJECT***2007,**Center for Contemporary Art at NaUKMA, Kyiv, Ukraine***COMMUNITIES**. YOUNG ARTISTS FROM UKRAINE *2007,**Arsenal gallery, Białystok, Poland*NEW UKRAINIAN LANGUAGE*2008,**Karas gallery, Kyiv, Ukraine*COMMON SPACE *2008, Arsenalna square, Escalators of “Arsenalna” metro station, Kyiv, Ukraine***TRANSIT***2008,**Ya-gallery, Kyiv, Ukraine*

---






WE ARE UKRAINIANS.
WHAT ELSE MATTERS? 




---






SMUGGLING   *2007*[>>](https://vimeo.com/27124736)*video*

---






SUPERPROPOSITION   *2008* [>>](https://vimeo.com/33344893)*video*

---

MOTHERLAND SHOP *2007, In collaboration with Mark Titchner, Ukrainian pavilion in the 52 Venice Biennale, Venice, Italy*

---






UKRAINIAN LAND  *2010*[>>](https://vimeo.com/33447207)*video*

---




EURORENOVATION



EURORENOVATION IN EUROPE *2010, Kunstraum Munich, Germany*EURORENOVATION. COLUMN FOR THE MUSEUM *2011, Made as a present to the National Cultural Art and Museum Complex "Mystetskyi Arsenal“ in Kyiv, Ukraine*


EURORENOVATION. CUT *2012, PinchukArtCentre, Kyiv, Ukraine*EURORENOVATION. IMPROVEMENT IS THE WAY *2013, Palazzo Contarini Polignac, Venice, Italy, Future Generation Art Prize @ Venice, Ukrainian Collateral Event on the 55th Venice Biennale (La Biennale di Venezia, 2013)***EURORENOVATION. SPROUTED***2013, Ya Gallery, Dnipropetrovsk*

---




**GREAT SURPRISE** *2010,**National Art Museum of
Ukraine, Kyiv, Ukraine*


---






ON METHOD *2011, Impossible community, Moscow Museum of Modern Art, Russia*

---

ARTWORKS THAT YOU CANNOT ACCEPT    *2013* [UA>>](http://archive.prostory.net.ua/ua/art/605-2013-11-05-08-59-14?fbclid=IwAR0S2ZrFVUB5o0y8ctLjKhV71TwS8WQSMmac05BtmLmPyb4_C3wRWpW2LOw) *Propositions for the exhibition “Grand and Great” in Museum Complex "Mystetskyi Arsenal", Kyiv, Ukraine*

---

MODEL
DEMONSTRATION 

---



**R.E.P. – ON METHOD, 10 YEARS** *2014*

---




STAGE *2009, Revolutionary moments, Center for Contemporary Art at NaUKMA, Kyiv***STAGE. LEVELING
POSITIONS** *2014*

---


**UKRAINIAN ARTISTS REPRESENT UKRAINE AT THE EXHIBITION IN
VIENNA** *2016*


---


**THE CHOSEN***2016*

---

**ON METHOD. A NON-HISTORY LESSON** *2016*

































 |  |





 



 |







  







[Sign in](https://accounts.google.com/ServiceLogin?continue=http://sites.google.com/a/ladanakonechna.com/ladanakonechna-com/r-e-p/r-e-p-projects&service=jotspot)|[Report Abuse](http://sites.google.com/a/ladanakonechna.com/ladanakonechna-com/system/app/pages/reportAbuse)|[Print Page](javascript:;)|Powered By **[Google Sites](http://sites.google.com/site)**






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
 


