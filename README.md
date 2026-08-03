# Mog source package template

Use this repository as a GitHub template for a new pure-Mog package. Before
publishing, replace `package-template` and `package_template` throughout the
repository, update the manifest and API, and replace the sample implementation
and tests.

The included CI validates the package against Mog `main`; the release workflow
creates a source archive and checksum when a matching `v*` tag is pushed.

```mog
const packageTemplate = @import("github.com/moglang/package-template")
print(packageTemplate.greeting())
```
