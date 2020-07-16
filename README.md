# BA-Recommending
Der praktische Teil der BA wird hier entfaltet werden und Stück für Stück aufgebaut.
Die Einzelteile sollen so laufen, dass sie mit möglichst wenig Änderungen für einen Wechsel des Datensatzes auskommen können.
Dementsprechend sind die Input- und Outputformate und Namen der Spalten des Dataframe (Cust_Id, Rating und Movie_Id) sehr wichtig.

Die momentanen Files:
- HilgeMovielens100k: Ein jupyter notebook File auf dem erfolgreich Filmvorschläge gemacht werden können und mehr
- movies100k: Teil des Movielens 100k Datensatzes, in dem u.A. den Movie_Ids die tatsächlichen Filme zugeordnet werden
- ratings100k: Teil des Movielens 100k Datensatzes, in dem 100000 Ratings in 0,5er Inkrementen von 0,5 bis 5,0 von Usern bezüglich Filmen angesammelt sind

Bisher wird noch nicht eingegangen auf:
-Filmmetadaten, da die Matrix Factorization Methode größtenteils ohne diese Auskommt - und erspart Speicher und Rechenleistung ohne
