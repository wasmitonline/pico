---
Robots: noindex, nofollow
---

# Einrichtung von iGP-E-Mail-Adressen

Auf dieser Seite finden Sie alle relevanten Informationen, um Ihre E-Mail-Adressen nach dem Muster vorname.nachname@igpweb.org auf Ihren Geräten einzurichten. Die Anleitung wird sukzessive erweitert. 



[toc]



Wenn Sie Fragen oder Wünsche haben, schreiben Sie mir gerne unter [tg@wasmitinter.net](mailto:tg@wasmitinter.net). 


## Outlook, Apple Mail, Thunderbird etc.

Richten Sie einen zusätzlichen (Mail- bzw. IMAP-) Account über Ihren Mailclient ein, also ein zusätzliches Konto in Outlook, Apple Mail oder Thunderbird. Dies funktioniert sowohl am PC als auch am Smartphone. Hier müssen Sie ein zusätzliches Mailpostfach in Ihrer jeweiligen Mail-App einrichten. 

Bei der Einrichtung müssen Sie die folgenden Zugangsdaten eingeben (ersetzen Sie dabei [vorname.nachname] durch Ihren eigenen Vor- und Nachnamen. Das Passwort bekommen Sie per E-Mail.

In der Regel „verstehen“ die Mailprogramme selbst, welche Einstellungen Sie verwenden sollten. Sollte das nicht der Fall sein, geben Sie die folgenden Zugangsdaten ein.


### Zugangsdaten IMAP (Mails empfangen)

| Server                  | `europa.uberspace.de`                        |
| ----------------------- | -------------------------------------------- |
| Port                    | `993`                                        |
| SSL/TLS-Verschlüsselung | Aktivieren (nicht STARTTLS)                  |
| Benutzername            | vorname.nachname@igpweb.org                  |
| Passwort                | Ihr Passwort (bekommen Sie separat via Mail) |

### Zugangsdaten SMTP (Mails versenden)

Beim Versenden von Mails haben Sie grundsätzlich die Auswahl zwischen zwei Verschlüsselungsstufen: Das ältere [STARTTLS](https://de.wikipedia.org/wiki/STARTTLS) (manche Mailprogramme mögen das lieber) und die eigentlich sicherere SSL/TLS-Variante. Je nachdem sind bei der Einrichtung unterschiedliche Ports anzugeben. Wenn möglich, empfehlen wir immer, die SSL-TLS-Verschlüsselung und Port 465 zu wählen (dritte Spalte).

| Server                  | `europa.uberspace.de`                        | `europa.uberspace.de`                        |
| ----------------------- | -------------------------------------------- | -------------------------------------------- |
| Port                    | `587`                                        | `465`                                        |
| SSL/TLS-Verschlüsselung | STARTTLS                                     | TLS                                          |
| Username                | vorname.nachname@igpweb.org                  | vorname.nachname@igpweb.org                  |
| Password                | Ihr Passwort (bekommen Sie separat via Mail) | Ihr Passwort (bekommen Sie separat via Mail) |

## Webmail

Sie können Mails über einen Webbrowser abrufen, indem Sie folgende Adresse aufrufen und dort Ihre Zugangsdaten eingeben:

[https://webmail.uberspace.de/](https://webmail.uberspace.de/)

## Einrichtung am Smartphone oder iPad

Beim iPhone geht das in der Regel über Einstellung > Mail > Accounts und dann mit denselben Daten wie am PC. 

Bei Android-Handys finden Sie die Einstellungen für die Mail-Apps i.d.R. direkt in den Einstellungen der jeweiligen App und nicht zentral.

### SMTP-Server auf Apple-Geräten (iPad) einstellen

Es kann bei Apple-Geräten vorkommen, dass die Daten für den Versandserver (SMTP) nicht direkt übernommen werden. In diesem Fall müssen Sie die SMTP-Daten extra konfigurieren. 

Gehen Sie dazu zunächst in die Einstellungen und dort unter > Mail und dann wählen Sie „Accounts“ aus: 

![Einstellungen: Accounts auswählen](/assets/ipad-mail_1.png)

Auf der nächsten Seite wählen Sie den Account aus, den Sie bearbeiten möchten. 

Hier ist es dann wichtig, unter den Accounteinstellungen auch „SMTP“ unter „Server für ausgehende Mails“ zu bearbeiten. Die Daten, die Sie hier eingeben müssen, sind dieselben wie oben.
