# MyDNS (AdGuard Home on Fly.io)

Dies ist ein einfaches Setup, um **AdGuard Home** als eigenen DNS-Server bei Fly.io zu betreiben.

## Features
- Unbegrenzter DNS mit Allow-/Denylist (wie NextDNS)
- Kostenlos im Fly.io Free Tier
- Verwaltung über Web-UI (Port 80)

## Nutzung
1. Repo zu GitHub hochladen
2. Bei [Fly.io](https://fly.io) → „Launch App from GitHub“ wählen
3. Dieses Repo auswählen
4. Fly.io baut automatisch den Container und startet AdGuard Home
5. Deine DNS-IP findest du im Fly.io Dashboard
6. In iOS: WLAN → DNS konfigurieren → Manuell → deine Fly.io IP eintragen
