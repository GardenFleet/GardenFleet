# Accessibility – Garden Fleet

_Last updated: 21. Mai 2026_

Garden Fleet is built to be usable by everyone, including people who navigate iOS with VoiceOver, Voice Control, larger text, or other built-in accessibility features. This page documents which Accessibility Nutrition Label features Garden Fleet supports on iPhone, how to turn each one on, and where the app falls short today.

> 🇩🇪 Eine deutsche Fassung steht unten unter [Bedienungshilfen (Deutsch)](#bedienungshilfen-deutsch).

## Supported features

### VoiceOver
Garden Fleet supports VoiceOver across all common tasks: onboarding, subscription purchase, connecting a GARDENA account, viewing the dashboard, switching between houses, starting and stopping individual valves, the Stop-All action, inspecting sensors, and managing app settings. All interactive elements expose a meaningful label, control type, and — where useful — a hint describing the action. Icons that exist purely as decoration are hidden from VoiceOver to keep announcements concise.

Turn on: Settings → Accessibility → VoiceOver.

### Voice Control
Voice Control benefits from the same labelling work as VoiceOver. Every tappable control in the common tasks above can be activated by name. The exact label for each control matches what VoiceOver announces.

Turn on: Settings → Accessibility → Voice Control.

### Larger Text
Garden Fleet's layouts have been validated up to the largest accessibility text size (AX5). House identifiers, sensor cards, valve rows and detail views all expand and reflow rather than truncating or overlapping. The status section of the active-house header rearranges itself so the house identifier and the weather indicator no longer compete for space.

Turn on: Settings → Accessibility → Display & Text Size → Larger Text.

### Dark Interface
Garden Fleet adopts the iOS system color scheme, so switching the system into Dark Mode automatically applies a consistent dark interface across all screens.

Turn on: Settings → Display & Brightness → Dark, or Settings → Accessibility → Display & Text Size → "Smart Invert" / "Classic Invert" if you prefer system-wide inversion.

### Differentiate Without Color Alone
Each house in Garden Fleet can be assigned a custom SF Symbol (house, leaf, tree, mountain, building, beach umbrella) in addition to an accent color. The symbol is shown in the house identifier badge, the sensor strip header chip and above the active page indicator dot. Users who cannot reliably distinguish colors can therefore identify each house by its symbol and its name.

Choose a symbol when adding a new house, or in the "Edit Home" sheet for any existing house.

### Sufficient Contrast
Garden Fleet uses Apple's system text colors and contrast-aware materials in all primary interface elements, which adapt automatically when "Increase Contrast" is enabled. Custom accent colors used for house badges are layered with darker overlays where text is rendered on top of header imagery, so the displayed text retains a WCAG-AA contrast ratio.

Turn on: Settings → Accessibility → Display & Text Size → Increase Contrast.

### Reduced Motion
Animations in Garden Fleet rely on the system's standard SwiftUI transitions, which respect the "Reduce Motion" setting and shorten or disable accordingly. The horizontal page swipe between houses, the splash transition and any auto-dismissing sheets behave less abruptly when this setting is on.

Turn on: Settings → Accessibility → Motion → Reduce Motion.

## Not supported

### Captions
**Not applicable.** Garden Fleet does not present any audio or video content. There is no spoken dialog, voice-over commentary, or sound effect that conveys information; therefore no captions are required.

### Audio Descriptions
**Not applicable.** Garden Fleet does not present any video content. There is no moving image that conveys information; therefore no audio descriptions are required.

## Known limitations and what we're working on

- The first release of Garden Fleet has not yet been tested with members of the blind/low-vision community in the field. We plan to invite external testers via TestFlight after public release and to iterate on real-user feedback in subsequent versions.
- Live Activities, Widgets and a watchOS companion are on the roadmap. When they ship, they will go through the same accessibility validation as the main app.
- Garden Fleet does not currently expose App Intents for Siri / Shortcuts / Vocal Shortcuts. These are planned for an upcoming release and will let users start, stop and switch between houses entirely by voice.

## Accessibility feedback

If you encounter an accessibility issue, or you have a suggestion to improve Garden Fleet for users with disabilities, please get in touch via the contact details in [IMPRESSUM.md](IMPRESSUM.md). We treat accessibility reports as priority.

---

# Bedienungshilfen (Deutsch)

_Letzte Aktualisierung: 21. Mai 2026_

Garden Fleet ist so gebaut, dass es für alle nutzbar ist – auch für Menschen, die iOS mit VoiceOver, Sprachsteuerung, größeren Schriften oder anderen Bedienungshilfen bedienen. Diese Seite dokumentiert, welche Features der Accessibility Nutrition Labels Garden Fleet auf dem iPhone unterstützt, wie du jede Funktion aktivierst und wo die App heute noch Lücken hat.

## Unterstützte Funktionen

### VoiceOver
Garden Fleet unterstützt VoiceOver über alle wichtigen Aufgaben hinweg: Onboarding, Abo-Abschluss, GARDENA-Account verbinden, Dashboard ansehen, zwischen Häusern wechseln, einzelne Ventile starten und stoppen, Stop-All, Sensoren prüfen und App-Einstellungen verwalten. Alle interaktiven Elemente haben ein aussagekräftiges Label, einen Steuerelement-Typ und – wo sinnvoll – einen Hint, der die Aktion beschreibt. Rein dekorative Icons sind vor VoiceOver versteckt, damit Ansagen kurz bleiben.

Aktivieren: Einstellungen → Bedienungshilfen → VoiceOver.

### Sprachsteuerung
Die Sprachsteuerung profitiert von derselben Beschriftung wie VoiceOver. Jedes tappbare Element in den oben genannten Aufgaben kann per Name aktiviert werden. Das Label entspricht dem, was VoiceOver ansagt.

Aktivieren: Einstellungen → Bedienungshilfen → Sprachsteuerung.

### Größerer Text
Garden Fleets Layouts wurden bis zur größten Bedienungshilfen-Schriftgröße (AX5) geprüft. Haus-Bezeichner, Sensor-Cards, Ventil-Zeilen und Detail-Ansichten dehnen sich aus und brechen um, statt abzuschneiden oder zu überlappen. Der Header-Bereich des aktiven Hauses arrangiert sich um, damit Hausname und Wetter-Anzeige nicht mehr um denselben Platz konkurrieren.

Aktivieren: Einstellungen → Bedienungshilfen → Anzeige & Textgröße → Größerer Text.

### Dunkles Erscheinungsbild
Garden Fleet übernimmt das System-Farbschema von iOS. Sobald du das System auf Dunkel umstellst, gilt das konsistent in allen Bereichen der App.

Aktivieren: Einstellungen → Anzeige & Helligkeit → Dunkel, oder Einstellungen → Bedienungshilfen → Anzeige & Textgröße → „Farben ohne Verschlechterung umkehren" / „Klassisch umkehren" für eine systemweite Invertierung.

### Identifikation ohne Farbe
Zu jedem Haus kann zusätzlich zur Akzentfarbe ein eigenes SF-Symbol gewählt werden (Haus, Blatt, Baum, Berge, Gebäude, Sonnenschirm). Das Symbol erscheint in der Haus-Pille, im Sensor-Strip-Kennzeichner und über dem aktiven Seiten-Indikator-Punkt. Wer Farben schlecht unterscheidet, erkennt jedes Haus dadurch eindeutig am Symbol und am Namen.

Wähle ein Symbol beim Anlegen eines neuen Hauses oder in „Haus bearbeiten" für ein bestehendes Haus.

### Ausreichender Kontrast
Garden Fleet nutzt System-Textfarben und kontrast-bewusste Materialien in allen primären Interface-Elementen. Sie passen sich automatisch an, sobald „Kontrast erhöhen" aktiv ist. Die Akzentfarben für Haus-Pillen sind dort, wo Text auf Header-Bildern liegt, mit dunklerem Overlay unterlegt, damit der WCAG-AA-Kontrastwert erhalten bleibt.

Aktivieren: Einstellungen → Bedienungshilfen → Anzeige & Textgröße → Kontrast erhöhen.

### Reduzierte Bewegung
Animationen in Garden Fleet basieren auf den SwiftUI-Standardübergängen, die die Einstellung „Bewegung reduzieren" respektieren und entsprechend verkürzen oder abschalten. Der horizontale Page-Swipe zwischen Häusern, der Splash-Übergang und alle automatisch schließenden Sheets verhalten sich dann weniger abrupt.

Aktivieren: Einstellungen → Bedienungshilfen → Bewegung → Bewegung reduzieren.

## Nicht unterstützt

### Untertitel
**Nicht anwendbar.** Garden Fleet zeigt keine Audio- oder Videoinhalte. Es gibt weder Sprachausgabe noch Geräusche, die Informationen vermitteln; Untertitel sind daher nicht erforderlich.

### Audiodeskriptionen
**Nicht anwendbar.** Garden Fleet zeigt keine Videoinhalte. Es gibt keine bewegten Bilder, die Informationen vermitteln; Audiodeskriptionen sind daher nicht erforderlich.

## Bekannte Lücken und nächste Schritte

- Das erste Release wurde noch nicht mit Menschen aus der blinden/sehbehinderten Community im Feldtest geprüft. Wir planen, externe Tester nach dem Public Release per TestFlight einzuladen und auf echtem User-Feedback in folgenden Versionen zu iterieren.
- Live Activities, Widgets und ein watchOS-Pendant sind auf der Roadmap. Wenn sie kommen, durchlaufen sie dieselbe Accessibility-Validierung wie die Haupt-App.
- App Intents für Siri / Kurzbefehle / Voice Shortcuts sind in einer kommenden Version geplant. Damit lässt sich Garden Fleet komplett per Stimme bedienen – Ventile starten/stoppen, Häuser wechseln.

## Feedback zur Barrierefreiheit

Wenn du auf ein Accessibility-Problem stößt oder einen Vorschlag zur Verbesserung hast, melde dich bitte über die Kontaktdaten in [IMPRESSUM.md](IMPRESSUM.md). Wir behandeln solche Meldungen mit hoher Priorität.
