title: "Otázky a odpovědi ke koronaviru"
perex: "Epidemie koronaviru, která se začala šířit z čínského města Wu-chan, děsí svět. První případy nákazy se už objevily na všech kontinentech a také státy Evropy čekají na případné spuštění svých pandemických plánů. Světová zdravotnická organizace nicméně varuje před šířením paniky a vzkazuje lidem, aby se drželi všech klíčových doporučení. Co o koronaviru víme? Jak se před ním chránit? A dá se odhadnout další vývoj?"
coverimg: https://www.irozhlas.cz/sites/default/files/styles/zpravy_snowfall/public/uploader/wu-chan_provizorni_n_200205-124042_eku.JPG?itok=nM-h1alK
coverimg_note: "Foto Reuters"
styles: ['https://unpkg.com/leaflet@1.6.0/dist/leaflet.css', 'https://data.irozhlas.cz/corona-map/style.css']
libraries: ['https://unpkg.com/leaflet@1.6.0/dist/leaflet.js', 'https://cdnjs.cloudflare.com/ajax/libs/d3/5.15.0/d3.min.js', 'https://cdnjs.cloudflare.com/ajax/libs/highcharts/8.0.0/highcharts.js'] #jquery, d3, highcharts, datatables
options: [] #wide, noheader (, nopic)
---

## 1. Kde se koronavirus vzal?

Nový typ koronaviru označovaný jako SARS-CoV-2 se poprvé objevil na začátku loňského prosince v čínské provincii Chu-pej, kde se také nachází jedenáctimilionové město Wu-chan. Virus se na člověka přenesl z divokých zvířat, podobně jako v případě jiných koronavirů. Za zdroj nákazy je označováno wuchanské tržiště, kde se kromě mořských plodů prodává právě divoce žijící zvěř.

Stále ale není jasné, jak přesně se nakazili první lidé. Nalezení takzvaného „pacienta nula“ je přitom pro boj s koronavirem SARS-CoV-2 zcela zásadní – jen díky němu mohou vědci s jistotou říct, jaký byl skutečný zdroj nákazy.

Z analýz DNA nicméně vyplývá, že zdrojem mohli být netopýři, kteří se na trhu prodávali, klíčovou roli při přenosu nákazy na člověka ale mohli sehrát také luskouni – chránění savci, kteří jsou v zemích jako Čína loveni nejen kvůli masu, ale také pro jejich šupiny používané k „léčbě“ nemocí.

„Je téměř jisté, že to skutečně byli luskouni – je tam 99procentní shoda, v případě netopýrů se to pohybuje kolem 90 procent,“ [říká pro iROZHLAS.cz](https://www.irozhlas.cz/zpravy-svet/koronavirus-nezname-cina-wu-chan-priznaky-lecba-epidemie-umrtnost-covid-19_2002240701_eku) epidemiolog a současný náměstek ministra zdravotnictví Roman Prymula. V tom se také liší od předešlých dvou známých případů šíření koronaviru – v případě SARS mohl za epidemii přenos ze šelmy cibetky, u MERS zase přenos z velbloudů.

Od začátku prosince, kdy se objevily první případy, se nákaza dostala i za hranice Číny a od druhé poloviny února už onemocnění hlásí všechny kontinenty kromě Antarktidy. Celkově se tak počet nakažených koronavirem vyšplhal na víc než 80 tisíc nakažených a zhruba tři tisíce mrtvých, drtivá většina pochází z pevninské části Číny. Jak vypadá aktuální situace je vidět zde:

<wide>
<div id="corona_map"></div>
</wide>
<script src="https://data.irozhlas.cz/corona-map/script.js"></script>

## 2. Jaké jsou příznaky a je virus nebezpečný? 

Onemocnění způsobené koronavirem, které nese oficiální název COVID-19, zasahuje sliznice dýchacích cest. Typický je suchý kašel a teplota. Zápal plic, který je nejčastější komplikací, se vyvíjí někdy kolem osmého devátého dne. Jak rychle po nakažení se tyto symptomy projevují, vědci zatím s jistotou nevědí – zjistí to až po podrobnější analýze nemoci.

Podle [Evropského centra](https://www.ecdc.europa.eu/en/novel-coronavirus-china/questions-answers) pro prevenci a kontrolu nemocí se inkubační doba pohybuje mezi dvěma a čtrnácti dny, některé případy nicméně ukázaly, že tato doba může být delší. Na případ 70letého muže, u něhož se příznaky nemoci objevily až po 27 dnech inkubační doby, v druhé polovině února upozornila i [agentura Reuters](https://www.reuters.com/article/us-china-health-incubation/coronavirus-incubation-could-be-as-long-as-27-days-chinese-provincial-government-says-idUSKCN20G06W).

Stejně tak se s jistotou zatím nevíme ani to, jaká je úmrtnost wuchanského koronaviru. Únorová studie čínských vědců ji vypočítala na 2,3 procenta – to je výrazně méně než u předchozích epidemií SARS či MERS, kde se mortalita pohybovala kolem deseti, respektive 30 až 35 procenty. Na konečné stanovení mortality je ale stále brzy.

Světová zdravotnická organizace (WHO) proto varuje před šířením paniky – u drtivé většiny všech nakažených se objevují pouze mírné příznaky nemoci a víc než 30 tisíc lidí se lékařům podařilo vyléčit.

„Pouze u čtyř až pěti procent nakažených se objevily vážné zdravotní potíže a jen dvě procenta lidí bohužel přišla o život. Téměř všichni byli pokročilého věku a už měli podlomené zdraví, trpěli například rakovinou nebo vážnými chronickými chorobami. Nemoc je proto méně děsivá, než se zdá,“ [uvedl](https://www.irozhlas.cz/zpravy-domov/koronavirus-v-cesku-who-srdan-matic-hranice_2002271157_bar) pro Radiožurnál ředitel Světové zdravotnické organizace (WHO) v Česku Srđan Matić.

## 3. Jak se virus přenáší?

Nemoc se šíří poměrně snadno a rychle – nejčastěji kapénkami, tedy vzduchem například při kašli nebo kýchání. „Respirační přenos je přitom ten nejjednodušší a nejhůře kontrolovatelný způsob šíření infekční nákazy,“ upozornil v lednovém rozhovoru pro iROZHLAS.cz vedoucí Ústavu epidemiologie a ochrany veřejného zdraví Lékařské fakulty Ostravské univerzity Rastislav Maďar.

V sobotu čínský oficiální list [The Global Times](https://www.irozhlas.cz/zivotni-styl/zdravi/koronavirus-novinky-prenos-aktualne-cina_2002221442_ako) napsal, že vědci identifikovali nový typ koronaviru v moči pacientů. Virus se tak podle nich přesouvá krví k orgánům a mnohé může poškodit. Jeho přítomnost v moči také znamená, že se dostane do kanalizace.

Největší otázkou však zůstává, zda k přenosu SARS-CoV-2 stačí dotyk s předmětem, na němž se virus zachytil. Podle náměstka ministra zdravotnictví Romana Prymuly jsou ale takové poznatky zatím spíš teoretické: „Například prostřednictvím zásilek k žádné nákaze nedošlo. Proto považuji tuto informaci o přenosu dotykem pouze za teoretickou – nemyslím si, že by reálně došlo k nákaze prostřednictvím styku s předmětem po několika dnech přenosu.“

Začátkem února také čínské úřady potvrdily možnost přenosu z matky na dítě během těhotenství nebo při porodu.

## 4. Jak se před virem chránit?

Jak uvádí doporučení ministerstva zdravotnictví, zcela zásadní je chovat se jako při klasickém respiračním onemocnění včetně chřipky. To znamená: vyhýbat se těm, kdo jsou zjevně nemocní; dodržovat základní hygienická pravidla; používat například i dezinfekci, pokud jsme v kontaktu s nakaženými, a nezdržovat se v místech s vyšším počtem lidí.

Lidé, kteří trpí respiračním onemocněním, by měli dodržovat pravidla respirační hygieny – při kýchání a kašlání řádně užívat, nejlépe jednorázové, kapesníky, při kašlání a kýchání si zakrývat ústa paží nebo rukávem, nikoliv rukou, protože kapénky se pak mohou přenést dál.

Víc chránit by se samozřejmě měli i sami zdravotníci, protože právě oni přicházejí s pacienty nejvíce do styku. To zřejmě přispělo také ke zhoršení situace v Itálii, která se stala nejhůře zasaženou zemí v Evropě.

<img class="embed" src="https://www.irozhlas.cz/sites/default/files/styles/zpravy_clanek_telo_4_3/public/uploader/italie_koronavirus_200224-131448_onz.JPG?itok=YgVSriH4" width="100%">

„V případě Itálie se ukázalo, že personál nemocnice nezavedl dostatečná opatření pro kontrolu šíření infekce, zdravotníci se tak stali jedněmi z těch, kteří přenesli koronavirus z jednoho pacienta na druhého. Právě proto je epidemie v Itálii tak velká,“ upozornil šéf WHO v Česku.

## 5. Jaká je léčba?

Ani očkování, ani léčba přímo proti tomuto viru zatím neexistuje. Světová zdravotnická organizace ale uklidňuje, že se dá léčit množství symptomů této nemoci. Léčba je vždy individuální a vychází z konkrétních pacientových potřeb. V těžkých případech pomáhají pacientům s dýcháním či okysličováním krve přístroje, aby se zmírnila námaha plic a srdce.

„U každého člověka, který má problémy s dechem, lze zvážit podpůrnou léčbu za pomoci kyslíku a při zhoršení potíží například umělé plicní ventilace. Tyto postupy jsou používány také v případě chřipky, pneumokokových infekcí a jiných respiračních onemocnění. Nejde tedy o nic specifického, léčba vychází primárně z aktuálního klinického stavu nemocného,“ popsal pro iROZHLAS.cz přednosta Ústavu epidemiologie Lékařské fakulty v Plzni Petr Pazdiora.

Běžná antivirotika nejsou v boji proti viru SARS-CoV-2 účinná, od konce ledna nicméně čínští vědci zkouší pacienty léčit za pomoci přípravků, které se často užívají proti HIV a AIDS – pacientům ve třech vybraných nemocnicích podávají lopinavir a ritonavir, které spadají pod antivirotika.

Jako nejlepší kandidát pro léčbu wuchanského koronaviru se podle WHO nicméně jeví lék zvaný remdesivir, který před několika lety vyvinul tým vědců kalifornské firmy Gilead Sciences, v jehož čele stojí Čech Tomáš Cihlář. Látku lékaři už krátce zkoušeli na pacientech nakažených krvácivou horečkou ebola v Kongu, kde ale testy následně zastavily. Podle studií citovaných Světovou zdravotnickou organizací nicméně remdesivir zabíral také na nemoci SARS a MERS, jež jsou způsobeny příbuzným typem koronaviru.

V současné době je tato látka v Číně klinicky testována. „Léčebný postup je takový, že pacienti dostávají jednou za den infúzi, která trvá třicet minut. Léčba potrvá celkem deset dní a doufáme, že během té doby poznáme, jaký vliv má na průběh nemoci,“ [popsal](https://www.irozhlas.cz/zpravy-domov/koronavirus-lek-biochemik-tomas-cihlar-rozhovor-uspech-zaver-vyvoj_2002182225_tzr) pro Český rozhlas Plus Tomáš Cihlář, jak testy probíhají.

<img width="100%" src="https://www.irozhlas.cz/sites/default/files/styles/zpravy_clanek_telo_4_3/public/uploader/2020-02-26t061728z_1_200226-085910_pj.JPG?itok=_MUTJ-tA">

## 6. Lze se nakazit podruhé?

Ukazuje se, že se k opakované nákaze může dojít. Jeden z případů, kdy se nákaza objevila u pacienta podruhé, kromě Číny zaznamenalo koncem února také Japonsko – šlo o ženu z Ósaky, která pracuje jako průvodkyně. Čtyřicátnice měla podle ósackých úřadů poprvé pozitivní test na konci ledna, z nemocnice byla po vyléčení propuštěna 1. února.

Podle Prymuly jde ale o „raritní“ záležitost. „Domnívám se, že po prodělání tohoto onemocnění by vůči němu měli mít vyléčení imunitu. Pokud by se člověk měl opakovaně nakazit, bylo by to poměrně raritní,“ uvedl pro iROZHLAS.cz.

## 7. Kdy bude epidemie kulminovat?

Původní odhady čínských vědců hovořily o tom, že by epidemie mohla být u konce v druhé polovině března, kvůli šíření koronaviru mimo čínské hranice jsou ale odborníci skeptičtí. Zatímco v Číně nárůst počtu nových případů od poloviny února klesá, v řadě ostatních zemích se situace zhoršuje – úterý 25. února se stalo dokonce prvním dnem, kdy počet nových případů hlášených mimo Čínu přesáhl počet nově infikovaných v nejlidnatější zemi světa.

„To, co je pro nás v tuto chvíli důležitější, je, jak se vyvíjí svět, a tady bohužel dochází k zhoršování téměř exponenciálnímu mimo pevninskou Čínu, to znamená, že epidemie je stále na vzestupu,“ podotýká Prymula.

<wide>
<div id="corona_count"></div>
</wide>
<script src="https://data.irozhlas.cz/corona-map/pocitadlo.js"></script>

Za současné situace je tak podle odborníků jedinou možnou cestou, jak se snažit zkrotit epidemii, identifikovat jednotlivé případy nákazy, izolovat je a vysledovat, s kým přišli do kontaktu. Za pomoci těchto opatření a dodržování základních hygienických pravidel se přitom podařilo zastavit i šíření v minulosti.

„Předchozí dva koronaviry – SARS a MERS – se dostaly pod kontrolu za pomoci individuálních opatření. Ne díky vakcíně nebo antivirotikům, ale mytím rukou, obličejovými maskami, izolací a podobně. Nejsou to špičkové, ani zvlášť sexy technologie, jsou ale naprostým základem,“ upozornil koncem ledna pro server [USA Today](https://eu.usatoday.com/story/news/nation/2020/01/25/china-coronavirus-how-do-you-treat-wuhan-coronavirus/4563385002/) ředitel prestižní kliniky Mayo Greg Poland.

Například u SARS byl výskyt poprvé hlášen 16. listopadu 2002 z čínské provincie Kuang-tung, odkud se nákaza rozšířila do více než 30 zemí. Za pomoci protiepidemických opatření se nicméně v polovině roku 2003 podařilo šíření infekce zastavit.

## 8. Bude virus mutovat?

Obavy vyvolává i možná mutace koronaviru, která je podle Rastislava Maďara nebezpečná hned z několika hledisek – nejenže by zmutovaný virus mohl způsobovat větší poškození lidského organismu, zároveň by se podle něj mohl lépe adaptovat a tím pádem být ještě infekčnější. „Druhá věc je pak ta, že může vzniknout nový klon, který bude více rezistentní vůči léčbě,“ dodává Maďar.
Jestli ale bude SARS-CoV-2 skutečně mutovat, se odborníci zdráhají odhadovat. Vyloučit to ale nelze.

„Mutace jsou přirozenou aktivitou virů – je to jejich obranyschopnost před našimi systémy, kterými se je snažíme dostat pod kontrolu. Mutace tedy určitě může nastat a čím vyšší kumulace viru v populaci viru bude, tím větší je riziko, že vznikne mutace, která bude životaschopná a která může způsobit větší problém,“ vysvětluje Prymula.

## 9. V jakém stadiu je vývoj vakcíny?

Vakcíny se zatím vyvíjejí, podle odborníků to ale nebude dřív než za několik měsíců, vytvoření vhodné vakcíny by ale mohlo trvat i rok.

Například americká farmaceutická společnost Moderna už nicméně oznámila, že poslala na testování první možnou vakcínu proti novému koronaviru. Očkovací látku s názvem mRNA-1273 bude na pacientech zkoušet americký Národní institut alergií a infekčních chorob. První výsledky budou známy nejdříve v červenci.
