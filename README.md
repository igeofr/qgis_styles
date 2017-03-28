# Fichiers de style pour QGIS

Pour télécharger un style depuis QGIS :

1. Installer et le plugin [QGIS Resource Sharing](http://www.akbargumbira.com/qgis_resources_sharing/).
2. Aller dans les propriétés du plugin pour ajouter le dépôt (https://github.com/igeofr/qgis_styles.git)
3. Installer le style qui vous intéresse

Pour charger un style dans QGIS :

1. Clic droit sur la couche.
2. Ouvrir les propriétés de la couche.
3. Se placer sur l'onglet : "Style".
4. Pour terminer : "Charger le style..." au format qml.  

**Les styles disponibles :**
- [Corine Land Cover](http://www.statistiques.developpement-durable.gouv.fr/donnees-ligne/li/1825.html)

  Pour la France métropolitaine :
    - [CLC Niveau 1](collections/CORINE_Land_Cover/style/clc_niveau1.qml)
    - [CLC Niveau 2](collections/CORINE_Land_Cover/style/clc_niveau2.qml)
    - [CLC Niveau 3](collections/CORINE_Land_Cover/style/clc_niveau3.qml)

  Pour les départements d'outre-mer (DOM) :
    - [CLC DOM Niveau 4](collections/CORINE_Land_Cover/style/clc_dom_niveau4.qml)
 
- [OCS GE](http://professionnels.ign.fr/ocsge)
 
  Couverture du sol :
    - [COUVERTURE Niveau 1](collections/OCS_GE/style/ocsge_cs_niveau1.qml)
    - [COUVERTURE Niveau 2](collections/OCS_GE/style/ocsge_cs_niveau2.qml)
    - [COUVERTURE Niveau 3](collections/OCS_GE/style/ocsge_cs_niveau3.qml)
    - [COUVERTURE Niveau 4](collections/OCS_GE/style/ocsge_cs_niveau4.qml)
    
  Usage du sol : 
    - [USAGE Niveau 1](collections/OCS_GE/style/ocsge_us_niveau1qml)
    - [USAGE Niveau 2](collections/OCS_GE/style/ocsge_us_niveau2qml)
    - [USAGE Niveau 3](collections/OCS_GE/style/ocsge_us_niveau3qml)

- [RPG](http://professionnels.ign.fr/rpg)
 
    - [Style RPG](collections/RPG/style/RPG.qml)
