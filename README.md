# Passwort-Datenbank
Erfassen und Verwalten von Passwörtern

Diese Android-App entspricht CRUD-SQLite:
>Create = Erfassen von Passwörtern in 4 Feldern
>Read = Anzeige aller erfassten Datensätze
>Update = Ändern von Passwort-Datensätzen
>Delete = Löschen von Datensätzen

Erfassen der Passwörtern erfolgt mit 4 Feldern:
Name = Eine aussagekräftige Bezeichnung -> Microsoft Account
Adresse = Internetadresse für den Browser -> https://www.live.com
Login = Der verwendete Benutzername -> max.muster@outlook.com
Passwort = Das passende Passwort dazu -> Pa$$w0rT25

Die Liste der Passwörter wird in einer ListView angezeigt.
Die Liste lässt sich über das ActionMenu nach allen 4 Feldern sortiert ausgeben.
Langes antippen aktiviert den Eintrag und ändert die ActionBar. Die Symbole für Edit und Delete werden angezeigt.

Für das Erfassen oder Bearbeiten von Einträgen wird jeweils ein AlertDialog erzeugt.
Leere Eingabefelder erzeugen einen Abbruch des gewählten Vorganges.
Eine Toast-Meldung gibt an, ob das "Passwort gespeichert" oder das "Passwort nicht gespeichert" wurde.

