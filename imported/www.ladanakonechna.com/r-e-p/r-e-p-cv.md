




/* Copyright 2008 Google. */ (function() { /*

Copyright The Closure Library Authors.
SPDX-License-Identifier: Apache-2.0
*/
(function(){function e(g){this.t={};this.tick=function(h,k,f){this.t[h]=[void 0!=f?f:(new Date).getTime(),k];if(void 0==f)try{window.console.timeStamp("CSI/"+h)}catch(m){}};this.getStartTickTime=function(){return this.t.start[0]};this.tick("start",null,g)}var a;if(window.performance)var d=(a=window.performance.timing)&&a.responseStart;var l=0<d?new e(d):new e;window.jstiming={Timer:e,load:l};if(a){var b=a.navigationStart;0<b&&d>=b&&(window.jstiming.srt=d-b)}if(a){var c=window.jstiming.load;0<b&&d>=
b&&(c.tick("\_wtsrt",void 0,b),c.tick("wtsrt\_","\_wtsrt",d),c.tick("tbsd\_","wtsrt\_"))}try{a=null,window.chrome&&window.chrome.csi&&(a=Math.floor(window.chrome.csi().pageT),c&&0<b&&(c.tick("\_tbnd",void 0,window.chrome.csi().startE),c.tick("tbnd\_","\_tbnd",b))),null==a&&window.gtbExternal&&(a=window.gtbExternal.pageT()),null==a&&window.external&&(a=window.external.pageT,c&&0<b&&(c.tick("\_tbnd",void 0,window.external.startE),c.tick("tbnd\_","\_tbnd",b))),a&&(window.jstiming.pt=a)}catch(g){}})(); })()



/* Copyright 2008 Google. */ (function() { function d(a){return document.getElementById(a)}window.byId=d;function g(a){return a.replace(/^\s+|\s+$/g,"")}window.trim=g;var h=[],k=0;window.JOT\_addListener=function(a,b,c){var f=new String(k++);a={eventName:a,handler:b,compId:c,key:f};h.push(a);return f};window.JOT\_removeListenerByKey=function(a){for(var b=0;b<h.length;b++)if(h[b].key==a){h.splice(b,1);break}};window.JOT\_removeAllListenersForName=function(a){for(var b=0;b<h.length;b++)h[b].eventName==a&&h.splice(b,1)};
window.JOT\_postEvent=function(a,b,c){var f={eventName:a,eventSrc:b||{},payload:c||{}};if(window.JOT\_fullyLoaded)for(b=h.length,c=0;c<b&&c<h.length;c++){var e=h[c];e&&e.eventName==a&&(f.listenerCompId=e.compId||"",(e="function"==typeof e.handler?e.handler:window[e.handler])&&e(f))}else window.JOT\_delayedEvents.push({eventName:a,eventSrc:b,payload:c})};window.JOT\_delayedEvents=[];window.JOT\_fullyLoaded=!1;
window.JOT\_formatRelativeToNow=function(a,b){a=((new Date).getTime()-a)/6E4;if(1440<=a||0>a)return null;var c=0;60<=a&&(a/=60,c=2);2<=a&&c++;return b?window.JOT\_siteRelTimeStrs[c].replace("\_\_duration\_\_",Math.floor(a)):window.JOT\_userRelTimeStrs[c].replace("\_\_duration\_\_",Math.floor(a))}; })()



 

 var breadcrumbs = [{"path":"/r-e-p","deleted":false,"title":"R.E.P. group","dir":"ltr"},{"path":"/r-e-p/r-e-p-cv","deleted":false,"title":"R.E.P. CV","dir":"ltr"}];
 var JOT\_clearDotPath = 'http://www.gstatic.com/sites/p/f560b7/system/app/images/cleardot.gif';

 
 var JOT\_userRelTimeStrs = ["a minute ago","\_\_duration\_\_ minutes ago","an hour ago","\_\_duration\_\_ hours ago"];

 
 

 

 var webspace = {"gvizGstaticVersion":"current","enableAnalytics":false,"pageSharingId":"jotspot\_page","codeembeds":{"outerIframeSrc":"https://www.gstatic.com/jotspot/embeds/code/0f08d42392f2000e7e3f3daf5b427a43/outer\_iframe.html","innerIframeSrc":"https://1140525463-jotspot-embeds.googleusercontent.com/code/8d87fa64604b2a11fae2ed06104c58d3/inner\_iframe.html"},"enableUniversalAnalytics":false,"sharingPolicy":"OPENED\_WITH\_INDICATOR","siteTitle":"ladanakonechna.com","experiments":{"enableSubpagesGadgetInTakeout":true,"overrideDisableDomainEditing":false,"DisableSiteEditingFeature\_\_disable\_site\_editing":true,"disableDomainEditing":false},"jot2atari":{"eligibility":"INELIGIBLE"},"onepickUrl":"https://docs.google.com/picker","adsensePublisherId":null,"features":{"moreMobileStyleImprovements":null,"subscriptionDataMigrationInProgress":null,"plusBadge":false},"configProperties":{"disableSiteEditing":null},"isPublic":true,"newSitesBaseUrl":"https://sites.google.com","isConsumer":false,"serverFlags":{"jot2AtariLearnMoreUrl":"https://support.google.com/sites/answer/7035197"},"domainAnalyticsAccountId":"","plusPageId":"","signInUrl":"https://accounts.google.com/AccountChooser?continue=http://sites.google.com/a/ladanakonechna.com/ladanakonechna-com/r-e-p/r-e-p-cv&service=jotspot","analyticsAccountId":"","scottyUrl":"/\_/upload","homePath":"/","siteNoticeUrlEnabled":null,"plusPageUrl":"","adsensePromoClickedOrSiteIneligible":true,"csiReportUri":"http://csi.gstatic.com/csi","sharingId":"jotspot","termsUrl":"//www.google.com/intl/en/policies/terms/","gvizVersion":1,"editorResources":{"sitelayout":["http://www.gstatic.com/sites/p/f560b7/system/app/css/sitelayouteditor.css"],"text":["http://www.gstatic.com/sites/p/f560b7/system/js/codemirror.js","http://www.gstatic.com/sites/p/f560b7/system/app/css/codemirror\_css.css","http://www.gstatic.com/sites/p/f560b7/system/js/trog\_edit\_\_en.js","http://www.gstatic.com/sites/p/f560b7/system/app/css/trogedit.css","/\_/rsrc/1638433988000/system/app/css/editor.css","http://www.gstatic.com/sites/p/f560b7/system/app/css/codeeditor.css","/\_/rsrc/1638433988000/system/app/css/camelot/editor-jfk.css"]},"sharingUrlPrefix":"/\_/sharing","isAdsenseEnabled":true,"domain":"ladanakonechna.com","baseUri":"","name":"ladanakonechna-com","siteTemplateId":false,"siteNoticeRevision":null,"siteNoticeUrlAddress":null,"siteNoticeMessage":null,"page":{"isRtlLocale":false,"canDeleteWebspace":null,"isPageDraft":null,"parentPath":"/r-e-p","parentWuid":"wuid:gx:242d1b707563f44b","siteLocale":"uk","timeZone":"America/Los\_Angeles","type":"text","title":"R.E.P. CV","locale":"en","wuid":"wuid:gx:5c4d5c99d91a8559","revision":7,"path":"/r-e-p/r-e-p-cv","isSiteRtlLocale":false,"pageInheritsPermissions":null,"name":"r-e-p-cv","canChangePath":true,"state":"","properties":{},"bidiEnabled":false,"currentTemplate":{"path":"/system/app/pagetemplates/text","title":"Web Page"}},"canPublishScriptToAnyone":true,"user":{"keyboardShortcuts":true,"sessionIndex":"","guest\_":true,"displayNameOrEmail":"guest","userName":"guest","uid":"","renderMobile":false,"domain":"","namespace":"","hasWriteAccess":false,"namespaceUser":false,"primaryEmail":"guest","hasAdminAccess":false,"isGoogleAdmin":false},"gadgets":{"baseUri":"/system/app/pages/gadgets"}};
 webspace.page.breadcrumbs = breadcrumbs;

 
 var JOT\_siteRelTimeStrs = ["\u0445\u0432\u0438\u043b\u0438\u043d\u0443 \u0442\u043e\u043c\u0443","\_\_duration\_\_ \u0445\u0432\u0438\u043b\u0438\u043d \u0442\u043e\u043c\u0443","\u0433\u043e\u0434\u0438\u043d\u0443 \u0442\u043e\u043c\u0443","\_\_duration\_\_ \u0433\u043e\u0434\u0438\u043d \u0442\u043e\u043c\u0443"];



 window.jstiming.load.tick('scl');
 









R.E.P. CV - ladanakonechna.com



 window.jstiming.load.tick('cl');
 



 








|  |  |
| --- | --- |
| [ladanakonechna.com](../index.html) |  |
|  |







|  |  |  |
| --- | --- | --- |
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
	+ R.E.P. CV
	+ [R.E.P. Projects](r-e-p-projects)
 | 
 

[R.E.P. group](../r-e-p)‎ > ‎
 

R.E.P. CV





| 
**R.E.P.**
(revolutionary experimental space) group was found in 2004. 
Since 2006 members of R.E.P. group are Nikita Kadan, Zhanna Kadyrova, Lesia Khomenko,
Volodymyr Kuznetsov, Ksenia Hnylytska, Lada Nakonechna,
all live and work in Kyiv, Ukraine

In **2006** group started own curatorial program
named “Shtab” (“Hadquarters”)
In **2008**
initiated HUDRADA (http://hudrada.tumblr.com/), the curatorial
union based on interdisciplinary communication

**Selected exhibitions**
**2018**
**The
Opposing Shore**, Université de Bretagne
Occidentale, Brest, France

**2017**
**Attention! Border!** Galeria
Arsenał
elektrownia, Białystok,
Galeria Labirynt, Lublin
**2016**
**After the
Rally,** Studio Gallery, Palace of Culture and Science, Warsaw
**Universal hospitality**, Alte Post, Wien
**Meanwhile, what
about socialism?**, Gallery North, Northumbria University, Newcastle**Dependence degree**, BWA Wrocław - Gallery of
Contemporary Art
**2015****R.E.P. – On method, 10 years**, Contemporary Art Space, Batumi/ Georgian State Art Museum, Tbilisi
**Limited liability pavilion**, apartment exhibition during56th International Art Exhibition – la Biennale di Venezia, Italy
**Demonstrating Minds:
Disagreements in Contemporary Art**, Museum of Contemporary Art KIASMA/
The Finnish National Gallery, Helsinki, Finland**Art has no alternative** ***(An Archive of Artists in Action)***,tranzit.sk*,* Bratislava,
Slovakia
**2014****The Wall, Art Face to Face with Borders**, Careof
DOCVA, Milan
**Referendum on withdrawal from the human race**,Teatr Powszechny im. Zygmunta Hübnera, Warsaw, Poland/Closer art centre,
Kyiv, Ukraine
**R.E.P. – On method, 10 years**, Labirynt gallery, Lublin, Poland
**Through maidan and beyond**, Architekturzentrum Wien in MuseumsQuartier,
Vienna, Ausria 
**Deprivation**, Arsenal gallery, Bialystok, Poland
**The Ukrainians**, daadgalerie, Berlin, Germany
**Imaginary archive**, Les Kurbas centre, Kyiv, Ukraine
**Disobedience Archive (The park)**, SALT Beyoğlu, Istanbul, Turkey
**Piazza dell`imaginario**, Prato, Italy
**The stairs**, project organized by Polish Institute on Ivana Franka st, Kyiv,
Ukraine
**2013** 
**Whisper down the lane**, Gallery 400, Chicago, USA
**global aCtIVISm,** ZKM | Museum
of Contemporary Art, Karlsruhe, Germany
**Odessa
Biennale of Contemporary Art, Self-government:
cultural evolution vs. Revolution,**
Odessa,Ukraine
**Ukrainian news,** CSW Zamek Ujazdowsky,
Warsaw, Poland
**Union of Hovels,**
First congress, Lido, Venice
**“The Future Generation Art Prize@Venice 2013”** Collateral Event of the 55th International Art Exhibition – la Biennale
di Venezia, Italy
**Disobedience Archive (The Republic),** Castello di Rivoli Museo d’Arte Contemporanea, Turin
**Court
Experiment**, SIZ gallery, Rijeka
**Showing its
colours. What makes art**, MARTa Herford, DE
**Sun of the
Poor**, Ya Gallery Art Center,
Dnipropetrovsk
 
**2012**
**Cantastoria,** UMOCA (Utah Museum
of Contemporary Art), Salt Lake City, USA
**It isn't
important, it's only art...,** Arsenal Gallery, Białystok, Poland
**“Disputed
Territory” is the 4th exhibition of the Ukrainian Curatorial Collective HUDRADA**, Sevastopol
Art Museum in Crimea, Ukraine
**"THE BEST OF TIMES, THE WORST OF TIMES – REBIRTH
AND APOCALYPSE IN CONTEMPORARY ART"**, main project of First Kyiv biennale
of contemporary art ARSENALE 2012, Museum Complex
"Mystetskyi Arsenal", Kyiv, UA
**“Myth
"Ukrainian baroque”,** National Art Museum, Kyiv
***Who told you so?!
#1*****Truth vs. Government**, Onomatopee
projectspace, Eindhoven, The Netherlands
**Atlas critique****,**Parc Saint Léger, Centre d’art
contemporain, France
**2011**
***Labor show***, CCA at
National University Kyiv Mohyla Academy, Visual Culture Research
Center, Kyiv, Ukraine
**Between
Ideology and Identity**. Budapest Version, in Labor,
Budapest, Hungary
**Impossible community**, Moscow
Museum of Modern Art, Russia  
**LIFE IN THE FOREST**, Galeria
Arsenal, Bialystok, Poland 
**ATLANTIS 11,****The alternative Bulgarian pavilion,**54th
Venice Biennial, Italy
**Independent,** Art Arsenal, Kyiv, Ukraine 
**A
complicated relation,** part 2, KALMAR KONSTMUSEUM, Kalmar, Sweden
**Making and art**,
Stadtgalerie Schwaz, Austria
**Public Folklore**, Grazer
Kunstverein, Graz, Austria 
**2010**
**PROTESTS, SUBVERSIONS, COMMUNITIES,
MARKETS: PUBLIC SPACE IN CONTEMPORARY UKRAINIAN ART**,
public screening, FLAT
SPACE, Chisinau 
**Art-Kyiv Contemporary,** parallel
exhibition, Art Arsenal,Kyiv,
Ukraine,
**Those, who came at the start of 2000**,
M17 Contemporary art centre, Kyiv, Ukraine
**Annex 6.** **The Politics of the Invisible Hand**,
ART IST KUKU NU UT 2010, Y-Gallery, Tartu,
Estonia
**Videozone 5, The 5 International Video Art
Biennial in Israel,** CCA, Tel Aviv, Israel
**Minimal Differences****,** White
Box, New York, USA
**ЯКЩО****/** **ЕСЛИ****/ IF. Ukrainian Art in Transition,** PERMM museum, Perm, Russia
**When One Has to Say “We”: Art as the Practice of
Solidarity**, Saint Petersburg, Russia 
**Over the
Counter,** Műcsarnok / Kunsthalle, Budapest
**Rain Of
Down,** Culturehouse Telakka, Tampere, Finland
**Euro renovation in Europe,** Kunstraum
muenchen, Munich, Germany
**Great surprise,** National Art Museum of Ukraine, Kyiv,
Ukraine
**SUPERMARKET** - the
artist-run art fair, Stockholm, Sweden
**Let’s talk about nationalism! Between ideology and identity,** Kumu Art
Museum, Tallinn, Estonia 
 
**2009**
**Revolutionary moments**, Center
for Contemporary Art at National University Kiev Mohyla Academy,  Kyiv, Ukraine;
**Communism Never Happened**,
Feinkost gallery, Berlin, Germany;
**FUTURE WAS YESTERDAY. Self organized artistic
practices from Ukraine,** Gallery SC + Gallery PM/HDLU,
Zagreb, Croatia;
**Old Cold War. Pols Socialist Countries Experience,** 3rd
Moscow Biennale, Moscow, Russia;
**Views,** Center for
Contemporary Art at National University Kiev Mohyla Academy, Kyiv, Ukraine;
**(Re)Socialisation of Art**, Museum of
Modern Art, Odesa, Ukraine;
**Open city,** Festival of
art in public space,Lublin, Poland;
**2. Katowice Biennale,** Katowice,
Poland;
**No More Reality. Crowd and performance,** Depo,
Istanbul, Turkey;
**Land of Human Rights: Being Responsible for
Resources**, < rotor > - art association in Graz, Austria 
 
**2008**
**Art as a present,** Pinchuk Art
Center, Kyiv, Ukraine;
**Alphabetical order,** Index – The
Swedish Contemporary Art Foundation, Stockholm, Sweden;
**Gyumry biennial,** Gyumry,
Armenia;
**EPAF** – European
festival of performances, Warsaw, Poland;
**Another city. Another life,** Zacheta
gallery, Warsaw, Poland;
**No more reality,** De Appel Art
Centre, Amsterdam, Holland;
**Pro** **Это****,**“Qui vive?” Biennale of young artists, State Centre
for contemporary art, Moscow, Russia;
**Transit**, curatorial projeсt
of R.E.P. group, “Ya gallery”, Kyiv**,**Ukraine;
**Common Space**, curatorial projeсt
of R.E.P. group supported by “Eidos” foundation, public
environment, Kyiv, Ukraine;
**New Ukrainian Language**, curatorial projeсt
of R.E.P. group, “Karas gallery”, Kyiv,
Ukraine;
**Checkpoint,** F.A.I.T.
gallery, Krakow, Poland;
**Satellite Tunes,**  National University of Fine Arts, Budapest,
Hungary;
**Shengen**, Feinkost gallery, Berlin, Germany
 
**2007**
**Consequences and Proposals,** Biennale
of young artists,Tallinn, Estonia;
**Contemporary art Norwich,** Norwich,
England;
**Ukrainian pavilion. Berlin,** Bereznitsky
gallery, Berlin, Germany;
**Patriotism”,** Capsula
gallery, Rome, Italy;
**Ginnungagap/Pavilion of Belief,** Presentation
of “Im Regierungsviertel” gallery in time of 52 VeniceBiennale, Venice,
Italy;
**We are Ukrainians,** In
collaboration with Mark Titchner, Ukrainian pavilion on 52 Venice Biennale,
Venice, Italy;
**Critically in between,** Special
project of “Art-Athina 2007” art fair, Athens, Greece;
**Progressive nostalgia,** Centro
Luigi Pecci, Prato, Italy;
**From Kosovo to Kaliningrad,** Third
Prague Biennale of Contemporary Art, Prague, Czechrepublic
**Return of memory,** KUMU museum,
Tallinn, Estonia;
**Comunities. Young artists from Ukraine,** curatorial
project of R.E.P. group, “Arsenal” gallery, Bialostok, Poland;
**Communities project**, curatorial
project of R.E.P. group, Center for Contemporary Art at National University
Kyiv Mohyla Academy, Kyiv, Ukraine;
**Petroliana. Oil patriotism**,
Second Moscow Biennale of Contemporary Art, Moscow Museum for Contemporary Art,
Moscow, Russia;
 
**2006** 
**Testing station**, “Skulpturens
Hus”, Stockholm, Sweden;
**Hot / Cool Ukraine,** Moscow,
Russia;
**Patriotism tomorrow,** Wyspa
institute for contemporary art, Gdansk;
**Festival of Contemporary Art in Shargorod,**
Ukraine;
**Contested Spaces in Post-Soviet Art**,
Sidney Mishkin Gallery, New York, USA;
**Intervention**, CSW Zamek
Ujazdowski, Warsaw, Poland;
**Terytoria**, Center of
culture in Lublin, Poland;
**New communities,** Caucasian
biennale, Tbilisi;
**Do You?!**, Zeh
gallery, Kyiv, Ukraine;
**Lirnyk**, project of
R.E.P. group, Festival of Performances in Ukraine, Kyiv, Ukraine;
**Postorange**, Kunsthalle, Vienna, Austria;
**Team Colors**, F.A.I.T.
gallery, Krakow, Poland;
**2005**
**Ukrainian
Hermitage** , Center for Contemporary Art at National University
Kiev Mohyla Academy,  Kyiv, Ukraine;
**Open laboratory**, Center for
Contemporary Art at National University Kiev Mohyla Academy, Kyiv, Ukraine;
**Ukrainian Art and the Orange Revolution**,
Ukrainian Institute of Modern Art, Chicago, U.S.A;
**Intervention**, Center for
Contemporary Art at National University Kyiv Mohyla Academy, Kyiv, Ukraine;
 
**2004** 
**Revolutionary Experimental Space**,
Center for Contemporary Art at National University Kyiv Mohyla Academy, Kyiv,
Ukraine.
 
**Residencies**
**2005** – Year
residence of R.E.P. group in Centre for Contemporary Art at Kyiv-Mohyla Academy
**2008** – Residence
in LIA – Leipzig International Art Program, Leipzig, Germany
 
**Collections**
Museo d’árte
contemporanea Luigi Pecci, Prato, Italy
Arsenal gallery, Bialystok, PolandLabirynt gallery, Lublin, Poland
FRAC Bretagne, France

 |





 



 |







  







[Sign in](https://accounts.google.com/ServiceLogin?continue=http://sites.google.com/a/ladanakonechna.com/ladanakonechna-com/r-e-p/r-e-p-cv&service=jotspot)|[Report Abuse](http://sites.google.com/a/ladanakonechna.com/ladanakonechna-com/system/app/pages/reportAbuse)|[Print Page](javascript:;)|Powered By **[Google Sites](http://sites.google.com/site)**






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
 


