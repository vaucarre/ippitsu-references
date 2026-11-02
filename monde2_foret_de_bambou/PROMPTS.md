# Prompts ChatGPT : fiches modèles du monde 2 (Forêt de bambou)

## Mode d'emploi

1. Ouvrir une nouvelle conversation ChatGPT (génération d'image) et **joindre la planche** `02_foret_de_bambou.png` (C:/Users/victo/ippitsu-env/bestiaires-gpt/02_foret_de_bambou.png). Joindre aussi une fiche du monde 1 (par exemple `bestiaire-w1/fiches/ashigaru.png`) comme modèle de mise en page si possible.
2. **Coller le prompt** du personnage (version française ; la version anglaise est en dessous si le résultat dérive).
3. Vérifier : 5 vues complètes, même échelle, même largeur de chapeau ou de coiffe d'une vue à l'autre, aucun texte sur les vues. Sinon, redemander en citant la contrainte non respectée.
4. **Enregistrer l'image** sous `fiches/<genre>.png` dans ce dossier (`monde2_foret_de_bambou/fiches/`), avec le même nom que la découpe correspondante dans `decoupes/`.

Un personnage par conversation (ou repartir d'une conversation propre) pour éviter que les personnages se mélangent.

Personnages (17) : `oni`, `kappa`, `brute`, `tate`, `funa`, `kitsunebi`, `kamaitachi`, `tanuki`, `kitsune_tsukai`, `kappa_yumi`, `shinobi`, `shuriken`, `kitsunebi_s`, `tanuki_d`, `brute_elite`, `sohei_gashira`, `ishi_nio`

---

## PAYSAN-MOINE : `fiches/oni.png`

Rôle : COMMUN · découpe : `decoupes/oni.png`

### Prompt (FR)

```text
Utilise la planche jointe (bestiaire « 2. FORÊT DE BAMBOU ») comme référence. Le personnage est celui de la carte « PAYSAN-MOINE » (rôle COMMUN, genre interne « oni »).

Crée sa fiche modèle individuelle, une seule image paysage 1536×1024, dans exactement le même style et la même mise en page que les fiches du monde 1 (Archipel) : rendu 3D stylisé façon figurine chibi, éclairage doux de studio, fond sombre presque noir.

PERSONNAGE (à respecter exactement, tel qu'il apparaît sur la grande vue de la planche) :
Petit moine-paysan chibi (env. 2,5 têtes de haut), garçon aux cheveux noirs mi-longs en mèches, grands yeux bleu-vert, air calme et sérieux. Grand chapeau conique de paille tressée beige. Kimono court écru à col croisé vert, ceinture vert foncé serrée par une cordelette de paille nouée sur le devant, hakama court vert mousse un peu effiloché, jambes nues, pieds nus. Hotte en osier tressé portée dans le dos par deux bretelles. Bâton de bois court à embout vert et bague dorée, tenu dans la main droite.

MISE EN PAGE :
- En haut à gauche : bandeau incliné couleur vert bambou avec une petite icône et le texte « MONDE 2 - FORÊT DE BAMBOU ». Dessous : petit portrait carré du visage, le nom « PAYSAN-MOINE » en grandes capitales blanches, une étiquette de rôle « COMMUN », et une ligne « ♥ — PV ».
- Colonne de gauche, sur toute la hauteur : grande pose 3/4 dynamique (il avance en tenant son bâton, la hotte bien visible), dans un décor du monde : la forêt de bambou : hautes tiges de bambou vert, temple de bois au fond de la bambouseraie, lanternes de pierre allumées, brume verte et lucioles. Le décor ne doit pas masquer le personnage.
- En haut à droite : vue tournante en 5 vues en pied, de gauche à droite : FACE, 3/4 FACE, PROFIL, DOS, 3/4 DOS. Fond sombre uni sans décor, chaque figurine posée sur un fin anneau lumineux vert bambou au sol. Les 5 figurines entières (de la pointe de la tête ou du chapeau jusqu'aux pieds), à la même échelle, pieds sur la même ligne, sommets à la même hauteur. Pose neutre identique sur les 5 vues : debout droit, bras un peu écartés du corps, bâton tenu verticalement le long du corps, main droite.
- Au centre : grille de 8 gros plans (2 colonnes × 4 lignes) dans des cadres arrondis à bord fin vert bambou : visage et yeux sous le bord du chapeau ; vannerie de la hotte ; nœud de cordelette de la ceinture ; puis dos de la tête ou de la coiffe, épaule et col, mains, pieds ou chaussures, détail du dos.
- À droite : panneau encadré avec la même pose en fil de fer blanc (maillage visible) sur fond sombre, les indications « ≈ tris », « ≈ verts », « 1 texture (PBR) 2048 × 2048 », et 3 vignettes de textures empilées (albedo dépliée, normal map bleue, roughness en gris).

CONTRAINTES DE COHÉRENCE (prioritaires) :
- Le même personnage, strictement identique sur la grande pose, les 5 vues, les gros plans et le fil de fer : mêmes couleurs, mêmes motifs, mêmes accessoires, du même côté du corps.
- Mêmes proportions sur les 5 vues (même hauteur totale, même taille de tête, même largeur d'épaules). Chapeau conique de paille (kasa) : même diamètre sur les 5 vues, environ 1,6 fois la largeur des épaules, même hauteur de pointe. Une vue où la coiffe, le chapeau ou l'arme change de taille rend la fiche inutilisable : c'est le défaut à éviter en priorité.
- Les 5 vues sont de vraies rotations orthographiques du même modèle (pas de perspective différente, pas de pose différente).
- Aucun texte, chiffre, flèche ni étiquette sur les 5 vues et sur les gros plans ; le texte n'apparaît que dans le bandeau, le bloc nom et le panneau fil de fer.
- Ne recopie pas la carte de la planche ni ses petites vignettes (elles sont parfois différentes du personnage) : suis la grande vue de la carte.
```

### Prompt (EN)

```text
Use the attached board (bestiary "2. FORÊT DE BAMBOU") as reference. The character is the one on the card "PAYSAN-MOINE" (role COMMUN, internal genre "oni").

Create its individual model sheet, a single landscape image 1536×1024, in exactly the same style and layout as the world 1 (Archipel) sheets: stylized 3D chibi figurine render, soft studio lighting, dark near-black background.

CHARACTER (follow exactly, as it appears in the large view of the board):
Chibi peasant-monk (about 2.5 heads tall), boy with mid-length black hair in strands, big blue-green eyes, calm serious look. Large beige woven-straw conical hat. Short off-white kimono with green crossed collar, dark green belt tied with a straw cord knotted at the front, short frayed moss-green hakama, bare legs, bare feet. Woven wicker basket carried on the back by two straps. Short wooden staff with a green tip and gold ring, held in the right hand.

LAYOUT:
- Top left: slanted bamboo green banner with a small icon and the text "MONDE 2 - FORÊT DE BAMBOU". Below: small square face portrait, the name "PAYSAN-MOINE" in large white capitals, a role tag "COMMUN", and a line "♥ — PV".
- Left column, full height: large dynamic 3/4 pose (walking forward holding his staff, basket clearly visible), in a world setting: the bamboo forest: tall green bamboo stalks, wooden temple deep in the grove, lit stone lanterns, green mist and fireflies. The setting must not hide the character.
- Top right: 5-view full-body turnaround, left to right: FRONT, 3/4 FRONT, SIDE, BACK, 3/4 BACK. Plain dark background with no scenery, each figurine standing on a thin glowing bamboo green ring on the floor. All 5 figurines complete (from the top of the head or hat down to the feet), same scale, feet on the same line, tops at the same height. Identical neutral pose in all 5 views: standing straight, arms slightly away from the body, staff held vertically along the body, right hand.
- Centre: grid of 8 close-ups (2 columns × 4 rows) in rounded frames with a thin bamboo green border: face and eyes under the hat brim; wicker weave of the basket; straw-cord belt knot; then back of the head or headgear, shoulder and collar, hands, feet or shoes, back detail.
- Right: framed panel with the same pose as a white wireframe (visible mesh) on a dark background, the labels "≈ tris", "≈ verts", "1 texture (PBR) 2048 × 2048", and 3 stacked texture thumbnails (unwrapped albedo, blue normal map, grey roughness).

CONSISTENCY RULES (top priority):
- The same character, strictly identical in the large pose, the 5 views, the close-ups and the wireframe: same colours, same patterns, same accessories, on the same side of the body.
- Same proportions in all 5 views (same total height, same head size, same shoulder width). Conical straw hat (kasa): identical diameter in all 5 views, about 1.6x the shoulder width, same tip height. A view where the headgear, hat or weapon changes size makes the sheet unusable: this is the defect to avoid first.
- The 5 views are true orthographic rotations of the same model (no different perspective, no different pose).
- No text, numbers, arrows or labels on the 5 views or the close-ups; text only appears in the banner, the name block and the wireframe panel.
- Do not copy the board card or its small thumbnails (they sometimes differ from the character): follow the card's large view.
```

---

## MOINE AU BÂTON : `fiches/kappa.png`

Rôle : COMMUN · découpe : `decoupes/kappa.png`

### Prompt (FR)

```text
Utilise la planche jointe (bestiaire « 2. FORÊT DE BAMBOU ») comme référence. Le personnage est celui de la carte « MOINE AU BÂTON » (rôle COMMUN, genre interne « kappa »).

Crée sa fiche modèle individuelle, une seule image paysage 1536×1024, dans exactement le même style et la même mise en page que les fiches du monde 1 (Archipel) : rendu 3D stylisé façon figurine chibi, éclairage doux de studio, fond sombre presque noir.

PERSONNAGE (à respecter exactement, tel qu'il apparaît sur la grande vue de la planche) :
Moine chibi au bâton : même gabarit que le paysan-moine, cheveux noirs, regard déterminé. Grand chapeau conique de paille beige. Kimono écru à col croisé vert, ceinture verte nouée avec pans pendants, hakama court vert foncé, pieds nus. Long bâton de combat (bō) en bambou clair, plus haut que lui, cerclé de bagues dorées, tenu dans la main droite.

MISE EN PAGE :
- En haut à gauche : bandeau incliné couleur vert bambou avec une petite icône et le texte « MONDE 2 - FORÊT DE BAMBOU ». Dessous : petit portrait carré du visage, le nom « MOINE AU BÂTON » en grandes capitales blanches, une étiquette de rôle « COMMUN », et une ligne « ♥ — PV ».
- Colonne de gauche, sur toute la hauteur : grande pose 3/4 dynamique (garde de combat, bâton planté au sol à côté de lui), dans un décor du monde : la forêt de bambou : hautes tiges de bambou vert, temple de bois au fond de la bambouseraie, lanternes de pierre allumées, brume verte et lucioles. Le décor ne doit pas masquer le personnage.
- En haut à droite : vue tournante en 5 vues en pied, de gauche à droite : FACE, 3/4 FACE, PROFIL, DOS, 3/4 DOS. Fond sombre uni sans décor, chaque figurine posée sur un fin anneau lumineux vert bambou au sol. Les 5 figurines entières (de la pointe de la tête ou du chapeau jusqu'aux pieds), à la même échelle, pieds sur la même ligne, sommets à la même hauteur. Pose neutre identique sur les 5 vues : debout droit, bras un peu écartés du corps, bâton vertical dans la main droite, sans masquer le corps.
- Au centre : grille de 8 gros plans (2 colonnes × 4 lignes) dans des cadres arrondis à bord fin vert bambou : visage sous le chapeau ; bâton bagué d'or ; nœud de la ceinture verte ; puis dos de la tête ou de la coiffe, épaule et col, mains, pieds ou chaussures, détail du dos.
- À droite : panneau encadré avec la même pose en fil de fer blanc (maillage visible) sur fond sombre, les indications « ≈ tris », « ≈ verts », « 1 texture (PBR) 2048 × 2048 », et 3 vignettes de textures empilées (albedo dépliée, normal map bleue, roughness en gris).

CONTRAINTES DE COHÉRENCE (prioritaires) :
- Le même personnage, strictement identique sur la grande pose, les 5 vues, les gros plans et le fil de fer : mêmes couleurs, mêmes motifs, mêmes accessoires, du même côté du corps.
- Mêmes proportions sur les 5 vues (même hauteur totale, même taille de tête, même largeur d'épaules). Chapeau conique de paille (kasa) : même diamètre sur les 5 vues, environ 1,6 fois la largeur des épaules, même hauteur de pointe. Une vue où la coiffe, le chapeau ou l'arme change de taille rend la fiche inutilisable : c'est le défaut à éviter en priorité.
- Les 5 vues sont de vraies rotations orthographiques du même modèle (pas de perspective différente, pas de pose différente).
- Aucun texte, chiffre, flèche ni étiquette sur les 5 vues et sur les gros plans ; le texte n'apparaît que dans le bandeau, le bloc nom et le panneau fil de fer.
- Ne recopie pas la carte de la planche ni ses petites vignettes (elles sont parfois différentes du personnage) : suis la grande vue de la carte.
```

### Prompt (EN)

```text
Use the attached board (bestiary "2. FORÊT DE BAMBOU") as reference. The character is the one on the card "MOINE AU BÂTON" (role COMMUN, internal genre "kappa").

Create its individual model sheet, a single landscape image 1536×1024, in exactly the same style and layout as the world 1 (Archipel) sheets: stylized 3D chibi figurine render, soft studio lighting, dark near-black background.

CHARACTER (follow exactly, as it appears in the large view of the board):
Chibi staff monk: same build as the peasant-monk, black hair, determined look. Large beige straw conical hat. Off-white kimono with green crossed collar, green belt knotted with hanging ends, short dark green hakama, bare feet. Long light bamboo fighting staff (bō), taller than him, banded with gold rings, held in the right hand.

LAYOUT:
- Top left: slanted bamboo green banner with a small icon and the text "MONDE 2 - FORÊT DE BAMBOU". Below: small square face portrait, the name "MOINE AU BÂTON" in large white capitals, a role tag "COMMUN", and a line "♥ — PV".
- Left column, full height: large dynamic 3/4 pose (combat guard, staff planted on the ground beside him), in a world setting: the bamboo forest: tall green bamboo stalks, wooden temple deep in the grove, lit stone lanterns, green mist and fireflies. The setting must not hide the character.
- Top right: 5-view full-body turnaround, left to right: FRONT, 3/4 FRONT, SIDE, BACK, 3/4 BACK. Plain dark background with no scenery, each figurine standing on a thin glowing bamboo green ring on the floor. All 5 figurines complete (from the top of the head or hat down to the feet), same scale, feet on the same line, tops at the same height. Identical neutral pose in all 5 views: standing straight, arms slightly away from the body, staff vertical in the right hand, not hiding the body.
- Centre: grid of 8 close-ups (2 columns × 4 rows) in rounded frames with a thin bamboo green border: face under the hat; gold-ringed staff; green belt knot; then back of the head or headgear, shoulder and collar, hands, feet or shoes, back detail.
- Right: framed panel with the same pose as a white wireframe (visible mesh) on a dark background, the labels "≈ tris", "≈ verts", "1 texture (PBR) 2048 × 2048", and 3 stacked texture thumbnails (unwrapped albedo, blue normal map, grey roughness).

CONSISTENCY RULES (top priority):
- The same character, strictly identical in the large pose, the 5 views, the close-ups and the wireframe: same colours, same patterns, same accessories, on the same side of the body.
- Same proportions in all 5 views (same total height, same head size, same shoulder width). Conical straw hat (kasa): identical diameter in all 5 views, about 1.6x the shoulder width, same tip height. A view where the headgear, hat or weapon changes size makes the sheet unusable: this is the defect to avoid first.
- The 5 views are true orthographic rotations of the same model (no different perspective, no different pose).
- No text, numbers, arrows or labels on the 5 views or the close-ups; text only appears in the banner, the name block and the wireframe panel.
- Do not copy the board card or its small thumbnails (they sometimes differ from the character): follow the card's large view.
```

---

## MOINE ARMÉ : `fiches/brute.png`

Rôle : COMMUN · découpe : `decoupes/brute.png`

### Prompt (FR)

```text
Utilise la planche jointe (bestiaire « 2. FORÊT DE BAMBOU ») comme référence. Le personnage est celui de la carte « MOINE ARMÉ » (rôle COMMUN, genre interne « brute »).

Crée sa fiche modèle individuelle, une seule image paysage 1536×1024, dans exactement le même style et la même mise en page que les fiches du monde 1 (Archipel) : rendu 3D stylisé façon figurine chibi, éclairage doux de studio, fond sombre presque noir.

PERSONNAGE (à respecter exactement, tel qu'il apparaît sur la grande vue de la planche) :
Moine armé chibi, plus trapu : crâne rasé avec un petit chignon noir au sommet, marque rouge en forme de flamme sur le front, sourcils froncés, petites cicatrices sur les joues. Robe vert sombre et cape verte effilochée sur les épaules, gros chapelet (mala) de perles de bois orange autour du cou, ceinture brune à boucle dorée, pieds nus. Lance (yari) à longue lame d'acier aux reflets violacés, hampe en bois, bague dorée, tenue dans la main droite.

MISE EN PAGE :
- En haut à gauche : bandeau incliné couleur vert bambou avec une petite icône et le texte « MONDE 2 - FORÊT DE BAMBOU ». Dessous : petit portrait carré du visage, le nom « MOINE ARMÉ » en grandes capitales blanches, une étiquette de rôle « COMMUN », et une ligne « ♥ — PV ».
- Colonne de gauche, sur toute la hauteur : grande pose 3/4 dynamique (il pointe sa lance vers l'avant, cape au vent), dans un décor du monde : la forêt de bambou : hautes tiges de bambou vert, temple de bois au fond de la bambouseraie, lanternes de pierre allumées, brume verte et lucioles. Le décor ne doit pas masquer le personnage.
- En haut à droite : vue tournante en 5 vues en pied, de gauche à droite : FACE, 3/4 FACE, PROFIL, DOS, 3/4 DOS. Fond sombre uni sans décor, chaque figurine posée sur un fin anneau lumineux vert bambou au sol. Les 5 figurines entières (de la pointe de la tête ou du chapeau jusqu'aux pieds), à la même échelle, pieds sur la même ligne, sommets à la même hauteur. Pose neutre identique sur les 5 vues : debout droit, bras un peu écartés du corps, lance verticale dans la main droite, lame en haut.
- Au centre : grille de 8 gros plans (2 colonnes × 4 lignes) dans des cadres arrondis à bord fin vert bambou : visage à la marque rouge ; chapelet de perles orange ; étoffe verte de la cape ; puis dos de la tête ou de la coiffe, épaule et col, mains, pieds ou chaussures, détail du dos.
- À droite : panneau encadré avec la même pose en fil de fer blanc (maillage visible) sur fond sombre, les indications « ≈ tris », « ≈ verts », « 1 texture (PBR) 2048 × 2048 », et 3 vignettes de textures empilées (albedo dépliée, normal map bleue, roughness en gris).

CONTRAINTES DE COHÉRENCE (prioritaires) :
- Le même personnage, strictement identique sur la grande pose, les 5 vues, les gros plans et le fil de fer : mêmes couleurs, mêmes motifs, mêmes accessoires, du même côté du corps.
- Mêmes proportions sur les 5 vues (même hauteur totale, même taille de tête, même largeur d'épaules). Même taille de tête et même chignon sur les 5 vues. Une vue où la coiffe, le chapeau ou l'arme change de taille rend la fiche inutilisable : c'est le défaut à éviter en priorité.
- Les 5 vues sont de vraies rotations orthographiques du même modèle (pas de perspective différente, pas de pose différente).
- Aucun texte, chiffre, flèche ni étiquette sur les 5 vues et sur les gros plans ; le texte n'apparaît que dans le bandeau, le bloc nom et le panneau fil de fer.
- Ne recopie pas la carte de la planche ni ses petites vignettes (elles sont parfois différentes du personnage) : suis la grande vue de la carte.
```

### Prompt (EN)

```text
Use the attached board (bestiary "2. FORÊT DE BAMBOU") as reference. The character is the one on the card "MOINE ARMÉ" (role COMMUN, internal genre "brute").

Create its individual model sheet, a single landscape image 1536×1024, in exactly the same style and layout as the world 1 (Archipel) sheets: stylized 3D chibi figurine render, soft studio lighting, dark near-black background.

CHARACTER (follow exactly, as it appears in the large view of the board):
Chibi armed monk, stockier: shaved head with a small black top-knot, red flame-shaped mark on the forehead, frowning brows, small scars on the cheeks. Dark green robe and frayed green cape over the shoulders, big mala of orange wooden beads around the neck, brown belt with gold buckle, bare feet. Spear (yari) with a long steel blade with violet glints, wooden shaft, gold ring, held in the right hand.

LAYOUT:
- Top left: slanted bamboo green banner with a small icon and the text "MONDE 2 - FORÊT DE BAMBOU". Below: small square face portrait, the name "MOINE ARMÉ" in large white capitals, a role tag "COMMUN", and a line "♥ — PV".
- Left column, full height: large dynamic 3/4 pose (pointing his spear forward, cape blowing), in a world setting: the bamboo forest: tall green bamboo stalks, wooden temple deep in the grove, lit stone lanterns, green mist and fireflies. The setting must not hide the character.
- Top right: 5-view full-body turnaround, left to right: FRONT, 3/4 FRONT, SIDE, BACK, 3/4 BACK. Plain dark background with no scenery, each figurine standing on a thin glowing bamboo green ring on the floor. All 5 figurines complete (from the top of the head or hat down to the feet), same scale, feet on the same line, tops at the same height. Identical neutral pose in all 5 views: standing straight, arms slightly away from the body, spear vertical in the right hand, blade up.
- Centre: grid of 8 close-ups (2 columns × 4 rows) in rounded frames with a thin bamboo green border: face with the red mark; orange bead mala; green cape fabric; then back of the head or headgear, shoulder and collar, hands, feet or shoes, back detail.
- Right: framed panel with the same pose as a white wireframe (visible mesh) on a dark background, the labels "≈ tris", "≈ verts", "1 texture (PBR) 2048 × 2048", and 3 stacked texture thumbnails (unwrapped albedo, blue normal map, grey roughness).

CONSISTENCY RULES (top priority):
- The same character, strictly identical in the large pose, the 5 views, the close-ups and the wireframe: same colours, same patterns, same accessories, on the same side of the body.
- Same proportions in all 5 views (same total height, same head size, same shoulder width). Same head size and same top-knot in all 5 views. A view where the headgear, hat or weapon changes size makes the sheet unusable: this is the defect to avoid first.
- The 5 views are true orthographic rotations of the same model (no different perspective, no different pose).
- No text, numbers, arrows or labels on the 5 views or the close-ups; text only appears in the banner, the name block and the wireframe panel.
- Do not copy the board card or its small thumbnails (they sometimes differ from the character): follow the card's large view.
```

---

## MOINE AU BOUCLIER : `fiches/tate.png`

Rôle : COMMUN · découpe : `decoupes/tate.png`

### Prompt (FR)

```text
Utilise la planche jointe (bestiaire « 2. FORÊT DE BAMBOU ») comme référence. Le personnage est celui de la carte « MOINE AU BOUCLIER » (rôle COMMUN, genre interne « tate »).

Crée sa fiche modèle individuelle, une seule image paysage 1536×1024, dans exactement le même style et la même mise en page que les fiches du monde 1 (Archipel) : rendu 3D stylisé façon figurine chibi, éclairage doux de studio, fond sombre presque noir.

PERSONNAGE (à respecter exactement, tel qu'il apparaît sur la grande vue de la planche) :
Moine au bouclier chibi : même gabarit que le paysan-moine, cheveux noirs, grand chapeau conique de paille beige. Kimono écru, ceinture verte nouée, hakama court vert, pieds nus. Grand bouclier rond en osier tressé (presque aussi haut que lui) marqué d'une croix en X faite de deux bandes vertes, tenu devant lui au bras gauche.

MISE EN PAGE :
- En haut à gauche : bandeau incliné couleur vert bambou avec une petite icône et le texte « MONDE 2 - FORÊT DE BAMBOU ». Dessous : petit portrait carré du visage, le nom « MOINE AU BOUCLIER » en grandes capitales blanches, une étiquette de rôle « COMMUN », et une ligne « ♥ — PV ».
- Colonne de gauche, sur toute la hauteur : grande pose 3/4 dynamique (accroupi derrière son bouclier, en garde), dans un décor du monde : la forêt de bambou : hautes tiges de bambou vert, temple de bois au fond de la bambouseraie, lanternes de pierre allumées, brume verte et lucioles. Le décor ne doit pas masquer le personnage.
- En haut à droite : vue tournante en 5 vues en pied, de gauche à droite : FACE, 3/4 FACE, PROFIL, DOS, 3/4 DOS. Fond sombre uni sans décor, chaque figurine posée sur un fin anneau lumineux vert bambou au sol. Les 5 figurines entières (de la pointe de la tête ou du chapeau jusqu'aux pieds), à la même échelle, pieds sur la même ligne, sommets à la même hauteur. Pose neutre identique sur les 5 vues : debout droit, bras un peu écartés du corps, bouclier tenu de côté au bras gauche pour laisser voir le corps.
- Au centre : grille de 8 gros plans (2 colonnes × 4 lignes) dans des cadres arrondis à bord fin vert bambou : visage sous le chapeau ; bouclier tressé à croix verte ; nœud de ceinture ; puis dos de la tête ou de la coiffe, épaule et col, mains, pieds ou chaussures, détail du dos.
- À droite : panneau encadré avec la même pose en fil de fer blanc (maillage visible) sur fond sombre, les indications « ≈ tris », « ≈ verts », « 1 texture (PBR) 2048 × 2048 », et 3 vignettes de textures empilées (albedo dépliée, normal map bleue, roughness en gris).

CONTRAINTES DE COHÉRENCE (prioritaires) :
- Le même personnage, strictement identique sur la grande pose, les 5 vues, les gros plans et le fil de fer : mêmes couleurs, mêmes motifs, mêmes accessoires, du même côté du corps.
- Mêmes proportions sur les 5 vues (même hauteur totale, même taille de tête, même largeur d'épaules). Chapeau conique de paille (kasa) : même diamètre sur les 5 vues, environ 1,6 fois la largeur des épaules, même hauteur de pointe. Une vue où la coiffe, le chapeau ou l'arme change de taille rend la fiche inutilisable : c'est le défaut à éviter en priorité.
- Les 5 vues sont de vraies rotations orthographiques du même modèle (pas de perspective différente, pas de pose différente).
- Aucun texte, chiffre, flèche ni étiquette sur les 5 vues et sur les gros plans ; le texte n'apparaît que dans le bandeau, le bloc nom et le panneau fil de fer.
- Ne recopie pas la carte de la planche ni ses petites vignettes (elles sont parfois différentes du personnage) : suis la grande vue de la carte.
```

### Prompt (EN)

```text
Use the attached board (bestiary "2. FORÊT DE BAMBOU") as reference. The character is the one on the card "MOINE AU BOUCLIER" (role COMMUN, internal genre "tate").

Create its individual model sheet, a single landscape image 1536×1024, in exactly the same style and layout as the world 1 (Archipel) sheets: stylized 3D chibi figurine render, soft studio lighting, dark near-black background.

CHARACTER (follow exactly, as it appears in the large view of the board):
Chibi shield monk: same build as the peasant-monk, black hair, large beige straw conical hat. Off-white kimono, knotted green belt, short green hakama, bare feet. Big round woven-wicker shield (almost his height) marked with an X cross of two green bands, held in front on the left arm.

LAYOUT:
- Top left: slanted bamboo green banner with a small icon and the text "MONDE 2 - FORÊT DE BAMBOU". Below: small square face portrait, the name "MOINE AU BOUCLIER" in large white capitals, a role tag "COMMUN", and a line "♥ — PV".
- Left column, full height: large dynamic 3/4 pose (crouched behind his shield, on guard), in a world setting: the bamboo forest: tall green bamboo stalks, wooden temple deep in the grove, lit stone lanterns, green mist and fireflies. The setting must not hide the character.
- Top right: 5-view full-body turnaround, left to right: FRONT, 3/4 FRONT, SIDE, BACK, 3/4 BACK. Plain dark background with no scenery, each figurine standing on a thin glowing bamboo green ring on the floor. All 5 figurines complete (from the top of the head or hat down to the feet), same scale, feet on the same line, tops at the same height. Identical neutral pose in all 5 views: standing straight, arms slightly away from the body, shield held to the side on the left arm so the body stays visible.
- Centre: grid of 8 close-ups (2 columns × 4 rows) in rounded frames with a thin bamboo green border: face under the hat; woven shield with green cross; belt knot; then back of the head or headgear, shoulder and collar, hands, feet or shoes, back detail.
- Right: framed panel with the same pose as a white wireframe (visible mesh) on a dark background, the labels "≈ tris", "≈ verts", "1 texture (PBR) 2048 × 2048", and 3 stacked texture thumbnails (unwrapped albedo, blue normal map, grey roughness).

CONSISTENCY RULES (top priority):
- The same character, strictly identical in the large pose, the 5 views, the close-ups and the wireframe: same colours, same patterns, same accessories, on the same side of the body.
- Same proportions in all 5 views (same total height, same head size, same shoulder width). Conical straw hat (kasa): identical diameter in all 5 views, about 1.6x the shoulder width, same tip height. A view where the headgear, hat or weapon changes size makes the sheet unusable: this is the defect to avoid first.
- The 5 views are true orthographic rotations of the same model (no different perspective, no different pose).
- No text, numbers, arrows or labels on the 5 views or the close-ups; text only appears in the banner, the name block and the wireframe panel.
- Do not copy the board card or its small thumbnails (they sometimes differ from the character): follow the card's large view.
```

---

## ESPRIT DE L'ÉTANG : `fiches/funa.png`

Rôle : COMMUN · découpe : `decoupes/funa.png`

### Prompt (FR)

```text
Utilise la planche jointe (bestiaire « 2. FORÊT DE BAMBOU ») comme référence. Le personnage est celui de la carte « ESPRIT DE L'ÉTANG » (rôle COMMUN, genre interne « funa »).

Crée sa fiche modèle individuelle, une seule image paysage 1536×1024, dans exactement le même style et la même mise en page que les fiches du monde 1 (Archipel) : rendu 3D stylisé façon figurine chibi, éclairage doux de studio, fond sombre presque noir.

PERSONNAGE (à respecter exactement, tel qu'il apparaît sur la grande vue de la planche) :
Esprit de l'étang : petit spectre chibi à la peau gris-bleu, grands yeux bleus lumineux sans pupille, cheveux noirs, vieux chapeau conique de paille délavé gris-brun. Kimono gris pâle en lambeaux, déchiqueté aux manches et en bas, ceinture de corde brune. Il tient au bout d'une cordelette un orbe d'eau bleu lumineux (main droite) ; quelques gouttes et particules bleues flottent autour de lui. Pieds gris nus, flottant à peine au-dessus du sol.

MISE EN PAGE :
- En haut à gauche : bandeau incliné couleur vert bambou avec une petite icône et le texte « MONDE 2 - FORÊT DE BAMBOU ». Dessous : petit portrait carré du visage, le nom « ESPRIT DE L'ÉTANG » en grandes capitales blanches, une étiquette de rôle « COMMUN », et une ligne « ♥ — PV ».
- Colonne de gauche, sur toute la hauteur : grande pose 3/4 dynamique (il tend son orbe d'eau vers l'avant, lambeaux flottants), dans un décor du monde : la forêt de bambou : hautes tiges de bambou vert, temple de bois au fond de la bambouseraie, lanternes de pierre allumées, brume verte et lucioles. Le décor ne doit pas masquer le personnage.
- En haut à droite : vue tournante en 5 vues en pied, de gauche à droite : FACE, 3/4 FACE, PROFIL, DOS, 3/4 DOS. Fond sombre uni sans décor, chaque figurine posée sur un fin anneau lumineux vert bambou au sol. Les 5 figurines entières (de la pointe de la tête ou du chapeau jusqu'aux pieds), à la même échelle, pieds sur la même ligne, sommets à la même hauteur. Pose neutre identique sur les 5 vues : debout droit, bras un peu écartés du corps, orbe pendu à la main droite le long du corps.
- Au centre : grille de 8 gros plans (2 colonnes × 4 lignes) dans des cadres arrondis à bord fin vert bambou : visage aux yeux lumineux ; bas du kimono déchiqueté ; orbe d'eau bleu ; puis dos de la tête ou de la coiffe, épaule et col, mains, pieds ou chaussures, détail du dos.
- À droite : panneau encadré avec la même pose en fil de fer blanc (maillage visible) sur fond sombre, les indications « ≈ tris », « ≈ verts », « 1 texture (PBR) 2048 × 2048 », et 3 vignettes de textures empilées (albedo dépliée, normal map bleue, roughness en gris).

CONTRAINTES DE COHÉRENCE (prioritaires) :
- Le même personnage, strictement identique sur la grande pose, les 5 vues, les gros plans et le fil de fer : mêmes couleurs, mêmes motifs, mêmes accessoires, du même côté du corps.
- Mêmes proportions sur les 5 vues (même hauteur totale, même taille de tête, même largeur d'épaules). Chapeau conique de paille (kasa) : même diamètre sur les 5 vues, environ 1,6 fois la largeur des épaules, même hauteur de pointe. Une vue où la coiffe, le chapeau ou l'arme change de taille rend la fiche inutilisable : c'est le défaut à éviter en priorité.
- Les 5 vues sont de vraies rotations orthographiques du même modèle (pas de perspective différente, pas de pose différente).
- Aucun texte, chiffre, flèche ni étiquette sur les 5 vues et sur les gros plans ; le texte n'apparaît que dans le bandeau, le bloc nom et le panneau fil de fer.
- Ne recopie pas la carte de la planche ni ses petites vignettes (elles sont parfois différentes du personnage) : suis la grande vue de la carte.
```

### Prompt (EN)

```text
Use the attached board (bestiary "2. FORÊT DE BAMBOU") as reference. The character is the one on the card "ESPRIT DE L'ÉTANG" (role COMMUN, internal genre "funa").

Create its individual model sheet, a single landscape image 1536×1024, in exactly the same style and layout as the world 1 (Archipel) sheets: stylized 3D chibi figurine render, soft studio lighting, dark near-black background.

CHARACTER (follow exactly, as it appears in the large view of the board):
Pond spirit: small chibi ghost with grey-blue skin, big glowing blue pupil-less eyes, black hair, old faded grey-brown straw conical hat. Pale grey tattered kimono, shredded at the sleeves and hem, brown rope belt. He holds a glowing blue water orb on a short cord (right hand); a few blue droplets and particles float around him. Bare grey feet, barely floating above the ground.

LAYOUT:
- Top left: slanted bamboo green banner with a small icon and the text "MONDE 2 - FORÊT DE BAMBOU". Below: small square face portrait, the name "ESPRIT DE L'ÉTANG" in large white capitals, a role tag "COMMUN", and a line "♥ — PV".
- Left column, full height: large dynamic 3/4 pose (holding his water orb forward, rags floating), in a world setting: the bamboo forest: tall green bamboo stalks, wooden temple deep in the grove, lit stone lanterns, green mist and fireflies. The setting must not hide the character.
- Top right: 5-view full-body turnaround, left to right: FRONT, 3/4 FRONT, SIDE, BACK, 3/4 BACK. Plain dark background with no scenery, each figurine standing on a thin glowing bamboo green ring on the floor. All 5 figurines complete (from the top of the head or hat down to the feet), same scale, feet on the same line, tops at the same height. Identical neutral pose in all 5 views: standing straight, arms slightly away from the body, orb hanging from the right hand along the body.
- Centre: grid of 8 close-ups (2 columns × 4 rows) in rounded frames with a thin bamboo green border: face with glowing eyes; shredded kimono hem; blue water orb; then back of the head or headgear, shoulder and collar, hands, feet or shoes, back detail.
- Right: framed panel with the same pose as a white wireframe (visible mesh) on a dark background, the labels "≈ tris", "≈ verts", "1 texture (PBR) 2048 × 2048", and 3 stacked texture thumbnails (unwrapped albedo, blue normal map, grey roughness).

CONSISTENCY RULES (top priority):
- The same character, strictly identical in the large pose, the 5 views, the close-ups and the wireframe: same colours, same patterns, same accessories, on the same side of the body.
- Same proportions in all 5 views (same total height, same head size, same shoulder width). Conical straw hat (kasa): identical diameter in all 5 views, about 1.6x the shoulder width, same tip height. A view where the headgear, hat or weapon changes size makes the sheet unusable: this is the defect to avoid first.
- The 5 views are true orthographic rotations of the same model (no different perspective, no different pose).
- No text, numbers, arrows or labels on the 5 views or the close-ups; text only appears in the banner, the name block and the wireframe panel.
- Do not copy the board card or its small thumbnails (they sometimes differ from the character): follow the card's large view.
```

---

## KITSUNEBI : `fiches/kitsunebi.png`

Rôle : PROPRE AU MONDE · découpe : `decoupes/kitsunebi.png`

### Prompt (FR)

```text
Utilise la planche jointe (bestiaire « 2. FORÊT DE BAMBOU ») comme référence. Le personnage est celui de la carte « KITSUNEBI » (rôle PROPRE AU MONDE, genre interne « kitsunebi »).

Crée sa fiche modèle individuelle, une seule image paysage 1536×1024, dans exactement le même style et la même mise en page que les fiches du monde 1 (Archipel) : rendu 3D stylisé façon figurine chibi, éclairage doux de studio, fond sombre presque noir.

PERSONNAGE (à respecter exactement, tel qu'il apparaît sur la grande vue de la planche) :
Kitsunebi : renard blanc chibi à quatre pattes, fourrure blanche duveteuse, marques bleu ciel sur le front et l'intérieur des oreilles, yeux bleu glacier en amande, air rusé. Sa queue se termine en flamme bleue spectrale et trois feux follets bleus flottent autour de lui. Aucun vêtement, aucun accessoire.

MISE EN PAGE :
- En haut à gauche : bandeau incliné couleur vert bambou avec une petite icône et le texte « MONDE 2 - FORÊT DE BAMBOU ». Dessous : petit portrait carré du visage, le nom « KITSUNEBI » en grandes capitales blanches, une étiquette de rôle « PROPRE AU MONDE », et une ligne « ♥ — PV ».
- Colonne de gauche, sur toute la hauteur : grande pose 3/4 dynamique (bondissant, flammes bleues en traînée), dans un décor du monde : la forêt de bambou : hautes tiges de bambou vert, temple de bois au fond de la bambouseraie, lanternes de pierre allumées, brume verte et lucioles. Le décor ne doit pas masquer le personnage.
- En haut à droite : vue tournante en 5 vues en pied, de gauche à droite : FACE, 3/4 FACE, PROFIL, DOS, 3/4 DOS. Fond sombre uni sans décor, chaque figurine posée sur un fin anneau lumineux vert bambou au sol. Les 5 figurines entières (de la pointe de la tête ou du chapeau jusqu'aux pieds), à la même échelle, pieds sur la même ligne, sommets à la même hauteur. Pose neutre identique sur les 5 vues : debout droit, bras un peu écartés du corps, debout sur ses quatre pattes, tête droite, queue relevée.
- Au centre : grille de 8 gros plans (2 colonnes × 4 lignes) dans des cadres arrondis à bord fin vert bambou : tête et yeux bleus ; queue-flamme ; feu follet bleu ; puis dos de la tête ou de la coiffe, épaule et col, mains, pieds ou chaussures, détail du dos.
- À droite : panneau encadré avec la même pose en fil de fer blanc (maillage visible) sur fond sombre, les indications « ≈ tris », « ≈ verts », « 1 texture (PBR) 2048 × 2048 », et 3 vignettes de textures empilées (albedo dépliée, normal map bleue, roughness en gris).

CONTRAINTES DE COHÉRENCE (prioritaires) :
- Le même personnage, strictement identique sur la grande pose, les 5 vues, les gros plans et le fil de fer : mêmes couleurs, mêmes motifs, mêmes accessoires, du même côté du corps.
- Mêmes proportions sur les 5 vues (même hauteur totale, même taille de tête, même largeur d'épaules). Même longueur de queue et même nombre de feux follets (3) sur les 5 vues. Une vue où la coiffe, le chapeau ou l'arme change de taille rend la fiche inutilisable : c'est le défaut à éviter en priorité.
- Les 5 vues sont de vraies rotations orthographiques du même modèle (pas de perspective différente, pas de pose différente).
- Aucun texte, chiffre, flèche ni étiquette sur les 5 vues et sur les gros plans ; le texte n'apparaît que dans le bandeau, le bloc nom et le panneau fil de fer.
- Ne recopie pas la carte de la planche ni ses petites vignettes (elles sont parfois différentes du personnage) : suis la grande vue de la carte.
```

### Prompt (EN)

```text
Use the attached board (bestiary "2. FORÊT DE BAMBOU") as reference. The character is the one on the card "KITSUNEBI" (role PROPRE AU MONDE, internal genre "kitsunebi").

Create its individual model sheet, a single landscape image 1536×1024, in exactly the same style and layout as the world 1 (Archipel) sheets: stylized 3D chibi figurine render, soft studio lighting, dark near-black background.

CHARACTER (follow exactly, as it appears in the large view of the board):
Kitsunebi: chibi white fox on four legs, fluffy white fur, sky-blue markings on the forehead and inside the ears, almond ice-blue eyes, sly look. Its tail ends in a spectral blue flame and three blue will-o'-wisps float around it. No clothes, no accessories.

LAYOUT:
- Top left: slanted bamboo green banner with a small icon and the text "MONDE 2 - FORÊT DE BAMBOU". Below: small square face portrait, the name "KITSUNEBI" in large white capitals, a role tag "PROPRE AU MONDE", and a line "♥ — PV".
- Left column, full height: large dynamic 3/4 pose (leaping, blue flames trailing), in a world setting: the bamboo forest: tall green bamboo stalks, wooden temple deep in the grove, lit stone lanterns, green mist and fireflies. The setting must not hide the character.
- Top right: 5-view full-body turnaround, left to right: FRONT, 3/4 FRONT, SIDE, BACK, 3/4 BACK. Plain dark background with no scenery, each figurine standing on a thin glowing bamboo green ring on the floor. All 5 figurines complete (from the top of the head or hat down to the feet), same scale, feet on the same line, tops at the same height. Identical neutral pose in all 5 views: standing straight, arms slightly away from the body, standing on all four legs, head up, tail raised.
- Centre: grid of 8 close-ups (2 columns × 4 rows) in rounded frames with a thin bamboo green border: head and blue eyes; flame tail; blue will-o'-wisp; then back of the head or headgear, shoulder and collar, hands, feet or shoes, back detail.
- Right: framed panel with the same pose as a white wireframe (visible mesh) on a dark background, the labels "≈ tris", "≈ verts", "1 texture (PBR) 2048 × 2048", and 3 stacked texture thumbnails (unwrapped albedo, blue normal map, grey roughness).

CONSISTENCY RULES (top priority):
- The same character, strictly identical in the large pose, the 5 views, the close-ups and the wireframe: same colours, same patterns, same accessories, on the same side of the body.
- Same proportions in all 5 views (same total height, same head size, same shoulder width). Same tail length and same number of wisps (3) in all 5 views. A view where the headgear, hat or weapon changes size makes the sheet unusable: this is the defect to avoid first.
- The 5 views are true orthographic rotations of the same model (no different perspective, no different pose).
- No text, numbers, arrows or labels on the 5 views or the close-ups; text only appears in the banner, the name block and the wireframe panel.
- Do not copy the board card or its small thumbnails (they sometimes differ from the character): follow the card's large view.
```

---

## KAMAITACHI : `fiches/kamaitachi.png`

Rôle : PROPRE AU MONDE · découpe : `decoupes/kamaitachi.png`

### Prompt (FR)

```text
Utilise la planche jointe (bestiaire « 2. FORÊT DE BAMBOU ») comme référence. Le personnage est celui de la carte « KAMAITACHI » (rôle PROPRE AU MONDE, genre interne « kamaitachi »).

Crée sa fiche modèle individuelle, une seule image paysage 1536×1024, dans exactement le même style et la même mise en page que les fiches du monde 1 (Archipel) : rendu 3D stylisé façon figurine chibi, éclairage doux de studio, fond sombre presque noir.

PERSONNAGE (à respecter exactement, tel qu'il apparaît sur la grande vue de la planche) :
Kamaitachi : belette-chat chibi au pelage noir, yeux jaune-vert, debout sur deux pattes. Bandeau crème à motif doré noué entre ses oreilles pointues, foulard vert couvrant le bas du museau, veste noire à liseré rouge, ceinture blanche et petit tablier blanc, pantalon noir. Longue queue rayée vert et jaune enroulée en croissant. Deux faucilles : une lame courbe rouge dans la main droite, une grande lame courbe blanche dans la main gauche.

MISE EN PAGE :
- En haut à gauche : bandeau incliné couleur vert bambou avec une petite icône et le texte « MONDE 2 - FORÊT DE BAMBOU ». Dessous : petit portrait carré du visage, le nom « KAMAITACHI » en grandes capitales blanches, une étiquette de rôle « PROPRE AU MONDE », et une ligne « ♥ — PV ».
- Colonne de gauche, sur toute la hauteur : grande pose 3/4 dynamique (fente latérale, les deux faucilles déployées), dans un décor du monde : la forêt de bambou : hautes tiges de bambou vert, temple de bois au fond de la bambouseraie, lanternes de pierre allumées, brume verte et lucioles. Le décor ne doit pas masquer le personnage.
- En haut à droite : vue tournante en 5 vues en pied, de gauche à droite : FACE, 3/4 FACE, PROFIL, DOS, 3/4 DOS. Fond sombre uni sans décor, chaque figurine posée sur un fin anneau lumineux vert bambou au sol. Les 5 figurines entières (de la pointe de la tête ou du chapeau jusqu'aux pieds), à la même échelle, pieds sur la même ligne, sommets à la même hauteur. Pose neutre identique sur les 5 vues : debout droit, bras un peu écartés du corps, faucilles tenues lames vers le bas, bras écartés.
- Au centre : grille de 8 gros plans (2 colonnes × 4 lignes) dans des cadres arrondis à bord fin vert bambou : yeux et foulard vert ; lame de faucille blanche ; bandeau à motif doré ; puis dos de la tête ou de la coiffe, épaule et col, mains, pieds ou chaussures, détail du dos.
- À droite : panneau encadré avec la même pose en fil de fer blanc (maillage visible) sur fond sombre, les indications « ≈ tris », « ≈ verts », « 1 texture (PBR) 2048 × 2048 », et 3 vignettes de textures empilées (albedo dépliée, normal map bleue, roughness en gris).

CONTRAINTES DE COHÉRENCE (prioritaires) :
- Le même personnage, strictement identique sur la grande pose, les 5 vues, les gros plans et le fil de fer : mêmes couleurs, mêmes motifs, mêmes accessoires, du même côté du corps.
- Mêmes proportions sur les 5 vues (même hauteur totale, même taille de tête, même largeur d'épaules). Mêmes oreilles et même queue en croissant sur les 5 vues. Une vue où la coiffe, le chapeau ou l'arme change de taille rend la fiche inutilisable : c'est le défaut à éviter en priorité.
- Les 5 vues sont de vraies rotations orthographiques du même modèle (pas de perspective différente, pas de pose différente).
- Aucun texte, chiffre, flèche ni étiquette sur les 5 vues et sur les gros plans ; le texte n'apparaît que dans le bandeau, le bloc nom et le panneau fil de fer.
- Ne recopie pas la carte de la planche ni ses petites vignettes (elles sont parfois différentes du personnage) : suis la grande vue de la carte.
```

### Prompt (EN)

```text
Use the attached board (bestiary "2. FORÊT DE BAMBOU") as reference. The character is the one on the card "KAMAITACHI" (role PROPRE AU MONDE, internal genre "kamaitachi").

Create its individual model sheet, a single landscape image 1536×1024, in exactly the same style and layout as the world 1 (Archipel) sheets: stylized 3D chibi figurine render, soft studio lighting, dark near-black background.

CHARACTER (follow exactly, as it appears in the large view of the board):
Kamaitachi: chibi weasel-cat with black fur, yellow-green eyes, standing on two legs. Cream headband with gold pattern tied between its pointed ears, green scarf covering the lower muzzle, black jacket with red trim, white belt and small white apron, black trousers. Long green-and-yellow striped tail curled like a crescent. Two sickles: a curved red blade in the right hand, a large curved white blade in the left hand.

LAYOUT:
- Top left: slanted bamboo green banner with a small icon and the text "MONDE 2 - FORÊT DE BAMBOU". Below: small square face portrait, the name "KAMAITACHI" in large white capitals, a role tag "PROPRE AU MONDE", and a line "♥ — PV".
- Left column, full height: large dynamic 3/4 pose (side slash, both sickles spread), in a world setting: the bamboo forest: tall green bamboo stalks, wooden temple deep in the grove, lit stone lanterns, green mist and fireflies. The setting must not hide the character.
- Top right: 5-view full-body turnaround, left to right: FRONT, 3/4 FRONT, SIDE, BACK, 3/4 BACK. Plain dark background with no scenery, each figurine standing on a thin glowing bamboo green ring on the floor. All 5 figurines complete (from the top of the head or hat down to the feet), same scale, feet on the same line, tops at the same height. Identical neutral pose in all 5 views: standing straight, arms slightly away from the body, sickles held blades down, arms apart.
- Centre: grid of 8 close-ups (2 columns × 4 rows) in rounded frames with a thin bamboo green border: eyes and green scarf; white sickle blade; gold-patterned headband; then back of the head or headgear, shoulder and collar, hands, feet or shoes, back detail.
- Right: framed panel with the same pose as a white wireframe (visible mesh) on a dark background, the labels "≈ tris", "≈ verts", "1 texture (PBR) 2048 × 2048", and 3 stacked texture thumbnails (unwrapped albedo, blue normal map, grey roughness).

CONSISTENCY RULES (top priority):
- The same character, strictly identical in the large pose, the 5 views, the close-ups and the wireframe: same colours, same patterns, same accessories, on the same side of the body.
- Same proportions in all 5 views (same total height, same head size, same shoulder width). Same ears and same crescent tail in all 5 views. A view where the headgear, hat or weapon changes size makes the sheet unusable: this is the defect to avoid first.
- The 5 views are true orthographic rotations of the same model (no different perspective, no different pose).
- No text, numbers, arrows or labels on the 5 views or the close-ups; text only appears in the banner, the name block and the wireframe panel.
- Do not copy the board card or its small thumbnails (they sometimes differ from the character): follow the card's large view.
```

---

## MOINE TANUKI : `fiches/tanuki.png`

Rôle : PROPRE AU MONDE · découpe : `decoupes/tanuki.png`

### Prompt (FR)

```text
Utilise la planche jointe (bestiaire « 2. FORÊT DE BAMBOU ») comme référence. Le personnage est celui de la carte « MOINE TANUKI » (rôle PROPRE AU MONDE, genre interne « tanuki »).

Crée sa fiche modèle individuelle, une seule image paysage 1536×1024, dans exactement le même style et la même mise en page que les fiches du monde 1 (Archipel) : rendu 3D stylisé façon figurine chibi, éclairage doux de studio, fond sombre presque noir.

PERSONNAGE (à respecter exactement, tel qu'il apparaît sur la grande vue de la planche) :
Moine tanuki : tanuki chibi rondouillard au pelage brun, gros ventre crème, masque sombre autour des yeux, petites oreilles. Grand chapeau conique de paille beige. Robe de moine brune ample, étole jaune-vert à motifs portée en bandoulière. Grosse gourde-calebasse brune tenue dans la main droite. Une feuille verte (feuille de métamorphose) glissée à la taille.

MISE EN PAGE :
- En haut à gauche : bandeau incliné couleur vert bambou avec une petite icône et le texte « MONDE 2 - FORÊT DE BAMBOU ». Dessous : petit portrait carré du visage, le nom « MOINE TANUKI » en grandes capitales blanches, une étiquette de rôle « PROPRE AU MONDE », et une ligne « ♥ — PV ».
- Colonne de gauche, sur toute la hauteur : grande pose 3/4 dynamique (il brandit sa gourde, ventre en avant), dans un décor du monde : la forêt de bambou : hautes tiges de bambou vert, temple de bois au fond de la bambouseraie, lanternes de pierre allumées, brume verte et lucioles. Le décor ne doit pas masquer le personnage.
- En haut à droite : vue tournante en 5 vues en pied, de gauche à droite : FACE, 3/4 FACE, PROFIL, DOS, 3/4 DOS. Fond sombre uni sans décor, chaque figurine posée sur un fin anneau lumineux vert bambou au sol. Les 5 figurines entières (de la pointe de la tête ou du chapeau jusqu'aux pieds), à la même échelle, pieds sur la même ligne, sommets à la même hauteur. Pose neutre identique sur les 5 vues : debout droit, bras un peu écartés du corps, gourde pendue à la main droite.
- Au centre : grille de 8 gros plans (2 colonnes × 4 lignes) dans des cadres arrondis à bord fin vert bambou : visage du tanuki ; gourde-calebasse ; feuille verte ; puis dos de la tête ou de la coiffe, épaule et col, mains, pieds ou chaussures, détail du dos.
- À droite : panneau encadré avec la même pose en fil de fer blanc (maillage visible) sur fond sombre, les indications « ≈ tris », « ≈ verts », « 1 texture (PBR) 2048 × 2048 », et 3 vignettes de textures empilées (albedo dépliée, normal map bleue, roughness en gris).

CONTRAINTES DE COHÉRENCE (prioritaires) :
- Le même personnage, strictement identique sur la grande pose, les 5 vues, les gros plans et le fil de fer : mêmes couleurs, mêmes motifs, mêmes accessoires, du même côté du corps.
- Mêmes proportions sur les 5 vues (même hauteur totale, même taille de tête, même largeur d'épaules). Chapeau conique de paille (kasa) : même diamètre sur les 5 vues, environ 1,6 fois la largeur des épaules, même hauteur de pointe. Une vue où la coiffe, le chapeau ou l'arme change de taille rend la fiche inutilisable : c'est le défaut à éviter en priorité.
- Les 5 vues sont de vraies rotations orthographiques du même modèle (pas de perspective différente, pas de pose différente).
- Aucun texte, chiffre, flèche ni étiquette sur les 5 vues et sur les gros plans ; le texte n'apparaît que dans le bandeau, le bloc nom et le panneau fil de fer.
- Ne recopie pas la carte de la planche ni ses petites vignettes (elles sont parfois différentes du personnage) : suis la grande vue de la carte.
```

### Prompt (EN)

```text
Use the attached board (bestiary "2. FORÊT DE BAMBOU") as reference. The character is the one on the card "MOINE TANUKI" (role PROPRE AU MONDE, internal genre "tanuki").

Create its individual model sheet, a single landscape image 1536×1024, in exactly the same style and layout as the world 1 (Archipel) sheets: stylized 3D chibi figurine render, soft studio lighting, dark near-black background.

CHARACTER (follow exactly, as it appears in the large view of the board):
Tanuki monk: chubby chibi tanuki with brown fur, big cream belly, dark mask around the eyes, small ears. Large beige straw conical hat. Loose brown monk robe, patterned yellow-green stole worn across the chest. Big brown gourd held in the right hand. A green leaf (transformation leaf) tucked at the waist.

LAYOUT:
- Top left: slanted bamboo green banner with a small icon and the text "MONDE 2 - FORÊT DE BAMBOU". Below: small square face portrait, the name "MOINE TANUKI" in large white capitals, a role tag "PROPRE AU MONDE", and a line "♥ — PV".
- Left column, full height: large dynamic 3/4 pose (raising his gourd, belly forward), in a world setting: the bamboo forest: tall green bamboo stalks, wooden temple deep in the grove, lit stone lanterns, green mist and fireflies. The setting must not hide the character.
- Top right: 5-view full-body turnaround, left to right: FRONT, 3/4 FRONT, SIDE, BACK, 3/4 BACK. Plain dark background with no scenery, each figurine standing on a thin glowing bamboo green ring on the floor. All 5 figurines complete (from the top of the head or hat down to the feet), same scale, feet on the same line, tops at the same height. Identical neutral pose in all 5 views: standing straight, arms slightly away from the body, gourd hanging from the right hand.
- Centre: grid of 8 close-ups (2 columns × 4 rows) in rounded frames with a thin bamboo green border: tanuki face; gourd; green leaf; then back of the head or headgear, shoulder and collar, hands, feet or shoes, back detail.
- Right: framed panel with the same pose as a white wireframe (visible mesh) on a dark background, the labels "≈ tris", "≈ verts", "1 texture (PBR) 2048 × 2048", and 3 stacked texture thumbnails (unwrapped albedo, blue normal map, grey roughness).

CONSISTENCY RULES (top priority):
- The same character, strictly identical in the large pose, the 5 views, the close-ups and the wireframe: same colours, same patterns, same accessories, on the same side of the body.
- Same proportions in all 5 views (same total height, same head size, same shoulder width). Conical straw hat (kasa): identical diameter in all 5 views, about 1.6x the shoulder width, same tip height. A view where the headgear, hat or weapon changes size makes the sheet unusable: this is the defect to avoid first.
- The 5 views are true orthographic rotations of the same model (no different perspective, no different pose).
- No text, numbers, arrows or labels on the 5 views or the close-ups; text only appears in the banner, the name block and the wireframe panel.
- Do not copy the board card or its small thumbnails (they sometimes differ from the character): follow the card's large view.
```

---

## MAÎTRE DES RENARDS : `fiches/kitsune_tsukai.png`

Rôle : PROPRE AU MONDE · découpe : `decoupes/kitsune_tsukai.png`

### Prompt (FR)

```text
Utilise la planche jointe (bestiaire « 2. FORÊT DE BAMBOU ») comme référence. Le personnage est celui de la carte « MAÎTRE DES RENARDS » (rôle PROPRE AU MONDE, genre interne « kitsune_tsukai »).

Crée sa fiche modèle individuelle, une seule image paysage 1536×1024, dans exactement le même style et la même mise en page que les fiches du monde 1 (Archipel) : rendu 3D stylisé façon figurine chibi, éclairage doux de studio, fond sombre presque noir.

PERSONNAGE (à respecter exactement, tel qu'il apparaît sur la grande vue de la planche) :
Maître des renards : homme-renard chibi au pelage blanc, oreilles pointues à bout noir, masque de kitsune blanc aux marques rouges et aux yeux rouges en amande. Kimono blanc à très longues manches ornées de motifs rouges, hakama noir, large ceinture tressée rouge-orangé avec cordons et pompons. Bâton de bois surmonté d'une boule de cristal bleu lumineux dans une monture dorée, tenu dans la main droite.

MISE EN PAGE :
- En haut à gauche : bandeau incliné couleur vert bambou avec une petite icône et le texte « MONDE 2 - FORÊT DE BAMBOU ». Dessous : petit portrait carré du visage, le nom « MAÎTRE DES RENARDS » en grandes capitales blanches, une étiquette de rôle « PROPRE AU MONDE », et une ligne « ♥ — PV ».
- Colonne de gauche, sur toute la hauteur : grande pose 3/4 dynamique (il lève son bâton, l'orbe bleu illuminant la scène), dans un décor du monde : la forêt de bambou : hautes tiges de bambou vert, temple de bois au fond de la bambouseraie, lanternes de pierre allumées, brume verte et lucioles. Le décor ne doit pas masquer le personnage.
- En haut à droite : vue tournante en 5 vues en pied, de gauche à droite : FACE, 3/4 FACE, PROFIL, DOS, 3/4 DOS. Fond sombre uni sans décor, chaque figurine posée sur un fin anneau lumineux vert bambou au sol. Les 5 figurines entières (de la pointe de la tête ou du chapeau jusqu'aux pieds), à la même échelle, pieds sur la même ligne, sommets à la même hauteur. Pose neutre identique sur les 5 vues : debout droit, bras un peu écartés du corps, bâton vertical dans la main droite, orbe au-dessus de la tête.
- Au centre : grille de 8 gros plans (2 colonnes × 4 lignes) dans des cadres arrondis à bord fin vert bambou : masque aux yeux rouges ; orbe de cristal bleu ; ceinture tressée à pompons ; puis dos de la tête ou de la coiffe, épaule et col, mains, pieds ou chaussures, détail du dos.
- À droite : panneau encadré avec la même pose en fil de fer blanc (maillage visible) sur fond sombre, les indications « ≈ tris », « ≈ verts », « 1 texture (PBR) 2048 × 2048 », et 3 vignettes de textures empilées (albedo dépliée, normal map bleue, roughness en gris).

CONTRAINTES DE COHÉRENCE (prioritaires) :
- Le même personnage, strictement identique sur la grande pose, les 5 vues, les gros plans et le fil de fer : mêmes couleurs, mêmes motifs, mêmes accessoires, du même côté du corps.
- Mêmes proportions sur les 5 vues (même hauteur totale, même taille de tête, même largeur d'épaules). Mêmes oreilles et même hauteur de bâton sur les 5 vues. Une vue où la coiffe, le chapeau ou l'arme change de taille rend la fiche inutilisable : c'est le défaut à éviter en priorité.
- Les 5 vues sont de vraies rotations orthographiques du même modèle (pas de perspective différente, pas de pose différente).
- Aucun texte, chiffre, flèche ni étiquette sur les 5 vues et sur les gros plans ; le texte n'apparaît que dans le bandeau, le bloc nom et le panneau fil de fer.
- Ne recopie pas la carte de la planche ni ses petites vignettes (elles sont parfois différentes du personnage) : suis la grande vue de la carte.
```

### Prompt (EN)

```text
Use the attached board (bestiary "2. FORÊT DE BAMBOU") as reference. The character is the one on the card "MAÎTRE DES RENARDS" (role PROPRE AU MONDE, internal genre "kitsune_tsukai").

Create its individual model sheet, a single landscape image 1536×1024, in exactly the same style and layout as the world 1 (Archipel) sheets: stylized 3D chibi figurine render, soft studio lighting, dark near-black background.

CHARACTER (follow exactly, as it appears in the large view of the board):
Fox master: chibi fox-man with white fur, pointed black-tipped ears, white kitsune mask with red markings and red almond eyes. White kimono with very long sleeves decorated with red patterns, black hakama, wide red-orange braided belt with cords and tassels. Wooden staff topped with a glowing blue crystal ball in a gold mount, held in the right hand.

LAYOUT:
- Top left: slanted bamboo green banner with a small icon and the text "MONDE 2 - FORÊT DE BAMBOU". Below: small square face portrait, the name "MAÎTRE DES RENARDS" in large white capitals, a role tag "PROPRE AU MONDE", and a line "♥ — PV".
- Left column, full height: large dynamic 3/4 pose (raising his staff, the blue orb lighting the scene), in a world setting: the bamboo forest: tall green bamboo stalks, wooden temple deep in the grove, lit stone lanterns, green mist and fireflies. The setting must not hide the character.
- Top right: 5-view full-body turnaround, left to right: FRONT, 3/4 FRONT, SIDE, BACK, 3/4 BACK. Plain dark background with no scenery, each figurine standing on a thin glowing bamboo green ring on the floor. All 5 figurines complete (from the top of the head or hat down to the feet), same scale, feet on the same line, tops at the same height. Identical neutral pose in all 5 views: standing straight, arms slightly away from the body, staff vertical in the right hand, orb above the head.
- Centre: grid of 8 close-ups (2 columns × 4 rows) in rounded frames with a thin bamboo green border: mask with red eyes; blue crystal orb; braided belt with tassels; then back of the head or headgear, shoulder and collar, hands, feet or shoes, back detail.
- Right: framed panel with the same pose as a white wireframe (visible mesh) on a dark background, the labels "≈ tris", "≈ verts", "1 texture (PBR) 2048 × 2048", and 3 stacked texture thumbnails (unwrapped albedo, blue normal map, grey roughness).

CONSISTENCY RULES (top priority):
- The same character, strictly identical in the large pose, the 5 views, the close-ups and the wireframe: same colours, same patterns, same accessories, on the same side of the body.
- Same proportions in all 5 views (same total height, same head size, same shoulder width). Same ears and same staff height in all 5 views. A view where the headgear, hat or weapon changes size makes the sheet unusable: this is the defect to avoid first.
- The 5 views are true orthographic rotations of the same model (no different perspective, no different pose).
- No text, numbers, arrows or labels on the 5 views or the close-ups; text only appears in the banner, the name block and the wireframe panel.
- Do not copy the board card or its small thumbnails (they sometimes differ from the character): follow the card's large view.
```

---

## MOINE ARCHER : `fiches/kappa_yumi.png`

Rôle : REVENANT · découpe : `decoupes/kappa_yumi.png`

### Prompt (FR)

```text
Utilise la planche jointe (bestiaire « 2. FORÊT DE BAMBOU ») comme référence. Le personnage est celui de la carte « MOINE ARCHER » (rôle REVENANT, genre interne « kappa_yumi », vient de : Archipel).

Crée sa fiche modèle individuelle, une seule image paysage 1536×1024, dans exactement le même style et la même mise en page que les fiches du monde 1 (Archipel) : rendu 3D stylisé façon figurine chibi, éclairage doux de studio, fond sombre presque noir.

PERSONNAGE (à respecter exactement, tel qu'il apparaît sur la grande vue de la planche) :
Moine archer : même gabarit que le paysan-moine, cheveux noirs, regard concentré, grand chapeau conique de paille beige. Kimono écru à col vert, ceinture brune, hakama court vert, pieds nus. Grand arc (yumi) en bois brun à poignée dorée dans la main gauche, carquois en bois rempli de flèches empennées dans le dos.

MISE EN PAGE :
- En haut à gauche : bandeau incliné couleur vert bambou avec une petite icône et le texte « MONDE 2 - FORÊT DE BAMBOU ». Dessous : petit portrait carré du visage, le nom « MOINE ARCHER » en grandes capitales blanches, une étiquette de rôle « REVENANT », et une ligne « ♥ — PV ».
- Colonne de gauche, sur toute la hauteur : grande pose 3/4 dynamique (arc bandé, flèche encochée, visant de côté), dans un décor du monde : la forêt de bambou : hautes tiges de bambou vert, temple de bois au fond de la bambouseraie, lanternes de pierre allumées, brume verte et lucioles. Le décor ne doit pas masquer le personnage.
- En haut à droite : vue tournante en 5 vues en pied, de gauche à droite : FACE, 3/4 FACE, PROFIL, DOS, 3/4 DOS. Fond sombre uni sans décor, chaque figurine posée sur un fin anneau lumineux vert bambou au sol. Les 5 figurines entières (de la pointe de la tête ou du chapeau jusqu'aux pieds), à la même échelle, pieds sur la même ligne, sommets à la même hauteur. Pose neutre identique sur les 5 vues : debout droit, bras un peu écartés du corps, arc tenu verticalement dans la main gauche.
- Au centre : grille de 8 gros plans (2 colonnes × 4 lignes) dans des cadres arrondis à bord fin vert bambou : visage sous le chapeau ; arc brun ; flèches empennées du carquois ; puis dos de la tête ou de la coiffe, épaule et col, mains, pieds ou chaussures, détail du dos.
- À droite : panneau encadré avec la même pose en fil de fer blanc (maillage visible) sur fond sombre, les indications « ≈ tris », « ≈ verts », « 1 texture (PBR) 2048 × 2048 », et 3 vignettes de textures empilées (albedo dépliée, normal map bleue, roughness en gris).

CONTRAINTES DE COHÉRENCE (prioritaires) :
- Le même personnage, strictement identique sur la grande pose, les 5 vues, les gros plans et le fil de fer : mêmes couleurs, mêmes motifs, mêmes accessoires, du même côté du corps.
- Mêmes proportions sur les 5 vues (même hauteur totale, même taille de tête, même largeur d'épaules). Chapeau conique de paille (kasa) : même diamètre sur les 5 vues, environ 1,6 fois la largeur des épaules, même hauteur de pointe. Une vue où la coiffe, le chapeau ou l'arme change de taille rend la fiche inutilisable : c'est le défaut à éviter en priorité.
- Les 5 vues sont de vraies rotations orthographiques du même modèle (pas de perspective différente, pas de pose différente).
- Aucun texte, chiffre, flèche ni étiquette sur les 5 vues et sur les gros plans ; le texte n'apparaît que dans le bandeau, le bloc nom et le panneau fil de fer.
- Ne recopie pas la carte de la planche ni ses petites vignettes (elles sont parfois différentes du personnage) : suis la grande vue de la carte.
```

### Prompt (EN)

```text
Use the attached board (bestiary "2. FORÊT DE BAMBOU") as reference. The character is the one on the card "MOINE ARCHER" (role REVENANT, internal genre "kappa_yumi").

Create its individual model sheet, a single landscape image 1536×1024, in exactly the same style and layout as the world 1 (Archipel) sheets: stylized 3D chibi figurine render, soft studio lighting, dark near-black background.

CHARACTER (follow exactly, as it appears in the large view of the board):
Archer monk: same build as the peasant-monk, black hair, focused look, large beige straw conical hat. Off-white kimono with green collar, brown belt, short green hakama, bare feet. Large brown wooden bow (yumi) with a gold grip in the left hand, wooden quiver full of fletched arrows on the back.

LAYOUT:
- Top left: slanted bamboo green banner with a small icon and the text "MONDE 2 - FORÊT DE BAMBOU". Below: small square face portrait, the name "MOINE ARCHER" in large white capitals, a role tag "REVENANT", and a line "♥ — PV".
- Left column, full height: large dynamic 3/4 pose (bow drawn, arrow nocked, aiming sideways), in a world setting: the bamboo forest: tall green bamboo stalks, wooden temple deep in the grove, lit stone lanterns, green mist and fireflies. The setting must not hide the character.
- Top right: 5-view full-body turnaround, left to right: FRONT, 3/4 FRONT, SIDE, BACK, 3/4 BACK. Plain dark background with no scenery, each figurine standing on a thin glowing bamboo green ring on the floor. All 5 figurines complete (from the top of the head or hat down to the feet), same scale, feet on the same line, tops at the same height. Identical neutral pose in all 5 views: standing straight, arms slightly away from the body, bow held vertically in the left hand.
- Centre: grid of 8 close-ups (2 columns × 4 rows) in rounded frames with a thin bamboo green border: face under the hat; brown bow; fletched arrows in the quiver; then back of the head or headgear, shoulder and collar, hands, feet or shoes, back detail.
- Right: framed panel with the same pose as a white wireframe (visible mesh) on a dark background, the labels "≈ tris", "≈ verts", "1 texture (PBR) 2048 × 2048", and 3 stacked texture thumbnails (unwrapped albedo, blue normal map, grey roughness).

CONSISTENCY RULES (top priority):
- The same character, strictly identical in the large pose, the 5 views, the close-ups and the wireframe: same colours, same patterns, same accessories, on the same side of the body.
- Same proportions in all 5 views (same total height, same head size, same shoulder width). Conical straw hat (kasa): identical diameter in all 5 views, about 1.6x the shoulder width, same tip height. A view where the headgear, hat or weapon changes size makes the sheet unusable: this is the defect to avoid first.
- The 5 views are true orthographic rotations of the same model (no different perspective, no different pose).
- No text, numbers, arrows or labels on the 5 views or the close-ups; text only appears in the banner, the name block and the wireframe panel.
- Do not copy the board card or its small thumbnails (they sometimes differ from the character): follow the card's large view.
```

---

## SHINOBI : `fiches/shinobi.png`

Rôle : PROPRE AU MONDE · découpe : `decoupes/shinobi.png`

### Prompt (FR)

```text
Utilise la planche jointe (bestiaire « 2. FORÊT DE BAMBOU ») comme référence. Le personnage est celui de la carte « SHINOBI » (rôle PROPRE AU MONDE, genre interne « shinobi »).

Crée sa fiche modèle individuelle, une seule image paysage 1536×1024, dans exactement le même style et la même mise en page que les fiches du monde 1 (Archipel) : rendu 3D stylisé façon figurine chibi, éclairage doux de studio, fond sombre presque noir.

PERSONNAGE (à respecter exactement, tel qu'il apparaît sur la grande vue de la planche) :
Shinobi : ninja chibi en tenue vert forêt, capuche verte en bonnet et masque vert-noir couvrant le bas du visage, yeux ambre. Longue écharpe verte aux extrémités brodées d'or qui flotte, gantelets noirs, sangle brune en travers du torse, pantalon vert, sandales. Dague (kunai) à lame d'acier dans la main droite.

MISE EN PAGE :
- En haut à gauche : bandeau incliné couleur vert bambou avec une petite icône et le texte « MONDE 2 - FORÊT DE BAMBOU ». Dessous : petit portrait carré du visage, le nom « SHINOBI » en grandes capitales blanches, une étiquette de rôle « PROPRE AU MONDE », et une ligne « ♥ — PV ».
- Colonne de gauche, sur toute la hauteur : grande pose 3/4 dynamique (fente basse vers l'avant, écharpe au vent), dans un décor du monde : la forêt de bambou : hautes tiges de bambou vert, temple de bois au fond de la bambouseraie, lanternes de pierre allumées, brume verte et lucioles. Le décor ne doit pas masquer le personnage.
- En haut à droite : vue tournante en 5 vues en pied, de gauche à droite : FACE, 3/4 FACE, PROFIL, DOS, 3/4 DOS. Fond sombre uni sans décor, chaque figurine posée sur un fin anneau lumineux vert bambou au sol. Les 5 figurines entières (de la pointe de la tête ou du chapeau jusqu'aux pieds), à la même échelle, pieds sur la même ligne, sommets à la même hauteur. Pose neutre identique sur les 5 vues : debout droit, bras un peu écartés du corps, dague tenue lame vers le bas, main droite.
- Au centre : grille de 8 gros plans (2 colonnes × 4 lignes) dans des cadres arrondis à bord fin vert bambou : visage masqué ; shuriken d'acier à 4 branches ; corde enroulée à la ceinture ; puis dos de la tête ou de la coiffe, épaule et col, mains, pieds ou chaussures, détail du dos.
- À droite : panneau encadré avec la même pose en fil de fer blanc (maillage visible) sur fond sombre, les indications « ≈ tris », « ≈ verts », « 1 texture (PBR) 2048 × 2048 », et 3 vignettes de textures empilées (albedo dépliée, normal map bleue, roughness en gris).

CONTRAINTES DE COHÉRENCE (prioritaires) :
- Le même personnage, strictement identique sur la grande pose, les 5 vues, les gros plans et le fil de fer : mêmes couleurs, mêmes motifs, mêmes accessoires, du même côté du corps.
- Mêmes proportions sur les 5 vues (même hauteur totale, même taille de tête, même largeur d'épaules). Même capuche et même longueur d'écharpe sur les 5 vues. Une vue où la coiffe, le chapeau ou l'arme change de taille rend la fiche inutilisable : c'est le défaut à éviter en priorité.
- Les 5 vues sont de vraies rotations orthographiques du même modèle (pas de perspective différente, pas de pose différente).
- Aucun texte, chiffre, flèche ni étiquette sur les 5 vues et sur les gros plans ; le texte n'apparaît que dans le bandeau, le bloc nom et le panneau fil de fer.
- Ne recopie pas la carte de la planche ni ses petites vignettes (elles sont parfois différentes du personnage) : suis la grande vue de la carte.
```

### Prompt (EN)

```text
Use the attached board (bestiary "2. FORÊT DE BAMBOU") as reference. The character is the one on the card "SHINOBI" (role PROPRE AU MONDE, internal genre "shinobi").

Create its individual model sheet, a single landscape image 1536×1024, in exactly the same style and layout as the world 1 (Archipel) sheets: stylized 3D chibi figurine render, soft studio lighting, dark near-black background.

CHARACTER (follow exactly, as it appears in the large view of the board):
Shinobi: chibi ninja in a forest-green outfit, green beanie-style hood and green-black mask over the lower face, amber eyes. Long green scarf with gold-embroidered ends floating, black gauntlets, brown strap across the chest, green trousers, sandals. Steel kunai dagger in the right hand.

LAYOUT:
- Top left: slanted bamboo green banner with a small icon and the text "MONDE 2 - FORÊT DE BAMBOU". Below: small square face portrait, the name "SHINOBI" in large white capitals, a role tag "PROPRE AU MONDE", and a line "♥ — PV".
- Left column, full height: large dynamic 3/4 pose (low lunge forward, scarf flying), in a world setting: the bamboo forest: tall green bamboo stalks, wooden temple deep in the grove, lit stone lanterns, green mist and fireflies. The setting must not hide the character.
- Top right: 5-view full-body turnaround, left to right: FRONT, 3/4 FRONT, SIDE, BACK, 3/4 BACK. Plain dark background with no scenery, each figurine standing on a thin glowing bamboo green ring on the floor. All 5 figurines complete (from the top of the head or hat down to the feet), same scale, feet on the same line, tops at the same height. Identical neutral pose in all 5 views: standing straight, arms slightly away from the body, dagger held blade down, right hand.
- Centre: grid of 8 close-ups (2 columns × 4 rows) in rounded frames with a thin bamboo green border: masked face; four-pointed steel shuriken; coiled rope at the belt; then back of the head or headgear, shoulder and collar, hands, feet or shoes, back detail.
- Right: framed panel with the same pose as a white wireframe (visible mesh) on a dark background, the labels "≈ tris", "≈ verts", "1 texture (PBR) 2048 × 2048", and 3 stacked texture thumbnails (unwrapped albedo, blue normal map, grey roughness).

CONSISTENCY RULES (top priority):
- The same character, strictly identical in the large pose, the 5 views, the close-ups and the wireframe: same colours, same patterns, same accessories, on the same side of the body.
- Same proportions in all 5 views (same total height, same head size, same shoulder width). Same hood and same scarf length in all 5 views. A view where the headgear, hat or weapon changes size makes the sheet unusable: this is the defect to avoid first.
- The 5 views are true orthographic rotations of the same model (no different perspective, no different pose).
- No text, numbers, arrows or labels on the 5 views or the close-ups; text only appears in the banner, the name block and the wireframe panel.
- Do not copy the board card or its small thumbnails (they sometimes differ from the character): follow the card's large view.
```

---

## LANCEUR DE SHURIKEN : `fiches/shuriken.png`

Rôle : PROPRE AU MONDE · découpe : `decoupes/shuriken.png`

### Prompt (FR)

```text
Utilise la planche jointe (bestiaire « 2. FORÊT DE BAMBOU ») comme référence. Le personnage est celui de la carte « LANCEUR DE SHURIKEN » (rôle PROPRE AU MONDE, genre interne « shuriken »).

Crée sa fiche modèle individuelle, une seule image paysage 1536×1024, dans exactement le même style et la même mise en page que les fiches du monde 1 (Archipel) : rendu 3D stylisé façon figurine chibi, éclairage doux de studio, fond sombre presque noir.

PERSONNAGE (à respecter exactement, tel qu'il apparaît sur la grande vue de la planche) :
Lanceur de shuriken : ninja chibi aux cheveux noirs, chapeau conique de paille brun-rosé, masque vert sur le bas du visage, sourcils froncés. Tenue verte, écharpe verte à bouts dorés, sangle et sacoche brunes à la ceinture, sandales. Shuriken à quatre branches (et un kunai) dans la main droite.

MISE EN PAGE :
- En haut à gauche : bandeau incliné couleur vert bambou avec une petite icône et le texte « MONDE 2 - FORÊT DE BAMBOU ». Dessous : petit portrait carré du visage, le nom « LANCEUR DE SHURIKEN » en grandes capitales blanches, une étiquette de rôle « PROPRE AU MONDE », et une ligne « ♥ — PV ».
- Colonne de gauche, sur toute la hauteur : grande pose 3/4 dynamique (geste de lancer, shuriken quittant la main), dans un décor du monde : la forêt de bambou : hautes tiges de bambou vert, temple de bois au fond de la bambouseraie, lanternes de pierre allumées, brume verte et lucioles. Le décor ne doit pas masquer le personnage.
- En haut à droite : vue tournante en 5 vues en pied, de gauche à droite : FACE, 3/4 FACE, PROFIL, DOS, 3/4 DOS. Fond sombre uni sans décor, chaque figurine posée sur un fin anneau lumineux vert bambou au sol. Les 5 figurines entières (de la pointe de la tête ou du chapeau jusqu'aux pieds), à la même échelle, pieds sur la même ligne, sommets à la même hauteur. Pose neutre identique sur les 5 vues : debout droit, bras un peu écartés du corps, shuriken tenu à hauteur de hanche, main droite.
- Au centre : grille de 8 gros plans (2 colonnes × 4 lignes) dans des cadres arrondis à bord fin vert bambou : visage masqué sous le chapeau ; shuriken à 4 branches ; sacoche de ceinture ; puis dos de la tête ou de la coiffe, épaule et col, mains, pieds ou chaussures, détail du dos.
- À droite : panneau encadré avec la même pose en fil de fer blanc (maillage visible) sur fond sombre, les indications « ≈ tris », « ≈ verts », « 1 texture (PBR) 2048 × 2048 », et 3 vignettes de textures empilées (albedo dépliée, normal map bleue, roughness en gris).

CONTRAINTES DE COHÉRENCE (prioritaires) :
- Le même personnage, strictement identique sur la grande pose, les 5 vues, les gros plans et le fil de fer : mêmes couleurs, mêmes motifs, mêmes accessoires, du même côté du corps.
- Mêmes proportions sur les 5 vues (même hauteur totale, même taille de tête, même largeur d'épaules). Chapeau conique de paille (kasa) : même diamètre sur les 5 vues, environ 1,6 fois la largeur des épaules, même hauteur de pointe. Une vue où la coiffe, le chapeau ou l'arme change de taille rend la fiche inutilisable : c'est le défaut à éviter en priorité.
- Les 5 vues sont de vraies rotations orthographiques du même modèle (pas de perspective différente, pas de pose différente).
- Aucun texte, chiffre, flèche ni étiquette sur les 5 vues et sur les gros plans ; le texte n'apparaît que dans le bandeau, le bloc nom et le panneau fil de fer.
- Ne recopie pas la carte de la planche ni ses petites vignettes (elles sont parfois différentes du personnage) : suis la grande vue de la carte.
```

### Prompt (EN)

```text
Use the attached board (bestiary "2. FORÊT DE BAMBOU") as reference. The character is the one on the card "LANCEUR DE SHURIKEN" (role PROPRE AU MONDE, internal genre "shuriken").

Create its individual model sheet, a single landscape image 1536×1024, in exactly the same style and layout as the world 1 (Archipel) sheets: stylized 3D chibi figurine render, soft studio lighting, dark near-black background.

CHARACTER (follow exactly, as it appears in the large view of the board):
Shuriken thrower: chibi ninja with black hair, pinkish-brown straw conical hat, green mask over the lower face, frowning brows. Green outfit, green scarf with gold ends, brown strap and pouch at the belt, sandals. Four-pointed shuriken (and a kunai) in the right hand.

LAYOUT:
- Top left: slanted bamboo green banner with a small icon and the text "MONDE 2 - FORÊT DE BAMBOU". Below: small square face portrait, the name "LANCEUR DE SHURIKEN" in large white capitals, a role tag "PROPRE AU MONDE", and a line "♥ — PV".
- Left column, full height: large dynamic 3/4 pose (throwing motion, shuriken leaving the hand), in a world setting: the bamboo forest: tall green bamboo stalks, wooden temple deep in the grove, lit stone lanterns, green mist and fireflies. The setting must not hide the character.
- Top right: 5-view full-body turnaround, left to right: FRONT, 3/4 FRONT, SIDE, BACK, 3/4 BACK. Plain dark background with no scenery, each figurine standing on a thin glowing bamboo green ring on the floor. All 5 figurines complete (from the top of the head or hat down to the feet), same scale, feet on the same line, tops at the same height. Identical neutral pose in all 5 views: standing straight, arms slightly away from the body, shuriken held at hip height, right hand.
- Centre: grid of 8 close-ups (2 columns × 4 rows) in rounded frames with a thin bamboo green border: masked face under the hat; four-pointed shuriken; belt pouch; then back of the head or headgear, shoulder and collar, hands, feet or shoes, back detail.
- Right: framed panel with the same pose as a white wireframe (visible mesh) on a dark background, the labels "≈ tris", "≈ verts", "1 texture (PBR) 2048 × 2048", and 3 stacked texture thumbnails (unwrapped albedo, blue normal map, grey roughness).

CONSISTENCY RULES (top priority):
- The same character, strictly identical in the large pose, the 5 views, the close-ups and the wireframe: same colours, same patterns, same accessories, on the same side of the body.
- Same proportions in all 5 views (same total height, same head size, same shoulder width). Conical straw hat (kasa): identical diameter in all 5 views, about 1.6x the shoulder width, same tip height. A view where the headgear, hat or weapon changes size makes the sheet unusable: this is the defect to avoid first.
- The 5 views are true orthographic rotations of the same model (no different perspective, no different pose).
- No text, numbers, arrows or labels on the 5 views or the close-ups; text only appears in the banner, the name block and the wireframe panel.
- Do not copy the board card or its small thumbnails (they sometimes differ from the character): follow the card's large view.
```

---

## KITSUNEBI (VARIANTE) : `fiches/kitsunebi_s.png`

Rôle : VARIANTE · découpe : `decoupes/kitsunebi_s.png`

### Prompt (FR)

```text
Utilise la planche jointe (bestiaire « 2. FORÊT DE BAMBOU ») comme référence. Le personnage est celui de la carte « KITSUNEBI (VARIANTE) » (rôle VARIANTE, genre interne « kitsunebi_s », scission : un kitsunebi abattu se coupe en deux).

Crée sa fiche modèle individuelle, une seule image paysage 1536×1024, dans exactement le même style et la même mise en page que les fiches du monde 1 (Archipel) : rendu 3D stylisé façon figurine chibi, éclairage doux de studio, fond sombre presque noir.

PERSONNAGE (à respecter exactement, tel qu'il apparaît sur la grande vue de la planche) :
Kitsunebi (variante « scission ») : le même renard blanc chibi que le kitsunebi (fourrure blanche, marques bleu ciel, yeux bleu glacier, queue-flamme bleue, trois feux follets bleus), un peu plus lumineux ; c'est celui qui, abattu, se coupe en deux petits renards.

MISE EN PAGE :
- En haut à gauche : bandeau incliné couleur vert bambou avec une petite icône et le texte « MONDE 2 - FORÊT DE BAMBOU ». Dessous : petit portrait carré du visage, le nom « KITSUNEBI (VARIANTE) » en grandes capitales blanches, une étiquette de rôle « VARIANTE », et une ligne « ♥ — PV ».
- Colonne de gauche, sur toute la hauteur : grande pose 3/4 dynamique (assis, flammes bleues dédoublées autour de lui comme une silhouette fantôme), dans un décor du monde : la forêt de bambou : hautes tiges de bambou vert, temple de bois au fond de la bambouseraie, lanternes de pierre allumées, brume verte et lucioles. Le décor ne doit pas masquer le personnage.
- En haut à droite : vue tournante en 5 vues en pied, de gauche à droite : FACE, 3/4 FACE, PROFIL, DOS, 3/4 DOS. Fond sombre uni sans décor, chaque figurine posée sur un fin anneau lumineux vert bambou au sol. Les 5 figurines entières (de la pointe de la tête ou du chapeau jusqu'aux pieds), à la même échelle, pieds sur la même ligne, sommets à la même hauteur. Pose neutre identique sur les 5 vues : debout droit, bras un peu écartés du corps, debout sur ses quatre pattes, tête droite.
- Au centre : grille de 8 gros plans (2 colonnes × 4 lignes) dans des cadres arrondis à bord fin vert bambou : tête et yeux bleus ; queue-flamme ; feu follet bleu ; puis dos de la tête ou de la coiffe, épaule et col, mains, pieds ou chaussures, détail du dos.
- À droite : panneau encadré avec la même pose en fil de fer blanc (maillage visible) sur fond sombre, les indications « ≈ tris », « ≈ verts », « 1 texture (PBR) 2048 × 2048 », et 3 vignettes de textures empilées (albedo dépliée, normal map bleue, roughness en gris).

CONTRAINTES DE COHÉRENCE (prioritaires) :
- Le même personnage, strictement identique sur la grande pose, les 5 vues, les gros plans et le fil de fer : mêmes couleurs, mêmes motifs, mêmes accessoires, du même côté du corps.
- Mêmes proportions sur les 5 vues (même hauteur totale, même taille de tête, même largeur d'épaules). Même longueur de queue et même nombre de feux follets (3) sur les 5 vues. Une vue où la coiffe, le chapeau ou l'arme change de taille rend la fiche inutilisable : c'est le défaut à éviter en priorité.
- Les 5 vues sont de vraies rotations orthographiques du même modèle (pas de perspective différente, pas de pose différente).
- Aucun texte, chiffre, flèche ni étiquette sur les 5 vues et sur les gros plans ; le texte n'apparaît que dans le bandeau, le bloc nom et le panneau fil de fer.
- Ne recopie pas la carte de la planche ni ses petites vignettes (elles sont parfois différentes du personnage) : suis la grande vue de la carte.
```

### Prompt (EN)

```text
Use the attached board (bestiary "2. FORÊT DE BAMBOU") as reference. The character is the one on the card "KITSUNEBI (VARIANTE)" (role VARIANTE, internal genre "kitsunebi_s").

Create its individual model sheet, a single landscape image 1536×1024, in exactly the same style and layout as the world 1 (Archipel) sheets: stylized 3D chibi figurine render, soft studio lighting, dark near-black background.

CHARACTER (follow exactly, as it appears in the large view of the board):
Kitsunebi ("split" variant): the same chibi white fox as the kitsunebi (white fur, sky-blue markings, ice-blue eyes, blue flame tail, three blue wisps), slightly more luminous; this is the one that splits into two small foxes when defeated.

LAYOUT:
- Top left: slanted bamboo green banner with a small icon and the text "MONDE 2 - FORÊT DE BAMBOU". Below: small square face portrait, the name "KITSUNEBI (VARIANTE)" in large white capitals, a role tag "VARIANTE", and a line "♥ — PV".
- Left column, full height: large dynamic 3/4 pose (sitting, blue flames doubled around it like a ghost silhouette), in a world setting: the bamboo forest: tall green bamboo stalks, wooden temple deep in the grove, lit stone lanterns, green mist and fireflies. The setting must not hide the character.
- Top right: 5-view full-body turnaround, left to right: FRONT, 3/4 FRONT, SIDE, BACK, 3/4 BACK. Plain dark background with no scenery, each figurine standing on a thin glowing bamboo green ring on the floor. All 5 figurines complete (from the top of the head or hat down to the feet), same scale, feet on the same line, tops at the same height. Identical neutral pose in all 5 views: standing straight, arms slightly away from the body, standing on all four legs, head up.
- Centre: grid of 8 close-ups (2 columns × 4 rows) in rounded frames with a thin bamboo green border: head and blue eyes; flame tail; blue wisp; then back of the head or headgear, shoulder and collar, hands, feet or shoes, back detail.
- Right: framed panel with the same pose as a white wireframe (visible mesh) on a dark background, the labels "≈ tris", "≈ verts", "1 texture (PBR) 2048 × 2048", and 3 stacked texture thumbnails (unwrapped albedo, blue normal map, grey roughness).

CONSISTENCY RULES (top priority):
- The same character, strictly identical in the large pose, the 5 views, the close-ups and the wireframe: same colours, same patterns, same accessories, on the same side of the body.
- Same proportions in all 5 views (same total height, same head size, same shoulder width). Same tail length and same number of wisps (3) in all 5 views. A view where the headgear, hat or weapon changes size makes the sheet unusable: this is the defect to avoid first.
- The 5 views are true orthographic rotations of the same model (no different perspective, no different pose).
- No text, numbers, arrows or labels on the 5 views or the close-ups; text only appears in the banner, the name block and the wireframe panel.
- Do not copy the board card or its small thumbnails (they sometimes differ from the character): follow the card's large view.
```

---

## MOINE TANUKI (VARIANTE) : `fiches/tanuki_d.png`

Rôle : VARIANTE · découpe : `decoupes/tanuki_d.png`

### Prompt (FR)

```text
Utilise la planche jointe (bestiaire « 2. FORÊT DE BAMBOU ») comme référence. Le personnage est celui de la carte « MOINE TANUKI (VARIANTE) » (rôle VARIANTE, genre interne « tanuki_d », leurre DORON du tanuki).

Crée sa fiche modèle individuelle, une seule image paysage 1536×1024, dans exactement le même style et la même mise en page que les fiches du monde 1 (Archipel) : rendu 3D stylisé façon figurine chibi, éclairage doux de studio, fond sombre presque noir.

PERSONNAGE (à respecter exactement, tel qu'il apparaît sur la grande vue de la planche) :
Moine tanuki (variante « leurre DORON ») : tanuki chibi brun et trapu, collerette de fourrure blanche bouffante sur la poitrine, masque sombre autour des yeux, grand chapeau conique de paille. Robe de voyage brune, étole vert camouflage en bandoulière, sac de toile dans le dos. Lanterne de papier allumée (lumière jaune chaude) dans la main droite.

MISE EN PAGE :
- En haut à gauche : bandeau incliné couleur vert bambou avec une petite icône et le texte « MONDE 2 - FORÊT DE BAMBOU ». Dessous : petit portrait carré du visage, le nom « MOINE TANUKI (VARIANTE) » en grandes capitales blanches, une étiquette de rôle « VARIANTE », et une ligne « ♥ — PV ».
- Colonne de gauche, sur toute la hauteur : grande pose 3/4 dynamique (il lève sa lanterne, un nuage de fumée DORON à ses pieds), dans un décor du monde : la forêt de bambou : hautes tiges de bambou vert, temple de bois au fond de la bambouseraie, lanternes de pierre allumées, brume verte et lucioles. Le décor ne doit pas masquer le personnage.
- En haut à droite : vue tournante en 5 vues en pied, de gauche à droite : FACE, 3/4 FACE, PROFIL, DOS, 3/4 DOS. Fond sombre uni sans décor, chaque figurine posée sur un fin anneau lumineux vert bambou au sol. Les 5 figurines entières (de la pointe de la tête ou du chapeau jusqu'aux pieds), à la même échelle, pieds sur la même ligne, sommets à la même hauteur. Pose neutre identique sur les 5 vues : debout droit, bras un peu écartés du corps, lanterne pendue à la main droite.
- Au centre : grille de 8 gros plans (2 colonnes × 4 lignes) dans des cadres arrondis à bord fin vert bambou : visage du tanuki ; lanterne allumée ; collerette de fourrure blanche ; puis dos de la tête ou de la coiffe, épaule et col, mains, pieds ou chaussures, détail du dos.
- À droite : panneau encadré avec la même pose en fil de fer blanc (maillage visible) sur fond sombre, les indications « ≈ tris », « ≈ verts », « 1 texture (PBR) 2048 × 2048 », et 3 vignettes de textures empilées (albedo dépliée, normal map bleue, roughness en gris).

CONTRAINTES DE COHÉRENCE (prioritaires) :
- Le même personnage, strictement identique sur la grande pose, les 5 vues, les gros plans et le fil de fer : mêmes couleurs, mêmes motifs, mêmes accessoires, du même côté du corps.
- Mêmes proportions sur les 5 vues (même hauteur totale, même taille de tête, même largeur d'épaules). Chapeau conique de paille (kasa) : même diamètre sur les 5 vues, environ 1,6 fois la largeur des épaules, même hauteur de pointe. Une vue où la coiffe, le chapeau ou l'arme change de taille rend la fiche inutilisable : c'est le défaut à éviter en priorité.
- Les 5 vues sont de vraies rotations orthographiques du même modèle (pas de perspective différente, pas de pose différente).
- Aucun texte, chiffre, flèche ni étiquette sur les 5 vues et sur les gros plans ; le texte n'apparaît que dans le bandeau, le bloc nom et le panneau fil de fer.
- Ne recopie pas la carte de la planche ni ses petites vignettes (elles sont parfois différentes du personnage) : suis la grande vue de la carte.
```

### Prompt (EN)

```text
Use the attached board (bestiary "2. FORÊT DE BAMBOU") as reference. The character is the one on the card "MOINE TANUKI (VARIANTE)" (role VARIANTE, internal genre "tanuki_d").

Create its individual model sheet, a single landscape image 1536×1024, in exactly the same style and layout as the world 1 (Archipel) sheets: stylized 3D chibi figurine render, soft studio lighting, dark near-black background.

CHARACTER (follow exactly, as it appears in the large view of the board):
Tanuki monk ("DORON decoy" variant): stocky brown chibi tanuki, puffy white fur ruff on the chest, dark mask around the eyes, large straw conical hat. Brown travel robe, camouflage-green stole across the chest, cloth bag on the back. Lit paper lantern (warm yellow light) in the right hand.

LAYOUT:
- Top left: slanted bamboo green banner with a small icon and the text "MONDE 2 - FORÊT DE BAMBOU". Below: small square face portrait, the name "MOINE TANUKI (VARIANTE)" in large white capitals, a role tag "VARIANTE", and a line "♥ — PV".
- Left column, full height: large dynamic 3/4 pose (raising his lantern, a DORON smoke puff at his feet), in a world setting: the bamboo forest: tall green bamboo stalks, wooden temple deep in the grove, lit stone lanterns, green mist and fireflies. The setting must not hide the character.
- Top right: 5-view full-body turnaround, left to right: FRONT, 3/4 FRONT, SIDE, BACK, 3/4 BACK. Plain dark background with no scenery, each figurine standing on a thin glowing bamboo green ring on the floor. All 5 figurines complete (from the top of the head or hat down to the feet), same scale, feet on the same line, tops at the same height. Identical neutral pose in all 5 views: standing straight, arms slightly away from the body, lantern hanging from the right hand.
- Centre: grid of 8 close-ups (2 columns × 4 rows) in rounded frames with a thin bamboo green border: tanuki face; lit lantern; white fur ruff; then back of the head or headgear, shoulder and collar, hands, feet or shoes, back detail.
- Right: framed panel with the same pose as a white wireframe (visible mesh) on a dark background, the labels "≈ tris", "≈ verts", "1 texture (PBR) 2048 × 2048", and 3 stacked texture thumbnails (unwrapped albedo, blue normal map, grey roughness).

CONSISTENCY RULES (top priority):
- The same character, strictly identical in the large pose, the 5 views, the close-ups and the wireframe: same colours, same patterns, same accessories, on the same side of the body.
- Same proportions in all 5 views (same total height, same head size, same shoulder width). Conical straw hat (kasa): identical diameter in all 5 views, about 1.6x the shoulder width, same tip height. A view where the headgear, hat or weapon changes size makes the sheet unusable: this is the defect to avoid first.
- The 5 views are true orthographic rotations of the same model (no different perspective, no different pose).
- No text, numbers, arrows or labels on the 5 views or the close-ups; text only appears in the banner, the name block and the wireframe panel.
- Do not copy the board card or its small thumbnails (they sometimes differ from the character): follow the card's large view.
```

---

## MOINE ARMÉ D'ÉLITE : `fiches/brute_elite.png`

Rôle : ÉLITE · découpe : `decoupes/brute_elite.png`

### Prompt (FR)

```text
Utilise la planche jointe (bestiaire « 2. FORÊT DE BAMBOU ») comme référence. Le personnage est celui de la carte « MOINE ARMÉ D'ÉLITE » (rôle ÉLITE, genre de base « brute », défi du sanctuaire de l'Oni (« GARDIEN D'ÉLITE »)).

Crée sa fiche modèle individuelle, une seule image paysage 1536×1024, dans exactement le même style et la même mise en page que les fiches du monde 1 (Archipel) : rendu 3D stylisé façon figurine chibi, éclairage doux de studio, fond sombre presque noir.

PERSONNAGE (à respecter exactement, tel qu'il apparaît sur la grande vue de la planche) :
Moine armé d'élite : moine chibi trapu au visage sombre caché sous un masque-crâne blanc et or à cornes (style oni/renard), aura orange. Tenue de combat noire à liserés dorés, épaulières noires, chapelet de grosses perles orange, ceinture à boucle dorée, pieds nus. Dague à large lame dans la main droite, naginata à lame courbe violacée dans la main gauche.

MISE EN PAGE :
- En haut à gauche : bandeau incliné couleur vert bambou avec une petite icône et le texte « MONDE 2 - FORÊT DE BAMBOU ». Dessous : petit portrait carré du visage, le nom « MOINE ARMÉ D'ÉLITE » en grandes capitales blanches, une étiquette de rôle « ÉLITE », et une ligne « ♥ — PV ».
- Colonne de gauche, sur toute la hauteur : grande pose 3/4 dynamique (posture d'attaque, les deux armes croisées), dans un décor du monde : la forêt de bambou : hautes tiges de bambou vert, temple de bois au fond de la bambouseraie, lanternes de pierre allumées, brume verte et lucioles. Le décor ne doit pas masquer le personnage.
- En haut à droite : vue tournante en 5 vues en pied, de gauche à droite : FACE, 3/4 FACE, PROFIL, DOS, 3/4 DOS. Fond sombre uni sans décor, chaque figurine posée sur un fin anneau lumineux vert bambou au sol. Les 5 figurines entières (de la pointe de la tête ou du chapeau jusqu'aux pieds), à la même échelle, pieds sur la même ligne, sommets à la même hauteur. Pose neutre identique sur les 5 vues : debout droit, bras un peu écartés du corps, armes tenues lames vers le bas, bras écartés.
- Au centre : grille de 8 gros plans (2 colonnes × 4 lignes) dans des cadres arrondis à bord fin vert bambou : masque-crâne doré ; chapelet orange ; lame de naginata ; puis dos de la tête ou de la coiffe, épaule et col, mains, pieds ou chaussures, détail du dos.
- À droite : panneau encadré avec la même pose en fil de fer blanc (maillage visible) sur fond sombre, les indications « ≈ tris », « ≈ verts », « 1 texture (PBR) 2048 × 2048 », et 3 vignettes de textures empilées (albedo dépliée, normal map bleue, roughness en gris).

CONTRAINTES DE COHÉRENCE (prioritaires) :
- Le même personnage, strictement identique sur la grande pose, les 5 vues, les gros plans et le fil de fer : mêmes couleurs, mêmes motifs, mêmes accessoires, du même côté du corps.
- Mêmes proportions sur les 5 vues (même hauteur totale, même taille de tête, même largeur d'épaules). Même masque et mêmes cornes sur les 5 vues. Une vue où la coiffe, le chapeau ou l'arme change de taille rend la fiche inutilisable : c'est le défaut à éviter en priorité.
- Les 5 vues sont de vraies rotations orthographiques du même modèle (pas de perspective différente, pas de pose différente).
- Aucun texte, chiffre, flèche ni étiquette sur les 5 vues et sur les gros plans ; le texte n'apparaît que dans le bandeau, le bloc nom et le panneau fil de fer.
- Ne recopie pas la carte de la planche ni ses petites vignettes (elles sont parfois différentes du personnage) : suis la grande vue de la carte.
```

### Prompt (EN)

```text
Use the attached board (bestiary "2. FORÊT DE BAMBOU") as reference. The character is the one on the card "MOINE ARMÉ D'ÉLITE" (role ÉLITE, base genre "brute").

Create its individual model sheet, a single landscape image 1536×1024, in exactly the same style and layout as the world 1 (Archipel) sheets: stylized 3D chibi figurine render, soft studio lighting, dark near-black background.

CHARACTER (follow exactly, as it appears in the large view of the board):
Elite armed monk: stocky chibi monk with a dark face hidden under a white-and-gold horned skull mask (oni/fox style), orange aura. Black combat outfit with gold trim, black shoulder guards, mala of big orange beads, gold-buckled belt, bare feet. Wide-bladed dagger in the right hand, naginata with a curved violet blade in the left hand.

LAYOUT:
- Top left: slanted bamboo green banner with a small icon and the text "MONDE 2 - FORÊT DE BAMBOU". Below: small square face portrait, the name "MOINE ARMÉ D'ÉLITE" in large white capitals, a role tag "ÉLITE", and a line "♥ — PV".
- Left column, full height: large dynamic 3/4 pose (attack stance, both weapons crossed), in a world setting: the bamboo forest: tall green bamboo stalks, wooden temple deep in the grove, lit stone lanterns, green mist and fireflies. The setting must not hide the character.
- Top right: 5-view full-body turnaround, left to right: FRONT, 3/4 FRONT, SIDE, BACK, 3/4 BACK. Plain dark background with no scenery, each figurine standing on a thin glowing bamboo green ring on the floor. All 5 figurines complete (from the top of the head or hat down to the feet), same scale, feet on the same line, tops at the same height. Identical neutral pose in all 5 views: standing straight, arms slightly away from the body, weapons held blades down, arms apart.
- Centre: grid of 8 close-ups (2 columns × 4 rows) in rounded frames with a thin bamboo green border: golden skull mask; orange beads; naginata blade; then back of the head or headgear, shoulder and collar, hands, feet or shoes, back detail.
- Right: framed panel with the same pose as a white wireframe (visible mesh) on a dark background, the labels "≈ tris", "≈ verts", "1 texture (PBR) 2048 × 2048", and 3 stacked texture thumbnails (unwrapped albedo, blue normal map, grey roughness).

CONSISTENCY RULES (top priority):
- The same character, strictly identical in the large pose, the 5 views, the close-ups and the wireframe: same colours, same patterns, same accessories, on the same side of the body.
- Same proportions in all 5 views (same total height, same head size, same shoulder width). Same mask and same horns in all 5 views. A view where the headgear, hat or weapon changes size makes the sheet unusable: this is the defect to avoid first.
- The 5 views are true orthographic rotations of the same model (no different perspective, no different pose).
- No text, numbers, arrows or labels on the 5 views or the close-ups; text only appears in the banner, the name block and the wireframe panel.
- Do not copy the board card or its small thumbnails (they sometimes differ from the character): follow the card's large view.
```

---

## SÔHEI-GASHIRA : `fiches/sohei_gashira.png`

Rôle : GARDIEN · découpe : `decoupes/sohei_gashira.png`

### Prompt (FR)

```text
Utilise la planche jointe (bestiaire « 2. FORÊT DE BAMBOU ») comme référence. Le personnage est celui de la carte « SÔHEI-GASHIRA » (rôle GARDIEN, identifiant de fichier « sohei_gashira », l'abbé guerrier du temple).

Crée sa fiche modèle individuelle, une seule image paysage 1536×1024, dans exactement le même style et la même mise en page que les fiches du monde 1 (Archipel) : rendu 3D stylisé façon figurine chibi, éclairage doux de studio, fond sombre presque noir.

PERSONNAGE (à respecter exactement, tel qu'il apparaît sur la grande vue de la planche) :
Sôhei-gashira, l'abbé guerrier : vieux moine chibi massif et trapu, crâne rasé, longue barbe blanche fournie et sourcils blancs broussailleux, regard sévère. Robe vert sombre à liserés dorés, manches larges, grand chapelet de grosses perles de bois brun, ceinture de corde dorée nouée, bandes de poignet noires. Sur le dos, une bannière (sashimono) jaune à mon noir. Shakujō (bâton de pèlerin) doré à anneau ouvragé dans la main droite, poing gauche levé.

MISE EN PAGE :
- En haut à gauche : bandeau incliné couleur vert bambou avec une petite icône et le texte « MONDE 2 - FORÊT DE BAMBOU ». Dessous : petit portrait carré du visage, le nom « SÔHEI-GASHIRA » en grandes capitales blanches, une étiquette de rôle « GARDIEN », et une ligne « ♥ — PV ».
- Colonne de gauche, sur toute la hauteur : grande pose 3/4 dynamique (il frappe le sol de son shakujō, poing levé, bannière déployée), dans un décor du monde : la forêt de bambou : hautes tiges de bambou vert, temple de bois au fond de la bambouseraie, lanternes de pierre allumées, brume verte et lucioles. Le décor ne doit pas masquer le personnage.
- En haut à droite : vue tournante en 5 vues en pied, de gauche à droite : FACE, 3/4 FACE, PROFIL, DOS, 3/4 DOS. Fond sombre uni sans décor, chaque figurine posée sur un fin anneau lumineux vert bambou au sol. Les 5 figurines entières (de la pointe de la tête ou du chapeau jusqu'aux pieds), à la même échelle, pieds sur la même ligne, sommets à la même hauteur. Pose neutre identique sur les 5 vues : debout droit, bras un peu écartés du corps, shakujō vertical dans la main droite.
- Au centre : grille de 8 gros plans (2 colonnes × 4 lignes) dans des cadres arrondis à bord fin vert bambou : visage à barbe blanche ; chapelet de perles ; anneau doré du shakujō ; puis dos de la tête ou de la coiffe, épaule et col, mains, pieds ou chaussures, détail du dos.
- À droite : panneau encadré avec la même pose en fil de fer blanc (maillage visible) sur fond sombre, les indications « ≈ tris », « ≈ verts », « 1 texture (PBR) 2048 × 2048 », et 3 vignettes de textures empilées (albedo dépliée, normal map bleue, roughness en gris).

CONTRAINTES DE COHÉRENCE (prioritaires) :
- Le même personnage, strictement identique sur la grande pose, les 5 vues, les gros plans et le fil de fer : mêmes couleurs, mêmes motifs, mêmes accessoires, du même côté du corps.
- Mêmes proportions sur les 5 vues (même hauteur totale, même taille de tête, même largeur d'épaules). Même hauteur de bannière et de bâton sur les 5 vues. Une vue où la coiffe, le chapeau ou l'arme change de taille rend la fiche inutilisable : c'est le défaut à éviter en priorité.
- Les 5 vues sont de vraies rotations orthographiques du même modèle (pas de perspective différente, pas de pose différente).
- Aucun texte, chiffre, flèche ni étiquette sur les 5 vues et sur les gros plans ; le texte n'apparaît que dans le bandeau, le bloc nom et le panneau fil de fer.
- Ne recopie pas la carte de la planche ni ses petites vignettes (elles sont parfois différentes du personnage) : suis la grande vue de la carte.
```

### Prompt (EN)

```text
Use the attached board (bestiary "2. FORÊT DE BAMBOU") as reference. The character is the one on the card "SÔHEI-GASHIRA" (role GARDIEN, file id "sohei_gashira").

Create its individual model sheet, a single landscape image 1536×1024, in exactly the same style and layout as the world 1 (Archipel) sheets: stylized 3D chibi figurine render, soft studio lighting, dark near-black background.

CHARACTER (follow exactly, as it appears in the large view of the board):
Sôhei-gashira, the warrior abbot: massive stocky chibi old monk, shaved head, thick long white beard and bushy white brows, stern look. Dark green robe with gold trim, wide sleeves, big mala of large brown wooden beads, knotted gold rope belt, black wrist bands. On his back a yellow banner (sashimono) with a black crest. Ornate gold ringed pilgrim staff (shakujō) in the right hand, left fist raised.

LAYOUT:
- Top left: slanted bamboo green banner with a small icon and the text "MONDE 2 - FORÊT DE BAMBOU". Below: small square face portrait, the name "SÔHEI-GASHIRA" in large white capitals, a role tag "GARDIEN", and a line "♥ — PV".
- Left column, full height: large dynamic 3/4 pose (striking the ground with his shakujō, fist raised, banner unfurled), in a world setting: the bamboo forest: tall green bamboo stalks, wooden temple deep in the grove, lit stone lanterns, green mist and fireflies. The setting must not hide the character.
- Top right: 5-view full-body turnaround, left to right: FRONT, 3/4 FRONT, SIDE, BACK, 3/4 BACK. Plain dark background with no scenery, each figurine standing on a thin glowing bamboo green ring on the floor. All 5 figurines complete (from the top of the head or hat down to the feet), same scale, feet on the same line, tops at the same height. Identical neutral pose in all 5 views: standing straight, arms slightly away from the body, shakujō vertical in the right hand.
- Centre: grid of 8 close-ups (2 columns × 4 rows) in rounded frames with a thin bamboo green border: white-bearded face; bead mala; gold ring of the shakujō; then back of the head or headgear, shoulder and collar, hands, feet or shoes, back detail.
- Right: framed panel with the same pose as a white wireframe (visible mesh) on a dark background, the labels "≈ tris", "≈ verts", "1 texture (PBR) 2048 × 2048", and 3 stacked texture thumbnails (unwrapped albedo, blue normal map, grey roughness).

CONSISTENCY RULES (top priority):
- The same character, strictly identical in the large pose, the 5 views, the close-ups and the wireframe: same colours, same patterns, same accessories, on the same side of the body.
- Same proportions in all 5 views (same total height, same head size, same shoulder width). Same banner and staff height in all 5 views. A view where the headgear, hat or weapon changes size makes the sheet unusable: this is the defect to avoid first.
- The 5 views are true orthographic rotations of the same model (no different perspective, no different pose).
- No text, numbers, arrows or labels on the 5 views or the close-ups; text only appears in the banner, the name block and the wireframe panel.
- Do not copy the board card or its small thumbnails (they sometimes differ from the character): follow the card's large view.
```

---

## ISHI-NIÔ : `fiches/ishi_nio.png`

Rôle : BOSS · découpe : `decoupes/ishi_nio.png`

### Prompt (FR)

```text
Utilise la planche jointe (bestiaire « 2. FORÊT DE BAMBOU ») comme référence. Le personnage est celui de la carte « ISHI-NIÔ » (rôle BOSS, identifiant de fichier « ishi_nio », le colosse de pierre du temple).

Crée sa fiche modèle individuelle, une seule image paysage 1536×1024, dans exactement le même style et la même mise en page que les fiches du monde 1 (Archipel) : rendu 3D stylisé façon figurine chibi, éclairage doux de studio, fond sombre presque noir.

PERSONNAGE (à respecter exactement, tel qu'il apparaît sur la grande vue de la planche) :
Ishi-niô, colosse de pierre : géant chibi massif en pierre gris-bleu taillée, cornes violettes recourbées, yeux verts lumineux, bouche grande ouverte en cri. Armure de pierre façon samouraï (épaulières, plastron, tassettes), cordes vertes croisées sur le torse, ceinture dorée à plaque verte. Massue (kanabō) en bois cloutée de pointes dans la main droite. Fines particules vertes lumineuses autour de lui.

MISE EN PAGE :
- En haut à gauche : bandeau incliné couleur vert bambou avec une petite icône et le texte « MONDE 2 - FORÊT DE BAMBOU ». Dessous : petit portrait carré du visage, le nom « ISHI-NIÔ » en grandes capitales blanches, une étiquette de rôle « BOSS », et une ligne « ♥ — PV ».
- Colonne de gauche, sur toute la hauteur : grande pose 3/4 dynamique (il lève sa massue en rugissant, éclats de pierre au sol), dans un décor du monde : la forêt de bambou : hautes tiges de bambou vert, temple de bois au fond de la bambouseraie, lanternes de pierre allumées, brume verte et lucioles. Le décor ne doit pas masquer le personnage.
- En haut à droite : vue tournante en 5 vues en pied, de gauche à droite : FACE, 3/4 FACE, PROFIL, DOS, 3/4 DOS. Fond sombre uni sans décor, chaque figurine posée sur un fin anneau lumineux vert bambou au sol. Les 5 figurines entières (de la pointe de la tête ou du chapeau jusqu'aux pieds), à la même échelle, pieds sur la même ligne, sommets à la même hauteur. Pose neutre identique sur les 5 vues : debout droit, bras un peu écartés du corps, massue tenue verticalement, tête en haut, main droite.
- Au centre : grille de 8 gros plans (2 colonnes × 4 lignes) dans des cadres arrondis à bord fin vert bambou : visage de pierre aux yeux verts ; cordes vertes croisées ; tête de massue cloutée ; puis dos de la tête ou de la coiffe, épaule et col, mains, pieds ou chaussures, détail du dos.
- À droite : panneau encadré avec la même pose en fil de fer blanc (maillage visible) sur fond sombre, les indications « ≈ tris », « ≈ verts », « 1 texture (PBR) 2048 × 2048 », et 3 vignettes de textures empilées (albedo dépliée, normal map bleue, roughness en gris).

CONTRAINTES DE COHÉRENCE (prioritaires) :
- Le même personnage, strictement identique sur la grande pose, les 5 vues, les gros plans et le fil de fer : mêmes couleurs, mêmes motifs, mêmes accessoires, du même côté du corps.
- Mêmes proportions sur les 5 vues (même hauteur totale, même taille de tête, même largeur d'épaules). Mêmes cornes et même massue sur les 5 vues. Une vue où la coiffe, le chapeau ou l'arme change de taille rend la fiche inutilisable : c'est le défaut à éviter en priorité.
- Les 5 vues sont de vraies rotations orthographiques du même modèle (pas de perspective différente, pas de pose différente).
- Aucun texte, chiffre, flèche ni étiquette sur les 5 vues et sur les gros plans ; le texte n'apparaît que dans le bandeau, le bloc nom et le panneau fil de fer.
- Ne recopie pas la carte de la planche ni ses petites vignettes (elles sont parfois différentes du personnage) : suis la grande vue de la carte.
```

### Prompt (EN)

```text
Use the attached board (bestiary "2. FORÊT DE BAMBOU") as reference. The character is the one on the card "ISHI-NIÔ" (role BOSS, file id "ishi_nio").

Create its individual model sheet, a single landscape image 1536×1024, in exactly the same style and layout as the world 1 (Archipel) sheets: stylized 3D chibi figurine render, soft studio lighting, dark near-black background.

CHARACTER (follow exactly, as it appears in the large view of the board):
Ishi-niô, stone colossus: massive chibi giant of carved grey-blue stone, curved purple horns, glowing green eyes, mouth wide open in a roar. Samurai-style stone armour (shoulder guards, chest plate, tassets), green ropes crossed on the chest, gold belt with green plate. Spiked wooden club (kanabō) in the right hand. Fine glowing green particles around him.

LAYOUT:
- Top left: slanted bamboo green banner with a small icon and the text "MONDE 2 - FORÊT DE BAMBOU". Below: small square face portrait, the name "ISHI-NIÔ" in large white capitals, a role tag "BOSS", and a line "♥ — PV".
- Left column, full height: large dynamic 3/4 pose (raising his club with a roar, stone chips on the ground), in a world setting: the bamboo forest: tall green bamboo stalks, wooden temple deep in the grove, lit stone lanterns, green mist and fireflies. The setting must not hide the character.
- Top right: 5-view full-body turnaround, left to right: FRONT, 3/4 FRONT, SIDE, BACK, 3/4 BACK. Plain dark background with no scenery, each figurine standing on a thin glowing bamboo green ring on the floor. All 5 figurines complete (from the top of the head or hat down to the feet), same scale, feet on the same line, tops at the same height. Identical neutral pose in all 5 views: standing straight, arms slightly away from the body, club held vertically, head up, right hand.
- Centre: grid of 8 close-ups (2 columns × 4 rows) in rounded frames with a thin bamboo green border: stone face with green eyes; crossed green ropes; spiked club head; then back of the head or headgear, shoulder and collar, hands, feet or shoes, back detail.
- Right: framed panel with the same pose as a white wireframe (visible mesh) on a dark background, the labels "≈ tris", "≈ verts", "1 texture (PBR) 2048 × 2048", and 3 stacked texture thumbnails (unwrapped albedo, blue normal map, grey roughness).

CONSISTENCY RULES (top priority):
- The same character, strictly identical in the large pose, the 5 views, the close-ups and the wireframe: same colours, same patterns, same accessories, on the same side of the body.
- Same proportions in all 5 views (same total height, same head size, same shoulder width). Same horns and same club in all 5 views. A view where the headgear, hat or weapon changes size makes the sheet unusable: this is the defect to avoid first.
- The 5 views are true orthographic rotations of the same model (no different perspective, no different pose).
- No text, numbers, arrows or labels on the 5 views or the close-ups; text only appears in the banner, the name block and the wireframe panel.
- Do not copy the board card or its small thumbnails (they sometimes differ from the character): follow the card's large view.
```
