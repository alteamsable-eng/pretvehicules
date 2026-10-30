# Prêt Véhicules - Gestion du parc atelier

Application web simple pour suivre les véhicules en prêt, les retours, les disponibilités et les retards au niveau d'un atelier.

## Fonctionnalités

- Gestion des véhicules du parc
- Suivi des prêts et des emprunteurs
- Statistiques globales du parc
- Détection des prêts en retard
- Persistance locale dans le navigateur via `localStorage`
- Interface simple et rapide pour l'atelier

## Démarrage rapide

### Option 1 : ouvrir directement

- Ouvrez simplement le fichier `index.html` dans votre navigateur.

### Option 2 : lancer un petit serveur local

```bash
cd pretvehicules
python3 -m http.server 8000
```

Puis ouvrez :

```text
http://localhost:8000
```

## Structure du projet

- `index.html` : structure de l'application
- `styles.css` : affichage et design
- `app.js` : logique métier et données

## Utilisation

1. Ajoutez des véhicules dans le formulaire de gauche.
2. Créez un prêt depuis le formulaire de droite.
3. Cliquez sur "Retourner" pour clôturer un emprunt.
4. La date de retour prévue est utilisée pour détecter les retards.
