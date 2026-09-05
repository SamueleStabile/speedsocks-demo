# SPEEDSOCKS ⚡ — landing + checkout demo

Landing page di calzini sportivi (tema: **velocità**) con checkout **Stripe in test mode**, costruita in one-shot con Claude Code come test di fattibilità per un corso.

## Stack

- HTML/CSS/JS statico, zero build — font: Anton + Archivo + IBM Plex Mono
- **Stripe Payment Link** (sandbox) per il checkout: prodotto *SpeedSocks Pro*, €14,90
- Repo creato con `gh` CLI, deploy statico su Vercel

## Test del checkout

Il bottone "Compra ora" apre un checkout Stripe **di prova**: nessun addebito reale.
Carta di test: `4242 4242 4242 4242`, scadenza futura qualsiasi, CVC qualsiasi.

---
🤖 Generato con [Claude Code](https://claude.com/claude-code) — MCP usati: Stripe (checkout), GitHub connector (tentato, fallback su `gh`), browser integrato per la verifica.
