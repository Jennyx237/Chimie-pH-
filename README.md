# Chimie-pH-
  Le code fourni commence la déclaration de la classe Flacon ,définit une fonction utilitaire afficher_melange dans le main(), crée plusieurs flacons et affiche leurs mélanges
Le corps de la classe Flacon est à compléter.

## Spécifications de la classe Flacon
   Un flacon est caractérisé par :
    -un nom (string)
    -un volume (double, en ml)
    -un pH (double)

### Méthodes
    -Constructeur avec paramètres (pas de constructeur par défaut)

    -Méthode etiquette :ostream& etiquette(ostream& sortie) const;
        Elle  affiche : Nom : volume ml, pH x .
          Exemple :Acide chlorhydrique : 250 ml, pH 2
      
    -Surcharge de l’opérateur : doit utiliser etiquette

    -Opérateur + (mélange de flacons)
        Le mélange de deux flacons donne :
           1.nom : "nom1 + nom2"
           2.volume : somme des volumes
           3.pH :𝑝𝐻=−log10((𝑣𝑜l𝑢m𝑒1⋅10^−𝑝H1+𝑣𝑜𝑙𝑢𝑚𝑒2⋅10^−𝑝ℎ2)/(v𝑜𝑙𝑢𝑚𝑒1+𝑣𝑜𝑙𝑢me2))
