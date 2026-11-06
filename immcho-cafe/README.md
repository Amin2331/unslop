# IMMCHO Café · Website-Entwurf

Einseitige Website für das IMMCHO Café (Immermannstraße, Little Tokyo, Düsseldorf).
Kein Build: `index.html` im Browser öffnen (der Ordner `vendor/` muss daneben liegen).
`preview/scroll-demo.mp4` zeigt die Animation als Video.

## Was sich bewegt
- **Weiches Scrollen** mit Lenis, alle Scroll-Animationen mit GSAP ScrollTrigger (lokal in `vendor/`).
- **Das Iced-Matcha-Glas** (gezeichnetes SVG) wandert durch die Seite: Hero → schräg links neben dem Text →
  fixierte Zubereitung (leert sich, dann Eis, Milch, Matcha-Strahl, Strohhalm) → fliegt aus dem Bild →
  kommt im grünen Schluss zurück. Schnelles Scrollen lässt die Flüssigkeit schwappen und das Glas kippen.
- Text, der sich Wort für Wort aufhellt; Laufband, dessen Tempo und Richtung am Scrollen hängt;
  drehender Stempel; Papierkörnung; Menü, das über grünen Flächen hell wird.
- Mit „Bewegung reduzieren“ im Betriebssystem: ruhige Version ohne Scroll-Effekte.

## Bevor sie dem Inhaber gezeigt wird
- **Fotos:** Eigene Bilder als JPG in `assets/img/` ablegen, sie erscheinen automatisch:
  `hero.jpg`, `eingang.jpg`, `matcha-latte.jpg`, `strawberry-matcha.jpg`, `kuchen.jpg`,
  `hojicha.jpg`, `aufschlagen.jpg`, `raum.jpg`, `theke.jpg`, `detail.jpg`, `schale.jpg`.
  Fehlt eine Datei, zeigt die Fläche die grüne Kanji-Kachel.
- **Preise und Karte sind Annahmen** und müssen mit der echten Karte abgeglichen werden.
- **Öffnungszeiten** (täglich 11:00–19:30) stammen aus öffentlichen Einträgen, bitte bestätigen.
- Impressum und Datenschutz fehlen noch (Angaben des Betreibers nötig).
