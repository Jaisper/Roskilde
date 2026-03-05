# Roskilde Festival 2026 — AI Kunstner Anbefaler

🎪 AI-drevet anbefalingsværktøj til Roskilde Festival 2026.

**Live:** [jaisper.github.io/Roskilde](https://jaisper.github.io/Roskilde/)

## Features

- 🎵 **100+ kunstnere** — hentet live fra roskilde-festival.dk ved hver sideload
- 📅 **Dag-opdeling** — onsdag til lørdag (Final Days 1-4 juli)
- 🎤 **Scene-kolonner** — Orange, Arena, Avalon, Gloria, Eos, Pavillon
- 🤖 **AI-anbefalinger** — vælg dine favoritter, få 10 personlige anbefalinger med beskrivelser
- 🎧 **Spotify-links** — direkte søgning for hver kunstner
- 🔗 **roskilde-festival.dk links** — på anbefalede kunstnere
- 📱 **Responsivt** — virker på desktop, tablet og mobil
- ⏰ **Tids-sortering** — skifter automatisk fra alfabetisk til tidssorteret når tidsplan offentliggøres
- 🔄 **Cached fallback** — virker offline med snapshot af seneste program

## Tech

- Ren HTML/CSS/JS — ingen build process
- Groq API (gratis) med Llama 3.3 70B
- CORS proxy for live scraping
- GitHub Pages deployment

## Brug

1. Åbn siden
2. (Valgfrit) Indtast Groq API nøgle fra [console.groq.com](https://console.groq.com)
3. Klik på kunstnere du kan lide
4. Tryk "Find anbefalinger"

## Opdatering

Programdata hentes automatisk fra roskilde-festival.dk. Cached fallback opdateres manuelt i `index.html`.
