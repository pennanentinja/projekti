# Acme Dashboard

Yksinkertaistettu taloushallintasovellus, rakennettu Next.js Learn -kurssin pohjalta.

## Ominaisuudet

- Kirjautuminen ja autentikointi (NextAuth.js)
- Laskujen listaus, haku ja sivutus
- Laskujen luonti, muokkaus ja poisto
- Responsiivinen design (Tailwind CSS)
- Server-side validointi (Zod)
- PostgreSQL-tietokanta (Neon)

## Teknologiat

- [Next.js 16](https://nextjs.org/)
- [TypeScript](https://www.typescriptlang.org/)
- [Tailwind CSS](https://tailwindcss.com/)
- [NextAuth.js](https://authjs.dev/)
- [Zod](https://zod.dev/)
- [PostgreSQL / Neon](https://neon.tech/)
- [Vercel](https://vercel.com/)

## Asennus

1. Kloonaa repositorio:
```bash
   git clone https://github.com/pennanentinja/projekti.git
   cd projekti/nextjs-dashboard
```

2. Asenna riippuvuudet:
```bash
   pnpm install
```

3. Luo `.env`-tiedosto ja lisää tarvittavat ympäristömuuttujat:
```env
POSTGRES_URL=...
AUTH_SECRET=...
```
4. Käynnistä kehityspalvelin:
```bash
   pnpm dev
```

## Käyttö
Avaa selaimessa [http://localhost:3000](http://localhost:3000)

Kirjaudu sisään tunnuksilla:
- Email: `user@nextmail.com`
- Salasana: `123456`

## Julkaistu sovellus on nähtävissä osoitteessa:
https://projekti-flame.vercel.app/
