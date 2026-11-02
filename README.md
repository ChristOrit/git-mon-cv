# Mon CV en ligne

Page web statique (HTML/CSS) présentant le curriculum vitae de Christ OrittcHacheoun, étudiant en 2e année d'informatique à l'ESGIS-Bénin. Le projet a été construit en s'exerçant avec les branches Git (une branche par section du CV).

## Contenu du CV

- **Présentation** : courte description personnelle
- **Formations** : BAC D (2021), BEPC (2018), certifications 2023 (CEH, CCNA, OCSP, PHP & MySQL)
- **Compétences** : développement web front-end/back-end, UX/UI design, réseaux locaux, montage vidéo, optique
- **Associations** : club de Sécurité (ESGIS), club de lecture (UAC Calavi), etc.

## État du projet

- `index.html` — contenu du CV. Le fichier contient encore des **marqueurs de conflit Git non résolus** (`<<<<<<< HEAD`) entre les branches de sections : le contenu des 4 sections est présent mais à fusionner proprement.
- `style.css` — feuille de style, encore vide (aucune mise en page pour l'instant).
- La page ne contient pas encore de balises `<head>` complètes (titre, langue FR, encodage à finaliser).

## Ouvrir la page

Aucune dépendance ni build : ouvrez `index.html` directement dans un navigateur, ou servez le dossier :

```bash
python3 -m http.server 8080
# puis ouvrir http://localhost:8080
```
