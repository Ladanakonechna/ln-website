




/* Copyright 2008 Google. */ (function() { /*

Copyright The Closure Library Authors.
SPDX-License-Identifier: Apache-2.0
*/
(function(){function e(g){this.t={};this.tick=function(h,k,f){this.t[h]=[void 0!=f?f:(new Date).getTime(),k];if(void 0==f)try{window.console.timeStamp("CSI/"+h)}catch(m){}};this.getStartTickTime=function(){return this.t.start[0]};this.tick("start",null,g)}var a;if(window.performance)var d=(a=window.performance.timing)&&a.responseStart;var l=0<d?new e(d):new e;window.jstiming={Timer:e,load:l};if(a){var b=a.navigationStart;0<b&&d>=b&&(window.jstiming.srt=d-b)}if(a){var c=window.jstiming.load;0<b&&d>=
b&&(c.tick("\_wtsrt",void 0,b),c.tick("wtsrt\_","\_wtsrt",d),c.tick("tbsd\_","wtsrt\_"))}try{a=null,window.chrome&&window.chrome.csi&&(a=Math.floor(window.chrome.csi().pageT),c&&0<b&&(c.tick("\_tbnd",void 0,window.chrome.csi().startE),c.tick("tbnd\_","\_tbnd",b))),null==a&&window.gtbExternal&&(a=window.gtbExternal.pageT()),null==a&&window.external&&(a=window.external.pageT,c&&0<b&&(c.tick("\_tbnd",void 0,window.external.startE),c.tick("tbnd\_","\_tbnd",b))),a&&(window.jstiming.pt=a)}catch(g){}})(); })()



/* Copyright 2008 Google. */ (function() { function d(a){return document.getElementById(a)}window.byId=d;function g(a){return a.replace(/^\s+|\s+$/g,"")}window.trim=g;var h=[],k=0;window.JOT\_addListener=function(a,b,c){var f=new String(k++);a={eventName:a,handler:b,compId:c,key:f};h.push(a);return f};window.JOT\_removeListenerByKey=function(a){for(var b=0;b<h.length;b++)if(h[b].key==a){h.splice(b,1);break}};window.JOT\_removeAllListenersForName=function(a){for(var b=0;b<h.length;b++)h[b].eventName==a&&h.splice(b,1)};
window.JOT\_postEvent=function(a,b,c){var f={eventName:a,eventSrc:b||{},payload:c||{}};if(window.JOT\_fullyLoaded)for(b=h.length,c=0;c<b&&c<h.length;c++){var e=h[c];e&&e.eventName==a&&(f.listenerCompId=e.compId||"",(e="function"==typeof e.handler?e.handler:window[e.handler])&&e(f))}else window.JOT\_delayedEvents.push({eventName:a,eventSrc:b,payload:c})};window.JOT\_delayedEvents=[];window.JOT\_fullyLoaded=!1;
window.JOT\_formatRelativeToNow=function(a,b){a=((new Date).getTime()-a)/6E4;if(1440<=a||0>a)return null;var c=0;60<=a&&(a/=60,c=2);2<=a&&c++;return b?window.JOT\_siteRelTimeStrs[c].replace("\_\_duration\_\_",Math.floor(a)):window.JOT\_userRelTimeStrs[c].replace("\_\_duration\_\_",Math.floor(a))}; })()



 

 var breadcrumbs = [{"path":"/info","deleted":false,"title":"\u0406\u041d\u0424\u041e\u0420\u041c\u0410\u0426\u0406\u042f/INFO","dir":"ltr"},{"path":"/info/cveng","deleted":false,"title":"eng","dir":"ltr"},{"path":"/info/cveng/cv\_eng","deleted":false,"title":"CV\_eng","dir":"ltr"}];
 var JOT\_clearDotPath = 'http://www.gstatic.com/sites/p/f560b7/system/app/images/cleardot.gif';

 
 var JOT\_userRelTimeStrs = ["a minute ago","\_\_duration\_\_ minutes ago","an hour ago","\_\_duration\_\_ hours ago"];

 
 

 

 var webspace = {"gvizGstaticVersion":"current","enableAnalytics":false,"pageSharingId":"jotspot\_page","codeembeds":{"outerIframeSrc":"https://www.gstatic.com/jotspot/embeds/code/0f08d42392f2000e7e3f3daf5b427a43/outer\_iframe.html","innerIframeSrc":"https://1870678329-jotspot-embeds.googleusercontent.com/code/8d87fa64604b2a11fae2ed06104c58d3/inner\_iframe.html"},"enableUniversalAnalytics":false,"sharingPolicy":"OPENED\_WITH\_INDICATOR","siteTitle":"ladanakonechna.com","experiments":{"enableSubpagesGadgetInTakeout":true,"overrideDisableDomainEditing":false,"DisableSiteEditingFeature\_\_disable\_site\_editing":true,"disableDomainEditing":false},"jot2atari":{"eligibility":"INELIGIBLE"},"onepickUrl":"https://docs.google.com/picker","adsensePublisherId":null,"features":{"moreMobileStyleImprovements":null,"subscriptionDataMigrationInProgress":null,"plusBadge":false},"configProperties":{"disableSiteEditing":null},"isPublic":true,"newSitesBaseUrl":"https://sites.google.com","isConsumer":false,"serverFlags":{"jot2AtariLearnMoreUrl":"https://support.google.com/sites/answer/7035197"},"domainAnalyticsAccountId":"","plusPageId":"","signInUrl":"https://accounts.google.com/AccountChooser?continue=http://sites.google.com/a/ladanakonechna.com/ladanakonechna-com/info/cveng/cv\_eng&service=jotspot","analyticsAccountId":"","scottyUrl":"/\_/upload","homePath":"/","siteNoticeUrlEnabled":null,"plusPageUrl":"","adsensePromoClickedOrSiteIneligible":true,"csiReportUri":"http://csi.gstatic.com/csi","sharingId":"jotspot","termsUrl":"//www.google.com/intl/en/policies/terms/","gvizVersion":1,"editorResources":{"sitelayout":["http://www.gstatic.com/sites/p/f560b7/system/app/css/sitelayouteditor.css"],"text":["http://www.gstatic.com/sites/p/f560b7/system/js/codemirror.js","http://www.gstatic.com/sites/p/f560b7/system/app/css/codemirror\_css.css","http://www.gstatic.com/sites/p/f560b7/system/js/trog\_edit\_\_en.js","http://www.gstatic.com/sites/p/f560b7/system/app/css/trogedit.css","/\_/rsrc/1638433988000/system/app/css/editor.css","http://www.gstatic.com/sites/p/f560b7/system/app/css/codeeditor.css","/\_/rsrc/1638433988000/system/app/css/camelot/editor-jfk.css"]},"sharingUrlPrefix":"/\_/sharing","isAdsenseEnabled":true,"domain":"ladanakonechna.com","baseUri":"","name":"ladanakonechna-com","siteTemplateId":false,"siteNoticeRevision":null,"siteNoticeUrlAddress":null,"siteNoticeMessage":null,"page":{"isRtlLocale":false,"canDeleteWebspace":null,"isPageDraft":null,"parentPath":"/info/cveng","parentWuid":"wuid:gx:6abf6eb9d9af8508","siteLocale":"uk","timeZone":"America/Los\_Angeles","type":"text","title":"CV\_eng","locale":"en","wuid":"wuid:gx:712ee6dd883e3d72","revision":23,"path":"/info/cveng/cv\_eng","isSiteRtlLocale":false,"pageInheritsPermissions":null,"name":"cv\_eng","canChangePath":true,"state":"","properties":{},"bidiEnabled":false,"currentTemplate":{"path":"/system/app/pagetemplates/text","title":"Web Page"}},"canPublishScriptToAnyone":true,"user":{"keyboardShortcuts":true,"sessionIndex":"","guest\_":true,"displayNameOrEmail":"guest","userName":"guest","uid":"","renderMobile":false,"domain":"","namespace":"","hasWriteAccess":false,"namespaceUser":false,"primaryEmail":"guest","hasAdminAccess":false,"isGoogleAdmin":false},"gadgets":{"baseUri":"/system/app/pages/gadgets"}};
 webspace.page.breadcrumbs = breadcrumbs;

 
 var JOT\_siteRelTimeStrs = ["\u0445\u0432\u0438\u043b\u0438\u043d\u0443 \u0442\u043e\u043c\u0443","\_\_duration\_\_ \u0445\u0432\u0438\u043b\u0438\u043d \u0442\u043e\u043c\u0443","\u0433\u043e\u0434\u0438\u043d\u0443 \u0442\u043e\u043c\u0443","\_\_duration\_\_ \u0433\u043e\u0434\u0438\u043d \u0442\u043e\u043c\u0443"];



 window.jstiming.load.tick('scl');
 









CV\_eng - ladanakonechna.com



 window.jstiming.load.tick('cl');
 



 








|  |  |
| --- | --- |
| [ladanakonechna.com](../../index.html) |  |
|  |







|  |  |  |
| --- | --- | --- |
| MENU* [НОВИНИ/NEWS](../../home/news)
* [РОБОТИ/WORKS selection](../../project)
	+ [2021](../../project/2021)
		- [Дисципліноване бачення/ Disciplined Vision](../../project/2021/disciplinovane-bacenna-disciplined-vision)
	+ [2020](../../project/2020)
		- [Images from abroad](../../project/2020/images-from-abroad)
		- [Bodies in the distance](../../project/2020/bodies-in-a-distance)
		- [Ми зіткнемося з можливістю/We shall be confronted with the possibility](../../project/2020/mi-zitknemosa-z-mozlivistu)
		- [Фотозона/Photozone](../../project/2020/photozone)
		- [У листі та в камені (автопортрет)/In foliage and in stone (self-portrait)](../../project/2020/u-listi-ta-v-kameni-avtoportret-in-foliage-and-in-stone-self-portrait)
		- [Без назви (присвячено виставкам)/ Untitled (dedicated to exhibitions)](../../project/2020/bez-nazvi-prisvaceno-vistavkam-untitled-dedicated-to-exhibitions)
		- [Пакунок/Package](../../project/2020/pakunok-package)
		- [The search of a proper sign for the monument to the Polish protests](../../project/2020/posuk-naleznoie-viviski-dla-pam-atnika-polskim-protestam-the-search-of-a-proper-sign-for-the-monument-to-the-polish-protests)
	+ [2019](../../project/2019)
		- [Прапори/Flags](../../project/flags)
		- [Historical pictures of the contemporary ruins](../../project/2019/historical-pictures-of-the-contemporary-ruins)
	+ [2018](../../project/2018)
		- [Background mode](../../project/background-mode)
		- [Demonstration](../../project/demonstration)
		- [Some examples from the field of management](../../project/some-examples-from-the-field-of-management)
	+ [2017](../../project/2017)
		- [Учитель/Teacher](../../project/ucitel-teacher)
	+ [2016](../../project/2016)
		- [Виставка/The exhibition](../../project/the-exhibition)
		- [The music stops. The guests are embarrassed. Pause](../../project/the-music-stops-the-guests-are-embarrassed-pause)
		- [Чорний ящик/Black Box](../../project/cornij-asik-black-box)
		- [artists` motto](../../project/artists-motto)
	+ [2015](../../project/2015)
		- [Merge Visible](../../project/merge-visible)
		- [Град/Hail (Grad)](../../project/grad-hail)
		- [Так звані/The so-called](../../project/tak-zvani-the-so-called)
		- [War in Ukraine](../../project/war-in-ukraine)
		- [Обман дистанції/The deception of distance](../../project/obman-distanciie-the-deception-of-distance)
	+ [2014](../../project/2014)
		- [Мобільна портативна модель/Mobile portable model](../../project/mobilna-portativna-model-mobile-portable-model)
		- [Нерозпочатий діалог другорядних героїв/Unstarted dialogue of unnamed characters](../../project/---unstarted-dialogue-of-unnamed-characters)
		- [Стіл переговорів/Negotiating table](../../project/stil-peregovoriv-negotiation-table)
		- [Фотографії з мого альбому. Придністров'я, 1973/Photos from my album. Transnistria, 1973](../../project/photos-from-my-album-transnistria-1973)
		- [Зарезервовано/Reserved](../../project/reserved)
		- [Зліва направо/From left to right](../../project/from-left-to-right)
	+ [2013](../../project/2013)
		- [Наочний приклад моєї участі/Object lesson of my participation](../../project/naocnij-priklad-moeie-ucasti-object-lesson-of-my-partisipation)
	+ [2012](../../project/2012)
		- [Bad face of Ukraine](../../project/bad-face-of-ukraine)
		- [Drinking a bottle of vodka alone in the park surrounding the CCA Ujazdowski Castle, opposite to the pavilion of Rikrit Tiravanija, during summer festival "Green Jazdów"](../../project/drinking-alone)
		- [Майже теж саме/Almost the same](../../project/majze-tez-same-almost-the-same)
		- [Welcome* if you can fit in](../../project/welcome)
	+ [2011](../../project/2011)
		- [Персональний щит/Personal shield](../../project/personalnij-sit-personal-shield-1)
		- [Ще один день/One More Day](../../project/se-odin-den-one-more-day)
		- [Ентузіазм/Enthusiasm](../../project/entuziazm-enthusiasm)
		- [Поки я бачу/While I can see](../../project/poki-a-bacu-while-i-can-see)
		- [Учні та освітлена площина/ Disciples and the illuminated plane](../../project/-ucni-ta-osvitlena-plosina-disciples-and-the-illuminated-plane)
		- [Монумент для двох/Monument for 2](../../project/monument-dla-dvoh-monument-for-2)
		- [Море/Sea](../../project/more-sea)
	+ [2010](../../project/2010)
		- [Листівки/Cards](../../project/listivki-cards)
		- [Перспектива/Perspective](../../project/perspektiva-perspective)
	+ [2009](../../project/2009)
		- [Місце/Place](../../project/misce-place)
		- [Дослідження систем маніпуляції/Investigation of manipulation mechanisms](../../project/doslidzenna-sistem-manipuliciie-investigation-of-mechanisms-of-manipulation)
		- [Раніше. Тепер. Далі/Before. Now. Further](../../project/ranise-teper-dali-before-now-further)
		- [Три точки зору на спільне поле та три можливості його придбати/Three points of view on common field and three possibilities to own it](../../project/tri-tocki-zoru-na-spilne-pole-ta-tri-mozlivosti-jogo-pridbati-three-points-of-view-on-common-field-and-three-possibilities-to-own-it)
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
 

[ІНФОРМАЦІЯ/INFO](../../info)‎ > ‎[eng](../cveng)‎ > ‎
 

CV\_eng





| Born  **1981** in Dnipropetrovsk, USSR Lives and works in Kyiv, Ukraine**e****ducation****Currently** PhD Researcher at the National Academy of Art and Architecture in Kyiv, Ukraine, Department of History and Theory of Arts**2006 - 2009**  -  National Academy of Fine Art and  Architecture, postgraduate course, Kyiv **2000** -  **2006**   - MA, National Academy of Fine Art and  Architecture, Kyiv **1996** **-** **2000** -  Dnipropetrovsk State Art College**1999** -  special course in video art, Center for Contemporary Art Kyiv, Ukraine**2008** Co-founder of Curatorial Union [**HUDRADA**](http://hudrada.tumblr.com/), a self-educational community based on interdisciplinary cooperation **2007-2008** *Shtab*(headquarters), project of REP group for supporting young artists, Center for Contemporary Art, Kyiv, UkraineSince  **2004** member of **[R.E.](../../r-e-p)****[P.](../../r-e-p)****[group](../../r-e-p)**Since **2013** run the **Course of Art** – educational program2015 Co-founder of **[Method Fund](https://sites.google.com/site/methodfund/news)**Since **2017** editor of the **[PROSTORY](http://prostory.net.ua/)**  - the journal of  art, literature, literary translation, politics**Awards**2014  Laureate of Malevich Award-2014, Kyiv2013  Second Special Prize of the PinchukArtCentre Prize 20132011 Finalist of Artistic Competition for a Monument to Freedom and Unity in Leipzig2009 Short list of competition participants in competition for Memorial for the Victims of the German NS Military Courts, Cologne2003  1st Award of the 3rd Ukrainian contest for young curators and artists, Center for Contemporary Art at NaUKMA, Kyiv.  
**Selected solo e****xhibitions** **and projects****2020** *The images from abroad,*Gallery EIGEN + ART  Berlin **2018**  *Background Mode*, Gallery EIGEN + ART Leipzig **2017** *Teacher*, National Art Museum of Ukraine, Kyiv
**2016** *The music stops. The guests are embarrassed. Pause**,* Gallery EIGEN + ART  Berlin **2016** The Exhibition, PinchukArtCentre, Kyiv, Ukraine**2016** *Experiments* (with Zhanna Kadyrova), BWA Warsaw, Poland  **2015** *The Deception of Distance*, Mikhail Bulgakov's Museum, Kyiv, Ukraine**2014** *Homey,* Intervention, Krakow Theatrical Reminiscences, Poland**2014** *State of things*, Toulouse Art Festival, Espace Croix-Baragnon, Toulouse, France **2014** *Mobile portable model,* Gallery EIGEN + ART Berlin**2012** *Alienation Effect,* Eigen + Art Lab, Berlin**2012** *While I see* , performance, Arsenal gallery, Byalistok, Poland**2012** *Weekdays,* CSW Zamek Ujazdowsky, Warsaw, Poland**2011** *One More Day* , performance, National Art Museum of Ukraine, Kyiv, Ukraine**2011** *2 Stories - 3 Worlds*. (with Ivan Bazak), BINZ39 Foundation, Zurich, Switzerland;**2011** *Perspective,* Public Art Project in University Library Albertina in Leipzig, Germany;**2009** *Place,* Foundation Center for Contemporary Art, Kyiv, Ukraine;**2003** *Comfortable* *environment,* CCA at NaUKMA, Kyiv, Ukraine **Selected group exhibitions****2020** **The economy of borders,** facade of the City hall of Tiergarten, Berlin**2019 *War in Museum,*** Kmytiv Art Museum, Ukraine**2019** ***Own motive,*** Poltava Art Museum, Ukraine**2019***On independence*, Kmytiv museum of fine art, Kmytiv, Ukraine **2019** *At the Front Line: Ukrainian Art, 2013-2019*, The National Museum of Cultures, Mexico**2019** *Tale of Novorossiya,* Arsenal Gallery, Poznan, Poland**2019***Listen
to us – artistic intelligence,*City
Art Gallery, Plovdiv, Bulgaria**2019***Searching for Identity
(at the time of the selfie),*Studio Tommaseo, Trieste **2018** *The world on Paper,*Palais Populaire, Berlin**2018**Zeitgeistlos, curated by\_Eszter
LÁZÁR & Edina NAGY, Knoll gallery, Vienna**2018***I am the Mouth,* Works from Central and Eastern European Artists from Art Collection Telecom, Museum of Contemporary Art Zagreb, Croatia  **2018***Follow the Line -* POSITIONS OF CONTEMPORARY DRAWING,  Kunsthalle der Spaskasse , Leipzig
**2017** *Festivities Are Canceled!*  The Kyiv International - Kyiv Biennial 2017, "UFO" at metro Lybidska (Ukrainian Institute of Scientific, Technical and Economic Information) and Pavlo Tychyna Literary Memorial Museum in Kyiv
**2017**  *Postpo**ned Futures* , DRAD, London***2016** Into the darkness,* VozdvizhenkaArtsHouse, Kyiv and WUK, Vienna, Austria 
**2016** *The school of Kyiv. Leipzig class. Seminar: Politics of Form*, GFZK, Leipzig*2016**Semantic Riots**,*Ausstellungsraum Klingental, Kasernenstrasse 23, Basel**2015** *à la frontière ...!* *old and new borders in Europe,* Studio Tommaseo , Trieste Contemporanea **2015** *Meshes of the Afternoon, The* Kyiv Biennale, Kunsthalltrondheim, Norway**2015** *In spite of everything* , Polish Institute Dusseldorf, Germany**2015** *Best evidence rule,* Association for Contemporary Art Leipzig, Germany**2015** *Lest The Two Seas Meet,* Museum of Modern Art in Warsaw, Poland***2015*** *Walk the Line. New ways of drawing* , Kunstmuseum Wolfsburg, Germany***2014*** *Referendum on withdrawal from the human race,* Art Center Closer, Kyiv, Ukraine **2014** *R.E.P.: 10 years.* *On method* , Labirynt Gallery, Lublin, Poland**2014** *Through Maidan and Beyond* , Architekturzentrum Wien, Austria**2014** *Sister Europa,* Kunstraum Lakeside, Klagenfurt, Austria **2014** *Deprivation* , Arsenal Gallery, Bialystok, Poland**2014** *Disconsent,* Center for Contemporary Art Plovdiv, Bulgaria**2014** *The Ukrainians* , Daad gallery, Berlin, Germany**2014** Gender and diplomacy - the »Ladies' Program«, House of World Cultures, Berlin**2014** Imaginary Archive, The Les'Kurbas Center for Theater Arts, Kyiv, Ukraine**2013** Measures of saving the world\_part 3, <rotor> center for contemporary art, Graz, Austria**2013** Odessa Biennial of Contemporary Art, Ukraine**2013** *Economics in Art* , Museum of Contemporary Art, Krakow, Poland **2013** Racing with time: The Art of 1960s - The Beginning of 2000s, National Art Museum of Ukraine, Kyiv **2013** Ukrainian news, group exhibition, CSW Zamek Ujazdowsky, Warsaw, Poland**2012** *Landscape shielded by the picture*, National Art Museum, Kyiv**2012** *The Ukrainian Body,* Visual Culture Research Center of NaUKMA**2011** *October project,* flood ditch e. V., Berlin, Germany**2011**  *Laboratory Show*, Visual Culture Research Center, Kyiv, Ukraine**2011** *Rewriting worlds**,* Main project of 4th Moscow Biennial of Contemporary Art, Moscow, Russia**2010** *IF. Ukrainian Art in Transition,* PERM Museum, Perm, Russia**Projects with REP group (selection)**2019 11/944 from the Collection of Galeria Labirynt, Galeria Labirynt, Lublin- The Influencing Machine, Galeria Nicodim, Bucharest2018 The Opposing Shore, University of Brittany Occidentale, Brest, France2017 Attention! Border! Galeria Arsenal elektrownia, Bialystok, Galeria Labirynt, Lublin2016 Meanwhile, what about socialism?, Gallery North, Northumbria University, Newcastle -  Dependence degree,  BWA Wrocław - Gallery of Contemporary Art2015 Demonstrating Minds: Contemporary Art Disease, KIASMA / The Finnish National Gallery, Хельсінкі, Finland                                                                              - REP - On method, 10 years, Galeria Labirynt, Lublin, Poland2014 - The Ukrainians, DAAD gallery, Berlin, Germany  **2013** - global aCtIVISm, ZKM | Museum of Contemporary Art, Karlovice, Німеччина 
- Disobedience Archive (The Republic), Castello di Rivoli Museo d'Arte Contemporanea, Turin, Italy **2012** Cantastoria, UMOCA (Utah Museum of Contemporary Art), USA**2011** Impossible community, State Museum of Modern Art of the Russian Academy of Arts, Moscow, Russia - Public Folklore, Grazer Kunstverein, Graz, Austria - Life in the forest, Galeria Arsenal, Bialystok, Poland - The Bulgarian Pavilion, 54th Venice Biennial, Venice, Italy - Kaliningrad, Kalmar, Sweden - Making and Art, Stadtgalerie Schwaz, Austria**2010**  Minimal differences, White box, Ney-York, США - Over the counter, Kunsthalle, Budapest, Hungary - Euro Renovation in Europe, Kunstraum Munich, Munich, Germany - Great Surprise, National Art Museum of Ukraine, Kyiv - SUPERMARKET - the artist -run art fair, Stockholm, Sweden - Let's Talk about Nationalism! Between Ideology and Identity, Kumu Art Museum, Tallinn, Estonia**2009**  Revolutionary Moments, http://revolutionarymoments.com/conference/, www.revolutionary-moments.blogspot.com, Foundation Center for Contemporary Art, Kyiv; - Future What Yesterday. Self-Organized Artistic Practices from Ukraine, Gallery SC + Gallery PM / HDLU, Zagreb, Croatia; - No More Reality. Crowd and Performance, Depo, Istanbul, Turkey - Land of Human Rights: Being Responsible for Resources, <rotor> - art association in Graz, Austria**2008** Art as A Present, Pinchuk Art Center, Kyiv, Ukraine - Alphabetical Order, Index - The Swedish Contemporary Art Foundation, Stockholm, Sweden - Another City. Another Life, Zacheta Gallery, Warsaw, Poland - No More Reality, De Appel Art Center, Amsterdam, The Netherlands - Satellite Tunes, Hungarian University of Fine Arts, Budapest, Hungary**2007** Consequences and Proposals, Biennial of Young Artists, Tallinn, Estonia - Contemporary Art Norwich, Norwich, England - A Poem about inland Sea, project in collaboration with Mark Titchner, Ukrainian Pavilion, 52nd Venice Biennial, Venice - Progressive nostalgia, Centro Luigi Pecci, Prato - From Kosovo to Kaliningrad, Third Prague Biennial of Contemporary Art, Prague - Return of Memory, KUMU Museum, Tallinn, Estonia - Petroliana. Oil Patriotism, Moscow Biennial of Contemporary Art, Moscow Museum for Contemporary Art, Moscow, Russia**2006** Postorange, Kunsthalle, Vienna - Intervention, CSW Zamek Ujazdowski, Warsaw, Poland - Contested Space in Post-Soviet Art, Sidney Mishkin Gallery, New York, USA**Curatorial activities**Exhibition by curatorial collective Hudrada:**2018**  **Union of Hovels. The Survivor Syndrome** ,  Mikhailovska Plosha / St Michael's Square in Kyiv, Ukraine **2017** *Festivities Are Canceled !,* The Kyiv International - Kyiv Biennial 2017, "UFO" at metro Lybidska (Ukrainian Institute of Scientific, Technical and Economic Information) and Pavlo Tychyna Literary Memorial Museum in Kyiv***2016 Into the darkness,*** VozdvizhenkaArtsHouse, Vozdvizhenska 32, Kyiv ***2016 Into the darkness,*** WUK, Kunsthalle Exnergasse, Vienna, Austria**2014**  **Unpurposeful use of premises,** Khreschatik 34, Kyiv
**2014 Referendum on withdrawal from the human race,** art center Closer, Kyiv, Ukraine**Referendum on withdrawal from the human race,** Teatr Powszechny, Warsaw, Poland2013 Union of hovels, first congress, Malomocco, Lido, Venice 2013 Portfolio review: "The Great and the Good,"  Ujazdowski Castle, Warsaw, Poland 2013 Court Experiment, SIZ gallery, Rijeka, Croatia 2012  Disputed territory, Kroshitsky Art Museum, Sevastopol, Crimea, Ukraine****2011** *Laboratory Show*, Visual Culture Research Center, Kyiv, Ukraine******2011** *Court experiment,*project in the frame of the non-commercial program of VIENNAFAIR 2011****2010** *****[Court Experiment](http://hudrada.tumblr.com/court%20experiment)***,Visual Culture Research Center, Center of  Study  of Society, Curatorial Union Hudrada together with tranzit.at,  Kyiv, Ukraine****2009** ***Views**,* Center for Contemporary Art, Kyiv,  UkraineProjects curated by the REP group:**2008** ***T******ransit**,* Ya gallery, Kyiv, Ukraine***Common Space***, public space near the Arsenalna metro station, Kyiv, Ukraine***New Ukrainian Language***, Karas gallery,Kyiv, Ukraine **2007** ***[Communities: Ukrainian Young Artists](http://galeria-arsenal.pl/en/exhibitions/communities-.html)**,* Arsenal gallery, Bialystok, Poland***Communities Project*****,** Center for Contemporary Art, Kyiv, Ukraine
**Lectures, talks (selection):**

2019 The so-called. Practical workshop, during a conference “How to talk to a suicidal shotgun. Art in the era of post-truth, conspiracy theories and negationism”, Galeria Labirynt, Lublin2018 Lexicon of Change: Ukraine 5 Years after Maidan. Conference initiated and organized by the German Federal Agency for Civic Education, Academy of Arts, Berlin 2017 Curatorial Network Talk #1: Lada Nakonechna. Reading International, School of Art, University of Reading, UK2017 Exchanging Notes 2: Making Memories, Seminar at the Norrköping Art Museum, Sweden2015 Guest lecture, Post Conceptual Study Program (prof. Marina Grzinic), Akademie der bildenden Künste Wien2011 The journey to the East, panel discussion, Bialystok, Poland    2011 Art in public space, symposium, University Library Leipzig2011 Presentation and discussion at the Master Fine Arts in Zürich (Invisible Borders, Lada Nakonecna, Luchezar Boyadjiev and Ivan Bazak, presentation and discussion (moderated by Heiko Schmid)2010  April:  Visiting artist, Theory Tuesdays, Corner college,  Zurich, Switzerland2009 Post-sowjetisch und Post-orange: Junge Ukrainische Kunst, Lothringer13 -  Städtische Kunsthalle München, Germany
 **Stipends, fellowships, residencies:**2018 residence at the Abbey Ruins,
Reading International, Reading, UK, Culture
Bridges International Mobility grant.2017 DAAD “Arts
and Media” program, research stipend.2017 Stipendium Griffelkunst at the print workshop of Ellen
Sturm, Hamburg2015 KulturKontakt Austria, Vienna2015 18th Art
Center, Santa Monica, USA2014 Fellowship at the
Hanse-Wissenschftskolleg, Delmenhorst, Germany2012, 2015  a-i-r
Laboratory, The Ujazdowski Castle Centre for Contemporary Art, Warsaw, Poland2010 Residence
BINZ39, Zurich and Zuger Kulturstiftung Landis & Gyr, Zug, Switzerland2009
Residency at Villa Waldberta, Munich, Germany2008, 2009 LIA – Leipzig International Art Program, Leipzig,
Germany2005 Center for Contemporary Art, Kyiv (with REP) **Works in public collections (selection)** 
Philadelphia Museum of Art, Deutsche Bank Collection, Frankfurt am Main, Sparkasse Leipzig Art Collection, Art Collection Telekom, Arsenal Gallery, Białystok, Westhoff Collection, Bremen, Albertina University Library, City of Leipzig, National Art Museum of Kyiv, SØR Rusche Collection, Oelde - Berlin |





 



 |







  







[Sign in](https://accounts.google.com/ServiceLogin?continue=http://sites.google.com/a/ladanakonechna.com/ladanakonechna-com/info/cveng/cv_eng&service=jotspot)|[Report Abuse](http://sites.google.com/a/ladanakonechna.com/ladanakonechna-com/system/app/pages/reportAbuse)|[Print Page](javascript:;)|Powered By **[Google Sites](http://sites.google.com/site)**






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
 


