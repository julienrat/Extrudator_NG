# EXTRUDATOR_NG

EXTRUDATOR_NG est un outil web qui permet de convertir des images en modèles 3D de manière simple et intuitive. Il utilise une approche de vectorisation pour transformer vos images en fichiers STL imprimables en 3D.

## Démo en ligne

Essayez EXTRUDATOR_NG directement dans votre navigateur : [https://julienrat.github.io/Extrudator_NG/](https://julienrat.github.io/Extrudator_NG/)

## Fonctionnalités

- Importation d'images (PNG, JPG, etc.)
- Vectorisation automatique avec contrôle du nombre de couleurs
- Prévisualisation en temps réel du SVG généré
- Modélisation 3D instantanée avec contrôle des hauteurs par couleur
- Export en plusieurs formats :
  - SVG (pour l'édition vectorielle)
  - STL (pour l'impression 3D)
  - DXF (pour la CAO)

## Comment utiliser

1. **Importation d'image**
   - Cliquez sur le bouton "Choisir un fichier" dans la section "Image Source"
   - Sélectionnez votre image

2. **Vectorisation**
   - Ajustez le nombre de couleurs (2 minimum)
   - Réglez la précision de la vectorisation
   - Le résultat s'affiche en temps réel

3. **Modélisation 3D**
   - Pour chaque couleur détectée, vous pouvez :
     - Activer/désactiver l'extrusion (checkbox)
     - Définir une hauteur d'extrusion (en mm)
   - Utilisez le curseur d'échelle pour redimensionner le modèle

4. **Export**
   - Cliquez sur les boutons correspondants pour télécharger en :
     - SVG (format vectoriel)
     - STL (pour impression 3D)
     - DXF (pour logiciels CAO)

## Technologies utilisées

- HTML5/CSS3/JavaScript
- Three.js pour le rendu 3D
- ImageTracer.js pour la vectorisation
- SVGLoader pour la conversion SVG vers 3D
- svg2dxf pour l'export DXF

## Contribution

Les contributions sont les bienvenues ! N'hésitez pas à ouvrir une issue ou proposer une pull request.

## Licence

Ce projet est sous licence MIT.

## Auteur

Julien RAT - 2025
