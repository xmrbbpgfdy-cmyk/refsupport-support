# RefSupport Support-Website

Statische, zweisprachige Support- und Rechtstexte für RefSupport. Die Website benötigt keinen Build-Schritt, kein JavaScript und keine externen Assets.

## Vor der Veröffentlichung

1. Alle Platzhalter projektweit ersetzen: `{{ANBIETER_NAME}}`, `{{STRASSE}}`, `{{PLZ_ORT}}`, `{{LAND}}`, `{{EMAIL}}`, `{{STAND_DATUM}}`.
2. Den Inhalt in ein eigenes öffentliches GitHub-Repository kopieren.
3. In den Repository-Einstellungen GitHub Pages für den Branch und Ordner aktivieren, in dem `index.html` liegt.
4. Die veröffentlichten URLs in App Store Connect und in `PurchaseConfiguration.swift` eintragen.

Die internen Links sind relativ und funktionieren deshalb auch unter `https://<user>.github.io/<repo>/`. Externe Verbindungen entstehen auf den Seiten nur, wenn ein normaler Hyperlink bewusst geöffnet wird.
