## Oplæg til kodning af genforandringer

### Mutation, amplifikation, metylering

Intervallet FE13A# til FE1ZZ# er tilrådighed for genforandringer, hvor de 5 første karakterer er unikke for et specifikt gen, f.eks. FE13C# = EGFR.

Betydningen af 6. karakter #:

```
0. mutation ikke påvist
1. genstatus normal
2. geninsertion
3. gen muteret
4. gendeletion
5. genamplifikation
6. genstatus borderline
7. gen metyleret
8. gen ikke metyleret
9. genændring uden kendt behandlingskonsekvens

A. translokation påvist
B. translokation ikke påvist
C. rearrangement påvist
D. rearrangement ikke påvist
```

For at kunne præcisere hvor genforandringen er lokaliseret, kan FE-koden kombineres med en ny kode som følger:

**Der indføres en ny G-akse:**

GXXYYY, hvor XX er et specifikt gen, f.eks. KRAS; X kan være både bogstaver og tal YYY er kodon-nummeret

Hvis første Y erstattes med e, GXXeYY, betegner YY exon-nummeret.

Teksten på G-aksens koder er ”gennavn kodon nummer abnorm”, f.eks. KRAS kodon 61 abnorm eller c-kit exon 11 abnorm. Dvs. hvis c-kit har fået tildelt X=34 i G-aksen, kodes en c-kit deletion i exon 11:

```
FE13G4  c-kit gendeletion

G34E11  c-kit exon 11 abnorm
```

### Translokationer

**Der indføres en ny J-akse:**

JXXYY0/1, hvor 5. ciffer 0=ikke påvist, 1=påvist

XX er første gen (eller kromosom) og YY er andet gen (eller kromosom)

Hvis XX og YY er tal, er der tale om kromosomnummer; 0X= X-kromosom og 0Y=Y-kromosom

Hvis XX og YY er bogstaver, er der tale om gener; gener tildeles et specifikt bogstavpar

