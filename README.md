# Synthé

Clavier de piano dans le navigateur pour composer les musiques et bruitages du jeu « Un Noël au Vietnam ».

- Instruments : piano, guitare, basse, violon, flûte, harmonica, banjo, grosse caisse, charleston, plus ceux du jeu (triangle, carré, sinus, scie, cuivres, cordes, timbale, caisse claire, cymbale).
- Enregistrement en direct (calé sur la grille) ou note par note, et grille de rythme.
- Pistes à accords (voix séparées par `|`, exportées en une partie par voix), fusion de pistes et regroupement par instrument.
- Partition éditable : glisser une note pour la décaler ou changer sa hauteur, tirer son bord pour la rallonger, double-clic pour ajouter ou supprimer, sélection d’un passage pour l’effacer, le couper, le copier, le coller ou le dupliquer ; zoom, hauteur réglable et longueur de piste.
- Morceaux : nouveau, vider, sauvegarder et rouvrir (dans le navigateur), annuler avec Ctrl+Z, refaire avec Ctrl+Y.
- Génère le code au format `TRACKS` (musique en boucle) ou `sfx` (bruitage), ainsi que le code moteur à ajouter une seule fois au jeu pour les nouveaux instruments.

Tout tient dans `index.html`, sans dépendance. En ligne via GitHub Pages : https://yvanngn.github.io/synthe/
