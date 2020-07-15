# Testat_Codebuch
Kohlekommission Netzwerk  

Datensatz der Mitglieder der Kohlekommission 

Codebuch Stand 2020-07-15
erstellt von Brigitte Buck (bb095@hdm-stuttgart.de)

Inhalt

Edges.csv (Edgelist)
Nodes.csv (Nodelist)
Codebuch.rm (Codierung der Datensätze)
Ursprung und Datenerhebung

Ich habe den Datensatz der Mitglieder der Kohlekommission aus dem Klimareporter Artikel, dem Munziger Archiv und der BMWI Pressemeldung. 

Das Netzwerk ist ein gerichtetes two-mode Netzwerk (Akteur-Organisationen). 

EDGE-Attribute

from 
(id Mitglied der Kommision)

to
(alle Mitgliedschaften der Person, soweit recherchierbar, dazu gehört z.B. politische Partei, Unternehmen, Verbände, Vereine und weitere Organisationen)

NODE-Attribute

id
Identische ID wie aus der edgelist zur Identifikation der Knoten. 

type 
Betrifft Person oder Organisation im Netzwerk:
0 = person 
1 = organization

sex
Geschlecht der Person:
1 = weiblich
2 = männlich
3 = divers

age
Alter der Person: 
1 = bis 20 Jahre
2 = 21 bis 30
3 = 31 bis 40
4 = 41 bis 50 
5 = 51 bis 60 
6 = 61 bis 70
7 = 71 bis 80 

party 
Persönlicher Mitgliedschaft in politischer Partei: 
1 = SDP
2 = CSU 
3 = CDU 
4 = GRÜNE 
5 = FDP 
6 = DIE LINKE  
7 = 

representation
Funktion der Person innerhalb der Kommission:
1 = Politik
2 = Wirtschaft
3 = Gewerkschaft
4 = Umwelt
5 = Regionen
6 = Wissenschaft

position
Position der Person: 
1 = Vorsitz
2 = Mitglied
3 = kein Stimmrecht

state 
Bundesland, dem die Person angehört: 
1 = Baden-Württemberg 
2 = Bayern
3 = Berlin
4 = Brandenburg 
5 = Bremen
6 = Hamburg 
7 = Hessen
8 = Mecklenburg-Vorpommern
9 = Niedersachsen
10 = Nordrhein-Westfalen
11 = Rheinland-Pfalz
12 = Saarland
13 = Sachsen
14 = Sachsen-Anhalt
15 = Schleswig-Holstein
16 = Thüringen

married 
1 = ja 
2 = nein 
