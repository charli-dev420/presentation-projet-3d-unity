# QA Validation / Validation QA

[FR](#francais) | [EN](#english)

![3D QA matrix](../assets/qa-matrix.svg)

## Francais

| Surface | Validation connue | A fermer | Impact |
| --- | --- | --- | --- |
| DatasetViewEval | `unittest`, compileall, backend API tests, model role readiness locale. | Release automation unifiee et packaging final. | Bon signal pour app desktop locale. |
| SFB core/dataset/orchestrator | Chemins smoke et scaffolds documentes. | Validation avec vrais GLB, Blender, Unity, ComfyUI. | Bloque claim pipeline complet. |
| Unity importer | Scaffold documente. | Compilation/test dans projet Unity reel. | Bloque import preuve production. |
| ComfyUI live | Concepts et integration documentes. | Execution live, node compatibility, output discovery. | Bloque generation proof. |
| CodexToUnity | Dry-run, plugin surface, smoke paths. | Live TRELLIS2/ComfyUI, Unity batch sans skip, mesh validation profonde. | Prototype seulement. |

### Regle QA publique

Une validation publique doit indiquer: source, scenario, environnement abstrait, resultat, limite et next action. Les fichiers generes, datasets, GLB, outputs, logs et endpoints restent hors repo.

## English

Public QA must describe source, scenario, abstract environment, result, limitation, and next action. Generated files, datasets, GLB files, outputs, logs, workflows, and endpoints remain out of the showcase.
