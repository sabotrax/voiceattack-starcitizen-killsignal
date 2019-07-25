# voiceattack-starcitizen-killsignal
Ein VoiceAttack-Profil für Star Citizen mit dynamischen, kontextbezogenen Inhalten und schwacher KI.

Über VoiceAttack:

VoiceAttack setzt gesprochene Anweisungen in Tastatur- und Mauseingaben um.
So lassen sich Spiele wie Star Citizen einfacher steuern.

Über dieses Profil:

Das Profil soll nützlich, robust und intuitiv zu bedienen sein. Es soll außerdem den Eindruck schwacher KI vermitteln, welcher durch vielfältige Antworten, scheinbar eigenständige Handlungen und erweiterbares Wissen erreicht werden soll. Das Profil weist einen leicht zynischen Charakter auf.

Installation:

- VoiceAttack von http://www.voiceattack.com/ besorgen und installieren. Die Probe-Version (Trial) reicht nicht aus.
- Die Spracherkennung von Windows trainieren (bei Windows 7 unter Systemsteuerung -> Spracherkennung -> Trainieren Sie den Computer). Das Training zwei bis dreimal durchführen.
- killsignal-36.vap downloaden, VoiceAttack als Administrator starten und Profil importieren (Icon mit Plus-Zeichen). Die Warnung, dass das Profil auf andere Anwendungen zugreifen will, kann ignoriert werden (siehe Bemerkungen).
- Beim ersten Start fragt das Profil nach dem bevorzugten Sprachstil. Standard ist "gesprächig", es geht aber auch "knapp". VoiceAttack neu starten, falls die Frage nach dem Sprachstil nicht gestellt wird.

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

Es wird die Standard-Tastaturbelegung vorausgesetzt. Ausnahmen stehen beim entsprechenden Befehl.

Legende zum Verständnis der Befehle:
- Baumhaus - Man kann "Baumhaus" sagen.
- Baum; Haus - Man kann "Baum" oder "Haus" sagen (Strichpunkte trennen Befehle).
- Baum[Rinde; Krone] - Man kann "Baumrinde" oder "Baumkrone" sagen (Klammern gruppieren sie).
- Katzen[Minze; Haus;] - Man kann "Katzen", "Katzenminze" oder "Katzenhaus" sagen (Ein Strichpunkt am Ende macht den Teil optional).

Liste der Befehle:

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
- abheben; los fliegen; Start; starten - lässt das Schiff ein paar Meter abheben und wechselt vom Lande- in den Flugmodus. Versucht, bei Bedarf das Schiff bzw. die Maschinen zu starten.
- aktivieren; Energie; spring; springe; springen; Springer; Sprung - führt einen Quantum-Sprung durch. Fragt nach, falls der Quantum-Antrieb nicht aktiviert wurde (siehe "QoL/Auf geht's").
- [Bremse; bremsen; verzögern] [halten;] - aktiviert Spacebrake für eine kurze Zeit. Mit "halten" wird dauerhaft gebremst bis "abbrechen" (siehe "QoL/abbrechen").
- kreuzen; Tempomat - schaltet den Cruise-Modus an und aus.
- koppeln - koppelt den Antrieb ein und aus.
- Quantum; Sprung [bereit machen; vorbereiten]; Sprungbereitschaft [herstellen;] - schaltet den Quantum-Antrieb an und aus.

HUD:
- anvisieren; Focus; focussieren - wählt das Ziel unter dem Fadenkreuz aus.
- [Feind; feindliches Ziel; Gegner; Nahziel; Rot] aufschalten - nächstgelegenen Gegner auswählen.
- [Feind; Gegner; Rot] minus; Vorheriger [Feind; Gegner; Rot] - wechselt zum vorherigen Gegner.
- [Feind; Gegner; Rot] plus; Nächster [Feind; Gegner; Rot] - wechselt zum nächsten Gegner.
- [Freund; Gegner; Grün; Rot; Sonderziel; Ziel] merken - Ziel pinnen.
- [Freund; Grün; Verbündeter] minus; Vorheriger [Freund; Grün; Verbündeter] - wechselt zum vorherigen freundlich gesinnten Ziel.
- [Freund; Grün; Verbündeter] plus; Nächster [Freund; Grün; Verbündeter] - wechselt zum nächsten freundlich gesinnten Ziel.
- nächstes [Subziel; Teilziel] [aufschalten;]; [Subziel; Teilziel] plus - nächstes Untersystem des Ziels anvisieren.
- vorheriges [Subziel; Teilziel] [aufschalten;]; [Subziel; Teilziel] minus - vorheriges Untersystem des Ziels anvisieren.
- Sonderziel minus; vorheriges Sonderziel - wechselt zum vorherigen gepinnten Ziel.
- Sonderziel plus; nächstes Sonderziel - wechselt zum nächsten gepinnten Ziel.
- [Subziel; Teilziel] [normal; reset; standard; zurücksetzen] - Auswahl der Untersysteme aufheben.

Kamera:
- Ansicht; Kamera - wechselt zwischen den Kamerapositionen.
- Rückspiegel [halten;]; Sicht [nach;] [achtern; hinten; rückwärts] [halten;]; was ist hinten [halten;] - schaltet für kurze Zeit auf die Rückkamera. Mit "halten" wird die Umschaltung dauerhaft bis "abbrechen" (siehe "QoL/abbrechen"). Taste LALT + Y.

Kampf:
- Abwehr[maßname; maßnamen;] [abfeuern; los; raus]; [Gegenmaßname; Gegenmaßnamen] [abfeuern; los; raus] - löst die aktive Gegenmaßname (Flare/Chaff) aus.
- Abwehr[maßname;maßnamen;] [ändern; tauschen; umschalten; wechseln]; andere Abwehr[maßname; maßnamen;]; andere [Gegenmaßname; Gegenmaßnamen]; [Gegenmaßname; Gegenmaßnamen] [ändern; tauschen; umschalten; wechseln] - wechselt zwischen den Gegenmaßnamen (Flare/Chaff).

Konfiguration:
- Sprachstil [ändern; wechseln] - leitet die Änderung des Sprachstils ein. Das Profil kann seine Antworten "knapp" halten oder "ausführlich" bzw. "gesprächig" sein.

Körper:
- Beleuchtung; [Kopf; Taschen;] Lampe; Lampe; Lampen; Licht; Lichter; Scheinwerfer [an; anschalten; aus; ausschalten;] - schaltet die Anzugbeleuchtung an und aus (gleiche Funktion bei "Rumpf").

MobiGlas:
- Computer; Mobi - blendet MobiGlas ein und aus.
- Karte; Sternenkarte - blendet die Starmap ein und aus.
- Kontakte - blendet die Kontakte ein und aus.

QoL:
- abbrechen; Abbruch; aufhören; hör [damit;] auf [damit;]; [tu; tut] das nicht - bricht alle laufenden Vorgänge ab.
- Auf geht's; Auf jeden [Fall;]; Bestätige; Ja [bitte; gerne; ist es; klar; Mama; schon; sicher; sicherlich; sind wir]; Ja wohl; jawoll; [Klar; Sicher] [doch;]; Mach [mal; schon]; Natürlich; Sicherlich - dient zur Bestätigung von Nachfragen bei z. B. "abheben" oder "landen".
- Beende [Programm; Prozess; Spiel]; [Programm; Prozess; Spiel] beenden - Beendet Star Citizen. Verlangt Bestätigung. Kann abgebrochen werden (siehe "QoL/abbrechen").
- nochmal; wiederholen - wiederholt den letzten Befehl. Funktioniert nur, wo es sinnvoll ist.

Rumpf:
- Beleuchtung; [Kopf; Taschen;] Lampe; Lampe; Lampen; Licht; Lichter; Scheinwerfer [an; anschalten; aus; ausschalten;] - schaltet die Fahrzeugbeleuchtung an und aus (gleiche Funktion bei "Körper").
- Fahrwerk; Landemodus - fährt das Fahrwerk aus und ein.
- landen - aktiviert die automatische Landung. Funktioniert nur, wenn man mit Landeerlaubnis über einem Pad schwebt. Fragt nach, falls das Fahrwerk nicht ausgefahren wurde (siehe "QoL/Auf geht's").
- Notausstieg; Schleudersitz; Sofort raus hier - betätigt den Schleudersitz.
- [Schiff; Tür; Türen] [entsperren; sperren] - sperrt die Türen, Fahrstühle und Rampen des Schiffs auf und zu.
- [Schiff; Tür; Türen] [öffnen; schließen] - öffnet die Türen, Fahrstühle und Rampen des Schiffs und schließt sie.

Sensoren:
- Aufklärungsmodus; Scanmodus - wechselt zum Scanmodus und zurück.

UI:
- Chat - blendet den Chat ein und aus.
- [Einladung;] ablehnen; ausblenden; ignorieren - lehnt Einladungen ab.
- [Einladung;] [annehmen; akzeptieren] - nimmt Einladungen an.

Fallstricke:
- Star Citizen liefert keine Information über seinen inneren Zustand. Deswegen kann VoiceAttack nicht wissen, ob der Quantum-Antrieb wirklich aktiviert wurde nachdem der Befehl gegeben wurde. Vielleicht war die Chateingabe aktiv und "b" ist dort gelandet. Deswegen ist dieses Profil auf keinen Fall narrensicher und leicht zu täuschen.
