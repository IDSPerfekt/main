# IDS Perfekt – Claude Code Team-Konfiguration

Dieses Repo verteilt die gemeinsame Claude-Code-Konfiguration ans Team.

## Claude for Legal

In `.claude/settings.json` ist der Marketplace
[`anthropics/claude-for-legal`](https://github.com/anthropics/claude-for-legal)
registriert und 12 Plugins sind aktiviert (commercial, privacy, product, corporate,
employment, regulatory, ai-governance, litigation, ip, law-student, legal-clinic,
legal-builder-hub).

### Nutzung

1. Repo klonen.
2. Claude Code in diesem Verzeichnis starten.
3. Die Plugins werden automatisch geladen und sind aktiv.

> Hinweis: `cocounsel-legal` (Thomson Reuters) ist bewusst nicht aktiviert – es benötigt
> ein separates Westlaw-/Practical-Law-Konto.

## Modico Growth Agent

In `.claude/agents/modico-growth-agent.md` liegt der autonome Marketing- &
Vertriebs-Agent für die Modico-Maschinen (UV-Flachbettdrucker, 360°-UV-Runddrucker,
Lasergravur). Output-Modi auf Zuruf: `landingpage`, `listing`, `ads`, `video`,
`outbound`.

**Wichtig:** Konkrete Modelle, Specs, Preise und Margen kommen ausschließlich aus
`data/products.json` — dort ist aktuell nur ein Struktur-Gerüst hinterlegt, das mit
den echten Produktdaten befüllt werden muss. Der Agent erfindet keine Zahlen.
