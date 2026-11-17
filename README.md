# SONOSPHÈRE 3D 🎻

Instrument audiovisuel interactif en **HTML + CSS + JavaScript**. Le **code du site est dans `index.html`**. Ce fichier contient l'interface, l'animation 3D et le moteur audio (Web Audio API), y compris le mode **VIOLON**.

## Télécharger et jouer en local (Windows 10 / Windows 11)

**Sans installation, sans compte et sans Internet une fois les fichiers téléchargés.**

1. [Télécharger le projet en ZIP](https://github.com/gratuitmusique123-prog/sonosphere-3d/archive/refs/heads/main.zip).
2. Cliquer avec le bouton droit sur le fichier ZIP puis **Extraire tout**.
3. Dans le dossier extrait, **double-cliquer sur `index.html`** : le site s'ouvre dans Edge, Chrome ou Firefox.
4. **Cliquer dans l'animation pour activer le son.** Le navigateur demande un geste pour démarrer la synthèse audio.
5. Cliquer sur **🎻 VIOLON**, garder le bouton de souris enfoncé et glisser pour changer la note. Sur un écran tactile, poser et déplacer le doigt.

Il n'est pas nécessaire d'installer Node.js, Python, de compiler, de démarrer un serveur local ni d'utiliser une API.

## Sons et modes

- **ORBITE** : notes spatiales douces.
- **CRISTAL** : sons cristallins.
- **PULSE** : synthèse rythmique.
- **🎻 VIOLON** : simulation de cordes frottées, vibrato et glissement entre les notes.

Les notes sont synthétisées **sur l'appareil**, pas téléchargées depuis Internet. Il s'agit d'un violon électronique synthétique, pas d'un échantillon enregistré d'un vrai instrument. Le bouton ♫ déclenche la mélodie automatique.

## Code source

- [Ouvrir `index.html`](https://github.com/gratuitmusique123-prog/sonosphere-3d/blob/main/index.html)
- [Télécharger uniquement le fichier HTML](https://raw.githubusercontent.com/gratuitmusique123-prog/sonosphere-3d/main/index.html)
- [Télécharger tout le dépôt en ZIP](https://github.com/gratuitmusique123-prog/sonosphere-3d/archive/refs/heads/main.zip)

## 🌍 Publication officielle sur GitHub Pages

La page du jeu est déjà le fichier `index.html` situé à la racine de la branche `main`. Il faut seulement activer GitHub Pages UNE FOIS sur GitHub, comme ceci :

1. Ouvrir [Settings → Pages](https://github.com/gratuitmusique123-prog/sonosphere-3d/settings/pages) en étant connecté au compte propriétaire.
2. Dans **Build and deployment → Source**, choisir **Deploy from a branch**.
3. Dans **Branch**, choisir **main**, puis **/(root)**, et cliquer sur **Save**.
4. Une fois GitHub Pages publié, le jeu s'ouvre sans compte à **https://gratuitmusique123-prog.github.io/sonosphere-3d/**.

Le site ne demande ni serveur, ni compilation, ni déploiement GitHub Actions. Le fichier `index.html` suffit. Si la page affiche 404 avant l'activation, c'est normal : mettre un dépôt en public ne suffit pas à activer GitHub Pages.

## Version en ligne

[SONOSPHÈRE 3D sur Base44](https://sonosphere-3-d-3329cced.base44.app/) (publication publique). La publication GitHub Pages n'est actuellement pas activée, mais cela **n'empêche pas** l'utilisation locale depuis `index.html`.

## Licence et dépendances

Ce prototype n'utilise pas de bibliothèque distante, de modèle d'IA, de serveur audio ou de CDN. L'ensemble de la synthèse tourne dans le navigateur avec Canvas et Web Audio.
