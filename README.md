# voiceattack-starcitizen-killsignal
Ein VoiceAttack-Profil für Star Citizen mit dynamischen, kontextbezogenen Inhalten und schwacher KI.

Über VoiceAttack:

VoiceAttack setzt gesprochene Anweisungen in Tastatur- und Mauseingaben um.
So lassen sich Spiele wie Star Citizen einfacher steuern.

Über dieses Profil:

Das Profil soll nützlich, robust und intuitiv zu bedienen sein. Es soll außerdem den Eindruck schwacher KI vermitteln, welcher durch vielfältige Antworten, scheinbar eigenständige Handlungen und erweiterbares Wissen erreicht werden soll. Das Profil weist einen leicht zynischen Charakter auf.

**Installation:**

- VoiceAttack von http://www.voiceattack.com/ besorgen und installieren. Die Probe-Version (Trial) reicht nicht aus.
- Die Spracherkennung von Windows trainieren (bei Windows 10 unter Systemsteuerung -> Spracherkennung -> Computer trainieren, damit er Sie besser versteht). Das Training mehrmals durchführen.
- killsignal-391.vap downloaden, VoiceAttack als Administrator starten und Profil importieren (Icon mit Plus-Zeichen). Die Warnung, dass das Profil auf andere Anwendungen zugreifen will, kann ignoriert werden (siehe Bemerkungen).
- Beim ersten Start fragt das Profil nach dem bevorzugten Sprachstil. Standard ist "gesprächig", es geht aber auch "knapp". VoiceAttack neu starten, falls die Frage nach dem Sprachstil nicht gestellt wird.

**Upgrade:**

Es gibt zwei Möglichen. Die erste ist etwas umständlicher, aber es bleiben die statistischen Daten erhalten.

- In VoiceAttack auf "Edit Profile" klicken (rechteckiges Icon mit Stift).
- Im neu geöffneten Fenster auf "Import Commands" klicken (unten links).
- Im nächsten Fenster das neue Profil auswählen und öffnen.
- Im nächsten Fenster auf "Import" klicken (unten rechts).
- Die folgenden zwei Warnungen bestätigen.
- Das Fenster "Edit Profile" mit Klick auf "Done" schließen (unten rechts).

Die zweite Möglichkeit besteht darin, das vorhandene Profil zu löschen und durch das neue zu ersetzen.

- In VoiceAttack auf "More Profile Actions" klicken (Icon mit Plus-Zeichen).
- "Import Profile" auswählen und das Profil importieren. Es wird dabei umbenannt, weil es den gleichen Namen hat.
- "Delete Profile" auswählen und das alte Profil löschen.
- Wenn gewünscht, auf "Edit Profile" klicken (Icon mit Stift) und den Namen im oberen Textfeld zurück ändern.

Es wird die Standard-Tastaturbelegung vorausgesetzt. Ausnahmen stehen beim entsprechenden Befehl.

**Legende zum Verständnis der Befehle:**
- Baumhaus - Man kann "Baumhaus" sagen.
- Baum; Haus - Man kann "Baum" oder "Haus" sagen (Strichpunkte trennen Befehle).
- Baum[Rinde; Krone] - Man kann "Baumrinde" oder "Baumkrone" sagen (Klammern gruppieren sie).
- Katzen[Minze; Haus;] - Man kann "Katzen", "Katzenminze" oder "Katzenhaus" sagen (Ein Strichpunkt am Ende macht den Teil optional).

**Liste der Befehle:**

**Energie:**
- Flugbereitschaft [herstellen;] - macht das Schiff flugbereit. Rotiert auch die Gegenmaßnahmen.
- [Haupt;] Energie an; volle Energie - Hauptenergie auf 100 %.
- [Haupt;] Energie aus - Hauptenergie auf 0 %. Achtung, schaltet z. Z. das Schiff aus.
- mehr Energie; Energie[zufuhr;] erhöhen - erhöht die Hauptenergie.
- weniger Energie; Energie[zufuhr;] [vermindern; verringern] - verringert die Hauptenergie.
- [Mehr Energie] [auf den; in den; zum;] Antrieb; mehr Antrieb; Antrieb verstärken - weist dem Antrieb mehr Energie zu.
- [Mehr Energie] [auf die; in die; zu den;] [Schilde; Schilden]; mehr Schilde; Schilde verstärken - weist den Schilden mehr Energie zu.
- [Mehr Energie] [auf die; in die; zu den;] Waffen; mehr Waffen; Waffen verstärken - weist den Waffen mehr Energie zu.
- [normale; standard] Energie[verteilung;]; Energie[verteilung;] [normal; reset; zurücksetzen] - setzt die Energieverteilung zurück.
- Schiff [an; anschalten; aus; ausschalten] - schaltet das Schiff an und aus. Kann auch den Antrieb schalten (siehe "QoL/Schiff plus Antrieb schalten").
- [Schiffs;] [Antrieb; Maschine; Maschinen; Motor; Motoren; Triebwerk; Triebwerke] [an; anschalten; aus; ausschalten] - schaltet den Antrieb an und aus.
- [Schiffs;] Waffen [an; anschalten; aus; ausschalten] - schaltet die Waffen an und aus.
- Schilde [an; anschalten; aus; ausschalten] - schaltet die Schilde an und aus.
- [Weniger Energie] [auf den; in den; zum;] Antrieb; weniger Antrieb; Antrieb [minus; verringern] - weist den Waffen und Schilden mehr Energie zu.
- [Weniger Energie] [auf die; in die; zu den;] [Schilde; Schilden]; weniger Schilde; Schilde [minus; verringern] - weist dem Antrieb und Waffen mehr Energie zu.
- [Weniger Energie] [auf die; in die; zu den;] Waffen; weniger Waffen; Waffen [minus; verringern] - weist dem Antrieb und Schilden mehr Energie zu.

**Flug:**
- abheben; los fliegen; Start; starten - lässt das Schiff ein paar Meter abheben und wechselt vom Lande- in den Flugmodus. Versucht, bei Bedarf das Schiff bzw. die Maschinen zu starten. Beachtet den Schiffstyp (siehe "Rumpf/Schiffstyp &ast;").
- aktivieren; Energie; spring; springe; springen; Springer; Sprung [ausführen; durchführen;] - führt den Quantum-Sprung durch. Fragt nach, falls der Quantum-Antrieb nicht aktiviert wurde (siehe "QoL/Auf geht's").
- [Alarm; Modus] [aufheben; beenden; reset; zurücksetzen] - setzt die Schild- und Energieverteilung zurück.
- [Bremse; bremsen; verzögern] [halten;] - aktiviert Spacebrake für eine kurze Zeit. Mit "halten" wird dauerhaft gebremst bis "abbrechen" (siehe "QoL/abbrechen").
- Fluchtmodus - verstärkt die hinteren Schilde maximal, weist dem Antrieb und Schilden alle Energie zu, rotiert die Gegenmaßnahmen.
- kreuzen; Tempomat - schaltet den Cruise-Modus an und aus.
- koppeln - koppelt den Antrieb ein und aus.
- Quantum; Sprung[bereit machen; vorbereiten]; Sprungbereitschaft [herstellen;]; spulen - schaltet den Quantum-Antrieb an und aus.
- Sprung [abbrechen; beenden] - bricht den Quantum-Sprung ab.

**HUD:**
- anvisieren; Focus; focussieren - wählt das Ziel unter dem Fadenkreuz aus.
- [Feind; feindliches Ziel; Gegner; Nahziel; Rot] aufschalten - nächstgelegenen Gegner auswählen.
- [Feind; Gegner; Rot] minus; Vorheriger [Feind; Gegner; Rot] - wechselt zum vorherigen Gegner.
- [Feind; Gegner; Rot] plus; Nächster [Feind; Gegner; Rot] - wechselt zum nächsten Gegner.
- [Freund; Gegner; Grün; Rot; Sonderziel; Ziel] [markieren; merken; pinnen] - Ziel pinnen.
- [Freund; Grün; Verbündeter] minus; Vorheriger [Freund; Grün; Verbündeter] - wechselt zum vorherigen freundlich gesinnten Ziel.
- [Freund; Grün; Verbündeter] plus; Nächster [Freund; Grün; Verbündeter] - wechselt zum nächsten freundlich gesinnten Ziel.
- [grüne; grünes; rote; rotes] [Ziel; Ziele] wechseln - wechselt das Ziel, freundlich oder feindlich, im Abstand von 3 Sekunden bis "abbrechen" (siehe "QoL/abbrechen"). Wird auch durch andere Befehle unterbrochen.
- nächstes [Subziel; Teilziel] [aufschalten;]; [Subziel; Teilziel] [plus; vor] - nächstes Untersystem des Ziels anvisieren.
- vorheriges [Subziel; Teilziel] [aufschalten;]; [Subziel; Teilziel] [minus; zurück] - vorheriges Untersystem des Ziels anvisieren.
- Sonderziel [minus; zurück]; [vorheriger; vorheriges] [Pin; Sonderziel] - wechselt zum vorherigen gepinnten Ziel.
- Sonderziel [plus; vor]; [nächster; nächstes] [Pin; Sonderziel] - wechselt zum nächsten gepinnten Ziel.
- [Teil; Sub]ziel [aufheben; löschen; normal; reset; standard; zurücksetzen]; [normal; normales] zielen - Auswahl der Untersysteme aufheben.
- [Visierung; Ziel] [aufheben; löschen; reset]; [kein; nicht] [Ziel; zielen] - Zielauswahl aufheben.

**Kamera:**
- Ansicht; Kamera - wechselt zwischen den Kamerapositionen.
- Rückspiegel [halten;]; Sicht [nach;] [achtern; hinten; rückwärts] [halten;]; was ist hinten [halten;] - schaltet für kurze Zeit auf die Rückkamera. Mit "halten" wird die Umschaltung dauerhaft bis "abbrechen" (siehe "QoL/abbrechen"). Taste LALT + J.

**Kampf:**
- Abwehr[maßname; maßnamen;] [abfeuern; los; raus]; [Gegenmaßnahme; Gegenmaßnahmen] [abfeuern; los; raus] - löst die aktive Gegenmaßnahme (Flare/Chaff) aus.
- Abwehr[maßname;maßnamen;] [ändern; tauschen; umschalten; wechseln]; andere Abwehr[maßname; maßnamen;]; andere [Gegenmaßnahme; Gegenmaßnahmen]; [Gegenmaßnahme; Gegenmaßnahmen] [ändern; tauschen; umschalten; wechseln] - wechselt zwischen den Gegenmaßnahmen (Flare/Chaff).
- [Rakete; Raketen; Torpedo; Torpedos] [abfeuern; los; starten] - feuert eine Rakete oder Torpedo auf das aufgeschaltete Ziel ab.
- [Rakete; Raketen; Torpedo; Torpedos] [aufheben; löschen; reset] - Raketen-Zielauswahl aufheben. Taste LALT + M.
- [Rakete; Raketen; Torpedo; Torpedos] [aufschalten;] - schaltet eine Rakete oder Torpedo auf das ausgewählte Ziel auf.
- [Waffen;]Aufhängung [ändern; beweglich; fest; fix; kardan; kardanisch; wechseln] - Gimbal-Modus ändern.

**Konfiguration:**
- Sprachstil [ändern; wechseln] - leitet die Änderung des Sprachstils ein. Das Profil kann seine Antworten "knapp" halten oder "ausführlich" bzw. "gesprächig" sein.

**Körper:**
- Beleuchtung; [Kopf; Taschen;] Lampe; Lampe; Lampen; Licht; Lichter; Scheinwerfer [an; anschalten; aus; ausschalten;] - schaltet die Anzugbeleuchtung an und aus (gleiche Funktion bei "Rumpf").

**MobiGlas:**
- Computer; Mobi - blendet MobiGlas ein und aus.
- Karte; Sternenkarte - blendet die Starmap ein und aus.
- Kontakte - blendet die Kontakte ein und aus.

**QoL:**
- abbrechen; Abbruch; aufhören; beenden; einstellen; hör [damit;] auf [damit;]; [tu; tut] das nicht - bricht alle laufenden Vorgänge ab.
- Auf geht's; Auf jeden [Fall;]; Bestätige; Hau rein; Ja [bitte; gerne; ist es; klar; Mama; schon; sicher; sicherlich; sind wir]; Ja wohl; jawoll; [Klar; Sicher] [doch;]; Mach [mal; schon]; Natürlich; Positiv; Sicherlich - dient zur Bestätigung von Nachfragen bei z. B. "abheben" oder "landen".
- Beende [Programm; Prozess; Spiel]; [Programm; Prozess; Spiel] beenden - beendet Star Citizen. Verlangt Bestätigung innerhalb von 30 Sekunden. Kann abgebrochen werden (siehe "QoL/abbrechen").
- [Chatkorrektur; Chat korrigieren] [ein; aus] - versucht, den Fehler zu korrigieren, dass der Chat beim Wechseln der Perspektive immer wieder eingeblendet wird. Funktioniert bei Kamera und Rückspiegel. Dazu: Chatkorrektur einschalten, Chat in Egoperspektive ausblenden, Kamera/Rückspiegel per VoiceAttack verwenden.
- geh schlafen; hör weg; mach [mal;] Pause - Beendet das Zuhören. Kann in der App per Hotkey oder Mausklick auf den Kopfhörer reaktiviert werden.
- [gibt's; gibt es] [etwas Neues; was Neues; Neuigkeiten]; Lies die Nachrichten [vor;]; Was [gibt's; gibt es] [für Neuigkeiten; Neues] - berichtet Nachrichten rund um Star Citizen.
- nochmal; wiederholen - wiederholt den letzten Befehl. Funktioniert nur, wo es sinnvoll ist.
- Schiff [plus Antrieb schalten; schaltet Antrieb] [ein; aus] - korrigiert den Fehler, dass nach dem Ausschalten des Schiffs weiterhin der Antrieb läuft und zu sehen ist.
- Welches Jahr [haben wir;] - nennt das Jahr in SC-Zeitrechnung.

**Rumpf:**
- [Antrieb; Antriebe; Triebwerk; Triebwerke] [drehen; fliegen; kippen; landen; senkrecht; tränen; waagerecht] - dreht die Triebwerke oder aktiviert VTOL (z. B. Cutlass, Constellation).
- Beleuchtung; [Kopf; Taschen;] Lampe; Lampe; Lampen; Licht; Lichter; Scheinwerfer [an; anschalten; aus; ausschalten;] - schaltet die Fahrzeugbeleuchtung an und aus (gleiche Funktion bei "Körper").
- Fahrwerk [ausfahren; einfahren; raus; rein]; Landemodus - fährt das Fahrwerk aus und ein.
- landebereit machen; Landebereitschaft [herstellen;]; Landung vorbereiten - stellt den Schub der Haupttriebwerke auf ca. 40 % Standard, dreht die Triebwerke, fährt das Fahrtwerk aus und öffnet die Kontakte (damit der Spieler die Landeanfrage stellen kann).
- landen - aktiviert die automatische Landung. Funktioniert nur, wenn man mit Landeerlaubnis über einem Pad schwebt. Fragt nach, falls das Fahrwerk nicht ausgefahren wurde (siehe "QoL/Auf geht's").
- [Melde; Nenne; Welcher; Welches] Schiff[styp;] - meldet den Schiffstyp (siehe "Rumpf/Schiffstyp &ast;").
- Notausstieg; Schleudersitz; Sofort raus hier - betätigt den Schleudersitz. Beachtet den Schiffstyp (siehe "Rumpf/Schiffstyp &ast;").
- [Schiff; Tür; Türen] [abschließen; entriegeln; entsperren; sperren; verriegeln] - sperrt die Türen, Fahrstühle und Rampen des Schiffs auf und zu.
- [Schiff; Tür; Türen] [auf; öffnen; schließen; zu] - öffnet die Türen, Fahrstühle und Rampen des Schiffs und schließt sie.
- [Schiffstyp; Schiffs Typ] &ast; - macht dem Profil ein Schiff bekannt (siehe "Schiffstypen").
- [Schiffstyp; Schiffs Typ] [reset; zurücksetzen] - hebt die Zuweisung des Schiffstyps auf.
- Selbstzerstörung[ssequenz;] [einleiten; initiieren; starten] - startet die Selbstzerstörung. Meldet die verbleibende Zeit bei 10 und 5 Sekunden, wenn der Schiffstyp bekannt ist (siehe "Rumpf/Schiffstyp &ast;").

**Schilde:**

Die Schilde können in Schritten von 25 % verändert werden. "Schilde nach vorn" verstärkt die Schilde dort um 25 % und belässt die übrigen bei 75 % (bei vier Schildflächen gesamt). Bei "Schilde halb nach vorn" beträgt die Änderung 50 %, bei "Schilde ganz nach vorn" 75 %.

- Schildverteilung; Verteilung der Schilde - meldet die Schildverteilung.
- [Schutz;][Schild; Schilde] [halb; ganz;] [nach;] hinten links - Schildmanagement.
- [Schutz;][Schild; Schilde] [halb; ganz;] [nach;] hinten rechts - Schildmanagement.
- [Schutz;][Schild; Schilde] [halb; ganz;] [nach;] [hinten; zurück] - Schildmanagement.
- [Schutz;][Schild; Schilde] [halb; ganz;] [nach;] links - Schildmanagement.
- [Schutz;][Schild; Schilde] [halb; ganz;] [nach;] rechts - Schildmanagement.
- [Schutz;][Schild; Schilde] [halb; ganz;] [nach;] [vor; vorn; vorne] - Schildmanagement.
- [Schutz;][Schild; Schilde] [halb; ganz;] [nach;] [vorn; vorne] links - Schildmanagement.
- [Schutz;][Schild; Schilde] [halb; ganz;] [nach;] [vorn; vorne] rechts - Schildmanagement.
- [Schutz;][Schild; Schilde] [normal; reset; standard; zurücksetzen] - setzt die Schildverteilung zurück.

**Sensoren:**
- [Aufklärungsmodus; Scanner; Scanmodus] [an; aus; ein] - wechselt zum Scanmodus und zurück.

**UI:**
- Chat - blendet den Chat ein und aus.
- [Einladung;] ablehnen; ausblenden; ignorieren - lehnt Einladungen ab.
- [Einladung;] [annehmen; akzeptieren] - nimmt Einladungen an.

**Schiffstypen &ast;&ast;BETA&ast;&ast;:**

Schiffstypen werden über Codes angegeben und nur für QoL-Aspekte verwendet, wie z. B. die Zeit bis zum Abheben oder das Wissen um den Schleudersitz.

Man kann "Schiffstyp A1" oder "Schiffstyp Delta 4" sagen.

- A1 - Anvil Pisces
- A7 - Anvil Hornet
- A11 - Anvil Carrack
- D4 - Drake Cutlass

**Bemerkungen:**
- Star Citizen liefert keine Information über seinen inneren Zustand. Deswegen kann VoiceAttack nicht wissen, ob der Quantum-Antrieb wirklich aktiviert wurde nachdem der Befehl gegeben wurde. Vielleicht war die Chateingabe aktiv und "b" ist dort gelandet. Deswegen ist dieses Profil auf keinen Fall narrensicher und leicht zu täuschen.
- Damit das Profil funktioniert, muss VoiceAttack mit Administrator-Rechten laufen. Damit kann es allerdings Windows-Prozesse steuern. Wem das nicht geheuer ist, kann es auf problematische Befehle untersuchen, wie z. B. "Spiel beenden".
