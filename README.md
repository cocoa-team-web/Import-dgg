# Level Import — development scaffold

Contains Geode metadata, CMake project, a GitHub Actions Android64 build workflow, and a DGG6 JSON validator.

**Status:** this is not a finished importer and is not yet a tested `.geode` package. The validator checks JSON shape only. It does not insert Geometry Dash objects into the editor or export a playable level. Those parts require a verified mapping from DGG6 object types to native game object IDs and tested editor insertion/export APIs.

DGG6 expected root: `level_name` (string), `objects` (array). Each object minimally needs `type`, `x`, and `y`.
