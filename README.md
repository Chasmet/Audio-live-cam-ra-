# Souvenir Clip

Application web mobile pour se filmer pendant qu'un morceau démarre exactement au moment choisi.

## Fonctionnalités V1

- Interface caméra verticale type application mobile.
- Caméra avant/arrière.
- Import audio depuis le téléphone : MP3, M4A, WAV, OGG, AAC.
- Choix du départ du morceau avec curseur.
- Bouton `Tester` pour écouter le passage avant de filmer.
- Minuterie avant enregistrement : 0 s, 2 s ou 5 s.
- Enregistrement vidéo avec l'audio choisi intégré.
- Le son de la caméra/micro est désactivé : la vidéo finale contient uniquement l'audio importé.
- Aperçu, recommencer, revoir et télécharger la vidéo.

## Important

La V1 fonctionne sans serveur et peut être publiée sur GitHub Pages.

Sur Android, le fichier exporté est généralement en `.webm`, car c'est le format le mieux supporté par Chrome mobile pour l'enregistrement caméra + audio.

## Utilisation

1. Ouvrir l'application depuis une adresse HTTPS, par exemple GitHub Pages.
2. Autoriser la caméra.
3. Appuyer sur l'icône musique.
4. Importer un audio.
5. Choisir le moment de départ.
6. Choisir la minuterie : 0 s, 2 s ou 5 s.
7. Appuyer sur le bouton rouge.
8. Appuyer à nouveau pour arrêter.
9. Télécharger la vidéo finale.

## Limites connues

- Le flash vidéo n'est pas activé dans cette V1 web.
- Le format de sortie est `.webm` selon le navigateur.
- La qualité 1080p / 60 fps dépend du téléphone et du navigateur.
