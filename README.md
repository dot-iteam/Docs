# Dot iTeam Documentation Website

The source code for the Dot iTeam documentation website.

This repository contains:

* The website landing page
* Documentation assets
* Generated DocC archives
* Static website resources
* Release artifacts used for publishing documentation

## Published Documentation

The latest published documentation is available at:

[Dot iTeam Documentation](https://docs.iteam.studio)

For most users, the published website should be considered the primary source of documentation.

## Repository Purpose

This repository serves as the source and distribution location for the Dot iTeam documentation platform.

It is intended to:

* Host the documentation website source code
* Maintain generated documentation artifacts
* Track documentation changes alongside project releases
* Publish documentation updates to docs.iteam.studio

## Documentation Projects

### SQLiteKit

Documentation for SQLiteKit is available through the published website:

https://docs.iteam.studio/docc/documentation/sqlitekit

Additional libraries and projects may be added over time.

## Local Development

Clone the repository:

```bash
git clone <repository-url>
cd <repository-name>
```

Open the website locally using any static web server.

Example:

```bash
python3 -m http.server 8000
```

Then visit:

```text
http://localhost:8000
```

## Repository Structure

```text
.
├── index.html
├── docc/
│   └── documentation/
├── releases/
├── assets/
└── README.md
```

The exact structure may evolve as additional documentation projects are introduced.

## Releases

Documentation releases are published to:

https://docs.iteam.studio

GitHub Releases may contain generated documentation archives, website snapshots, or deployment artifacts corresponding to published versions.

## Contributing

Documentation improvements, corrections, and enhancements are welcome.

Before submitting changes:

1. Verify links are valid.
2. Review generated documentation output.
3. Ensure local builds complete successfully.
4. Confirm published pages render correctly.

## License

Unless otherwise specified, documentation content and website source code are subject to the license included in this repository.
