# Simulateur de marge — toiture

Outil statique (un seul `index.html`, aucune dépendance) pour calculer la marge d'un chantier de toiture moyen et comparer les produits entre eux.

## Ce qu'il calcule
- **Chantier moyen** : surface × prix au m², main d'œuvre (ouvriers × heures × coût horaire chargé), déplacement, location, autres frais.
- **Produits** (démoussant, hydrofuge…) avec deux options A / B : conditionnement (L), prix du bidon, dilution, rendement (m²/L de mélange), nombre de couches.
  - prix au litre pur et au litre de mélange, litres et bidons nécessaires, coût au m², coût par chantier ;
  - verdict : quelle option est la moins chère, de combien par chantier et par an.
- **Résultat** : marge par chantier, taux de marge, marge au m², marge annuelle, gain possible en changeant de produits.

Option « Compter les bidons entamés en entier » : par défaut le produit est compté au litre consommé (le reste sert au chantier suivant).

Les valeurs saisies sont gardées dans le navigateur ; export / import JSON pour les sauvegarder ou les partager.

## Utilisation
Ouvrir `index.html` dans un navigateur.
