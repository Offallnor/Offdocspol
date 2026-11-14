# Skills

Kilden til skillen for denne basen. Skillen ligger i `skills/<navn>/SKILL.md` og lagres av brukeren fra et kort. Første gang lastes den ned som zip-fil fra samme mappe.

Dokumentene og regelverket i skillen er et utvalg, ikke alt som finnes. Si dette til brukeren når du viser lista.

| Skill | Hva den gjør | Zip |
|---|---|---|
| `offdocspol` | Gir svar fra offentlige dokumenter om politiet og kriminalitetsforebygging (NOU-er, meldinger, proposisjoner, strategier, veiledere, evalueringer og tildelingsbrev), og fra lovene for informasjonsdeling og forebygging i regelverksbasen | `skills/offdocspol/offdocspol.zip` |

## Felles skills

Felles skills som også passer for brukerne av denne basen. Kildene ligger i `https://raw.githubusercontent.com/Offallnor/offdocs/main/skills/<navn>/SKILL.md`, og nyeste versjon står i `https://raw.githubusercontent.com/Offallnor/offdocs/main/SKILLVERSJONER.md`. De lagres fra kort.

| Skill | Hva den gjør | Hvem |
|---|---|---|
| `felles-regelverk` | Gir svar fra lover, forskrifter og rundskriv utover politiet (blant annet forvaltningsloven, offentleglova, arkivlova og språklova), og om Stortinget: skriftlige spørsmål, interpellasjoner, anmodningsvedtak og representantforslag fra alle departementers områder | Anbefalt |
| `felles-sprak` | Skriveregler, nynorsk og oversetting | Anbefalt |
| `felles-data` | Gir svar om statistikk fra SSB, Nav, Eurostat og OECD. Har lite om kriminalitet | Valgfri |
| `felles-analyse` | Fast prosess for større analyser med oppdragsbeskrivelse, kildevurdering og vedlegg. Start med «kjør en større analyse» | Valgfri, for utredere |

## Installere

1. Last ned `offdocspol.zip` fra `skills/offdocspol/` (knappen «Download raw file» på GitHub).
2. I Claude: Innstillinger → Funksjoner → Skills → «Last opp skill», og velg zip-fila.
3. Claude må få hente fra raw.githubusercontent.com. Skillen sier fra hvis det ikke er tillatt, og hvordan det ordnes.

Skillen oppdaterer seg selv: den sier fra når det finnes en nyere versjon, og «oppdater skillen» gir et kort som lagrer den nye. «Hvilke skills finnes» gir kort for de felles skillene over, og «oppdater skillene» oppdaterer dem også.
