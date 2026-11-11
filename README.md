# Organizare de Șantier fără Emisii CO₂/CO — 07.11.2026

Engineering Division — Jedi Ciprian Lazar

## Fișiere curente (vezi folderul `07.11.2026/`)
- `07.11.2026.Organizare_Santier_Calcul_v4.xlsx` — calculatorul (Principal + Personal + Clima_RO legate; restul independente)
- `07.11.2026.Organizare_Santier_Fara_Emisii_v4.html` — pagina dinamică (rulează direct în browser, și pe telefon)

## Ce conține v4
- [x] Program de lucru pe sezon (iarnă/vară): ore, oră de start, zile/săpt (inclusiv weekend)
- [x] 15°C în afara programului (anti-îngheț); dormitoare 15°C în program, 22/20°C după program
- [x] 3 scenarii din brief (CMD/NOR/ECO) + producție identică între scenarii
- [x] Optimizare automată a programului (scan ore × zile) — regula: **off-grid obligatoriu**
- [x] Tabel localități România (41) în loc de hartă: t calc, îngheț STAS 6054/77 → fundare, vânt, PV
- [x] Turbine pe stâlp 6 m (hub), 2 rânduri × 15–20 m, front ajustabil; putere turbină 3/3,5 kW (<5 kW = fără prag 5 m/s)
- [x] 1 tablou = max 2 invertoare (întreg); 1 tablou general (ATS) + sub-tablouri pe grupuri; BMS/EMS cu délestare pe priorități
- [x] Stație EV dublă 2×11 kW (vară, mai–sep); iluminat exterior (stâlpi autonomi solar / cu turbină)
- [x] Scheme în HTML jos: bloc flux, bloc tablouri, funcțională instalații (ventilație+ACM), desfășurate SDS + jurnal de cabluri
- [x] Prețuri editabile pe echipamente + cost total; default amplasament = Constanța

## Cum continui de pe telefon (fără laptop)
1. Deschide acest README + fișierele din `07.11.2026/` direct din GitHub pe telefon.
2. În orice conversație nouă cu asistentul, dă paste la lista ta de cerințe rămase — contextul se reconstruiește din repo + listă.

## Cerințe rămase / de bifat
- [ ] (adaugă aici din lista de pe telefon)
