# CODEBUCH #
erstellt von Hanna Bekele (hb070@hdm-stuttgart.de)

## Inhalt
- Edges.csv (Edgelist)
- Nodes.csv (Nodelist)
- Codebuch.md (Codierung der Datensätze)

## Ursprung und Datenerhebung
Ich habe den Datensatz aus Wikipedia, Abgeordnetenwatch, Bundestag.de und den jeweiligen Social-Media-Kanälen der Politker:innen erhoben.

Das Netzwerk ist ein *gerichtetes two-mode Akteursnetzwerk*.



# EDGE - Attribute

**relationship**
definiert Verbindungen zwischen Politiker*innen und den Organisationen
codiert nach:

	1 = Ministerium
	2 = politische Funktion (in Ausschuessen, Gremien, Partei)
	3 = Mitgliedschaften in NGOs, Stiftungen, GedenkstÃ¤tten
	4 = Beteiligung an Unternehmen
	5 = Stipendien
	6 = Berufstaetigkeiten
	7 = Studien- und laengere Aufenthalte im In- und Ausland
	*year*	das Jahr der Verbindung


	
# NODE-Attribute

**id** <br>
eindeutige Identifikation jedes einzelnen Knotens (vertex), der erfasst wird.  
<br>

**short_name**<br>
Nachnahme des/der Politiker:in, Abkürzung des Organisationsnamens
<br>

**name**<br>
Vollstaendiger Name des/der Politiker:in, der Organisation
<br>

**sex**<br>
Geschlecht <br>
1 = male <br>
2 = female <br>
<br>

**education** <br>
hoechster Bildungsabschluss <br>
1 = Promotion <br>
2 = Diplom <br>
3 = Staatsexamen <br>
4 = Magister <br>
<br>

**position** <br>
jetzige Position <br>
1 = Staatssekretear:in <br>
2 = Minister:in <br>
<br>

**subject** <br>
Fachrichtung bei Studium/Promotion <br>
1= Politik <br>
2 = Recht <br>
3 = Wirtschaft <br>
4 = Soziales <br>
<br>

**party** <br>
Parteizugehoerigkeit <br>
<br>

**religion** <br>
Religion <br>
<br>

**kids** <br>
Anzahl der Kinder <br>
<br>

**twitter**<br>
Anzahl Twitter-Follower:innen <br>
<br>

**facebook**<br>
Anzahl Facebook-Follower:innen <br>
<br>

**youtube**<br>
Anzahl Youtube-Abonnent:innen <br>
<br>

**instagram**<br>
Anzahl der Instagram-Follower:innen <br>
<br>

**type**<br>
Art des Knotens<br>
0 = Person<br>
1 = Organisation <br>
<br>
	
##
