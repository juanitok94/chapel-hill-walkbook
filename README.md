# Boulder Walkbook

A digital coffee passport for Pearl Street — Boulder's main corridor.

Ten coffee stops. One road. Walk it.

## What this is

A warmly narrated neighborhood guide and passport game built on the
Camino de Santiago pilgrim passport model. Collect stamps at each of
the 10 core coffee stops on Pearl Street. Earn your True Boulder Walker badge.

## Stack

- Next.js 16 (Turbopack)
- TypeScript
- Tailwind CSS 4
- Static JSON data layer
- localStorage for stamp state

## Run locally

git clone https://github.com/[yourusername]/boulder-walkbook.git
cd boulder-walkbook
npm install
npm run dev

Open http://localhost:3000

## Data

All business data lives in /src/data/
- shops.json — 17 stops, 8 layers, full data model
- layers.json — layer definitions
- badges.json — badge tiers
- trivia.json — per-stop trivia

## Design principles

- Steve Krug: Don't Make Me Think
- Camino de Santiago: personal, directional, earned
- Hygge: warmth without friction

## Hashtags

#PearlStreetWalk #Boulder #CUBuffs