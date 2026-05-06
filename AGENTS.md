# Project Instructions – Spenglerei Wögini

## Design Constraints (override skill defaults)

- **Font für Logo:** Georgia / Serif (fest) - für die restliche Seite sonst egal
- **Hauptfarben:** Schwarz (#0a0a0a) / Weiß als Hauptfarben; andere Farben erlaubt
- **Layout:** Geradlinig, architektonisch – KEIN Grid-breaking, keine Asymmetrie, kein Chaos
- **Effekte:** 3D-Optik 
- **Zielgruppe:** 40+, modern 
- **Keine Preise** auf der Website

## Skill-Hierarchie

Bei widersprüchlichen Empfehlungen der Skills gilt diese Reihenfolge:

1. **Dieses Dokument** – Projekt-spezifische Vorgaben überschreiben alles
2. **ui-ux-pro-max** – UX-Regeln (Accessibility, Touch-Targets, Performance, Responsive) gelten immer
3. **frontend-design** – Kreative Umsetzung innerhalb der oben definierten Constraints
4. **web-design-guidelines** – Ergänzende Review-Kriterien
5. **ckm-design-system** – Design-Token-Architektur (CSS Custom Properties, Spacing-/Typografie-Scales)
6. **theme-factory** – Nur zur strukturierten Anwendung des bestehenden Farbschemas

## Skill-Zuordnung

| Skill | Einsatzbereich |
|-------|---------------|
| **ui-ux-pro-max** | Layout, Responsive, Accessibility, Touch-Targets, Interaction States |
| **frontend-design** | Kreative Umsetzung von Sections, Komponenten, Animationen |
| **web-design-guidelines** | Code-Review, Compliance-Check gegen Best Practices |
| **ckm-design-system** | CSS Custom Properties, Token-Struktur, konsistente Scales |
| **theme-factory** | Farbschema-Struktur innerhalb der definierten Hauptfarben |
| **seo-audit** | Technisches SEO, Meta-Tags, Struktur, Local SEO für Handwerksbetrieb |
| **gdpr-data-handling** | Cookie-Consent, Kontaktformular-Datenschutz, Impressum/Datenschutzerklärung |
| **agent-browser** + **core** | Visuelles Testen, Screenshot-Vergleiche, Responsive-Checks |
| **canvas-design** | Erstellung visueller Assets (Poster, Grafiken) falls benötigt |

## Technische Vorgaben

- **Stack:** Plain HTML/CSS, kein Framework, kein Build-Step
- **Keine externen Requests** ohne Cookie-Consent (Fonts lokal hosten, keine CDNs, keine Tracker)
- **Single-Page Website** (aktuell)
- **Hosting:** GitHub Pages
- **CSS Reset:** modern-normalize (lokal eingebunden)

## SEO-Vorgaben

- Lokales SEO für Handwerksbetrieb (Spenglerei) in Österreich
- Strukturierte Daten (LocalBusiness Schema) einsetzen
- Semantisches HTML (header, nav, main, section, footer)
- Meta-Description, Open Graph Tags
- `seo-audit` Skill für regelmäßige Überprüfung nutzen

## Datenschutz / GDPR

- Cookie-Consent vor externen Requests (falls zukünftig nötig)
- Kontaktformular: Hinweis auf Datenverarbeitung, keine Speicherung ohne Rechtsgrundlage
- Impressum & Datenschutzerklärung erforderlich (österreichisches Recht + DSGVO)
- `gdpr-data-handling` Skill für Compliance-Checks nutzen

## Gestaltungsprinzipien

- Wenig & kurze Texte, viele Bilder
- Großzügiger Whitespace
- Klare visuelle Hierarchie
- Konsistente Abstände und Schriftgrößen
- Animations: subtil, purposeful, CSS-only (prefers-reduced-motion respektieren)

## Testing & QA

- `agent-browser` + `core` Skills für visuelles Testing verwenden
- Responsive-Checks auf verschiedenen Viewports
- Accessibility-Audit (Kontraste, Keyboard-Navigation, Screen-Reader)
