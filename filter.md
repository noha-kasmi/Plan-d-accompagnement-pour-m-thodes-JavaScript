Fiche Méthode #filter 
Methode : filter 
1. MA DÉFINITION PERSONNELLE
filter() sert a selectionner des elements dans un tableau selon une condition.

2. PARAMÈTRES ACCEPTÉS
condition 

3. CE QU’ELLE RETOURNE
Retourne un nouveau tableau avec les elements que accepte la condition .

4. QUAND L’UTILISER ?
Quand je veux garder seulement certains elements.

5. CE QU’ELLE NE FAIT PAS ?
Ne modifie pas le tableau original.

6. pratique : 
const notes = [8, 12, 18];
const bonnes = notes.filter(n => n >= 10);

7. return : 
[12, 18]