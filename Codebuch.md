## CODEBUCH ##
"Im Codebuch definieren Sie, wie und nach welchen Kriterien erfasst werden."

## Inhalt

# edgelist
Grundregel: Die Edgelist darf pro Spalte immer nur einen Wert enthalten. Bis auf die ID idealerweise numerisch codiert (als Zahl). 

from,definiert den Sender in gerichteten Netzwerken. Entspricht ID in der Nodelist. 
to,definiert den Empfänger in ungerichteten Netzwerken. Entspricht ID in der Nodelist. 

**relationship**
<p>definiert Verbindungen zwischen Politiker*innen und dem Organisationen
<p>codiert nach:
<p>1 = Ministerium
<p>2 = politische Funktion (in Gremien, der Partei)"
<p>3 = Mitgliedschaften in NGOs, Stiftungen, Gedenkstätten"
<p>4 = Beteiligung an Unternehmen
<p>5 = Stipendien
<p>6 = Berufstätigkeiten
<p>7 = Studien- und längere Aufenthalte im In- und Ausland
<p>year = das Jahr der Verbindung


# nodelist
<p>Grundregel: die IDs der Nodelist müssen mit den IDs der Edgelist komplett übereinstimmen. Ausprägungen der Attribute in der Regel numerisch definieren.

**id**
<p>eindeutige Identifikation jedes einzelnen Knotens (vertex), der erfasst wird.

**name**
<p>Vollständiger Name  des*der Politiker*in 

**short_name**
<p>Nachnahme des*der Politiker*in 

**sex**
<p>Geschlecht, numerische Ausprägung/Codierung:
<p>1 = female und 2 = male"

**position**
<p>aktuelle Position
<p>Codierung: 1 = Minister*in, 2= Staatssekretär*in"

**party**
<p>Parteizugehörigkeit

**education**
<p>höchster Bildungsabschluss, numerische Ausprägung/Codierung:
<p>1 = Diplom, 2 = Promotion, 3 = Staatsexamen, 4 = Magister"

**religion**
<p>Religion
<p>Codierung: 1 = evangelisch, 2 = römisch-katholisch

**subject**
<p>Fachrichtung des Studiums/Promotion,
<p>Codierung: 1= Politik, 2 = Rechtswissenschaften, 3 = Soziales, 4 = Wirtschaft"

**kids**
<p>Anzahl der Kinder

**facebook**
A<p>nzahl der Facebook-Follower

**instagram**
<p>Anzahl der Instagram-Follower

**youtube**
<p>Anzahl der Youtube-Abonnenten

**twitter**
<p>Anzahl der Twitter-Follower

**type**
<p>Art des Knoten
<p>Codierung: 0 = Organisation, 1 = Person"

##
