# Tutorials / Tutoriels

[EN](#english) | [FR](#francais)

## English

### Tutorial 1 - Read The Pipeline In 20 Minutes

1. Start with the [one-pager](one-pager.md) for the product promise.
2. Use the [project map](project-map.md) to place Dataset ReviewEval, Splat Face, CodexUnity, Mob'ia/ccomf-unity, and LocalAssetFactory.
3. Open [evidence](evidence.md) and [source facts](source-facts.md) to see what is public, private, verified, or framed for demo.
4. Finish with [QA validation](qa-validation.md) so the discussion stays grounded in acceptance criteria, not only visual appeal.

### Tutorial 2 - Prepare A Dataset For Asset Work

An asset dataset is not just a folder of images. It should explain what can be generated, what should be avoided, and how a reviewer will check the result.

Minimum review fields:

- source or provenance category;
- target use in Unity or mobile;
- framing and readability;
- duplication or near-duplicate risk;
- visual noise that could harm generation or baking;
- decision: keep, fix, reject, or reserve for manual review.

### Tutorial 3 - Evaluate A Splat Face 2.5D Candidate

1. Identify the cleared visual source and intended Unity use.
2. Check silhouette, depth readability, scale expectation, and texture/material assumptions.
3. Decide whether the output is a lightweight visual prop, a facade/background element, or a candidate for deeper asset work.
4. Record what a Unity reviewer should inspect: bounds, orientation, material slots, texture size, and mobile risk.
5. Keep the result public-safe by publishing criteria and summaries, not private meshes or generated outputs.

### Tutorial 4 - Prepare A CodexUnity Or LocalAssetFactory Handoff

Before a Unity handoff, confirm the asset name, manifest, pivot, scale, orientation, bounds, materials, texture expectations, collision needs, and validation status. A useful handoff lets another reviewer reproduce the decision without seeing local endpoints, private paths, or raw logs.

### Tutorial 5 - Read A Quality Proof

A useful proof states the source category, scenario, abstract environment, expected result, observed result, acceptance decision, known constraint, and next action. Raw logs are supporting material; they are not a public proof until summarized and redacted.

## Francais

### Tutoriel 1 - Lire le pipeline en 20 minutes

1. Commencer par le [one-pager](one-pager.md) pour la promesse produit.
2. Utiliser la [carte projet](project-map.md) pour placer Dataset ReviewEval, Splat Face, CodexUnity, Mob'ia/ccomf-unity et LocalAssetFactory.
3. Ouvrir les [preuves](evidence.md) et [faits sources](source-facts.md) pour voir ce qui est public, prive, verifie ou cadre pour demo.
4. Finir par la [QA validation](qa-validation.md) pour garder la discussion sur des criteres d'acceptation, pas seulement sur le rendu visuel.

### Tutoriel 2 - Preparer un dataset asset

Un dataset asset n'est pas seulement un dossier d'images. Il doit expliquer ce qui peut etre genere, ce qu'il faut eviter et comment le resultat sera verifie.

Champs minimum:

- source ou categorie de provenance;
- usage cible dans Unity ou mobile;
- cadrage et lisibilite;
- risque de doublon ou quasi-doublon;
- bruit visuel pouvant nuire a la generation ou au bake;
- decision: garder, corriger, rejeter ou reserver pour revue manuelle.

### Tutoriel 3 - Evaluer un candidat Splat Face 2.5D

1. Identifier la source visuelle autorisee et l'usage Unity attendu.
2. Verifier silhouette, profondeur lisible, echelle attendue et hypotheses de textures/materiaux.
3. Decider si la sortie est un prop visuel leger, un element facade/background ou un candidat a un travail asset plus profond.
4. Noter ce qu'un reviewer Unity doit inspecter: bounds, orientation, slots materiaux, taille texture et risque mobile.
5. Garder le resultat public-safe en publiant criteres et resumes, pas les meshes prives ni sorties generees.

### Tutoriel 4 - Preparer un handoff CodexUnity ou LocalAssetFactory

Avant un handoff Unity, confirmer nom d'asset, manifest, pivot, echelle, orientation, bounds, materiaux, textures attendues, collisions si necessaire et statut de validation. Un bon handoff permet a un autre reviewer de comprendre la decision sans voir endpoints locaux, chemins prives ni logs bruts.

### Tutoriel 5 - Lire une preuve qualite

Une preuve utile indique categorie de source, scenario, environnement abstrait, resultat attendu, resultat observe, decision d'acceptation, contrainte connue et prochaine action. Les logs bruts sont du support; ils ne deviennent preuve publique qu'apres synthese et redaction.
