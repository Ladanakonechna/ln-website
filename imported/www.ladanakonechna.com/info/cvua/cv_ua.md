




/* Copyright 2008 Google. */ (function() { /*

Copyright The Closure Library Authors.
SPDX-License-Identifier: Apache-2.0
*/
(function(){function e(g){this.t={};this.tick=function(h,k,f){this.t[h]=[void 0!=f?f:(new Date).getTime(),k];if(void 0==f)try{window.console.timeStamp("CSI/"+h)}catch(m){}};this.getStartTickTime=function(){return this.t.start[0]};this.tick("start",null,g)}var a;if(window.performance)var d=(a=window.performance.timing)&&a.responseStart;var l=0<d?new e(d):new e;window.jstiming={Timer:e,load:l};if(a){var b=a.navigationStart;0<b&&d>=b&&(window.jstiming.srt=d-b)}if(a){var c=window.jstiming.load;0<b&&d>=
b&&(c.tick("\_wtsrt",void 0,b),c.tick("wtsrt\_","\_wtsrt",d),c.tick("tbsd\_","wtsrt\_"))}try{a=null,window.chrome&&window.chrome.csi&&(a=Math.floor(window.chrome.csi().pageT),c&&0<b&&(c.tick("\_tbnd",void 0,window.chrome.csi().startE),c.tick("tbnd\_","\_tbnd",b))),null==a&&window.gtbExternal&&(a=window.gtbExternal.pageT()),null==a&&window.external&&(a=window.external.pageT,c&&0<b&&(c.tick("\_tbnd",void 0,window.external.startE),c.tick("tbnd\_","\_tbnd",b))),a&&(window.jstiming.pt=a)}catch(g){}})(); })()



/* Copyright 2008 Google. */ (function() { function d(a){return document.getElementById(a)}window.byId=d;function g(a){return a.replace(/^\s+|\s+$/g,"")}window.trim=g;var h=[],k=0;window.JOT\_addListener=function(a,b,c){var f=new String(k++);a={eventName:a,handler:b,compId:c,key:f};h.push(a);return f};window.JOT\_removeListenerByKey=function(a){for(var b=0;b<h.length;b++)if(h[b].key==a){h.splice(b,1);break}};window.JOT\_removeAllListenersForName=function(a){for(var b=0;b<h.length;b++)h[b].eventName==a&&h.splice(b,1)};
window.JOT\_postEvent=function(a,b,c){var f={eventName:a,eventSrc:b||{},payload:c||{}};if(window.JOT\_fullyLoaded)for(b=h.length,c=0;c<b&&c<h.length;c++){var e=h[c];e&&e.eventName==a&&(f.listenerCompId=e.compId||"",(e="function"==typeof e.handler?e.handler:window[e.handler])&&e(f))}else window.JOT\_delayedEvents.push({eventName:a,eventSrc:b,payload:c})};window.JOT\_delayedEvents=[];window.JOT\_fullyLoaded=!1;
window.JOT\_formatRelativeToNow=function(a,b){a=((new Date).getTime()-a)/6E4;if(1440<=a||0>a)return null;var c=0;60<=a&&(a/=60,c=2);2<=a&&c++;return b?window.JOT\_siteRelTimeStrs[c].replace("\_\_duration\_\_",Math.floor(a)):window.JOT\_userRelTimeStrs[c].replace("\_\_duration\_\_",Math.floor(a))}; })()



 

 var breadcrumbs = [{"path":"/info","deleted":false,"title":"\u0406\u041d\u0424\u041e\u0420\u041c\u0410\u0426\u0406\u042f/INFO","dir":"ltr"},{"path":"/info/cvua","deleted":false,"title":"ua","dir":"ltr"},{"path":"/info/cvua/cv\_ua","deleted":false,"title":"cv\_ua","dir":"ltr"}];
 var JOT\_clearDotPath = 'http://www.gstatic.com/sites/p/f560b7/system/app/images/cleardot.gif';

 
 var JOT\_userRelTimeStrs = ["a minute ago","\_\_duration\_\_ minutes ago","an hour ago","\_\_duration\_\_ hours ago"];

 
 

 

 var webspace = {"gvizGstaticVersion":"current","enableAnalytics":false,"pageSharingId":"jotspot\_page","codeembeds":{"outerIframeSrc":"https://www.gstatic.com/jotspot/embeds/code/0f08d42392f2000e7e3f3daf5b427a43/outer\_iframe.html","innerIframeSrc":"https://116227506-jotspot-embeds.googleusercontent.com/code/8d87fa64604b2a11fae2ed06104c58d3/inner\_iframe.html"},"enableUniversalAnalytics":false,"sharingPolicy":"OPENED\_WITH\_INDICATOR","siteTitle":"ladanakonechna.com","experiments":{"enableSubpagesGadgetInTakeout":true,"overrideDisableDomainEditing":false,"DisableSiteEditingFeature\_\_disable\_site\_editing":true,"disableDomainEditing":false},"jot2atari":{"eligibility":"INELIGIBLE"},"onepickUrl":"https://docs.google.com/picker","adsensePublisherId":null,"features":{"moreMobileStyleImprovements":null,"subscriptionDataMigrationInProgress":null,"plusBadge":false},"configProperties":{"disableSiteEditing":null},"isPublic":true,"newSitesBaseUrl":"https://sites.google.com","isConsumer":false,"serverFlags":{"jot2AtariLearnMoreUrl":"https://support.google.com/sites/answer/7035197"},"domainAnalyticsAccountId":"","plusPageId":"","signInUrl":"https://accounts.google.com/AccountChooser?continue=http://sites.google.com/a/ladanakonechna.com/ladanakonechna-com/info/cvua/cv\_ua&service=jotspot","analyticsAccountId":"","scottyUrl":"/\_/upload","homePath":"/","siteNoticeUrlEnabled":null,"plusPageUrl":"","adsensePromoClickedOrSiteIneligible":true,"csiReportUri":"http://csi.gstatic.com/csi","sharingId":"jotspot","termsUrl":"//www.google.com/intl/en/policies/terms/","gvizVersion":1,"editorResources":{"sitelayout":["http://www.gstatic.com/sites/p/f560b7/system/app/css/sitelayouteditor.css"],"text":["http://www.gstatic.com/sites/p/f560b7/system/js/codemirror.js","http://www.gstatic.com/sites/p/f560b7/system/app/css/codemirror\_css.css","http://www.gstatic.com/sites/p/f560b7/system/js/trog\_edit\_\_en.js","http://www.gstatic.com/sites/p/f560b7/system/app/css/trogedit.css","/\_/rsrc/1638433988000/system/app/css/editor.css","http://www.gstatic.com/sites/p/f560b7/system/app/css/codeeditor.css","/\_/rsrc/1638433988000/system/app/css/camelot/editor-jfk.css"]},"sharingUrlPrefix":"/\_/sharing","isAdsenseEnabled":true,"domain":"ladanakonechna.com","baseUri":"","name":"ladanakonechna-com","siteTemplateId":false,"siteNoticeRevision":null,"siteNoticeUrlAddress":null,"siteNoticeMessage":null,"page":{"isRtlLocale":false,"canDeleteWebspace":null,"isPageDraft":null,"parentPath":"/info/cvua","parentWuid":"wuid:gx:5e2d9c23c3f36ed3","siteLocale":"uk","timeZone":"America/Los\_Angeles","type":"text","title":"cv\_ua","locale":"en","wuid":"wuid:gx:5699bedda5572fba","revision":18,"path":"/info/cvua/cv\_ua","isSiteRtlLocale":false,"pageInheritsPermissions":null,"name":"cv\_ua","canChangePath":true,"state":"","properties":{},"bidiEnabled":false,"currentTemplate":{"path":"/system/app/pagetemplates/text","title":"Web Page"}},"canPublishScriptToAnyone":true,"user":{"keyboardShortcuts":true,"sessionIndex":"","guest\_":true,"displayNameOrEmail":"guest","userName":"guest","uid":"","renderMobile":false,"domain":"","namespace":"","hasWriteAccess":false,"namespaceUser":false,"primaryEmail":"guest","hasAdminAccess":false,"isGoogleAdmin":false},"gadgets":{"baseUri":"/system/app/pages/gadgets"}};
 webspace.page.breadcrumbs = breadcrumbs;

 
 var JOT\_siteRelTimeStrs = ["\u0445\u0432\u0438\u043b\u0438\u043d\u0443 \u0442\u043e\u043c\u0443","\_\_duration\_\_ \u0445\u0432\u0438\u043b\u0438\u043d \u0442\u043e\u043c\u0443","\u0433\u043e\u0434\u0438\u043d\u0443 \u0442\u043e\u043c\u0443","\_\_duration\_\_ \u0433\u043e\u0434\u0438\u043d \u0442\u043e\u043c\u0443"];



 window.jstiming.load.tick('scl');
 









cv\_ua - ladanakonechna.com



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
 

[ІНФОРМАЦІЯ/INFO](../../info)‎ > ‎[ua](../cvua)‎ > ‎
 

cv\_ua





| Народилась у **1981** році, м. Дніпропетровськ, СССР                                                                Живе та працює у Києві, Україна **Освіта****2006-2009** - Національна академія образотворчого мистецтва та архітектури, асистентура-стажування, Київ**2000-2006** - Національна академія образотворчого мистецтва та архітектури, графічний факультет, Київ**1996-2000**  - Дніпропетровський державний художній коледж, Україна З **2004** членкиня **[групи Р.Е.П.](../../r-e-p)** - «революційний експериментальний простір» **2008**членкиня [**Худрад****и**](https://hudrada.tumblr.com/), самоорганізаційної міждисциплінарної кураторської спільноти **2011** –  співзасновниця **[–ІСТМ](http://istmkyiv.wordpress.com/)**(Ініціатива самозахисту трудящих мистецтва) **2015** – співзасновниця [Метод Фонду](https://sites.google.com/site/methodfund/news) та кураторка його освітнього напрямку [Курс мистецтва](https://courseofart.com)Співредакторка [PROSTORY](http://prostory.net.ua/) - виданя про мистецтво, літературу та політику**Нагороди****2014** –  Лауреатка премії ім. Казимира Малевича, Київ, Україна**2013**– Друга спеціальна премія PinchukArtCentre 2013 **2009, 2011** Фіналістка PinchukArtPrize, Київ, Україна                                                                                **2008, 2012**  Фіналістка премії ім. Казимира Малевича, Київ, Україна**2003** Переможниця III Українського конкурсу молодих кураторів та художників, Центр сучасного мистецтва при НаУКМА, Київ, Україна**Роботи в публічних колекціях:**Philadelphia Museum of Art, Sammlung Deutsche Bank, Frankfurt am Main, Kunstsammlung der Sparkasse Leipzig , Art Collection Telekom , Arsenał Gallery, Białystok, Sammlung Westhoff, Bremen , Universitätsbibliothek Albertina, City of Leipzig, National Art Museum of Ukraine, Kyiv,  SØR Rusche Sammlung, Oelde – Berlin **Виставки та проекти****Вибрані персональні виставки та проекти****2021** *Дисципліноване бачення,* NAMU, Київ**2020** *Bodies in a distance**,* Skala gallery, Познань, Польща**2020** *Images from abroad,* Eigen+Art Berlin**2018***Background Mode*, Galerie EIGEN + ART Leipzig, Німеччина**2017***Учитель*, втручання, Національний художній музей України, Київ**2016***Die Musik bricht ab. Die Gäste sind verlegen. Pause.**,* Eigen+Art, Берлін**2016**  *Експерименти* (разом з Жанною Кадировою), BWA Warsaw, Польща**2015***The Deception of Distance*, Музей М. Булгакова, Київ, Україна**2014***Домашні,*інтервенція, Krakow Theatrical Reminiscences, Польща**2014** *State of things*, Toulouse Art Festival,Espace Croix-Baragnon, Тулуза, Франція**2014***Mobile portable model,*Eigen+Art Berlin**2012***Entfremdungseffect,* Eigen+Art Lab, Berlin**2012***Поки я бачу*, перфоманс, Arsenal gallery, Білосток, Польща**2012***Будні,*CSW Zamek Ujazdowsky, Варшава, Польща**2011***Ще один день*, перформанс, Національний художній музей України, Київ, Україна**2011***2 Stories – 3 Worlds*. (with Ivan Bazak), BINZ39 Foundation, Цюрих, Швейцарія;**2011***Перспектива,*Public Art Project in University Library Albertina in Leipzig,Німеччина;**2009***Місце**,* Центр сучасного мистецтва при НаУКМА, Київ, Україна;                                                             **2003** Зручне середовище*,* ЦСМ при НаУКМА, Київ, Україна**Групові виставки** (*Проекти у складі групи Р.Е.П.)**2020****The economy of borders. Ц****e lost our soft soul, by crossing the borders,** facade of the City hall of Tiergarten, Берлін**2019****Про самостійність**, Кмитівський музей образотворчого мистецтва імені Й. Д. Буханчука**Війна в музеї**, Кмитівський музей образотворчого мистецтва імені Й. Д. Буханчука**At the Front Line: Ukrainian Art, 2013-2019,** The National Museum of Cultures**Власний мотив,** Полтавський художній музей (галерея мистецтв) імені Миколи Ярошенка**Tale of Novorossiya,** Arsenal Gallery, Poznan
**Listen to us – artistic
intelligence,**City
Art Gallery, Пловдів, Болгарія***Searching for Identity
(at the time of the selfie)***, Studio Tommaseo, Трієст, Італія  **11/944. from the Collection of Galeria Labirynt*, Galeria Labirynt, Lublin****The Influencing Machine***, Galeria Nicodim, Бухарест, Руминія**2018*****The world on Paper,***Palais Populaire, Берлін***Zeitgeistlos*,**curated by\_Eszter LÁZÁR & Edina NAGY, Knoll gallery, Відень**I am the Mouth**, Works from Central and Eastern European Artists from Art Collection Telekom, Museum of Contemporary Art Zagreb, Croatia **Follow the Line -** POSITIONEN ZEITGENÖSSISCHER ZEICHNUNG, Kunsthalle der Spaskasse, Leipzig**2017****Festivities Are Cancelled!**Exhibition by curatorial collective Hudrada at The Kyiv International – Kyiv Biennial 2017“UFO” at metro Lybidska (Ukrainian Institute of Scientific, Technical and Economic Information) and Pavlo Tychyna Literary Memorial Museum in Kyiv**Attention! Border****,**Arsenal Gallery in Bialystok and Galeria Labirynt in Lublin***A la frontier**, Šv. Jono gatvės galerija, Vilnius**History about some history**, curated by Jaroslav Futymskyi, Labyrinth Gallery in Lublin, Poland**Postpo****ned Futures**, GRAD, London**2016****У темряву**, VozdvizhenkaArtsHouse, Київ та WUK, Кунстхалле Екснергассе, Відень**The school of Kyiv. Leipzig class.** Seminar: Politics of Form, GFZK, Leipzig***Meanwhile, what about socialism?**, Gallery North, Northumbria University, Newcastle**2015** **Demonstrating Minds: Disagreements in Contemporary Art**, Museum of Contemporary Art KIASMA/ The Finnish National Gallery, Хельсінкі, Фінляндія***à la frontière…! old and new borders in Europe**,Studio Tommaseo, Trieste Contemporanea**Meshes of the Afternoon**(The Plein Air School of Landscape / Die Schule der Landschaft),Kyiv biennale, Kunsthalltrondheim, Norway**In spite of everything,** Polish Intitute Dusseldorf, Germany**Best evidence rule,** Verein für zeitgenössische Kunst Leipzig, Germany**Lest The Two Seas Meet,** Museum of Modern Art in Warsaw, Польща**Walk the Line. Neue Wege der Zeichnung**, Kunstmuseum Wolfsburg, Німеччина**2014****Homey,** интервенция, Krakow Theatrical Reminiscences, Польща**State of things**, персональна виставка, Toulouse Art Festival, Espace Croix-Baragnon, Тулуза, Франція**Мобільна портативна модель**, персональна виставка, Eigen+Art, Берлін;**Референдум щодо виходу зі складу людства**, арт-центр Closer, Київ**Р.E.П.: 10 років. Про метод**, Labirint Gallery, Люблін, Польща**Through Maidan and Beyond,** Architekturzentrum Wien, Австрія**Sister Europa,** Kunstraum Lakeside, Klagenfurt, Австрія**Позбавлення****,** Arsenal gallery, Бялисток, Польща**Disconsent**, Center for Contemporary Art Plovdiv, Болгарія**Листівки з Майдану**, ЦСМ Замок Уяздовського, Варшава**The Ukrainians,** Daad gallery, Берлін, Німеччина**Gender and diplomacy – the »Ladies’ Programme«,**Haus der Kulturen der Welt, Berlin**Leipzig – Heldenstadt**?, Гете Інститут, Париж, Франція**Imaginary Archive**, Центр театрального мистецтва ім. Л. Курбаса, Київ, Україна**2013****Самоуправління: культурна еволюція vs****революція,** Одеська Бієнале сучасного мистецтва, Музей сучасного мистецтва Одеси, Україна**Measures of saving the world \_ part 3**, < rotor > center for contemporary art , Грац, Австрія**Economics in Art****,**Museum of Contemporary Art, Краків, Польща **Перегони з часом: Мистецтво 1960-х - початку 2000-х років,**Національний художній музей України, Київ;**Українські новини,**ЦСМ Замок Уяздовського, Польща, Україна**2012****Подвійна гра, спеціальний проект Арсеналє2012,************Мистецький Арсенал, Київ, Україна;********************Криві дзеркала, паралельна програма**********************Арсеналє2012, галерея Taiss спільно з галереєю Лавра, Київ, Україна;**********************Г********************ендер в Ізоляції. Право на самоконструювання в умовах патріархату, Ізоляція, галерея Медпункт, Донецьк********************;************Картина затуляє краєвид**,****Національний художній музей України, Київ;******Українське тіло**, ЦВК при НаУКМА, Київ, Україна**У найкращій формі,** Kunsthalle der Sparkasse, Лейпціг, Німеччина **2011****Переписывая миры, 4 Московска Бієнале, основний проект, Москва, Россія******Виставка 20-ти номінантів Премії PinchukArtCentre, 2011, Київ, Україна;Новояз, Мала галерея мистецького Арсеналу, Київ, Україна;Жовтневий проект, Am Flutgraben, Берлін, Німеччина;Незалежні/Independent, нове мистецтво нової країни 1991-2011, Мистецький Арсенал, Київ, Україна;****Шість і три, художники груп SOSka та Р.Е.П., галерея Brown Stripe та квартирна галерея на Черемушках, Москва, Россія************Просто. Мистецтво****,** Фундація Центр Сучасного Мистецтва, Національний художній музей України, Київ;**Космічна Одіссея****,** Мистецький Арсенал, Київ, Україна;**Слово**, Я галерея, Київ, Україна****Учні та освітлена площина**, в рамках лекції Культурного проекту, мала галерея Мистецького Арсеналу;**Перспектива**,проект у публічному просторі, Університетська бібліотека „Альбертіна” у м. Лейпціг, Германія;**2010** **Судовий експеримент**, проект Худради, приміщення ЦВК при НаУКМА, Київ, Україна;**Протести, диверсії, спільноти, ринки:****публічний простір у сучасному українському мистецтві**– відеопоказ, FLAT SPACE, Кишинів, Республіка молдова;**Art****-****Kyiv****contemporary****2010, паралельна виставка,**Мистецький арсенал, Київ;**Ті, хто прийшли у 2000-ні**, М17 Центр сучасного мистецтва, Київ, Україна;**Rundgang Spinnerei**, Ляйпціг, Німеччина;**[Minimal differences](http://galeria-arsenal.pl/arsenal.php?id=1152)**, White box, Нью-Йорк, США*;**[Over the counter](http://www.mucsarnok.hu/new_site/index.php?lang=en&t=539)**, Kunsthalle Mucsarnok, Будапешт, Угорщина***[At home in Wollishofen](http://www.artfoyer.org/exhibitions/at-home-in-wollishofen)**, artfoyer Cavigelli, Цюріх, Швейцарія**[Групова виставка художників фундаціїї BINZ39](http://www.binz39.ch/gruppenausstellung-stiftung-binz39.html)**, Цюріх, Швейцарія[**ЯКЩО / ЕСЛИ / IF. Українське мистецтво на зламі**](http://permm.ru/exposition/yaksho.html), PERMM музей, Пєрмь, Росія**[Євроремонт у Європі](http://www.kunstraum-muenchen.de/index.php?id=14&no_cache=1&tx_ttnews%5Btt_news%5D=759&tx_ttnews%5BbackPid%5D=17&cHash=be7b5de98b)**, Kunstraum München, Мюнхен, Німеччина*                          **Велика несподіванка**, Національний художній музей України, Київ***SUPERMARKET****-  the artist-run art fair**, Стокгольм, Швеція*; каталог: <http://www.ribbung.com/pdf/supermarket_2010_lr.pdf>[**Давайте поговоримо про націоналізм! Поміж ідеологією та ідентичністю**](http://www.publicpreparation.org/2010/lets-talk-about-nationalism/), Kumu Art Museum, Таллінн, Естонія***ArtParis, Grand Palaise, Париж, Франція****2009** **Революційні моменти**, Центр сучасного мистецтва при НаУКМА, Київ, Україна*, <http://revolutionarymoments.com/conference/>, [www.revolutionary-moments.blogspot.com](http://www.revolutionary-moments.blogspot.com/)            **Глядачі у лісі.****Художник та маніпуляція**, Weltraum, Мюнхен, Німеччина;                                                 **Речові докази**, галерея GEDOKmuc, Мюнхен, Німеччина;                                                                      **Communism Never Happened**, галерея Feinkost, Берлін, Німеччина*;                                             **Майбутнє було вчора. Самоорганізаційні художні практики з України**, Gallery SC + Gallery PM/HDLU, Загреб, Хорватія.  **Leipzig calling**, New York Academy of Art, Нью Йорк, США;                                                                                  **Місце**, Центр сучасного мистецтва при НаУКМА, Київ, Україна;                                                             **[Homestories II](http://www.revisitinghome.de/homestories2/homestories3.html)**, Arttransponder, Берлін, Німеччина;**Відкриті дні**, Spinnerei, Ляйпціг, Німеччина;                                                                                                     **2.****Katowice Biennale**, Катовіце, Польша*;**Open City**, фестиваль мистецтва у публічному просторі, Люблін, Польша*;                                             **No More Reality. Crowd and Performance**, Depo, Стамбул, Турція*;                                                                            **[Land of Human Rights: Being Responsible for Resources](http://www.landofhumanrights.eu/eng/project/exhibition5-2009.html)**, < rotor > - художня асоціація, Грац, Австрія*; **2008** **Art as A Present**, Pinchuk Art Centre, Київ, Україна*;**Alphabetical Order**, Index – Шведська фундація сучасного мистецтва, Стокгольм, Швеція*;**Another City. Another Life**, Zacheta Gallery, Варшава, Польша*;**No More Reality**, De Appel Art Centre, Амстердам, Голландія*;**Про Это****,** в межах Бієнале молодого мистецтва, Державний центр сучасного мистецтва, Москва, Росія*;**Свіжа кров**, Diehl + Gallery One, Москва, Росія;**Satellite Tunes**, Угорський університет мистецтв, Будапешт, Угорщина*;**2007****Назовні**, Центр сучасного мистецтва, Київ, Україна;**Consequences and Proposals**, Бієнале молодих художників, Таллін, Естонія*;**Contemporary Art Norwich**, Норвіч, Англія*;                                                                                                  **Поема про внутрішнє море**, у співпраці з Марком Тічнером, Український павільйон, 52 Венеційська бієнале, Венеція*;**Critically in-between**, спеціальний проект на ярмарці «Арт-Афіни», Афіни, Греція*;**Прогресивна ностальгія**, Centro Luigi Pecci, Прато, Італія*;**Від Косово до Калінінграду**, Третя пражська бієнале сучасного мистецтва, Прага, Чехія*;**Повернення пам’яті**, KUMU Museum, Таллінн, Естонія*;**Петроліана. Нафтовий патріотизм**, Друга московська бієнале сучасного мистецтва, Московський музей сучасного мистецтва, Москва, Россія*;**Generation UsA**, Pinchuk Art Center, Київ, Україна;**2006** **Postorange**, Kunsthalle, Відень, Австрія*;**Інтервенція**, ЦСМ Замок Уяздовський, Варшава, Польша*;**Contested Spaces in Post-Soviet Art**, Sidney Mishkin Gallery, Нью Йорк, США*;**Резиденції****2020** Жовтень-листопад: Wielka19 Assosiation, Познань, Польща**2018** Reading International, Редінг, Великобританія**2017** November: DAAD “Arts and Media” programm, дослідницька стипендія**2017** June-September: Aschersleben, Німечина***2017** Stipendium Griffelkunst*at the print workshop of Ellen Sturm, Гамбург [>>](http://www.griffelkunst.de/en)**2015, 2012** a-i-r Laboratory, ЦСМ Замок Уяздовського, Варшава, Польша**2015** KulturKontakt Austria, Відень**2015** Residency in 18t Street Arts Center, Санта Моніка, США**2014** Fellowship at the Hanse-Wissenschftskolleg, Делменхорст, Німеччина**2012**липень-серпень: a-i-r Laboratory, ЦСМ Замок Уяздовського, Варшава, Польша**2010** березень - серпень: резиденція **[*BINZ39*](http://www.binz39.ch/gast-stipendiatguest-stipendiary-lada-nakonechna)**, Цюріх и Zuger Kulturstiftung Landis & Gyr, Цуг, Швейцарія;**2009** вересень - листопад: резиденція [***Villa Waldberta***](http://www.villa-waldberta.de/), Мюнхен, Германія; **2008-2009**[***LIA – Leipzig International Art Program***](http://www.liap.eu/), Ляйпціг, Німеччина; **2005** однорічна резиденція групи Р.Е.П. у Центрі сучасного мистецтва, Київ, Україна**вибрані лекції****, презентації**2021 Лекція-презентація в рамках семінару Florian Malzacher, Institut für Angewandte Theaterwissenschaft im Wintersemester 2020/21, Gießen2021 Гостьова лекція в рамках семінару Євгенії Белорусець, Humboldt-Universität zu Berlin2017 Reading International. Curatorial Network Talk #1: Lada Nakonechna, South Street Arts, Reading, UK2017 Exchanging Notes 2: Making Memories, Seminar at the Norrköping Art Museum, Sweden2012 травень: лекція в Ізоляції, Донецьк2011 серпень: панельна дискуссія *The**journey**to**the**East*, Бялосток, Польща2011 січень: Мистецтво у публічному просторі**,**симпозіум,Університетська бібліотека міста Лейпціг, Німеччина2011 січень: *Invisible**Borders**,**Лада Наконечна, Лучезар Бояджиєв та Іван Базак презентація та дискуссія* (модератор Heiko Schmid), Master Fine Arts, Цюрих, Швейцарія2010 квітень: Visiting artist, Theory Tuesdays, Corner college, Цюріх, Швейцарія, http://www.corner-college.com/Archiv/142009 листопад: Пост радянське та пост помаранчове: молоде українське мистецтво, Lothringer13 -  Städtische Kunsthalle München, Мюнхен, Німеччина**Виставки кураторського об'єднання Худрада:****2018****Союз буд. Синдром того, хто вижив,**Михайлівська площа, Київ**2017** **Свято скасовано!** Київський Інтернаціонал – Київська бієнале 2017, «Тарілка» на м. Либідська (будівля Українського інституту науково-технічної та економічної інформації) та Літературно-меморіальний музеї-квартира П. Г. Тичини в Києві**2016****У темряву**, VozdvizhenkaArtsHouse, Воздвиженська 32, Київ**У темряву**, WUK, Кунстхалле Екснергассе, в рамках Бієнале сучасного мистецтва «Київська школа», Відень**2014****Нецільове використання приміщення**, Хрещатик 34, 2 поверх, Київ**Референдум по виходу зі складу людства,**  Closer art-centre, Київ, Україна та Teatr Powszechny, Варшава, Польща**2013** **Союз буд. З’їзд перший**, село Маломокко, острів Лідо, Венеція**Портфоліо-ревю “Відомі та знамениті”**, ЦСМ Замок Уяздовського, Варшава, Польша**Судовий експеримент**, SIZ gallery, Рієка, Хорватія**2012****Спірна територія**, Художній музей ім. М.П. Крошицького, Севастополь, Україна**2011****Трудова виставка**, ЦВК при НаУКМА, Київ, Україна**Судовий експеримент** в рамках некомерційної програми VIENNAFAIR 2011, Відень, Австрія**2010****Судовий експеримент**,  ЦВК при НаУКМА, Київ, Україна**2009****Постер-кампанія проти гомофобії та інших форм страху**, Київ, міський простір**Погляди**, Центр сучасного мистецтва, Київ, Україна**2007-2008 *Штаб,* кураторський проект групи Р.Е.П. для підтримки молодих художників:**          2008 *Транзит,* Я галерея, Київ, Україна          2008 *Спільний простір,* публічний простір, Київ, Україна          2008 *Нова українська мова*, галерея Карась, Київ, Україна          2007 *Спільноти: українські молоді художники*, галерея Арсенал, Бялосток, Польща          2007 *Проект спільнот*, Центр сучасного мистецтва, Київ, Україна |





 



 |







  







[Sign in](https://accounts.google.com/ServiceLogin?continue=http://sites.google.com/a/ladanakonechna.com/ladanakonechna-com/info/cvua/cv_ua&service=jotspot)|[Report Abuse](http://sites.google.com/a/ladanakonechna.com/ladanakonechna-com/system/app/pages/reportAbuse)|[Print Page](javascript:;)|Powered By **[Google Sites](http://sites.google.com/site)**






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
 


