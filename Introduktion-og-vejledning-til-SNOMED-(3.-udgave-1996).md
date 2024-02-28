### Introduktion 

#### EDB-registrering af patologisk-anatomiske data 

Indførelsen af edb-teknik på de patologisk-anatomiske afdelinger har givet en række fordele såvel internt 
som i kommunikationen med andre afdelinger. Der er bl.a. opnået mulighed for at afskaffe de stadig mere 
uoverskuelige manuelle kartoteker, lettere adgang til informationer om tidligere og aktuelle undersøgelser, 
større funktionel sikkerhed omkring behandling og lagring af informationer og bedre mulighed for 
patientopfølgning samt udnyttelse af data i videnskabeligt og administrativt øjemed. I det omfang, de 
patologisk-anatomiske afdelinger indgår i større hospitalsinformationssystemer, skabes der samtidig 
mulighed for hurtig kommunikation mellem afdelingerne. Gennem oprettelse af en fælles database kan 
alle, der er impliceret i et patientforløb, til enhver tid få alle relevante oplysninger om aktuelle og tidligere 
forhold vedrørende patienten Stillet til rådighed. 

I løbet af 1996 anvender næsten alle landets patologisk-anatomiske afdelinger edb. Nogle benytter endnu kun det elektroniske medium som diagnosekartotek, men de fleste udnytter edb til systematisk behandling af alle patientrelaterede data, således at både rekvirering, »journalføring« og besvarelse af en undersøgelse sker ved hjælp af edb. Tillige kan der være tale om automatisk nummertildeling til undersøgelser og materialer, etiketudskrift og kommunikation til andre afdelinger via terminaler eller i netværk. De fleste afdelinger, der anvender edb, er tilsluttet Kommunedatas landsomfattende »røde system« (RS). De øvrige afdelinger er tilsluttet systemer, der alene betjener et enkelt amt eller et enkelt sygehus.
 
Den omsætning af det diagnostiske sprog til et »matematisk sprog«, der muliggøi elektronisk databehandling med uhyre hurtig og nøjagtig opsamling, lagring. ordning og udskrivning af data efter bestemte kriterier, foregår ved hjælp af applicerede numeriske koder. Dette må, uanset kodesystemernes nok så forfinede struktur, af mange opfattes som en triviel fremgangsmåde og en hæmsko for den frie diagnostiske udtryksform. Imidlertid sikres herved den præcisering af det diagnostiske udtryk, der er nødvendig for en entydig kommunikation mellem patologer 
indbyrdes og mellem klinikerne og patologer, nationalt såvel som internationalt. Selv om man kan se frem til, at denne fremgangsmåde vil blive afløst af databehandling, der bygger på onaturaJ languagea, det vil sige at diagnosernes essens »opfattes« i edb-systemet alene på grundlag af det sproglige udtryk, må også sådanne systemer stille krav om præcision i det diagnostiske udtryk. 

Al individbaseret edb-registrering af patologisk-anatomiske data sker i henhold til bestemmelser, der er angivet i Sundhedsstyrelsens rapport nr. 5 , »Registrering af patologisk-anatomiske undersøgelser«, fra 1983, herunder bestemmelse om, at SNOMED skal anvendes til diagnoseregistrering. 

#### Systematized Nomenclature Of Medicine (SNOMED)

SNOMED er et nomenklatur og klassifikationssystem udviklet af College Of American Pathologists og udgivet første gang i 1976 med henblik på edb-behandling af medicinske data. Den amerikanske SNOMED's 2. udgave er fra 1979.1 1993 udkom den 3. udgave betegnet SNOMED International. 

SNOMED indeholder nøjagtige matematiske ækvivalenter til alle sproglige udtryk eller termer inden for det medicinske begrebsunivers, det vil sige. at alle relevante informationer vedrørende den menneskelige organisme, dens normale og patologiske, anatomiske og funktionelle forhold samt procedurer knyttet til diagnostik og behandling, er kodificerede.

##### SNOMED's opbygning 

SNOMED er et multiaksialt system, hvor hver akse indeholder et defineret område af kodificerede 
udsagn. 

Kodenumrene er ASCII-sorteret, d,v.s. at tal kommer før bogstaver (fx g før a) i den alfanumeriske rækkefølge. Koder indeholdende bogstaver er oftest konstrueret senere end de øvrige, og i enkelte tilfælde har det af pladshensyn været nødvendigt at bonse fra den hierarkiske struktur. 

Hver akse er identificeret ved en bogstavbetegnelse, der sættes foran et 5-cifret kodenummer. Følgende 6 SNOMED-akser benyttes i patologisk-anatomisk undersøgelsesregistrenng: 

**Topografi (T)** der omfatter alle anatomiske lokalisationer og strukturer; **morfologi (M)**, der omfatter alle 
strukturelle forandnnger i væv, celler og subcellu]ære enheder; **ætiologi (Æ)**, der omfatter alle kausale 
faktorer knyttet til en sygdom; **funktion (F)** der omfatter alle normale og abnorme funktionelle tilstande og enheder; **sygdom (S)**, der omfatter sygdomme og syndromer; og **procedure (P)**, der omfatter alle administrative, præventive, diagnostiske og terapeutiske handlinger knyttet til sygdom. 

SNOMED er hierarkisk opbygget, således at alle begreber fra de mest overordnede til de mest speci 
fikke er arrangeret i et logisk system, hvor de tilknyttede kodenumres første ciffer udtrykker det mest generelle, mens de efterfølgende cifre udtrykker tiltagende uddifferentiering af begreberne (Fig. 1). Der er således altid mulighed for at finde en kode, der svarer til den grad af specificitet, der, afhængig af kliniske oplysninger, problemstilling, afdelingens art etc. , ønskes udtrykt i diagnosen. 

###### Figur 1: SNOMED'S hierarkiske struktur illustreret ved eksempler fra topografi- og morfologiakserne. 

```
T 40000  Blodkar
T 41000  Arterie
T 43000  Koronararterie
T 43100  Venstre koronararterie
T 43120  Venstre koronararteries ramus circumflexus

M 40000  inflammation		 
M 41000  akut inflammation	 
M 41400  akut suppurativ inflammation
M 41410  akut flegmonøs inflammation
```

Kodificerede udsagn fra hver af akserne kan kombineres efter behov for at give et fuldstændigt ækvivalent udtryk for det, der ønskes registreret. Grundlæggende anvendes altid et topografisk og et morfologisk udsagn, men en diagnose kan i princippet bestå af et vilkårligt antal kodificerede udsagn fra alle akser (Fig. 2). Af praktiske og forståelsesmæssige grunde bør antallet af udsagn dog være begrænset. Kodenumrene er i nogle tilfælde opbygget ikke alene af tal, men også visse bogstaver (a-f, L k, x, y). Bogstaverne er i kodenumrene skrevet med småt (bortset fra L, for at undgå forveksling med 1 (ét)). 

###### Figur 2 Eksempel på diagnose dannet ved kombination af udsagn fra flere akser. 

```
T 74010  Vesica urinaria slimhinde
M 81203  transitiocellulær, papillær tumor
Æ yyy13  grad III
Æ f1830  pT1
P 30619  randombiopsi
```

##### Den Danske SNOMED for Patologi 

Den Danske SNOlvfE.D for Patologi bygger på den amerikanske SNOMED's 2. udgave fra 1979, tilpasset dansk sprogbrug. Nomenklatur og klassifikation følger så vidt muligt den almindelige patologisk-anatomiske nomenklatur (for latinske topografiske termers vedkommende Nomina Anatomica) og gældende klassifikationsprincipper, herunder WHO's tumorklassifikation. Ortografien følger reglerne for dansk medicinsk retskrivning. 

Det har været nødvendigt i løbet af årene at konstruere en række nye koder til dansk formål, således at Den Danske SNOMED for Patologi nu rummer langt de fleste af de termer, der er behov for i dansk patologisk anatomi. Inden for hæmatologisk diagnostik har det været nødvendigt at udarbejde en ny struktur, der bl.a. benytter REAL-klassifikationen som det bærende element inden for lymfomdiagnostik. 

Den Danske SNOMED for Patologi er lagret i Sundhedsstyrelsen, hvorfra ajourførte kodelister på papir eller diskette til enhver tid kan rekvireres. 

#### Historisk kodeliste 

I den tid, Den Danske SNOMED for Patologi har eksisteret, er der løbende sket en tilpasning af terminologien i takt med udviklingen inden for det patologisk-anatomiske fagområde. Med henblik på diagnosesøgning i ældre materialer kan det derfor 
være nødvendigt at råde over en historisk kodeliste. Den kan rekvireres fra Registrerings- og Nomenklaturudvalget. 

#### Kodebogen 

Kodebog for patologisk anatomi udkom første gang i 1983, 2. udgave kom i 1987. I den foreliggende 3. udgave fra 1996 er antallet af termer, der er medtaget i kodebogen, stærkt udvidet. 

Opbygningen af kodebogen er overvejende numerisk, idet SNOMED' s kodenumre for topografi og morfologi danner bogens »rygrad«.

Kodebogen er redigeret af Flemming Lass og Mogens Vyberg. Medlemmerne af Registerings— og Nomenklaturudvalget har i samarbejde med en række af landets patolog-anatomer inden for de respektive interesseområder varetaget tilretningen af de enkelte organ afsnit. 

Peter Holm-Nielsen har gennemset de topografiske udsagn med henblik på overensstemmelsen med Nomina Anatomica. 

#### Registrerings- og nomenklatur- udvalget (RNU) 

RNU blev nedsat af Dansk Selskab for Patologisk Anatomi og Cytologi i 1983 til at vedligeholde Den Danske SNOMED for Patologi og kodebogen samt til at virke som kontaktorgan til Sundhedsstyrelsen i spørgsmål vedrørende registrering af patologisk- 
anatomiske undersøgelser. I takt med nye behov har RNU lagt nye termer og koder i Den Danske SNO- MED for Patologi. 

RNU' s medlemmer er pr. 1/1-96: Beth Bjerregaard, Finn Løve Jepsen, Flemming Lass (fmd.), Niels Tinggaard Pedersen, Hans Svanholm og Mogens Vyberg (sekr.). Ønsker om nye koder kan tilstilles RNU eller Sundhedsstyrelsen. 

---
#### Kodebogens opbygning 
Kodebogen, der er et uddrag af Den Danske SNOMED for Patologi, indeholder kodificerede udsagn ordnet i følgende afsnit: uspecifik topografi og uspecifik morfologi ætiologi og moderatorer; funktion; sygdom; procedurer; organsystemer (systematisk topografi/morfologi); regioner; og cytologi. Bagest i kodebogen er der et henvisningsregister med alfabetisk ordnede ikke-kodificerede termer (synonymer og underbegreber).

Kodebogen indeholder de fleste af de termer, der benyttes i patologisk-anatomisk diagnostik og de dertil svarende koder. Begrebernes sproglige udtryk, som de findes i kodebogen og Den Danske SNOMED for Patologi, er også formet med henblik på, at de skal kunne anvendes direkte i kommunikationen. I kodebogens centrale afsnit, opdelt i organsystemer (systematisk topografihnorfologi), er opstillingen af topografi og morfologi numerisk svarende til SNOMED's numeriske system med koden placeret til venstre for den tilhørende tekst. Visse udsagn, der logisk kan placeres i flere sammenhænge eller som på grund af den klassifikationsmæssige udvikling indgår i anden sammenhæng end den, der afspejler sig i SNOMED's opbygning, kan være medtaget nere steder i afsnittene. I de tilfælde, hvor de listede udsagns kodenumre ikke passer i den numeriske rækkefølge, er kodenumrene anbragt til højre for teksten. 

Hvis en morfologisk forandring ikke kan findes i et bestemt organafsnit, kan den Oftest findes i et andet afsnit, omhandlende et organ som hyppigere er associeret med den pågældende forandring. I nogle tilfælde kan det være nødvendigt at finde termer og tilhørende koder i Den Danske SNOMED for Patologi, der som edb-udskrift eller på diskette bør være tilgængelig på alle patologiafdelinger. 

Synonymer, beslægtede begleber og underbegreber, der ikke er kodificerede, er angivet med petit under de morfologiske udsagn med ét tabulatorstops indrykning, og er yderligere samlet i henvisningsregisteret bagest i bogen. 

I kodebogens afsnit om organsystemer er ætiologi-, funktions- og sygdomsudsagn, der typisk er knyttet til en given morfologi (og er af betydning for den specifikke kodning) placeret under morfologiteksten i petit med to tabulatorstops indrykning af teksten og kodenummeret placeret til højre. 

I nogle tilfælde er der efter et (som regel ikke-kodificeret) udsagn anført »/+«, som henviser til et efterfølgende supplerende udsagn, der bør anvendes for at gøre den kodede diagnose tilstrækkelig specifik (Fig. 3). 

###### Figur 3: Eksempler på kodebogens Struktur med underbegreber og henvisninger. 

```
M 22140 kongenit deviation
	kongenit septum deviation /+
				Septum nasi		T21340

M 76100 fibromatose
	postirradiativ fibromatose /+
				stråleforandring	M11600
```


##### Topografi (T) 
T-aksen er obligatorisk for al patologisk-anatomisk kodning. Kodebogens organsystemafsnit er baseret på topografiaksen i numerisk orden. 

Grundlaget for topografi-registreringen i patologisystemet er især l) patologens identifikation af bestemte vævs- eller organstrukturer, 2) klinikerens oplysning om lokalisation af den patologiske proces, 3) patologens kendskab til mulige udgangspunkter for en given proces, 4) den tradition, der lokalt er udviklet mellem patologer og klinikere med hensyn til diagnoseudformning, 5) patologens ønske om med anvendelse af bestemte topografikoder at udtrykke, ved hvilken (klinisk) procedure materialet er fremkommet. 6) patologens afvejning af ønsket om specifik og detaljeret kodning kontra behovet for et konfattet diagnostisk udsagn, 7) særlige interesser fx i forbindelse med videnskabelige projekter. 

Til én given undersøgelse (rekvisition) kan der knyttes flere T-koder fx i tilfælde af, at 1) der foreligger flere materialer (»prøver«), især hvis de kommer fra flere organer eller fra flere områder i et organ, der ønskes identificeret separat, 2) der i et materiale er forskellige morfologiske forandringer med forskellige lokalisationer, 3) der er behov for at kode topografi på flere niveauer (se »kombination af topografiske udsagn« nedenfor).

I nogle topografikoder er organet/vævet kombineret med en regionsangivelse, fx »T 08200 Lymfeknude på hals« og »T 02120 Hud i ansigt«, men i mange tilfælde må en topografisk region findes i regionsafsnittet sidst i bogen. Kodning for topografisk region kan benyttes som supplement eller alternativ til organ- eller vævstopografi. Fx indeholder udsagnet »T y4600 Retroperitoneum, M 54110 fedtnekrose« flere informationer end »T 1x010 Fedtvæv, M 54110 fedtnekrose«. Visse generelle regler for opbygning af de topografiske koder gør det lettere at huske numrene: Et 1-tal på 4. ciffers plads markerer i mange organer slimhinde, fx »T 68010 Rectumslimhinde«. Et 8-tal på 3. ciffers plads markerer kombination af parrede organer, fx »T 79800 Begge ductus deferentes«. Et 9-tal på 3. ciffers plads markerer kombination af to ikke-parrede organer, fx »T 74900 Vesica urinaria og vagina«. 

##### Morfologi (M) 
Brug af M-aksen er i princippet obligatorisk ved patologisk-anatomisk kodning. M.koden knyttes altid til en foranstående T-kode. En diagnose kan indeholde flere M-koder. I de systematiske organafsnit findes i numerisk orden de morfologiske udsagn og dertil hørende koder, der oftest benyttes i den angivne topografiske sammenhæng. Den overordnede gruppering af morfologiudsagn fremgår af Fig. 4. 

Figur 4: M-aksens overordnede opbygning. 
```
M 0	uspecifik morfologi 
M 1	traumatike forandringer
M 2	kongenitte malformationer, graviditetsprodukter
M 3	mekaniske forandringer
M 4	inflammation og fibrose
M 5	degeneration, nekrose, aflejring, dystrofi, atrofi
M 6	cellulære forandringer
M 7	vækst- og modningsingsændringer
M 8-9	neoplasier
```

Grundlaget for brugen af M-koder afhænger bl.a. af 1) patologens beslutmng om hvilke forandringer, der er mest fremherskende, mest typiske eller mest hensigtsmæssige at medtage i diagnosen, 2) den tradition, der lokalt er udviklet mellem patologer og 
klinikere med hensyn til diagnoseudformning, 3) patologens afvejning af ønsket om specifik og detaljeret diagnostik/kodning kontra behovet for et kortfattet diagnostisk udsagn, 4) særlige interesser fx i forbindelse med videnskabelige projekter, 5) valg af klassifikationssystem for tumorer etc. 

De morfologiske udsagn vil i nogle tilfælde have karakter af en »definitiva diagnose, fx hvis det drejer sig om en cancer. I andre tilfælde er morfologien mere deskriptiv Deskriptive morfologiske terrner kan nogle gange tvangfrit oversættes til en definitiv diagnose, fx T 66000 Appendix + M 41000 akut inflammation = akut appendicitis. Men ofte fremkommer den definitive diagnose først, når der suppleres med koder fra andre akser, fx T 64000 Tyndtarm + M 44200 ikke-nekrotiserende granulomatøs 
inflammation + S 62160 morbus Crohn. 

Til en diagnose anvendes flere M-koder i tilfælde af, at der i et materiale er morfologiske forandringer, hvis natur ikke kan udtrykkes i en enkelt dækkende term. Specielt ved deskriptive M-diagnoser vil der ofte blive benyttet flere M-koder, fx M 41700 akut nekrotiserende inflammation 4 M 45000 inflammation med fibrose. M-aksen bruges også til hjælpekoder - fx M 09000 for lidt materiale til diagnostisk vurdering. 

##### Ætiologi (Æ) 

En liste over samtlige Æ-koder findes i afsnittet »Æ-akse: ætiologi«.

I patologisk anatomi benyttes kodning efter Æ-aksen sædvanligvis, hvor det ætiologiske agens kan påvises histologisk. I nogle tilfælde kan det dog være relevant også at kode et formodet ætiologisk agens som fx virus eller hormon. I organafsnittene er der medtaget relevante Æ-udsagn, placeret i boks og under de M-udsagn, de oftest knytter sig til. 

Æ-aksen benyttes endvidere til moderatorer, se nedenfor. 

##### Funktion (F) 

En liste over samtlige F-koder findes i afsnittet »F-akse: funktion«. 

F-aksen bruges bl.a. til kodning af kvantitative forhold for visse histologisk påviselige emner, fx jern. Det sidste ciffer kan angive forskydninger (fx 3 = forøget niveau, 4 = nedsat niveau, 5 = fravær af, 6 = abnorm forekomst af). 

F-aksen bruges endvidere til at udtrykke forskellige tilstande, fx præmaturitet, graft failure etc. I organafsnittene er medtaget relevante F-koder, sædvanligvis placeret i boks og under de M-koder, de oftest knytter sig til. 

##### Sygdom (S) 

En liste over samtlige S-koder findes i afsnittet »S-akse: sygdom«.

S-aksen, der er SNOMED's sygdomsklassifikation, bruges i patologisk anatomi hyppigst i de tilfælde, hvor diagnosen i væsentlig grad er baseret på andet end det morfologiske billede, fx kliniske informationer, bl.a. fordi de morfologiske forandringer er uspecifikke, eller for at sikre søgemuligheder (Fig. 5). 

###### Figur 5: Eksempler på kodning, der omfatter S-aksen. 
```
T 67000  Colon
M 42100  akut og kronisk inflammation
S 62560  colitis ulcerosa

T 68010  Rectumslimhinde
M 44200  kke-nekrotiserende granulomatos inflammation
M 43030  kronisk ulcerativ inflammation
S 62160  morbus Crohn
```

Udsagn fra S-aksen er placeret i de organafsnit, hvor de naturligt hører til, placeret i boks og så vidt muligt også under de udsagn fra morfologiaksen, som de hyppigst er associeret med. 

##### Procedure (P) 
En liste over samtlige P-koder findes i afsnittet »P-akse: procedure«. 

P-aksen anvendes til at identificere procedurer i forbindelse med en undersøgelse. Det drejer sig dels om udsagn, der angiver undersøgelsesmetoder anvendt på den patologisk-anatomiske afdeling, dels om udsagn, der angiver noget om det undersøgte materiales natur. P-koder bruges på nogle afdelinger kun til at markere specielle procedurer, men hvis kodning af undersøgelsesprocedurer anvendes systematisk, kan registreringen være nyttig til produktionsopgørelser mv. (Fig. 6). 

###### Figur 6. Eksempler på P-koder til brug i mammapatologi.
```
P 30611  ekscisionsiopsi 
P 30620  resektat 
	 - reduktionsplastik
P 306x0  ektomipræparat 
	 - mastektomi
P 306x3  lumpektomi
P 30990  nålebiopsi
P 31002  anden cytologi
	 - cystevæske
	 - mammasekret
	 - areolaskrab
P 31060  finnålsaspirat
P x0000  røntgenundersøgelse
	 - nålemarkering 
```

P-kodeme kan endvidere benyttes til identifikation af undersøgelser, der indgår i projekter eller til at markere konference- eller konsultationstilfælde. Bestemmende for anvendelse af P-koder er bl.a.: 1) hvorvidt der er adgang til i systemet at registrere procedurer, fx materialetype, på en anden, simplere måde, 2) den tradition, der lokalt er udviklet mellem patologer og klinikere med hensyn til diagnoseudformning, 3) patologens ønske om med anvendelse af bestemte P-koder at udtrykke, ved hvilken procedure 
materialet gr fremkommet eller behandlet, 4) patologens afvejning af ønsket om specifik og detaljeret kodning kontra behovet for et kortfattet diagnostisk udsagn, 5) særlige interesser fx i forbindelse med videnskabelige projekter. 

##### Moderatorer 
Moderatorer er udsagn, der modificerer eller udbygger andre udsagn, fx »Æ yyy00 obs. pro« og »Æ yyy21 let grad«. Moderatorkoderne er af tekniske grunde placeret i Æ-aksen i Den Danske SNOMED for Patologi. Moderatorkoden skal stå umiddelbart efter det u&sagn, der skal modereres. Udtryk som »obs. pro« og »let grad« kan alternativt anføres i fri tekst (se nedenfor), men i så fald kan der ikke søges på begreberne.

#### Det diagnostiske udsagn 
Det sproglige udtryk, som man kalder en patologiskanatomisk diagnose, fx »appendicitis acuta«, vil ved en analyse med henblik på det begrebsmæssige indhold normalt rumme mindst ét topografisk og ét morfologisk udsagn. De essentielle topografiske og morfologiske begreber i denne diagnose er appendix og akut inflammation, hvorfor diagnosen i SNOMED kan omskrives til »appendix, akut inflammation«, eller forsynet med koder: »T 66000 Appendix, M 41000 akut inflammation«. 

En diagnose kan også være mere omfattende, og der kan indgå begreber, der ikke er topografiske eller morfologiske. Antallet af koder for hver akse, der kan benyttes til kodningen er altså frit. I nogle tilfælde svarer kodeteksten måske ikke til den almindeligt anvendte terminologi. Fx skal begrebet »iskæmisk colitis« findes i afsnit T 62-69 (esophagus og gastrointestinalkanal) i det morfologiske underafsnit M 5 (degeneration, nekrose, aflejring, atrofi). Her er anført »M 54200 iskæmisk nekrose« med underfor men »iskæmisk enteritis«. Diagnosen kan herefter kodes: »T 67000 Colon, M 54200 iskæmisk nekrose«. Selvom den kodificerede diagnose således ikke indeholder det sproglige udtryk »iskæmisk colitis« eller »iskæmisk enteritis«, er diagnosen alligevel kodet med tilstrækkelig specificitet hvad angår det begrebsmæssige indhold af udsagnet og med mulighed for genfinding. Se endvidere nedenfor under »fri tekst«.

##### Fri tekst 
For at afhjælpe problemet med det ofte noget stereotype og unuancerede sproglige udtryk, der kan blive resultatet af kombination af aksernes kodetekster, er der i de fleste edb-systemer indbygget mulighed for såkaldt fri tekst, som kan uddybe, supplere eller modificere kodeteksten (Fig. 7). 

###### Figur 7: Eksempler på anvendelse af fri tekst. 
```
M 82110  tubulært adenom 
	 - formentlig, se tekst
T y4500  Bughule 
	 - materiale fra 
```

De tekster, der i organafsnittene er anbragt under morfologikodeteksterne med 2 karakterers indrykning, vil ofte være uddybende morfologiske udtryk, herunder synonymer og underbegreber, der med fordel kan benyttes som fri tekst. For at markere, at det drejer sig om fli tekst, kan man fx benytte tankestreg eller parenteser. De frie tekster er ikke kodificerede og kan altså ikke gøres til genstand for en søgning ved hjælp af koder. 

##### Kombination af topografiske udsagn 
En diagnose, som ønskes kodet, kan være: »uterus med cervikalt adenokarcinom«. Heri indgår en overordnet topografi, uterus, og den mere detaljerede, cervix uteri. Kodningen kan følgelig være: »T 82000 Uterus, T 83000 Cervix uteri, M 81403 adenokarcinom«. Den første topografiske term udtrykker, at det er hele uterus, der er fjernet og undersøgt, mens den anden topografiske term knytter sig direkte til den anførte morfologi, altså at karcinomet sidder i cervix. Hvor en given morfologi omfatter nere væv i en region, kan det være rationelt blot at kode regionen og eventuelt tilføje vævene i fri tekst (Fig. 8). 

###### Figur 8: Eksempel på forenklet topografikodning. 
```
T y4300  Bugvæg 
	 - hud, subcutis, tascie, muskulatur 
M 11100 forbrænding 
```

##### Kodning af biopsier og operationsmaterialer 
Det er ofte hensigtsmæssigt at »indbygge« information om det undersøgte materiales art i den kodificerede diagnose. Dette gøres i T-aksen, fx anvendes »T 67700 Colon sigmoideum«, når materialet er resektat, »T 67710 Colon sigmoideum slimhinde«, når materialet er en biopsi. Tilsvarende anvendes »T 82000 Uterus« om et ysterektomimateriale, »T 84000 Endometrium« om materiale fra en abrasio. I nogle tilfælde vil det dog være nødvendigt med en supplerende fri tekst eller procedure (P)-angivelse. 

##### Kodning af neoplasier 
I morfologi-aksens neoplasiafsnit (M8-9) modificeres de morfologiske udsagn ved ændringer af 5. ciffer efter princippet vist i Fig. 9. Et eksempel er vist i Fig. 10. 

###### Figur 9: Princip for modifikation at 5. ciffer neoplasiafsnittet
```
0 = benign 
1 = uvist om benign eller malign, 
2 = carcinoma in situ / inkomplet remission 
3 = malign, primær 
4 = direkte spredning 
6 = malign, metastase 
7 = malign, recidiv 
8 = malign, i remission 
9 = malign, usikkert om primær eller metastase. 
```

De modificerede morfologiske udsagn, hvis kodenummer ender på 4-9, er **ikke** medtaget i kodebogen. 

###### Figur 10: Eksempler på modifikation af 5. Offer i neoplasikodning 
```
M 84709  mucinøst cystadenom 
M 84701  mucinøst cystadenom, borderline 
M 84703  mucinøst cystadenokarcinom

M 98633  kronisk myeloid leukæmi 
M 98637  kronisk myeloid leukæmi, recidiv 
M 98638  kronisk myeloid leukæmi i remission 
```

Hvis man ønsker at angive, at resektionsrandene er frie, kan en kode for frie resektionsrande findes i afsnittet »uspecifik morfologia. Den kodede diagnose kan fx være: »T 68000 Rectum, M 81403 adenokarcinom, M 09400 frie resektionsrande«. Hvis der derimod er tumorinfiltration i resektionsrandene, og dette ønskes kodet, kan T-kode for resektionsrand bruges: »T 68000 Rectum, M 81403 adenokarcinom; T 00100 Resektionsrand, M 81404 adenokarcinom, direkte spredning«. 

Stadier, grader og typer bør angives som kodificerede udsagn i form af moderatorer, jfr. ovenstående, idet anvendelse af fri tekst hindrer søgemuligheder mv. 

##### Kodning af cytologiske undersøgelser 
I cytologiafsnittet i kodebogen findes T-koder for eksfoliativ cytologi. I de tilfælde, hvor der ikke findes en T-kode specielt for cytologisk materiale (fx ved apirationscytologi), anvendes den sædvanlige T-kode for det pågældende organ eller væv. Da der således i sidstnævnte tilfælde ikke i T-koden er »indbygget« information om materialets art, må denne information, hvis det ønskes, kodificeres på anden måde, fx med en P-kode (P 31060 finnålsaspirat) eller udtrykkes i fri tekst.

##### Kodning af hæmatologiske undersøgelser 
Man behøver kun at kode det væv eller den celletype, i hvilken de relevante morfologiske forandringer findes. Hvis alene det myelopoietiske væv i marven er sæde for hyperplasi, er den kodede diagnose »T 06200 Myelopoietisk væv, M 72000 hyperplasi«. Hvis såvel det myelopoietiske som erythropoietiske væv og megakaryocytterne er sæde for hyperplasi, er den kodede diagnose »T 06000 Knoglemarv, M 72000 hyperplasi«. 

Hvis der foreligger en »specifik« morfologisk diagnose på en knoglemarvsundersøgelse, er det normalt unødvandigt samtidig at kode forandringer i det perifere blod, idet vurdering af blodet er en »integreret« del af en knoglemarvsundersøgelse og dermed implicit en del af diagnosegrundlaget. Er forandringerne i marven imidlertid uspecifikke, eller er marven normal, medens der samtidig er forandringer i det perifere blod, kodes disse forandringer. 

Topografikoden afhænger i nogle tilfælde af problemstillingen. Fx kodes knoglemarv med myelomatose: »T 06000 Knoglemarv, M 97303 myelomatose«, mens en tilstand med øget indhold af plasmaceller i marven kodes »T 06750 Marv plasmacelle, M 72000 hyperplasi«. 

I flere edb-systemer er patologerne enedes om et fælles indhold ved registrering af kliniske oplysninger og resultater af differentialtælling ved knoglemarvsundersøgelse. Informationerne kan registreres skematisk i et skærmbillede. 

##### Kodning af autopsier 
Den Danske SNOMED for Patologi er endnu ikke fuldt udbygget, hvad angår kodificeret terminologi til autopsidiagnostisk kodning. Flere afdelinger har akkviesceret ved kun at kode de »vigtigste« diagnoser, herunder dødsårsagerne i en sekvens, der svarer til dødsattestens dødsårsagsrubrikker, se eksempel i Fig. 11. 

###### Figur 11 Eksempel på koftning af dødsårsager.
```
T 32600  Venstre ventrikel 
T 33030  myokardium i bagvæg 
M 54860  transmuralt infarkt 
T 43200  Højre koronararterie 
M 52110  aterosklerose 
M 43100  stenose 
T 41000  Arterie
	 - universelt 
M 52000  arteriosklerose
	 - svær grad
S 23310  diabetes mellitus
```

Kodning af begreber som »operatum sequelae« kræver en omskrivning. Hvis fx patienten tidligere er gastrektomeret for karcinom, kan der kodes »T 63000 Ventrikel, M 18000 følger af kirurgisk indgreb, M 09451 ingen resttumor«. 

##### Temporære koder 
I Danmark fandt man behov for at kodificere en del diagnoser eller termer, der ikke havde fået en kode i den amerikanske SNOMED's 2. udgave. I de fleste tilfælde valgte man at benytte en temporær kode – karakteriseret ved at have »yy« som de to første cifre. DC temporære koder er ikke tilpasset den hierarkiske opbygning. Ved ajourføringen af kodesystemet pr. 1/1-96 er alle yy-koder i Den Danske SNOMED for Patologi tranformeret til blivende koder med hierarkisk korrekt nummer. Ved søgning på undersøgelser registreret før denne dato skal man være opmærksom på, at tidligere stilllede diagnoser beholder deres yy-koder, jfr. Den Danske SNOMED for patologi's historikliste. 

#### Patologisystemet i »Det Røde System« (RS) 
De fleste edb-brugere blandt patologer anvender et patologisystem, der er et modul i RS. De særlige forhold, der skal tages i betragtning i forbindelse med diagnosekodning i RS patologisystemet, hvor selve diagnoseafgivelsen foregår ved h]ælp af Den Danske SNOMED for Patologi' s koder, skal derfor kort gennemgås her. 

##### Sammenkædning af diagnoser og materialer 
Hvis der sammen med en rekvisition er sendt flere materialer og disse som følge heraf får samme mikroskopinurnmer, kan det ofte være nødvendigt at markere en entydig relation mellem diagnoserne og de tilhørende materialer. 

Da der i RS ikke er teknisk mulighed for at angive en tal- eller bogstavmarkering til venstre for diagnoserne, er det nødvendigt at placere disse i den frie tekst i diagnosen. Hvis materialerne (bøtterne) fx er forsynet med romertal og stammer fra flere forskellige steder, placeres romertallene som fri tekst efter topografiudsagnet, se Fig. 12. Hvis der er flere materialer fra samme topografiiske område, men med forskellig morfologi, kan man vælge at placere romertallene enten i forbindelse med topografien eller i forbindelse med morfologierne (Fig. 12). 

###### Figur 12: Eksempler på sammenkædning af materialer og diagnoser ved hjælp af romertal i fri tekst. 
```
T 24400  Stemmebånd
	 - I
M 80703  planocellulært karcinom
T 24010  Epiglottis
	 - II
M 43000  kronisk inflammation
——————————————————————————————————
T 24400  Stemmebånd
	 - I
M 80703  planocellulært karcinom
T 24400  Stemmebånd
	 - II
M 43000  kronisk inflammation
——————————————————————————————————
T 24400  Stemmebånd
M 80703  planocellulært karcinom
	 - I
M 43000  kronisk inflammation
	 - II
```

Af tekniske grunde er det i RS nødvendigt at angive T-kode før hver M-kode, også selv om qer er tale om det samme topografiudsagn. I udskriften undertrykkes imidlertid de gentagne (ens) T-udsagn. Undertrykkelsen sker ikke, hvis der er fri tekst efter T-udsagnet. 

RS' afløser, »det grønne system for patologi«, der ventes færdigudviklet i løbet af 1996, har faciliteter, der løser ovennævnte problemer. 

##### Undladelse af morfologi-kodning 
I nogle tilfælde er der behov for at kunne afgive flere T-koder i rækkefølge uden mellemliggende M -koder, ligesom der kan (undtagelsesvis) være behov for at lade et T-udsagn direkte efterfølges af et Æ-, F- eller S-udsagn. Da en T-kode i patologisystemet altid skal efterfølges af en ,M-kode, er der mulighed for at benytte »M æ0020 se efterfølgende«, idet dette udsagn undertrykkes i svaret (det findes stadig på arbejdsseddelen, »rekvisition 2«). Bemærk, at der også i systemet findes en kode »M 00020 morfologiakse ikke anvendelig«, som ikke undertrykkes. 

##### Undertrykkelse af P-koder 
Da det ofte er overflødigt eller uhensigtsmæssigt i udskriften til rekvirenten at lade diagnosen følge af en angivelse af patologisk-anatomiske procedurer, har man valgt at undertrykke de fleste p-udsagn i forbindelse med diagnoseudskrivningen. Dog fremkommer alle procedureregistreringer ved udskrift af tidligere undersøgelser (arbejdsseddelen, »rekvisition 2«). Hvis man i diagnosen ønsker at give information om en anvendt procedure til den kliniske afdeling, men hvor P-udsagnet undertrykkes, må det ske ved anvendelse af fri tekst. 