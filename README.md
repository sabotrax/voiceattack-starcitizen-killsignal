# voiceattack-starcitizen-killsignal
Ein einfaches VoiceAttack-Profil für Star Citizen

BETA und kompatibel mit SC Alpha 2.6.

VoiceAttack setzt Sprache in Tastatur- und Mauseingaben um.
So lassen sich Spiele wie Star Citizen einfacher steuern.

Um dieses Profil einsetzen zu können, müssen ein paar Vorbereitungen getroffen werden:

1. VoiceAttack von http://www.voiceattack.com/ besorgen und installieren.
Die Probe-Version (Trial) reicht nicht aus, weil das Profil deren Umfang sprengt.
2. Die Spracherkennung von Windows trainieren (bei Win 7 unter Systemsteuerung.
-> Spracherkennung -> Trainieren Sie den Computer..). Das Training zwei bis dreimal durchführen.
3. killsignal-26.vap downloaden, VoiceAttack als Administrator starten, Profil importieren (Icon mit Plus-Zeichen).
Eine eventuelle Warnung, dass das Profil auf andere Anwendungen zugreifen will, kann ignoriert werden (siehe Bemerkungen).
4. Star Citizen starten.
5. Beim ersten Start fragt das Profil nach dem bevorzugten Sprachstil. Der Standard ist "gesprächig",
es geht aber auch "knapp". VoiceAttack neu starten, falls die Frage nicht gestellt wird.

Das Profil beherrscht folgende Befehle (Legende unten):

- Abbruch; abbrechen - bricht alle laufenden Vorgänge ab: die Selbstzerstörung des Schiffs, das Beenden des Star Citizen Prozesses.
- abheben; starten; Start - lässt das Schiff ein paar Meter abheben und wechselt vom Lande- in den Flugmodus.
- Abwehr[maßname; maßnamen;] [raus; abfeuern]; [Gegenmaßname; Gegenmaßnamen] [raus; abfeuern] - löst die aktive Gegenmaßname (Flare/Chaff) aus.
- Abwehr[maßname;maßnamen;] [wechseln; tauschen]; [Gegenmaßname; Gegenmaßnamen] [wechseln; tauschen] - wechselt zwischen den Gegenmaßnamen (Flare/Chaff).
- anpassen - passt die eigene Schiffsgeschwindigkeit kontinuierlich an die des Ziels an.
- anvisieren; focussieren; Focus - wählt das Ziel unter dem Fadenkreuz aus.
- Anzug [stop; anhalten; halt] - beendet den Vorwärtsschub des Raumanzugs (gedacht für E.V.A.).
- Anzug [vorwärts; los; go] - lässt den Raumanzug mit Shift-Boost vorwärts schieben (gedacht für E.V.A.).
- Beende Spiel; Spiel beenden; Prozess beenden; Beende Prozess - Beendet Star Citizen. Kann abgebrochen werden.
- Chat - zeigt das Chat-Fensters oder blendet es aus.
- gesprächig; ausführlich - ändert den Sprachstil.
- [Ich;] bin draußen - teilt dem Profil mit, dass man zu Fuß oder E.V.A. ist.
- [Ich;] bin gelandet - teilt dem Pofil mit, dass man gelandet ist (aktiviert aber nicht den Landemodus).
- [Ich;] [bin; sitz; sitze;] am Steuer [und gelandet;] - teilt dem Profil mit, dass man ein Raumschiff steuert (und es gelandet ist).
- initialisieren - setzt die Konfiguration zurück. Hilfreich, wenn das Profil nicht mehr funktioniert.
- Kamera; Kammerer - wechselt die Kameraposition.
- knapp - ändert den Sprachstil.
- [Lade;] [Steuerung; Programm] Joystick; Lade [Steuerung; Programm;] Joystick - Sperrt Gimbal und schaltet Look Ahead Modus aus.
- [Lade;] [Steuerung; Programm] Maus; Lade [Steuerung; Programm;] Maus - Löst Gimbal und schaltet Look Ahead Modus ein.
- Landemodus - aktiviert den Landemodus.
- landen - leitet die automatische Landung ein (funktioniert nur in der Zone für die automatische Landung).
- langsamer; bremsen - verringert den Schub ein wenig.
- Licht; Beleuchtung; Scheinwerfer - schaltet die Schiffsbeleuchtung ein und aus.
- [maximale; maximal; volle] Vergrößerung - vergrößert die Ansicht (Zoom) maximal.
- Moby - zeigt mobiGlass oder blendet es aus.
- Noch ein Schiff zerstört - erhöht den im Profil gespeicherten Zähler der zerschmetterten Feindfahrzeuge um eins.
- Quantum - aktiviert die Zielauswahl des Quantum-Antriebs.
- [Rakete; Raketen] [abfeuern; los; starten] - feuert eine Rakete auf das ausgewählte Ziel ab.
- Rakete; Raketen [aufschalten;] - schaltet eine Rakete auf das ausgewählte Ziel auf.
- schau [nach;] links; [nach;] links schauen - schaut für eine kurze Zeit nach links.
- schau [nach;] [oben; hoch]; [nach;] [oben; hoch] schauen - schaut für eine kurze Zeit nach oben.
- schau [nach;] rechts; [nach;] rechts schauen - schaut für eine kurze Zeit nach rechts.
- schau [nach;] unten; [nach;] [unten; runter] schauen - schaut für eine kurze Zeit nach unten.
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
- Spieldaten; Daten des Spiels - meldet im Profil gespeicherte Daten wie z.B. die Anzahl der zerstörten Raumschiffe.
- Sprung [abbrechen; Stopp] - stellt den Quantum-Antrieb ab bzw. bricht den Sprung ab.
- Sprung; spring; springe - aktiviert den Quantum-Antrieb.
- Status - gibt Status- und Debug-Meldungen aus. Kann abgebrochen werden.
- Stopp - bricht das automatische Wechseln der Ziele ab.
- Stopp Stopp; Halt Halt; Schub 0; anhalten; Vollbremsung - reduziert den Schub auf Null.
- Taschenlampe; Funzel - schaltet die Taschenlampe ein und aus.
- [ver;][folge; folgen] - Kombination aus "anvisieren" und "anpassen".
- vergrößern; größer - vergrößert die Ansicht ein wenig.
- Vergrößerung zurücksetzen; Standardvergrößerung - setzt die Vergrößerung der Ansicht (Zoom) zurück.
- verkleinern; kleiner - verkleinert die Ansicht ein wenig.
- [Wie ist die;] Uhrzeit; [Wieviel Uhr; Wieviele Uhr] [ist es;]; Wie spät [ist es;] - nennt die Uhrzeit.
- Wo bin ich - meldet die angenommene Position des Spielers.
- [Ziel; Ziele] wechseln - wechselt in kurzen Abständen das Ziel, bis mit "Stopp" abgebrochen wird.

Legende:
- Baumhaus - Man kann "Baumhaus" sagen.
- Baum; Haus - Man kann "Baum" oder "Haus" sagen.
- Baum[Rinde; Krone] - Man kann "Baumrinde" oder "Baumkrone" sagen.
- Katzen[Minze; Haus;] - Man kann "Katzen", "Katzenminze" oder "Katzenhaus" sagen.

Bemerkungen:

- Ziel ist es, das Spiel intuitiv bedienen zu können. Gleichzeitig soll das Profil unanfällig gegen Fehler sein. Deswegen fragt es oft nach der Position des Spielers. Zu wissen, ob er ein Raumschiff steuert, herum läuft oder E.V.A. ist, hilft dem Profil, die richtigen Aktionen auszuführen. Man kann dem Profil helfen, indem man ihm nach Positionswechseln sagt, wo man sich befindet.
- Damit das Profil funktioniert, muss VoiceAttack im Admin-Modus laufen. Damit kann VoiceAttack Windows-Prozesse steuern. Wem das mit einem fremden Profil nicht geheuer ist, der kann es auf problematische Befehle überprüfen, wie z.B. "Spiel beenden".

Fehler:

- Wenn man Sprach- und Tastatureingaben bei zusammenhängenden Aktionen wie "Quantum" und "Sprung" mischt, kann es zu Fehlern kommen. Sagt man bespielsweise "Quantum" und drückt dann "F", um den Sprung auszulösen, so wird ein nachfolgender Sprungversuch abgelehnt. Dann hilft "initialisieren".
- Wenn man ein Profil neu importiert, gehen alle gespeicherten Daten, wie die Zahl der Abschüsse, verloren.
