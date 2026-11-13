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
<!-- AUTO-SLUTT -->

## For redaktører

- Hvilke dokumenter som hentes, står i `dokumenter.json`: per Kudos-type en mappe, første år (`fra_ar`), eiere (tom liste betyr alle) og eventuelt `ta_med` (nøyaktige titler) eller `ta_med_start` (titler som begynner slik). Legg til en tittel der, så hentes dokumentet ved neste kjøring. `mottakere` (liste med uttrykk) begrenser en type til dokumenter med en mottaker som passer, slik tildelingsbrevene er begrenset til politiet og etatene rundt.
- Dokumenter på over 100 000 tegn deles automatisk av `verktoy/deling.py` hver gang de lagres, både ved henting fra Kudos og fra innboksen. `python3 -I verktoy/deling.py` deler alle på nytt etter gjeldende regler.
- `verktoy/kudos_hent.py` kjøres hver tirsdag og ved behov (`kudos-hent.yml`), og går rett i main. Lagrede dokumenter hentes ikke på nytt. `--liste <type> --fra <år> --sok <regex>` lister kandidater uten å lagre, og `--liste typer` viser hvilke typer Kudos har. Jobben `kudos-liste.yml` (`verktoy/kudos_liste.py`) gjør det samme med lenker til dokumentside og originalfil, og kan kjøre mens hentingen pågår.
- Bedre tekst for et dokument med rotete tabeller: legg Word-, epub- eller HTML-fila i `innboks/`, se `innboks/README.md`. Jobben `innboks.yml` leser den inn med `verktoy/innboks.py`, og Kudos-hentingen skriver ikke over teksten senere.
- Lista over er laget av skriptet. Rediger teksten utenfor AUTO-blokken.
- Repoet er åpent. Legg ikke inn interne dokumenter, utkast eller svar som ikke er publisert.
