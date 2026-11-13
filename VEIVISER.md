# Dokumenter om politiet – veiviser

Denne basen har offentlige dokumenter om politiet og forvaltningen rundt politiet: Politidirektoratet, politidistriktene og særorganene, Politiets sikkerhetstjeneste (PST), Spesialenheten for politisaker, påtalemyndigheten med Riksadvokaten og tilgrensende deler av justissektoren. Basen har utvalgte NOU-er, stortingsmeldinger, lovproposisjoner, strategier og handlingsplaner, og tildelingsbrev fra 2020 til Politiet (Politidirektoratet), Politiets sikkerhetstjeneste, Spesialenheten for politisaker og Riksadvokaten. Dokumentene er hentet fra Kudos (kudos.dfo.no), DFØs åpne arkiv over statlige dokumenter. Lov og forskrift ligger ikke her.

## Slik henter du filer

Alle stier er relative til rotadressen:

```
https://raw.githubusercontent.com/Offallnor/offdocspol/main/
```

Hent med `curl -sL <adresse>` eller med hentverktøyet ditt. Hent bare filene du trenger. Mange dokumenter er store (en NOU kan ha over 100 000 ord). Bruk lista nedenfor og `dokumenter.tsv` til å finne riktig fil. Dokumenter på over 100 000 tegn er delt i deler på høyst om lag 75 000 tegn, se under.

## Hva filene inneholder

Hvert dokument har én fil: `dokumenter/<mappe>/<år>/<id>-<tittel>.md`. Er dokumentet stort, har fila bare toppen med lenker og en innholdsfortegnelse, og teksten ligger i en mappe med samme navn: `dokumenter/<mappe>/<år>/<id>-<tittel>/del-01.md`, `del-02.md` og så videre. Innholdsfortegnelsen viser hvilke kapitler (Word-tekst) eller sider og kapitler (PDF-tekst) hver del har, og hele stien til delen. Åpne hovedfila først og så bare delen eller delene du trenger. I PDF-tekst er kapitlene i innholdsfortegnelsen funnet automatisk og kan mangle; sidetallene er sikre. Hver del har lenkene og linja **Tekst** øverst, så sidelenker og varsel om tabeller kan hentes fra delen alene. Tildelingsbrev ligger under budsjettåret de gjelder (året i tittelen), også når de ble publisert året før. Andre dokumenter ligger under året de ble publisert. Øverst i hver fil står tittel, type, publiseringsdato, eier, mottaker og lenker:

- **Les hele dokumentet**: dokumentets side på regjeringen.no (eller institusjonens nettside). Gi brukeren denne lenken når du viser til dokumentet.
- **Original-PDF**: PDF-en dokumentet er hentet fra.
- **Kudos**: dokumentets side i Kudos. Noen tildelingsbrev har bare denne lenken.

Teksten fra PDF-en har et merke, `[Side N]`, der hver side begynner. Lenken til PDF-en med `#page=N` bak åpner riktig side. Teksten er hentet automatisk fra PDF-en. Løpende tekst blir som regel riktig, men tabeller og figurer blir ofte oppløst: tallene havner på egne linjer og kan bli skilt fra radene og kolonnene de hørte til. Av figurene blir som regel bare akseverdier og etiketter igjen. Linja **Tekst** øverst i hver fil sier om det er tegn til dette (antall tabell- og figurtitler og linjer med løsrevne tall). Kolonnene `tabeller`, `figurer` og `tall_linjer` i `dokumenter.tsv` har de samme tallene. Kontroller tall mot originalen før de brukes i noe som skal ut. For noen dokumenter er PDF-teksten byttet ut med tekst fra Word, epub eller HTML. Da står det i linja **Tekst**, og tabellene er med som tabeller.

`dokumenter.tsv` har én rad per dokument: id, type, år, tittel, sammendrag (fra Kudos), eiere, mottakere, utførere, fil og lenker. Bruk den til å søke på tvers, for eksempel alle tildelingsbrev til én mottaker.

## Kjente feller

- **Utredninger, meldinger og proposisjoner er ikke vedtak.** En NOU er et utvalgs forslag. En melding til Stortinget er regjeringens politikk på det tidspunktet. En lovproposisjon er regjeringens lovforslag og er en del av forarbeidene: Stortinget kan ha endret forslaget, så sjekk gjeldende lovtekst på lovdata.no. Si hvilken type dokument svaret bygger på, og at forslagene kan være endret eller forkastet.
- **Tildelingsbrev kommer i flere deler.** Det første brevet for et år følges ofte av tillegg («Supplerende tildelingsbrev», «Tillegg nr. 3»). Et oppdrag eller en bevilgning kan være endret i et senere tillegg. Se alle brevene for samme mottaker og år før du svarer.
- **Politidistriktene og særorganene har ikke egne tildelingsbrev fra departementet.** Politidirektoratet fordeler midlene videre. Spør brukeren om politidistrikter, Kripos, Politihøgskolen eller Politiets IKT-tjenester, finn svaret i brevet til Politidirektoratet, og si at direktoratets egne disponeringsskriv ikke er med.
- **Utvalget er ikke fullstendig.** Basen har et utvalg NOU-er, meldinger, proposisjoner og strategier, ikke alle. Finner du ikke et dokument, si at det ikke er i dokumentbasen, og tilby å finne det og lese det, se regel 5 i `CLAUDE.md`.

## Dokumenter i basen

<!-- AUTO-START: lages av verktoy/kudos_hent.py, rediger ikke for hånd -->

### NOU (12)

| År | Tittel | Innhold | Fil |
|---|---|---|---|
| 2026 | NOU 2026: 8 | NOUen vurderer samarbeid og informasjonsdeling i kriminalitetsforebyggende arbeid med særlig fokus på kriminalitet begått av barn og unge, vold og overgrep i nære relasjoner og voldelig ekstremisme. Den analyserer gjelde | `dokumenter/nou/2026/cb093a85-nou-2026-8.md` |
| 2026 | NOU 2026: 3 | Regjeringen oppnevnte 10. februar 2023 et uavhengig utvalg for å granske straffesaken mot Viggo Kristiansen i Baneheia-saken og foreta en særskilt gjennomgang av Kommisjonen for gjenopptakelse av straffesaker (Gjenopptak | `dokumenter/nou/2026/9cee8194-nou-2026-3.md` |
| 2024 | NOU 2024: 5 | Utvalget for utredning om identitetsskjerming for ansatte i politiet og kriminalomsorgen (ID-skjermingsutvalget) ble oppnevnt av Justis- og beredskapsdepartementet 23. februar 2023. Bakgrunnen for oppnevningen var Storti | `dokumenter/nou/2024/8c4f35af-nou-2024-5.md` |
| 2024 | NOU 2024: 4 |  | `dokumenter/nou/2024/bde1dd67-nou-2024-4.md` |
| 2024 | NOU 2024: 24 | Regjeringen oppnevnte 10. februar 2023 et uavhengig utvalg for å granske straffesaken mot Viggo Kristiansen i Baneheia-saken og foreta en særskilt gjennomgang av Kommisjonen for gjenopptakelse av straffesaker (Gjenopptak | `dokumenter/nou/2024/55111135-nou-2024-24.md` |
| 2024 | NOU 2024: 12 |  | `dokumenter/nou/2024/51c0ce0a-nou-2024-12.md` |
| 2022 | NOU 2022: 15 | Utleverings- og arrestordreutvalget foreslår en ny lov om utlevering og overlevering til og fra Norge (utleverings- og arrestordreloven). Loven er ment å erstatte reglene i utleveringsloven fra 1975 om utlevering av lovb | `dokumenter/nou/2022/49d91474-nou-2022-15.md` |
| 2020 | NOU 2020: 17 | Partnerdrapsutvalget ble oppnevnt for å gjennomgå saker om drap der gjerningspersonen er daværende eller tidligere partner, og å gi anbefalinger som kan bidra til å forebygge slike drap i fremtiden. Utvalget har gjennomg | `dokumenter/nou/2020/9dfffdcf-nou-2020-17.md` |
| 2017 | NOU 2017: 9 | Utvalget har vurdert dagens bevæpningsordning for norsk politi og hvorvidt denne bør endres. Utvalget har sett hen til samfunns- og kriminalitetsutviklingen, endringer i trusselbildet, bevæpningsordninger i andre land og | `dokumenter/nou/2017/8bd6d95e-nou-2017-9.md` |
| 2017 | NOU 2017: 5 | Påtaleanalyseutvalget ble oppnevnt ved kongelig resolusjon 4. mars 2016. Utvalgets oppdrag har vært å gjennomføre en analyse som kan danne grunnlag for en videreutvikling og kvalitetsreform i påtalemyndigheten. Perspekti | `dokumenter/nou/2017/c209b959-nou-2017-5.md` |
| 2017 | NOU 2017: 11 | Utvalget har vurdert behov for endringer i oppgaver og organisering av politiets særorganer og nasjonale beredskapsressurser. I lys av nærpolitireformen anbefaler utvalget at oppgaver og ansvar som utgangspunkt bør legge | `dokumenter/nou/2017/868f644b-nou-2017-11.md` |
| 2016 | NOU 2016: 24 | Straffeprosessutvalgets forslag til ny straffeprosesslov. | `dokumenter/nou/2016/1182afc0-nou-2016-24.md` |

### Melding til Stortinget (7)

| År | Tittel | Innhold | Fil |
|---|---|---|---|
| 2025 | Meld. St. 31 (2024–2025) | Hovedmålene for meldingen er at straffegjennomføringen i Norge skal ha et meningsfullt og forsvarlig innhold som virker kriminalitetsforebyggende, at bemanningen og arbeidsforholdene for de ansatte i kriminalomsorgen ska | `dokumenter/meldinger/2025/bc93f177-meld-st-31-20242025.md` |
| 2024 | Meld. St. 15 (2023–2024) | Stortingsmeldingen «Felles verdier – felles ansvar» legger grunnlaget for en styrket innsats når det gjelder forebygging og bekjempelse av økonomisk kriminalitet. Viktige formål med stortingsmeldingen er å bedre myndighe | `dokumenter/meldinger/2024/9b948c41-meld-st-15-20232024.md` |
| 2022 | Meld. St. 9 (2022–2023) | I stortingsmeldingen om nasjonal kontroll og digital motstandskraft redegjør regjeringen for behovet for en helhetlig og langsiktig tilnærming til nasjonal sikkerhet i hele samfunnet. Meldingen gir en strategisk retning  | `dokumenter/meldinger/2022/cca07c40-meld-st-9-20222023.md` |
| 2021 | Meld. St. 34 (2020–2021) | Stortingsmeldingen beskriver status, utvikling og utfordringer når det gjelder barne-, ungdoms- og gjengkriminaliteten i Norge. Regjeringens politikk er forebygging gjennom tidlig og samordnet innsats på tvers av sektore | `dokumenter/meldinger/2021/58234aca-meld-st-34-20202021.md` |
| 2020 | Meld. St. 5 (2020–2021) | Å sørge for innbyggernes sikkerhet er en av statens viktigste oppgaver. Stortingsmeldingen Samfunnssikkerhet i en usikker verden presenterer regjeringens politikk på samfunnssikkerhetsfeltet de neste fire årene. I meldin | `dokumenter/meldinger/2020/9a10f2b6-meld-st-5-20202021.md` |
| 2020 | Meld. St. 29 (2019–2020) | Politimeldingen – et politi for fremtiden beskriver et endret kriminalitetsbilde, og de utfordringer og behov for endringer det medfører. Meldingen beskriver politiets situasjon i dag og utviklingen av beredskapsevnen et | `dokumenter/meldinger/2020/8c4fec6a-meld-st-29-20192020.md` |
| 2015 | Meld. St. 13 (2015–2016) | Denne meldingen er en oppfølging av Stortingets anmodningsvedtak i forbindelse med behandlingen av Prop. 61 LS (2014–2015) om nærpolitireformen – om å «legge frem en sak med forslag om nasjonal kriseledelse, og klargjøre | `dokumenter/meldinger/2015/955db487-meld-st-13-20152016.md` |

### Strategi/plan (21)

| År | Tittel | Innhold | Fil |
|---|---|---|---|
| 2026 | Politiets virksomhetsstrategi 2026–2030 | Denne virksomhetsstrategien beskriver hvordan politiet skal utvikle evner og prioriteringer for å løse samfunnsoppdraget i perioden 2026–2030. Den setter ambisjoner om å være i forkant, beredt og endringsdyktig, og prese | `dokumenter/strategier/2026/d9d440fb-politiets-virksomhetsstrategi-20262030.md` |
| 2026 | Nasjonal strategi for helhetlig grenseforvaltning | Denne nasjonale strategien fastsetter mål og prioriteringer for helhetlig grenseforvaltning (Integrated Border Management) i Norge. Strategien skal sikre effektiv forvaltning av grensepasseringer, beskytte ytre grenser o | `dokumenter/strategier/2026/45839363-nasjonal-strategi-for-helhetlig-grenseforvaltning.md` |
| 2025 | Plan for en styrket påtalemyndighet og bedre etterforskning | Regjeringen legger frem en plan som beskriver tiltak for å styrke påtalemyndigheten og forbedre etterforskning i politiet, med særlig fokus på kompetanseheving, teknologiske krav og økt kapasitet. Planens tiltak har som  | `dokumenter/strategier/2025/b0e8f1ee-plan-for-en-styrket-patalemyndighet-og-bedre-etterforskning.md` |
| 2025 | Nasjonal strategi mot menneskehandel (2025-2030) | Regjeringen styrker innsatsen mot menneskehandel gjennom en ny, nasjonal strategi. Fem departementer står bak 18 tiltak som skal gjennomføres fra 2025-2030. | `dokumenter/strategier/2025/6b7cf929-nasjonal-strategi-mot-menneskehandel-2025-2030.md` |
| 2024 | Rettssikkerhetsløftet | Målet med rettssikkerhetsløftet er å sikre trygghet, rettssikkerhet og tilgjengelige tjenester for folk, og legge til rette for arbeidsplasser og juridiske fagmiljøer i hele landet. | `dokumenter/strategier/2024/a6aaad6c-rettssikkerhetsloftet.md` |
| 2024 | Handlingsplan mot radikalisering og voldelig ekstremisme | Handlingsplan mot radikalisering og voldelig ekstremisme ble lansert i 2014. Den ble sist revidert i 2020, og forrige statusrapportering ble publisert sommeren 2021. Høsten 2023 gjennomførte Justis- og beredskapsdepartem | `dokumenter/strategier/2024/d608d671-handlingsplan-mot-radikalisering-og-voldelig-ekstremisme.md` |
| 2024 | Handlingsplan for trygg digital oppvekst | Barn skal ha de samme rettigheter i digitale rom som de har på andre arenaer i samfunnet, og det er statens ansvar å sette barnerettigheter ut i livet. Artikkel 4 i FNs barnekonvensjon1 slår fast at partene som har ratif | `dokumenter/strategier/2024/684800c7-handlingsplan-for-trygg-digital-oppvekst.md` |
| 2023 | Trygghet i hverdagen | Regjeringen ønsker levende og trygge lokalsamfunn og tilgjengelige tjenester for folk uansett hvor de bor. Da må vi ha politi, tjenester og arbeidsplasser over hele landet. Denne handlingsplanen følger opp regjeringens p | `dokumenter/strategier/2023/4033822e-trygghet-i-hverdagen.md` |
| 2022 | Revidering av nasjonal kontraterrorstrategi | Strategien danner grunnlaget for en samlet innsats på tvers av alle relevante sektorer, for å forebygge radikalisering og hindre terror - slik at vi kan leve frie liv i et trygt samfunn. | `dokumenter/strategier/2022/022f25af-revidering-av-nasjonal-kontraterrorstrategi.md` |
| 2022 | Mangfold, dialog og tillit - Handlingsplan for politiets arbeid (2022 - 2025) | Politiets handlingsplan for mangfold, dialog og tillit | `dokumenter/strategier/2022/8669cbaa-mangfold-dialog-og-tillit-handlingsplan-for-politiets-arbeid.md` |
| 2021 | Strategi mot arbeidslivskriminalitet (2021–) | Den reviderte strategien mot arbeidslivskriminalitet ble lagt fram i regjeringens kontaktutvalg med partene i arbeidslivet 8. februar. | `dokumenter/strategier/2021/c1e64549-strategi-mot-arbeidslivskriminalitet-2021.md` |
| 2021 | Nasjonal kontraterrorstrategi | Strategien skal forebygge og motvirke terror, og gir en tydelig ramme for arbeidet med kontraterror de neste årene. | `dokumenter/strategier/2021/7e1c388b-nasjonal-kontraterrorstrategi.md` |
| 2021 | I forkant av kriminaliteten | Forebygging er i kjernen av politiets samfunnsoppdrag. Strategidokumentet gir retning for gjennomføringen frem mot 2025. | `dokumenter/strategier/2021/d8cfc2e4-i-forkant-av-kriminaliteten.md` |
| 2021 | Frihet fra vold | Regjeringens handlingsplan for å forebygge og bekjempe vold i nære relasjoner 2021-2024. Handlingsplanen inneholder 82 tiltak for å styrke innsatsen mot denne kriminaliteten ytterligere. | `dokumenter/strategier/2021/5c548cbf-frihet-fra-vold.md` |
| 2021 | Forebygging og bekjempelse av internettrelaterte overgrep mot barn | Nasjonal strategi for samordnet innsats (2021–2025) (PDF) | `dokumenter/strategier/2021/0d3e42ae-forebygging-og-bekjempelse-av-internettrelaterte-overgrep-mo.md` |
| 2020 | Regjeringens strategi for bekjempelse av hvitvasking, terrorfinansiering og finansiering av spredning av masseødeleggelsesvåpen | Regjeringens andre samlede strategi for bekjempelse av hvitvasking, terrorfinansiering og finansiering av spredning av masseødeleggelsesvåpen. Strategien utgjør en viktig del av regjeringens samlede innsats mot økonomisk | `dokumenter/strategier/2020/73d92a44-regjeringens-strategi-for-bekjempelse-av-hvitvasking-terrorf.md` |
| 2020 | Etterretningsdoktrine for politiet | Etterretning i politiet er i rask utvikling. I 2018 ble sannsynlighetsmatrisen endret slik at den harmonerer med tilsvarende i NATO, internasjonale politiorganisasjoner og PST. I 2020 ble det besluttet en nasjonal strukt | `dokumenter/strategier/2020/80f9cacc-etterretningsdoktrine-for-politiet.md` |
| 2019 | Handlingsplan mot voldtekt 2019–2022 | Regjeringens handlingsplan mot voldtekt fokuserer på målrettet forebyggende innsats, et godt hjelpetilbud etter voldtekt, god faglig oppfølging av fornærmede, god etterforskningskvalitet samt mer kunnskap og kompetanse. | `dokumenter/strategier/2019/bab16896-handlingsplan-mot-voldtekt-20192022.md` |
| 2017 | Redusert tilbakefall til ny kriminalitet | Nasjonal strategi for samordnet tilbakeføring etter gjennomført straff 2017-2021 | `dokumenter/strategier/2017/a775060e-redusert-tilbakefall-til-ny-kriminalitet.md` |
| 2015 | Justis- og beredskapsdepartementets strategi for å bekjempe IKT-kriminalitet | Justis- og beredskapsdepartementets første strategi for å bekjempe IKT-kriminalitet. | `dokumenter/strategier/2015/e054512b-justis-og-beredskapsdepartementets-strategi-for-a-bekjempe-i.md` |
| 2015 | Datakrimstrategien | Rapport fra arbeidsgruppe med forslag til overordnet nasjonal strategi for bekjempelsen av datakriminalitet. | `dokumenter/strategier/2015/7a0757c3-datakrimstrategien.md` |

### Proposisjon til Stortinget (33)

| År | Tittel | Innhold | Fil |
|---|---|---|---|
| 2026 | Prop. 4 L (2026–2027) | Proposisjonen foreslår endringer i straffeprosessloven og tilpasninger til straffeloven som følge av innføringen av en ny hjemmel for selvstendig inndragning. Forslaget legger opp til et nytt kapittel i straffeprosesslov | `dokumenter/proposisjoner/2026/4bef17cd-prop-4-l-20262027.md` |
| 2026 | Prop. 35 L (2025–2026) | Proposisjonen foreslår endringer i politiloven og tvangsfullbyrdelsesloven for å erstatte kjønnsspesifikke begreper som «lensmann» og «politimann» med kjønnsnøytrale betegnelser. Forslaget følger opp Stortingets anmodnin | `dokumenter/proposisjoner/2026/2c0cb23e-prop-35-l-20252026.md` |
| 2025 | Prop. 140 L (2024–2025) | Justis- og beredskapsdepartementet fremmer i proposisjonen forslag til endringer i politiloven § 6 som åpner for at Politidirektoratet kan beslutte at politiet skal være bevæpnet i den daglige tjenesten (generell bevæpni | `dokumenter/proposisjoner/2025/e7aa1b27-prop-140-l-20242025.md` |
| 2025 | Prop. 123 LS (2024–2025) | Justis- og beredskapsdepartementet fremmer i proposisjonen forslag til endringer i grenseloven og utlendingsloven mv. for å gjennomføre den reviderte grenseforordningen i norsk rett. Det bes også om Stortingets samtykke  | `dokumenter/proposisjoner/2025/efcaf8ad-prop-123-ls-20242025.md` |
| 2025 | Prop. 112 L (2024–2025) | Justis- og beredskapsdepartementet fremmer i denne proposisjonen forslag om å samle den strafferettslige reguleringen av befatning med mindre mengder narkotika til egen bruk i en ny straffebestemmelse i legemiddelloven.  | `dokumenter/proposisjoner/2025/08d18c3b-prop-112-l-20242025.md` |
| 2024 | Prop. 45 L (2023–2024) | Justis- og beredskapsdepartementet fremmer i proposisjonen forslag til et nytt ledd i politiloven § 6 som tydeliggjør at barnets beste skal tas i betraktning som et grunnleggende hensyn ved alle politiets handlinger og a | `dokumenter/proposisjoner/2024/3c77366a-prop-45-l-20232024.md` |
| 2024 | Prop. 115 L (2023–2024) | Justis- og beredskapsdepartementet legg med denne proposisjonen fram forslag til endringar i våpenlova som eit ledd i arbeidet med ei ny digital våpenforvalting. | `dokumenter/proposisjoner/2024/2fa70651-prop-115-l-20232024.md` |
| 2023 | Prop. 99 LS (2022–2023) | Proposisjonen inneholder forslag til endringer i våpenloven som åpner for å gjøre unntak fra taushetsplikten i forskrift. Hensikten med lovendringene er å legge til rette for gjennomføring av delegert kommisjonsforordnin | `dokumenter/proposisjoner/2023/599b1220-prop-99-ls-20222023.md` |
| 2023 | Prop. 128 L (2022–2023) | Justis- og beredskapsdepartementet legger i denne proposisjonen frem forslag til endringer i straffeprosessloven mv. for å bedre etterlevelsen av besøksforbud og kontaktforbud. Etter forslaget kan det ilegges elektronisk | `dokumenter/proposisjoner/2023/e6c17fcc-prop-128-l-20222023.md` |
| 2022 | Prop. 31 L (2022–2023) | I proposisjonen foreslås det endringer i politiloven som lovfester Politiets sikkerhetstjenestes oppgave som innenlands etterretningstjeneste, og som tydeliggjør hva denne oppgaven innebærer. I tillegg foreslås det endri | `dokumenter/proposisjoner/2022/82e30ec9-prop-31-l-20222023.md` |
| 2022 | Prop. 137 L (2021–2022) | Proposisjonen inneholder forslag om tydeligere regler om visitasjon, undersøkelser og beslag i forbindelse med politiets registrering av asylsøknader. Det foreslås blant annet regler om for hvilke formål det kan foretas  | `dokumenter/proposisjoner/2022/7767a12f-prop-137-l-20212022.md` |
| 2021 | Prop. 229 L (2020–2021) | Justis- og beredskapsdepartementet foreslår i denne proposisjonen endringer i grenseloven og utlendingsloven for å gjennomføre EUs forordninger om etableringen av et inn- og utreisesystem (EES) og et fremreisesystem (ETI | `dokumenter/proposisjoner/2021/0b54c657-prop-229-l-20202021.md` |
| 2021 | Prop. 190 L (2020–2021) | Justis- og beredskapsdepartementet legger i proposisjonen frem forslag til endringer i straffeprosessloven og straffeloven. Det foreslås en ny bestemmelse i straffeprosessloven som åpner for at retten, etter begjæring fr | `dokumenter/proposisjoner/2021/e126c949-prop-190-l-20202021.md` |
| 2021 | Prop. 152 L (2020–2021) | Proposisjonen inneholder forslag til en ny bestemmelse i politiloven som vil gi ansatte i politiet rett til full erstatning for skader som skyldes pålagt operativ trening. Den foreslåtte erstatningsordningen favner enhve | `dokumenter/proposisjoner/2021/10923ddb-prop-152-l-20202021.md` |
| 2021 | Prop. 146 L (2020–2021) | Proposisjonen inneholder forslag til endringer i straffeprosessloven for å styrke rettssikkerheten og effektiviteten i norsk straffesaksbehandling. Departementet foreslår endringer for å legge bedre til rette for aktiv s | `dokumenter/proposisjoner/2021/453140c0-prop-146-l-20202021.md` |
| 2021 | Prop. 139 L (2020–2021) | Justis- og beredskapsdepartementet foreslår i denne proposisjonen enkelte endringer i politiregisterloven og utlendingsloven. I politiregisterloven foreslås det blant annet å presisere at DNA-profiler kun kan benyttes i  | `dokumenter/proposisjoner/2021/bc0110cd-prop-139-l-20202021.md` |
| 2020 | Prop. 66 L (2019–2020) | I denne proposisjonen foreslår regjeringen en rekke lovforslag i straffeloven, straffeprosessloven og enkelte andre lover. Proposisjonen følger opp syv anmodningsvedtak fra Stortinget og enkelte handlingsplaner. Den følg | `dokumenter/proposisjoner/2020/adeabff8-prop-66-l-20192020.md` |
| 2020 | Prop. 19 L (2020–2021) | Proposisjonen inneholder forslag om enkelte endringer i våpenloven. I forbindelse med arbeidet med ny våpenforskrift har departementet blitt oppmerksom på flere forhold som det er behov for å presisere i våpenloven. Ette | `dokumenter/proposisjoner/2020/cbaa7bb3-prop-19-l-20202021.md` |
| 2019 | Prop. 4 L (2019–2020) | Proposisjonen omhandler endringer i straffeprosessloven og politiregisterloven. Forslaget innebærer at opplysninger fra kommunikasjonskontroll som ikke er brukt i saken, som hovedregel skal sperres ved rettskraftig dom o | `dokumenter/proposisjoner/2019/5f21a2d0-prop-4-l-20192020.md` |
| 2019 | Prop. 142 L (2018–2019) | I denne proposisjonen foreslår regjeringen å lovfeste at påtalemyndigheten er uavhengig. Samtidig foreslås det å oppheve adgangen for Kongen i statsråd til å instruere påtalemyndigheten i enkeltsaker samt den eksklusive  | `dokumenter/proposisjoner/2019/c956b3ac-prop-142-l-20182019.md` |
| 2018 | Prop. 70 L (2017–2018) | Forslaget innebærer at det gis adgang til å fastsette bestemmelser om tidsubegrenset bevæpning ved sårbare objekter, såkalt punktbevæpning | `dokumenter/proposisjoner/2018/bcbd3b28-prop-70-l-20172018.md` |
| 2017 | Prop. 99 L (2016–2017) | Proposisjonen inneholder forslag til endringer i politiregisterloven for å gjennomføre direktiv (EU) 2016/680 om beskyttelse av fysiske personer ved behandling av personopplysninger for å forebygge, etterforske, avdekke  | `dokumenter/proposisjoner/2017/d52bf547-prop-99-l-20162017.md` |
| 2017 | Prop. 61 L (2016–2017) | Proposisjonen omhandler endringer i straffeprosessloven og politiloven for å gi en utvidet adgang til utlevering av opplysninger fra PST til E-tjenesten. Lovforslaget gir PST mulighet til å utlevere opplysninger innhente | `dokumenter/proposisjoner/2017/d15f9a3b-prop-61-l-20162017.md` |
| 2017 | Prop. 165 L (2016–2017) | Justis- og beredskapsdepartementet føreslår ei ny lov om våpen, skytevåpen, våpendelar og ammunisjon (våpenlova). Lovframlegget vil avløyse våpenlova frå 1961 og lovfestar sentrale reglar som i dag er fastsett i forskrif | `dokumenter/proposisjoner/2017/678b09ed-prop-165-l-20162017.md` |
| 2017 | Prop. 161 L (2016–2017) | I proposisjonen foreslår Justis- og beredskapsdepartementet en ny lov om grensetilsyn og grensekontroll av personer (grenseloven). Lovforslaget baserer seg fullt ut på eksisterende ansvarsfordeling og organisering av gre | `dokumenter/proposisjoner/2017/e45325a8-prop-161-l-20162017.md` |
| 2017 | Prop. 156 L (2016–2017) | I proposisjonen foreslås det et rettslig grunnlag for at politiet, etter skriftlig anmodning og uten hinder av taushetsplikt, skal få utlevert opplysninger om navn, fødselsdato og nasjonalitet til nåværende og tidligere  | `dokumenter/proposisjoner/2017/c1570211-prop-156-l-20162017.md` |
| 2017 | Prop. 106 L (2016–2017) | Proposisjonen omhandler endringer i straffeprosessloven § 199 a. Det foreslås at politiet ved ransaking eller beslag av datasystem kan pålegge enhver som har befatning med datasystemet å åpne det ved bruk av biometrisk a | `dokumenter/proposisjoner/2017/dadbeac6-prop-106-l-20162017.md` |
| 2016 | Prop. 68 L (2015–2016) | Proposisjonen omhandler endringer i straffeprosessloven. Det foreslås at politiet gis en utvidet adgang til å benytte skjulte tvangsmidler ved etterforskning, avverging og forebygging av alvorlige lovbrudd. Utvidelsen om | `dokumenter/proposisjoner/2016/fb2c12df-prop-68-l-20152016.md` |
| 2016 | Prop. 60 L (2015–2016) | Endringer i politiloven (utnevning av visepolitimestere på åremål). | `dokumenter/proposisjoner/2016/15ade63a-prop-60-l-20152016.md` |
| 2016 | Prop. 107 L (2015–2016) | Justis- og beredskapsdepartementet foreslår en tydeligere forankring av bestemmelsen om midlertidig bevæpning i våpeninstruks for politiet i lov 4. august 1995 nr. 53 om politiet (politiloven) § 29. Forslaget setter også | `dokumenter/proposisjoner/2016/7ae193ff-prop-107-l-20152016.md` |
| 2015 | Prop. 94 L (2014-2015) | Proposisjonen inneholder forslag til endringer i flere hjemler for utstedelse av politiattest for å tilpasse bestemmelsene til ny straffelov. I tillegg foreslås det nødvendige endringer i politiregisterloven for å tilpas | `dokumenter/proposisjoner/2015/ad26f467-prop-94-l-2014-2015.md` |
| 2015 | Prop. 79 L (2014-2015) | Proposisjonen inneholder forslag til endringer i politiloven. Formålet med lovforslaget er å oppfylle kravet i Grunnloven § 101 tredje ledd om lovhjemmel for bruk av militær makt mot innbyggerne ved Forsvarets bistand ti | `dokumenter/proposisjoner/2015/80c8e711-prop-79-l-2014-2015.md` |
| 2015 | Prop. 61 LS (2014-2015) | Regjeringens forslag til reform av politiet. Forslaget tar for seg politi- og lensmannsetatens struktur, oppgaveportefølje og ansvarsdeling og er samtidig en gjennomgang av ledelse og kultur i politiet. | `dokumenter/proposisjoner/2015/3c0ea855-prop-61-ls-2014-2015.md` |

### Tildelingsbrev (158)

Mappe: `dokumenter/tildelingsbrev/<år>/`. Søk i `dokumenter.tsv` (kolonnen `mottakere`) for å finne brevene til én mottaker. Brev og tillegg per mottaker og budsjettår:

| Mottaker | Brev | År |
|---|---|---|
| Politiet | 93 | 2020 (1), 2021 (20), 2022 (20), 2023 (14), 2024 (14), 2025 (14), 2026 (10) |
| Politiets sikkerhetstjeneste | 22 | 2021 (5), 2022 (5), 2023 (4), 2024 (3), 2025 (4), 2026 (1) |
| Riksadvokaten | 22 | 2021 (4), 2022 (4), 2023 (4), 2024 (5), 2025 (4), 2026 (1) |
| Spesialenheten for politisaker | 21 | 2021 (3), 2022 (4), 2023 (5), 2024 (3), 2025 (3), 2026 (3) |

### Veileder (7)

| År | Tittel | Innhold | Fil |
|---|---|---|---|
| 2025 | Veileder for kommune- og politisamarbeid | Veileder laget av Politidirektoratet i samarbeid med Kommunesektorens organisasjon (KS). Veilederen gir råd og anbefalinger for å styrke samarbeidet mellom politi og kommune. | `dokumenter/veiledere/2025/0218c577-veileder-for-kommune-og-politisamarbeid.md` |
| 2022 | Veileder kriminalitetsforebygging i planprosesser | Veilederen skal bidra til økt kunnskap om politiets rolle og ansvar i planprosesser. | `dokumenter/veiledere/2022/b5740909-veileder-kriminalitetsforebygging-i-planprosesser.md` |
| 2022 | Utenfor boksen - innenfor lovverket : veileder for god informasjonsflyt | Veilederen er utarbeidet for å forbedre informasjonsflyt og samarbeid mellom aktører som jobber med unge som begår gjentatt kriminalitet. Den gir praktiske retningslinjer for å sikre juridisk korrekt deling av informasjo | `dokumenter/veiledere/2022/feea562b-utenfor-boksen-innenfor-lovverket-veileder-for-god-informasj.md` |
| 2021 | Rettleiar ved bekymring for radikalisering og valdeleg ekstremisme |  | `dokumenter/veiledere/2021/33eded48-rettleiar-ved-bekymring-for-radikalisering-og-valdeleg-ekstr.md` |
| 2020 | Delbart? Om ulovlig bildedeling blant ungdommer | Målgruppen for foredraget er barn og unge på mellomtrinnet og ungdomsskolen, samt deres foreldre. Målet er at barn skal få mer kunnskap om konsekvensene av bildedeling. Foredraget kan holdes for alt fra små grupper til s | `dokumenter/veiledere/2020/67e1f7ac-delbart-om-ulovlig-bildedeling-blant-ungdommer.md` |
| 2017 | Veileder for politiets bekymringssamtale | Formålet med denne veilederen er å legge til rette for god rolle- og ansvarsavklaring, gode rutiner og oppfølgingsmuligheter ved bruk av bekymringssamtalen. Veilederen skal også bidra til å videreutvikle... | `dokumenter/veiledere/2017/682302d5-veileder-for-politiets-bekymringssamtale.md` |
| 2016 | Veileder for egenevaluering av politiradets arbeid | Veilederen er et tiltak for å støtte det enkelte politiråd i gjennomføring av en egenevaluering. Det anbefales å gjennomføre evalueringen en gang i året og at dette blir en integrert del av politirådets... | `dokumenter/veiledere/2016/deae85d8-veileder-for-egenevaluering-av-politiradets-arbeid.md` |

### Evaluering (3)

| År | Tittel | Innhold | Fil |
|---|---|---|---|
| 2026 | Evaluering av støttesenter for kriminalitetsutsatte | Rapporten evaluerer støttesentre for kriminalitetsutsatte som ble etablert i politidistriktene i 2017. Den kartlegger organisering, bemanning, oppgaveutførelse og måloppnåelse basert på intervjuer, statistikk og dokument | `dokumenter/evalueringer/2026/145d16ad-evaluering-av-stottesenter-for-kriminalitetsutsatte.md` |
| 2022 | Forebyggende tiltak mot ungdomskriminalitet i Oslo kommune | OsloMet, ved Velferdsforskningsinstituttet NOVA og By- og regionsforsknings- instituttet NIBR har gjennomført en følgeforskning og evaluering av tilskudd gitt av Barne-, ungdoms- og familiedirektoratet (Bufdir) til Oslo  | `dokumenter/evalueringer/2022/17ec4d84-forebyggende-tiltak-mot-ungdomskriminalitet-i-oslo-kommune.md` |
| 2020 | «Omvendt voldsalarm» En evaluering av kontaktforbud med elektronisk kontroll (straffeloven § 57) i saker om vold i nære relasjoner | På oppdrag fra Justis- og beredskapsdepartementet har Velferdsforskningsinstituttet NOVA ved OsloMet – storbyuniversitetet, gjennomført en evaluering av prakti- seringen av straffelovens bestemmelse om kontaktforbud med  | `dokumenter/evalueringer/2020/6608983b-omvendt-voldsalarm-en-evaluering-av-kontaktforbud-med-elektr.md` |

<!-- AUTO-SLUTT -->

## For redaktører

- Hvilke dokumenter som hentes, står i `dokumenter.json`: per Kudos-type en mappe, første år (`fra_ar`), eiere (tom liste betyr alle) og eventuelt `ta_med` (nøyaktige titler) eller `ta_med_start` (titler som begynner slik). Legg til en tittel der, så hentes dokumentet ved neste kjøring. `mottakere` (liste med uttrykk) begrenser en type til dokumenter med en mottaker som passer, slik tildelingsbrevene er begrenset til politiet og etatene rundt.
- Dokumenter på over 100 000 tegn deles automatisk av `verktoy/deling.py` hver gang de lagres, både ved henting fra Kudos og fra innboksen. `python3 -I verktoy/deling.py` deler alle på nytt etter gjeldende regler.
- `verktoy/kudos_hent.py` kjøres hver tirsdag og ved behov (`kudos-hent.yml`), og går rett i main. Lagrede dokumenter hentes ikke på nytt. `--liste <type> --fra <år> --sok <regex>` lister kandidater uten å lagre, og `--liste typer` viser hvilke typer Kudos har. Jobben `kudos-liste.yml` (`verktoy/kudos_liste.py`) gjør det samme med lenker til dokumentside og originalfil, og kan kjøre mens hentingen pågår.
- Bedre tekst for et dokument med rotete tabeller: legg Word-, epub- eller HTML-fila i `innboks/`, se `innboks/README.md`. Jobben `innboks.yml` leser den inn med `verktoy/innboks.py`, og Kudos-hentingen skriver ikke over teksten senere.
- Lista over er laget av skriptet. Rediger teksten utenfor AUTO-blokken.
- Repoet er åpent. Legg ikke inn interne dokumenter, utkast eller svar som ikke er publisert.
