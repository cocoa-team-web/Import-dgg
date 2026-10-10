# Level Import — Android Geode prototype

**Incomplete source prototype; not an installable `.geode` mod yet.**

Current status:
- Minimal Geode source layout and Android64 build workflow.
- Logs when the mod is loaded.
- `.dgg6` parsing, file picker, import/export buttons, and native object placement are not implemented.
- No successful build or in-game test has been performed.

Expected `.dgg6` format is JSON with a `level_name` string and an `objects` array. Each object may contain `type`, `x`, `y`, `group`, `color_base`, `color_of_parts`, `size_x`, and `size_y`.

Before installing, verify the Geode SDK and Geometry Dash version match the target device.
