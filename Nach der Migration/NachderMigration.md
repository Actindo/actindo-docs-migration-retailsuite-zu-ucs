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
