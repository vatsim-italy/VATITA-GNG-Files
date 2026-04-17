
# VATITA GNG Files

This repository contains configuration files, sector resources, plugin data, profiles, and settings used for controlling in Italy.

## Contributing

Contributions are welcome and help keep files accurate, current, and operationally useful.

### What you can contribute

- Airspace and sector configuration updates
- Plugin data fixes and improvements
- Profile and settings corrections
- Documentation updates
- Data quality improvements (ICAO mappings, airports, airlines, symbols, etc.)

### Before you start

- Check existing files carefully to avoid duplicates or conflicting definitions.
- Keep changes focused: one topic or fix per pull request.
- Avoid unrelated formatting-only edits.
- Ensure paths and naming remain consistent with existing repository conventions.

## Editing airspace

While not strictly mandatory, using QGIS is highly recommended for editing airspace files to ensure all geometries are valid and correctly formatted. If you choose to use QGIS, PM @FabioMike06 to have an automated converter between TopSkyMaps/Areas and GeoPackage formats.

## How to contribute

1. Fork the repository.
2. Create a branch from `main` with a clear name, for example: `fix/lirf-sector-boundary`.
3. Make your changes and validate them locally (syntax, references, and consistency).
4. Commit with a clear message explaining what was changed and why.
5. Open a pull request to `main` with:
	- A short summary
	- A list of changed files
	- Operational impact (if any)
	- Validation notes




### Pull request checklist

- [ ] Changes are scoped and intentional
- [ ] No unrelated file edits are included
- [ ] File format and style are consistent with surrounding content
- [ ] References to sectors/plugins/profiles are updated where needed
- [ ] Description explains reason, impact, and verification

## Contributor license agreement
Individual contributions including all fixes, patches, and modifications are submitted under the agreement that VATITA retains the right to use them in sector file production. By submitting your work, you agree to transfer full ownership of these creations to VATITA.