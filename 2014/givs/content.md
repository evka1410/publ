Dobrý den,

jmenuji se Jáchym Čepický, jsem člen představenstva Open Source Geospatial
Foundation a předseda občanského sdružení Otevřená
GeoInfrastruktura, více než deset let se zabývám vývojem open source software
pro geoinformatiku. Úzce s tím souvisí i to, že trochu déle se počítám mezi
uživatele operačního systému GNU/Linux. To obyčejně nepovažuji za důležité
zmiňovat, ale v kontextu této přednášky to považuji za významou skutečnost.

Během studií jsem u svého kamaráda našel v jeho knihovničce knížku Učíme se Red Hat Linux
a při jejím čtení mi došlo, že vedle počítačů jak je znám existuje jiný
svět, který bych rád poznal. V té době pro mě počítač bylo PC s MS Windows 98,
používal jsem Excel na tvorbu protokolů a prací pro svůj obor (kterým bylo lesní
inženýrství). Nikdy jsem neměl ambici programovat, počítače jsem chápal jako
nástroje, které by mi měli v ideálním případě usnadnit práci. V knížce jsem se
seznámil se základními ideemi open source a free software a byly mi sympatické,
jakkoliv jsem nedokázal pochopit, proč by někdo sdílel svoji práci -
intelektuální vlastnictví - s kýmkoliv jiným. Když se mi v krátké době podařilo
pořídit si svůj vlastní nový počítač, požádal jsem kamaráda o pomoc
nainstalovali jsme můj první Linux. 

Od té doby jsem se stal uživatelem open source a free software a postupem času i
jeho spolutvůrcem. Naučil jsem se, jak funguje komunita uživatelů a přispěvatelů
do open source software, pochopil jsem některé jemné rozdíly mezi svobodným
software a otevřeným software a tak dále. A dnes chápu, že open source, nebo
obecně tak zvaný crowd source - sdílený přístup - není žádná anomálie.

Většina z vás už určitě slyšela o tom, že hnutí free software založil Richard
Matthew Stallman v 80. letech minulého století prací na operačním systému GNU.
Definoval tři základní svobody nebo práva, které by měl každý uživatel software
mít: právo vidět zdrojový kód, právo sdílet zdrojový kód a právo měnit zdrojový
kód a dále ho sdílet.

V systém se stal úspěšný také díky jádru operačního systému Linux. Dnes je Linux
nejpoužívanějším serverovým operačním systémem, používá se v mobilních
zařezních, na super počítačích. Proč se tak stalo? Protože je to otevřený systém
- systém, ve kterém ostatní sdílí svůj kód - svoje know-how - svoje
 intelektuální vlastnictví s ostatními.

Ale koncept sdílení není přece vynalezen v 80 letech. Západní věda tak jak ji
chápeme je snad od dob antiky postavena na stejných principech: publikuji
výsledek způsobem, že je opakovatelný, očekávám, že někdo jiný mou práci
zopakuje, přezkouší její platnost, případně navrhne některé změny, a výsledek
opět publikuje. Vědecká komunita díky sdílení informací posouvá hranice našeho
poznání dále, stejně jako komunita vývojářská posouvá hranice software.

Open source software není jediný příklad pro fungující intelektuální
spoluvlastnictví. Nikdo snad nepochybuje, že wikipedia je spolehlivý informační
zdroj a přitom na její obsah nemá nikdo monopol, neexistuje globální autorita,
která by strážila věcný obsah Wikipedie. OpenStreetMap je podle mě další
úspěšný projekt. Jako geoprostoroví profesionálové můžete zpochybňovat polohovou
přesnost dat, jejich faktickou správnost nebo aktuálnost, ale nemůžete
zpochybnit, že globálně vzato je to ucelený dataset který nemá v prorietárním
světe obdoby.

Všechny tyto příklady mají díky svým licencím společné tři základní vlastnosti,
které vyzývají další a další uživatele aby se přidali: vidět obsah, sdílet obsah
a provádět změny v obsahu a sdílet tyto změny dál.

Open Source a geoinformační technologie: co k tomu říct. Všichni jste slyšeli o
GRASS GIS, mnozí mají na svých počítačích QGIS, většina používá knihovnu GDAL,
anižby o tom věděla, jsouc používána mimo jiné v ESRI ArcGIS nebo asi tušíte, že
místo prorietárních databázových systémů lze použít PostgreSQL s prostorovou
nadstavbou PostGIS. Možná jste si všimli, že nejeden český velký geoportál
používá pro zobraní mapové části knihovnu OpenLayers, a už jste slyšeli, že
MapServer je skutečně mapový server.

Je jen málo oblastí geoinformatiky, které by nebyly pokryty kvalitním open
source software - i když připouštím, že jsou. Stále vznikají nové programy pro
další oblasti, staré ozkoušené projekty jsou ale stále zde, stabilní, s
rozšířenou vývojářskou a uživatelskou komunitou, stále dostávají nové funkce, ty
staré jsou oprašovány a udržovány.

Kdo jste ještě nebyli na žádné konferenci zabývající se obecně geo* open source
software, doporučuji vám navštívit některou z konferencí FOSS4G, ať už letos ve
Spojených státech globální, nebo její evropskou odnož v Brémách. Máte také
možnost nahlídnout přímo do  vývojářské kuchyně na některém z code sprints,
naposledy ve Vídni, další možnost budete mít v italském Bozlanu. 

Z toho všeho co říkám si možná říkáte: proč to tedy nidko nepoužívá, když je to
tak skvělý produkt? Proč není open source software dávno rozšířenější, než jak
to vypadá?

Důvody pro tento stav - a je jedno jestli je to objektivní fakt nebo subjektivní
pocit - jsou samozřejmě mnohé a jak už to bývá, mají povahu vnitřní i vnější.

Jako jeden z prvních důvodů (bez nároku na prvenství z hlediska významosti)
uvedu to, že člověk používá to, co zná. Věřím, že obsahem výuky na
školách ve všech oborech a stupních by měly být především obecně platné
principy, až od nich odvozené konkrétní situace. Učíme obecně Archimedův zákon,
a teprve následně několik jeho praktických aplikací, jako že ve vodě je slon
lehčí nebo spolu s inženýry španělského námořnictva, že ponorka, má-li se vynořit,
musí mít především v součtu menší objemovou hustotu, než voda. Proč se ale tento
princip uplatňuje při výuce software jen velice zřídka? Proč výuka počítačí
obecně a GIS konkrétně se téměř bez výjimky provádí na konkrétním jednom
software?

Dalším důvodem je neexistejce jednohého telefonního čísla - chybí marketingové
oddělení open source GIS, není tu někdo, kdo by zákazníkům vysvětlil proč je
konkrétní produkt ten nejlepší (v absolutním i relativním významu). U open source
software se předpokládá, že jste dospělí, že jste nebo se chcete stát experty a
proto na to, co je pro váš případ to nejlepší si přijdete sami. Open source je
náročný na lidské zdroje, pokud nemáte u sebe někoho dalšího, jste v tom tak
trochu sami, "jenom" s podporou komunity. To může hodně lidí odradit, ale
bylo mnohokrát  ilustrováno, že podpora komunity funguje, první odpověď v mailing
listech bývá u větších projtků v řádu minut.

Dalším důvodem bude roztříštěná nabídka open source software. Jak jsem řekl
dříve, nemáte se moc koho zeptat a ještě ke všemu si musíte vybírat z množství
variant -- sám s tím mám často problém. Provozní výzkum, porovnávání různých
programů a sledování nových je denní chléb. Mám vzít TileCache, MapStach,
GeoServer cache, MapCache? A co je to ten Mapnik? A jaký je rozdíl mezi Leaflet
a OpenLayers? Na tyto otázky získáte nejlépe odpověď tak, že budete číst nebo se
zeptáte někoho, kdo to ví, ale jak jsem již řekl - ve vašem okolí je většinou
problém najít někoho kdo by to věděl. Nebo snad ne?

Dalším důvodem je nejednotný systém návazného vzdělávání. Existují spíše
jednotlivci, nebízející školení. Školení jsou ale nejednotná, různá obsahem i
kvalitou.

Důvodů, proč open source software není úspěšnější - myšleno absolutně - je ještě
celá další řada. Některé z nich a některé z již zmíněných se bude snažit zaplnit
na naší geo- scéně projekt GISMentors.

Projekt GISMentors je společný projekt několika jednotlivců, kteří se rozhodli
spojit své síly a nabídnout pod společnou hlavičkou kvalitní školení pro
co nejširší oblast open source GIS. Školení budou obsahovat všechno to, na co
jsou účastníci podobných akcí zvyklí, ale ještě i něco navíc -- účastníci si
odnesou s sebou domů i software, na kterém školení probíhalo spolu s daty, která
byla použita. Doufáme, že se nám tak podaří snížit jednu z bariér pro větší
rozšíření open source software pro geoprostorové informace. 

Máme tým zkušených školitelů, kteří za sebou mají doposud individuální školicí a konzultační
praxi v oblasti Open Source GIS. Dali jsme se dohromady tak, abychom pokryli
co nejšiřší spektrum poptávky. Víme, že nemáme pokryté všechny open source
projekty a proto očekáváme jeho růst.

Takže věříme, že budete-li mít v budoucnu problém s open source software pro GIS
nebo budete-li si chtít doplnit vzdělání, budete mít kde.
