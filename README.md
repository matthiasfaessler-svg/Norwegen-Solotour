# Südnorwegen Solotour 2026

Web-App zur Motorhome-Solotour 23.10.–6.11.2026 (Oberdiessbach – Kiel – Oslo und zurück). Eine einzige Datei, `index.html`, kein Build.

- **Startseite:** die drei Varianten A (West), B (Ost) und C (Rondane + Härjedalen) im Vergleich, plus Entscheidungsregel für Mo 26.10. in Oslo.
- **Einstellungen (Zahnrad):** Design Dunkel, Hell, Nordlicht oder Norwegen; Standort ein/aus.
- **Pro Variante:** Plan (Tage inkl. An- und Rückreise, Google-Maps-Links), Orte, Touren (Komoot), Nähe (Live-Standort, Plätze/Gas/Entsorgung nach Distanz, Schnellsuche Supermarkt, WC-Entsorgung, Tankstelle), Infos (Checkliste, Gas, Pässe, Fahrzeug, Nordlicht, Angeln, Tageslicht, Notruf) und Chat.
- **Chat-Berater:** kennt den ganzen Plan der gewählten Variante und den letzten Standort. In der Claude-Ansicht läuft er über das Claude-Konto; auf einer eigenen Adresse (z. B. GitHub Pages) braucht er einen Anthropic API-Schlüssel, der nur im Browser gespeichert wird.
- **Standort:** funktioniert auf einer eigenen HTTPS-Adresse (GitHub Pages) solange die App offen ist, nicht im Hintergrund.

Checkliste, Chatverlauf und letzter Standort bleiben im localStorage des Browsers.
