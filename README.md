# Kelvra source package template

Use this repository as a GitHub template for a new pure-Kelvra package. Before
publishing, replace `package-template` and `package_template` throughout the
repository, update the manifest and API, and replace the sample implementation
and tests.

The small caller workflows use the versioned `kelvralang/package-actions@v2`
contract. CI validates the package against Kelvra `main`; a matching `v*` tag
creates a source archive, SHA-256 checksum, and GitHub Release.

```kelvra
const packageTemplate = @import("github.com/kelvralang/package-template")
print(packageTemplate.greeting())
```
