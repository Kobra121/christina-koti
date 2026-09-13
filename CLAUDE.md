# Christina Maria Koti — site vitrine

Site d'une pianiste grecque installée à Paris (duo voix-piano avec le baryton
Jared Andrew Michaud). Un seul fichier `index.html` auto-suffisant (CSS/JS inline),
pas de framework, pas de build. Ressource externe : Google Fonts (Cormorant Garamond,
Inter). Vidéos YouTube en « lite embed » (iframe youtube-nocookie chargée au clic).

## Sources

- Bio : https://www.maison-heinrich-heine.org/intervenant/christina-koti/ (texte FR
  repris presque tel quel dans #biographie et les cartes « Prix & sélections »).
- Photos :
  - `img/hero.jpg` — portrait N&B (source `IMG-20230829-WA0000.jpg`, 1024×683 compressé
    WhatsApp, agrandi ×2 en Lanczos + légère accentuation via Pillow ; à remplacer par un
    original haute définition ou une version upscalée par IA si disponible).
  - `img/concert.jpg` (1600×1066, concert J.M. Vogl-Stichting, NL) ; `img/portrait.jpg` et
    `img/concert-wide.jpg` sont des recadrages de la même photo (bio et bandeau plein écran).
- Vidéos : chaîne YouTube de Jared Michaud (ids 4SEMbp23WGM, uTiZpJYGtWU, ATH_xhk1mL8, 60OztQLdFho).

## Orientation éditoriale

Christina d'abord comme **pianiste** (récital, musique de chambre), le duo voix-piano avec
Jared Andrew Michaud est une facette parmi d'autres. La section Vidéos a un bloc « Piano
solo » (placeholder « en préparation ») à remplir dès que les vidéos solo arrivent, puis
le bloc duo.

## À compléter

- Adresse e-mail réelle (placeholder `contact@christinakoti.com` dans #contact).
- Prochaines dates dans #agenda (les deux entrées actuelles sont passées).
- Vidéos piano solo (remplacer le placeholder), version EN, réseaux sociaux, plus de photos.

## Design

Thème sombre : fond `#0b0b0d`, encre ivoire `#ece7dd`, accent doré `#c9a96e` (parcimonieux).
Titres serif Cormorant Garamond, corps Inter 300. Reveal au scroll, hero plein écran
avec la photo de concert assombrie.

## Aperçu local

Depuis le repo Sonata : configuration `christina-koti` du launch.json (python http.server, port 8765).
