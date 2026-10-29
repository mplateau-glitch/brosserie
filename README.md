# La Brosserie — variantes d'une même inspiration

Application web interactive mettant en scène le passage d'un poème à ses variantes.

## Description

- Un texte apparaît aléatoirement parmi 17 variantes (la prose initiale et les 16 versions du poème « La brosserie », d'après Francis Ponge).
- **Souris** : les lettres et les mots sont emportés par le mouvement comme par un souffle, puis reprennent leur place quand la souris s'arrête.
- **Clic** : les lettres s'éparpillent et se réassemblent pour former une autre variante — soulignant que les poèmes sont des variantes d'une même inspiration.
- **Espace** : fige l'image, puis relance l'animation.
- Police *Special Elite* rappelant les machines à écrire des années 40-50.
- Sons mécaniques de machine à écrire (claquements, ding de fin de ligne, retour de chariot) synthétisés en WebAudio, sans fichiers audio.

## Utilisation

Ouvrir `index.html` dans un navigateur — aucun build, aucune dépendance. Le son démarre au premier mouvement de souris ou clic (exigence des navigateurs).

## Déploiement

Site 100 % statique : glisser-déposer le dossier sur [Netlify Drop](https://app.netlify.com/drop), ou connecter le dépôt GitHub à Netlify.
