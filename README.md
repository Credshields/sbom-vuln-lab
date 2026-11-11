# sbom-vuln-lab

Dependency manifests with known-vulnerable, pinned package versions, for testing SBOM / software-composition scanners.

Manifests only, no application code. Nothing to install or run.

| Ecosystem | Manifest |
|-----------|----------|
| npm | `npm/package.json` |
| pip | `python/requirements.txt` |
| Maven | `maven/pom.xml` |
| Go | `go/go.mod` |
| Cargo | `rust/Cargo.toml` |

Point a scanner at this repo to generate an SBOM and surface the vulnerable dependencies.


Temp Line Add
