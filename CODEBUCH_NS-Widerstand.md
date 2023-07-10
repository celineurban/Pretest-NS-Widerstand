CODEBUCH												
Wert	Kommentar											
edgelist	Grundregel: Die Edgelist darf pro Spalte immer nur einen Wert enthalten. Bis auf die ID idealerweise numerisch codiert (als Zahl).											
from	definiert den Sender in gerichteten Netzwerken. Entspricht ID in der Nodelist. Keine Sonderzeichen, nur ein Wort											
to	definiert den Empfänger in ungerichteten Netzwerken. Entspricht ID in der Nodelist. Keine Sonderzeichen, etc.	
relation  Art der Beziehung (1=familiär, 2=freundschaftlich, 3=flüchtige Bekanntschaft)
time  Dauer der Beziehung										
nodelist	Grundregel: die IDs der Nodelist müssen mit den IDs der Edgelist komplett übereinstimmen. Ausprägungen der Attribute in der Regel numerisch definieren.											
id	eindeutige Identifikation jedes einzelnen Knotens (vertex), der erfasst wird.											
name	Namen der Personen											
age	Alter der Personen zum Todeszeitpunkt											
social group	Angehörigkeit zu gesellschaftlicher Gruppe (1 = KZ-Häftling, 2 = Ex-Soldat, 3 = Halbjude, 4 = Arbeiter, 5 = Kommunist)																					
NA	definiert fehlende Werte, bei der Datenerhebung das Feld einfach leer lassen, R rechnet NAs (missing values) automatisch raus..											