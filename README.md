# Mog source package template

Use this repository as a GitHub template for a new pure-Mog package. Before
publishing, replace `package-template` and `package_template` throughout the
repository, update the manifest and API, and replace the sample implementation
and tests.

The small caller workflows use the versioned `moglang/package-actions@v1`
contract. CI validates the package against Mog `main`; a matching `v*` tag
creates a source archive, SHA-256 checksum, and GitHub Release.

```mog
const packageTemplate = @import("github.com/moglang/package-template")
print(packageTemplate.greeting())
```
