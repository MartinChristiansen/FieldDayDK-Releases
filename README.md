# FieldDayDK af OZ1IKU
![main window](https://raw.githubusercontent.com/MartinChristiansen/FieldDayDK-Releases/master/screenshot.png)

## Hvad er det?
FieldDayDK er et logprogram, som er udviklet specielt til dansk deltagere i EDRs årlige **HF Field Day**. Programmet er skræddersyet til at bruge de gældende, danske regler for logføring og points. Programmet er kun til Windows (.NET 8).

## Hent seneste version her
Downloadlink (downloader, når du klikker): [FieldDayDKSetup.msi 1.0.1.0](https://github.com/MartinChristiansen/FieldDayDK-Releases/releases/download/v1.0.1.0/FieldDayDK_1_0_1_0.msi)

Link til [alle releases](https://github.com/MartinChristiansen/FieldDayDK-Releases/releases)


## De vigtigste features:
- **Programmet er på dansk** i hele brugerfladen
- **Superlet at betjene**, og næsten ingen opsætning
- Holder styr på de **op til 15 krævede, samtidige logblade** (et logblad pr. mode (CW/SSB/DIGI) pr. bånd (80-40-20-15-10)
- **To forskellige indtastningsmodes** ('Live' og 'Efterregistrering)
- **Skifter automatisk til det tilsvarende logblad**, når man skifter mode eller bånd på radioen (kræver OmniRig installeret)
- **Tilføjer automatisk FT8- og FT4-QSO'er**, hvis man kører med WSJT-X på samme maskine
- **Dubletkontrol** (naturligvis)
- **Henter automatisk seneste liste med DXCC-lande i baggrunden** (fra internettet). Hvis der ikke er internetforbindelse til rådighed, bruges den senest hentede fil, eller den, som kommer med programmet.
- **Automatisk, kontinuerlig pointudregning**, både pr.bånd og totalt
- **Løbende opslag og visning af DXCC-land**, alt imens man taster kaldesignal
- **Løbende opslag og visning af navn på modpart**, imens man taster kaldesignal (QRZ.com-opslag)
- **Løbende indikering af multiplier, dublet og QSO-points**, imens man indtaster kaldesignal
- **Direkte editering i loggede QSO'er** (dobbeltklik på den celle, som skal rettes. En evt. efterfølgende genberegning af points mm. foretages automatisk).
- **Vindue med oversigt over, hvilke prefixer, der er kørt på hvilke bånd** (Prefix matrix)
- **Ét-kliks-generering af ADIF-filer + udfyldt sammentællingsblad** (til fieldday-manager, når testen er slut)
  
## Versionshistorik:

### 1.0.2.0:
- **To forskellige indtastningsmodes:** _Live_ og _Efterregistrering_ (_Live_=indstastning imens QSO foregår, _Efterregistrering_=indtastning af alle QSO'er fra papirlog, når testen er slut)

### 1.0.1.0:
- **Forbedret håndtering af navigering til indtastningsfelt med eksisterende tekst** (vha. TAB eller SPACE): Teksten i feltet bliver nu automatisk markeret, således at den bliver erstattet, hvis man begynder at taste ny tekst. Førhen blev der tilføjet tekst foran det, der stod i feltet forvejen, hvilket var meget uhensigtsmæssigt. 
- **Tilføjet automatisk tjek for opdateret version ved hver opstart**, med mulighed for straks at downloade den ny version. 
- **Tilføjet mulighed for at skifte imellem logblade vha. tastatur:** "10" i kaldesignalfeltet skifter f.eks. til 10m-logbladet (uændret mode), og "CW" skifter til CW-logbladet (uændret bånd). Man kan også skifte logblad for bånd og mode på én gang med f.eks. "15DIGI" (skifter til logbladet for  15m digital). NB: Fungerer kun, når radioen ikke styrer det selv.
- **Forbedret skalering:** Når man gør programvinduet større eller mindre, tilpasser indtastingsområdet sig automatisk således, at alle indtastningsfelterne til stadighed er synlige og brugbare (hele indtastningsområdet bliver forstørret/formindsket sammen med vinduet i stedet for at blive klippet af). På den måde kan man stadig bruge programmet, selv om man gør det meget mindre for at få plads til andre ting på skærmen også.

### 1.0.0.0:
- Første officielle version til rigtigt brug
- Debugget i alle detaljer.
- Hjælpemenu med programnoter (__vigtigt: husk at læse dem!__)
- Kan nu fortolke WSJT-X-Qso-beskeder fra både primær og sekunder UDP-port
- Kræver nu som udgangspunkt, at WSJT-X kører i "EU VHF Contest"-mode
- Kosmetiske forbedringer

### 0.9.0:
Stadig en prototype (tidsbegrænset indtil 1. september 2025)

