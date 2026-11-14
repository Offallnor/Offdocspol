---
name: "offdocspol"
description: "Offentlige dokumenter og regelverk om politiet og forvaltningen rundt politiet: NOU-er, stortingsmeldinger, lovproposisjoner, strategier, handlingsplaner, veiledere, evalueringer og tildelingsbrev til Politidirektoratet, PST, Spesialenheten og Riksadvokaten. Særlig kriminalitetsforebygging: samarbeid mellom kommune og politi, informasjonsdeling, bekymringssamtale, politiråd, radikalisering og voldelig ekstremisme, barn og unge, vold i nære relasjoner. Også lovene for informasjonsdeling og forebygging: politiloven, politiregisterloven (taushetsplikt i politiet), barnevernsloven og helsepersonelloven. Bruk ved «hva sier NOU-en om…», «hva står i tildelingsbrevet til POD», «hva har regjeringen sagt om forebygging», «finnes det en veileder for…», «kan politiet dele opplysninger med skolen», «når må vi melde til barnevernet», også uten fagord. Last den før du svarer, og svar ikke fra hukommelsen. Også når brukeren spør hva basen inneholder, eller vil oppdatere skillen."
---

# Dokumenter om politiet

**Versjon 2026-11-14.**

Dokumentene og lovene ligger ikke i denne skillen. De ligger i to åpne baser på GitHub og hentes ved hvert oppslag.

## Fremgangsmåte

1. Hent `https://raw.githubusercontent.com/Offallnor/offdocspol/main/CLAUDE.md` med `curl -sL` i kodeverktøyet, eller med hentverktøyet ditt. Følg den.
2. Hent `VEIVISER.md` fra samme sted og finn dokumentet i lista. Åpne bare dokumentet eller delen du trenger.
3. Finnes ikke dokumentet, følg regel 5 i CLAUDE.md.
4. **Gjelder spørsmålet hva loven sier** (for eksempel taushetsplikt, informasjonsdeling, bekymringssamtale, meldeplikt til barnevernet, forvaltningsloven eller personvern), hent `https://raw.githubusercontent.com/Offallnor/offdocs/main/CLAUDE.md` og følg den. Der ligger politiloven med politiinstruksen, politiregisterloven med politiregisterforskriften, barnevernsloven, helsepersonelloven, forvaltningsloven, offentleglova og personopplysningsloven. Svar ikke på lovspørsmål fra hukommelsen. Straffeloven og straffeprosessloven er ikke med: si det, og vis til lovdata.no.

## Ny versjon

Hent `https://raw.githubusercontent.com/Offallnor/offdocspol/main/SKILLVERSJONER.md`. Står det en nyere versjon av `offdocspol` der enn i versjonslinjen over, avslutt svaret med en skillelinje og: «**Ny versjon:** Det finnes en nyere versjon av denne skillen. Si "oppdater skillen" for å få den.» Si det bare én gang i samtalen. Ber brukeren om å oppdatere, hent `https://raw.githubusercontent.com/Offallnor/offdocspol/main/skills/offdocspol/SKILL.md` og vis den som et lagringskort. Feiler hentingen, la det være.

## Hvis hentingen feiler

Svar ikke fra hukommelsen. Ser feilen ut som en sperre (403, «not allowed», «blocked» eller nektet tilkobling), si:

«Jeg fikk ikke hentet dokumentet, fordi Claude ikke har lov til å hente fra nettstedet [nettsted]. Du kan åpne for det selv: Gå til Innstillinger → Funksjoner. Under «Kodekjøring og filoppretting i skyen» skroller du ned til «Tillatelsesliste for domener» og legger til [nettsted]. Spør meg igjen etterpå, gjerne i en ny samtale.»

Ved andre feil: «Jeg fikk ikke hentet dokumentet nå. Prøv igjen litt senere.»

## Feil, mangler og ønsker

Sier brukeren at noe er feil eller mangler, eller ønsker et dokument eller en lov som ikke er med, si at du ikke kan melde fra herfra, og be brukeren ta det med den som ga dem skillen.
