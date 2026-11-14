---
name: "offdocspol"
description: "Offentlige dokumenter og regelverk om politiet og forvaltningen rundt politiet: NOU-er, stortingsmeldinger, lovproposisjoner, strategier, handlingsplaner, veiledere, evalueringer og tildelingsbrev til Politidirektoratet, PST, Spesialenheten og Riksadvokaten. Særlig kriminalitetsforebygging: samarbeid mellom kommune og politi, informasjonsdeling, bekymringssamtale, politiråd, radikalisering og voldelig ekstremisme, barn og unge, vold i nære relasjoner. Også lovene for informasjonsdeling og forebygging: politiloven, politiregisterloven (taushetsplikt i politiet), barnevernsloven og helsepersonelloven. Bruk ved «hva sier NOU-en om…», «hva står i tildelingsbrevet til POD», «finnes det en veileder for…», «kan politiet dele opplysninger med skolen», «når må vi melde til barnevernet», også uten fagord. Last den før du svarer, og svar ikke fra hukommelsen. Også når brukeren spør hva basen inneholder, hvilke skills som finnes, eller sier «oppdater skillen» eller «oppdater skillene»."
---

# Dokumenter om politiet

**Versjon 2026-11-14.2.**

Dokumentene og lovene ligger ikke i denne skillen. De ligger i to åpne baser på GitHub og hentes ved hvert oppslag.

## Fremgangsmåte

1. Hent `https://raw.githubusercontent.com/Offallnor/offdocspol/main/CLAUDE.md` med `curl -sL` i kodeverktøyet, eller med hentverktøyet ditt. Følg den.
2. Hent `VEIVISER.md` fra samme sted og finn dokumentet i lista. Åpne bare dokumentet eller delen du trenger.
3. Finnes ikke dokumentet, følg regel 5 i CLAUDE.md.
4. **Gjelder spørsmålet hva loven sier** (for eksempel taushetsplikt, informasjonsdeling, bekymringssamtale, meldeplikt til barnevernet, forvaltningsloven eller personvern), hent `https://raw.githubusercontent.com/Offallnor/offdocs/main/CLAUDE.md` og følg den. Der ligger politiloven med politiinstruksen, politiregisterloven med politiregisterforskriften, barnevernsloven, helsepersonelloven, forvaltningsloven, offentleglova og personopplysningsloven. Svar ikke på lovspørsmål fra hukommelsen. Straffeloven og straffeprosessloven er ikke med: si det, og vis til lovdata.no.

## Andre skills

Noen felles skills passer også for brukerne av denne skillen. Lista står under «Felles skills» i `https://raw.githubusercontent.com/Offallnor/offdocspol/main/skills/KATALOG.md`. Kildene ligger i `https://raw.githubusercontent.com/Offallnor/offdocs/main/skills/<navn>/SKILL.md`.

**Tips i svaret.** Bygger svaret på lov eller forskrift, og er `felles-regelverk` ikke blant skillene dine, avslutt svaret med en skillelinje og: «**Tips:** Det finnes også en skill for lov og forskrift og for det som skjer på Stortinget. Si "hvilke skills finnes" for å få den.» Gjelder spørsmålet skriving, nynorsk eller oversetting, og er `felles-sprak` ikke blant skillene dine, si det samme om en skill for skriveregler, nynorsk og oversetting. Gi høyst ett tips i samtalen, og ikke i samme svar som beskjeden om ny versjon.

**«Hvilke skills finnes» eller «installer flere skills»:** hent katalogen. Si kort hvilke av skillene der som er installert, og hvilke som mangler. Legg straks fram kort for de anbefalte som mangler. Nevn de valgfrie i én setning med hva de er til, og legg dem fram bare hvis brukeren vil ha dem. Si at innholdet er et utvalg, ikke alt som finnes.

**«Oppdater skillene»** (også når en felles skill sier at det finnes en nyere versjon): har brukeren skillen `felles-intern`, la den gjøre jobben. Ellers: hent `https://raw.githubusercontent.com/Offallnor/offdocspol/main/SKILLVERSJONER.md` og `https://raw.githubusercontent.com/Offallnor/offdocs/main/SKILLVERSJONER.md`. Finn de installerte skillene fra katalogen og denne skillen med kodeverktøyet, for eksempel under `/mnt/skills/` eller `~/.claude/skills/`, og les hele den installerte SKILL.md for hver. Legg fram kort for dem som har en nyere versjon i lista. Si i én setning at resten er oppdatert.

**Kort:** bruk kilden uendret. Har du verktøyet `propose_skills`, legg skillene fram som kort brukeren kan lagre, med høyst tre per kort. Bruk `kind: new` for nye skills og `kind: improvement` for installerte, og les den installerte fila helt før du foreslår en forbedring. Bruk beskrivelsen fra fila uendret. Har du ikke verktøyet, si at skillen ikke kan lagres herfra nå, og be brukeren prøve igjen i en ny samtale.

Snakk enkelt om dette: «jeg henter skillene fra den felles samlingen», «lagre skillene ved å trykke på kortet under». Nevn ikke nettadresser, filer eller versjonsnumre.

## Ny versjon

Hent `https://raw.githubusercontent.com/Offallnor/offdocspol/main/SKILLVERSJONER.md`. Står det en nyere versjon av `offdocspol` der enn i versjonslinjen over, avslutt svaret med en skillelinje og: «**Ny versjon:** Det finnes en nyere versjon av denne skillen. Si "oppdater skillen" for å få den.» Si det bare én gang i samtalen. Ber brukeren om å oppdatere, hent `https://raw.githubusercontent.com/Offallnor/offdocspol/main/skills/offdocspol/SKILL.md` og vis den som et lagringskort. Feiler hentingen, la det være.

## Hvis hentingen feiler

Svar ikke fra hukommelsen. Ser feilen ut som en sperre (403, «not allowed», «blocked» eller nektet tilkobling), si:

«Jeg fikk ikke hentet dokumentet, fordi Claude ikke har lov til å hente fra nettstedet [nettsted]. Du kan åpne for det selv: Gå til Innstillinger → Funksjoner. Under «Kodekjøring og filoppretting i skyen» skroller du ned til «Tillatelsesliste for domener» og legger til [nettsted]. Spør meg igjen etterpå, gjerne i en ny samtale.»

Ved andre feil: «Jeg fikk ikke hentet dokumentet nå. Prøv igjen litt senere.»

## Feil, mangler og ønsker

Sier brukeren at noe er feil eller mangler, eller ønsker et dokument eller en lov som ikke er med, også i en av de felles skillene, si at du ikke kan melde fra herfra, og be brukeren ta det med den som ga dem skillen.
