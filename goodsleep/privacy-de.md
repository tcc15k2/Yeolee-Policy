# Datenschutzerklärung für GoodSleep

Gültig ab: 2026-10-16
Verantwortlicher: Yeolee (Einzelentwickler) · Kontakt: tcc15k2@gmail.com
Englische Fassung: https://tcc15k2.github.io/Yeolee-Policy/goodsleep/privacy-en.html · Koreanische Fassung: https://tcc15k2.github.io/Yeolee-Policy/goodsleep/privacy.html

## 1. Was GoodSleep tut
GoodSleep ist eine kostenlose App, die Ihren Schlaf aufzeichnet und Klänge abspielt, die sich an akustischen Eigenschaften aus der Schlafforschung orientieren. GoodSleep ist kein Medizinprodukt und ersetzt weder Diagnose noch Behandlung.

## 2. Daten, die nur auf Ihrem Smartphone gespeichert werden
Alle Funktionen sind ohne Anmeldung nutzbar. Die folgenden Daten werden standardmäßig **ausschließlich auf Ihrem Smartphone** gespeichert.

| Daten | Inhalt | Zweck |
|---|---|---|
| Schlafaufzeichnungen | Schlafens- und Aufwachzeit, geschätzte Schlafphasen in 30-Sekunden-Schritten, Qualität und Kennzahlen, Morgenstimmung und Notizen | Tagebuch, Statistiken, Wochenbericht |
| Geräuschereignisse | Zeitpunkt und Dauer von erkanntem Schnarchen, Husten und Sprechen im Schlaf | Geräuschereignisse im Tagebuch |
| Geräuschclips | **Kurze Ausschnitte (höchstens etwa 10 Sekunden, geringe Qualität)** rund um erkannte Ereignisse. Durchgehende Aufnahmen werden nie gespeichert | Erneutes Anhören im Tagebuch |
| Mixe, Schlafziele, Einstellungen | Gespeicherte Klangkombinationen, Ziele pro Wochentag, App-Einstellungen | Funktion der App |
| Diagnoseprotokoll | Zeitpunkte und Namen von Ereignissen des Klangdienstes, der Aufzeichnung und der Wiedergabe (z. B. „Wiedergabefehler“, „Ausgabegerät getrennt“) sowie der Grund, warum der App-Prozess zuletzt beendet wurde. Es enthält keine Audiodaten, keine Schlafdaten und keine personenbezogenen Kennungen | Herausfinden, warum der Klang gestoppt hat. Es bleibt auf Ihrem Smartphone und verlässt es nur, wenn Sie selbst Profil > „Diagnoseprotokoll senden“ wählen |

- Mikrofonaudio wird **nur auf Ihrem Smartphone analysiert** und nie an einen Server gesendet. Dafür wird ein Klassifizierungsmodell verwendet, das auf dem Gerät läuft (YAMNet).
- Geräuschclips werden je nach Einstellung „Geräuschclips aufbewahren“ im Profil (nicht speichern / 1 / 20 / 100 Nächte) automatisch gelöscht. Mit „Daten löschen“ können Sie sie sofort entfernen.
- Wenn Sie die Aufzeichnung per Smartphone-Bewegung (Beschleunigungssensor) wählen, wird das Mikrofon nicht verwendet.

## 3. Daten, die Ihr Smartphone nur bei einer optionalen Funktion verlassen
### 3-1. Konto und Backup (Google-Anmeldung, optional)
Wenn Sie das Backup aktivieren, melden Sie sich mit Ihrem Google-Konto an (Kennung, E-Mail-Adresse, Name). Folgende Daten werden in Ihrem persönlichen Bereich von **Google Firebase (Firestore)** gespeichert:
- Schlafaufzeichnungen (einschließlich des Diagramms in 30-Sekunden-Schritten), Notizen und Tags, Mixe, Schlafziele, Einstellungen
- **Nicht enthalten**: Geräuschclips, Werbe-ID, Geräteinformationen

Mit „Konto und Backups löschen“ in der App löschen Sie die Serverdaten und Ihr Konto. Die Aufzeichnungen auf Ihrem Smartphone bleiben erhalten.

### 3-2. Health Connect (optional)
Wenn Sie Health Connect verbinden, werden Schlafzeiten und Schlafphasen in Health Connect **geschrieben**. Eine Leseberechtigung wird nicht angefordert. Sie können die Berechtigung jederzeit in den Health-Connect-Einstellungen widerrufen.

## 4. Dienste, die immer verwendet werden

| Dienst | Übermittelte Daten | Zweck | Abschalten |
|---|---|---|---|
| Firebase Analytics | Ereignisse wie die Nutzungshäufigkeit von Funktionen (keine Schlafaufzeichnungen, keine Klänge), Geräte- und App-Version. **Standardmäßig aus; wird nur gesendet, wenn Sie Profil > „Nutzungsstatistik senden“ selbst einschalten** | Verbesserung der App | Profil > „Nutzungsstatistik senden“ |
| Firebase Crashlytics | Absturzberichte (Gerätemodell, Betriebssystem, Stacktrace) | Stabilität | — |
| Firebase Remote Config | (nur Empfang) Werte von Funktionsschaltern | Funktionen bei Problemen aus der Ferne abschalten | — |
| Google AdMob | Werbe-ID und App-Set-ID, IP-Adresse (kann zur Schätzung des ungefähren Standorts verwendet werden), Interaktionen wie App-Starts und Tippen sowie Diagnosedaten zur Leistung von App und Werbe-SDK | Anzeige von Bannerwerbung, Messung und Analyse der Werbeleistung, Missbrauchsverhinderung | Profil > „Datenschutz und Werbeeinwilligung“ |

- Werbung erscheint nur auf den Bildschirmen Klänge, Tagebuch, Statistik, Profil und Schlaf-Startseite (vor Beginn der Aufzeichnung). **Während Sie schlafen, beim Wecken und beim Morgen-Check-in erscheint keine Werbung.** Zwischen 0:00 und 6:00 Uhr werden Banner ausgeblendet.
- Im Europäischen Wirtschaftsraum, im Vereinigten Königreich und in der Schweiz wird Ihre Einwilligung zur Werbung über die User Messaging Platform (UMP) von Google eingeholt. Sie können das Formular im Profil erneut öffnen und Ihre Entscheidung ändern.
- Die von AdMob übermittelten Daten werden an Google weitergegeben und nach der Datenschutzerklärung von Google verarbeitet (https://policies.google.com/privacy). Alle Übertragungen sind mit TLS verschlüsselt. Die Werbe-ID können Sie in den Android-Einstellungen zurücksetzen oder löschen.

## 5. Rechtsgrundlagen (DSGVO)
- **Backup und Konto**: Erfüllung des Nutzungsverhältnisses auf Ihren Wunsch (Art. 6 Abs. 1 lit. b DSGVO).
- **Health Connect**: Ihre Einwilligung (Art. 6 Abs. 1 lit. a DSGVO), die Sie in Health Connect jederzeit widerrufen können.
- **Werbung (AdMob)**: Ihre Einwilligung über das UMP-Formular (Art. 6 Abs. 1 lit. a DSGVO); ohne Einwilligung werden nur nicht personalisierte Anzeigen ausgeliefert, soweit Google dies zulässt.
- **Nutzungsstatistik (Firebase Analytics)**: Ihre Einwilligung (Art. 6 Abs. 1 lit. a DSGVO, § 25 TDDDG), die Sie durch Einschalten im Profil erteilen und jederzeit dort widerrufen können.
- **Absturzberichte und Remote Config**: berechtigtes Interesse an einem stabilen und sicheren Betrieb (Art. 6 Abs. 1 lit. f DSGVO).
- Daten, die nur auf Ihrem Smartphone bleiben (Abschnitt 2), werden nicht an uns übermittelt.

## 6. Übermittlung in Drittländer
Firebase und AdMob werden von Google bereitgestellt. Dabei können Daten in die USA übermittelt werden. Google LLC ist nach dem EU-US Data Privacy Framework zertifiziert; ergänzend gelten die Standardvertragsklauseln der EU-Kommission.

## 7. Speicherdauer und Löschung
- Daten auf Ihrem Smartphone: werden gelöscht, wenn Sie die App deinstallieren oder Profil > „Daten löschen“ wählen.
- Backup-Daten: löschen Sie mit „Konto und Backups löschen“ oder über die Löschanfrage im Web (siehe unten).
- Wenn Sie in der App nicht löschen können, schreiben Sie an tcc15k2@gmail.com. Wir bearbeiten die Anfrage innerhalb von 7 Tagen.

## 8. Ihre Rechte
Sie haben das Recht auf Auskunft, Berichtigung, Löschung, Einschränkung der Verarbeitung, Datenübertragbarkeit (z. B. über den CSV-Export in der App) und Widerspruch gegen Verarbeitungen auf Grundlage berechtigter Interessen. Eine erteilte Einwilligung können Sie jederzeit mit Wirkung für die Zukunft widerrufen. Sie haben außerdem das Recht, sich bei einer Datenschutz-Aufsichtsbehörde zu beschweren, insbesondere in dem Mitgliedstaat Ihres Wohnsitzes. Für Anfragen schreiben Sie an tcc15k2@gmail.com.

## 9. Kinder
GoodSleep richtet sich nicht an Kinder unter 16 Jahren (bzw. dem in Ihrem Land geltenden Mindestalter), und wir erheben wissentlich keine Daten von Kindern.

## 10. Änderungen
Wenn sich diese Erklärung ändert, weisen wir in der App und in diesem Dokument mit dem Gültigkeitsdatum darauf hin.

## 11. Kontakt
Yeolee · tcc15k2@gmail.com
Löschanfrage im Web: https://tcc15k2.github.io/Yeolee-Policy/goodsleep/account-deletion/de/

*Bei Abweichungen zwischen den Sprachfassungen ist die koreanische Fassung maßgeblich.*
