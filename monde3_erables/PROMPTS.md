# Prompts ChatGPT : fiches modèles du monde 3 (Érables)

## Mode d'emploi

1. Ouvrir une nouvelle conversation ChatGPT (génération d'image) et **joindre la planche** `03_erables.png` (C:/Users/victo/ippitsu-env/bestiaires-gpt/03_erables.png). Joindre aussi une fiche du monde 1 (par exemple `bestiaire-w1/fiches/ashigaru.png`) comme modèle de mise en page si possible.
2. **Coller le prompt** du personnage (version française ; la version anglaise est en dessous si le résultat dérive).
3. Vérifier : 5 vues complètes, même échelle, même largeur de chapeau ou de coiffe d'une vue à l'autre, aucun texte sur les vues. Sinon, redemander en citant la contrainte non respectée.
4. **Enregistrer l'image** sous `fiches/<genre>.png` dans ce dossier (`monde3_erables/fiches/`), avec le même nom que la découpe correspondante dans `decoupes/`.

Un personnage par conversation (ou repartir d'une conversation propre) pour éviter que les personnages se mélangent.

Personnages (15) : `oni`, `kappa`, `brute`, `tate`, `funa`, `shinobi`, `shuriken`, `kunoichi`, `kamaitachi`, `konoha`, `tanuki`, `tanuki_d`, `brute_elite`, `jonin`, `oni_musha`

---

## NINJA ROUGE : `fiches/oni.png`

Rôle : COMMUN · découpe : `decoupes/oni.png`

### Prompt (FR)

```text
Utilise la planche jointe (bestiaire « 3. ÉRABLES ») comme référence. Le personnage est celui de la carte « NINJA ROUGE » (rôle COMMUN, genre interne « oni »).

Crée sa fiche modèle individuelle, une seule image paysage 1536×1024, dans exactement le même style et la même mise en page que les fiches du monde 1 (Archipel) : rendu 3D stylisé façon figurine chibi, éclairage doux de studio, fond sombre presque noir.

PERSONNAGE (à respecter exactement, tel qu'il apparaît sur la grande vue de la planche) :
Ninja rouge : ninja chibi en tenue noire, capuche rouge bordeaux pointue, masque noir couvrant le bas du visage, yeux rouges perçants. Écharpe rouge autour du cou, protège-bras noirs, ceinture (obi) rouge nouée avec une cordelette dorée et pans pendants, pantalon noir resserré, tabi rouge sombre. Katana à garde dorée dans la main droite.

MISE EN PAGE :
- En haut à gauche : bandeau incliné couleur orange érable avec une petite icône et le texte « MONDE 3 - ÉRABLES ». Dessous : petit portrait carré du visage, le nom « NINJA ROUGE » en grandes capitales blanches, une étiquette de rôle « COMMUN », et une ligne « ♥ — PV ».
- Colonne de gauche, sur toute la hauteur : grande pose 3/4 dynamique (accroupi, katana levé), dans un décor du monde : le village sous les érables d'automne : érables rouges et orange, pont de bois laqué rouge, toits de temple, lanternes, feuilles d'érable qui tombent, lumière de fin d'après-midi. Le décor ne doit pas masquer le personnage.
- En haut à droite : vue tournante en 5 vues en pied, de gauche à droite : FACE, 3/4 FACE, PROFIL, DOS, 3/4 DOS. Fond sombre uni sans décor, chaque figurine posée sur un fin anneau lumineux orange érable au sol. Les 5 figurines entières (de la pointe de la tête ou du chapeau jusqu'aux pieds), à la même échelle, pieds sur la même ligne, sommets à la même hauteur. Pose neutre identique sur les 5 vues : debout droit, bras un peu écartés du corps, katana tenu lame vers le bas, main droite.
- Au centre : grille de 8 gros plans (2 colonnes × 4 lignes) dans des cadres arrondis à bord fin orange érable : yeux rouges sous la capuche ; étoffe rouge de l'écharpe ; nœud de cordelette dorée ; puis dos de la tête ou de la coiffe, épaule et col, mains, pieds ou chaussures, détail du dos.
- À droite : panneau encadré avec la même pose en fil de fer blanc (maillage visible) sur fond sombre, les indications « ≈ tris », « ≈ verts », « 1 texture (PBR) 2048 × 2048 », et 3 vignettes de textures empilées (albedo dépliée, normal map bleue, roughness en gris).

CONTRAINTES DE COHÉRENCE (prioritaires) :
- Le même personnage, strictement identique sur la grande pose, les 5 vues, les gros plans et le fil de fer : mêmes couleurs, mêmes motifs, mêmes accessoires, du même côté du corps.
- Mêmes proportions sur les 5 vues (même hauteur totale, même taille de tête, même largeur d'épaules). Même capuche/cagoule et même longueur d'écharpe sur les 5 vues. Une vue où la coiffe, le chapeau ou l'arme change de taille rend la fiche inutilisable : c'est le défaut à éviter en priorité.
- Les 5 vues sont de vraies rotations orthographiques du même modèle (pas de perspective différente, pas de pose différente).
- Aucun texte, chiffre, flèche ni étiquette sur les 5 vues et sur les gros plans ; le texte n'apparaît que dans le bandeau, le bloc nom et le panneau fil de fer.
- Ne recopie pas la carte de la planche ni ses petites vignettes (elles sont parfois différentes du personnage) : suis la grande vue de la carte.
```

### Prompt (EN)

```text
Use the attached board (bestiary "3. ÉRABLES") as reference. The character is the one on the card "NINJA ROUGE" (role COMMUN, internal genre "oni").

Create its individual model sheet, a single landscape image 1536×1024, in exactly the same style and layout as the world 1 (Archipel) sheets: stylized 3D chibi figurine render, soft studio lighting, dark near-black background.

CHARACTER (follow exactly, as it appears in the large view of the board):
Red ninja: chibi ninja in black, pointed dark-red hood, black mask over the lower face, piercing red eyes. Red scarf around the neck, black arm guards, red obi knotted with a gold cord and hanging ends, tight black trousers, dark red tabi. Katana with gold guard in the right hand.

LAYOUT:
- Top left: slanted maple orange banner with a small icon and the text "MONDE 3 - ÉRABLES". Below: small square face portrait, the name "NINJA ROUGE" in large white capitals, a role tag "COMMUN", and a line "♥ — PV".
- Left column, full height: large dynamic 3/4 pose (crouched, katana raised), in a world setting: the village under autumn maples: red and orange maple trees, red lacquered wooden bridge, temple roofs, lanterns, falling maple leaves, late-afternoon light. The setting must not hide the character.
- Top right: 5-view full-body turnaround, left to right: FRONT, 3/4 FRONT, SIDE, BACK, 3/4 BACK. Plain dark background with no scenery, each figurine standing on a thin glowing maple orange ring on the floor. All 5 figurines complete (from the top of the head or hat down to the feet), same scale, feet on the same line, tops at the same height. Identical neutral pose in all 5 views: standing straight, arms slightly away from the body, katana held blade down, right hand.
- Centre: grid of 8 close-ups (2 columns × 4 rows) in rounded frames with a thin maple orange border: red eyes under the hood; red scarf fabric; gold cord knot; then back of the head or headgear, shoulder and collar, hands, feet or shoes, back detail.
- Right: framed panel with the same pose as a white wireframe (visible mesh) on a dark background, the labels "≈ tris", "≈ verts", "1 texture (PBR) 2048 × 2048", and 3 stacked texture thumbnails (unwrapped albedo, blue normal map, grey roughness).

CONSISTENCY RULES (top priority):
- The same character, strictly identical in the large pose, the 5 views, the close-ups and the wireframe: same colours, same patterns, same accessories, on the same side of the body.
- Same proportions in all 5 views (same total height, same head size, same shoulder width). Same hood and same scarf length in all 5 views. A view where the headgear, hat or weapon changes size makes the sheet unusable: this is the defect to avoid first.
- The 5 views are true orthographic rotations of the same model (no different perspective, no different pose).
- No text, numbers, arrows or labels on the 5 views or the close-ups; text only appears in the banner, the name block and the wireframe panel.
- Do not copy the board card or its small thumbnails (they sometimes differ from the character): follow the card's large view.
```

---

## NINJA AUX DEUX LAMES : `fiches/kappa.png`

Rôle : COMMUN · découpe : `decoupes/kappa.png`

### Prompt (FR)

```text
Utilise la planche jointe (bestiaire « 3. ÉRABLES ») comme référence. Le personnage est celui de la carte « NINJA AUX DEUX LAMES » (rôle COMMUN, genre interne « kappa »).

Crée sa fiche modèle individuelle, une seule image paysage 1536×1024, dans exactement le même style et la même mise en page que les fiches du monde 1 (Archipel) : rendu 3D stylisé façon figurine chibi, éclairage doux de studio, fond sombre presque noir.

PERSONNAGE (à respecter exactement, tel qu'il apparaît sur la grande vue de la planche) :
Ninja aux deux lames : ninja chibi en tenue noire, cagoule noire avec bandeau rouge à motif doré noué derrière en longs pans flottants, masque noir, yeux rouges. Écharpe rouge, protège-bras, ceinture rouge-brun, pantalon noir. Deux ninjatō à lame droite, un dans chaque main.

MISE EN PAGE :
- En haut à gauche : bandeau incliné couleur orange érable avec une petite icône et le texte « MONDE 3 - ÉRABLES ». Dessous : petit portrait carré du visage, le nom « NINJA AUX DEUX LAMES » en grandes capitales blanches, une étiquette de rôle « COMMUN », et une ligne « ♥ — PV ».
- Colonne de gauche, sur toute la hauteur : grande pose 3/4 dynamique (jambes écartées, les deux lames tendues de chaque côté), dans un décor du monde : le village sous les érables d'automne : érables rouges et orange, pont de bois laqué rouge, toits de temple, lanternes, feuilles d'érable qui tombent, lumière de fin d'après-midi. Le décor ne doit pas masquer le personnage.
- En haut à droite : vue tournante en 5 vues en pied, de gauche à droite : FACE, 3/4 FACE, PROFIL, DOS, 3/4 DOS. Fond sombre uni sans décor, chaque figurine posée sur un fin anneau lumineux orange érable au sol. Les 5 figurines entières (de la pointe de la tête ou du chapeau jusqu'aux pieds), à la même échelle, pieds sur la même ligne, sommets à la même hauteur. Pose neutre identique sur les 5 vues : debout droit, bras un peu écartés du corps, lames tenues vers le bas, bras légèrement écartés.
- Au centre : grille de 8 gros plans (2 colonnes × 4 lignes) dans des cadres arrondis à bord fin orange érable : yeux rouges et bandeau ; les deux lames ; nœud de ceinture ; puis dos de la tête ou de la coiffe, épaule et col, mains, pieds ou chaussures, détail du dos.
- À droite : panneau encadré avec la même pose en fil de fer blanc (maillage visible) sur fond sombre, les indications « ≈ tris », « ≈ verts », « 1 texture (PBR) 2048 × 2048 », et 3 vignettes de textures empilées (albedo dépliée, normal map bleue, roughness en gris).

CONTRAINTES DE COHÉRENCE (prioritaires) :
- Le même personnage, strictement identique sur la grande pose, les 5 vues, les gros plans et le fil de fer : mêmes couleurs, mêmes motifs, mêmes accessoires, du même côté du corps.
- Mêmes proportions sur les 5 vues (même hauteur totale, même taille de tête, même largeur d'épaules). Même capuche/cagoule et même longueur d'écharpe sur les 5 vues. Une vue où la coiffe, le chapeau ou l'arme change de taille rend la fiche inutilisable : c'est le défaut à éviter en priorité.
- Les 5 vues sont de vraies rotations orthographiques du même modèle (pas de perspective différente, pas de pose différente).
- Aucun texte, chiffre, flèche ni étiquette sur les 5 vues et sur les gros plans ; le texte n'apparaît que dans le bandeau, le bloc nom et le panneau fil de fer.
- Ne recopie pas la carte de la planche ni ses petites vignettes (elles sont parfois différentes du personnage) : suis la grande vue de la carte.
```

### Prompt (EN)

```text
Use the attached board (bestiary "3. ÉRABLES") as reference. The character is the one on the card "NINJA AUX DEUX LAMES" (role COMMUN, internal genre "kappa").

Create its individual model sheet, a single landscape image 1536×1024, in exactly the same style and layout as the world 1 (Archipel) sheets: stylized 3D chibi figurine render, soft studio lighting, dark near-black background.

CHARACTER (follow exactly, as it appears in the large view of the board):
Twin-blade ninja: chibi ninja in black, black hood with a red gold-patterned headband tied at the back in long floating tails, black mask, red eyes. Red scarf, arm guards, red-brown belt, black trousers. Two straight-bladed ninjatō, one in each hand.

LAYOUT:
- Top left: slanted maple orange banner with a small icon and the text "MONDE 3 - ÉRABLES". Below: small square face portrait, the name "NINJA AUX DEUX LAMES" in large white capitals, a role tag "COMMUN", and a line "♥ — PV".
- Left column, full height: large dynamic 3/4 pose (legs apart, both blades extended to each side), in a world setting: the village under autumn maples: red and orange maple trees, red lacquered wooden bridge, temple roofs, lanterns, falling maple leaves, late-afternoon light. The setting must not hide the character.
- Top right: 5-view full-body turnaround, left to right: FRONT, 3/4 FRONT, SIDE, BACK, 3/4 BACK. Plain dark background with no scenery, each figurine standing on a thin glowing maple orange ring on the floor. All 5 figurines complete (from the top of the head or hat down to the feet), same scale, feet on the same line, tops at the same height. Identical neutral pose in all 5 views: standing straight, arms slightly away from the body, blades held down, arms slightly apart.
- Centre: grid of 8 close-ups (2 columns × 4 rows) in rounded frames with a thin maple orange border: red eyes and headband; the two blades; belt knot; then back of the head or headgear, shoulder and collar, hands, feet or shoes, back detail.
- Right: framed panel with the same pose as a white wireframe (visible mesh) on a dark background, the labels "≈ tris", "≈ verts", "1 texture (PBR) 2048 × 2048", and 3 stacked texture thumbnails (unwrapped albedo, blue normal map, grey roughness).

CONSISTENCY RULES (top priority):
- The same character, strictly identical in the large pose, the 5 views, the close-ups and the wireframe: same colours, same patterns, same accessories, on the same side of the body.
- Same proportions in all 5 views (same total height, same head size, same shoulder width). Same hood and same scarf length in all 5 views. A view where the headgear, hat or weapon changes size makes the sheet unusable: this is the defect to avoid first.
- The 5 views are true orthographic rotations of the same model (no different perspective, no different pose).
- No text, numbers, arrows or labels on the 5 views or the close-ups; text only appears in the banner, the name block and the wireframe panel.
- Do not copy the board card or its small thumbnails (they sometimes differ from the character): follow the card's large view.
```

---

## SAMOURAÏ ROUGE : `fiches/brute.png`

Rôle : COMMUN · découpe : `decoupes/brute.png`

### Prompt (FR)

```text
Utilise la planche jointe (bestiaire « 3. ÉRABLES ») comme référence. Le personnage est celui de la carte « SAMOURAÏ ROUGE » (rôle COMMUN, genre interne « brute »).

Crée sa fiche modèle individuelle, une seule image paysage 1536×1024, dans exactement le même style et la même mise en page que les fiches du monde 1 (Archipel) : rendu 3D stylisé façon figurine chibi, éclairage doux de studio, fond sombre presque noir.

PERSONNAGE (à respecter exactement, tel qu'il apparaît sur la grande vue de la planche) :
Samouraï rouge : samouraï chibi en armure laquée rouge à lamelles bordées d'or (dō, sode, kusazuri), kabuto rouge orné d'un maedate doré en feuille d'érable, menpo rouge sur le bas du visage, yeux sombres déterminés. Écharpe rouge, ceinture dorée, jambières rouges. Katana dans la main gauche.

MISE EN PAGE :
- En haut à gauche : bandeau incliné couleur orange érable avec une petite icône et le texte « MONDE 3 - ÉRABLES ». Dessous : petit portrait carré du visage, le nom « SAMOURAÏ ROUGE » en grandes capitales blanches, une étiquette de rôle « COMMUN », et une ligne « ♥ — PV ».
- Colonne de gauche, sur toute la hauteur : grande pose 3/4 dynamique (garde basse, katana pointé vers l'avant), dans un décor du monde : le village sous les érables d'automne : érables rouges et orange, pont de bois laqué rouge, toits de temple, lanternes, feuilles d'érable qui tombent, lumière de fin d'après-midi. Le décor ne doit pas masquer le personnage.
- En haut à droite : vue tournante en 5 vues en pied, de gauche à droite : FACE, 3/4 FACE, PROFIL, DOS, 3/4 DOS. Fond sombre uni sans décor, chaque figurine posée sur un fin anneau lumineux orange érable au sol. Les 5 figurines entières (de la pointe de la tête ou du chapeau jusqu'aux pieds), à la même échelle, pieds sur la même ligne, sommets à la même hauteur. Pose neutre identique sur les 5 vues : debout droit, bras un peu écartés du corps, katana tenu lame vers le bas.
- Au centre : grille de 8 gros plans (2 colonnes × 4 lignes) dans des cadres arrondis à bord fin orange érable : visage sous le kabuto ; lamelles rouges de l'armure ; épaulière et cordons ; puis dos de la tête ou de la coiffe, épaule et col, mains, pieds ou chaussures, détail du dos.
- À droite : panneau encadré avec la même pose en fil de fer blanc (maillage visible) sur fond sombre, les indications « ≈ tris », « ≈ verts », « 1 texture (PBR) 2048 × 2048 », et 3 vignettes de textures empilées (albedo dépliée, normal map bleue, roughness en gris).

CONTRAINTES DE COHÉRENCE (prioritaires) :
- Le même personnage, strictement identique sur la grande pose, les 5 vues, les gros plans et le fil de fer : mêmes couleurs, mêmes motifs, mêmes accessoires, du même côté du corps.
- Mêmes proportions sur les 5 vues (même hauteur totale, même taille de tête, même largeur d'épaules). Même kabuto et même maedate (taille identique) sur les 5 vues. Une vue où la coiffe, le chapeau ou l'arme change de taille rend la fiche inutilisable : c'est le défaut à éviter en priorité.
- Les 5 vues sont de vraies rotations orthographiques du même modèle (pas de perspective différente, pas de pose différente).
- Aucun texte, chiffre, flèche ni étiquette sur les 5 vues et sur les gros plans ; le texte n'apparaît que dans le bandeau, le bloc nom et le panneau fil de fer.
- Ne recopie pas la carte de la planche ni ses petites vignettes (elles sont parfois différentes du personnage) : suis la grande vue de la carte.
```

### Prompt (EN)

```text
Use the attached board (bestiary "3. ÉRABLES") as reference. The character is the one on the card "SAMOURAÏ ROUGE" (role COMMUN, internal genre "brute").

Create its individual model sheet, a single landscape image 1536×1024, in exactly the same style and layout as the world 1 (Archipel) sheets: stylized 3D chibi figurine render, soft studio lighting, dark near-black background.

CHARACTER (follow exactly, as it appears in the large view of the board):
Red samurai: chibi samurai in red lacquered armour with gold-edged lamellae (dō, sode, kusazuri), red kabuto with a gold maple-leaf maedate crest, red menpo over the lower face, dark determined eyes. Red scarf, gold belt, red greaves. Katana in the left hand.

LAYOUT:
- Top left: slanted maple orange banner with a small icon and the text "MONDE 3 - ÉRABLES". Below: small square face portrait, the name "SAMOURAÏ ROUGE" in large white capitals, a role tag "COMMUN", and a line "♥ — PV".
- Left column, full height: large dynamic 3/4 pose (low guard, katana pointing forward), in a world setting: the village under autumn maples: red and orange maple trees, red lacquered wooden bridge, temple roofs, lanterns, falling maple leaves, late-afternoon light. The setting must not hide the character.
- Top right: 5-view full-body turnaround, left to right: FRONT, 3/4 FRONT, SIDE, BACK, 3/4 BACK. Plain dark background with no scenery, each figurine standing on a thin glowing maple orange ring on the floor. All 5 figurines complete (from the top of the head or hat down to the feet), same scale, feet on the same line, tops at the same height. Identical neutral pose in all 5 views: standing straight, arms slightly away from the body, katana held blade down.
- Centre: grid of 8 close-ups (2 columns × 4 rows) in rounded frames with a thin maple orange border: face under the kabuto; red armour lamellae; shoulder guard and cords; then back of the head or headgear, shoulder and collar, hands, feet or shoes, back detail.
- Right: framed panel with the same pose as a white wireframe (visible mesh) on a dark background, the labels "≈ tris", "≈ verts", "1 texture (PBR) 2048 × 2048", and 3 stacked texture thumbnails (unwrapped albedo, blue normal map, grey roughness).

CONSISTENCY RULES (top priority):
- The same character, strictly identical in the large pose, the 5 views, the close-ups and the wireframe: same colours, same patterns, same accessories, on the same side of the body.
- Same proportions in all 5 views (same total height, same head size, same shoulder width). Same kabuto and same crest (identical size) in all 5 views. A view where the headgear, hat or weapon changes size makes the sheet unusable: this is the defect to avoid first.
- The 5 views are true orthographic rotations of the same model (no different perspective, no different pose).
- No text, numbers, arrows or labels on the 5 views or the close-ups; text only appears in the banner, the name block and the wireframe panel.
- Do not copy the board card or its small thumbnails (they sometimes differ from the character): follow the card's large view.
```

---

## PORTE-PAVOIS : `fiches/tate.png`

Rôle : COMMUN · découpe : `decoupes/tate.png`

### Prompt (FR)

```text
Utilise la planche jointe (bestiaire « 3. ÉRABLES ») comme référence. Le personnage est celui de la carte « PORTE-PAVOIS » (rôle COMMUN, genre interne « tate »).

Crée sa fiche modèle individuelle, une seule image paysage 1536×1024, dans exactement le même style et la même mise en page que les fiches du monde 1 (Archipel) : rendu 3D stylisé façon figurine chibi, éclairage doux de studio, fond sombre presque noir.

PERSONNAGE (à respecter exactement, tel qu'il apparaît sur la grande vue de la planche) :
Porte-pavois : ninja chibi trapu, bonnet rouge, masque noir, yeux rouges, cape rouge sur les épaules, tenue noire. Grand pavois rectangulaire en planches de bois rouge cerclé de métal doré, orné d'une feuille d'érable orange, tenu devant lui au bras gauche.

MISE EN PAGE :
- En haut à gauche : bandeau incliné couleur orange érable avec une petite icône et le texte « MONDE 3 - ÉRABLES ». Dessous : petit portrait carré du visage, le nom « PORTE-PAVOIS » en grandes capitales blanches, une étiquette de rôle « COMMUN », et une ligne « ♥ — PV ».
- Colonne de gauche, sur toute la hauteur : grande pose 3/4 dynamique (accroupi derrière son pavois), dans un décor du monde : le village sous les érables d'automne : érables rouges et orange, pont de bois laqué rouge, toits de temple, lanternes, feuilles d'érable qui tombent, lumière de fin d'après-midi. Le décor ne doit pas masquer le personnage.
- En haut à droite : vue tournante en 5 vues en pied, de gauche à droite : FACE, 3/4 FACE, PROFIL, DOS, 3/4 DOS. Fond sombre uni sans décor, chaque figurine posée sur un fin anneau lumineux orange érable au sol. Les 5 figurines entières (de la pointe de la tête ou du chapeau jusqu'aux pieds), à la même échelle, pieds sur la même ligne, sommets à la même hauteur. Pose neutre identique sur les 5 vues : debout droit, bras un peu écartés du corps, pavois tenu de côté au bras gauche pour laisser voir le corps.
- Au centre : grille de 8 gros plans (2 colonnes × 4 lignes) dans des cadres arrondis à bord fin orange érable : yeux sous le bonnet ; feuille d'érable du pavois ; ceinture et cape ; puis dos de la tête ou de la coiffe, épaule et col, mains, pieds ou chaussures, détail du dos.
- À droite : panneau encadré avec la même pose en fil de fer blanc (maillage visible) sur fond sombre, les indications « ≈ tris », « ≈ verts », « 1 texture (PBR) 2048 × 2048 », et 3 vignettes de textures empilées (albedo dépliée, normal map bleue, roughness en gris).

CONTRAINTES DE COHÉRENCE (prioritaires) :
- Le même personnage, strictement identique sur la grande pose, les 5 vues, les gros plans et le fil de fer : mêmes couleurs, mêmes motifs, mêmes accessoires, du même côté du corps.
- Mêmes proportions sur les 5 vues (même hauteur totale, même taille de tête, même largeur d'épaules). Même taille de pavois sur les 5 vues. Une vue où la coiffe, le chapeau ou l'arme change de taille rend la fiche inutilisable : c'est le défaut à éviter en priorité.
- Les 5 vues sont de vraies rotations orthographiques du même modèle (pas de perspective différente, pas de pose différente).
- Aucun texte, chiffre, flèche ni étiquette sur les 5 vues et sur les gros plans ; le texte n'apparaît que dans le bandeau, le bloc nom et le panneau fil de fer.
- Ne recopie pas la carte de la planche ni ses petites vignettes (elles sont parfois différentes du personnage) : suis la grande vue de la carte.
```

### Prompt (EN)

```text
Use the attached board (bestiary "3. ÉRABLES") as reference. The character is the one on the card "PORTE-PAVOIS" (role COMMUN, internal genre "tate").

Create its individual model sheet, a single landscape image 1536×1024, in exactly the same style and layout as the world 1 (Archipel) sheets: stylized 3D chibi figurine render, soft studio lighting, dark near-black background.

CHARACTER (follow exactly, as it appears in the large view of the board):
Pavise bearer: stocky chibi ninja, red cap, black mask, red eyes, red cape over the shoulders, black outfit. Big rectangular pavise of red wooden planks framed in gold metal, decorated with an orange maple leaf, held in front on the left arm.

LAYOUT:
- Top left: slanted maple orange banner with a small icon and the text "MONDE 3 - ÉRABLES". Below: small square face portrait, the name "PORTE-PAVOIS" in large white capitals, a role tag "COMMUN", and a line "♥ — PV".
- Left column, full height: large dynamic 3/4 pose (crouched behind his pavise), in a world setting: the village under autumn maples: red and orange maple trees, red lacquered wooden bridge, temple roofs, lanterns, falling maple leaves, late-afternoon light. The setting must not hide the character.
- Top right: 5-view full-body turnaround, left to right: FRONT, 3/4 FRONT, SIDE, BACK, 3/4 BACK. Plain dark background with no scenery, each figurine standing on a thin glowing maple orange ring on the floor. All 5 figurines complete (from the top of the head or hat down to the feet), same scale, feet on the same line, tops at the same height. Identical neutral pose in all 5 views: standing straight, arms slightly away from the body, pavise held to the side on the left arm so the body stays visible.
- Centre: grid of 8 close-ups (2 columns × 4 rows) in rounded frames with a thin maple orange border: eyes under the cap; maple leaf on the pavise; belt and cape; then back of the head or headgear, shoulder and collar, hands, feet or shoes, back detail.
- Right: framed panel with the same pose as a white wireframe (visible mesh) on a dark background, the labels "≈ tris", "≈ verts", "1 texture (PBR) 2048 × 2048", and 3 stacked texture thumbnails (unwrapped albedo, blue normal map, grey roughness).

CONSISTENCY RULES (top priority):
- The same character, strictly identical in the large pose, the 5 views, the close-ups and the wireframe: same colours, same patterns, same accessories, on the same side of the body.
- Same proportions in all 5 views (same total height, same head size, same shoulder width). Same pavise size in all 5 views. A view where the headgear, hat or weapon changes size makes the sheet unusable: this is the defect to avoid first.
- The 5 views are true orthographic rotations of the same model (no different perspective, no different pose).
- No text, numbers, arrows or labels on the 5 views or the close-ups; text only appears in the banner, the name block and the wireframe panel.
- Do not copy the board card or its small thumbnails (they sometimes differ from the character): follow the card's large view.
```

---

## NINJA NOYÉ : `fiches/funa.png`

Rôle : COMMUN · découpe : `decoupes/funa.png`

### Prompt (FR)

```text
Utilise la planche jointe (bestiaire « 3. ÉRABLES ») comme référence. Le personnage est celui de la carte « NINJA NOYÉ » (rôle COMMUN, genre interne « funa »).

Crée sa fiche modèle individuelle, une seule image paysage 1536×1024, dans exactement le même style et la même mise en page que les fiches du monde 1 (Archipel) : rendu 3D stylisé façon figurine chibi, éclairage doux de studio, fond sombre presque noir.

PERSONNAGE (à respecter exactement, tel qu'il apparaît sur la grande vue de la planche) :
Ninja noyé : spectre chibi à la peau gris-bleu, yeux bleus lumineux, longs cheveux gris raides, chapeau conique de paille brun usé. Tenue de ninja gris anthracite en lambeaux, ceinture à boucle de métal, bandes aux poignets. Bâton de bois recourbé terminé par un anneau, dans la main gauche.

MISE EN PAGE :
- En haut à gauche : bandeau incliné couleur orange érable avec une petite icône et le texte « MONDE 3 - ÉRABLES ». Dessous : petit portrait carré du visage, le nom « NINJA NOYÉ » en grandes capitales blanches, une étiquette de rôle « COMMUN », et une ligne « ♥ — PV ».
- Colonne de gauche, sur toute la hauteur : grande pose 3/4 dynamique (il avance en s'appuyant sur son bâton, lambeaux flottants), dans un décor du monde : le village sous les érables d'automne : érables rouges et orange, pont de bois laqué rouge, toits de temple, lanternes, feuilles d'érable qui tombent, lumière de fin d'après-midi. Le décor ne doit pas masquer le personnage.
- En haut à droite : vue tournante en 5 vues en pied, de gauche à droite : FACE, 3/4 FACE, PROFIL, DOS, 3/4 DOS. Fond sombre uni sans décor, chaque figurine posée sur un fin anneau lumineux orange érable au sol. Les 5 figurines entières (de la pointe de la tête ou du chapeau jusqu'aux pieds), à la même échelle, pieds sur la même ligne, sommets à la même hauteur. Pose neutre identique sur les 5 vues : debout droit, bras un peu écartés du corps, bâton vertical dans la main gauche.
- Au centre : grille de 8 gros plans (2 colonnes × 4 lignes) dans des cadres arrondis à bord fin orange érable : visage aux yeux lumineux ; bas de tenue déchiqueté ; lambeaux de la manche ; puis dos de la tête ou de la coiffe, épaule et col, mains, pieds ou chaussures, détail du dos.
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
Use the attached board (bestiary "3. ÉRABLES") as reference. The character is the one on the card "NINJA NOYÉ" (role COMMUN, internal genre "funa").

Create its individual model sheet, a single landscape image 1536×1024, in exactly the same style and layout as the world 1 (Archipel) sheets: stylized 3D chibi figurine render, soft studio lighting, dark near-black background.

CHARACTER (follow exactly, as it appears in the large view of the board):
Drowned ninja: chibi ghost with grey-blue skin, glowing blue eyes, long straight grey hair, worn brown straw conical hat. Tattered charcoal-grey ninja outfit, belt with metal buckle, wrist wraps. Curved wooden staff ending in a ring, in the left hand.

LAYOUT:
- Top left: slanted maple orange banner with a small icon and the text "MONDE 3 - ÉRABLES". Below: small square face portrait, the name "NINJA NOYÉ" in large white capitals, a role tag "COMMUN", and a line "♥ — PV".
- Left column, full height: large dynamic 3/4 pose (advancing leaning on his staff, rags floating), in a world setting: the village under autumn maples: red and orange maple trees, red lacquered wooden bridge, temple roofs, lanterns, falling maple leaves, late-afternoon light. The setting must not hide the character.
- Top right: 5-view full-body turnaround, left to right: FRONT, 3/4 FRONT, SIDE, BACK, 3/4 BACK. Plain dark background with no scenery, each figurine standing on a thin glowing maple orange ring on the floor. All 5 figurines complete (from the top of the head or hat down to the feet), same scale, feet on the same line, tops at the same height. Identical neutral pose in all 5 views: standing straight, arms slightly away from the body, staff vertical in the left hand.
- Centre: grid of 8 close-ups (2 columns × 4 rows) in rounded frames with a thin maple orange border: face with glowing eyes; shredded hem; tattered sleeve; then back of the head or headgear, shoulder and collar, hands, feet or shoes, back detail.
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
Utilise la planche jointe (bestiaire « 3. ÉRABLES ») comme référence. Le personnage est celui de la carte « SHINOBI » (rôle PROPRE AU MONDE, genre interne « shinobi »).

Crée sa fiche modèle individuelle, une seule image paysage 1536×1024, dans exactement le même style et la même mise en page que les fiches du monde 1 (Archipel) : rendu 3D stylisé façon figurine chibi, éclairage doux de studio, fond sombre presque noir.

PERSONNAGE (à respecter exactement, tel qu'il apparaît sur la grande vue de la planche) :
Shinobi : ninja chibi en tenue noire, cagoule noire, bandeau rouge à motif doré, masque noir, yeux rouges. Longue écharpe rouge qui flotte, ceinture brune à boucle dorée, protège-bras. Shuriken d'acier à plusieurs branches dans la main droite.

MISE EN PAGE :
- En haut à gauche : bandeau incliné couleur orange érable avec une petite icône et le texte « MONDE 3 - ÉRABLES ». Dessous : petit portrait carré du visage, le nom « SHINOBI » en grandes capitales blanches, une étiquette de rôle « PROPRE AU MONDE », et une ligne « ♥ — PV ».
- Colonne de gauche, sur toute la hauteur : grande pose 3/4 dynamique (fente vers l'avant, bras tendu avec le shuriken), dans un décor du monde : le village sous les érables d'automne : érables rouges et orange, pont de bois laqué rouge, toits de temple, lanternes, feuilles d'érable qui tombent, lumière de fin d'après-midi. Le décor ne doit pas masquer le personnage.
- En haut à droite : vue tournante en 5 vues en pied, de gauche à droite : FACE, 3/4 FACE, PROFIL, DOS, 3/4 DOS. Fond sombre uni sans décor, chaque figurine posée sur un fin anneau lumineux orange érable au sol. Les 5 figurines entières (de la pointe de la tête ou du chapeau jusqu'aux pieds), à la même échelle, pieds sur la même ligne, sommets à la même hauteur. Pose neutre identique sur les 5 vues : debout droit, bras un peu écartés du corps, shuriken tenu à hauteur de hanche.
- Au centre : grille de 8 gros plans (2 colonnes × 4 lignes) dans des cadres arrondis à bord fin orange érable : yeux et bandeau ; shuriken d'acier ; nœud de cordelette ; puis dos de la tête ou de la coiffe, épaule et col, mains, pieds ou chaussures, détail du dos.
- À droite : panneau encadré avec la même pose en fil de fer blanc (maillage visible) sur fond sombre, les indications « ≈ tris », « ≈ verts », « 1 texture (PBR) 2048 × 2048 », et 3 vignettes de textures empilées (albedo dépliée, normal map bleue, roughness en gris).

CONTRAINTES DE COHÉRENCE (prioritaires) :
- Le même personnage, strictement identique sur la grande pose, les 5 vues, les gros plans et le fil de fer : mêmes couleurs, mêmes motifs, mêmes accessoires, du même côté du corps.
- Mêmes proportions sur les 5 vues (même hauteur totale, même taille de tête, même largeur d'épaules). Même capuche/cagoule et même longueur d'écharpe sur les 5 vues. Une vue où la coiffe, le chapeau ou l'arme change de taille rend la fiche inutilisable : c'est le défaut à éviter en priorité.
- Les 5 vues sont de vraies rotations orthographiques du même modèle (pas de perspective différente, pas de pose différente).
- Aucun texte, chiffre, flèche ni étiquette sur les 5 vues et sur les gros plans ; le texte n'apparaît que dans le bandeau, le bloc nom et le panneau fil de fer.
- Ne recopie pas la carte de la planche ni ses petites vignettes (elles sont parfois différentes du personnage) : suis la grande vue de la carte.
```

### Prompt (EN)

```text
Use the attached board (bestiary "3. ÉRABLES") as reference. The character is the one on the card "SHINOBI" (role PROPRE AU MONDE, internal genre "shinobi").

Create its individual model sheet, a single landscape image 1536×1024, in exactly the same style and layout as the world 1 (Archipel) sheets: stylized 3D chibi figurine render, soft studio lighting, dark near-black background.

CHARACTER (follow exactly, as it appears in the large view of the board):
Shinobi: chibi ninja in black, black hood, red gold-patterned headband, black mask, red eyes. Long floating red scarf, brown belt with gold buckle, arm guards. Multi-pointed steel shuriken in the right hand.

LAYOUT:
- Top left: slanted maple orange banner with a small icon and the text "MONDE 3 - ÉRABLES". Below: small square face portrait, the name "SHINOBI" in large white capitals, a role tag "PROPRE AU MONDE", and a line "♥ — PV".
- Left column, full height: large dynamic 3/4 pose (forward lunge, arm stretched with the shuriken), in a world setting: the village under autumn maples: red and orange maple trees, red lacquered wooden bridge, temple roofs, lanterns, falling maple leaves, late-afternoon light. The setting must not hide the character.
- Top right: 5-view full-body turnaround, left to right: FRONT, 3/4 FRONT, SIDE, BACK, 3/4 BACK. Plain dark background with no scenery, each figurine standing on a thin glowing maple orange ring on the floor. All 5 figurines complete (from the top of the head or hat down to the feet), same scale, feet on the same line, tops at the same height. Identical neutral pose in all 5 views: standing straight, arms slightly away from the body, shuriken held at hip height.
- Centre: grid of 8 close-ups (2 columns × 4 rows) in rounded frames with a thin maple orange border: eyes and headband; steel shuriken; cord knot; then back of the head or headgear, shoulder and collar, hands, feet or shoes, back detail.
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
Utilise la planche jointe (bestiaire « 3. ÉRABLES ») comme référence. Le personnage est celui de la carte « LANCEUR DE SHURIKEN » (rôle PROPRE AU MONDE, genre interne « shuriken »).

Crée sa fiche modèle individuelle, une seule image paysage 1536×1024, dans exactement le même style et la même mise en page que les fiches du monde 1 (Archipel) : rendu 3D stylisé façon figurine chibi, éclairage doux de studio, fond sombre presque noir.

PERSONNAGE (à respecter exactement, tel qu'il apparaît sur la grande vue de la planche) :
Lanceur de shuriken : ninja chibi en tenue noire, cagoule noire avec bandeau orange-doré à plaque, masque noir, yeux ambre. Écharpe rouge flottante, sangle et ceinture dorées. Shuriken doré à quatre branches dans la main gauche.

MISE EN PAGE :
- En haut à gauche : bandeau incliné couleur orange érable avec une petite icône et le texte « MONDE 3 - ÉRABLES ». Dessous : petit portrait carré du visage, le nom « LANCEUR DE SHURIKEN » en grandes capitales blanches, une étiquette de rôle « PROPRE AU MONDE », et une ligne « ♥ — PV ».
- Colonne de gauche, sur toute la hauteur : grande pose 3/4 dynamique (geste de lancer, shuriken doré en avant), dans un décor du monde : le village sous les érables d'automne : érables rouges et orange, pont de bois laqué rouge, toits de temple, lanternes, feuilles d'érable qui tombent, lumière de fin d'après-midi. Le décor ne doit pas masquer le personnage.
- En haut à droite : vue tournante en 5 vues en pied, de gauche à droite : FACE, 3/4 FACE, PROFIL, DOS, 3/4 DOS. Fond sombre uni sans décor, chaque figurine posée sur un fin anneau lumineux orange érable au sol. Les 5 figurines entières (de la pointe de la tête ou du chapeau jusqu'aux pieds), à la même échelle, pieds sur la même ligne, sommets à la même hauteur. Pose neutre identique sur les 5 vues : debout droit, bras un peu écartés du corps, shuriken tenu à hauteur de hanche.
- Au centre : grille de 8 gros plans (2 colonnes × 4 lignes) dans des cadres arrondis à bord fin orange érable : yeux et bandeau doré ; shuriken doré ; sacoche de ceinture ; puis dos de la tête ou de la coiffe, épaule et col, mains, pieds ou chaussures, détail du dos.
- À droite : panneau encadré avec la même pose en fil de fer blanc (maillage visible) sur fond sombre, les indications « ≈ tris », « ≈ verts », « 1 texture (PBR) 2048 × 2048 », et 3 vignettes de textures empilées (albedo dépliée, normal map bleue, roughness en gris).

CONTRAINTES DE COHÉRENCE (prioritaires) :
- Le même personnage, strictement identique sur la grande pose, les 5 vues, les gros plans et le fil de fer : mêmes couleurs, mêmes motifs, mêmes accessoires, du même côté du corps.
- Mêmes proportions sur les 5 vues (même hauteur totale, même taille de tête, même largeur d'épaules). Même capuche/cagoule et même longueur d'écharpe sur les 5 vues. Une vue où la coiffe, le chapeau ou l'arme change de taille rend la fiche inutilisable : c'est le défaut à éviter en priorité.
- Les 5 vues sont de vraies rotations orthographiques du même modèle (pas de perspective différente, pas de pose différente).
- Aucun texte, chiffre, flèche ni étiquette sur les 5 vues et sur les gros plans ; le texte n'apparaît que dans le bandeau, le bloc nom et le panneau fil de fer.
- Ne recopie pas la carte de la planche ni ses petites vignettes (elles sont parfois différentes du personnage) : suis la grande vue de la carte.
```

### Prompt (EN)

```text
Use the attached board (bestiary "3. ÉRABLES") as reference. The character is the one on the card "LANCEUR DE SHURIKEN" (role PROPRE AU MONDE, internal genre "shuriken").

Create its individual model sheet, a single landscape image 1536×1024, in exactly the same style and layout as the world 1 (Archipel) sheets: stylized 3D chibi figurine render, soft studio lighting, dark near-black background.

CHARACTER (follow exactly, as it appears in the large view of the board):
Shuriken thrower: chibi ninja in black, black hood with an orange-gold headband with a plate, black mask, amber eyes. Floating red scarf, gold strap and belt. Gold four-pointed shuriken in the left hand.

LAYOUT:
- Top left: slanted maple orange banner with a small icon and the text "MONDE 3 - ÉRABLES". Below: small square face portrait, the name "LANCEUR DE SHURIKEN" in large white capitals, a role tag "PROPRE AU MONDE", and a line "♥ — PV".
- Left column, full height: large dynamic 3/4 pose (throwing motion, gold shuriken forward), in a world setting: the village under autumn maples: red and orange maple trees, red lacquered wooden bridge, temple roofs, lanterns, falling maple leaves, late-afternoon light. The setting must not hide the character.
- Top right: 5-view full-body turnaround, left to right: FRONT, 3/4 FRONT, SIDE, BACK, 3/4 BACK. Plain dark background with no scenery, each figurine standing on a thin glowing maple orange ring on the floor. All 5 figurines complete (from the top of the head or hat down to the feet), same scale, feet on the same line, tops at the same height. Identical neutral pose in all 5 views: standing straight, arms slightly away from the body, shuriken held at hip height.
- Centre: grid of 8 close-ups (2 columns × 4 rows) in rounded frames with a thin maple orange border: eyes and gold headband; gold shuriken; belt pouch; then back of the head or headgear, shoulder and collar, hands, feet or shoes, back detail.
- Right: framed panel with the same pose as a white wireframe (visible mesh) on a dark background, the labels "≈ tris", "≈ verts", "1 texture (PBR) 2048 × 2048", and 3 stacked texture thumbnails (unwrapped albedo, blue normal map, grey roughness).

CONSISTENCY RULES (top priority):
- The same character, strictly identical in the large pose, the 5 views, the close-ups and the wireframe: same colours, same patterns, same accessories, on the same side of the body.
- Same proportions in all 5 views (same total height, same head size, same shoulder width). Same hood and same scarf length in all 5 views. A view where the headgear, hat or weapon changes size makes the sheet unusable: this is the defect to avoid first.
- The 5 views are true orthographic rotations of the same model (no different perspective, no different pose).
- No text, numbers, arrows or labels on the 5 views or the close-ups; text only appears in the banner, the name block and the wireframe panel.
- Do not copy the board card or its small thumbnails (they sometimes differ from the character): follow the card's large view.
```

---

## KUNOICHI : `fiches/kunoichi.png`

Rôle : PROPRE AU MONDE · découpe : `decoupes/kunoichi.png`

### Prompt (FR)

```text
Utilise la planche jointe (bestiaire « 3. ÉRABLES ») comme référence. Le personnage est celui de la carte « KUNOICHI » (rôle PROPRE AU MONDE, genre interne « kunoichi »).

Crée sa fiche modèle individuelle, une seule image paysage 1536×1024, dans exactement le même style et la même mise en page que les fiches du monde 1 (Archipel) : rendu 3D stylisé façon figurine chibi, éclairage doux de studio, fond sombre presque noir.

PERSONNAGE (à respecter exactement, tel qu'il apparaît sur la grande vue de la planche) :
Kunoichi : jeune femme ninja chibi, cheveux noirs en chignon haut noué d'un ruban rouge, frange, grands yeux rouges, air résolu. Écharpe rouge, tenue noire ajustée à liserés rouges, ceinture rouge, gants noirs. Une lame courte dans chaque main (wakizashi et kunai).

MISE EN PAGE :
- En haut à gauche : bandeau incliné couleur orange érable avec une petite icône et le texte « MONDE 3 - ÉRABLES ». Dessous : petit portrait carré du visage, le nom « KUNOICHI » en grandes capitales blanches, une étiquette de rôle « PROPRE AU MONDE », et une ligne « ♥ — PV ».
- Colonne de gauche, sur toute la hauteur : grande pose 3/4 dynamique (en garde basse, lames croisées), dans un décor du monde : le village sous les érables d'automne : érables rouges et orange, pont de bois laqué rouge, toits de temple, lanternes, feuilles d'érable qui tombent, lumière de fin d'après-midi. Le décor ne doit pas masquer le personnage.
- En haut à droite : vue tournante en 5 vues en pied, de gauche à droite : FACE, 3/4 FACE, PROFIL, DOS, 3/4 DOS. Fond sombre uni sans décor, chaque figurine posée sur un fin anneau lumineux orange érable au sol. Les 5 figurines entières (de la pointe de la tête ou du chapeau jusqu'aux pieds), à la même échelle, pieds sur la même ligne, sommets à la même hauteur. Pose neutre identique sur les 5 vues : debout droit, bras un peu écartés du corps, lames tenues vers le bas, bras écartés.
- Au centre : grille de 8 gros plans (2 colonnes × 4 lignes) dans des cadres arrondis à bord fin orange érable : visage et yeux rouges ; feuille d'érable rouge ; ruban et chignon ; puis dos de la tête ou de la coiffe, épaule et col, mains, pieds ou chaussures, détail du dos.
- À droite : panneau encadré avec la même pose en fil de fer blanc (maillage visible) sur fond sombre, les indications « ≈ tris », « ≈ verts », « 1 texture (PBR) 2048 × 2048 », et 3 vignettes de textures empilées (albedo dépliée, normal map bleue, roughness en gris).

CONTRAINTES DE COHÉRENCE (prioritaires) :
- Le même personnage, strictement identique sur la grande pose, les 5 vues, les gros plans et le fil de fer : mêmes couleurs, mêmes motifs, mêmes accessoires, du même côté du corps.
- Mêmes proportions sur les 5 vues (même hauteur totale, même taille de tête, même largeur d'épaules). Même chignon et même ruban sur les 5 vues. Une vue où la coiffe, le chapeau ou l'arme change de taille rend la fiche inutilisable : c'est le défaut à éviter en priorité.
- Les 5 vues sont de vraies rotations orthographiques du même modèle (pas de perspective différente, pas de pose différente).
- Aucun texte, chiffre, flèche ni étiquette sur les 5 vues et sur les gros plans ; le texte n'apparaît que dans le bandeau, le bloc nom et le panneau fil de fer.
- Ne recopie pas la carte de la planche ni ses petites vignettes (elles sont parfois différentes du personnage) : suis la grande vue de la carte.
```

### Prompt (EN)

```text
Use the attached board (bestiary "3. ÉRABLES") as reference. The character is the one on the card "KUNOICHI" (role PROPRE AU MONDE, internal genre "kunoichi").

Create its individual model sheet, a single landscape image 1536×1024, in exactly the same style and layout as the world 1 (Archipel) sheets: stylized 3D chibi figurine render, soft studio lighting, dark near-black background.

CHARACTER (follow exactly, as it appears in the large view of the board):
Kunoichi: chibi young female ninja, black hair in a high bun tied with a red ribbon, bangs, big red eyes, resolute look. Red scarf, fitted black outfit with red trim, red belt, black gloves. A short blade in each hand (wakizashi and kunai).

LAYOUT:
- Top left: slanted maple orange banner with a small icon and the text "MONDE 3 - ÉRABLES". Below: small square face portrait, the name "KUNOICHI" in large white capitals, a role tag "PROPRE AU MONDE", and a line "♥ — PV".
- Left column, full height: large dynamic 3/4 pose (low guard, blades crossed), in a world setting: the village under autumn maples: red and orange maple trees, red lacquered wooden bridge, temple roofs, lanterns, falling maple leaves, late-afternoon light. The setting must not hide the character.
- Top right: 5-view full-body turnaround, left to right: FRONT, 3/4 FRONT, SIDE, BACK, 3/4 BACK. Plain dark background with no scenery, each figurine standing on a thin glowing maple orange ring on the floor. All 5 figurines complete (from the top of the head or hat down to the feet), same scale, feet on the same line, tops at the same height. Identical neutral pose in all 5 views: standing straight, arms slightly away from the body, blades held down, arms apart.
- Centre: grid of 8 close-ups (2 columns × 4 rows) in rounded frames with a thin maple orange border: face and red eyes; red maple leaf; ribbon and bun; then back of the head or headgear, shoulder and collar, hands, feet or shoes, back detail.
- Right: framed panel with the same pose as a white wireframe (visible mesh) on a dark background, the labels "≈ tris", "≈ verts", "1 texture (PBR) 2048 × 2048", and 3 stacked texture thumbnails (unwrapped albedo, blue normal map, grey roughness).

CONSISTENCY RULES (top priority):
- The same character, strictly identical in the large pose, the 5 views, the close-ups and the wireframe: same colours, same patterns, same accessories, on the same side of the body.
- Same proportions in all 5 views (same total height, same head size, same shoulder width). Same bun and same ribbon in all 5 views. A view where the headgear, hat or weapon changes size makes the sheet unusable: this is the defect to avoid first.
- The 5 views are true orthographic rotations of the same model (no different perspective, no different pose).
- No text, numbers, arrows or labels on the 5 views or the close-ups; text only appears in the banner, the name block and the wireframe panel.
- Do not copy the board card or its small thumbnails (they sometimes differ from the character): follow the card's large view.
```

---

## KAMAITACHI : `fiches/kamaitachi.png`

Rôle : PROPRE AU MONDE · découpe : `decoupes/kamaitachi.png`

### Prompt (FR)

```text
Utilise la planche jointe (bestiaire « 3. ÉRABLES ») comme référence. Le personnage est celui de la carte « KAMAITACHI » (rôle PROPRE AU MONDE, genre interne « kamaitachi », (planche : « kunoichi », erreur)).

Crée sa fiche modèle individuelle, une seule image paysage 1536×1024, dans exactement le même style et la même mise en page que les fiches du monde 1 (Archipel) : rendu 3D stylisé façon figurine chibi, éclairage doux de studio, fond sombre presque noir.

PERSONNAGE (à respecter exactement, tel qu'il apparaît sur la grande vue de la planche) :
Kamaitachi (habit Érables) : ninja chibi portant un masque de kitsune blanc aux marques rouges et oreilles pointues, cheveux noirs en chignon, écharpe rouge, tenue noire et rouge à ceinture dorée. Deux faucilles : une à lame rouge en croissant (main droite), une à lame argentée (main gauche). Note : la planche indique par erreur genre « kunoichi » ; le genre interne est « kamaitachi ».

MISE EN PAGE :
- En haut à gauche : bandeau incliné couleur orange érable avec une petite icône et le texte « MONDE 3 - ÉRABLES ». Dessous : petit portrait carré du visage, le nom « KAMAITACHI » en grandes capitales blanches, une étiquette de rôle « PROPRE AU MONDE », et une ligne « ♥ — PV ».
- Colonne de gauche, sur toute la hauteur : grande pose 3/4 dynamique (fente tournoyante, les deux faucilles en arc), dans un décor du monde : le village sous les érables d'automne : érables rouges et orange, pont de bois laqué rouge, toits de temple, lanternes, feuilles d'érable qui tombent, lumière de fin d'après-midi. Le décor ne doit pas masquer le personnage.
- En haut à droite : vue tournante en 5 vues en pied, de gauche à droite : FACE, 3/4 FACE, PROFIL, DOS, 3/4 DOS. Fond sombre uni sans décor, chaque figurine posée sur un fin anneau lumineux orange érable au sol. Les 5 figurines entières (de la pointe de la tête ou du chapeau jusqu'aux pieds), à la même échelle, pieds sur la même ligne, sommets à la même hauteur. Pose neutre identique sur les 5 vues : debout droit, bras un peu écartés du corps, faucilles tenues lames vers le bas, bras écartés.
- Au centre : grille de 8 gros plans (2 colonnes × 4 lignes) dans des cadres arrondis à bord fin orange érable : masque de kitsune ; lame argentée ; poignée et cordons ; puis dos de la tête ou de la coiffe, épaule et col, mains, pieds ou chaussures, détail du dos.
- À droite : panneau encadré avec la même pose en fil de fer blanc (maillage visible) sur fond sombre, les indications « ≈ tris », « ≈ verts », « 1 texture (PBR) 2048 × 2048 », et 3 vignettes de textures empilées (albedo dépliée, normal map bleue, roughness en gris).

CONTRAINTES DE COHÉRENCE (prioritaires) :
- Le même personnage, strictement identique sur la grande pose, les 5 vues, les gros plans et le fil de fer : mêmes couleurs, mêmes motifs, mêmes accessoires, du même côté du corps.
- Mêmes proportions sur les 5 vues (même hauteur totale, même taille de tête, même largeur d'épaules). Même masque, mêmes oreilles sur les 5 vues. Une vue où la coiffe, le chapeau ou l'arme change de taille rend la fiche inutilisable : c'est le défaut à éviter en priorité.
- Les 5 vues sont de vraies rotations orthographiques du même modèle (pas de perspective différente, pas de pose différente).
- Aucun texte, chiffre, flèche ni étiquette sur les 5 vues et sur les gros plans ; le texte n'apparaît que dans le bandeau, le bloc nom et le panneau fil de fer.
- Ne recopie pas la carte de la planche ni ses petites vignettes (elles sont parfois différentes du personnage) : suis la grande vue de la carte.
```

### Prompt (EN)

```text
Use the attached board (bestiary "3. ÉRABLES") as reference. The character is the one on the card "KAMAITACHI" (role PROPRE AU MONDE, internal genre "kamaitachi").

Create its individual model sheet, a single landscape image 1536×1024, in exactly the same style and layout as the world 1 (Archipel) sheets: stylized 3D chibi figurine render, soft studio lighting, dark near-black background.

CHARACTER (follow exactly, as it appears in the large view of the board):
Kamaitachi (Maples outfit): chibi ninja wearing a white kitsune mask with red markings and pointed ears, black hair in a bun, red scarf, black and red outfit with gold belt. Two sickles: a red crescent blade (right hand) and a silver blade (left hand). Note: the board wrongly says genre "kunoichi"; the internal genre is "kamaitachi".

LAYOUT:
- Top left: slanted maple orange banner with a small icon and the text "MONDE 3 - ÉRABLES". Below: small square face portrait, the name "KAMAITACHI" in large white capitals, a role tag "PROPRE AU MONDE", and a line "♥ — PV".
- Left column, full height: large dynamic 3/4 pose (spinning slash, both sickles in an arc), in a world setting: the village under autumn maples: red and orange maple trees, red lacquered wooden bridge, temple roofs, lanterns, falling maple leaves, late-afternoon light. The setting must not hide the character.
- Top right: 5-view full-body turnaround, left to right: FRONT, 3/4 FRONT, SIDE, BACK, 3/4 BACK. Plain dark background with no scenery, each figurine standing on a thin glowing maple orange ring on the floor. All 5 figurines complete (from the top of the head or hat down to the feet), same scale, feet on the same line, tops at the same height. Identical neutral pose in all 5 views: standing straight, arms slightly away from the body, sickles held blades down, arms apart.
- Centre: grid of 8 close-ups (2 columns × 4 rows) in rounded frames with a thin maple orange border: kitsune mask; silver blade; grip and cords; then back of the head or headgear, shoulder and collar, hands, feet or shoes, back detail.
- Right: framed panel with the same pose as a white wireframe (visible mesh) on a dark background, the labels "≈ tris", "≈ verts", "1 texture (PBR) 2048 × 2048", and 3 stacked texture thumbnails (unwrapped albedo, blue normal map, grey roughness).

CONSISTENCY RULES (top priority):
- The same character, strictly identical in the large pose, the 5 views, the close-ups and the wireframe: same colours, same patterns, same accessories, on the same side of the body.
- Same proportions in all 5 views (same total height, same head size, same shoulder width). Same mask, same ears in all 5 views. A view where the headgear, hat or weapon changes size makes the sheet unusable: this is the defect to avoid first.
- The 5 views are true orthographic rotations of the same model (no different perspective, no different pose).
- No text, numbers, arrows or labels on the 5 views or the close-ups; text only appears in the banner, the name block and the wireframe panel.
- Do not copy the board card or its small thumbnails (they sometimes differ from the character): follow the card's large view.
```

---

## KONOHA-TENGU : `fiches/konoha.png`

Rôle : PROPRE AU MONDE · découpe : `decoupes/konoha.png`

### Prompt (FR)

```text
Utilise la planche jointe (bestiaire « 3. ÉRABLES ») comme référence. Le personnage est celui de la carte « KONOHA-TENGU » (rôle PROPRE AU MONDE, genre interne « konoha », (planche : « slanobi », erreur)).

Crée sa fiche modèle individuelle, une seule image paysage 1536×1024, dans exactement le même style et la même mise en page que les fiches du monde 1 (Archipel) : rendu 3D stylisé façon figurine chibi, éclairage doux de studio, fond sombre presque noir.

PERSONNAGE (à respecter exactement, tel qu'il apparaît sur la grande vue de la planche) :
Konoha-tengu : tengu-feuille chibi à tête d'oiseau rouge, long bec jaune pointu, œil vif, crête de plumes rouges et noires. Manteau-ailes fait de feuilles d'érable rouges et orange, tenue rouge sombre à ceinture dorée, serres. Petite lame (kunai) dans la main gauche. Note : la planche indique « slanobi » (faute) ; le genre interne est « konoha ».

MISE EN PAGE :
- En haut à gauche : bandeau incliné couleur orange érable avec une petite icône et le texte « MONDE 3 - ÉRABLES ». Dessous : petit portrait carré du visage, le nom « KONOHA-TENGU » en grandes capitales blanches, une étiquette de rôle « PROPRE AU MONDE », et une ligne « ♥ — PV ».
- Colonne de gauche, sur toute la hauteur : grande pose 3/4 dynamique (il déploie son manteau de feuilles, rafale de feuilles), dans un décor du monde : le village sous les érables d'automne : érables rouges et orange, pont de bois laqué rouge, toits de temple, lanternes, feuilles d'érable qui tombent, lumière de fin d'après-midi. Le décor ne doit pas masquer le personnage.
- En haut à droite : vue tournante en 5 vues en pied, de gauche à droite : FACE, 3/4 FACE, PROFIL, DOS, 3/4 DOS. Fond sombre uni sans décor, chaque figurine posée sur un fin anneau lumineux orange érable au sol. Les 5 figurines entières (de la pointe de la tête ou du chapeau jusqu'aux pieds), à la même échelle, pieds sur la même ligne, sommets à la même hauteur. Pose neutre identique sur les 5 vues : debout droit, bras un peu écartés du corps, manteau replié le long du corps, lame vers le bas.
- Au centre : grille de 8 gros plans (2 colonnes × 4 lignes) dans des cadres arrondis à bord fin orange érable : tête d'oiseau au bec jaune ; feuilles rouges du manteau ; feuille d'érable ; puis dos de la tête ou de la coiffe, épaule et col, mains, pieds ou chaussures, détail du dos.
- À droite : panneau encadré avec la même pose en fil de fer blanc (maillage visible) sur fond sombre, les indications « ≈ tris », « ≈ verts », « 1 texture (PBR) 2048 × 2048 », et 3 vignettes de textures empilées (albedo dépliée, normal map bleue, roughness en gris).

CONTRAINTES DE COHÉRENCE (prioritaires) :
- Le même personnage, strictement identique sur la grande pose, les 5 vues, les gros plans et le fil de fer : mêmes couleurs, mêmes motifs, mêmes accessoires, du même côté du corps.
- Mêmes proportions sur les 5 vues (même hauteur totale, même taille de tête, même largeur d'épaules). Même bec et même envergure du manteau sur les 5 vues. Une vue où la coiffe, le chapeau ou l'arme change de taille rend la fiche inutilisable : c'est le défaut à éviter en priorité.
- Les 5 vues sont de vraies rotations orthographiques du même modèle (pas de perspective différente, pas de pose différente).
- Aucun texte, chiffre, flèche ni étiquette sur les 5 vues et sur les gros plans ; le texte n'apparaît que dans le bandeau, le bloc nom et le panneau fil de fer.
- Ne recopie pas la carte de la planche ni ses petites vignettes (elles sont parfois différentes du personnage) : suis la grande vue de la carte.
```

### Prompt (EN)

```text
Use the attached board (bestiary "3. ÉRABLES") as reference. The character is the one on the card "KONOHA-TENGU" (role PROPRE AU MONDE, internal genre "konoha").

Create its individual model sheet, a single landscape image 1536×1024, in exactly the same style and layout as the world 1 (Archipel) sheets: stylized 3D chibi figurine render, soft studio lighting, dark near-black background.

CHARACTER (follow exactly, as it appears in the large view of the board):
Konoha-tengu: chibi leaf-tengu with a red bird head, long pointed yellow beak, sharp eye, crest of red and black feathers. Wing-cloak made of red and orange maple leaves, dark red outfit with gold belt, talons. Small blade (kunai) in the left hand. Note: the board says "slanobi" (typo); the internal genre is "konoha".

LAYOUT:
- Top left: slanted maple orange banner with a small icon and the text "MONDE 3 - ÉRABLES". Below: small square face portrait, the name "KONOHA-TENGU" in large white capitals, a role tag "PROPRE AU MONDE", and a line "♥ — PV".
- Left column, full height: large dynamic 3/4 pose (spreading its leaf cloak, gust of leaves), in a world setting: the village under autumn maples: red and orange maple trees, red lacquered wooden bridge, temple roofs, lanterns, falling maple leaves, late-afternoon light. The setting must not hide the character.
- Top right: 5-view full-body turnaround, left to right: FRONT, 3/4 FRONT, SIDE, BACK, 3/4 BACK. Plain dark background with no scenery, each figurine standing on a thin glowing maple orange ring on the floor. All 5 figurines complete (from the top of the head or hat down to the feet), same scale, feet on the same line, tops at the same height. Identical neutral pose in all 5 views: standing straight, arms slightly away from the body, cloak folded along the body, blade down.
- Centre: grid of 8 close-ups (2 columns × 4 rows) in rounded frames with a thin maple orange border: bird head with yellow beak; red leaves of the cloak; maple leaf; then back of the head or headgear, shoulder and collar, hands, feet or shoes, back detail.
- Right: framed panel with the same pose as a white wireframe (visible mesh) on a dark background, the labels "≈ tris", "≈ verts", "1 texture (PBR) 2048 × 2048", and 3 stacked texture thumbnails (unwrapped albedo, blue normal map, grey roughness).

CONSISTENCY RULES (top priority):
- The same character, strictly identical in the large pose, the 5 views, the close-ups and the wireframe: same colours, same patterns, same accessories, on the same side of the body.
- Same proportions in all 5 views (same total height, same head size, same shoulder width). Same beak and same cloak span in all 5 views. A view where the headgear, hat or weapon changes size makes the sheet unusable: this is the defect to avoid first.
- The 5 views are true orthographic rotations of the same model (no different perspective, no different pose).
- No text, numbers, arrows or labels on the 5 views or the close-ups; text only appears in the banner, the name block and the wireframe panel.
- Do not copy the board card or its small thumbnails (they sometimes differ from the character): follow the card's large view.
```

---

## MOINE TANUKI : `fiches/tanuki.png`

Rôle : REVENANT · découpe : `decoupes/tanuki.png`

### Prompt (FR)

```text
Utilise la planche jointe (bestiaire « 3. ÉRABLES ») comme référence. Le personnage est celui de la carte « MOINE TANUKI » (rôle REVENANT, genre interne « tanuki »).

Crée sa fiche modèle individuelle, une seule image paysage 1536×1024, dans exactement le même style et la même mise en page que les fiches du monde 1 (Archipel) : rendu 3D stylisé façon figurine chibi, éclairage doux de studio, fond sombre presque noir.

PERSONNAGE (à respecter exactement, tel qu'il apparaît sur la grande vue de la planche) :
Moine tanuki (revenant, habit Érables) : tanuki chibi rond au pelage brun, ventre crème, masque sombre autour des yeux, grand chapeau conique de paille. Collier-écharpe rouge-orangé noué avec glands, petite bourse, tenue brune. Lanterne de papier allumée (lumière chaude) dans la main droite.

MISE EN PAGE :
- En haut à gauche : bandeau incliné couleur orange érable avec une petite icône et le texte « MONDE 3 - ÉRABLES ». Dessous : petit portrait carré du visage, le nom « MOINE TANUKI » en grandes capitales blanches, une étiquette de rôle « REVENANT », et une ligne « ♥ — PV ».
- Colonne de gauche, sur toute la hauteur : grande pose 3/4 dynamique (il lève sa lanterne, feuilles d'érable autour), dans un décor du monde : le village sous les érables d'automne : érables rouges et orange, pont de bois laqué rouge, toits de temple, lanternes, feuilles d'érable qui tombent, lumière de fin d'après-midi. Le décor ne doit pas masquer le personnage.
- En haut à droite : vue tournante en 5 vues en pied, de gauche à droite : FACE, 3/4 FACE, PROFIL, DOS, 3/4 DOS. Fond sombre uni sans décor, chaque figurine posée sur un fin anneau lumineux orange érable au sol. Les 5 figurines entières (de la pointe de la tête ou du chapeau jusqu'aux pieds), à la même échelle, pieds sur la même ligne, sommets à la même hauteur. Pose neutre identique sur les 5 vues : debout droit, bras un peu écartés du corps, lanterne pendue à la main droite.
- Au centre : grille de 8 gros plans (2 colonnes × 4 lignes) dans des cadres arrondis à bord fin orange érable : visage du tanuki ; gourde ; nœud du collier ; puis dos de la tête ou de la coiffe, épaule et col, mains, pieds ou chaussures, détail du dos.
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
Use the attached board (bestiary "3. ÉRABLES") as reference. The character is the one on the card "MOINE TANUKI" (role REVENANT, internal genre "tanuki").

Create its individual model sheet, a single landscape image 1536×1024, in exactly the same style and layout as the world 1 (Archipel) sheets: stylized 3D chibi figurine render, soft studio lighting, dark near-black background.

CHARACTER (follow exactly, as it appears in the large view of the board):
Tanuki monk (returning, Maples outfit): round chibi tanuki with brown fur, cream belly, dark mask around the eyes, large straw conical hat. Red-orange knotted scarf-collar with tassels, small purse, brown outfit. Lit paper lantern (warm light) in the right hand.

LAYOUT:
- Top left: slanted maple orange banner with a small icon and the text "MONDE 3 - ÉRABLES". Below: small square face portrait, the name "MOINE TANUKI" in large white capitals, a role tag "REVENANT", and a line "♥ — PV".
- Left column, full height: large dynamic 3/4 pose (raising his lantern, maple leaves around), in a world setting: the village under autumn maples: red and orange maple trees, red lacquered wooden bridge, temple roofs, lanterns, falling maple leaves, late-afternoon light. The setting must not hide the character.
- Top right: 5-view full-body turnaround, left to right: FRONT, 3/4 FRONT, SIDE, BACK, 3/4 BACK. Plain dark background with no scenery, each figurine standing on a thin glowing maple orange ring on the floor. All 5 figurines complete (from the top of the head or hat down to the feet), same scale, feet on the same line, tops at the same height. Identical neutral pose in all 5 views: standing straight, arms slightly away from the body, lantern hanging from the right hand.
- Centre: grid of 8 close-ups (2 columns × 4 rows) in rounded frames with a thin maple orange border: tanuki face; gourd; collar knot; then back of the head or headgear, shoulder and collar, hands, feet or shoes, back detail.
- Right: framed panel with the same pose as a white wireframe (visible mesh) on a dark background, the labels "≈ tris", "≈ verts", "1 texture (PBR) 2048 × 2048", and 3 stacked texture thumbnails (unwrapped albedo, blue normal map, grey roughness).

CONSISTENCY RULES (top priority):
- The same character, strictly identical in the large pose, the 5 views, the close-ups and the wireframe: same colours, same patterns, same accessories, on the same side of the body.
- Same proportions in all 5 views (same total height, same head size, same shoulder width). Conical straw hat (kasa): identical diameter in all 5 views, about 1.6x the shoulder width, same tip height. A view where the headgear, hat or weapon changes size makes the sheet unusable: this is the defect to avoid first.
- The 5 views are true orthographic rotations of the same model (no different perspective, no different pose).
- No text, numbers, arrows or labels on the 5 views or the close-ups; text only appears in the banner, the name block and the wireframe panel.
- Do not copy the board card or its small thumbnails (they sometimes differ from the character): follow the card's large view.
```

---

## MOINE TANUKI (VARIANTE) : `fiches/tanuki_d.png`

Rôle : VARIANTE · découpe : `decoupes/tanuki_d.png`

### Prompt (FR)

```text
Utilise la planche jointe (bestiaire « 3. ÉRABLES ») comme référence. Le personnage est celui de la carte « MOINE TANUKI (VARIANTE) » (rôle VARIANTE, genre interne « tanuki_d », leurre DORON du tanuki).

Crée sa fiche modèle individuelle, une seule image paysage 1536×1024, dans exactement le même style et la même mise en page que les fiches du monde 1 (Archipel) : rendu 3D stylisé façon figurine chibi, éclairage doux de studio, fond sombre presque noir.

PERSONNAGE (à respecter exactement, tel qu'il apparaît sur la grande vue de la planche) :
Moine tanuki (variante « leurre DORON », habit Érables) : même tanuki chibi brun au grand chapeau conique ; une feuille d'érable orange flotte au-dessus du chapeau (signe de la métamorphose) ; haori orange imprimé de feuilles d'érable, tenue noire, ceinture de corde nouée.

MISE EN PAGE :
- En haut à gauche : bandeau incliné couleur orange érable avec une petite icône et le texte « MONDE 3 - ÉRABLES ». Dessous : petit portrait carré du visage, le nom « MOINE TANUKI (VARIANTE) » en grandes capitales blanches, une étiquette de rôle « VARIANTE », et une ligne « ♥ — PV ».
- Colonne de gauche, sur toute la hauteur : grande pose 3/4 dynamique (pose espiègle, nuage de fumée DORON), dans un décor du monde : le village sous les érables d'automne : érables rouges et orange, pont de bois laqué rouge, toits de temple, lanternes, feuilles d'érable qui tombent, lumière de fin d'après-midi. Le décor ne doit pas masquer le personnage.
- En haut à droite : vue tournante en 5 vues en pied, de gauche à droite : FACE, 3/4 FACE, PROFIL, DOS, 3/4 DOS. Fond sombre uni sans décor, chaque figurine posée sur un fin anneau lumineux orange érable au sol. Les 5 figurines entières (de la pointe de la tête ou du chapeau jusqu'aux pieds), à la même échelle, pieds sur la même ligne, sommets à la même hauteur. Pose neutre identique sur les 5 vues : debout droit, bras un peu écartés du corps, bras le long du corps, légèrement écartés.
- Au centre : grille de 8 gros plans (2 colonnes × 4 lignes) dans des cadres arrondis à bord fin orange érable : visage du tanuki ; haori à feuilles d'érable ; nœud de corde ; puis dos de la tête ou de la coiffe, épaule et col, mains, pieds ou chaussures, détail du dos.
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
Use the attached board (bestiary "3. ÉRABLES") as reference. The character is the one on the card "MOINE TANUKI (VARIANTE)" (role VARIANTE, internal genre "tanuki_d").

Create its individual model sheet, a single landscape image 1536×1024, in exactly the same style and layout as the world 1 (Archipel) sheets: stylized 3D chibi figurine render, soft studio lighting, dark near-black background.

CHARACTER (follow exactly, as it appears in the large view of the board):
Tanuki monk ("DORON decoy" variant, Maples outfit): same brown chibi tanuki with large conical hat; an orange maple leaf floats above the hat (transformation sign); orange haori printed with maple leaves, black outfit, knotted rope belt.

LAYOUT:
- Top left: slanted maple orange banner with a small icon and the text "MONDE 3 - ÉRABLES". Below: small square face portrait, the name "MOINE TANUKI (VARIANTE)" in large white capitals, a role tag "VARIANTE", and a line "♥ — PV".
- Left column, full height: large dynamic 3/4 pose (mischievous pose, DORON smoke puff), in a world setting: the village under autumn maples: red and orange maple trees, red lacquered wooden bridge, temple roofs, lanterns, falling maple leaves, late-afternoon light. The setting must not hide the character.
- Top right: 5-view full-body turnaround, left to right: FRONT, 3/4 FRONT, SIDE, BACK, 3/4 BACK. Plain dark background with no scenery, each figurine standing on a thin glowing maple orange ring on the floor. All 5 figurines complete (from the top of the head or hat down to the feet), same scale, feet on the same line, tops at the same height. Identical neutral pose in all 5 views: standing straight, arms slightly away from the body, arms along the body, slightly apart.
- Centre: grid of 8 close-ups (2 columns × 4 rows) in rounded frames with a thin maple orange border: tanuki face; maple-leaf haori; rope knot; then back of the head or headgear, shoulder and collar, hands, feet or shoes, back detail.
- Right: framed panel with the same pose as a white wireframe (visible mesh) on a dark background, the labels "≈ tris", "≈ verts", "1 texture (PBR) 2048 × 2048", and 3 stacked texture thumbnails (unwrapped albedo, blue normal map, grey roughness).

CONSISTENCY RULES (top priority):
- The same character, strictly identical in the large pose, the 5 views, the close-ups and the wireframe: same colours, same patterns, same accessories, on the same side of the body.
- Same proportions in all 5 views (same total height, same head size, same shoulder width). Conical straw hat (kasa): identical diameter in all 5 views, about 1.6x the shoulder width, same tip height. A view where the headgear, hat or weapon changes size makes the sheet unusable: this is the defect to avoid first.
- The 5 views are true orthographic rotations of the same model (no different perspective, no different pose).
- No text, numbers, arrows or labels on the 5 views or the close-ups; text only appears in the banner, the name block and the wireframe panel.
- Do not copy the board card or its small thumbnails (they sometimes differ from the character): follow the card's large view.
```

---

## SAMOURAÏ ROUGE D'ÉLITE : `fiches/brute_elite.png`

Rôle : ÉLITE · découpe : `decoupes/brute_elite.png`

### Prompt (FR)

```text
Utilise la planche jointe (bestiaire « 3. ÉRABLES ») comme référence. Le personnage est celui de la carte « SAMOURAÏ ROUGE D'ÉLITE » (rôle ÉLITE, genre de base « brute », défi du sanctuaire de l'Oni (« GARDIEN D'ÉLITE »)).

Crée sa fiche modèle individuelle, une seule image paysage 1536×1024, dans exactement le même style et la même mise en page que les fiches du monde 1 (Archipel) : rendu 3D stylisé façon figurine chibi, éclairage doux de studio, fond sombre presque noir.

PERSONNAGE (à respecter exactement, tel qu'il apparaît sur la grande vue de la planche) :
Samouraï rouge d'élite : samouraï chibi en armure rouge et or plus ornée que le samouraï rouge, kabuto à grand maedate doré en érable, menpo sombre aux crocs, écharpe rouge, épaulières larges, tassettes à liserés dorés et bleu nuit. Katana dans la main gauche.

MISE EN PAGE :
- En haut à gauche : bandeau incliné couleur orange érable avec une petite icône et le texte « MONDE 3 - ÉRABLES ». Dessous : petit portrait carré du visage, le nom « SAMOURAÏ ROUGE D'ÉLITE » en grandes capitales blanches, une étiquette de rôle « ÉLITE », et une ligne « ♥ — PV ».
- Colonne de gauche, sur toute la hauteur : grande pose 3/4 dynamique (garde haute, prêt à frapper), dans un décor du monde : le village sous les érables d'automne : érables rouges et orange, pont de bois laqué rouge, toits de temple, lanternes, feuilles d'érable qui tombent, lumière de fin d'après-midi. Le décor ne doit pas masquer le personnage.
- En haut à droite : vue tournante en 5 vues en pied, de gauche à droite : FACE, 3/4 FACE, PROFIL, DOS, 3/4 DOS. Fond sombre uni sans décor, chaque figurine posée sur un fin anneau lumineux orange érable au sol. Les 5 figurines entières (de la pointe de la tête ou du chapeau jusqu'aux pieds), à la même échelle, pieds sur la même ligne, sommets à la même hauteur. Pose neutre identique sur les 5 vues : debout droit, bras un peu écartés du corps, katana tenu lame vers le bas.
- Au centre : grille de 8 gros plans (2 colonnes × 4 lignes) dans des cadres arrondis à bord fin orange érable : visage sous le kabuto ; lamelles d'armure ; cordons et nœud ; puis dos de la tête ou de la coiffe, épaule et col, mains, pieds ou chaussures, détail du dos.
- À droite : panneau encadré avec la même pose en fil de fer blanc (maillage visible) sur fond sombre, les indications « ≈ tris », « ≈ verts », « 1 texture (PBR) 2048 × 2048 », et 3 vignettes de textures empilées (albedo dépliée, normal map bleue, roughness en gris).

CONTRAINTES DE COHÉRENCE (prioritaires) :
- Le même personnage, strictement identique sur la grande pose, les 5 vues, les gros plans et le fil de fer : mêmes couleurs, mêmes motifs, mêmes accessoires, du même côté du corps.
- Mêmes proportions sur les 5 vues (même hauteur totale, même taille de tête, même largeur d'épaules). Même kabuto et même maedate sur les 5 vues. Une vue où la coiffe, le chapeau ou l'arme change de taille rend la fiche inutilisable : c'est le défaut à éviter en priorité.
- Les 5 vues sont de vraies rotations orthographiques du même modèle (pas de perspective différente, pas de pose différente).
- Aucun texte, chiffre, flèche ni étiquette sur les 5 vues et sur les gros plans ; le texte n'apparaît que dans le bandeau, le bloc nom et le panneau fil de fer.
- Ne recopie pas la carte de la planche ni ses petites vignettes (elles sont parfois différentes du personnage) : suis la grande vue de la carte.
```

### Prompt (EN)

```text
Use the attached board (bestiary "3. ÉRABLES") as reference. The character is the one on the card "SAMOURAÏ ROUGE D'ÉLITE" (role ÉLITE, base genre "brute").

Create its individual model sheet, a single landscape image 1536×1024, in exactly the same style and layout as the world 1 (Archipel) sheets: stylized 3D chibi figurine render, soft studio lighting, dark near-black background.

CHARACTER (follow exactly, as it appears in the large view of the board):
Elite red samurai: chibi samurai in red-and-gold armour more ornate than the red samurai, kabuto with a big gold maple maedate, dark fanged menpo, red scarf, wide shoulder guards, tassets with gold and midnight-blue trim. Katana in the left hand.

LAYOUT:
- Top left: slanted maple orange banner with a small icon and the text "MONDE 3 - ÉRABLES". Below: small square face portrait, the name "SAMOURAÏ ROUGE D'ÉLITE" in large white capitals, a role tag "ÉLITE", and a line "♥ — PV".
- Left column, full height: large dynamic 3/4 pose (high guard, ready to strike), in a world setting: the village under autumn maples: red and orange maple trees, red lacquered wooden bridge, temple roofs, lanterns, falling maple leaves, late-afternoon light. The setting must not hide the character.
- Top right: 5-view full-body turnaround, left to right: FRONT, 3/4 FRONT, SIDE, BACK, 3/4 BACK. Plain dark background with no scenery, each figurine standing on a thin glowing maple orange ring on the floor. All 5 figurines complete (from the top of the head or hat down to the feet), same scale, feet on the same line, tops at the same height. Identical neutral pose in all 5 views: standing straight, arms slightly away from the body, katana held blade down.
- Centre: grid of 8 close-ups (2 columns × 4 rows) in rounded frames with a thin maple orange border: face under the kabuto; armour lamellae; cords and knot; then back of the head or headgear, shoulder and collar, hands, feet or shoes, back detail.
- Right: framed panel with the same pose as a white wireframe (visible mesh) on a dark background, the labels "≈ tris", "≈ verts", "1 texture (PBR) 2048 × 2048", and 3 stacked texture thumbnails (unwrapped albedo, blue normal map, grey roughness).

CONSISTENCY RULES (top priority):
- The same character, strictly identical in the large pose, the 5 views, the close-ups and the wireframe: same colours, same patterns, same accessories, on the same side of the body.
- Same proportions in all 5 views (same total height, same head size, same shoulder width). Same kabuto and same crest in all 5 views. A view where the headgear, hat or weapon changes size makes the sheet unusable: this is the defect to avoid first.
- The 5 views are true orthographic rotations of the same model (no different perspective, no different pose).
- No text, numbers, arrows or labels on the 5 views or the close-ups; text only appears in the banner, the name block and the wireframe panel.
- Do not copy the board card or its small thumbnails (they sometimes differ from the character): follow the card's large view.
```

---

## JÔNIN : `fiches/jonin.png`

Rôle : GARDIEN · découpe : `decoupes/jonin.png`

### Prompt (FR)

```text
Utilise la planche jointe (bestiaire « 3. ÉRABLES ») comme référence. Le personnage est celui de la carte « JÔNIN » (rôle GARDIEN, identifiant de fichier « jonin », le maître des ninjas rouges).

Crée sa fiche modèle individuelle, une seule image paysage 1536×1024, dans exactement le même style et la même mise en page que les fiches du monde 1 (Archipel) : rendu 3D stylisé façon figurine chibi, éclairage doux de studio, fond sombre presque noir.

PERSONNAGE (à respecter exactement, tel qu'il apparaît sur la grande vue de la planche) :
Jônin, maître des ninjas rouges : ninja chibi plus massif, cagoule brun-noir, bandeau rouge à plaque dorée, masque noir, yeux ambre perçants. Large écharpe rouge, veste noire, ceinture dorée garnie de sacoches et de plaques, pantalon noir, chaussures blanches. Deux ninjatō, un dans chaque main.

MISE EN PAGE :
- En haut à gauche : bandeau incliné couleur orange érable avec une petite icône et le texte « MONDE 3 - ÉRABLES ». Dessous : petit portrait carré du visage, le nom « JÔNIN » en grandes capitales blanches, une étiquette de rôle « GARDIEN », et une ligne « ♥ — PV ».
- Colonne de gauche, sur toute la hauteur : grande pose 3/4 dynamique (jambes écartées, les deux lames en croix vers le bas), dans un décor du monde : le village sous les érables d'automne : érables rouges et orange, pont de bois laqué rouge, toits de temple, lanternes, feuilles d'érable qui tombent, lumière de fin d'après-midi. Le décor ne doit pas masquer le personnage.
- En haut à droite : vue tournante en 5 vues en pied, de gauche à droite : FACE, 3/4 FACE, PROFIL, DOS, 3/4 DOS. Fond sombre uni sans décor, chaque figurine posée sur un fin anneau lumineux orange érable au sol. Les 5 figurines entières (de la pointe de la tête ou du chapeau jusqu'aux pieds), à la même échelle, pieds sur la même ligne, sommets à la même hauteur. Pose neutre identique sur les 5 vues : debout droit, bras un peu écartés du corps, lames tenues vers le bas, bras écartés.
- Au centre : grille de 8 gros plans (2 colonnes × 4 lignes) dans des cadres arrondis à bord fin orange érable : yeux et plaque du bandeau ; ceinture à sacoches ; sacoche et sangle ; puis dos de la tête ou de la coiffe, épaule et col, mains, pieds ou chaussures, détail du dos.
- À droite : panneau encadré avec la même pose en fil de fer blanc (maillage visible) sur fond sombre, les indications « ≈ tris », « ≈ verts », « 1 texture (PBR) 2048 × 2048 », et 3 vignettes de textures empilées (albedo dépliée, normal map bleue, roughness en gris).

CONTRAINTES DE COHÉRENCE (prioritaires) :
- Le même personnage, strictement identique sur la grande pose, les 5 vues, les gros plans et le fil de fer : mêmes couleurs, mêmes motifs, mêmes accessoires, du même côté du corps.
- Mêmes proportions sur les 5 vues (même hauteur totale, même taille de tête, même largeur d'épaules). Même capuche/cagoule et même longueur d'écharpe sur les 5 vues. Une vue où la coiffe, le chapeau ou l'arme change de taille rend la fiche inutilisable : c'est le défaut à éviter en priorité.
- Les 5 vues sont de vraies rotations orthographiques du même modèle (pas de perspective différente, pas de pose différente).
- Aucun texte, chiffre, flèche ni étiquette sur les 5 vues et sur les gros plans ; le texte n'apparaît que dans le bandeau, le bloc nom et le panneau fil de fer.
- Ne recopie pas la carte de la planche ni ses petites vignettes (elles sont parfois différentes du personnage) : suis la grande vue de la carte.
```

### Prompt (EN)

```text
Use the attached board (bestiary "3. ÉRABLES") as reference. The character is the one on the card "JÔNIN" (role GARDIEN, file id "jonin").

Create its individual model sheet, a single landscape image 1536×1024, in exactly the same style and layout as the world 1 (Archipel) sheets: stylized 3D chibi figurine render, soft studio lighting, dark near-black background.

CHARACTER (follow exactly, as it appears in the large view of the board):
Jônin, master of the red ninjas: bulkier chibi ninja, brown-black hood, red headband with a gold plate, black mask, piercing amber eyes. Wide red scarf, black jacket, gold belt with pouches and plates, black trousers, white shoes. Two ninjatō, one in each hand.

LAYOUT:
- Top left: slanted maple orange banner with a small icon and the text "MONDE 3 - ÉRABLES". Below: small square face portrait, the name "JÔNIN" in large white capitals, a role tag "GARDIEN", and a line "♥ — PV".
- Left column, full height: large dynamic 3/4 pose (legs apart, both blades crossed downward), in a world setting: the village under autumn maples: red and orange maple trees, red lacquered wooden bridge, temple roofs, lanterns, falling maple leaves, late-afternoon light. The setting must not hide the character.
- Top right: 5-view full-body turnaround, left to right: FRONT, 3/4 FRONT, SIDE, BACK, 3/4 BACK. Plain dark background with no scenery, each figurine standing on a thin glowing maple orange ring on the floor. All 5 figurines complete (from the top of the head or hat down to the feet), same scale, feet on the same line, tops at the same height. Identical neutral pose in all 5 views: standing straight, arms slightly away from the body, blades held down, arms apart.
- Centre: grid of 8 close-ups (2 columns × 4 rows) in rounded frames with a thin maple orange border: eyes and headband plate; pouch belt; pouch and strap; then back of the head or headgear, shoulder and collar, hands, feet or shoes, back detail.
- Right: framed panel with the same pose as a white wireframe (visible mesh) on a dark background, the labels "≈ tris", "≈ verts", "1 texture (PBR) 2048 × 2048", and 3 stacked texture thumbnails (unwrapped albedo, blue normal map, grey roughness).

CONSISTENCY RULES (top priority):
- The same character, strictly identical in the large pose, the 5 views, the close-ups and the wireframe: same colours, same patterns, same accessories, on the same side of the body.
- Same proportions in all 5 views (same total height, same head size, same shoulder width). Same hood and same scarf length in all 5 views. A view where the headgear, hat or weapon changes size makes the sheet unusable: this is the defect to avoid first.
- The 5 views are true orthographic rotations of the same model (no different perspective, no different pose).
- No text, numbers, arrows or labels on the 5 views or the close-ups; text only appears in the banner, the name block and the wireframe panel.
- Do not copy the board card or its small thumbnails (they sometimes differ from the character): follow the card's large view.
```

---

## ONI-MUSHA : `fiches/oni_musha.png`

Rôle : BOSS · découpe : `decoupes/oni_musha.png`

### Prompt (FR)

```text
Utilise la planche jointe (bestiaire « 3. ÉRABLES ») comme référence. Le personnage est celui de la carte « ONI-MUSHA » (rôle BOSS, identifiant de fichier « oni_musha », le démon-guerrier des érables).

Crée sa fiche modèle individuelle, une seule image paysage 1536×1024, dans exactement le même style et la même mise en page que les fiches du monde 1 (Archipel) : rendu 3D stylisé façon figurine chibi, éclairage doux de studio, fond sombre presque noir.

PERSONNAGE (à respecter exactement, tel qu'il apparaît sur la grande vue de la planche) :
Oni-musha, démon-guerrier des érables : samouraï chibi démoniaque, kabuto à deux grandes cornes blanches recourbées et maedate doré en érable, menpo d'oni rouge aux crocs et yeux dorés, armure rouge et or ornée, écharpe rouge. Deux katanas aux lames lumineuses, un dans chaque main. Aura orangée.

MISE EN PAGE :
- En haut à gauche : bandeau incliné couleur orange érable avec une petite icône et le texte « MONDE 3 - ÉRABLES ». Dessous : petit portrait carré du visage, le nom « ONI-MUSHA » en grandes capitales blanches, une étiquette de rôle « BOSS », et une ligne « ♥ — PV ».
- Colonne de gauche, sur toute la hauteur : grande pose 3/4 dynamique (il charge, lames croisées, feuilles d'érable en tourbillon), dans un décor du monde : le village sous les érables d'automne : érables rouges et orange, pont de bois laqué rouge, toits de temple, lanternes, feuilles d'érable qui tombent, lumière de fin d'après-midi. Le décor ne doit pas masquer le personnage.
- En haut à droite : vue tournante en 5 vues en pied, de gauche à droite : FACE, 3/4 FACE, PROFIL, DOS, 3/4 DOS. Fond sombre uni sans décor, chaque figurine posée sur un fin anneau lumineux orange érable au sol. Les 5 figurines entières (de la pointe de la tête ou du chapeau jusqu'aux pieds), à la même échelle, pieds sur la même ligne, sommets à la même hauteur. Pose neutre identique sur les 5 vues : debout droit, bras un peu écartés du corps, katanas tenus lames vers le bas.
- Au centre : grille de 8 gros plans (2 colonnes × 4 lignes) dans des cadres arrondis à bord fin orange érable : menpo d'oni ; feuille d'érable dorée ; lamelles de l'armure ; puis dos de la tête ou de la coiffe, épaule et col, mains, pieds ou chaussures, détail du dos.
- À droite : panneau encadré avec la même pose en fil de fer blanc (maillage visible) sur fond sombre, les indications « ≈ tris », « ≈ verts », « 1 texture (PBR) 2048 × 2048 », et 3 vignettes de textures empilées (albedo dépliée, normal map bleue, roughness en gris).

CONTRAINTES DE COHÉRENCE (prioritaires) :
- Le même personnage, strictement identique sur la grande pose, les 5 vues, les gros plans et le fil de fer : mêmes couleurs, mêmes motifs, mêmes accessoires, du même côté du corps.
- Mêmes proportions sur les 5 vues (même hauteur totale, même taille de tête, même largeur d'épaules). Mêmes cornes (même longueur) sur les 5 vues. Une vue où la coiffe, le chapeau ou l'arme change de taille rend la fiche inutilisable : c'est le défaut à éviter en priorité.
- Les 5 vues sont de vraies rotations orthographiques du même modèle (pas de perspective différente, pas de pose différente).
- Aucun texte, chiffre, flèche ni étiquette sur les 5 vues et sur les gros plans ; le texte n'apparaît que dans le bandeau, le bloc nom et le panneau fil de fer.
- Ne recopie pas la carte de la planche ni ses petites vignettes (elles sont parfois différentes du personnage) : suis la grande vue de la carte.
```

### Prompt (EN)

```text
Use the attached board (bestiary "3. ÉRABLES") as reference. The character is the one on the card "ONI-MUSHA" (role BOSS, file id "oni_musha").

Create its individual model sheet, a single landscape image 1536×1024, in exactly the same style and layout as the world 1 (Archipel) sheets: stylized 3D chibi figurine render, soft studio lighting, dark near-black background.

CHARACTER (follow exactly, as it appears in the large view of the board):
Oni-musha, demon warrior of the maples: demonic chibi samurai, kabuto with two big curved white horns and a gold maple maedate, red fanged oni menpo with golden eyes, ornate red-and-gold armour, red scarf. Two katanas with glowing blades, one in each hand. Orange aura.

LAYOUT:
- Top left: slanted maple orange banner with a small icon and the text "MONDE 3 - ÉRABLES". Below: small square face portrait, the name "ONI-MUSHA" in large white capitals, a role tag "BOSS", and a line "♥ — PV".
- Left column, full height: large dynamic 3/4 pose (charging, blades crossed, maple leaves swirling), in a world setting: the village under autumn maples: red and orange maple trees, red lacquered wooden bridge, temple roofs, lanterns, falling maple leaves, late-afternoon light. The setting must not hide the character.
- Top right: 5-view full-body turnaround, left to right: FRONT, 3/4 FRONT, SIDE, BACK, 3/4 BACK. Plain dark background with no scenery, each figurine standing on a thin glowing maple orange ring on the floor. All 5 figurines complete (from the top of the head or hat down to the feet), same scale, feet on the same line, tops at the same height. Identical neutral pose in all 5 views: standing straight, arms slightly away from the body, katanas held blades down.
- Centre: grid of 8 close-ups (2 columns × 4 rows) in rounded frames with a thin maple orange border: oni menpo; gold maple leaf; armour lamellae; then back of the head or headgear, shoulder and collar, hands, feet or shoes, back detail.
- Right: framed panel with the same pose as a white wireframe (visible mesh) on a dark background, the labels "≈ tris", "≈ verts", "1 texture (PBR) 2048 × 2048", and 3 stacked texture thumbnails (unwrapped albedo, blue normal map, grey roughness).

CONSISTENCY RULES (top priority):
- The same character, strictly identical in the large pose, the 5 views, the close-ups and the wireframe: same colours, same patterns, same accessories, on the same side of the body.
- Same proportions in all 5 views (same total height, same head size, same shoulder width). Same horns (same length) in all 5 views. A view where the headgear, hat or weapon changes size makes the sheet unusable: this is the defect to avoid first.
- The 5 views are true orthographic rotations of the same model (no different perspective, no different pose).
- No text, numbers, arrows or labels on the 5 views or the close-ups; text only appears in the banner, the name block and the wireframe panel.
- Do not copy the board card or its small thumbnails (they sometimes differ from the character): follow the card's large view.
```
