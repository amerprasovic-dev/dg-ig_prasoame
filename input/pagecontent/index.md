<!--
  Schritt 7: Startseite eures IG
  Ersetzt die TODOs durch eigenen Text. Markdown ist erlaubt.
  Diese Seite ist die erste, die man auf GitHub Pages sieht.
-->

### Use Case

Eine Hausarztpraxis erfasst Arzneimittelallergien von Patientinnen und Patienten strukturiert in ihrem System. Eine Notfallstation ruft diese Daten bei Bedarf ab und liest sie aus, um bei der Medikamentenabgabe im Notfall zuverlässig und schnell lebensbedrohliche allergische Reaktionen zu verhindern.

### Scope

Dieses IG deckt ausschliesslich die Dokumentation von Allergien gegen Arzneimittel (Medikamente) ab, einschliesslich deren Kritikalität und der aufgetretenen Reaktionen. Es deckt bewusst keine Lebensmittel-, Umwelt- oder Tierhaarallergien ab und enthält keine Regeln für die generelle Verschreibung von Medikamenten.

### Artefakte

- [DG Arzneimittelallergie](StructureDefinition-dg-medication-allergy.html): Das Profil definiert die zwingenden Regeln und Einschränkungen für das strukturierte Erfassen einer Arzneimittelallergie (Kardinalitäten, Must Support und Terminology Bindings).
- [Penicillin-Allergie von Anna Muster](AllergyIntolerance-PenicillinAllergieAnna.html): Ein konkretes und validiertes Beispiel einer bestätigten Penicillin-Allergie, welches alle Regeln des Profils und der Invariante erfüllt.

### Abhängigkeiten

Dieses IG baut auf [CH Core 6.0.0](https://fhir.ch/ig/ch-core/6.0.0/) auf.

### Autorin oder Autor

Amer Prasovic

<p style="font-size:smaller">Erstellt im Lab des Moduls Data Standards in Healthcare, ZHAW, HS26. Kein offizieller Standard.</p>