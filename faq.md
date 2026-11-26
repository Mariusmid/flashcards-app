---
title: FlashCards – Häufige Fragen
description: Antworten auf häufige Fragen zu FlashCards, zu Lernen mit FSRS, KI-Karten, Import und iCloud-Sync.
---

# Häufige Fragen

Hier findest du Antworten rund um FlashCards. Fehlt etwas? Dann schreib mir über den [Support](support.html).

## Erste Schritte

<details markdown="1">
<summary>Wie bekomme ich FlashCards?</summary>

FlashCards ist gerade als öffentliche Beta verfügbar. Installiere auf deinem iPhone, iPad oder Mac die App [TestFlight](https://apps.apple.com/de/app/testflight/id899247664) von Apple und öffne dann diesen Link: [https://testflight.apple.com/join/Hp9zpBBu](https://testflight.apple.com/join/Hp9zpBBu). Der Start im App Store folgt.

Feedback zur Beta kannst du direkt in TestFlight senden oder mir per [E-Mail](support.html) schicken.
</details>

<details markdown="1">
<summary>Wie fange ich an?</summary>

Lege einen Stapel an, darin ein Kapitel, und füge Karten hinzu. Oder importiere vorhandene Karten über „Importieren …“. Mit „Üben“ lernst du alle Karten, die heute anstehen.
</details>

<details markdown="1">
<summary>Was bedeuten „neu“, „nochmal“ und „fällig“?</summary>

- <span class="c-new">neu</span> (blau): Karten, die du noch nicht gelernt hast.
- <span class="c-again">nochmal</span> (rot): Karten, die du gerade lernst oder vergessen hast und jetzt wiederholen sollst.
- <span class="c-due">fällig</span> (orange): gelernte Karten, deren Wiederholung heute ansteht.

Jede Karte zählt immer nur in einem dieser drei Töpfe.
</details>

<details markdown="1">
<summary>Was sind Tageslimits und die Ziel-Merkquote?</summary>

Pro Stapel legst du fest, wie viele neue Karten und wie viele Wiederholungen du höchstens an einem Tag lernen möchtest (Standard: 20 neue, 200 Wiederholungen). Die Ziel-Merkquote (70 bis 97 %, Standard 90 %) bestimmt, wie sicher du eine Karte noch können sollst, wenn sie wiederkommt. Höher heißt: öfter wiederholen, dafür weniger vergessen.

Die Startwerte für neue Stapel stellst du in den Einstellungen unter „Neue Stapel“ ein.
</details>

<details markdown="1">
<summary>Wie bewerte ich eine Karte?</summary>

Nach dem Aufdecken wählst du „Nochmal“, „Schwer“, „Gut“ oder „Leicht“. Danach berechnet FlashCards, wann die Karte wiederkommt.
</details>

<details markdown="1">
<summary>Kann ich einen Stapel oder ein Kapitel pausieren?</summary>

Ja. Ein pausierter Stapel oder ein pausiertes Kapitel bleibt sichtbar und bearbeitbar, kommt aber nicht ins Üben. Ein pausierter Stapel pausiert alle seine Kapitel.
</details>

## Lernen mit FSRS

<details markdown="1">
<summary>Was ist FSRS?</summary>

FSRS (Free Spaced Repetition Scheduler) ist ein moderner Algorithmus für verteiltes Wiederholen. Er schätzt für jede Karte, wie gut du sie noch weißt, und legt sie dir kurz vor dem Vergessen wieder vor. So behältst du mehr mit weniger Lernzeit. Anki nutzt denselben Algorithmus.
</details>

<details markdown="1">
<summary>Was macht „Lernabstände optimieren“?</summary>

Hast du genug gelernt (mindestens 400 auswertbare Antworten), kann FlashCards die FSRS-Parameter an deine eigene Lernhistorie anpassen. Die neuen Werte werden nur übernommen, wenn sie deine bisherigen Antworten besser vorhersagen. Du findest die Funktion in den Einstellungen unter „Lernabstände“.
</details>

## Karten mit KI erstellen

<details markdown="1">
<summary>Wie erstellt FlashCards Karten aus meinen Unterlagen?</summary>

Wähle eine PDF- oder Textdatei, zum Beispiel Vorlesungsfolien. Apple Intelligence liest den Inhalt direkt auf deinem Gerät und schlägt Lernkarten vor, nach Kapiteln sortiert. Du siehst alle Vorschläge vorher, kannst sie bearbeiten oder verwerfen und entscheidest, was in deinen Stapel kommt.
</details>

<details markdown="1">
<summary>Warum kann ich keine Karten mit KI erzeugen?</summary>

Die Generierung braucht ein Gerät, das Apple Intelligence unterstützt, und Apple Intelligence muss in den Systemeinstellungen eingeschaltet sein. Nach dem Einschalten lädt das System das Modell eventuell erst herunter. Die App zeigt dir den genauen Grund an.

Ohne Apple Intelligence kannst du „Mit eigener KI erstellen“ nutzen (siehe nächste Frage).
</details>

<details markdown="1">
<summary>Wie funktioniert „Mit eigener KI erstellen“?</summary>

1. Wähle den Ziel-Stapel und tippe auf „Prompt kopieren“.
2. Füge den Prompt in eine KI deiner Wahl ein, etwa ChatGPT, Claude oder Gemini, zusammen mit deinem Lernstoff.
3. Kopiere die Antwort der KI und füge sie in FlashCards ein. Du siehst sofort eine Vorschau.
4. Tippe auf „Karten anlegen“.

FlashCards selbst sendet dabei nichts. Was du in die KI einfügst, entscheidest du. Mit den Kurzbefehlen „KI-Prompt für Karten“ und „Karten hinzufügen“ lässt sich das auch automatisieren.
</details>

<details markdown="1">
<summary>Werden meine Unterlagen ins Internet hochgeladen?</summary>

Nein. Die Generierung mit Apple Intelligence läuft auf deinem Gerät. Weder der Entwickler noch Dritte bekommen deine Dateien.
</details>

## Import und Export

<details markdown="1">
<summary>Welche Formate kann ich importieren?</summary>

| Quelle | Format |
|---|---|
| Anki | Pakete `.apkg` und `.colpkg`, inklusive Bildern |
| Mochi | `.mochi` |
| Quizlet | Set exportieren und den Text in FlashCards einfügen |
| Tabellen | CSV oder Text mit Trennzeichen, Excel `.xlsx` |
| Word | Tabellen in `.docx` |
| Notizen | Markdown aus Obsidian, Logseq und RemNote |
| FlashCards | JSON-Kartenformat |

Öffne „Importieren …“ und wähle die passende Zeile. Jeder Import legt einen neuen Stapel an.
</details>

<details markdown="1">
<summary>Was wird aus Anki übernommen?</summary>

Vorder- und Rückseiten (auch Lückentexte), Stapelstruktur und Bilder. Töne werden nicht übernommen, und alle Karten starten in FlashCards als neu. Dein Lernfortschritt aus Anki wird also nicht mitgenommen.
</details>

<details markdown="1">
<summary>Wie importiere ich ein Quizlet-Set?</summary>

Öffne das Set in Quizlet, wähle „Exportieren“ und kopiere den Text. In FlashCards gehst du auf „Importieren …“ → „Quizlet“, fügst den Text ein und wählst dieselben Trennzeichen wie in Quizlet.
</details>

<details markdown="1">
<summary>Wie sichere ich meine Karten?</summary>

Über „Sicherung exportieren“ speicherst du alle Stapel, Karten, Bilder und den Lernfortschritt in eine Datei. Mit „Sicherung wiederherstellen“ holst du sie zurück, wahlweise zusätzlich zu deinen Karten oder als vollständiger Ersatz.
</details>

## Bilder

<details markdown="1">
<summary>Wie füge ich Bilder in eine Karte ein?</summary>

Im Karteneditor über „Bild einfügen“: aus Fotos, mit der Kamera (iPhone und iPad), aus einer Datei oder aus der Zwischenablage. Auf dem Mac kannst du Bilder auch einfach in das Textfeld ziehen. Beim Lernen tippst du auf ein Bild, um es zu vergrößern.
</details>

<details markdown="1">
<summary>Belegen Bilder viel Speicher?</summary>

FlashCards verkleinert Bilder beim Einfügen auf höchstens 1600 Pixel an der längsten Seite und entfernt Metadaten wie den Aufnahmeort. Bilder werden mit iCloud abgeglichen und zählen dort zu deinem eigenen Speicher.
</details>

## iCloud und Geräte

<details markdown="1">
<summary>Wie synchronisiere ich iPhone, iPad und Mac?</summary>

Melde dich auf allen Geräten mit demselben Apple Account bei iCloud an. FlashCards gleicht Karten, Lernfortschritt und wichtige Einstellungen automatisch ab. Nach Änderungen kann das einige Minuten dauern. Den Status siehst du in den Einstellungen unter „iCloud-Sync“.
</details>

<details markdown="1">
<summary>Mein iCloud-Speicher ist voll. Was passiert?</summary>

Deine Karten bleiben auf dem Gerät erhalten, werden aber nicht mehr abgeglichen. FlashCards zeigt dann einen Hinweis an. Gib Speicher frei oder erweitere ihn, danach geht der Abgleich von selbst weiter.
</details>

<details markdown="1">
<summary>Welche Geräte werden unterstützt?</summary>

iPhone und iPad mit iOS bzw. iPadOS 26.5 oder neuer sowie Macs mit macOS 26.5 oder neuer. Für die KI-Generierung braucht es zusätzlich ein Gerät mit Apple Intelligence.
</details>

## Datenschutz

<details markdown="1">
<summary>Brauche ich ein Konto?</summary>

Nein. FlashCards hat kein eigenes Konto und keine Anmeldung. Für den Abgleich nutzt die App nur dein bestehendes iCloud.
</details>

<details markdown="1">
<summary>Welche Daten sammelt FlashCards?</summary>

Keine. Es gibt keine Werbung, kein Tracking und keine Analyse. Details stehen in der [Datenschutzerklärung](datenschutz.html).
</details>

<details markdown="1">
<summary>Wie lösche ich meine Daten?</summary>

Stapel, Kapitel und Karten löschst du direkt in der App. Die Daten in iCloud entfernst du auf dem iPhone unter Einstellungen → tippe oben auf deinen Namen → iCloud → Speicher verwalten → FlashCards. Auf dem Mac findest du dasselbe unter Systemeinstellungen → Apple Account → iCloud → Verwalten.
</details>
