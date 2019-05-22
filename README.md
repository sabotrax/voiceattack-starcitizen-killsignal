# voiceattack-starcitizen-killsignal
Ein VoiceAttack-Profil für Star Citizen mit dynamischen, kontextbezogenen Inhalten und schwacher KI.

*Das Profil befindet sich in Überarbeitung für Alpha 3.5 und VoiceAttack 1.7.5.*

*Siehe "Alte Version" für weitere Information.*

Es wird die Standard-Tastaturbelegung vorausgesetzt.

Befehle, die in der aktuellen SC-Version funktionieren:

Energie:
- Flugbereitschaft [herstellen;] - macht das Schiff flugbereit.
- [Haupt;] Energie an; volle Energie - Hauptenergie auf 100 %.
- [Haupt;] Energie aus - Hauptenergie auf 0 %. Achtung, schaltet z. Z. das Schiff aus.
- mehr Energie; Energie erhöhen - erhöht die Hauptenergie.
- weniger Energie; Energie [vermindern; verringern] - verringert die Hauptenergie.
- mehr Antrieb; Antrieb verstärken - weist dem Antrieb mehr Energie zu.
- mehr Schilde; Schilde verstärken - weist den Schilden mehr Energie zu.
- mehr Waffen; Waffen verstärken - weist den Waffen mehr Energie zu.
- [normale; standard] Energie[verteilung;]; Energie[verteilung;] [normal; reset; zurücksetzen] - setzt die Energieverteilung zurück.
- Schiff [an; anschalten; aus; ausschalten] - schaltet das Schiff an und aus.
- [Schiffs;] [Antrieb; Maschine; Maschinen; Motor; Motoren] [an; anschalten; aus; ausschalten] - schaltet den Antrieb an und aus.
- [Schiffs;] Waffen [an; anschalten; aus; ausschalten] - schaltet die Waffen an und aus.
- Schilde [an; anschalten; aus; ausschalten] - schaltet die Schilde an und aus.

Flug:
- aktivieren; Energie; spring; springe; springen; Springer; Sprung - führt einen Quantum-Sprung durch. Fragt nach, falls der Quantum-Antrieb nicht aktiviert wurde (siehe "QoL/Auf geht's").
- kreuzen; Tempomat - schaltet den Cruise-Modus an und aus.
- koppeln - koppelt den Antrieb ein und aus.
- Quantum; Sprung [bereit machen; vorbereiten]; Sprungbereitschaft [herstellen;] - schaltet den Quantum-Antrieb an und aus.

HUD:
- Chat - blendet den Chat ein und aus.

Kamera:
- Ansicht; Kamera - wechselt zwischen den Kamerapositionen.

Kampf:
- Abwehr[maßname; maßnamen;] [abfeuern; los; raus]; [Gegenmaßname; Gegenmaßnamen] [abfeuern; los; raus] - löst die aktive Gegenmaßname (Flare/Chaff) aus.
- Abwehr[maßname;maßnamen;] [ändern; tauschen; umschalten; wechseln]; andere Abwehr[maßname; maßnamen;]; andere [Gegenmaßname; Gegenmaßnamen]; [Gegenmaßname; Gegenmaßnamen] [ändern; tauschen; umschalten; wechseln] - wechselt zwischen den Gegenmaßnamen (Flare/Chaff).

Körper:
- Beleuchtung; [Kopf; Taschen;] Lampe; Lampe; Lampen; Licht; Lichter; Scheinwerfer [an; anschalten; aus; ausschalten;] - schaltet die Anzugbeleuchtung an und aus (gleiche Funktion bei "Rumpf").

mobiGlas:
- Alfred; Computer; Moby - blendet MobiGlas ein und aus.
- Karte; Sternenkarte - blendet die Starmap ein und aus.
- Kontakte - blendet die Kontakte ein und aus.

QoL:
- Auf geht's; Auf jeden [Fall;]; Bestätige; Ja [bitte; gerne; ist es; klar; Mama; schon; sicher; sicherlich; sind wir]; Ja wohl; jawoll; [Klar; Sicher] [doch;]; Mach [mal; schon]; Natürlich; Sicherlich - dient zur Bestätigung von Nachfragen bei z. B. "abheben" oder "landen".
- nochmal; wiederholen - wiederholt den letzten Befehl. Funktioniert nur, wo es sinnvoll ist.

Rumpf:
- Beleuchtung; [Kopf; Taschen;] Lampe; Lampe; Lampen; Licht; Lichter; Scheinwerfer [an; anschalten; aus; ausschalten;] - schaltet die Fahrzeugbeleuchtung an und aus (gleiche Funktion bei "Körper").
- Fahrwerk; Landemodus - fährt das Fahrwerk aus und ein.
- landen - aktiviert die automatische Landung. Funktioniert nur, wenn man mit Landeerlaubnis über einer Pad schwebt. Fragt nach, falls das Fahrwerk nicht ausgefahren wurde (siehe "QoL/Auf geht's").

Sensoren:
- Aufklärungsmodus - wechselt in den Scannermodus und zurück.

UI:
- [Einladung;] ablehnen; ausblenden; ignorieren - lehnt Einladungen ab.
- [Einladung;] annehmen - nimmt Einladungen an.

Fallstricke:
- Star Citizen liefert keinen Information über seinen inneren Zustand (im Gegensatz zu Elite Dangerous). Deswegen kann VoiceAttack nicht wissen, ob der Quantum-Antrieb wirklich aktiviert wurde nachdem der Befehl gegeben wurde. Vielleicht war die Chateingabe aktiv und "b" ist dort gelandet. Deswegen ist dieses Profil auf keinen Fall narrensicher und leicht zu täuschen. Ich habe dafür noch keine Lösung und bitte, es mir nachzusehen.

**Alte Version:**

Kompatibel mit Alpha 2.6.3 und VoiceAttack 1.6.6

BETA!

Über VoiceAttack:

VoiceAttack setzt Sprache in Tastatur- und Mauseingaben um.
So lassen sich Spiele wie Star Citizen einfacher steuern.

Über dieses Profil:

Das Profil soll nützlich, robust und intuitiv zu bedienen sein. Es soll außerdem den Eindruck schwacher KI vermitteln, welcher durch vielfältige Antworten, scheinbar eigenständige Handlungen und erweiterbares Wissen erreicht werden soll. Das Profil weist einen leicht zynischen Charakter auf. Es gibt auch ein Video https://www.youtube.com/watch?v=zLD67eXXc6c&t

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

- [1/2; 50 Prozent; halbe; halber; mittlere; mittlerer] [Fahrt; Impuls; Kraft; Schub] [voraus;]; [Fahrt; Schub] 50 [Prozent;]; Voraus [Halbe; Halber] - stellt den Schub auf ca. 50%.
- [1/4; 25 Prozent; kleine; kleiner; langsame; langsamer; Viertel] [Fahrt; Impuls; Kraft; Schub] [voraus;]; [Fahrt; Schub] 25 [Prozent;]; Voraus [Kleine; Kleiner] - stellt den Schub auf ca. 25%.
- [100 Prozent; voll; voller] [Fahrt; Impuls; Kraft; Schub] [voraus;]; Äußerste Fahrt voraus; [Fahrt; Schub] 100 [Prozent;]; los los; Vollgas; Voraus [Volle; Voller] - stellt den Schub auf 100%.
- [3/4; 75 Prozent; große; großer] [Fahrt; Impuls; Kraft; Schub] [voraus;]; [Fahrt; Schub] 75 [Prozent;]; Voraus [Große; Großer] - stellt den Schub auf ca. 75%.
- abbrechen; Abbruch; aufhören; hör [damit;] auf [damit;]; [tu; tut] das nicht - bricht alle laufenden Vorgänge ab: die Selbstzerstörung des Schiffs, das Beenden des Star Citizen Prozesses.
- abheben; los fliegen; Start; starten - lässt das Schiff ein paar Meter abheben und wechselt vom Lande- in den Flugmodus.
- Abwehr[maßname; maßnamen;] [abfeuern; los; raus]; [Gegenmaßname; Gegenmaßnamen] [abfeuern; los; raus] - löst die aktive Gegenmaßname (Flare/Chaff) aus.
- Abwehr[maßname;maßnamen;] [ändern; tauschen; umschalten; wechseln]; andere Abwehr[maßname; maßnamen;]; andere [Gegenmaßname; Gegenmaßnamen]; [Gegenmaßname; Gegenmaßnamen] [ändern; tauschen; umschalten; wechseln] - wechselt zwischen den Gegenmaßnamen (Flare/Chaff).
- Alfred; Moby - zeigt mobiGlass oder blendet es aus.
- anhalten; Halt Halt; [Maschine; Maschinen] stopp; Schub 0 [Prozent;]; Stopp Stopp; Vollbremsung; Voller Stopp - reduziert den Schub auf 0%.
- anpassen - passt die eigene Schiffsgeschwindigkeit an die des Ziels an.
- anvisieren; Focus; focussieren - wählt das Ziel unter dem Fadenkreuz aus.
- Anzug [anhalten; halt; stop] - beendet den Vorwärtsschub des Raumanzugs (gedacht für E.V.A.).
- Anzug [go; los; vorwärts] - lässt den Raumanzug mit Shift-Boost vorwärts schieben (gedacht für E.V.A.).
- Auf geht's; Auf jeden [Fall;]; Bestätige; Ja [bitte; gerne; ist es; klar; Mama; schon; sicher; sicherlich; sind wir]; Ja wohl; jawoll; [Klar; Sicher] [doch;]; Mach [mal; schon]; Natürlich; Sicherlich - dient zur Bestätigung von Nachfragen bei z. B. "abheben" oder "landen".
- ausführlich; gesprächig - ändert den Sprachstil.
- Beende [Programm; Prozess; Spiel]; [Programm; Prozess; Spiel] beenden - Beendet Star Citizen. Kann abgebrochen werden.
- Beleuchtung; Licht; Scheinwerfer - schaltet die Schiffsbeleuchtung ein und aus.
- beschleunigen; gas geben; schneller - erhöht den Schub ein wenig.
- [Bin; ich bin;] am Steuer *Schiffstyp* - teilt dem Profil mit, dass man ein Raumschiff steuert. Zusätzlich kann man den Typ des Schiffs angeben (wie in "Bin am Steuer einer Freelancer"). Das ist nicht zwingend nötig, aber es beeinflusst andere Funktionen wie z. B. "Monitor zeigen" (diese sind in verschiedenen Schiffen unterschiedlich angebracht) oder "Schleudersitz" (manche Schiffe haben keinen).
- bremsen; langsamer; verzögern - verringert den Schub ein wenig.
- Chat - zeigt das Chat-Fensters oder blendet es aus.
- [Daten; Statistik] des Spiels; Spiel[daten; statistik]; Statistik - meldet im Profil gespeicherte Daten wie z. B. die Anzahl der zerstörten Raumschiffe.
- [Die;] [oben; oberen; unten; unteren] [darstellen; zeigen;] - Schaut auf die entsprechenden Monitore, wenn kein Schiffstyp angegeben wurde, aber "Monitor zeigen" befohlen wurde.
- aktivieren; Energie; spring; springe; springen; Springer; Sprung - aktiviert den Quantum-Antrieb.
- [Feind; Gegner] minus; Vorheriger [Feind; Gegner] - wechselt zum vorherigen feindlich gesinnten Ziel.
- [Feind; Gegner] plus; Nächster [Feind; Gegner] - wechselt zum nächsten feindlich gesinnten Ziel.
- Fluchtsprung; Notsprung; [spring; springe; springer] weg - führt einen kurzen Quantum-Sprung ohne Zielauswahl durch.
- Flugcomputer; Flugsicherheit; Flusi - wechselt die Zustände von COMSTAB und G-SAFE.
- [Freund; Verbündeter] minus; Vorheriger [Freund; Verbündeter] - wechselt zum vorherigen freundlich gesinnten Ziel.
- [Freund; Verbündeter] plus; Nächster [Freund; Verbündeter] - wechselt zum nächten freundlich gesinnten Ziel.
- Funzel; Taschenlampe - schaltet die Taschenlampe ein und aus.
- [geringste; geringster; 5 Prozent] [Fahrt; Impuls; Kraft; Schub] [voraus;]; [Fahrt; Schub] 5 [Prozent;]; Voraus [Geringste; Geringster] - stellt den Schub auf ca. 5%.
- [Gibt's; gibt es] [etwas Neues; was Neues; Neuigkeiten]; Lies die Nachrichten [vor;]; Was [gibt's; gibt es] [für Neuigkeiten; Neues] - besorgt Nachrichten rund um Star Citizen und liest sie vor. Kann abgebrochen werden.
- größer; vergrößern - vergrößert die Ansicht ein wenig.
- häng dich dran; hinterher; [ver;][folge; folgen] - Kombination aus "anvisieren" und "anpassen".
- Harakiri; Seppuku - Erzwingt einen Respawn. Verlangt nach Bestätigung. Funktioniert nur "draußen".
- [Ich;] bin draußen - teilt dem Profil mit, dass man zu Fuß oder E.V.A. ist.
- [Ich;] bin gelandet - teilt dem Pofil mit, dass man gelandet ist (aktiviert aber nicht den Landemodus).
- initialisieren; zurücksetzen - setzt die Konfiguration zurück. Hilfreich, wenn ein neues Spiel begonnen wird oder das Profil nicht mehr funktioniert.
- Kamera; Kammerer - wechselt die Kameraposition.
- kleiner; verkleinern - verkleinert die Ansicht ein wenig.
- knapp - ändert den Sprachstil.
- koppeln - koppelt den Antrieb ein und aus.
- [Lade;] [Programm; Steuerung] Joystick; Lade [Programm; Steuerung;] Joystick - Sperrt Gimbal und schaltet Look Ahead aus.
- [Lade;] [Programm; Steuerung] Maus; Lade [Programm; Steuerung;] Maus - Löst Gimbal und schaltet Look Ahead ein.
- Landemodus - aktiviert den Landemodus.
- landen - leitet die automatische Landung ein (funktioniert nur in der Zone für die automatische Landung).
- Mauszeiger - blendet den UI Mauszeiger ein und aus.
- [maximale; maximal; volle] Vergrößerung - vergrößert die Ansicht (Zoom) maximal.
- [oberen; unteren;] [Monitor; Monitore] [oben; unten;] [zeigen;]; zeige [oberen; unteren;] [Monitor; Monitore] [oben; unten;] - schaut auf die Monitore, wenn der Schiffstyp angegeben wurde und dies eindeutig möglich ist (siehe "[Bin; ich bin;] am Steuer"). Schaut sonst in die angegeben Richtung. Fragt ohne Richtungsangabe nach, wohin es schauen soll. Alle Aktionen bis Abbruch.
- [nach;] links schauen; schau [nach;] links; was ist links; [zeig; zeige] links - schaut für eine kurze Zeit nach links.
- [nach;] [oben; hoch] schauen; schau [nach;] [oben; hoch]; was ist oben; zeige oben - schaut für eine kurze Zeit nach oben.
- [nach;] rechts schauen; schau [nach;] rechts; was ist rechts; zeige rechts - schaut für eine kurze Zeit nach rechts.
- [nach;] [unten; runter] schauen; schau [nach;] unten; was ist unten; zeige unten - schaut für eine kurze Zeit nach unten.
- Nächstes Ziel; Ziel plus - wechselt zum nächsten Ziel.
- Noch ein Schiff zerstört - erhöht den im Profil gespeicherten Zähler der abgeschossenen Raumschiffe um eins.
- nochmal; wiederholen - wiederholt den kürzlich gegebenen Befehl. Funktioniert nur, wo es sinnvoll ist.
- Quantum - aktiviert die Zielauswahl des Quantum-Antriebs.
- [Rakete; Raketen] [abfeuern; los; starten] - feuert eine Rakete auf das aufgeschaltete Ziel ab.
- Rakete; Raketen [aufschalten;] - schaltet eine Rakete auf das ausgewählte Ziel auf.
- Rückspiegel; Sicht [nach;] [achtern; hinten; rückwärts]; was ist hinten - schaltet für eine kurze Zeit auf die Rückkamera.
- Schiff [hoch; nach oben] - verschiebt das Schiff ein kleines Stück nach oben.
- Schiff [nach unten; runter] - verschiebt das Schiff ein kleines Stück nach unten.
- Schiff [nach;] links - verschiebt das Schiff ein kleines Stück nach links.
- Schiff [nach;] rechts - verschiebt das Schiff ein kleines Stück nach rechts.
- Schildverteilung; Verteilung der Schilde - meldet die Verteilung der Schildenergie.
- Schleudersitz - betätigt den Schleudersitz. Funktioniert nur, wenn der Schiffstyp angegeben wurde (siehe "[Bin; ich bin;] am Steuer").
- [Schutz;][Schild; Schilde] [nach;] hinten - Schildsteuerung.
- [Schutz;][Schild; Schilde] [nach;] hinten links - Schildsteuerung.
- [Schutz;][Schild; Schilde] [nach;] hinten rechts - Schildsteuerung.
- [Schutz;][Schild; Schilde] [nach;] links - Schildsteuerung.
- [Schutz;][Schild; Schilde] [nach;] rechts - Schildsteuerung.
- [Schutz;][Schild; Schilde] [nach;] [vorn; vorne] - Schildsteuerung.
- [Schutz;][Schild; Schilde] [nach;] [vorn; vorne] links - Schildsteuerung.
- [Schutz;][Schild; Schilde] [nach;] [vorn; vorne] rechts - Schildsteuerung.
- [Schutz;][Schild; Schilde] [normal; reset; standard; zurücksetzen] - Schildsteuerung.
- Selbstzerstörung[ssequenz;] [einleiten; initiieren;] - leitet die Selbstzerstörung des Raumschiffs ein. Kann abgebrochen werden.
- kein Sprung; nicht springen; Sprung [abbrechen; Abbruch; halt; Stopp] - stellt den Quantum-Antrieb ab bzw. bricht den Sprung ab.
- Status - gibt Status- und Debug-Meldungen aus. Kann abgebrochen werden.
- Stopp - bricht das automatische Wechseln der Ziele ab.
- Vergrößerung [normal; reset; standard; zurücksetzen]; Standard Vergrößerung - setzt die Vergrößerung der Ansicht (Zoom) zurück.
- Version - nennt die Version des Profils.
- Vorheriges Ziel; Ziel minus - wechselt zum vorherigen Ziel.
- [Wie ist die;] Uhrzeit; [Wieviel Uhr; Wieviele Uhr] [ist es;]; Wie spät [ist es;] - nennt die Uhrzeit.
- Wo bin ich - meldet die angenommene Position des Spielers und - falls bekannt - das Schiff, in dem er sich aufhält.
- [Ziel; Ziele] wechseln - wechselt in kurzen Abständen das Ziel, bis mit "Stopp" abgebrochen wird.

Legende:
- Baumhaus - Man kann "Baumhaus" sagen.
- Baum; Haus - Man kann "Baum" oder "Haus" sagen.
- Baum[Rinde; Krone] - Man kann "Baumrinde" oder "Baumkrone" sagen.
- Katzen[Minze; Haus;] - Man kann "Katzen", "Katzenminze" oder "Katzenhaus" sagen.

Bemerkungen:

- Das Profil fragt den Spieler manchmal nach seiner Position. Zu wissen, ob er ein Raumschiff steuert, herum läuft oder E.V.A. ist, hilft beim Ausführen der richtigen Aktion. Dann muss man mit "Ich bin draußen" oder "Ich bin am Steuer" antworten (siehe Befehlsliste für alternative Formulierungen).
- Damit das Profil funktioniert, muss VoiceAttack mit Administrator-Rechten laufen. Damit kann es allerdings Windows-Prozesse steuern. Wem das nicht geheuer ist, kann es auf problematische Befehle untersuchen, wie z. B. "Spiel beenden".

Fallstricke und Fehler:

- Das Profil setzt deutsche Tastaturbelegung voraus.
- Das Profil spricht mithilfe des internen Windows TTS (Text-To-Speech). Sätze werden so fomuliert, dass sie sich mit der weiblichen Standard-Stimme Hedda von Windows 10 gut anhören. Als Folge davon kann es sein, dass andere Stimmen, die für sich vielleicht besser als Hedda sind, hier falsch klingen.
- Die Befehl "Anzug los" kann die Tastatureingabe von Windows stören, wenn man die Anwendung wechselt, während er noch aktiv ist.
- Die Befehle zum absoluten Regeln des Schubs funtionieren nur mit Schwankungen. So kann "halbe Kraft voraus" 48 %, aber auch 55 % Schub bedeuten.
- "Fluchtsprung" funktioniert manchmal nicht. Der Befehl aktiviert dann zwar den QD-Antrieb, aber es wird kein Sprung ausgelöst.
- "Monitor zeigen" funktioniert nicht sinnvoll in Schiffen wie der Constellation, da sich die MFDs dort an Plätzen befinden, die nicht mit einem einzigen Blick überschaut werden können (oben, unten).

Schiffstypen:

Mancher Name hört sich albern an. Das liegt daran, dass die deutsche Spracherkennung sich mit Wörtern wie "Retaliator" schwer tut. In diesen Fällen musste ich mir etwas ausdenken. Für alternative Bezeichnungen bin ich dankbar.

- 300, 315, 325, 350
- 85, 85x
- Aurora, Polarlicht
- Avenger = Pinguin, Rächer
- Caterpillar = Raupe
- Constellation = Conny
- Cutlass = Badewanne, Machete
- Freelancer
- Gladiator, leichten Bomber
- Gladius = Kurzschwert
- Glaive = Gleve
- Herald, Herold
- Hornet, Hornisse
- M50
- Merlin
- MPUV = Transporter
- Mustang
- Reliant = Motte
- Retaliator = schweren/schwerer Bomber, Vergelter
- Sabre = Säbel
- Scythe = Sense
- Starfarer = Tanker
- Vanguard = Speerspitze, Vorhut, Vorreiter
