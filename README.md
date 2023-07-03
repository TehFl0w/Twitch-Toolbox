
<div align=center style="text-align: center">
<h1 style="text-align: center"> Twitch-Toolbox </h1>
Ein Moderationsprogramm und Chatbot zur einfachen Verwaltung mehrerer Twitch-Kanäle.
</div>

<br>
<div align=center>

![GitHub all releases](https://img.shields.io/github/downloads/tehfl0w/twitch-toolbox/total) ![GitHub release (latest by date)](https://img.shields.io/github/downloads/tehfl0w/twitch-toolbox/latest/total)

<br>

⚠⚠⚠ _**Diese Software befindet sich in der Entwicklung, erwarte Abstürze, Fehler usw.**_ ⚠⚠⚠
</div>

## Über
Die Twitch-Toolbox ermöglichst Streamern und Moderatoren mehrere Kanäle gleichzeitig zu moderieren und verwalten.
Als Basis dient eine vom Institut für Sicherheit und Datenanalyse im Streaming gepflegte Datenbank mit bekannten Hatern, Trollen und sonstigen Nutzern, die sich "daneben" benehmen.

## Warum?
Warum nicht? Die Verwaltung des Kanals und Chats über die unnötig überladene Twitchwebsite ist teilweise sehr umständlich und vor allem verdammt langsam!
Und so wirklich eine alternative gibt es ja nicht. Jaja Chatty und co. aber das sind nur Chatprogramme und bieten nicht die Funktionen die ich und andere wünschen bzw. brauchen.

## Features
* Chatclient und Bot zur einfachen Verwaltung der User im Chatraum
* Abfrage sämtlicher Informationen über einen User auf Twitch
* Auslösen von Chat-Events `Announcement`,`Shoutout`,`Poll`&`Prediction`
* Umschalten von Chat-Modi z.B. Follower-Chat oder Emote-Chat
* Möglichkeit den ganzen Chatraum in einen "Lockdown" zu versetzen
* Channelabhängige Auto-Moderation von Chatnachrichten, Emotes und Usern
* Channelabhängige Reaktionen auf Event z.B. Auto-Shoutout bei einen Raid
* Follow-Remover (In einem gewählen Zeitraum oder alle potentiellen Bots, geht nur als Streamer)
* Bannen von einzelnen Nutzern und ganzen Listen über mehrere Kanäle hinweg
* Bannen der gesammten Community eines anderen Streamers
* Erkennen und Bannen von Seller-Bots "Buy Prime, Viewer blablabla"
* User können auf eine interne "Verdächtigenliste" mit der Möglichkeit zum Export/Teilen gesetzt werden
* Sortieren von Listen als .txt Datei

## Nutzungsrecht / Lizenz
* Ich gewähre ein unentgeltliches, zeitlich nicht befristetes und nicht ausschließliches Recht zur Nutzung (Lizenz) dieser SOFTWARE (nachstehend "Twitch-Toolbox“ genannt) Die Lieferung des Quellcodes gehört nicht zum Lieferumfang.
* Die Lizenz berechtigt zur Einzelnutzung der Twitch-Toolbox im Rahmen eines normalen Gebrauchs. Es dürfen keinerlei Änderungen und Übersetzungen oder weitere Vervielfältigungen der Twitch-Toolbox geschehen, auch nicht teilweise oder vorübergehend, gleich welcher Art und mit welchen Mitteln.
* Die Twitch-Toolbox darf weder vermieten noch verleihen werden.
* Auch darf die Twitch-Toolbox weder zurückentwickelt (Reverse Engineering), dekompiliert noch disassembliert werden.
* Missbrauch der Software zum trollen, verängstigen oder sonstwie schädigen von anderen Nutzern ist zu unterlassen.

## Haftungsausschluss
* Die Software wird "so wie sie ist" ohne irgendwelche Gewährleistungen bereitgestellt.
* Benutzung der Software geschieht auf eigene Gefahr, ich übernehme keine Verantwortung für eventuelle Schäden durch die Software oder falsche Handhabung derer.

## Voraussetzungen
Ehh 
* Windows 7/8/10/11
* ein Prozessor
* ~100MB Ram
* Eine Internetverbindung

## Installation
Die Toolbox ist "portable" und muss nicht klassisch installiert werden, schmeiß die .exe einfach in einen Ordner deiner Wahl, um alles andere kümmert sich das Programm von selbst.
Nach dem ersten Start wird eine `config.cfg` im Ordner angelegt, trage einfach dort deine ganzen Login-Daten ein und starte die Toolbox neu :)
* Username sollte klar sein
* Den oAuth-Token um dich anmelden zu können bekommst du [hier](https://twitchapps.com/tmi/)
* Du musst eine [App auf Twitch registrieren](https://dev.twitch.tv/docs/authentication/register-app/) um dann [hier](https://twitchtokengenerator.com) deinen Access-Token zu generieren. Wähle unten `Select All` um alle Scopes auszuwählen, ansonsten werden einige Funktionen nicht laufen.
* Unter Channel trägst du die Kanäle ein, denen du mein start automatisch beitreten möchtest, mit komma getrennt -> `channels=channel1,channel2,channel3`

Wenn alles korrekt eingetragen ist ist die Toolbox einsatzbereit.<br>
Wie du das Programm benutzt kannst du in der [Einführung](https://github.com/TehFl0w/Twitch-Toolbox/blob/main/docs/quickstart.md) nachlesen.

## Warum Closed-Source?
Auch wenn ich prinzipiell nichts dagegen habe den Quellcode offen zu legen weiß ich, dass viele Funktionen sehr einfach missbräuchlich umgeschrieben werden können und das möchte ich nicht. Ausserdem bin ich kein Fan davon wenn man sich mit fremden Lorbeeren schmückt... Ich will hiermit Streamern und deren Moderatoren den Kampf gegen die Windmühlen des Hasses erleichtern und nicht umgekehrt. Wenn du Fragen hast schau einfach bei mir im Stream vorbei.

## Danksagung
* [Institut für Sicherheit und Datenanalyse im Streaming](https://isds.tech/)
* TwitchMods DACH

## Sonstiges
Bei weiteren Fragen, Anregungen oder was weiß ich was schau am besten einfach bei mir im Stream vorbei: [*Klick*](https://twitch.tv/tehfl0w)
<br>Ansonsten viel Spaß und Erfolg mit dem Tool!
