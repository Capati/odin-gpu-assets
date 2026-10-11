# glTF-Validator base fixtures

`data/` and `assets.json` are copied from the glTF-Validator repository's
`test/base` suite. They are used by `utils/gltf/gltf_tests.odin` to exercise the
valid base-object and accessor-data cases. The adjacent `LICENSE` is copied
from that repository (Apache License 2.0).

The `.report.json` files are retained as upstream references; these tests check
the pure-Odin parser and document validation API, not glTF-Validator's issue
report output.
