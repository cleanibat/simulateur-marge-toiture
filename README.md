# Simulateur de marge — toiture

Outil statique (un seul `index.html`, aucune dépendance) pour calculer la marge d'un chantier de toiture moyen et comparer les produits entre eux.

## Ce qu'il calcule
Pensé pour les **solopreneurs** (artisan seul, sans salarié).

- **Chantier moyen** : surface × prix au m², heures passées, déplacement, location, autres frais.
- **Mon activité** : chantiers par an, frais fixes annuels (répartis par chantier), cotisations sociales en % du CA, option franchise de TVA (produits comptés TTC).
- **Produits** (démoussant, hydrofuge…) avec deux options A / B : conditionnement (L), prix du bidon, dilution, rendement (m²/L de mélange), nombre de couches.
  - prix au litre pur et au litre de mélange, litres et bidons nécessaires, coût au m², coût par chantier ;
  - verdict : quelle option est la moins chère, de combien par chantier et par an.
- **Résultat** : ce qui reste par chantier, gain par heure travaillée, part du prix qui reste, revenu annuel et mensuel, gain possible en changeant de produits.

Option « Compter les bidons entamés en entier » : par défaut le produit est compté au litre consommé (le reste sert au chantier suivant).

Les valeurs saisies sont gardées dans le navigateur ; export / import JSON pour les sauvegarder ou les partager.

## Utilisation
Ouvrir `index.html` dans un navigateur.
