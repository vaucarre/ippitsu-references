# Fiche de référence du décor — Monde 1, Archipel — prompt type

À joindre au générateur avec : les planches `01_vue_ensemble.jpg` (échelle, caméra, sol jouable, palette),
`02_salles.jpg`, `03_sanctuaire_boss.jpg`, `04_objets_decor.jpg`, `05_sol_eau_bords.jpg`, et une fiche de personnage
pour le style (`ippitsu-env/heros-fiche/fiche_reference.jpg`, `bestiaire-w1/fiches/ashigaru.jpg`).
On peut générer une fiche par sujet : **salle type**, **sanctuaire de départ**, **arène du gardien/boss**,
**kit d'objets**, **matières (sol, bords, eau)** — remplacer `{SUJET}` et `{PIÈCES}`.

---

## English

```
Environment concept sheet for a mobile roguelite, same layout language and render style as the attached
character sheets (stylized chibi 3D, soft render, dark charcoal background #16181E, clean rounded panels,
white sans-serif labels). World 1 "Archipelago": an ukiyo-e ocean harbour — wooden piers and boardwalks over
a deep blue sea, fishermen's stilt houses, lanterns, sake barrels, moored boats, a red torii at the end of the
pier, Hokusai's Great Wave on the horizon. Subject: {SUBJECT, e.g. "a standard combat room"}.

Layout, 3:2 landscape:
1. LEFT, large: the in-game view from the game camera (looking down at 44°, narrow 32° field of view, portrait
   phone frame 9:19.5). A long straight pier, 9.2 m wide, fills the width of the frame; the chibi ronin hero
   (navy gi, straw kasa hat, vermilion scarf, 1.75 m, about 4 heads tall) stands in the lower third for scale.
   The walkable pier is a clear, calm, mid-value central path; the edges are dense and colourful; the sea on
   both sides is out of bounds; an exit landmark (torii or gate) at the far end.
2. TOP RIGHT: top-down floor plan of the room (9.2 m × 17.2 m per section, several sections in a row), walkable
   area outlined, props on the borders, entrance at the bottom, exit at the top, a 1 m grid and the hero
   silhouette for scale.
3. MIDDLE: the modular kit, each piece in its own rounded frame, in 3/4 view next to a 1.75 m hero silhouette:
   {PIECES, e.g. "plank 0.62 m wide, dark sumi edge beam, corner, footbridge, steps, stilts, rope and bollards"}.
4. RIGHT: material swatches as flat squares (sand-coloured wet planks with knots and grain, dark beam, brown
   underside, rope, sea with seigaiha wave pattern, white claw-like foam) and the world palette with hex codes:
   #5E98D6 #2B6BAA #1F578F #163E6A #0A233B (sea), #9C8C6A #A88452 (wood), #1B1A1E (ink edges).
5. Small strip: 3 close-up views at the low camera (32°): pier edge with reeds and foam, a lantern cluster,
   moored boat.

Style constraints (strict):
- Toon / cel-shading with 2–3 hard bands, flat colour areas, dark sumi-ink outlines on every object.
- Soft key light from the left, cool shadows (#A3BDFF tint), no dramatic backlight.
- NO glow, NO bloom, NO light rays, NO emissive halos; lanterns are lit by colour, not by light bleeding.
- NO kanji or Japanese symbols painted on the ground (allowed on objects: lanterns, banners, plaques).
- No background band under the ground. The sea is the void around the pier.
- Readable on a small phone screen: the walkable floor stays mid-value and low-detail (wide planks, clean
  joints, no fine high-contrast pattern that would shimmer), so that the black ink stroke, the navy enemies and
  the vermilion danger markers pop on it. Strong contrast is kept for the borders and props.
- Vermilion red only for the torii and small accents (it is reserved in-game for danger and the player's hits).
```

## Français

```
Fiche de concept de décor pour un roguelite mobile, même langage de mise en page et même rendu que les fiches
de personnages jointes (3D chibi stylisée, rendu doux, fond anthracite #16181E, cadres arrondis, textes blancs).
Monde 1 « Archipel » : un port d'estampe sur l'océan — pontons et quais de planches au-dessus d'une mer bleu
profond, maisons de pêcheurs sur pilotis, lanternes, tonneaux de saké, barques amarrées, un torii rouge au bout
du ponton, la Grande Vague d'Hokusai à l'horizon. Sujet : {SUJET, ex. « une salle de combat type »}.

Mise en page, paysage 3:2 :
1. À GAUCHE, en grand : la vue en jeu à la caméra du jeu (plongée 44°, focale serrée 32°, cadre de téléphone
   portrait 9:19,5). Un long ponton droit de 9,2 m de large remplit la largeur du cadre ; le héros ronin chibi
   (gi bleu nuit, kasa de paille, écharpe vermillon, 1,75 m, ≈ 4 têtes) dans le tiers bas pour l'échelle.
   Le quai jouable est une allée centrale nette, calme, de valeur moyenne ; les bords sont denses et colorés ;
   la mer des deux côtés est hors jeu ; un repère de sortie (torii ou porte) au fond.
2. EN HAUT À DROITE : le plan de la salle vu de dessus (9,2 × 17,2 m par tronçon, plusieurs tronçons à la suite),
   contour du sol jouable, objets sur les bords, entrée en bas, sortie en haut, grille de 1 m et silhouette du
   héros pour l'échelle.
3. AU MILIEU : le kit modulaire, chaque pièce dans son cadre arrondi, en 3/4 à côté d'une silhouette de héros
   de 1,75 m : {PIÈCES, ex. « planche de 0,62 m, poutre de bord sumi, angle, passerelle, marches, pilotis, corde
   et bittes d'amarrage »}.
4. À DROITE : les matières en carrés plats (planches de sable mouillé avec nœuds et veines, poutre sombre,
   dessous brun, corde, mer à motif seigaiha, écume blanche en griffes) et la palette du monde avec les codes :
   #5E98D6 #2B6BAA #1F578F #163E6A #0A233B (mer), #9C8C6A #A88452 (bois), #1B1A1E (bords d'encre).
5. Bande du bas : 3 gros plans à la caméra basse (32°) : bord du ponton avec roseaux et écume, groupe de
   lanternes, barque amarrée.

Contraintes de style (strictes) :
- Cell-shading à 2-3 bandes nettes, aplats, contour d'encre sumi sur chaque objet.
- Lumière douce de la gauche, ombres froides (teinte #A3BDFF), pas de contre-jour.
- AUCUN glow, bloom, rayon de lumière ni halo émissif ; les lanternes sont « allumées » par la couleur, sans
  lumière qui bave.
- AUCUN kanji ni symbole japonais peint au sol (permis sur les objets : lanternes, bannières, plaques).
- Pas de bande de fond sous le sol. La mer est le vide autour du ponton.
- Lisible sur un petit écran : le sol jouable reste de valeur moyenne et peu détaillé (planches larges, joints
  nets, pas de motif fin et contrasté qui scintille), pour que le trait d'encre noir, les ennemis bleu nuit et
  les annonces vermillon ressortent dessus. Les forts contrastes sont gardés pour les bords et les objets.
- Vermillon seulement pour le torii et de petites touches (en jeu, il est réservé aux dangers et aux coups du
  joueur).
```

---

## Sujets à générer, dans l'ordre conseillé

1. **Matières : sol, bords, eau** (ce qui occupe le plus l'écran à la caméra rapprochée) — planche `05`.
2. **Salle type** (vue en jeu + plan + kit modulaire) — planches `01` et `02`.
3. **Kit d'objets du quai** : lanternes (papier, mate, pierre), tonneaux, caisse, filet, flotteur, panier, seau,
   bittes, rochers, barque, maison de pêcheur, cabane sur pilotis, nobori, torii — planche `04`.
4. **Sanctuaire de départ** (ponton du torii, embarcadère) — planche `03`.
5. **Arène du gardien et du boss** (parvis de bois sombre, pavillon, tōrō en rang, cercle d'arène) — planche `03`.
