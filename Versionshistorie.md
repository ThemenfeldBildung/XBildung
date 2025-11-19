**XBildung - Versionshistorie**

<!-- TOC start -->

- [Version 1.2](#version-12)
- [Version 1.1](#version-11)
- [Version 1.0](#version-10)
- [Version 0.95](#version-095)

<!-- TOC end -->

<!-- TOC --><a name="version-12"></a>
# Version 1.2

**Veröffentlichungsdatum:** 28.10.2025

## Änderungen im Kontext der XÖV-Zertifizierung

Im Kontext des Antrags zur XÖV-Zertifizierung wurden einige Änderungen vorgenommen um Konformität zu den Kriterien des XÖV-Handbuchs und des XÖV-Codelisten-Handbuchs herzustellen.

## Änderungen an Codelisten

Die Codeliste Art des Schulabschlusses wurde aktualisiert, wodurch die Beschreibung und die Werte der Codeliste angepasst wurden. Grundlage ist nun das Merkmal Schulabschlüsse (BILAG1) des Statistischen Bundesamtes (Destatis). Die bisherige Referenz auf die Fachserie 11, Reihe 1, 2009/10 wurde ersetzt.

## Erweiterung der Klasse Benotung

Die Klasse Benotung wurde um die Eigenschaft beschreibung erweitert. Das Feld soll genutzt werden, um unstrukturierte Informationen über die Note zu übermitteln. Die Angabe einer Beschreibung zur Note ist optional.

## Liste der umgesetzten Tickets

Folgende (intern dokumentierte) Tickets wurden umgesetzt:

- XBD-436: Codeliste 'Art des Schulabschlusses' aktualisieren
- XBD-455: Lizenzangabe und Copyright Claim anpassen
- XBD-468: Codeliste 'Erreichbarkeit' aktualisieren
- XBD-470: Codelisten: fehlende Language-Metadaten hinzufügen (NDR-33/K-11)
- XBD-471: Codelisten-Metadaten unverändert übernehmen (NDR-22)
- XBD-475: Metadaten des Standards anpassen (K7, Beschreibung)
- XBD-478: bereitgestellte Artefakte autonom validieren
- XBD-479: Abweichungen von Kernkomponenten im Modell dokumentieren
- XBD-483: Klasse 'Benotung' um Eigenschaft 'beschreibung' erweitern
- XBD-488: Modell auf gültige XÖV-Konfiguration aktualisieren, XÖV-Profil auf 3.0.3 umstellen

<!-- TOC --><a name="version-11"></a>
# Version 1.1

**Veröffentlichungsdatum:** 04.02.2025

## Änderungen an Codelisten

Die Codeliste Lernzeitmodell, die bisher in XHochschule verwendet wurde, ist aufgrund übergreifender Relevanz nun in XBildung eingebunden und kann durch alle Teilvorhaben nachgenutzt werden. Das Mapping auf die europäischen ELM-Werte für Teilzeit und Vollzeit wurde wieder aufgenommen und die Beschreibung überarbeitet.

Die Codeliste Art der Bemerkung, die zuvor sowohl in XSchule wie auch in XBerufsbildung mit unterschiedlichen Werten Verwendung fand, ist nun unter Vereinigung der Werte aus beiden Teilvorhaben in XBildung eingebunden und kann durch die Teilvorhaben nachgenutzt werden. Sie wurde um die Werte \"Beurteilung Sozialverhalten\", \"Beurteilung Arbeitsverhalten\" und \"längerfristige Befreiung\" erweitert. Der bestehende Eintrag \"Allgemeine Beurteilung\" wurde in \"Beurteilung Allgemein\" umbenannt.

Die Codeliste Gesetzlicher Vertreter, die bisher in XSchule wie auch in XBerufsbildung unter Rückgriff auf die Listenwerte des DSMeld verwendet wurde, ist nun zentral in XBildung eingebunden und kann durch die Teilvorhaben nachgenutzt werden.

Die Codelisten ISCED-F-2013 und Language wurden auf die aktuelle Fassung gebracht.

Die Versionierung der Codelisten Art der Bemerkung und Lernzeitmodell wurde auf \"2025-02-04\" geändert und das Vorgehen für die Versionsbezeichnung im Kapitel II.3 Code-Datentypen erklärt.

Der Bezugsort der vom EU Publications Office herausgegebenen Codelisten wurde im Modell vereinheitlicht.

Die Codeliste Bewertungsschema wurde um einen Eintrag ergänzt, der die alternative Repräsentation von Hochschulnoten nach dem Schema A-F umfasst.

## Bereitstellung einer Nonce in Klasse Dokument

Entsprechend einer Stakeholder-Anforderung wurde für die Klasse Dokument, und damit für alle in den Teilvorhaben bereitgestellten Nachweise, die Möglichkeit zur Angabe einer Nonce für den sicheren Datentransport bereitgestellt.

## Sonstige Änderungen

Elemente aus XBildung werden mit dem zugehörigen Namespace verwendet.

In Wichtige Hinweise zur Implementierung wurde der Abschnitt zur Relevanz von Schematron überarbeitet.

Das Kapitel Grundlegende Designentscheidungen wurde in die Einleitung verschoben und mit neuen Verweisen auf die Registermodernisierung (RegMo) und die Single Digital Gateway Verordnung (SDG) überarbeitet. Zusätzlich wurde die dazugehörige Grafik überarbeitet.

## Liste der umgesetzten Tickets

Folgende (intern dokumentierte) Tickets wurden umgesetzt:

- XBD-390: XBD Präfixe einbinden
- XBD-392: Abgrenzung der Pre-Releases und Releases im Wording festlegen
- XBD-393: Codeliste \"Gesetzlicher Vertreter\" über XBD einbinden
- XBD-396: Lizenzangaben in GitHub ergänzen
- XBD-399: Pre-Release-Tag in GitHub einführen
- XBD-401: Codelisten-Kennungen überprüfen und anpassen
- XBD-403: XBildung als Standard-Eigentümer im XRepository angeben
- XBD-405: Codeliste \"Art der Bemerkung\" zusammenführen und in XBD einbinden
- XBD-406: Codelisten \"ISCED-F-2013\", \"Language\" auf neue Version updaten
- XBD-419: Anpassung des Abschnitts zu \"Schematron\" in Spezifikation
- XBD-421: Feld auf Ebene \"Dokument\" / Nonce bereitstellen
- XBD-422: Codeliste \"Lernzeitmodell\" von XHS auf XBD umziehen
- XBD-424: Vereinheitlichung von Listen des EU Publications Office
- XBD-426: Codeliste ArtDerBemerkung: neue Werte aufnehmen
- XBD-427: Codeliste Lernzeitmodell: Mapping auf PO aufnehmen
- XBD-429: Codeliste \"ArtDerBemerkung\" um \"längerfristige Befreiung\" erweitern
- XBD-437: Alternative Repräsentation von \"note\"
- XBD-438: Kapitel \"Grundlegende Designentscheidungen\" überarbeiten
- XBD-443: Versionierung von Codelisten an neue Systematik anpassen

---

<!-- TOC --><a name="version-10"></a>
# Version 1.0

**Veröffentlichungsdatum:** 14. Mai 2024

## Neues Konzept zur Einbindung von Kernkomponenten

Die XÖV-Kernkomponenten wurden aus XBildung entfernt, da sie zukünftig von den Vorhaben XSchule, XHochschule und XBerufsbildung direkt über die XÖV-Bibliothek eingebunden werden. Ausnahmen bilden die Kernkomponenten Zeitraum und Ortsangabe (ehemals Geburtsort, basierend auf Anschrift), diese verbleiben im Modell von XBildung.

Ortsangabe, bestehend aus Ort und Staat, wird als reduzierte Anschrift genutzt. Sie ersetzt in Dokument und Praktikum die bisherige Angabe des Orts als Text.

## Änderungen an Codelisten

Es wurden Vereinheitlichungen an einigen Codelisten vorgenommen. So wurde unter anderem für Code.ArtDerTraegerschaft auf sprechende Werte umgestellt. Des Weiteren stimmen bei den Codelisten nun die Paketnamen mit der Kennung überein.

Aus der Kennung lässt sich zudem der URI-Pfad ableiten. Daher wurden in den Codelisten Code.ArtDerSchule und Code.ArtDesSchulabschlusses die URIs der Codelistenwerte angepasst. Außerdem erfolgte für Code.ArtDerSchule eine Anpassung der Beschreibung mit Verweis auf die Verwendung von Version 4.0 des KDS (Kerndatensatzes).

## Ergänzung der Klasse Benotung um XBBD-spezifische Informationen

Die Klasse Benotung wurde um Elemente erweitert, um spezifische Prüfungsleistungen aus dem Kontext der Berufsbildung abbilden zu können. Die Beschreibung wurde entsprechend angepasst.

## Inhaltliche Änderungen an der Spezifikation

Die Spezifikation wurde textlich überarbeitet und inhaltlich konkretisiert. Zudem wurde der Spezifikation ein neues Kapitel Wichtige Hinweise zur Implementierung hinzugefügt. Das Kapitel enthält einen Link zu Anweisungen für die Validierung mit Schematron. Die XBildung-Journey sowie Glossar und Abkürzungsverzeichnis wurden überarbeitet.

## Sonstige Änderungen

Die Eigenschaften der Klassen Benotung, Dokument, Ortsangabe, Praktikum und TeilbekanntesDatum wurden als \"Unqualified\" ausgezeichnet, was es Teilmodulen ermöglicht, eingeschränkte Versionen dieser Klassen zu verwenden.

Die Klasse Kurs wurde aus XBildung entfernt, da sie von den einzelnen Teilvorhaben direkt umgesetzt wird. Die Klasse Abschlussarbeit wurde gelöscht, da sie in keinem Vorhaben verwendet wurde.

In der Klasse Dokument wurde die Eigenschaft gueltigkeitszeitraum vom Typ xbd:zeitraum ersetzt durch neue Eigenschaft gueltigkeitsdatum vom Typ W3C/date.

Es wurde eine Redirect-URL erstellt, die auf die aktuelle Version verweist. Daher ist die jeweils aktuelle Release-Version von XBildung ab jetzt verfügbar unter den URLs: <https://xbildung.de/def/xbildung/aktuell/> und <https://xbildung.de/def/xbildung/current/>

Die Menge der zulässigen Schriftzeichen für das Freitext-Element Ort im komplexen Datentyp Ortsangabe wurde von DIN 91379 Datentyp B auf Datentyp C erweitert. Der technische Datentyp C wurde für alle normativen Schriftzeichen der DIN 91379 entworfen. Griechische oder kyrillische Buchstaben sowie erweiterte (nicht-normative) Nicht-Buchstaben sind unzulässig.

## Liste der umgesetzten Tickets

Folgende (intern dokumentierte) Tickets wurden umgesetzt:

- XBD-397: Seite zur XML-Validierung in allen Teilvorhaben harmonisieren
- XBD-395: Ortsangabe Typ von datatypeB auf datatypeC ändern
- XBD-394: Dokumentation der Klasse Benotung ergänzen
- XBD-386: Beziehungen zu 2019-03 entfernen
- XBD-381: Codelisten mit Status Vorentwurf im XRepository prüfen
- XBD-380: Klasse Abschlussarbeit löschen
- XBD-378: Nachlaufende Tasks aus neuem Kapitel \"Hinweise zur Implementierung\" dokumentieren
- XBD-376: Codelisten aus Kernkomponenten ggf. löschen
- XBD-374: Journey - Tabelle und Graphik überarbeiten
- XBD-371: Codeliste ArtDerTraegerschaft auf sprechende Werte umstellen
- XBD-365: Kernkomponenten entfernen
- XBD-360: Kennung der Codeliste ArtDesSchulabschlusses prüfen
- XBD-358: Gültigkeitszeitraum-Ende aus Klasse Dokument entfernen
- XBD-357: Kursstatus Beschreibung konkretisieren
- XBD-355: Neues Kapitel \"Ausstellen und Einlesen von XML-Instanzen\" erstellen
- XBD-353: Versionierung von Codelisten prüfen und ggf. anpassen
- XBD-352: Codeliste ArtDerSchule mit KDS (Kerndatensatz) Version 4.0 abgleichen und anpassen
- XBD-349: Redirect-URL auf aktuelle XBD-Spezifikation erstellen/anpassen
- XBD-290: EQF in das Glossar aufnehmen
- XBD-288: Im src-Ordner aufräumen
- XBD-287: Notwendigkeit von XÖV-Codeliste Verzeichnisdienste prüfen
- XBD-282: Codeliste ArtDerSchule auf sprechende Werte umstellen
- XBD-258: Eigenschaften auf Unqualified setzen um Fachmodulen Restrictions zu ermöglichen
- XBD-231: Leere Mapping-Werte nicht als preflabel kennzeichnen
- XBD-218: Spezifikation inhaltlich schärfen
- XBD-55: RDF-Ausspielung bei Codelisten optimieren

---

<!-- TOC --><a name="version-095"></a>
# Version 0.95

**Veröffentlichungsdatum:** 10. Juli 2023

**Veränderungen zur vorherigen Version:** Schwerpunkt war das einheitliche Vorgehen für String-basierte Datentypen. Im Detail:

- XBD-251: Codeliste Erreichbarkeit auf Typ 2 umstellen
- XBD-248: Typ-4-Codelisten mit Typ 2 bzw. 3 ersetzen
- XBD-247: Codeliste Geschlecht aus XInneres verwenden
- XBD-276: Standard-Codes in Codelisten überarbeiten
- XBD-283: Version der Codeliste CEFR aktualisieren
- XBD-281: Version der Codeliste Language aktualisieren
- XBD-255: EQF als Feld einbauen
- XBD-222: Vereinheitlichung der Modellierung und Codelisten für Staat und Staatsbürgerschaft
- XBD-285: xbd:Sprache ausbauen, stattdessen immer direkt Code.Language verwenden
- XBD-235: Vereinheitlichen der Datentypen für Zeichenketten
- XBD-277: Änderungen der Kardinalität von String.Localized-Eigenschaften
- XBD-256: Verwendung von xs:ID überarbeiten
- XBD-286: Häufigkeit von Sprache in xbd:Dokument auf 1..1 setzen
- XBD-146: Reihenfolge der Eigenschaften in Kernkomponenten gemäß Vorgabe nutzen
- XBD-275: Praktikum aufnehmen
- XBD-243: xbd:identifikation aus xbd:Dokument entfernen
- XBD-250: Geburt:datum auf TeilbekanntesDatum umstellen
- XBD-279: Metadaten zur Konfiguration im Modell aktualisieren
- XBD-167: spezifikation.ent-Dateien anpassen an XHS-Format
- XBD-246: Metadaten der Codeliste ArtDerSchule\" ausbessern
