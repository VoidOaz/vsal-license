===============================================================================
VETERAN SOURCE-AVAILABLE-LIZENZ (VSAL)
Version 1.2 – Allgemeine source-available und auditierbare Softwarelizenz
===============================================================================

Copyright (c) 2026 Berkay Kesgin / VoidOaz. Alle Rechte vorbehalten.

-------------------------------------------------------------------------------
PRÄAMBEL UND ZWECK
-------------------------------------------------------------------------------
Diese Lizenzvereinbarung („Lizenz“) ist ein rechtsgültiger Vertrag zwischen dem
Autor (VoidOaz) und jeder natürlichen oder juristischen Person oder Organisation,
die auf die Software zugreift, sie prüft, kompiliert oder bewertet
(„Lizenznehmer“ oder „Sie“).

Der Autor hat die Software entwickelt und erstellt, um Serveradministratoren,
Entwicklern und Sicherheitsforschern vollständige Quellcode-Transparenz,
statische Sicherheitsaudits und operative Überprüfbarkeit zu ermöglichen.

Der Autor behält sich sämtliche geistigen Eigentumsrechte, Urheberrechte und
Eigentumsrechte an der Software vor. Der Zugang zum Quellcode wird ausschließlich
zu den ausdrücklichen Bedingungen, Bestimmungen und Einschränkungen dieser
Lizenz gewährt.

DIESE SOFTWARE WIRD UNTER EINEM „SOURCE-AVAILABLE“-MODELL BEREITGESTELLT. SIE
IST KEINE OPEN-SOURCE-SOFTWARE (IM SINNE DER OPEN SOURCE INITIATIVE), KEINE
FREIE SOFTWARE UND AUCH KEIN GEMEINFREIES WERK. DER ZUGANG ZUM QUELLCODE WIRD
AUSSCHLIESSLICH ZWECKEN DER PRÜFUNG, INSPEKTION UND NICHTKOMMERZIELLEN TESTS
GEWÄHRT, WIE HIERIN FESTGELEGT.


===============================================================================
ABSCHNITT 1 – DEFINITIONEN
===============================================================================

1.1 „Autor“ bezeichnet Berkay Kesgin (VoidOaz), den alleinigen Schöpfer und
Urheberrechtsinhaber der Software.

1.2 „Software“ bezeichnet die gesamte Suite von Quellcodedateien, kompiliertem
Bytecode (.jar, .class), Build-Konfigurationen, Asset-Dateien, Dokumentation und
Algorithmen, die im Rahmen dieses Pakets bereitgestellt werden.

1.3 „Quellcode“ bezeichnet die menschenlesbaren Programmierdateien (einschließlich
Java, XML und Build-Skripten), aus denen die Software besteht.

1.4 „Binärdatei“ oder „Kompiliertes Executable“ bezeichnet aus dem Quellcode
erzeugte computerlesbare Bytecode-Archive (.jar) oder ausführbare Dateien.

1.5 „Audit“ oder „Inspektion“ bezeichnet die zerstörungsfreie, schreibgeschützte
Durchsicht oder statische Analyse, die durchgeführt wird, um Sicherheit,
Leistung und die Abwesenheit von Schadcode zu überprüfen.

1.6 „Produktionsumgebung“ bezeichnet jede Live-, öffentliche, netzwerkverbundene
oder kommerzielle Serverinstanz (einschließlich Minecraft-Servernetzwerken,
Proxys oder Containern), die für Endbenutzer oder Spieler zugänglich ist.

1.7 „Nichtkommerzieller Lokaltest“ bezeichnet die Ausführung der Software
ausschließlich auf einem privaten, offline betriebenen, nicht öffentlichen
Rechner oder in einer lokalen Umgebung (localhost), ohne dass finanzielle
Zahlungen, Spenden oder kommerzielle Vorteile angenommen werden.

1.8 „Autorisierter Distributionskanal“ bezeichnet Plattformen, Websites oder
Repositories, die vom Autor offiziell gepflegt oder schriftlich ausdrücklich
genehmigt wurden.

1.9 „Abgeleitetes Werk“ bezeichnet jede Software oder jedes Modul, das
wesentliche Teile des tatsächlichen Quellcodes der Software unmittelbar
übernimmt, kopiert oder wiederverwendet. Unabhängige Implementierungen ähnlicher
Funktionalität, die keinen Quellcode der Software kopieren, gelten nicht als
Abgeleitete Werke.

1.10 „Lizenzschlüssel“ oder „Validierungsprotokoll“ bezeichnet einen Token,
Schlüssel oder ein Online-Validierungsprotokoll, das vom Autor zur Autorisierung
der Ausführung in Produktionsumgebungen bereitgestellt wird.


===============================================================================
ABSCHNITT 2 – ERLAUBTE NUTZUNGEN (TRANSPARENZ UND AUDIT)
===============================================================================

2.1 Quellcode-Inspektion
Unter der Voraussetzung der Einhaltung dieser Lizenz gewährt Ihnen der Autor ein
nicht ausschließliches, nicht übertragbares, beschränktes Recht, den Quellcode
einzusehen, zu lesen und zu prüfen. Dieses Recht ist in Bezug auf die konkrete
Version des Quellcodes, auf die Sie zugegriffen haben, zeitlich unbegrenzt,
selbst wenn die Lizenz aus anderen Gründen beendet wird, sofern Sie ihn nicht
entgegen Abschnitt 4 weiterverbreiten.

2.2 Sicherheitsaudit und statische Analyse
Es ist Ihnen vollumfänglich gestattet, statische Codeanalyse-Tools,
Sicherheitsscanner und lokale Profiling-Software auf den Quellcode anzuwenden,
um dessen Leistung und Sicherheitsintegrität zu prüfen.

2.3 Veröffentlichung von Auditberichten
Sie dürfen unabhängige technische Überprüfungen oder Sicherheitsauditberichte
veröffentlichen, sofern:
(a) Die Berichte technisch und objektiv sind;
(b) Sicherheitslücken gemäß Abschnitt 8 dieser Lizenz behandelt werden;
(c) Der Bericht nicht über angemessene Codeauszüge (Fair Use) hinaus ganze
    Quelldateien wiedergibt.

2.4 Feedback und Community-Beiträge
Wenn Sie Fehlerberichte, Sicherheitshinweise oder Codebeiträge an den Autor
übermitteln, räumen Sie dem Autor hiermit ein unbefristetes, weltweites, nicht
ausschließliches Recht ein, dieses Feedback in die Software aufzunehmen und zu
kommerzialisieren. Im Gegenzug verpflichtet sich der Autor, den Beitragenden in
der Projektdokumentation, der CREDITS-Datei oder einem gleichwertigen
öffentlichen Namensnennungsmechanismus, der mit dem offiziellen Repository der
Software gepflegt wird, öffentlich anzuerkennen und zu benennen. Diese
Anerkennung bleibt bestehen, solange der eingebrachte Beitrag Teil der Software
ist.


===============================================================================
ABSCHNITT 3 – PRODUKTIONSEINSATZ UND KOMMERZIELLE NUTZUNG
===============================================================================

3.1 Kommerzielle Lizenzpflicht
Das Ausführen, Hosten oder Betreiben der kompilierten Binärdatei (.jar) in
jeglicher Produktionsumgebung erfordert eine gültige kommerzielle Lizenz oder
eine ausdrückliche Genehmigung, die direkt vom Autor oder über einen
autorisierten Distributionskanal eingeholt wurde.

3.2 Nichtkommerzielle lokale Evaluierung
Ihnen wird das eingeschränkte Recht eingeräumt, die Software ausschließlich für
nichtkommerzielle lokale Tests auszuführen. Dieses Recht erlischt unverzüglich,
wenn der Server öffentlich zugänglich wird oder kommerzielle Einnahmen/Spenden
erzielt.


===============================================================================
ABSCHNITT 4 – BESCHRÄNKUNGEN ZUR WEITERVERBREITUNG UND KOMPILIERUNG
===============================================================================

4.1 Wörtliche Wiederverwendung und Extraktion von Code
Sie dürfen den tatsächlichen Quellcode oder die Klassendateien dieser Software
nicht ohne schriftliche Zustimmung des Autors kopieren, extrahieren,
vervielfältigen oder in anderen öffentlichen oder kommerziellen Projekten
weiterverbreiten.

4.2 Weitergabebeschränkungen
Sie dürfen den Quellcode oder die kompilierten Binärdateien nicht auf
Drittanbieter-Dateitauschplattformen oder nicht autorisierten öffentlichen
Repositories hosten, weiterverkaufen, unterlizenzieren oder verbreiten.

4.3 Eigenkompilierung
Die Eigenkompilierung des Quellcodes zu ausführbaren Binärdateien (.jar) ist
ausschließlich zu lokalem Debugging, zu Bildungszwecken und zur Überprüfung, ob
die offizielle Binärdatei mit dem öffentlich zugänglichen Quellcode
übereinstimmt (z. B. durch einen reproduzierbaren Build-Vergleich), gestattet.
Die Bereitstellung selbst kompilierter Binärdateien in jeglicher
Produktionsumgebung ist ohne gültige kommerzielle Vereinbarung untersagt.


===============================================================================
ABSCHNITT 5 – GEISTIGE EIGENTUMSRECHTE
===============================================================================

5.1 Eigentum
Sämtliche Rechte, Titel und Interessen an der Software, einschließlich
Quellcode, Branding und Original-Assets, verbleiben ausschließlich beim Autor
(Berkay Kesgin / VoidOaz).

5.2 Erhalt von Hinweisen
Sie dürfen keine in den Quellcodedateien enthaltenen Urheberrechtsvermerke,
Autorenangaben oder Namensnennungs-Header entfernen, verdecken oder verändern.
Diese Verpflichtung erstreckt sich nicht auf die übliche Serverprotokoll-
Filterung oder Konsolenausgaben-Unterdrückung, die von Serververwaltungstools
vorgenommen wird, solange die zugrunde liegenden Quell-Header unverändert
bleiben.


===============================================================================
ABSCHNITT 6 – DRITTANBIETER-BIBLIOTHEKEN UND ABHÄNGIGKEITEN
===============================================================================

6.1 Geltungsbereich
Diese Lizenz gilt ausschließlich für den vom Autor geschriebenen Originalcode.
Von der Software referenzierte Drittanbieter-Bibliotheken oder Open-Source-APIs
(wie Spigot, Paper, Velocity, Jackson, Guava usw.) unterliegen weiterhin ihren
jeweiligen Open-Source-Lizenzen.


===============================================================================
ABSCHNITT 7 – SOFTWAREINTEGRITÄT UND LIZENZVALIDIERUNG
===============================================================================

7.1 Integritätsgarantie
Der Autor sichert zu, dass offizielle Releases aus autorisierten Kanälen frei von
versteckten Keyloggern, zerstörerischer Ransomware oder bösartigem Datenlöschcode
sind.

7.2 Asynchrone Lizenzvalidierung
Die Software kann ein schlankes, asynchrones Netzwerkprotokoll zur Überprüfung
aktiver Produktionslizenzschlüssel enthalten. Dieser Prozess übermittelt
ausschließlich grundlegende Betriebsmetadaten: den Lizenzschlüssel, einen
gesalzenen kryptografischen Hash (SHA-256) der öffentlichen IP-Adresse des
Servers (der die Klartext-IP nicht preisgibt), die Softwareversion und die
verwendete Java-Laufzeitversion. Es werden keinerlei personenbezogene Daten
von Endnutzern, Chatprotokolle, Spielerdaten oder Datenbankinhalte erhoben,
gespeichert oder übermittelt.


===============================================================================
ABSCHNITT 8 – VERANTWORTUNGSVOLLE OFFENLEGUNG VON SICHERHEITSLÜCKEN
===============================================================================

8.1 Vertrauliche Meldung
Sollten Sie bei der Quellcodeinspektion eine Sicherheitslücke entdecken,
verpflichten Sie sich, diese dem Autor vertraulich zu melden, bevor Sie sie
öffentlich machen.

8.2 Lösungsfrist und verantwortungsvolle Offenlegung
Dem Autor wird eine Frist von 30 Tagen eingeräumt, um das gemeldete Problem zu
untersuchen und zu beheben. Wird die Sicherheitslücke nachweislich aktiv
ausgenutzt („Zero-Day“), gilt eine verkürzte Meldefrist von 7 Tagen, bevor
technische Warnungen zum Schutz der Öffentlichkeit veröffentlicht werden dürfen.
In jedem Fall ist die Offenlegung so zu koordinieren, dass Nutzer Zugang zu
einem Patch erhalten, bevor technische Details weite Verbreitung finden.


===============================================================================
ABSCHNITT 9 – KÜNDIGUNG UND RECHTSMITTEL
===============================================================================

9.1 Automatische Kündigung
Ihre Rechte zur Ausführung, Kompilierung für den Einsatz oder sonstigen Nutzung
der Software (mit Ausnahme des in Abschnitt 2.1 gewährten unbefristeten
Quellcode-Inspektionsrechts) erlöschen automatisch, wenn Sie eine wesentliche
Bedingung dieser Lizenz nicht einhalten.

9.2 Folgen der Kündigung
Im Falle der Kündigung müssen Sie sämtliche Produktions- und lokale Ausführungen
der Software einstellen, alle unter Verstoß verwendeten kompilierten
Binärdateien entfernen und unbefugt erlangte Kopien des Quellcodes, die
außerhalb des erlaubten Inspektionskanals bezogen wurden, vernichten. Das
unbefristete Recht, den öffentlich zugänglichen Quellcode zu historischen/
Prüfzwecken aufzubewahren und einzusehen, bleibt auch nach Kündigung bestehen,
sofern Sie ihn nicht weiterverbreiten.

9.3 Rechtliche Schritte
Nicht genehmigte kommerzielle Nutzung, nicht genehmigte Unterlizenzierung oder
vorsätzlicher Code-Diebstahl stellen eine Vertragsverletzung und
Urheberrechtsverstoß dar. Der Autor behält sich alle Rechte vor, rechtliche
Schritte, Unterlassungsverfügungen und urheberrechtliche Abmahnungen nach
geltendem Recht einzuleiten.


===============================================================================
ABSCHNITT 10 – ANWENDBARES RECHT UND GERICHTSSTAND
===============================================================================

10.1 Anwendbares Recht
Diese Lizenz unterliegt dem Recht der Republik Türkei und ist in Übereinstimmung
mit diesem auszulegen, ohne Berücksichtigung kollisionsrechtlicher Vorschriften.


===============================================================================
ABSCHNITT 11 – GEWÄHRLEISTUNGSAUSSCHLUSS UND HAFTUNGSBESCHRÄNKUNG
===============================================================================

11.1 Gewährleistungsausschluss
DIE SOFTWARE WIRD OHNE MÄNGELGEWÄHR UND „WIE BESEHEN“ BEREITGESTELLT. ES WERDEN
KEINERLEI AUSDRÜCKLICHE ODER KONKLUDENTE GARANTIEN GEWÄHRT. DER AUTOR HAFTET IN
KEINEM FALL FÜR ANSPRÜCHE, SCHÄDEN, DATENVERLUSTE ODER SONSTIGE
HAFTUNGSVERPFLICHTUNGEN, DIE SICH AUS DER NUTZUNG ODER HANDHABUNG DER SOFTWARE
ERGEBEN.

11.2 Haftungsbeschränkung
IM MAXIMAL GESETZLICH ZULÄSSIGEN UMFANG HAFTET DER AUTOR NICHT FÜR INDIREKTE,
ZUFÄLLIGE, BESONDERE ODER FOLGESCHÄDEN (EINSCHLIESSLICH ENTGANGENER GEWINNE,
BETRIEBSUNTERBRECHUNGEN ODER DATENVERLUSTE), SELBST WENN AUF DIE MÖGLICHKEIT
SOLCHER SCHÄDEN HINGEWIESEN WURDE.


===============================================================================
ABSCHNITT 12 – SALVATORISCHE KLAUSEL
===============================================================================

12.1 Sollte eine Bestimmung dieser Lizenz von einem zuständigen Gericht für
unwirksam oder nicht durchsetzbar befunden werden, wird diese Bestimmung im
größtmöglichen Umfang aufrechterhalten, um dem Willen der Parteien Wirkung zu
verleihen, und die übrigen Bestimmungen dieser Lizenz bleiben in vollem Umfang
wirksam und gültig.


===============================================================================
ENDE DER LIZENZBEDINGUNGEN – VSAL v1.2
===============================================================================
