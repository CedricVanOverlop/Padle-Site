# Padel Club Charleroi - Site Web

Site web pour le Padel Club Charleroi (Fictif)

## 📁 Structure du projet

```
/
├── index.html                      # Page d'accueil avec scroll
├── contact.html                    # Page de contact
├── cours.html                      # Page cours & stages
├── reservation.html                # Page de réservation
├── tournois-interclubs.html        # Page tournois & interclubs
├── css/
│   └── style.css                   # Fichier CSS principal
└── image/                          # Dossier des images
```

## 🎨 Pages du site

- **Accueil** (`index.html`) : Page avec scroll vertical et 5 sections
- **Cours & Stages** (`cours.html`) : Informations sur les cours, coachs et stages
- **Tournois & Interclubs** (`tournois-interclubs.html`) : Calendrier des événements
- **Contact** (`contact.html`) : Coordonnées et horaires
- **Réservation** (`reservation.html`) : Formulaire de réservation de terrains

## 🎯 Fonctionnalités

- Design responsive (mobile, tablette, desktop)
- Navigation sticky
- Scroll snap sur la page d'accueil
- Système d'accordéon pour les tournois
- Popup pour le menu de la buvette
- Formulaire de réservation

## 📱 Responsive

Le site est optimisé pour :
- **Desktop** : > 1024px
- **Tablettes** : 769px - 1024px
- **Mobiles** : 768px - 450px
⚠️ La page index n'est pas optimisée pour des écrans avec un rapport longueur / largeur > 1.8 ou pour les écrans <450px?
🎯 Cependant cela ne procure aucun bug. 

## 🎨 CSS

Le fichier `style.css` est organisé en 10 sections :
1. Configuration générale
2. Header
3. Footer
4. Main
5. Page Index
6. Page Cours
7. Contact
8. Tournois & Interclubs
9. Réservation
10. Media Queries (tous regroupés)


## 🚀 Utilisation

Ouvrir `index.html` dans un navigateur web.

Aucune dépendance externe requise - HTML/CSS pur.
