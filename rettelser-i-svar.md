# Rettelser i patologibesvarelser (DPAS informatikudvalg)

## Vejledning udarbejdet af DPAS’ Informatikudvalg september 2014.

Det kan være nødvendigt at foretage rettelser (inklusive tilføjelser) i patologibeskrivelser og diagnoser (SNOMED-koder), efter at svaret er sendt til rekvirenten.

Rettelser skal foretages i overensstemmelse med Bekendtgørelse af lov om autorisation af sundhedspersoner og om sundhedsfaglig virksomhed kapitel 6 (LBK nr. 877 af 04/08/2011) https://www.retsinformation.dk/Forms/R0710.aspx?id=138178#K6 (Autorisationsloven) og
Bekendtgørelse om autoriserede sundhedspersoners patientjournaler (journalføring, opbevaring, videregivelse og overdragelse m.v.) (BEK nr. 3 af 02/01/2013) https://www.retsinformation.dk/Forms/R0710.aspx?id=144978 (Journalføringsbekendtgørelsen).

Følgende uddrag af autorisationsloven og journalføringsbekendtgørelsen belyser kravene til rettelser:

## Autorisationsloven
### Rettelse af journaler
§ 24. Oplysninger i patientjournalen må ikke slettes eller gøres ulæselige.

Stk. 2. Sundhedsstyrelsen fastsætter regler om rettelser i patientjournalen.

### Journalføringsbekendtgørelsen
§ 2. Ved en patientjournal forstås optegnelser, som oplyser om patientens tilstand, den planlagte og udførte behandling m.v. herunder hvilken information, der er givet, og hvad patienten på den baggrund har tilkendegivet. Optegnelser, der i øvrigt indeholder oplysninger om rent private forhold og andre fortrolige oplysninger om patienten, er også en del af patientjournalen.

Stk. 2. Omfattet af patientjournalen er sundhedsfaglige erklæringer, diagrammer og hjælpeark, udskrivningsbreve (epikriser), hen- og tilbagevisninger, røntgenbilleder/beskrivelser, kliniske fotos, modeller samt resultatet af undersøgelses- og behandlingsforløb, i det omfang de har betydning for behandling m.v.

Stk. 3. Biologiske præparater er ikke omfattet af patientjournalen.

§ 13. Oplysninger i patientjournalen må ikke slettes eller gøres ulæselige.

Stk. 2. Er det nødvendigt at rette eller tilføje i patientjournalen, skal det ske på en sådan måde, at den oprindelige tekst bevares. Det skal fremgå, hvem der har foretaget rettelsen eller tilføjelsen og hvornår.

Stk. 3. I en elektronisk patientjournal skal den oprindelige version af de oplysninger, der er ændret ved at rette eller tilføje, fortsat være tilgængelig.

Ovenstående tekst tager sigte på journalen med dens indhold af bl.a. undersøgelsesresultater, herunder patologibeskrivelser, naturligvis skal være identiske med de beskrivelser, der findes i patologisystemerne.

Loven og bekendtgørelsen anviser imidlertid ikke konkret, hvordan en patologibesvarelse rettes, og tager ikke højde for en forkert kode, der er indberettet til Patobank og dermed videre til Landsregister for patologi (LRP) samt kliniske databaser m.m., der trækker data fra LRP.

## Informatikudvalget anbefaler følgende fremgangsmåde ved rettelser

### Tekst
Originale beskrivelser og fritekstdiagnoser i teksten skal bevares.

Så vidt muligt lades de urørte, og beskrivelser (makroskopi/mikroskopi/konklusion/fritekstdiagnoser) suppleres med en tekst, der markeres med ”Suppleret d. [dd.mm.åå] af [patologens navn].

Hvis det imidlertid er nødvendigt for at forebygge misforståelser, kan der over den originale beskrivelse indføjes en overskrift, fx ”Oprindelige beskrivelse/diagnose [dd.mm.åå], ikke gyldig /[patologens navn]”, og som overskrift for en efterfølgende ny beskrivelse fx ”Ny beskrivelse/diagnose [dd.mm.åå], erstatter ovenstående, oprindelige beskrivelse /[patologens navn]”.

### Diagnosekoder
Diagnosekoder i form af SNOMED-koder skal bevares, hvis rettelse kan ske på tilfredsstillende måde gennem supplerende diagnosekoder.
Diagnosekoder skal slettes, såfremt de må anses for væsentligt forkerte, fx hvis patienten har fået en malign diagnose, der ikke er grundlag for. Den oprindelige diagnosetekst skal herefter anføres som en fri tekst til den korrigerede diagnose eller i konklusionstfeltet, fx ”Diagnosen ændret [dd.mm.åå] fra [gammel diagnose] /[patologens navn].

Nye patologibesvarelser, der erstatter supplerede eller korrigerede besvarelser, skal tilføjes diagnosen P30701 NYT SVAR, ERSTATTER TIDL FREMSENDTE PÅ DETTE UNDERSØGELSESNR.

Den enkelte patologiafdeling skal sikre, at kodeteksten ”NYT SVAR…” kommer med ud på udskriften til rekvirenten (dvs. at det ikke er en kodetekst, som undertrykkes på svarudskriften), ligesom den enkelte patologiafdeling skal sikre, at den aktuelle rekvirent af den prøve, der foranlediger, at besvarelsen korrigeres, også modtager en korrigeret besvarelse.

Når den rettede besvarelse godkendes i patologisystemet, indberettes den til patologidatabanken, hvorved de kodede diagnoser ajourføres.
