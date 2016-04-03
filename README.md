# voiceattack-starcitizen-killsignal
Ein einfaches VoiceAttack-Profil für Star Citizen

VoiceAttack setzt Sprache in Tastatur- und Mauseingaben um.
So lassen sich Spiele wie Star Citizen einfacher steuern.

Um dieses Profil einsetzen zu können, muss folgendes erledigt werden:
1. die Beta von http://www.voiceattack.com/ besorgen und installieren
2. die Spracherkennung von Windows trainieren (bei Win 7 unter Systemsteuerung
-> Spracherkennung -> Trainieren Sie den Computer.. (2-3 mal durchführen))
3. VoiceAttack als Administrator starten, Profil importieren (Icon mit Plus-Zeichen)
VoiceAttack sollte mit "initialized myself" antworten
4. Star Citizen starten
5. im Spiel "Status" sagen. VoiceAttack sollte mit "ready" antworten

Das Profil beherrscht folgende Befehle:

(Befehl - was es tut)

annehmen - zur Bestätigung von Befehlen. Aktuell nur zur Annahme des vorgeschlagenen Landepunkts im Landemodus.

Autolandung - schaltet die automatische Landung ein oder aus. Standard ist "ein".

Energie reset; Energie normal; Energie standard - Setzt die Energieverteilung auf je 1/3 für Waffen, Antrieb und Schilde zurück.

Fluchtmodus - verteilt die Energie auf Antrieb und Schilde. Schaltet die Waffen aus.

initialisieren - setzt Variablen zurück. Hilfreich, wenn das Profil nicht mehr richtig funktioniert. Wird automatisch beim 
Laden des Profils ausgeführt.

Kampfmodus - verteilt die Energie auf Waffen und Schilde. Schaltet die Waffen an.

Lade Programm 1 - Joystickmodus: sperrt den Gimbal und schaltet Look Ahead aus.

Landemodus - aktiviert den Landemodus und die automatische Landung.

langsamer - verringert die Geschwindigkeit um ca. 1/5.

Maschine; Maschinen; Energie - zeigt die Energieverteilung.

mehr Antrieb - gibt mehr Energie in den Antrieb. Die Änderung soll gering sein, hängt aber vom Schiffstyp ab.

mehr Schilde - gibt mehr Energie zu den Schilden. Die Änderung soll gering sein, hängt aber vom Schiffstyp ab.

mehr Waffen - gibt mehr Energie zu den Waffen. Die Änderung soll gering sein, hängt aber vom Schiffstyp ab.

Quantum - aktiviert die Zielauswahl des Quantum-Antriebs.

Radar - schaltet durch die verschiedenen Radar-Auflösungen.

Schild hinten links; Schilde hinten links

Schild hinten rechts; Schilde hinten rechts

Schild hinten; Schilde hinten

Schild links; Schilde links

Schild rechts; Schilde rechts

Schild reset; Schilde reset; Schild normal; Schilde normal; Schild standard; Schilde standard

Schild vorn links; Schild vorne links; Schilde vorn links; Schilde vorne links

Schild vorn rechts; Schild vorne rechts; Schilde vorn rechts; Schilde vorne rechts

Schild vorn; Schild vorne; Schilde vorn; Schilde vorne

Schild; Schilde - zeigt den Schildstatus und die Konfiguration

schneller - erhöht die Geschwindigkeit um ca. 1/5.

Sicht hinten - schaltet für 2 Sekunden auf die Rückkamera um.

Sprung; spring; springe - aktiviert den Quantum-Antrieb für das angepeilte Ziel.

Status - antwortet bei korrekter Initialisierung mit "OK".

Übersicht - zeigt die Übersicht.

vergrößern; größer - zoomt rein.

verkleinern; kleiner - zoomt raus.

volle Schilde - alle Energie zu den Schilden.

volle Waffen - alle Energie zu den Waffen.

voller Antrieb - alle Energie in den Antrieb.

Waffen - zeigt die Waffenkonfiguration.

Bemerkung:
Windows 7 Pro hat eine deutsche Spracherkennung, aber englische Ausgabe. Man kann deutsche Stimmen nachinstallieren,
wozu ich aber zu faul war. Deswegen (und weil ich von meinem Raumschiff nicht vollgequatscht werden will) habe ich mich im Profil auf kurze Antworten wie "OK" oder "negative" beschränkt.
Mit "Anna" gibt es ein sehr umfangreiches, jedoch englisches Profil https://forums.robertsspaceindustries.com/discussion/153203/voiceattack-anna-v5-52-control-everything-with-your-voice
"Lena" ist ein weiteres großes Profil, aber deutsch https://www.systemsunitednavy.com/threads/german-voice-attack-ultimate-profile-lena-updates.4297/
Meines ist, wie gesagt, die kleine Lösung.

Fehler:
Wenn man Sprach- und Tastatureingaben mischt, kann es zu Fehlern kommen. Sagt man bespielsweise "Quantum" und drückt dann die mittlere Maustaste, um den Sprung auszulösen, so kann es sein, dass ein nachfolgender Sprungversuch mit "negative" quittiert wird. Dann hilft "initialisieren".

Einschränkungen:
Das Profil funktioniert nur in Schiffen mit HUD vollständig (wo man mit den F-Tasten zwischen den Ansichten umschalten kann). Dazu zählen z.B. die Hornets, Sabre und Khartu-Al. Stand Alpha 2.3.
