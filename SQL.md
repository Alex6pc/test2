# Datenbanken
- Hierarchische Datenbanken
- Netzwerk-Datenbank
- Relationale Datenbanken
- Objektorientierte Datenbanken
- Objekt-Relationale Datenbanken
- Key-Value Stores
------
### Hierarchische Datenbanken

#### Einsatzgebiete
- Banken
- Einrichtungshäuser
- Fluggesellschaften 

#### Großrechner
- Performante IO-Operationen
- Multiprozessor System
- Batch-Betrieb
- Spezielle Großrechner-Betriebssyteme
- Programmiersprachen : PL/1, Großrechner-Assembler 


### Datenspeicher 
#### Tranisenz 
- Flüchtige Speicher
- Daten zur Laufzeit
- z.B. Daten im Hauptspeicher

#### Persistenz
- Dauerhafte Speicherung
- Daten existieren über die Dauer der Anwendung hinaus
- z.B. Daten auf dem Festspeicher (Dateien)





### Modellierung eines Fahrrads

- Informationen wird strukturiere gespeichert
- Informationen kann sehr schnell sequentiell gelesen werden, da die Daten zusammengehalten werden
- Nachteil: keine Mehrfach zu den Mehrfachbeziehung möglich! Lediglich hierarchische 1:N-Beziehung sind erlaubt


### Datenbanken im Client-Server-Umfeld
- Client Server Prinzip
- Server stellt DB-Dienst bereit
- Client nutzt diesen Dienst
- Client kann auf der gleichen Maschine laufen, wer der Server
- In der Regel -  Einsatz eines relationalen Datenbank-Servers (Oracle, MS-SQL, PostgreSQL, My
- SQL)














-------

## Logische Datennunabhängigkeit 
Die logische datenun



## Physikalische Datenunabhängigkeit
Unter der physikalischen Datenunabhängigkeit versteht man die 


### Allgemeinwissen IT
- Datenbanken existeren seit den fünziger Jahren. 
- Der erste PC von IBM wurde 1981 entwickelt. Da es keine Festplatten oder ähnliches gab wurden Lochkarten verwendet um ein Programm zu starten. 
- Filesysteme sind speicherorte für Daten 
- Datei sind dateisystem das aus mehreren komponenten besteht 
- Welchen zweck haben Dateien heute. gehören zu block orientierte geräte block device.
- Port ist eine Adresse für ein Programm 
- SQL = Strucure Query LAnguage (Idee Dr. Edgar Codd)
- 



Konzenption = Planung
Referienzelle integrität = Zusammenhang zweier Tabellen
Entitäten = Zeile einer Tabelle (erscheinung) abbildung
Entitätsmenge (Entity set) = ist noch keine Tabelle sondern der zwischenschirtt zur Planung einer Tabelle 
Attribut = Spaltenübershrift jedes einzelne Tabelle (überschrift)
Schlüssel= dient dazu die Id zu identifizieren

# PRÜFUNG !!!
### TCP IP !!!!!
### 1 Architekurmuster für die Grobe entwurf eines software Entwicklung
### 2 Entwurfmuster die feine struktur eines Softwareentwicklung Pattern


-----
# Datenbank
## Aufgabenliste: 1 (25.08.22)
### Aufgabe 1 
##### Vorteile hierarchische Datenbanken
- Informationen kann sehr schnell sequentiell gelesen und geschrieben werden.
- (Übersichtlichkeit) klare Struktur
- Eignung für Große Datenmengen
- Effizienter Zugriff auf Daten
- Sicherstellung hoher Integrität (zuverlässige und korrekte) durch Zusammenhalten von Information

##### Nachteile hierarchische Datenbanken
- Struktur muss den Nutzern bekannt sein
- Struktur ist nicht flexibel um anpassungen vorzunehmen 
- Es gib keine n:m-Beziehungen 


### Aufgabe 2
##### Warum wereden hierarchische Datenbanken eingesetzt?
- Wechsel häufig aufgrund von gewachsener Struktur nicht möglich 
- Banken
- Versicherungen
- Reisebüro
- Fluggesellschaften

### Aufgabe 3
##### Was bedeutet batch-betrieb?
- Batch: Stapelsystem 
 
##### Aus welchen Gründen kommt dieser zum Einsatz?
- Gründe: Sequentielle Verarbeitung von Vorgängen 

##### Wird dieses Prinzip noch verwendet?
-  Prinzip heute: z.B. Backup o.a. bei denen Befehle nacheinander ausgeführt werden 

### Aufgabe 4
##### Beispiele zur hierarchische Datenbanken aufbau und Richtung

										Abteilung
											   |
		----------------------------------------
		|                   |                   |
	Abt nur            Abt name             stadt


### Aufgabe 5
##### Was sind Dateien?
- Eine nach bestimmten Kriterien geordnete Amsammlung von Daten 
- Dateien sind Teil eines Dateisystems 
- Dateien sind logischer Natur - Verwaltung der Blöcke

##### Wozu werden Dateien im zusammenhang mit Datenbanken verwendet?
- Daten werden in form von Dateien abgelegt.

### Aufgabe 6
##### A) Was ist CSV-Format und wozu wird dies benötigt?
Datenaustauschformat in Textform


##### B) Erstellen Sie eine CSV-Datei für eine Telefon-E-Mail-Liste mit einem dafür geeigneten Tool
Alexandros;1736547954; alex-notis@outlook.com Chris;1733093490; Chris@me.de

##### C) Wie sieht die Struktur einer hierarchische Datenbanken für unsere Telefon-E-Mail-Liste aus?
								Telefonliste
										   | 
				---------------------------
				|	        |		      |
		Vorname      Telefon       E-mail

### Aufgabe 7
##### Transienz
Flüchtige Speicherung im Hauptspeicher 

##### Persistenz
Persistenz: Dauerhafte Speicherung


### Aufgabe 8 
##### A) Auf welche Weise können Sie über ein Netzwerk auf den Server zugreifen?
Netzwerks-Socket, denn Socket besteht aus IP-Adresse und Port

##### B) Wie unterscheidet sich ihr oben beschriebener Zugriff-technisch- von einem Mehrfach-Zugriff auf eine zentral bereit gestellte MS-Excel-Datei 

-----------

## Aufgabenblatt: 2 26.08.2022


## Aufgabe 1 : 
#### Was ist ein RDBMS und welche Aufgaben kommen diesen zu?
- Relationale Datenbank Management System 
Aufgaben: Verwalten von Datenbanken (Daten)

## Aufgabe 2 : 
#### A) Was ist unter Redundanz zu verstehen?
Redudanz: Mehrfachspeicherung von Daten 

#### B) Aus welchen Gründen bereitet Redundanz dem Administrator viel Arbeit? 
Inkonsistente (widerspruchsbehaftet) Daten

## Aufgabe 3 : 
#### Mit welchen Maßnahmen kann Redundanz eingedämmt werden?
Entfernen von mehrfach vorkommenden Daten
Normalisierte Tabellenstrukturen verwenden!

## Aufgabe 4 : 
#### Erläutern Sie den Unterschied zwischen Redundanz und Konsistenz! (mit Beispiele)
Redundanz: Mehrfachgespeicherte Daten 
Konsistenz: Widerspruchsfreiheit 
Wenn Mehrfach gespeicherte Informationen sich auch nur in einem Wert wiedersprechen liegen Inkonsistente Daten vor.
Bei jeder neuen Redundanz steigt das Risiko für Inkonsistenz

## Aufgabe 5 : 
#### Grenzen Sie die Begriffe:
##### Datenschutz: Schutz der Daten vor Zugriff von Dritten (Stichwort Datenschutzgesetz DSGVO)

##### Datensicherheit: Alle Maßnahmen, die ergriffen werden können um den Bestand der Daten in Zukunft sicherzustellen

##### Datensicherung: Backup
Datensicherheit und Datensicherung: Datensicherheit meint sämtliche Maßnahmen, die ergriffen werden können. Datensicherung (backup) ist genau eine davon, (updates), (mehrere Hardware)


## Aufgabe 6 :
#### Differenzieren Sie die Begriffe: 

##### Datenbank-System: hat die Komponenten: Datenbank, Datenbankserver (Service)

##### Datenbankserver: stellt Datenbank-Service bereit

##### Datenbank = Daten

##### Daten = Plural(mehrzahl) von Datum 

##### Datum = Singular(einzahl) für Daten

------
## Tabellenausdrücke

. Aggregatfunktion gibt immer nur einen Wert zurück
- Persistenz >> Dauerhafte Speicherung 
- Transient >> Flüchtige Speicherung 


##### Abgeleitete Tabelle -  Transient 
Select Jahr, Projekt, sum(123*Gehalt) as SummeGehalt
from (
		Select Projekt, Count(mittel) as Anzahl, Year(einst_dat) as Jahr
		From Projekt
		group by Projekt
) as Virtuelle Tabelle
##### CTE's (Common Table Expressions) Allgemeine Tabellenausdruck -  Transient
With CTE as
(
		Select Projekt, Count(mittel) as Anzahl, Year(einst_dat) as Jahr
		From Projekt
		group by Projekt
), CTE 2 as
(
		select *
		from arbeiten

)
Select CTE *, CTE2*
from CTE, CTE2

##### View/Sichten = Gespeicherte Abfragen, virtuelle Tabellen - Persistent
create view_asd as 
(Select pr_nr count,(aufgabe)
from arbeiten
group by pr_nr)

##### Inline Funktion (Parametrisierte Views) - Persistent

---------------------------------------------------------


## Fragen zu u.a. Datenbank-Objekten

#### 1) Schema

a) Was ist ein Datenbankschema?
- Ein Schema ist ein art verzeichnis wobei man die zugehörigkeit unterornden kann.
- ablagesystem für das beschränken von daten und einlagern von tabellen
- planung einer erm modell wird in physikalische Tabellen umgesetzt
- 3 stufige namen objektname.schema.datenbank

b) Wozu wird dies verwendet?
- Um Große Datenbank Tabellen zu Strukturieren  
- Ordnungschaffen und zu ordnung von Tabellen bezogen auf Große Datenbanken 
- bereitstellung von benutzer Daten 


#### 2) View

a) Was sind Views?
- Eine Persistente (dauerhafte) Sql abfrage unter einem bestimmten Namen

b) Wozu werden diese verwendet?
- Virtuelle Tabelle die eine SQL abfrage Speichert um mit den Vorhandenen Tabellen zu arbeiten
- um komplexe sachen zusammen zu fassen 
- Um auf häufige SQL abfragen schnell zugreifen zu können
- Um bestimmte Daten einsichtlich zu machen und einsichten zu verhindern vor unbefugte (benutzerrechte)
- Systemviews gibt es so viele um Redundanzen zu vermeiden, Mit view kann man viele teballen zusammen einzusehen 

c) Was sind Eingabeviews?
-  Diese werden verwendet um Daten aus mehreren Tabellen zu ändern, hinzufügen und zu Löschen
- Vorteile um einzeilne Daten zu erfassen. 
- ein View der zur eingabe dient 
- Check OPTION da wird die 'where' bedingung zusätzlich geprüft 

d) Wie unterscheiden sich diese von gewöhnlichen Views
- Eingabeviews nur aus einer Tabelle bestellen
- andere können aus mehreren bestehen jedoch keine Eingaben machen, da die Eingabe nicht genau weißt auf welche Attribut Sie zu greifen soll (nur zum gucken)

e) Welche View-Options gibt es?
- Encrytpion - Verschlüsselung
- Schemabinding - zwinkt zugreif nur über 2-teilige namen / Tabellen lassen sich nicht in der Struktu verändern sondern in der Schema werden die Daten Manipulierbar. 
- View_Metadata - Änderung der Spalten Namen möglich (um echte Attribut namen zu verstecken) 

#### 3) Procedure

a) Was sind Procedures?
- Procedures sind abläufe die in Hintergrund ablaufen
- kompilierte Datenbanken 

b) Wozu werden diese verwendet?
- Diese werden verwendet um Daten zu ändern 

c) Könnte man Procedures zur Erfassung von Datensätzen verwenden?
- Ja!
- über Parameter und Argumente

d) Wo-innerhalb der Procedure werden: Variablen, Parameter plaziert?
- Nach dem Namen und vor dem AS
- Bsp create Procedure meinProc
	@Para_1 int, 
	@Para_2 char(3)
	AS
	declare @var_1 int 
	
e) welche Procedure-Options gibt es?
 - Recompile - Compeliert 
 - Encryption - Verschlüsselung
 - Execute as Clause - (Benutzerrechte verteilen)


f) Was passiert beim Kompilieren?
- Die Prozedure wird in Binär format durch einen C Compiler übersetzt

g) Wie werden Procedures aufgerufen?
- EXEC Procdeurename(ARGUMENT, ARGUMENT)

h) Auf welchem Wege gelangen Ergebnisse aus einer Procedure nach außen?
- Verwendung des OUT- oder OUTPUT Zusatzes in Argument und Parameter

i)  Welche Aufgabe hat der OUT-Parameter
- Das OUT-Variable von Außen übernimmt die Daten vom Procedure genannte OUT-Parameter
- Ermöglicht call by reference an stelle von call by value

#### 4) Funktion

a) Welche Arten von Funktionen gibt es?
- Skarla Funktion
- Tabellenwertfunktion 
- Inline Funktion 

b) Wie unterscheiden sich Parameter von Funktionen von denen einer Procedure?
- Die Klammern sind der Unterschied zwischen Funktion und Procedure
- Bei Procedure kann man OUTPUT zusatz Klausel nutzen 

c) Wozu dient return - wozu dient returns?
- returns - was für ein Datentypen asugegeben soll
- return - welcher Wert ausgegeben wird

#### 5)Tabellenausdruck

a) Was ist unter dem Begriff Tabellenausdruck zu verstehen?
- Ein Sql Statement welches transient oder persistent abgelegt werden kann

b) Nennen Sie 4 unterschiedlich Tabellenausdrücke
- 1.) Abgeleitete Tabelle (Transienz)
- 2.) CTE (Common Table Expression) (Transienz)
- 3.) View/Sichten (Persistent)
- 4.) inline Function (persistent)

c) Was bedeutet persistent und transient bezüglich Tabellenausdrücke?
- Persistent bedeutet dauerhaftet Speicherung 
- Transienz bedeutet flüchtige Speicherung


