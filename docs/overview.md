# 3D Unity Overview / Vue generale 3D Unity

[EN](#english) | [FR](#francais)

![3D Unity pipeline map](../assets/diagrams/pipeline-map.svg)

## English

### Product Shape

The showcase is centered on **Splat Face / Splat Facade Baker**. The product direction is not "generate something pretty"; it is to make lightweight 2.5D and facade-oriented asset candidates that can be inspected in a Unity/mobile context.

The pipeline starts before any asset candidate exists. A visual source has to be reviewed, scored, and either kept, fixed, or rejected. If the source is weak, the rest of the pipeline only hides the problem.

After source review, Splat Face explores the asset route: framing, silhouette, depth-card logic, texture readability, expected use in a scene, and mobile constraints. A useful candidate has a reason to exist and a written way to judge it.

### Connected Surfaces

**Dataset ReviewEval** gives the source review discipline. It is the place where visual inputs become decisions and exports instead of loose folders of images.

**CodexUnity / CodexToUnity** gives the handoff language: request, job shape, manifest, expected output, import check, and review note.

**Mob'ia / ccomf-unity** gives the product layer around profiles, jobs, artifacts, and clients so the work can be followed from a user-facing surface.

**LocalAssetFactory** keeps local preparation practical: normalization, naming, manifest, import expectations, and review criteria.

### Reading Path

Start with [Splat Face](projects/splat-face.md). Then read [Dataset ReviewEval](projects/dataset-revieweval.md), [validation scenarios](validation-scenarios.md), and [QA validation](qa-validation.md). Use [project evaluation](project-evaluation.md) and [partnership](partnership.md) for collaboration, funding, missions, or role discussions.

## Francais

### Forme Produit

La vitrine est centree sur **Splat Face / Splat Facade Baker**. La direction produit n'est pas de "generer quelque chose de joli"; elle consiste a produire des candidats assets 2.5D et facade que l'on peut inspecter dans un contexte Unity/mobile.

Le pipeline commence avant tout candidat asset. Une source visuelle doit etre revue, scoree, puis gardee, corrigee ou refusee. Si la source est faible, le reste du pipeline ne fait que cacher le probleme.

Apres la revue source, Splat Face travaille la route asset: cadrage, silhouette, logique depth-card, lisibilite texture, usage attendu dans une scene et contraintes mobile. Un candidat utile a une raison d'exister et une facon ecrite de le juger.

### Surfaces Reliees

**Dataset ReviewEval** apporte la discipline de revue source. C'est l'endroit ou les entrees visuelles deviennent decisions et exports, pas seulement dossiers d'images.

**CodexUnity / CodexToUnity** apporte le langage du handoff: demande, forme de job, manifest, sortie attendue, controle import et note de revue.

**Mob'ia / ccomf-unity** apporte la couche produit autour des profils, jobs, artefacts et clients pour suivre le travail depuis une surface utilisateur.

**LocalAssetFactory** garde la preparation locale pratique: normalisation, nommage, manifest, attentes import et criteres de revue.

### Chemin De Lecture

Commencer par [Splat Face](projects/splat-face.md). Lire ensuite [Dataset ReviewEval](projects/dataset-revieweval.md), [validation scenarios](validation-scenarios.md) et [QA validation](qa-validation.md). Utiliser [project evaluation](project-evaluation.md) et [partnership](partnership.md) pour collaboration, financement, missions ou postes.
