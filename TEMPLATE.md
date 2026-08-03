# Customization checklist

1. Rename the GitHub repository and replace the module identity in `mog.toml`.
2. Set `import_name`, package declaration, description, version, and runtime range.
3. Replace `package.api.mog`, `src/main.mog`, and `tests/main.mog`.
4. Update the README, changelog, and license as appropriate.
5. Change `PACKAGE_NAME` in both workflows.
6. Run the package test locally before creating the first `v*` tag.

Do not keep this template's sample API in a published package.
