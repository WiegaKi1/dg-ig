<!--
  Startseite des IG
-->

### Use Case

Eine Hausarztpraxis erfasst Arzneimittelallergien ihrer Patientinnen und Patienten strukturiert und mit Codes.
Eine Notfallstation liest diese Angaben, um rasch zu erkennen, welche Medikamente gefährlich sind und wie schwer eine Reaktion ausfallen kann.

### Scope

Dieses IG deckt Allergien und Intoleranzen gegen Arzneimittel ab (AllergyIntolerance mit category = medication), erfasst von einer Ärztin oder einem Arzt.
Nicht abgedeckt sind Allergien gegen Nahrungsmittel, Umweltstoffe oder biologische Stoffe sowie die Behandlung einer Reaktion.

### Artefakte

* [DG Arzneimittelallergie](StructureDefinition-dg-medication-allergy.html): Profil auf Basis von CH Core AllergyIntolerance mit den Regeln für Arzneimittelallergien und der Invariante dg-allergy-1 (bestätigte Allergie braucht eine Reaktion).
* [Penicillinallergie Anna Muster](AllergyIntolerance-PenicillinAllergieAnna.html): Beispiel einer bestätigten Penicillinallergie mit Urtikaria, erfasst von Dr. med. Sara Keller.

### Abhängigkeiten

Dieses IG baut auf [CH Core 6.0.0](https://fhir.ch/ig/ch-core/6.0.0/) auf.

### Autorin oder Autor

Kim Wiegand

<p style="font-size:smaller">Erstellt im Lab des Moduls Data Standards in Healthcare, ZHAW, HS26. Kein offizieller Standard.</p>
