<!--
  Schritt 7: Startseite eures IG
  Ersetzt die TODOs durch eigenen Text. Markdown ist erlaubt.
  Diese Seite ist die erste, die man auf GitHub Pages sieht.
-->

### Use Case

Eine Hausarztpraxis erfasst Arzneimittelallergien so, dass die Notfallstation sie zuverlässig auswerten kann. Die Hausärztin oder der Hausarzt dokumentiert die Allergie, die Notfallstation liest sie, um bei Notfällen keine gefährlichen Medikamente zu verabreichen.

### Scope

Dieses IG deckt ausschliesslich Allergien gegen Arzneimittel ab (Profil auf Basis von CH Core AllergyIntolerance). Nahrungsmittel-, Umwelt- und andere Allergien sowie Unverträglichkeiten sind bewusst nicht abgedeckt.

### Artefakte

* [DG Arzneimittelallergie](StructureDefinition-dg-medication-allergy.html): Profil für Arzneimittelallergien mit Pflichtangaben zu Status, Code, Kritikalität, Beginn, Erfasser und Reaktion.
* [Penicillinallergie von Anna Muster](AllergyIntolerance-PenicillinAllergieAnna.html): Beispiel einer bestätigten Penicillinallergie mit Reaktion.

### Abhängigkeiten

Dieses IG baut auf [CH Core 6.0.0](https://fhir.ch/ig/ch-core/6.0.0/) auf.

### Autorin oder Autor

TODO: Euer Name.

<p style="font-size:smaller">Erstellt im Lab des Moduls Data Standards in Healthcare, ZHAW, HS26. Kein offizieller Standard.</p>
