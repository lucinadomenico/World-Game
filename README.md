# World-Game v0.1 (MVP)
Versione minimale **online**: Lobby + Room + Bubble 1v1 (demo).

## Requisiti
- Node.js 18+

## Avvio
1) Apri terminale nella cartella `server/`
2) Installa dipendenze:
```bash
npm install
```
3) Avvia server:
```bash
npm run dev
```
4) Apri dal browser:
- http://localhost:3000

## Test 1v1
- Apri due finestre browser (o 2 dispositivi)
- Entra con nickname
- Crea stanza → condividi il codice
- Entra con codice (seconda finestra)
- Entrambi: Ready → countdown → Apri gioco → clic bolle → risultato

Credits: Domenico Lucina


## Struttura estesa (pronta per crescere)
- `games/` giochi modulari (bubble, poker, roulette, ecc.)
- `assets/` risorse (avatar, carte, suoni, loghi)
- `database/` cartelle placeholder (in v0.1 non usate)
- `updates/` sistema patch locale (MVP) + `patches/`
- `docs/` documentazione
- `logs/` log aggiornamenti (ignorati da git)

### Patch locali (MVP)
Metti uno zip in `updates/patches/` con dentro i file da sostituire (stesso path).
Poi esegui:
```bash
cd server
npm run update
```
