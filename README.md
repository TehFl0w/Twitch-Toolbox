
<div align=center style="text-align: center">
<h1 style="text-align: center"> Twitch-Toolbox </h1>
Ein Moderationsprogramm und Chatbot zur einfachen Verwaltung mehrerer Twitch-Kanäle.
</div>

<br>
<div align=center>
  
⚠⚠⚠ _**Diese Software befindet sich in der Entwicklung, erwarte Abstürze, Fehler usw.**_ ⚠⚠⚠
  <br>
  <br>
  
<img src="https://img.shields.io/badge/Windows%20x64-grey?logo=windows&labelColor=%23323232&color=%23424242" style="max-height: 300px;">  
<img src="https://img.shields.io/badge/.NET%206.0-grey?logo=.net&labelColor=%23323232&color=%23424242" style="max-height: 300px;">  
<img src="https://img.shields.io/badge/cSharp-grey?logo=sharp&labelColor=%23323232&color=%23424242" style="max-height: 300px;"> 
<br> 
<img src="https://img.shields.io/github/downloads/TehFl0w/Twitch-Toolbox/total?labelColor=%23323232&color=%2300CC00" style="max-height: 300px;"> 
<img src="https://img.shields.io/github/downloads/TehFl0w/Twitch-Toolbox/latest/total?labelColor=%23323232&color=%2300CC00" style="max-height: 300px;"> 
<br>
<br>  
<a href="https://www.twitch.tv/tehfl0w"><img src="https://img.shields.io/twitch/status/tehfl0w?logo=twitch&label=Twitch-Stream%3A&labelColor=%23323232&color=%23424242" style="max-height: 300px;"></a>
<br>
<br>
  
-> [VirusTotal aktuelles Release](https://www.virustotal.com/gui/file/954b530b293ea475943087282598343c80aeae1a6ad991af33a15750e392b492) <-
</div>

## Über
Die Twitch-Toolbox ermöglicht Streamern und Moderatoren mehrere Kanäle gleichzeitig zu moderieren und verwalten.
Als Basis dient eine vom Institut für Sicherheit und Datenanalyse im Streaming gepflegte Datenbank mit bekannten Hatern, Trollen und sonstigen Nutzern, die sich "daneben" benehmen.
<br><br>
Das ist ein reines Hobby-Projekt, ich arbeite weder mit noch für Twitch.

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
* Die Twitch-Toolbox darf weder vermietet noch verliehen werden.
* Auch darf die Twitch-Toolbox weder zurückentwickelt (Reverse Engineering), dekompiliert noch disassembled werden.
* Missbrauch der Software in jedweder Form aber insbesondere zum trollen, verängstigen oder sonstwie schädigen von anderen Nutzern oder der Plattform ist zu unterlassen und strafbar!
* Durch die Nutzung der Twitch-Toolbox stimmt der Endnutzer automatisch diesen Bedingungen zu, es benötigt kein seperates akzeptieren eines Lizenzvertrages.

## Haftungsausschluss
* Die Software wird "so wie sie ist" ohne irgendwelche Gewährleistungen bereitgestellt.
* Benutzung der Software geschieht auf eigene Gefahr, ich übernehme keine Verantwortung für eventuelle Schäden durch die Software oder falscher Handhabung dieser.

## Voraussetzungen
Ehh 
* Windows 7/8/10/11
* ein Prozessor
* ca. 80 MB Ram
* eine Internetverbindung

## Installation
Die Toolbox ist "portable" und muss nicht klassisch installiert werden, schmeiß die .exe einfach in einen Ordner deiner Wahl, um alles andere kümmert sich das Programm von selbst.
Beim ersten Start wirst du nach deinen Login-Daten gefragt:
* Username sollte klar sein
* Du musst eine [App auf Twitch registrieren](https://dev.twitch.tv/docs/authentication/register-app/) und die `Redirect URL` auf `http://localhost:300/` stellen: [BEISPIEL](https://github.com/TehFl0w/Twitch-Toolbox/blob/main/images/twitchapp.png)
* Mit der `Client-ID` und dem `Secret` deiner App kannst du dich dann über die Toolbox einloggen.
* Unter Channel trägst du die Kanäle ein, denen du beim Start automatisch beitreten möchtest, einer pro Zeile. 

Wenn alles korrekt eingetragen ist kannst du dich authorisieren und loslegen!<br><br>
Wie du das Programm benutzt kannst du in der [Einführung](https://github.com/TehFl0w/Twitch-Toolbox/blob/main/docs/quickstart.md) nachlesen.

## Warum Closed-Source?
Auch wenn ich prinzipiell nichts dagegen habe den Quellcode offen zu legen weiß ich, dass viele Funktionen sehr einfach missbräuchlich umgeschrieben werden können und das möchte ich nicht. Ausserdem bin ich kein Fan davon wenn man sich mit fremden Lorbeeren schmückt... Ich will hiermit Streamern und deren Moderatoren den Kampf gegen die Windmühlen des Hasses erleichtern und nicht umgekehrt. Wenn du Fragen hast schau einfach bei mir im Stream vorbei.

## Danksagung
* [Institut für Sicherheit und Datenanalyse im Streaming](https://isds.tech/)
* TwitchMods DACH
* Alle Closed-Beta Tester! :)

## Sonstiges
Bei weiteren Fragen, Anregungen oder was weiß ich was schau am besten einfach bei mir im Stream vorbei: [*Klick*](https://twitch.tv/tehfl0w)
<br>Ansonsten viel Spaß und Erfolg mit dem Tool!
