# Customization checklist

1. Rename the GitHub repository and replace the module identity in `kelvra.toml`.
2. Set `import_name`, package declaration, description, version, and runtime range.
3. Replace `package.api.kel`, `src/main.kel`, and `tests/main.kel`.
4. Update the README, changelog, and license as appropriate.
5. Set `package_name` and any package-specific inputs in the workflow callers.
6. Run the package test locally before creating the first `v*` tag.

Do not keep this template's sample API in a published package.
