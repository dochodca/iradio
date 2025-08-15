# ČRo Dvojka – Live (Podcast Feed pre Spotify)

Tento projekt generuje RSS feed pre Český rozhlas Dvojka, ktorý sa každú hodinu automaticky aktualizuje,
aby Spotify neukončilo prehrávanie streamu.

## Použitie
1. Vytvor si nový GitHub repository (public)
2. Nahraj tieto súbory
3. V Settings → Pages nastav publikovanie z `main` branch (root folder)
4. Skopíruj URL k `feed.rss`
5. V Spotify for Podcasters pridaj túto URL ako podcast

Po aktivácii GitHub Actions sa `feed.rss` bude každú hodinu obnovovať.
