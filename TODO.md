# BITWIG MET CLAUDE — takenlijst leerpad

*Opgesteld 22 oktober 2026, fase 0 afgerond dezelfde dag. Structuur: mengvorm — de handleiding als ruggengraat, Ch19 gesplitst per devicefamilie, plus Praktijk en Wat is nieuw.*

## Bronnenprincipe (afgesproken)

| Rol | Bronnen | Opmerking |
|---|---|---|
| **Lezen** (basis, dicht bij het DAW-gebruik) | Handleiding (MANUAL_PLUS, versie 5.3) · Polarity's geschreven gidsen (polarity.me/bitwig-guides) | De handleiding is 5.3: Bitwig 6-nieuwigheden komen uit de release notes 6.0 en 6.1 |
| **Kijken** (uitleg) | XNB (voorrang bij overlap) · Bitwig · Alex Reid · andere makers · **Polarity-video's die bij zijn geschreven gidsen horen** (kanaal @BitwigGuide) | Opgeknipt in clips die de speler afspeelt. De gidsvideo's van Polarity zijn per device gemaakt en volgen de handleiding |
| **Kijken** (gevorderd) | Overige Polarity-video's (hoofdkanaal, livestreams, tips) | Vaak vrijer en gevorderder; als verdieping na de basis |
| **Eigen notities** | Dropbox `MARKDOWN NOTITIES/Muziek/DAWs/Bitwig` | Arpeggiator.md, Modulators – eigen notities, samenvatting met shortcuts |

## Stand per onderdeel

Legende: ✅ klaar · 🟡 deels · ⬜ nog niet · — bestaat niet. Bitwig 6-nieuws 🟡 = samengevat uit de release notes in index.html, nog niet getoetst aan video's.

| Onderdeel | Handleiding (MANUAL_PLUS) | Bitwig 6-nieuws | Polarity-gidsen | Video's in lijst | Video's uitgediept (clips) | Eigen notities |
|---|---|---|---|---|---|---|
| Ch00–04 Basis | ✅ | 🟡 | — (alleen algemene tips) | 17 (2u50) | ⬜ | 🟡 samenvatting met shortcuts |
| **Ch03 + Ch05 Arranger** | ✅ | ✅ getoetst aan video's | — | 9 (2u23) | ✅ **79 clips uit 11 video's** | 🟡 samenvatting hfst. 5 |
| Ch06 Clip Launcher | ✅ | 🟡 | — | 3 (23 min) | ⬜ | 🟡 samenvatting hfst. 6 |
| Ch07 Mix View | ✅ | 🟡 | — | 4 (49 min) | ⬜ | ⬜ |
| Ch08 Devices (containers, layers) | ✅ | 🟡 | 🟡 Voice Stacks (1 gids + video) | 6 (57 min) | ⬜ | ⬜ |
| Ch09 Automation | ✅ | 🟡 | — | 3 (39 min) | ⬜ | ⬜ |
| Ch10 Audio Events | ✅ | 🟡 | — | 10 (2u00) | ⬜ | ⬜ |
| **Ch11 Note Events** | ✅ | ✅ getoetst aan video's | — | 7 (1u04) | ✅ **45 clips uit 6 video's** | 🟡 samenvatting 7.0 (deels onjuist, zie index) |
| Ch12 Operators | ✅ | 🟡 | — | 2 (1u02) | ⬜ | ⬜ |
| Ch15 MIDI Controllers | ✅ | 🟡 | — | 13 (1u13) | ⬜ | ⬜ |
| **Ch16 Modulators** | ✅ | 🟡 | ✅ **uitgeplozen** (38 gidsen incl. modulatiesysteem en copy/paste, elk met video; leerplan_modulators.html) | 43 (7u14) | ⬜ | ✅ Modulators – eigen notities |
| Ch17 The Grid | ✅ | 🟡 | 🟡 12 modulegidsen (11 met video) + Grid-cursus | 45 (17u14) | ⬜ | ⬜ |
| **Ch19a Note FX** | ✅ | 🟡 | — (geen gidsen) | 25 (4u04) | ✅ **Note FX-clipgids** | ✅ Arpeggiator.md |
| Ch19b Instrumenten | ✅ | 🟡 (6.1 Sampler!) | 🟡 Polysynth, Organ, Sampler (2), elk met video | 42 (7u14) | ⬜ | ⬜ |
| Ch19c Audio FX | ✅ | 🟡 | 🟡 15 gidsen met video (o.a. Delay-1, Reverb, Saturator, Tool, Filter+) | 48 (9u13) | ⬜ | ⬜ |
| Ch19d Spectral | ✅ | 🟡 | — | 9 (1u58) | ⬜ | ⬜ |
| Praktijk | — | — | 🟡 Tips & Tricks-pagina | 17 (6u44) | ⬜ | — |
| Wat is nieuw | — | ✅ release notes 6.0/6.1 verdeeld | — | 5 (49 min) | — | — |
| Ch13, Ch14, Ch18 | ✅ | 🟡 | — | bijna geen | — | — |

## Takenlijst

### Fase 0 — Fundament (eenmalig)
- [x] De video's bij Polarity's 71 geschreven gidsen inventariseren: 69 gidsen hebben precies één video, 2 (Tips & Tricks, generatieve Grid-patches stoppen) geen. Per onderdeel in index.html onder "Polarity-gidsvideo's".
- [x] `index.html` in de root: inhoudspagina volgens de mengvorm, met per onderdeel links naar MANUAL_PLUS, Polarity-gidsen, video's/clips, eigen notities en deze status.
- [x] Note FX-clipgids opnemen in de inhoudspagina (onderdeel Ch19a), in plaats van als aparte pagina.
- [x] Release notes Bitwig **6.0 en 6.1** verwerken tot een laag "Nieuw in Bitwig 6" per onderdeel (de handleiding is 5.3).
- [ ] `_te_verwijderen/` leegmaken (Dany).
- [x] Ankers toegevoegd aan alle MANUAL_PLUS-hoofdstukken (`#s-…` per sectie) en aan Ch19 Device Descriptions (`#d-arpeggiator`, `#cat-note-fx` …) zodat de inhoudspagina per device kan linken. Origineel in `_archief/MANUAL_PLUS_voor_ankers/`.

### Fase 1 — Dagelijks werkgebied (arranger, piano roll, automation)
Per onderdeel: transcripties → clips (XNB voorrang) → koppelen aan handleiding + Bitwig 6 → gaten → eigen notities.
- [x] Ch11 Note Events (incl. Expressions): 45 clips, gaten en Bitwig 6-vlaggen per onderwerp. Operators in Bitwig 4 → Ch12, Audio Expressions → Ch10.
- [x] Ch05 Arranger Clips + Ch03 Arranger: 79 clips. Video's uit Basis (Arranger and Clip Launcher, Snap/Grid) en Audio events (Clips & Audio Events, Offset & Loop, Clip Aliases, Overdub) verplaatst naar dit onderdeel.
- [ ] Ch09 Automation (Bitwig 6: Automation Clips, automation-editing)
- [ ] Ch06 Clip Launcher
- [ ] Ch10 Audio Events (comping, fades)
- [ ] Ch12 Operators

Open vragen uit Ch11:
- Welke Bitwig 6-functie vervangt XNB's 'consolidate' voor Spread-expressies?
- Werkt Pen + Alt (Quick Draw) nog in Bitwig 6, of alleen de Spray Can?
- Samenvatting sectie 7.0 nakijken: Fix Overlaps, Invert, Extend to Playhead, Shorten to Grid, Enable MPE for clip staan niet in de handleiding.

Open vragen uit Ch03/Ch05:
- Punch In/Out in Bitwig 6: starten ze nog een opname, of begrenzen ze alleen (release notes 6.0)?
- Bounce while dragging (toets B, 6.1) even uitproberen.

### Fase 2 — Modulatie (lezen is klaar, video's nog niet)
- [ ] Ch16: video's opknippen en naast het Polarity-leerplan en je eigen notities leggen
- [ ] Verplaatste video's verwerken (Quantize-, Note Counter- en Note Sidechain-modulator)

### Fase 3 — Devices
- [ ] Ch19c Audio FX (14 Polarity-gidsen beschikbaar)
- [ ] Ch19b Instrumenten (Polysynth, Organ, Sampler)
- [ ] Ch19d Spectral
- [ ] Ch08 Containers, layers, voice stacks

### Fase 4 — Rest
- [ ] Ch00–04 Basis, Ch07 Mix, Ch15 Hardware
- [ ] Praktijk (workshops, How It's Done)
- [ ] Overige Polarity-video's toevoegen als laag "gevorderd" per onderdeel
- [ ] Ch17 The Grid (geparkeerd; ±10 Polarity-modulegidsen + Grid-cursus)

## Mappen

```
BITWIG MET CLAUDE/
├── index.html              ← inhoudspagina (gegenereerd; vinkjes "bekeken" bewaart de browser)
├── TODO.md                 ← dit bestand
├── MANUAL_PLUS/            ← handleiding 5.3 per hoofdstuk + Polarity-inserts (Masterclass verwijderd)
├── SOURCES/
│   ├── 01_Officiele_Handleiding/
│   ├── 03_YouTube_Polarity_etc/   (leeg)
│   └── leerplan_modulators.html   ← Polarity-modulatorleerplan
├── _archief/               ← INDEX_mei2026, MANUAL_PLUS_met_masterclass
└── _te_verwijderen/        ← Morningdew + Mattias-video (zelf leegmaken)
```
