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
Jared Andrew Michaud est une facette parmi d'autres. La section Vidéos ouvre sur un bloc « Piano
solo » (Mompou h1INrrYjYsg, Poulenc 4hUnn06Rluk — chaîne @ChristinaMariaKoti, id
UCM_k_xT2NbA-mvHaWPi01qQ), puis le bloc duo (chaîne de Jared Michaud).

## À compléter

- Contact : christinamariakoti@gmail.com et chaîne YouTube @ChristinaMariaKoti (repris de son ancien site christinamariakoti.com, WordPress, période londonienne).
- Prochaines dates dans #agenda (les deux entrées actuelles sont passées).
- Nouvelles vidéos solo annoncées, version EN, réseaux sociaux, plus de photos.

## Design

Thème sombre : fond `#0b0b0d`, encre ivoire `#ece7dd`, accent doré `#c9a96e` (parcimonieux).
Titres serif Cormorant Garamond, corps Inter 300. Reveal au scroll, hero plein écran
avec la photo de concert assombrie.

## Hébergement

Repo GitHub public `Kobra121/christina-koti`, servi par GitHub Pages depuis `main` (racine) :
**https://kobra121.github.io/christina-koti/**. Chaque push sur `main` redéploie en ~1 min.
Aperçu partagé (sans lecteur vidéo intégré) publié aussi en Artifact Claude.
Domaine : **christinamariakoti.com** (registrar WordPress.com/Automattic, compte de Christina, expire 01/2027 ; fichier `CNAME` à la racine, DNS A → GitHub Pages + CNAME www). christinamariacoti.com = achat par erreur chez Namecheap, remboursement demandé.

## SEO (posé le 13/09/2026)

- Title « Christina Maria Koti — Pianiste à Paris », canonical https://christinamariakoti.com/,
  Open Graph + Twitter card avec `img/og-image.jpg` (1200×630, générée par Pillow depuis
  `img/hero.jpg` + Georgia ; régénérer si le portrait change).
- JSON-LD : Person (pianiste, alumni, prix, sameAs YouTube + Maison Heinrich Heine) + WebSite
  + 2 VideoObject (piano solo). Garder synchronisé avec la bio et les vidéos.
- `robots.txt`, `sitemap.xml` (mettre à jour lastmod à chaque changement notable),
  `404.html` (redirige vers l'accueil : les anciennes URL WordPress /about/ etc. y tombent).
- Favicons `img/favicon-32.png`, `img/icon-192.png`, `img/apple-touch-icon.png` (K doré).
- Google Search Console : à vérifier par Christina (propriété de domaine via TXT DNS chez
  WordPress.com, ou balise meta à ajouter dans le head), puis soumettre le sitemap.

## Aperçu local

Depuis le repo Sonata : configuration `christina-koti` du launch.json (python http.server, port 8765).
