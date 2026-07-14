AnzahlLocal = SUMX(RELATEDTABLE('Cluster of Responsible Product'), 'Cluster of Responsible Product'[LOCABenutzerdefiniert])



if [Column44] <> null and Value.Is([Column44], type text) and Text.Contains(Text.Upper([Column44]), "LOCAL") then 1 else 0
