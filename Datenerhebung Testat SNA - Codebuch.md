# CODEBUCH #
erstellt von Hanna Bekele (hb070@hdm-stuttgart.de)

##Inhalt
- Edges.csv (Edgelist)
- Nodes.csv (Nodelist)
- Codebuch.md (Codierung der Datens‰tze)

## Ursprung und Datenerhebung
Ich habe den Datensatz aus Wikipedia, Abgeordnetenwatch, Bundestag.de und den jeweiligen Social-Media-Kan‰len der Politker:innen erhoben.

Das Netzwerk ist ein *gerichtetes two-mode Akteursnetzwerk*.



# EDGE - Attribute

**relationship**
definiert Verbindungen zwischen Politiker*innen und den Organisationen
codiert nach:

	1 = Ministerium
	2 = politische Funktion (in Ausschuessen, Gremien, Partei)
	3 = Mitgliedschaften in NGOs, Stiftungen, Gedenkst√§tten
	4 = Beteiligung an Unternehmen
	5 = Stipendien
	6 = Berufstaetigkeiten
	7 = Studien- und l√§ngere Aufenthalte im In- und Ausland
year	das Jahr der Verbindung


	
# NODE-Attribute

**id**
eindeutige Identifikation jedes einzelnen Knotens (vertex), der erfasst wird.  

**short_name**
Nachnahme des/der Politiker:in, Abk¸rzung des Organisationsnamens

**name**
Vollstaendiger Name des/der Politiker:in

**sex**
Geschlecht, numerische Codierung: 1 = male und 2 = female

**education**
hoechster Bildungsabschluss, numerische Codierung: 1 = Promotion, 2 = Diplom,  3 = Staatsexamen, 4 = Magister

**position**
jetzige Position, Codierung: 1 = Staatssekret√§r:in, 2 = Minister:in

**subject**
Fachrichtung bei Studium/Promotion, Codierung: 1= Politik, 2 = Recht, 3 = Wirtschaft, 4 = Soziales

**party**
Parteizugehoerigkeit

**religion**
Religion

**kids**
Anzahl der Kinder

**twitter**
Anzahl Twitter-Follower:innen

**facebook**
Anzahl Facebook-Follower:innen

**youtube**
Anzahl Youtube-Abonnent:innen

**type**
Art des Knotens, Codierung: 0 = Person, 1 = Organisation
	
##	
