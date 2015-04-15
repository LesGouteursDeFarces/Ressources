Aspiration BDD RateBeer

Annalyse des URL de Rate Beer
Forme trouvée : `http://ratebeer.com/beer/_textquelconque_/_idbiere_/`
  
Programme C++ : 
  - Compteur de 0 à n (ou n assez grand +50.000)  
  - Faisant appel au programme Java  
  
Programme Java :  
  - Prend une adresse HTTP ou fichier en paramètre de l'application  
  - Télécharge la page Web  
  - Parsage (oui ce mot existe !) la page web à la recherche des élements  
    - Nom
    - Style (transformer sous forme d'id )
    - ABV
    - Origine
    - Note général
    - Note de style
    - Brasserie
  - Production sur la sortie standard d'une requète SQL d'insertion  
  
Regarde le code Java si tu veux mettre des morceau de code. Il se trouve ici dans Ressource.  

Nombre d'enregistrement recupéré : 28.257 après nettoyage des entrées inutilisable  
Temps pour faire cette récup ~24h
