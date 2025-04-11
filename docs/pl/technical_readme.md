# Dokumentacja Techniczna

## Stack Technologiczny
- TypeScript
- pnpm
- React
- PostgreSQL (Database)
- Next.js (Framework)
- Python

  ## Sugerowane wersje narzędzi:
  - python: 3.10
  
## Uruchomienie projektu
1. Instalacja zależności
```bash
  pnpm install
  pip install -r requirements.txt
 ```
2. Uruchomienie backendu
```bash
  python main.py
```
3. Uruchomienie aplikacji
```bash
   pnpm run start
```

## Komendy:
- `pnpm run dev` - uruchomienie projektu w trybie deweloperskim
- `pnpm run build` - zbudowanie projektu
- `pnpm run start` - uruchomienie projektu w trybie produkcyjnym
- `pnpm run lint` - sprawdzenie kodu pod kątem błędów
- `pnpm run db:push` - przesłanie zmian w bazie danych
- `pnpm run db:studio` - otwarcie UI bazy danych
  
## Struktura projektu
- `src/app` - folder z główna aplikacją oraz ekranami.
- `src/server` - folder z bazą danych.
- `src/styles` - folder z arkuszami stylów.

]
