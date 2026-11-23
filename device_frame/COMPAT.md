# Flutter 3.16.x compatibility (Atom735 fork)

Branch: `compat/flutter-3.16`

This branch lowers `device_frame` SDK / Flutter constraints so the package
analyzes and runs on **Flutter 3.16.9 / Dart 3.2.6** (used by
[atmos_dart_pubs](https://github.com/Atom735/atmos_dart_pubs)).

Changes vs upstream `device_frame` 1.4.0:

- `environment.sdk`: `>=3.2.0 <4.0.0`
- `environment.flutter`: `>=3.16.0`
- Softened `freezed_annotation` / codegen dev_dependency ranges for Dart 3.2
- Example app SDK aligned to the same floor

Upstream: https://github.com/aloisdeniel/flutter_device_preview
