# Mein Liebesbrief an die IT-Systemtechnik

## Ausbildungsinhalte

* Erwartungen und Bedürfnisse der Kundinnen und Kunden zur Funktionsweisen und Anforderungen an die IT-Systeme und Geräte abstimmen; insb. Sicherheitsanforderungen
* Kundinnen und Kunden über mögliche IT-System-Lösungen beraten
* bei Planung und Aufbau neuer Umgebungen und Lösungen mitarbeiten
* Umsetzungskonzept und Zeit-, Kosten- und Projektplan erstellen
* Benutzerend- und Peripheriegeräte, Komponenten auswählen, bereitstellen, konfigurieren (einrichten), synchronisieren
* neue Netzkomponenten auswählen und in Betrieb nehmen
* Serversysteme entwickeln, installieren (inkl. Serverraum), konfigurieren
* Serversysteme bereitstellen und administrieren
* Cloud-Dienste, Datenspeichersysteme, Backup-Lösungen installieren und einrichten
* Berechtigungskonzepte erstellen und umsetzen, Benutzerschnittstellen einrichten
* Maßnahmen zur Datensicherheit, Datenschutz und evt. Datenverschlüsselung umsetzen
* Dienste zur Unterstützung von Gruppenarbeiten (Groupware) konfigurieren und in Betrieb nehmen
* Netzwerkdienste z. B. Content Management System (CMS), Schnittstellen einrichten
* Leistungsfähigkeit, Funktionssicherheit von Netzen prüfen und sicherstellen
* Wartungen und Reparaturen durchführen, Fehler beheben
* Arbeiten und Test dokumentieren, Benutzeranleitungen erstellen, NutzerInnen einschulen
* Kundenservice anbieten und gegebenenfalls IT-Systeme erweitern

## Berufsinhalte

### Direkt am Arbeitsplatz / in der IT-Abteilung:

* Wartung und Reparatur von Arbeitsplatzrechnern: Diagnose und Behebung von Hard- und Softwareproblemen an den Computern der Mitarbeiter, Austausch defekter Komponenten.
* Installation und Konfiguration von Software: Installation von Betriebssystemen, Anwendungssoftware und Updates auf den Arbeitsplatzrechnern.
* Einrichtung und Betreuung von Peripheriegeräten: Anschließen, Konfigurieren und Warten von Druckern, Scannern und anderen Geräten.
* Benutzerunterstützung (First- und Second-Level-Support): Entgegennahme und Bearbeitung von Supportanfragen der Mitarbeiter bei technischen Problemen, Hilfestellung per Telefon, E-Mail oder persönlich.
* Netzwerkadministration im lokalen Netzwerk (LAN): Überwachung und Wartung der Netzwerkkomponenten, Fehlerbehebung bei Netzwerkproblemen im Büro.
* Sicherheitsmaßnahmen am Arbeitsplatz: Installation und Konfiguration von Virenschutzsoftware, Durchführung von grundlegenden Sicherheitsüberprüfungen an den Arbeitsplatzrechnern.
* Dokumentation: Erstellung von Anleitungen und Dokumentationen für Benutzer und interne IT-Prozesse.
* Inventarisierung: Erfassung und Verwaltung der vorhandenen IT-Hardware und -Software am Arbeitsplatz.
* Durchführung von Schulungen: Einweisung neuer Mitarbeiter in die IT-Systeme und Schulung in der Nutzung spezifischer Software.
* Im Serverraum / Rechenzentrum (falls vorhanden):

* Wartung und Überwachung von Servern: Überprüfung der Serverhardware und -software, Austausch defekter Teile, Performance-Monitoring.
* Installation und Konfiguration von Serverbetriebssystemen und -anwendungen: Einrichtung und Wartung der zentralen Serverdienste.
* Netzwerkadministration der Serverinfrastruktur: Konfiguration und Wartung von Switches, Routern und Firewalls im Serverbereich.
* Datensicherung und -wiederherstellung: Durchführung geplanter Backups und Wiederherstellung von Daten im Fehlerfall.
* Zugriffsverwaltung und Benutzerkontenpflege: Anlegen und Verwalten von Benutzerkonten und Zugriffsrechten auf Server und Netzwerkressourcen.
* Implementierung und Überwachung von Sicherheitsrichtlinien auf Serverebene: Konfiguration von Sicherheitseinstellungen und Überwachung auf Bedrohungen.

### Ortsunabhängig / Remote:

* Fernwartung: Zugriff auf Systeme und Arbeitsplatzrechner zur Fehlerbehebung und Unterstützung der Benutzer aus der Ferne.
* Überwachung von Systemen und Netzwerken: Einsatz von Monitoring-Tools zur frühzeitigen Erkennung von Problemen, auch außerhalb der regulären Arbeitszeiten.
* Bearbeitung von Tickets im Supportsystem: Abarbeiten von Supportanfragen, die über ein Ticketsystem eingegangen sind.
* Planung und Vorbereitung von IT-Projekten: Erstellung von Konzepten und Durchführung von Recherchen für neue IT-Lösungen.
* Erstellung von Dokumentationen und Berichten: Auch diese Aufgaben können oft remote erledigt werden.
* Beim Kunden vor Ort:

* Installation und Konfiguration von IT-Systemen beim Kunden: Aufbau und Inbetriebnahme von Hardware, Software und Netzwerken beim Kunden.
* Fehlerbehebung und Reparatur von Systemen beim Kunden: Diagnose und Behebung technischer Probleme direkt beim Kunden.
* Beratung und Schulung der Kunden: Unterstützung der Kunden bei der Auswahl und Nutzung von IT-Systemen.

### Meine Vorstellungen / meine liebsten Tätigkeiten

> Installation und Konfiguartion von Systemen (Windows, Linux, MacOS)

> Assemblierung und Reparatur von Endgeräten (Endgeräte - PC)

> Skripte / Programme schreiben
```python
# Python Libary Imports
from dataclassses import dataclass

@dataclass
class Character:
  """
  My Character Class.
  
  Arguments:
    full_name: [str] -> Full Name of Character as String
    age: [int] -> Age of Character as Int
    email: [str] -> Email of Character as String
    skills: [str] -> 
  Notes:
    - Here is a Single Note.
  
  Methods:
    func: (parameter: bool) -> This Function has no Usage.
  """
  full_name: str = 'Manuel Staufer'
  age: int = 26
  email: str = 'manuel.staufervb@gmail.com'
  skills: dict = {'Python': 'Advanced', 'Java': 'Basic'}

  def get_skills(self) -> None:
    for skill in self.skills:
      print(skill)
  
  def get_profile(self) -> list:
    return self.full_name, self.age, self.email, self.skills

if __name__ == '__main__':
  myself = Character()
  print(myself.get_profile())
  myself.get_skills()

```

## Author

> Manuel Staufer (username)
* [Github](https://github.com/mstvb)
* [BBRZ-Email](mailto::itn318670@qualifizierung.at)
* [Email](mailto::manuel.staufervb@gmail.com)

## License

Dieses Projekt benötigt keine License
