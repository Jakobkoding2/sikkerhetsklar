# SikkerhetsKlar — NIS2 Samsvarssjekk for Norske Bedrifter

NIS2 gap-analyse-as-a-service for norske SMBer. Selvbetjent verktøy som kartlegger samsvar med Digitalsikkerhetsloven og NIS2 Art. 21.

## Funksjoner

- Interaktiv vurdering med 44 spørsmål fordelt på 10 NIS2-domener
- Automatisk klassifisering (vesentlig/viktig enhet)
- Visuell resultatside med score per domene
- Profesjonell PDF-rapport med handlingsplan
- Stripe-betaling (990 NOK engangskjøp)
- E-postlevering av rapport via Resend
- Admin-dashboard for statistikk

## Kjør lokalt

```bash
npm install
cp .env.local.example .env.local
npm run dev
```

Åpne [http://localhost:3000](http://localhost:3000).
