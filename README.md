# PTO Geotag - Application d'Horodatage de Photos

Application web single-file pour horodater et géolocaliser des photos techniques de type PTO (Point de Terminaison Optique).

## 🎯 Fonctionnalités

- 📷 **Prise de photo directe** ou sélection depuis la galerie (Android compatible)
- 📍 **Géolocalisation automatique** via GPS
- 🌍 **Adresse complète** via l'API OpenStreetMap Nominatim
- 🖼️ **Incrustation de texte** avec contour noir épais pour visibilité maximale
- 🗑️ **Suppression des métadonnées EXIF** d'origine
- 💾 **Téléchargement automatique** avec nom de fichier horodaté

## 📋 Informations incrustées

L'application ajoute 4 lignes de texte en bas à gauche de chaque photo :

1. **Ligne 1** : Texte personnalisable (ex: "PTO", nom du projet, etc.)
2. **Ligne 2** : Date et heure au format `JJ/MM/AAAA HH:MM:SS`
3. **Ligne 3** : Coordonnées GPS `Latitude ; Longitude`
4. **Ligne 4** : Adresse complète (Numéro Rue Code Postal Ville)

## 🚀 Utilisation

1. Ouvrez `index.html` dans votre navigateur (Chrome ou Firefox recommandé)
2. Autorisez l'accès à la localisation quand demandé
3. Cliquez sur "📷 Prendre/Choisir une photo"
4. Attendez le traitement (GPS + adresse + incrustation)
5. Téléchargez la photo traitée

## 📱 Compatibilité Mobile

- ✅ Android (Chrome, Firefox)
- ✅ iOS (Safari)
- ⚠️ Nécessite l'autorisation de localisation
- ⚠️ Nécessite une connexion Internet pour l'adresse

## 🔧 Technologies

- HTML5 Canvas pour le traitement d'image
- Geolocation API pour le GPS
- OpenStreetMap Nominatim API pour le géocodage inversé
- Vanilla JavaScript (aucune dépendance)

## 📄 Licence

Libre d'utilisation

## 👨‍💻 Auteur

Mohamed Fettis
