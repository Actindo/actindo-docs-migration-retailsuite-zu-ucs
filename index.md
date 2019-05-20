[toc]

## 1.	Hintergrund
Dieser Migrationsleitfaden richtet sich an Kunden, die bislang die RetailSuite (RS) eingesetzt haben und einen Umstieg auf die Unified Commerce Suite (UCS) planen. Dadurch soll ein reibungsloser Übergang gewährleistet werden.

Für ein schlüssiges Gesamtkonzept wird Ihnen aufgezeigt, welche Komponenten migriert werden sollen, welche Module betroffen sind und wie Sie die Migration, beispielsweise durch vorherige Updates und Tests, erleben werden.

### 1.1	Begriffserklärung
Um Sie vorab hinsichtlich der verwendeten Begrifflichkeiten abzuholen, hier ein kurzer Einblick in die Bezeichnungen „Unified Commerce Suite“ und „Actindo Core1“.

Die Actindo Core1 beschreibt die Plattform und Laufzeitumgebung, auf dem das ERP – in unserem Fall die UCS und andere Entwicklungen sowie Applikationen – betrieben werden können. Weiterhin besteht die Möglichkeit, hier „indirekte Touchpoints“, wie Beispielsweise eine Webseite, für den Endkunden anzubinden.

Die Unified Commerce Suite (Abk: UCS), ist eine neue Softwaregeneration, basierend auf der Actindo Core1. Sie setzt sich durch die Kombination von verschiedenen Actindo Modulen wie Faktura, Buchhaltung, Pim, usw. zusammen und bildet das Betriebssystem für Ihren Handel.

### 1.2	 Der Aufbau dieser Anleitung
Für eine Schrittweise Anleitung werden Ihnen vorab alle Schritte, die vor einer Migration durchzuführen sind, erläutert. Im Anschluss dazu wird der Antrag auf eine Migration als auch die Schritte während und nach der Durchführung dieser, aufgelistet. So wird sichergestellt, dass Sie durch jede Migrationsphase angeleitet werden.

### 1.3	 Die Migrationsziele
Die UCS ist eine webbasierte Plattform, die sowohl im B2C (Business to Customer) als auch im B2B (Business to Business) Geschäft unabdingbar ist. Dies begründet sich durch die harmonische Integration von Handelsprozessen und Systemen die bislang unabhängig und abgegrenzt voneinander agiert haben. Dadurch wird die Transparenz und Interaktion der internen Channels gewährleistet.

Die Ziele dieser strategischen Migration auf die Unified Commerce Plattform sind:

* einen verbesserten Anwendernutzen zu erzielen
* die Sicherheit eines einheitlichen Datenbestandes durch das konsistente Speichern der Informationen zu ermöglichen
* ein anwenderfreundliches Design, dass die Einarbeitung erleichtert
* bisherige Fehler zu beheben
* die Produktivität zu steigern
* den Funktionsumfang zu erweitern

Es müssen dabei, im Vorfeld als auch danach, Maßnahmen ergriffen werden, welche Sie mit unserer Anleitung selbstständig durchführen können. Im nachfolgenden Kapitel werden diese erläutert.

## 2.	Vor der Migration
Für die UCS-Migration müssen im Vorfeld grundlegende Einstellungen vorgenommen werden. Für deren schrittweise Umsetzung stellen wir Ihnen Ansprechpartner, Ablaufpläne, Anleitungen und Hilfsmittel zur Verfügung:

**Ihre Ansprechpartner:**

Florian Anlauf	Email: florian.anlauf@actindo.com
Max Ager		Email: max.ager@actindo.com

### 2.1	Das Informationsgespräch
Für eine Beratung bezüglich Ihrer Migration, bieten wir Ihnen ein Telefonat mit einem Berater an. Mit diesem können Sie alle offenen Fragen klären, sowie weiteres Informationsmaterial anfragen.

Bitte teilen Sie uns vorab mit, wenn Ihr System mit Custom-Entwicklungen (siehe auch Kapitel 2.2.1 dieses Dokuments) arbeitet. Wir können dann die entsprechend benannten Punkte und/oder Module screenen und gegebenenfalls den vorhandenen Mehraufwand einkalkulieren.

***Bei Versäumnis der Mitteilung kann Actindo nicht für damit verbundene Fehlfunktionen oder Prozessausfällen belangt werden.***

#### 2.1.1	Die Anforderungen
*Wer sollte migrieren?*
Die Migration auf die Unified Commerce Suite ist grundlegend für jeden mit Interesse an einer einheitlichen Plattform geeignet und wird nur mit einem einzigen Anbieter abgewickelt. Mit diesem vertrauenswürdigen Anbieter haben Sie in Zukunft einen direkten Ansprechpartner für Support und Updates.

*Wann sollte man die Migration durchführen?*
Den Zeitpunkt einer Migration können Sie individuell entscheiden. Als Anhaltspunkt einer stressfreien Migration empfehlen wir nachdrücklich, diese nicht während einer Hochsaison Ihres Betriebs vorzunehmen.

#### 2.1.2	Die Benutzer-Einstellungen
Der Benutzer, der einen Core1-Account registriert, auf welchem Ihre Unified Commerce Suite installiert und betrieben wird, ist zu diesem Zeitpunkt auch der Eigentümer dieses Accounts. Dieser verfügt dann über die vollen Admin-Rechte innerhalb dieses Kontos, einschließlich der Manipulation und Anlage anderer Benutzer, die in diesem Konto – und somit auf die Core1 registriert sind.

Daher ist es wichtig, vorher abzuwägen, welcher Benutzer die Administratorrechte für ein bestimmtes Konto erhält und uns diesen mitzuteilen oder im dafür vorgesehenen Feld einzutragen. Danach muss eingestellt werden, welche weiteren Benutzer ebenfalls auf dieses Konto Zugriff erhalten und wie viel diese dann einsehen dürfen.

Da Ihre bisherigen Benutzer und Gruppen nicht migriert werden, müssen Sie diese neu anlegen. Dafür gibt es drei Möglichkeiten:

**1.)Benutzer selbst anlegen:**
*Vorgehensweise:*
Im Core1 Hauptmenü (links) auf Einstellungen klicken.
Benutzer und Gruppen auswählen
Nun können Sie zwischen Benutzerverwaltung und Gruppenverwaltung wählen, um dort Ihre Einstellungen zu tätigen.

![Benutzerkonten](/assets/Benutzerkonten.png)

**2.)	Hauptnutzer durch Actindo anlegen lassen:**
*Vorgehensweise:*
Dafür senden Sie uns den von Ihnen bestimmten Hauptnutzer, welchen wir dann mit den vollen Admin-Rechten für Sie anlegen. Durch diesen Hauptnutzer haben Sie dann die Möglichkeit alle weiteren Nutzer anzulegen.

**3.)	Actindo legt alle Nutzer an:**
Dies ist eine Option innerhalb der Hypercare (Kapitel 2.2.3), in welchem wir alle Ihre Nutzer für Sie anlegen. Sie müssen uns dafür lediglich die gewünschten Namen der Benutzer zusenden.

### 2.2	Actindos Angebote
Der Leistungsumfang beinhaltet die Migration, eine Beratung zu Custom-Entwicklungen, sowie auf Wunsch auch persönlichen und individuellen Support, der exakt auf Ihre Bedürfnisse zugeschnitten ist.

#### 2.2.1	Custom-Entwicklungen
Benötigen Sie Beispielsweise einen für Sie angepassten Shop-Connector oder andere Anwendungen, die speziell für Ihre Bedürfnisse zugeschnitten sind, können Sie diese bei Ihrem Berater Anfragen und gegebenenfalls in Auftrag geben.

#### 2.2.2	Support
Unser Support ist in drei Kategorien eingeteilt. Professional, Premium und Enterprise.

##### 2.2.2.1 Professional
Der Professional Support beinhaltet:
•	Keine Mindestlaufzeit des Vertrags
•	Keine erweiterte Betreuung durch einen persönlichen Customer Success Manager
•	Kein In-Account Support
•	Eine Reaktionszeit von drei Tagen
•	(...)

##### 2.2.2.2 Premium (Optional)
Der Premium Support beinhaltet:
•	12 Monate Mindestlaufzeit des Vertrags
•	Keine erweiterte Betreuung durch einen persönlichen Customer Success Manager
•	In-Account Support
•	Eine Reaktionszeit von einem Tag
•	(...)

##### 2.2.2.3 Enterprise (Optional)
Der Enterprise Support beinhaltet:
•	12 Monate Mindestlaufzeit des Vertrags
•	Erweiterte Betreuung durch einen persönlichen Customer Success Manager
•	In-Account Support
•	Eine Reaktionszeit von vier Stunden
•	(...)

Für die gesamte Übersicht suchen Sie bitte die [Actindo Support Optionen](https://www.actindo.com/de/doku/) auf.

#### 2.2.3	Hypercare
Um Ihrerseits eine reibungslose Prozessübernahme sicherzustellen, beachten Sie bitte, dass zur Migration des von Ihnen gewählten Pakets, das Zubuchen folgender Dienstleistungen empfehlenswert ist, um eventuelle Nachschulungen Ihrer Mitarbeiter abzudecken.

##### 2.2.3.1	Das Hypercare Grund-Paket
Das Hypercare Grund-Paket beinhaltet eine Hypercare-Phase von eins bis fünf Tagen. Während dieser Zeit haben Sie einen direkten Ansprechpartner sowie gebuchte Zeiten in der Entwicklung, in der Ihre Bedürfnisse und Probleme priorisiert bearbeitet werden.
Custom-Entwicklungen werden nach Absprache mit Ihrem Betreuer evaluiert und angeboten.

##### 2.2.3.2	Das Hypercare Erweiterungs-Paket
Das Hypercare Erweiterungs-Paket beinhaltet eine Hypercare-Phase von mindestens fünf Tagen. Während dieser Zeit haben Sie Anspruch auf eine persönliche Betreuung durch einen Migrationsberater vor Ort* , der die Schulung Ihrer Mitarbeiter übernimmt und die Schnittstelle zwischen Ihnen und der Entwicklungsabteilung ausmacht.
Sie erhalten ebenfalls eine Parametrierungshilfe, die Sie bei der Einrichtung des Berechtigungssystems unterstützt, sowie unter anderem bei Ihren Textbausteinen, Lagerprozessen und Benachrichtigungsmodulen.
Sie erhalten zudem ein regelmäßiges Account Screening der Performance sowie Funktionalität der Automatismen.
Ihnen steht außerdem eine hochpriorisierte Bearbeitung Ihrer Issues in der Entwicklung zu.

Bitte wenden Sie sich bei Interesse an Ihren Migrationsberater.

*(*Vor-Ort-Termine verstehen sich zzgl. Fahrtkosten zu 0,40 EUR pro Kilometer, Hotelauslagen bis zu einer Höhe von 120 EUR pro Person und Nacht, Spesen nach gesetzlicher Berechnung sowie entstandenen Auslagen wie z.B. Taxi oder Parkkosten. Erfolgt die Anreise per Flug, werden die tatsächlich anfallenden Flugkosten anstelle der Kilometerpausschale weiterberechnet.)*

#### 2.2.4	Test-Account  (Optional)
*(Beinhaltet einen Core1-Account inklusive eines UCS Pakets)*

Bei einem Test-Account handelt es sich lediglich um einen leeren Account, auf welchem Sie die Funktionen ausprobieren können. Erst bei einer Testmigration (Kapitel 2.2.5), werden Ihre Daten eingespielt, um in der Testphase alle Funktionen anwenden zu können.

Auf unserer Webseite können Sie sich ein Core1 Test-Account anlegen.

**Core1 Test-Account anlegen:**
*Vorgehensweise:*
1 Klicken Sie auf Preise
2 Stellen Sie Ihre User und Transaktionen (mtl.) genauso wie Ihre gewünschte      Laufzeit/Abrechnung ein.
3 Direkt unter Ihren Einstellungen werden Ihnen unsere drei Pakete angezeigt. Ihre Auswahl generiert eine Auswahl des von uns vorgeschlagenen Pakets, das dann grün umrandet als Recommended angezeigt wird.
4 Um zusätzlich auch Ihre Geschäftsziele hinzuzufügen, scrollen Sie weiter nach unten.

**INFORMATION:** In der „Feature Übersicht“ können Sie manuell die Kriterien Ihres Paketes bestimmen und diese dann auswählen.

5 Tragen Sie Ihre Daten ein und wählen Sie LOS GEHT’S.
6 Nun können Sie Ihr Paket unverbindlich für 14 Tage testen.

**Ihre Ansprechpartner:**

Emina Planic 	Email: emina.planic@actindo.com
Max Ager		Email: max.ager@actindo.com

#### 2.2.5	Test-Migration mit Sandbox (Optional)
Hierbei haben Sie die Möglichkeit, auf Anfrage eine Test-Migration durchführen zu lassen. Senden Sie hierzu eine Anfrage an unser Sales Team. Die Kollegen senden Ihnen gerne einen entsprechenden Kostenvoranschlag.

In dieser Test-Migration werden wir für Sie eine Sandbox erstellen, um in diese Ihre Daten zu migrieren. Sie haben nun die Möglichkeit die UCS in dieser Testversion samt Ihren eigenen Daten, unverbindlich zu testen. Entscheiden Sie sich nun für eine Migration, können Sie diese direkt beantragen.

## 3.	Der Migrations-Antrag
Einen Antrag auf eine Migration können Sie jederzeit stellen, sofern Sie die Anforderungen (Kapitel 2.1.1) für eine Migration erfüllen. Weiterhin besteht für Sie die Möglichkeit, die 14 tägige Testphase abzuwarten und währenddessen oder im Anschluss mit Ihrem Betreuer durch ein Telefongespräch weitere Fragen des Migrationsprozesses zu klären.

Nachdem wir mit Ihnen die relevanten Informationen (angelehnt am vorher geführten Informationsgespräch, Kapitel 2.1) analysiert haben, schicken wir Ihnen Ihren Bedürfnissen entsprechend, ein Angebot zu.

### 3.1	Der Vertrag
Sobald der von Ihrer Seite unterschriebene Vertrag bei uns eingegangen ist, erhalten Sie Ihre Migrationsbestätigung und die Zugangsdaten, welche ab diesem Zeitpunkt einsatzbereit sind.

Die Zugangsdaten sind angelehnt an den vorher bestimmten Benutzer-Einstellungen (Kapitel 2.1.2).

***Bitte beachten Sie, dass die Lizensierung Ihres UCS-Pakets sofort ab Unterschrift erfolgt. (Siehe Kapitel 4.1 a und b)***

### 3.2	Die Terminvereinbarung
Die Vorbereitungsmaßnahmen der Migration (Kapitel 2 – Vor der Migration) geben den Handlungsrahmen für diese vor. Sie können anhand derer Ihren Wunschtermin für eine Migration vereinbaren.

**Die Anhaltspunkte der Terminauswahl für eine Migration:**
*-Terminvergabe:*
Vorlauf von mindestens drei Werktagen
*-Migrationstage:*
Montag bis Donnerstag, ausgenommen sind gesetzliche Feiertage
*-Migrationsdatum:*
Kann bei Terminkonflikten 1x kostenfrei verschoben werden

## 4.	Während der Migration
### 4.1		Die Aktivierung des UCS Accounts
***(Wird von Actindo ausgeführt)***

Sobald wir den unterschriebenen Vertrag von Ihnen zurückerhalten, findet die Aktivierung Ihres UCS Account statt.

### 4.2	Die Sperrung des RS Accounts
***(Wird von Actindo ausgeführt)***

Sobald die Migration beginnt, wird von unserer Seite Ihr RS-Account automatisch gesperrt, um Überschneidungen im Arbeitsprozess auszuschließen. Die Kosten Ihres Alt-Accounts (RetailSuite), werden tagesgenau von unserer Buchhaltung berechnet und Ihnen eine entsprechende Abschlussrechnung zugesandt.

**Hinweis auf Lizenskostenparallelität:**
Der alte RS-Account wird bis zur Abnahme (Kapitel 3.1 - Der Vertrag) des UCS-Accounts weiterberechnet.

**Hinweis auf Ihren Betrieb:**
Ihr Tagesgeschäft werden Sie am Tag der Ausführung in der Regel ab 16:00 Uhr oder zu einer mit Ihrem Betreuer abgesprochenen Uhrzeit einstellen. Der Migrationsprozess geschieht dann über Nacht. Sie können sich am darauffolgenden Tag ab 6:00 Uhr wie gewohnt mit Ihren neuen Zugangsdaten auf Ihrem neuen UCS Account einloggen.

Sollten Beeinträchtigungen auftreten, werden Sie umgehend informiert.

### 4.3	Daten Übertragen
***(Wird von Actindo durchgeführt)***

Auf dem Weg zur UCS spielt die Migration des Altdatenbestandes aus Ihrem RS-Account eine entscheidende Rolle. Da es sich bei der UCS als auch der RS um Actindo Systeme handelt, bleibt Ihnen die Dokumentation Ihres aktuellen Datenbestandes oder die Entscheidung, welche Datenübernommen werden und welche nicht, erspart. Alle Ihre Daten werden von uns automatisch bei der Migration übernommen.

## 5.	Nach der Migration
Nachdem die Migration durchgeführt wurde, müssen von Ihrer Seite Einstellungen vorgenommen werden. In den nächsten Unter-Kapiteln werden Sie dazu eingeleitet.

### 5.1	  	SFTP
Da bisher neben der SFTP**  Verbindung auch die FTP***  Verbindung angeboten wurde, beachten Sie bitte, dass jetzt nur noch die SFTP Verbindung unterstützt wird. Stellen Sie Ihren Server deshalb rechtzeitig darauf um.

***Nicht auf FTPS umstellen!***

Bitte kontaktieren Sie für diesen Vorgang Ihren Anbieter.

**(*Secure File Transfer Protocoll)*
***(*File Transfer Protocoll)*

### 5.2	Bankkonten wiederherstellen
*(Für PayPal ist dieser Vorgang nicht notwendig.)*

Synchronisieren Sie Ihre HBCI Kontakte neu, sodass sich diese mit der UCS verbinden. Ohne diese Einstellung, werden Sie bei jedem Vorgang darum gebeten, Ihren PIN neu einzugeben.

**Bankkonten wiederherstellen:**
*Vorgehensweise:*
1 Im Hauptmenü (links) auf Zahlungsabwicklungen klicken.
2 Dann Einstellungen auswählen.
3 Nun können Sie für Ihren Vorgang HBCI Kontakte anlegen/ bearbeiten auswählen.
4 Wenn schon ein Kontakt vorliegt – wählen Sie diesen aus und klicken Sie dann auf Zugang Synchronisieren.
5 Sollte noch kein Kontakt vorliegen, können Sie auf NEU einen anlegen, um diesen dann im Anschluss zu synchronisieren.

 ![Bankkonten](/assets/Bankkonten.png)

### 5.3	Trackingdaten aktualisieren
*(Nur relevant, sollten Sie bisher Tracking Daten  im Einsatz gehabt haben oder nach Ihrer Migration Tracking Daten in Betrieb nehmen wollen.)*

**Bisher:** Für den Re-Import wurde die Tracking Nummer bisher vom FTP Server geholt.

**Jetzt:** Die Tracking Nummer wird nun vom SFTP Server geholt.
Mit Einrichtung des Versandartikels erfolgt ebenfalls der Re-Import vom Versand, sprich der Import der Tracking Nummern in das ERP System. Für eine Weitergabe an die jeweiligen Vertriebskanäle muss über das Modul „Benachrichtigungsmanager“ jeweils ein Benachrichtigungsjob eingerichtet werden.

**Trackingdaten aktualisieren:**
*Vorgehensweise:*
SFTP Server einrichten (Kapitel 5.1)
1 Actindo Core1: Im Hauptmenü (links) auf Fakturierung klicken.
2 Dann Einstellungen auswählen.
3 Wählen Sie Versandanbieter aus und dann Versand.
4 Klicken Sie auf Re-Import.
5 Nun können Sie unter Aktion nach Import eine Auswahl treffen zwischen:
6.1 Importierte Datei soll gelöscht werden
6.2 Importierte Datei soll verschoben werden
7   Klicken Sie auf speichern, um den Vorgang abzuschließen.

![ID Einrichten](/assets/ID-Einrichten.png)

**Einrichtung des automatisierten Abrufs von Tracking Daten:**
*Vorgehensweise:*
1 Actindo Core1: Im Hauptmenü (links) auf Einstellungen klicken.
2 Dann RS Grundeinstellungen auswählen.
3 Nun klicken Sie auf Automator.

![Automator](/assets/Automator.png)

**Einrichtung des manuellen Abrufs von Tracking Daten:**
*Vorgehensweise:*
Actindo Core1: Im Hauptmenü (links) auf Fakturierung klicken.
Dann Versand auswählen.
Klicken Sie dann auf Re-Import vom Versand.
Wählen Sie unten links Re-Import starten aus.

![Manuell](/assets/Manuell.png)

**Im Benachrichtigungsmanager können Sie nach dem Tracken der Daten, diese auf Marktplätze übermitteln:**
*Vorgehensweise:*
1	Actindo Core1: Im Hauptmenü (links) auf Einstellungen klicken.
2	Dann RS Grundeinstellungen auswählen.
3	Nun klicken Sie auf Benachrichtigungen.
4	Um eine neue Benachrichtigung einzustellen, klicken Sie auf NEU um dann aus der Sparte Ereignis, die Rubrik Re-Import vom Versand auszuwählen.

![reimport](/assets/reimport.png)

*Folgende Angaben bitte wie gefolgt ausfüllen:*
•	Bezeichnung: Name des Jobs (Von Ihnen gewählt)
•	Aktiv: JA
•	Aufrufreihenfolge: Zahl > 0
•	Aktion: Marktplatz Versandstatus Aktualisierung
•	Marktplatz: (Marktplatz auswählen - Anzahl beliebig)

![reimport2](/assets/reimport2.png)

Nach dem Ausfüllen aller für Sie relevanten Felde können Sie Ihren Vorgang abschließen, indem Sie speichern auswählen.

**Einrichtung der Trackingdaten im DMS:**
Sollten Sie Ihre Trackingdaten bisher im DMS eingerichtet haben, findet keine Änderung des Vorgangs statt.

### 5.4 MDE Aktualisieren
*(Nur relevant, sollten Sie bisher ein Gerät für die mobile Datenerfassung im Einsatz gehabt haben. Sollten Sie nach Ihrer Migration ein MDE Gerät in Betrieb nehmen wollen, beachten Sie bitte die Versionen)*

Damit Ihre MDE Geräte nach der Migration ebenfalls UCS-kompatibel sind, müssen diese auf die neueste Version aktualisiert werden.

***Handelt es sich bei Ihren MDE-Geräten um das „Honeywell Dolphin 70E“, raten wir Ihnen derzeit von einer UCS-Migration ab. Der Grund hierfür ist, dass dieses Gerät nicht auf die erforderliche Android Version aktualisiert werden kann, um auf TLS-Verschlüsselungen zurückzugreifen.***

Für alle anderen Geräte stellen wir Ihnen unser 'LogiScanSmart' Paket zur Verfügung. Mithilfe dieser Software können Sie dann das Update durchführen. Sie erhalten es auf Anfrage von Ihrem Migrationsbetreuer.

### 5.5 APS  Aktualisieren
*(Nur relevant, sollten Sie bisher das Actindo Print System, im Einsatz gehabt haben. Sollten Sie nach Ihrer Migration ein APS in Betrieb nehmen wollen, beachten Sie bitte das beschriebene Prozedere.)*

In der Retail Suite sind bisher alle Prozesse über die gleiche URL gelaufen: [actindo.biz/actindo](https://www.actindo.biz/actindo/)

Da mit der Nutzung der Core1 jeder Mandant eine individuelle URL mit einem eigenen Präfix hat, muss die Eingabe manuell erfolgen.

Nach Abschluss der Migration benötigen Sie deshalb einen UCS-kompatiblen APS-Client. Diesen bekommen Sie zum Zeitpunkt der Migration samt Anmeldedaten von Ihrem jeweiligen Migrationsbetreuer zugeschickt.

![APS aktualisieren](/assets/APS-aktualisieren.png)

1	Bitte öffnen Sie die heruntergeladene Anwendung, um Ihre Anmeldedaten einzutragen.
2	Tragen Sie Ihren jetzigen Benutzernamen und Passwort ein.
3	Mandant: Diese Nummer hat sich ebenfalls geändert. Sie finden die Neue Mandantennummer unter: Actindo Core1: Hauptmenü (links): Einstellungen. Wählen Sie dann Account aus um anschließend ID anzuklicken.
4	Zum Abschluss der Aktualisierung, fügen Sie dort Ihre neue URL ein:
Wenn Sie in einer Sandbox arbeiten: firmenname.dev.actindo.com/retailsuite/xmlrpc.php
Wenn Sie in Ihrem Live-Account arbeiten: firmenname.actindo.com/retailsuite/xmlrpc.php
5	Sobald Sie Ihr APS aktualisiert haben, raten wir Ihnen, Ihre Druckeinstellungen nochmals zu überprüfen. Diese finden Sie unter: Actindo Core1: Im Hauptmenü (links): Einstellungen. Wählen Sie dann RS Grundeinstellungen aus um anschließend Druckeinstellungenanzuklicken.

## 6. Die Betriebsaufnahme nach der Migration
In diesem Kapitel werden die entfallenen sowie umgezogenen Funktionen im Umfeld der Migration aufgelistet. Zudem werden die Hintergründe der jeweiligen Entscheidung erläutert. Abschließend finden Sie eine Anleitung, wie Sie unseren Support bei Fragen rund um die Nutzung der neuen UCS-Plattform erreichen können aber auch wie Sie Dokumentationen der einzelnen Module einsehen können.

### 6.1 Entfernte Funktionen
**•	"Generic SQL" import/export**
Aufgrund geringer Nachfrage wurde diese Funktion zur Leistungssteigerung entfernt.
**•	FTP-Verbindung**
Die FTP-Verbindung wurde aus Gründen der Datensicherheit entfernt. Der Leitfaden gibt in Kapitel 4.5 nähere Auskunft.
**•	Grafiken in Statistik**
Sie erhalten die Statistiken aus der UCS nur noch in reiner Tabellenform, da die ursprünglich eingesetzten Tools nicht mehr mit den neueren Browsern kompatibel sind.
**•	MailToDMS**
Um weiterhin Daten in das Dokumentenarchiv laden zu können, sollte eine direkte Einbindung als Laufwerk von einem Drittanbieter erfolgen.
**•	WEBDAV-Namespace-Attribute-Definition**
Aufgrund geringer Nachfrage wurde diese Funktion zur Leistungssteigerung entfernt.
**•	Elektronische Signatur**
Aufgrund geringer Nachfrage wurde diese Funktion zur Leistungssteigerung entfernt. Haben Sie auf der RS Plattform jedoch eine elektronische Signatur verwendet, sollte diese deaktiviert werden.

### 6.2 Umgezogene Funktionen
**•	Gläubiger-ID**
Während die Gläubiger-ID zum Einzug von Lastschriften bisher in den Grundeinstellungen der Kundendaten zu finden war, wurde diese nun in das Modul "Zahlungsabwicklung", in die Einstellungen verlegt.
Die Funktionen bleiben unverändert.

**Bisher:**

 ![Früher-ID](/assets/Frueher-ID.png)

**Jetzt:**

 ![Jetzt-ID](/assets/Jetzt-ID.png)

**•	Manuelle Updates**
Bitte beachten Sie, dass Sie Ihre Updates nun individuell durchführen können. Hierfür werden alle von uns zur Verfügung gestellten Updates in Ihrem Core1 Fenster eingeblendet. Auf Wunsch können Sie diese dann direkt durchführen oder ablehnen.

![Updates](/assets/Updates.png)

### 6.3 Weitere Hilfestellungen
Der technische Support sowie die Bereitstellung der Benutzerinformationen spielen auf der gesamten Unified Commerce Suite eine übergeordnete Rolle. Durch zielgerichtete Unterstützung sollen Sie aus unseren Produkten vom Zeitpunkt der Erstinstallation den maximalen Nutzen ziehen.

***Die Dokumentation der Module:***
Zur Maximierung Ihrer Zufriedenheit stellen wir Ihnen die einzelnen Module vor und erklären deren Umgang.


**Die Dokumentation:**
1	Klicken Sie in der Actindo Core1: Im Hauptmenü (links, ganz unten) auf den Hilfe-Button.
2	Über diesen gelangen Sie auf unseren Actindo Customer Center.
Jetzt haben Sie die Möglichkeit, die Dokumentationen unserer Module einzusehen.

![Hilfe](/assets/Hilfe.png)

Bei aktiver Nutzung verschiedener Module, können Sie obendrein direkt im geöffneten Modul einen Antrag auf Support stellen.

**Support-Tickets erstellen:**
Da der Support die höchste Priorität genießt, ist der Zugang dazu von überall auf dem Core1-Account möglich.

*1. Über das Modul "Support":*
Sie können direkt über Ihr Modul "Support" ein Ticket an uns senden oder um einen Rückruf bitten.

*2. Über den grünen "Hilfe" Button:*
Sie können, egal in welchem Modul Sie sich befinden, über den "Grünen-Hilfe-Button" unten rechts, an den Support wenden. Dabei haben Sie wieder die Auswahl zwischen dem Verfassen eines Tickets, oder einem Rückruf von uns.

Bitte beachten Sie bei einem Rückruf, dass dieser immer auf den darauffolgenden Tag erfolgt! Möchten Sie einen Rückruf noch am selben Tag erhalten, müssen Sie die Zeit manuell zurücksetzen.
Die Support Nutzerrechte: Damit bestimmte Benutzer den Support kontaktieren können, muss sichergestellt werden, dass die dazugehörige Benutzergruppe die entsprechende Berechtigung erhalten hat (Kapitel 2.1.2).

![Support](/assets/Support.png)

## 7. Actindos UCS
Wir wünschen Ihnen viel Erfolg bei Ihren täglichen Geschäften und freuen uns, dass Sie sich für deren Ausführung für die Unified Commerce Suite Plattform entschieden haben und so ein Teil unserer Vision geworden sind.

*"Unsere Vision ist es, Unternehmen von den Einschränkungen veralteter Technologien (…) zu befreien (…). Ihr Unternehmen soll ohne Einschränkungen auf Basis einer modernen und zukunftssicheren Plattform dynamisch wachsen, skalieren, und transformieren"*
-Boris Krstic (CSMO).


<div style="display: flex;">
    <img style="flex-basis: 50%; margin-right: 1em;" title="In Bearbeitung" src="In_Bearbeitung.svg"/>
    <div style="flex-basis: 50%;">
        <p>
            Diese Dokumentation befindet sich derzeit noch in Bearbeitung.
        </p>
    </div>
