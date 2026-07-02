# Project Map / Carte projet

[EN](#english) | [FR](#francais)

![Pipeline map](../assets/diagrams/pipeline-map.svg)

## English

### Main Line

The project map follows one practical line: **review the source, prepare a lightweight candidate, hand it to Unity, and write the review decision**.

**Splat Face / Splat Facade Baker** is the center of that line. It handles the 2.5D and facade-oriented asset route: visual framing, depth-card thinking, texture readability, expected scene role, and mobile constraints.

**Dataset ReviewEval** sits before it. It keeps the pipeline honest by forcing a decision on the source material: keep, fix, reject, export, or revisit.

**CodexUnity / CodexToUnity** sits at the handoff point. It makes request framing, manifests, generated candidates, import checks, and review notes understandable.

**Mob'ia / ccomf-unity** sits around the workflow as a product layer: profiles, jobs, artifacts, clients, and review states.

**LocalAssetFactory** sits close to the machine: local files, normalization, manifests, Unity import expectations, and final review notes.

### Product Reading

The chain should not end with "asset created". It should end with a decision that another person can read: accepted, revise, reject, archive, or keep for later review.

## Francais

### Ligne Principale

La carte projet suit une ligne pratique: **revoir la source, preparer un candidat leger, le passer a Unity et ecrire la decision de revue**.

**Splat Face / Splat Facade Baker** est le centre de cette ligne. Il porte la route asset 2.5D et facade: cadrage visuel, logique depth-card, lisibilite texture, role attendu en scene et contraintes mobile.

**Dataset ReviewEval** vient avant. Il garde le pipeline honnete en forcant une decision sur le materiel source: garder, corriger, refuser, exporter ou revoir plus tard.

**CodexUnity / CodexToUnity** intervient au handoff. Il rend lisibles le cadrage de demande, les manifests, les candidats generes, les controles import et les notes de revue.

**Mob'ia / ccomf-unity** entoure le workflow comme couche produit: profils, jobs, artefacts, clients et etats de revue.

**LocalAssetFactory** reste proche de la machine: fichiers locaux, normalisation, manifests, attentes d'import Unity et notes de revue finales.

### Lecture Produit

La chaine ne doit pas finir par "asset created". Elle doit finir par une decision qu'une autre personne peut lire: accepter, reviser, refuser, archiver ou garder pour revue ulterieure.
