TP 3 - Page Produit Symfony
Ce qui a été fait
Transformation de la maquette HTML statique en page Symfony complète utilisant les techniques demandées :

1. Formulaire Symfony avec Form Type
Création de src/Form/CartItemType.php

Champs : quantity (IntegerType, min=1 max=10) + color (ChoiceType avec 3 options)

Configuration des attributs HTML identiques à la maquette

2. Contrôleur
src/Controller/ProductController.php

Route /product (name: app_product_show)

Création et gestion du formulaire avec handleRequest()

3. Template Twig
templates/product/show.html.twig

Reproduction exacte du HTML fourni

Remplacement du formulaire HTML par form_start(), form_row(), form_end()

Import Bootstrap 5.3 CDN

4. Configuration Twig
config/packages/twig.yaml

Activation du thème bootstrap_5_layout.html.twig pour style automatique Bootstrap 5

5. Intégration complète
Page responsive Bootstrap (image + specs + formulaire)

Données statiques du produit (AudioTech, $129.99, etc.)

Formulaire fonctionnel avec validation Symfony
