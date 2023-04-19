# schema
Ontologies and schemas for dataset descriptions in RiverBench

## Versioning and releases

The ontologies in the schema are versioned in sync. The `dev` version corresponds to the latest version on the main branch. The numbered versions correspond to specific tagged releases. Releases are made by pushing a `vX.Y.Z` tag to the main branch. The CI then packages the ontologies and releases them as a GitHub release.

In the ontology sources please use the `dev` version IRIs for `owl:versionIRI` and `owl:imports` properties. They will be updated automatically on release.
