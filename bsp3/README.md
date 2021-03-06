<h1>Infos zur Abgabe</h1>

Die App wurde in Google Chrome getestet. Die App wurde für Mobilgeräte (Tablet/Handies) erstellt. Sie wurde einerseits als "Desktop Version" getestet und andererseits mit Google Chrome IPhone 5 (Entwicklertools->Toogle Device).

Die App kann über login.html "gestartet" werden.

Wenn man sich registrieren möchte, muss der Account einer realen Person zuordnen werden können. Dies wurde mittels Handysignatur (Drittanbieter - deshalb auch die Screenshots), oder Wohnadressbestätigung mit einem Brief, der einen Aktivierungscode enthält, erreicht.

Beim Dashboard wurde so gut es möglich war, die Userinteraktionen anderer Benutzer simuliert.

Wenn beispielsweise auf dem Dashboard ein "Need assistance Request" anlegt wird, wird nach einigen Sekunden ein neues Dialogfenster geöffnet mit der Info, dass der Benutzer Max Musterman uns bei unserer Anfrage helfen möchte.

Anschließend ist auch die Möglichkeit den Hilferequest zu schließen, vorhanden. Das wird im Normalfall gemacht, wenn der Hilfegebende auch Hilfe geleistet hat. Danach kann gereviewed werden.

Umgekehrt sehen wir im Dashboard auch die Hilfeanfragen anderer Benutzer. Wir können durch Klicken auf die jeweilige Anfrage diese nochmal reviewen und akzeptieren.

Auch hier gilt, den Hilfsrequest zu schließen macht erst Sinn, wenn Hilfe abgeleistet wurde.

Wechselt man vom Dashboard auf eine andere Seite z.b. rate/remove, geht der aktuelle state vom Dashboard verloren. Das liegt daran, dass die Funktionalität vom Prototyp beschränkt ist.

<h1>Requirements Analysis</h1>

Im Rahmen dieses Beispiels ist es Ihre Aufgabe, ein Online-Tool zu designen, welches von Privatpersonen genutzt werden kann um persönliche Ressourcen mit anderen Menschen
innerhalb einer bestehenden Community zu teilen.

>Unsere App ist für hilfsbedürftige Menschen und Helfer. Die App soll Menschen, die Hilfe für alltägliche Aufgaben benötigen,
z.B. für eine Begleitung über gefährliche Straßenkreuzungen, Einkaufstasche nach Hause tragen, Glühbirne wechseln, oder auch Fahrtendienste übernehmen, anbieten. Sie ist auch für gehandicapte Personen sehr wertvoll. Sie führt auch einerseits hilfsbedürftige und andererseits hilfegebende Personen zusammen.

Der Service dient der direkten Vermittlung zwischen Privatpersonen
>Vermittlung zwischen Hilfesuchenden und Hilfegebenden aus der näheren Umgebung.

Der Service dient der Vermittlung von Personen, die bereits gemeinsam Teil eines geschlossenen Personenkreises bzw. einer 
bestehenden Community sind (z.B. Nachbarschaft, Freundeskreis, Arbeitskollegen und -kolleginnen in einem Unternehmen,
Mitglieder in einem Verein, Studierende an einer Universität, ...
>Freiwillige Dienstleistungsplattform für gehandicapte Personen.

Der Service soll nicht-kommerziell sein: Der Austausch von Ressourcen erfolgt ohne finanzielle Abgeltung zwischen den teilnehmenden Parteien.
>Eine Entschädigung erfolgt nicht über die App Plattform. Der Hilfeempfangende kann selbst entscheiden, ob es beispielsweise eine Entschädigung in Form von Naturalien, oder einem freien Trinkgeld gibt. Eine Entschädigung ist nicht vorgesehen, da ansonsten die Plattform für gewerbliche Zwecke missbraucht werden kann und auch steuerpflichtig ist und Gesetzesvorgaben eingehalten werden müssten.

Der Service soll nicht generisch sein: Überlegen Sie sich eine konkrete Zielgruppe und Anwendungsdomäne.. [..]
>Anwendungsdomäne = Hilfesuchende/Hilfegebende

<h2>Fragen, die abgedeckt werden sollten</h2>

 Ist es in dem von Ihnen gewählten Anwendungsszenario sinnvoll bzw. notwendig eine Registrierung vorrauszusetzen?
 >Ja um Missbrauch zu verhindern und um Protokoll zu führen. Weiters ist eine Registrierung notwendig, damit Kommunikation stattfinden kann und auch Hilfestellungen, wie beispielsweise einen Besuch an einer jeweiligen Adresse zu erledigen, gewährleistet werden kann.  
 
Macht es für die von Ihnen gewählte Anwendungsdomäne mehr Sinn, wenn das System von Angebot, Nachfrage oder beidem getrieben wird?
>Für das gewähltes Anwendungsszenario sind Angebot und Nachfrage relevant zugleich. Wenn es zu viel Hilfesuchende gibt, und die Anfragen nicht abgedeckt werden könnenn, wird das System für den Hilfesuchenden uninteressant. Gleiches gilt ebenfalls für die Hilfegebenden.

Soll die Kommunikation zwischen den Benutzern und Benutzerinnen des Systems innerhalb Ihrer Anwendung stattfinden oder soll diese ausgelagert werden (z.B. auf E-Mail, Telefon, ...)? Welche Vor- und Nachteile ergeben sich daraus?
>Es soll keine direkte Kommunikation auf der Plattform der User stattfinden. Das schützt die Benutzer/innen einerseits vor Missbrauch und andererseits soll der Hilfeaustausch dadurch nicht verkompliziert werden. Die Plattform unterstüzt E-Mail und Telefon Anfragen. Damit sollen Menschen, die durch ihre Einschränkung, Apps schlechter bedienen können, nicht ausgeschlossen werden. 

Wie kann man Benutzer und Benutzerinnen bei der Eingabe von Daten unterstützen? Wie lassen sich Fehleingaben vermeiden?
>Einfache und unkomplizierte Eingabemasken.

Welche Informationen sind für Benutzer und Benutzerinnen besonders wichtig und wie lässt sich deren Bedeutung im System repräsentieren?
>Nützliche Informationen sind zusätzliche Angaben durch die Art des Handicaps, um sich darauf einstellen zu können und auch sofort einzuschätzen, ob der Dienst annehmbar ist. Außerdem ist die Wahrscheinlichkeit bei gehandicapten Menschen größer, unerwartet ambulaten Dienstleistungen in Anspruch zu nehmen. Deshalb wird, z.B. auch die Blutgruppe bei der Registrierung aufgenommen. Bei einem Unfall kann das System (sofern der Helfende dieses durch die App meldet) die Blutgruppe des verunfallten in Erfahrung bringen.

Welche Such-/Filter-/Sortier-Funktionen sind notwendig bzw. nützlich?
>Ein Suchfilter macht z.B. Sinn in dem Hilfsgesuche in eine Aufwandskategorie eingeteilt werden. So können Helfer, die sich nicht so viel zutrauen einfachere Hilfsgesuche bearbeiten. Außerdem macht es Sinn die Hilfeanforderungen nach Nähe zu sortieren. Aus Zeitgründen wurden diese beim Prototyp nicht implementiert, da ein Fehlen die Funktionalität nicht einschränkt.

