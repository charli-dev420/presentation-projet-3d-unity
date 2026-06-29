# Source Facts / Faits sources

[EN](#english) | [FR](#francais)

## English

Public-safe source review checked on 2026-06-29. The table uses public names for product surfaces and avoids private internal naming.

| Source | Status | License / sharing | Publicly usable facts | Published here |
| --- | --- | --- | --- | --- |
| Dataset ReviewEval / DatasetViewEval | Local desktop dataset-review app. | MIT. | Windows Tkinter UI, quality/Trellis2 analysis, JSON/CSV/Markdown exports, documented test baseline, clean secret-scan signal. | [Evidence](evidence.md), [QA validation](qa-validation.md) |
| Splat Face / Splat Facade Baker | Pre-MVP repo-ready surface. | MIT. | Depth-card baker, dataset factory, orchestrator, training prep/runner, studio UI scaffold, Unity importer scaffold. | [Proof pack](proof-pack.md), [demo scenarios](demo-scenarios.md) |
| CodexUnity / CodexToUnity | Experimental public prototype. | Not presented as a supported release. | Asset Factory direction, persistent jobs, GLB normalization, Unity manifest, sockets, dry-run/smoke paths. | [QA validation](qa-validation.md), [evidence](evidence.md) |
| Mob'ia / ccomf-unity | Private product layer. | Source-available noncommercial surfaces only where explicitly agreed; no redistribution without agreement. | Product layer in front of ComfyUI-style workflows: profiles/pipelines, async jobs, artifact storage, Unity/web/mobile clients. | [Project map](project-map.md), [demo scenarios](demo-scenarios.md) |
| LocalAssetFactory | Private/local validation loop. | Not published as source. | `.glb` orientation, queue, preflight, one job at a time, normalization, manifest, and Unity handoff concepts. | [Visual index](visual-index.md), [QA notes](qa-and-blockers.md) |

### Interpretation

The strongest public evidence is split across three kinds of material: public repositories, product maps, and written QA/proof summaries. That is intentional. The public dossier lets an evaluator understand the product direction without requiring private code, datasets, generated assets, or infrastructure details.

## Francais

Verification publique et public-safe du 2026-06-29. Le tableau utilise les noms publics des surfaces produit et evite les anciens noms internes.

| Source | Statut | Licence / partage | Faits utilisables publiquement | Preuve publiee ici |
| --- | --- | --- | --- | --- |
| Dataset ReviewEval / DatasetViewEval | App desktop locale orientee revue dataset. | MIT. | Interface Windows Tkinter, analyse qualite/Trellis2, exports JSON/CSV/Markdown, baseline de tests documentee, scan secret sans signal publiable. | [Evidence](evidence.md), [QA validation](qa-validation.md) |
| Splat Face / Splat Facade Baker | Surface pre-MVP repo-ready. | MIT. | Depth-card baker, dataset factory, orchestrator, training prep/runner, studio UI scaffold, Unity importer scaffold. | [Proof pack](proof-pack.md), [demo scenarios](demo-scenarios.md) |
| CodexUnity / CodexToUnity | Prototype public experimental. | Pas presente comme release supportee. | Direction Asset Factory, jobs persistants, normalisation GLB, manifest Unity, sockets, dry-run/smoke. | [QA validation](qa-validation.md), [evidence](evidence.md) |
| Mob'ia / ccomf-unity | Couche produit privee. | Surfaces source-available noncommercial seulement si explicitement convenu; pas de redistribution sans accord. | Couche produit devant des workflows type ComfyUI: profils/pipelines, jobs async, stockage artefacts, clients Unity/web/mobile. | [Project map](project-map.md), [demo scenarios](demo-scenarios.md) |
| LocalAssetFactory | Boucle privee/locale de validation. | Non publie comme source. | Orientation `.glb`, queue, preflight, un job a la fois, normalisation, manifest et concepts de handoff Unity. | [Visual index](visual-index.md), [QA notes](qa-and-blockers.md) |

### Interpretation

La preuve publique la plus solide combine trois types de materiel: repos publics, cartes produit et resumes QA/preuves rediges. C'est volontaire. Le dossier public permet a un evaluateur de comprendre la direction produit sans demander code prive, datasets, assets generes ou details infra.
