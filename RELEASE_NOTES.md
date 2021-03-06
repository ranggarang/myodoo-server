#### 26.09.2016
#### website, 1.0.25
##### FIX
- HREFLANG wurde nun in der IF Abfrage angepasst, so dass es nur greift bei mehrsprachigen Websites. Der Druck wurde geprüft.

#### 23.09.2016
#### website, 1.0.23
##### FIX
- Anpassung vom 15.09.2016 rückgängig gemacht, nun können Angebote wieder gedruckt werden (SEO: hreflang if-abfrage auskommentiert damit die hreflang wieder funktioniert).

#### 20.09.2016
#### web, 1.0.7
##### CHG
- In der JavaScript-Datei jquery.cleditor.js Zeile 1177-1180 wieder einkomentiert, sodass eine Bearbeitung von multilingualen Texten (Kopf- und Fußtexten) wieder möglich ist.

#### 15.09.2016
#### website, 1.0.21
##### FIX
- SEO: hreflang if-abfrage auskommentiert damit die hreflang wieder funktioniert

#### 18.08.2016
#### mail, 1.0.3
##### CHG
- Änderung der Übersetzung von "Empfänger" zu "Zugeordneter Partner".

#### 16.08.2016
#### mail, 1.0.2
##### CHG
- Kontext vom Posteingang auskommentiert. Dieser hat die Anzeige von zugeordneten mail.messages blockiert.

#### 18.07.2016
#### website_sale, 1.0.4
##### CHG
- Deutsche Übersetzung „Jetzt Kaufen“ in "Jetzt kaufen" geändert.

#### 15.07.2016
#### product, 1.1.3
##### CHG
- Anpassungen für Setzen des Preises


#### 13.07.2016
#### account_followup, 1.0.3
##### IMP
- Übersetzungsdatei, und passende Texte angepasst


#### 11.07.2016
#### account_followup, 1.0.2
##### FIX
- de.po Datei korrigiert, sodass beim Aufruf des Parameters partner_name dieser auch als String angesehen wird (Beispiel: %(partner_name)s ). Das "s" fehlte in der kompletten de.po Datei nach dem Aufruf des jeweiligen Parameters.


#### 29.06.2016
#### point_of_sale, 1.0.3
##### FIX
- Tippfehler in der Versionsnummer korrigiert, damit man Odoo wieder starten kann


#### 29.06.2016
#### account, 1.1.4
##### CHG
- Das Feld attachment bei dem Bericht "Rechnungen" wird nun nicht mehr gesetzt (auskommentiert).

#### 28.06.2016
#### website_sale, 1.0.1
##### IMP
- Ein unnötiger Bindestrich wurde entfernt

#### 20.06.2016
#### account_analytic_analysis, 1.2
##### ADD
- Noupdate="1" und forcecreate="False" beim Email Template "Contract expiration reminder" eingefügt, sodass das Template nach einem Löschvorgang auch gelöscht bleibt.

#### 20.06.2016
#### calendar, 1.4
##### CHG
- Übersetzung der Email-Templates zu "Meeting Invitation", "Meeting Invitation - Reminder" und "Meeting Invitation - Change Date" aus der .po-Datei entfernt. Dadurch wird die Übersetzung nicht mehr über die importierten Template geladen.

#### 20.06.2016
#### crm, 1.4
##### CHG
- Übersetzung des Email-Templates zu "Reminder to User" aus der .po-Datei entfernt. Dadurch wird die Übersetzung nicht mehr über das importierte Template geladen.

#### 20.06.2016
#### auth_signup, 1.0.5
##### CHG
- Übersetzung des Email-Templates zu "Password Reset" aus der .po-Datei entfernt. Dadurch wird die Übersetzung nicht mehr über das importierte Template geladen.

#### 20.06.2016
#### purchase, 1.4
##### CHG
- Übersetzung der Email-Templates zu "RFQ - Send by Email" und "Purchase Order - Send by Email" aus der .po-Datei entfernt. Dadurch wird die Übersetzung nicht mehr über das importierte Template geladen.

#### 20.06.2016
#### account, 1.1.3
##### CHG
- Übersetzung des Email-Templates zu "Invoice - Send by Email" aus der .po-Datei entfernt. Dadurch wird die Übersetzung nicht mehr über das importierte Template geladen.

#### 20.06.2016
#### sale, 1.3
##### CHG
- Übersetzung des Email-Templates zu "Sales Order - Send by Email" aus der .po-Datei entfernt. Dadurch wird die Übersetzung nicht mehr über das importierte Template geladen.

#### 16.06.2016
#### calendar, 1.3
##### ADD
- Deutsche Übersetzung für at...To (von...bis) für das Email-Template "Meeting Invitation - Change Date" hinzugefügt.

#### 03.06.2016
#### web, 1.0.19
##### CHG
- Änderung in Generierung von Meta-Tag "Robots" auf den Seiten. Der Wert wird ab jetzt aus der Tabelle ir_ui_view.website_meta_robots geholt

#### 01.06.2016
#### web, 1.0.4
##### FIX
- Die JavaScript-Datei jquery.cleditor.js dementsprechend angepasst, sodass keine Autovervollständigung mehr stattfindet.

#### 31.05.2016
#### web, 1.0.3
##### FIX
- JavaScript debugger entfernt.

#### 31.05.2016
#### web, 1.0.2
##### CHG
- JavaScript Datei "view_form.js" so angepasst (Aufruf der Funktion "updateTextArea()" auskommentiert), dass bei einer Bearbeitung der Email-Templates im ersten Editor keine Auto-Verollständigung mehr stattfindet.

#### 31.05.2016
#### web_analytics, 1.0.1
##### ADD
- Übersetzungsdatei de.po in Ordner i18n eingefügt

#### email_template, 1.4
##### CHG
- Bei dem Email-Template zu Partner Mass Mail musste um das dauerhafte Löschen zu gewährleisten noch ein noupdate="1" eingefügt werden. Außerdem wurde die entsprechende Action act_window zu dem Template auskommentiert, um bei einem Löschen des Templates eine fehlende Referenzierung zu verhindern.

#### 31.05.2016
#### auth_signup, 1.0.4
##### CHG
- Bei dem Email-Template zu Reset Password und Odoo Enterprise Connection musste um das dauerhafte Löschen zu gewährleisten noch ein noupdate="1" eingefügt werden.

#### 31.05.2016
#### crm_partner_assign, 1.2
##### CHG
- Bei dem Email-Template zu Lead Mass Mail musste um das dauerhafte Löschen zu gewährleisten noch ein noupdate="1" eingefügt werden.

#### 31.05.2016
#### crm, 1.3
##### CHG
- Action act_window zu dem Template "Lead/Opportunity Mass Mail" auskommentiert, um bei einem Löschen des Templates eine fehlende Referenzierung zu verhindern.

#### 30.05.2016
#### purchase, 1.3
##### CHG
- Bei dem Email-Template zu RFQ - Send by Email ein forcecreate="False" eingefügt. Dadurch bleibt bei einem Löschen des Templates das Template gelöscht.

#### 30.05.2016
#### auth_signup, 1.0.3
##### CHG
- Bei dem Email-Template zu Reset Password ein forcecreate="False" eingefügt. Dadurch bleibt bei einem Löschen des Templates das Template gelöscht.

#### 30.05.2016
#### crm, 1.2
##### CHG
- Bei dem Email-Template zu Reminder to User ein forcecreate="False" eingefügt. Dadurch bleibt bei einem Löschen des Templates das Template gelöscht.

#### 30.05.2016
#### purchase, 1.2
##### CHG
- Bei dem Email-Template zu Purchase Order - Send by Email ein forcecreate="False" eingefügt. Dadurch bleibt bei einem Löschen des Templates das Template gelöscht.

#### 30.05.2016
#### email_template, 1.3
##### CHG
- Bei dem Email-Template zu Partner Mass Mail ein forcecreate="False" eingefügt. Dadurch bleibt bei einem Löschen des Templates das Template gelöscht.

#### 30.05.2016
#### auth_signup, 1.0.2
##### CHG
- Bei dem Email-Template zu Odoo Enterprise Connection ein forcecreate="False" eingefügt. Dadurch bleibt bei einem Löschen des Templates das Template gelöscht.

#### 30.05.2016
#### calendar, 1.2
##### CHG
- Bei den 3 Email-Templates zu Meeting Invitation ein forcecreate="False" eingefügt. Dadurch bleibt bei einem Löschen des Templates das Template gelöscht.

#### 30.05.2016
#### crm, 1.1
##### CHG
- Bei dem Email-Template zu Lead/Opportunity Mass Mail ein forcecreate="False" eingefügt. Dadurch bleibt bei einem Löschen des Templates das Template gelöscht.

#### 30.05.2016
#### crm_partner_assign, 1.1
##### CHG
- Bei dem Email-Template zu Lead Mass Mail ein forcecreate="False" eingefügt. Dadurch bleibt bei einem Löschen des Templates das Template gelöscht.

#### 30.05.2016
#### portal_sale, 0.3
##### CHG
- Bei dem Email-Template zu Invoice - Send by Email (Portal) ein forcecreate="False" eingefügt. Dadurch bleibt bei einem Löschen des Templates das Template gelöscht.

#### 30.05.2016
#### account, 1.1.2
##### CHG
- Bei dem Email-Template zu Invoice - Send by Email ein forcecreate="False" eingefügt. Dadurch bleibt bei einem Löschen des Templates das Template gelöscht.

#### 30.05.2016
#### website_quote, 1.1
##### Fix
- Bei dem Email-Template zu Sales Order - Send by Email (Online Quote) ein forcecreate="False" eingefügt. Dadurch bleibt bei einem Löschen des Templates das Template gelöscht.

#### 30.05.2016
#### sale, 1.2
##### Fix
- Copy-Paste-Fehler entfernt.

#### 30.05.2016
#### sale, 1.1
##### CHG
- Bei dem Email-Template zu Sales Order - Send by Email ein forcecreate="False" eingefügt. Dadurch bleibt bei einem Löschen des Templates das Template gelöscht.

#### 30.05.2016
#### portal_sale, 0.2
##### CHG
- Bei dem Email-Template zu Sales Order - Send by Email (Portal) ein forcecreate="False" eingefügt. Dadurch bleibt bei einem Löschen des Templates das Template gelöscht.

#### 19.05.2016
#### mass_mailing, 2.3
##### ADD
- Für die Weiterleitung bei dem Link "Newsletter abbestellen" wird jetzt das Layout der Webseite gerendert. Außerdem wurde eine Ansicht geschaffen, die jetzt vom Aussehen und von der Formatierung angepasst werden kann.

#### 19.05.2016
#### web, 1.0.1
##### FIX
- Korrektur für das Problem mit dem Button "Speichern", der im Editmodus nicht aktiviert wurde

#### 11.05.2016
#### website, 1.0.18
##### ADD
- Das Meta-Tag <meta name="robots" content="index,follow" /> wird nun gesetzt, wenn das Flag "Suchmaschinen davon abhalten, diese Webseite zu indexieren [eq_website_customerportal] " in den Einstellungen nicht gesetzt ist.


#### 11.05.2016
#### website, 1.0.17
##### FIX
- Durch die Google Indexierung wurde im Backend ein Fehler verursacht, welcher das Laden von E-Mail Vorlagen nicht mehr ermöglicht hat. Dies wurde nun behoben.


#### 11.05.2016
#### website, 1.0.16
##### Änderung
- Es wird nun überprüft ob das Modul eq_website_customerportal installiert ist, um dann mit Hilfe des Flags zur Google Indexierung bei Aktivierung den Meta-Tag <meta name="robots" content="noindex,nofollow" /> zu setzen.


#### 02.05.2016
#### auth_signup, 1.0.1
##### Änderung
- E-Mail Template Passwort-Zurücksetzen Fomratierungsfehler entfernt.


#### 22.04.2016
#### website, 1.0.15
##### Änderung
- Übersetzungen

#### 21.04.2016
#### website, 1.0.14
##### Änderung
- Mediacenter
1. Größenangaben der Buttons verbessert (statische Größen entfernt)
2. Ansicht der Bildmengen von 80 auf 12 verringert (12 Bilder wie in der standard Ansicht)
3. Die Höhe der Listenansicht der Bilder ist nun dynamisch anhand des ModalPopup-Inhaltes

#### 20.04.2016
#### website, 1.0.13
##### Änderung
- Mediacenter, Icon "Delete" auf der Listview Ansicht auf default "Papierkorb" geändert

#### 20.04.2016
#### website, 1.0.12
##### Erweiterung
- Mediacenter, In dem Listview kann man ab jetzt Bilder anwählen und sie werden automatisch übernommen

#### 20.04.2016
#### website, 1.0.11
##### Erweiterung
- Mediacenter, beide Listviews (Bilder und Dateien) wurde um Sortierung in der Spalte "Letzte Änderung" erweitert

#### 20.04.2016
#### website, 1.0.10
##### Erweiterung
- Mediacenter, beide Listviews (Bilder und Dateien) wurde um Sortierung (im Moment nur in der Spalte Dateiname) erweitert 

#### 20.04.2016
#### website, 1.0.9
##### Änderung
- Mediacenter, Listviews -> max. Anzahl der Zeile pro Seite auf 80 gesetzt

#### 20.04.2016
#### website, 1.0.8
##### Erweiterung
- Mediacenter um diese Features erweitert:
1. Beide Listviews (Bilder und Dateien) zeigen max. 80 Zeilen auf einer Seite
2. Die Ansicht "Images-ListView" wurde um eigene Logik für Pager erweitert
3. Pager für die Ansicht "Images-NormalView" wurde angepasst, damit die Logik von der Ansicht "Images-ListView" getrennt ist
4. Dateigröße ist ab jetzt immer in KB ein diesem Format angezeigt 95,22 KB
5. Beide ListViews haben jetzt eine Spalte "Letzte Änderung"

#### 19.04.2016
#### website_sale_options, 1.0.1
##### FIX
- Übersetzung "Produkt zum verschieben in Einkaufskorb" mit "Produkt zum Warenkorb hinzufügen" ersetzt

#### 18.04.2016
#### website, 1.0.7
##### Erweiterung
- Kern um Ivan's (Fileupload) und Sody's (Paging für jede Seite im Kontext) Anpassungen erweitert

#### 18.04.2016
#### website, 1.0.6
##### Änderung
- MediaCenter - Paging für Bilder verbessert. Ab jetzt funktioniert es korrekt mit Kontext jeder Seite

#### 15.04.2016
#### website, 1.0.5
##### Änderung
- Migration der Funktionalität vom eq_website_customerportal in Kern

#### 15.04.2016
#### website, 1.0.4
##### Änderung
- Änderung der kontextbezogene Suche + Änderung der Defaultansicht

#### 15.04.2016
#### website, 1.0.3
##### Erweiterung
- Mediacenter, Neue Buttons für "Normalview" und "Listview" zusammen mit der Basis für Korrektur fürs Paging

#### 15.04.2016
#### website, 1.0.2
##### Erweiterung
- Mediacenter, kontextbezogene Bildsuche auf im Normalview und Listview und Anzeige der Treffersuche verbesser. Ab jetzt wird immer die aktuelle ansicht (view) korrekt angezeigt und Benutzer wird nicht mehr zurück auf Normalview umgeleitet

#### 15.04.2016
#### website, 1.0.1
##### Erweiterung
- Mediacenter, Bildupload um Listview erweitert