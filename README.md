# Feedbacks

Belle exécution du code avec un très bel effort de rédiger le code en anglais, c'est très bien.

Voici quelques points d'amélioration :

- Commentaires inutiles dans le html, les noms des classes sont suffisamments clairs et précises pour donner l'information sur l'emplacement des blocs.
- Idem pour le CSS
- Structure de ta page HTML est incorrecte
  - Utiliser le css à la place de la balise *<center></center>*
  - Idem pour *<strong></strong>, <em></em>*
  - Dans une *section*, il doit y avoir obligatoirement un *h2*
- S'assurer de vérifier la structure de son code HTML et CSS
- Créer des dossiers pour ranger le css, js, images, etc. dans des dossiers dédiés. Généralement on utilise un dossier racine */public/* ou */assets/* ou */src/* tels que :
.
├── css
│   ├── main.css
│   └── contact.css
├── img
│   ├── profile.jpg
│   └── logo.svg
├── js
├── index.html
└── README.md

## Résultats tests automatisés

- CV page accueil : **4/8**
 - Manque le lien vers LinkedIn
 - Manque les liens vers les écoles et entreprises
 - Manque la mise en page avec les flexbox
 - Manque un élément img
 - Manque l'attribut alt sur l'image
 - Manque le lien vers le formulaire de contact
- CV page contact : 0/4, page de contact manquante
- Validation des structures du code :
  - HTML accueil : 0/1, erreurs dans le HTML
  - HTML contact : 0/1 page manquante
  - CSS accueil : 1/1
  - CSS contact : 0/1 page manquante