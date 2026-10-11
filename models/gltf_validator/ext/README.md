# glTF-Validator extension fixtures

The extension directories and their `data/` fixtures and `assets.json`
manifests are copied from the glTF-Validator repository's `test/ext` suite.
They support the extension integration tests in `utils/gltf/gltf_tests.odin`.
The adjacent `LICENSE` is copied from that repository (Apache License 2.0).

The `.report.json` files are retained as upstream references. These tests cover
the pure-Odin parser's typed extension data and preservation of unrecognized
extension payloads; they do not reproduce glTF-Validator's issue reports.
