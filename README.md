# voiceattack-starcitizen-killsignal
Ein VoiceAttack-Profil für Star Citizen mit dynamischen, kontextbezogenen Inhalten und schwacher KI.

Kompatibel mit Alpha 2.6

BETA!

Über VoiceAttack:

VoiceAttack setzt Sprache in Tastatur- und Mauseingaben um.
So lassen sich Spiele wie Star Citizen einfacher steuern.

Über dieses Profil:

Das Profil soll nützlich, robust und intuitiv zu bedienen sein. Es soll außerdem den Eindruck schwacher KI vermitteln, welcher durch vielfältige Antworten, scheinbar eigenständige Handlungen und erweiterbares Wissen erreicht werden soll. Das Profil weist einen zynischen, leicht depressiven Charakter auf. Es gibt auch ein Video https://www.youtube.com/watch?v=zLD67eXXc6c&t

Installation:

- VoiceAttack von http://www.voiceattack.com/ besorgen und installieren. Die Probe-Version (Trial) reicht nicht aus.
- Die Spracherkennung von Windows trainieren (bei Windows 7 unter Systemsteuerung -> Spracherkennung -> Trainieren Sie den Computer). Das Training zwei bis dreimal durchführen.
- killsignal-26.vap downloaden, VoiceAttack als Administrator starten und Profil importieren (Icon mit Plus-Zeichen). Eine eventuelle Warnung, dass das Profil auf andere Anwendungen zugreifen will, kann ignoriert werden (siehe Bemerkungen).
- Beim ersten Start fragt das Profil nach dem bevorzugten Sprachstil. Standard ist "gesprächig", es geht aber auch "knapp". VoiceAttack neu starten, falls die Frage nicht gestellt wird.

Upgrade:

Es gibt zwei Möglichen. Die erste ist etwas umständlicher, aber es bleiben statistische Daten erhalten, die sich das Profil gemerkt hat.

- In VoiceAttack auf "Edit Profile" klicken (rechteckiges Icon mit Stift).
- Im neu geöffneten Fenster auf "Import Commands" klicken (unten links).
- Im nächsten Fenster das neue Profil auswählen und öffnen.
- Im nächsten Fenster auf "Import" klicken (unten rechts).
- Die folgenden zwei Warnungen bestätigen.
- Das Fenster "Edit Profile" mit Klick auf "Done" schließen (unten rechts).

Die zweite Möglichkeit besteht darin, das vorhandene Profil zu löschen und durch das neue zu ersetzen.

- In VoiceAttack auf "More Profile Actions" klicken (Icon mit Plus-Zeichen).
- "Delete Profile" auswählen und bestätigen.
- Das neue Profil wie bei "Installation" beschrieben importieren.

Befehlsumfang (Legende unten):

- Abbruch; abbrechen - bricht alle laufenden Vorgänge ab: die Selbstzerstörung des Schiffs, das Beenden des Star Citizen Prozesses.
- abheben; starten; Start - lässt das Schiff ein paar Meter abheben und wechselt vom Lande- in den Flugmodus.
- Abwehr[maßname; maßnamen;] [raus; abfeuern]; [Gegenmaßname; Gegenmaßnamen] [raus; abfeuern] - löst die aktive Gegenmaßname (Flare/Chaff) aus.
- Abwehr[maßname;maßnamen;] [wechseln; tauschen; umschalten]; [Gegenmaßname; Gegenmaßnamen] [wechseln; tauschen; umschalten] - wechselt zwischen den Gegenmaßnamen (Flare/Chaff).
- anpassen - passt die eigene Schiffsgeschwindigkeit an die des Ziels an.
- anvisieren; focussieren; Focus - wählt das Ziel unter dem Fadenkreuz aus.
- Anzug [stop; anhalten; halt] - beendet den Vorwärtsschub des Raumanzugs (gedacht für E.V.A.).
- Anzug [vorwärts; los; go] - lässt den Raumanzug mit Shift-Boost vorwärts schieben (gedacht für E.V.A.).
- Beende Spiel; Spiel beenden; Prozess beenden; Beende Prozess - Beendet Star Citizen. Kann abgebrochen werden.
- Chat - zeigt das Chat-Fensters oder blendet es aus.
- gesprächig; ausführlich - ändert den Sprachstil.
- [Ich;] bin draußen - teilt dem Profil mit, dass man zu Fuß oder E.V.A. ist.
- [Ich;] bin gelandet - teilt dem Pofil mit, dass man gelandet ist (aktiviert aber nicht den Landemodus).
- [Ich;] [bin; sitz; sitze;] am Steuer [und gelandet;] - teilt dem Profil mit, dass man ein Raumschiff steuert (und es gelandet ist).
- initialisieren - setzt die Konfiguration zurück. Hilfreich, wenn ein neues Spiel begonnen wird oder das Profil nicht mehr funktioniert.
- Ja [bitte; ist es; klar; Mama; schon; sicher; sind wir]; Ja wohl; jawoll; Auf jeden [Fall;]; [Klar; Sicher] [doch;]; Sicherlich; Bestätige; Mach schon; Auf geht's - dient zur Bestätigung von Nachfragen bei z.B. "abheben" oder "landen".
- Kamera; Kammerer - wechselt die Kameraposition.
- knapp - ändert den Sprachstil.
- [Lade;] [Steuerung; Programm] Joystick; Lade [Steuerung; Programm;] Joystick - Sperrt Gimbal und schaltet Look Ahead Modus aus.
- [Lade;] [Steuerung; Programm] Maus; Lade [Steuerung; Programm;] Maus - Löst Gimbal und schaltet Look Ahead Modus ein.
- Landemodus - aktiviert den Landemodus.
- landen - leitet die automatische Landung ein (funktioniert nur in der Zone für die automatische Landung).
- langsamer; bremsen; verzögern - verringert den Schub ein wenig.
- Licht; Beleuchtung; Scheinwerfer - schaltet die Schiffsbeleuchtung ein und aus.
- [maximale; maximal; volle] Vergrößerung - vergrößert die Ansicht (Zoom) maximal.
- Moby; Alfred - zeigt mobiGlass oder blendet es aus.
- Nächster [Feind; Gegner]; [Feind; Gegner] plus - wechselt zum nächsten feindlich gesinnten Ziel.
- Nächster Freund; Freund plus - wechselt zum nächten freundlich gesinnten Ziel.
- Nächstes Ziel; Ziel plus - wechselt zum nächsten Ziel.
- Noch ein Schiff zerstört - erhöht den im Profil gespeicherten Zähler der zerschmetterten Feindfahrzeuge um eins.
- Notsprung - führt einen kurzen Quantum-Sprung ohne Zielauswahl durch.
- Quantum - aktiviert die Zielauswahl des Quantum-Antriebs.
- [Rakete; Raketen] [abfeuern; los; starten] - feuert eine Rakete auf das aufgeschaltete Ziel ab.
- Rakete; Raketen [aufschalten;] - schaltet eine Rakete auf das ausgewählte Ziel auf.
- schau [nach;] links; [nach;] links schauen; Was ist links? - schaut für eine kurze Zeit nach links.
- schau [nach;] [oben; hoch]; [nach;] [oben; hoch] schauen; Was ist oben? - schaut für eine kurze Zeit nach oben.
- schau [nach;] rechts; [nach;] rechts schauen; Was ist rechts? - schaut für eine kurze Zeit nach rechts.
- schau [nach;] unten; [nach;] [unten; runter] schauen; Was ist unten? - schaut für eine kurze Zeit nach unten.
- Schiff [hoch; nach oben] - verschiebt das Schiff ein kleines Stück nach oben.
- Schiff [nach unten; runter] - verschiebt das Schiff ein kleines Stück nach unten.
- Schiff [nach;] links - verschiebt das Schiff ein kleines Stück nach links.
- Schiff [nach;] rechts - verschiebt das Schiff ein kleines Stück nach rechts.
- Schildverteilung; Verteilung der Schilde - meldet die Verteilung der Schildenergie.
- schneller; beschleunigen - erhöht den Schub ein wenig.
- Schub 100; voller Schub; volle Kraft; los los; Vollgas - gibt maximalen SCM-Schub.
- [Schutz;][Schild; Schilde] [nach;] hinten - Schildsteuerung.
- [Schutz;][Schild; Schilde] [nach;] hinten links - Schildsteuerung.
- [Schutz;][Schild; Schilde] [nach;] hinten rechts - Schildsteuerung.
- [Schutz;][Schild; Schilde] [nach;] links - Schildsteuerung.
- [Schutz;][Schild; Schilde] [nach;] rechts - Schildsteuerung.
- [Schutz;][Schild; Schilde] [nach;] [vorn; vorne] - Schildsteuerung.
- [Schutz;][Schild; Schilde] [nach;] [vorn; vorne] links - Schildsteuerung.
- [Schutz;][Schild; Schilde] [nach;] [vorn; vorne] rechts - Schildsteuerung.
- [Schutz;][Schild; Schilde] [reset; normal; standard; zurücksetzen] - Schildsteuerung.
- Selbstzerstörung[ssequenz;] [initiieren; einleiten;] - leitet die Selbstzerstörung des Raumschiffs ein. Kann abgebrochen werden.
- Sicht hinten; Rückspiegel; Sicht achtern - schaltet für eine kurze Zeit auf die Rückkamera.
- Spieldaten; Daten des Spiels; Spielstatistik; Statistik - meldet im Profil gespeicherte Daten wie z.B. die Anzahl der zerstörten Raumschiffe.
- Sprung [abbrechen; Stopp] - stellt den Quantum-Antrieb ab bzw. bricht den Sprung ab.
- Sprung; spring; springe - aktiviert den Quantum-Antrieb.
- Status - gibt Status- und Debug-Meldungen aus. Kann abgebrochen werden.
- Stopp - bricht das automatische Wechseln der Ziele ab.
- Stopp Stopp; Halt Halt; Schub 0; anhalten; Vollbremsung - reduziert den Schub auf Null.
- Taschenlampe; Funzel - schaltet die Taschenlampe ein und aus.
- [ver;][folge; folgen] - Kombination aus "anvisieren" und "anpassen".
- vergrößern; größer - vergrößert die Ansicht ein wenig.
- Vergrößerung [normal; reset; standard; zurücksetzen]; Standard Vergrößerung - setzt die Vergrößerung der Ansicht (Zoom) zurück.
- verkleinern; kleiner - verkleinert die Ansicht ein wenig.
- Vorheriger [Feind; Gegner]; [Feind; Gegner] minus - wechselt zum vorherigen feindlich gesinnten Ziel.
- Vorheriger Freund; Freund minus - wechselt zum vorherigen freundlich gesinnten Ziel.
- Vorheriges Ziel; Ziel minus - wechselt zum vorherigen Ziel.
- [Wie ist die;] Uhrzeit; [Wieviel Uhr; Wieviele Uhr] [ist es;]; Wie spät [ist es;] - nennt die Uhrzeit.
- Wo bin ich - meldet die angenommene Position des Spielers.
- [Ziel; Ziele] wechseln - wechselt in kurzen Abständen das Ziel, bis mit "Stopp" abgebrochen wird.

Legende:
- Baumhaus - Man kann "Baumhaus" sagen.
- Baum; Haus - Man kann "Baum" oder "Haus" sagen.
- Baum[Rinde; Krone] - Man kann "Baumrinde" oder "Baumkrone" sagen.
- Katzen[Minze; Haus;] - Man kann "Katzen", "Katzenminze" oder "Katzenhaus" sagen.

Bemerkungen:

- Das Profil fragt den Spieler manchmal nach seiner Position. Zu wissen, ob er ein Raumschiff steuert, herum läuft oder E.V.A. ist, hilft beim Ausführen der richtigen Aktion. Dann muss man mit "Ich bin draußen" oder "Ich bin am Steuer" antworten (siehe Befehlsliste für alternative Formulierungen).
- Damit das Profil funktioniert, muss VoiceAttack mit Administrator-Rechten laufen. Damit kann es allerdings Windows-Prozesse steuern. Wem das nicht geheuer ist, kann es auf problematische Befehle untersuchen, wie z.B. "Spiel beenden".

Fallstricke und Fehler:

- Das Profil setzt deutsche Tastaturbelegung voraus.
