# schema

Ontologies and schemas for metadata in RiverBench.

**See the documentation and releases [on the website](https://w3id.org/riverbench/schema)**

More information about metadata in RiverBench: [https://w3id.org/riverbench/documentation/metadata](https://w3id.org/riverbench/documentation/metadata)

## Versioning and releases

The ontologies in the schema are versioned in sync. The `dev` version corresponds to the latest version on the main branch. The numbered versions correspond to specific tagged releases. Releases are made by pushing a `vX.Y.Z` tag to the main branch. The CI then packages the ontologies and releases them as a GitHub release.

In the ontology sources please use the `dev` version IRIs for `owl:versionIRI` and `owl:imports` properties. They will be updated automatically on release.

## License

The schemas and ontologies of RiverBench are licensed under the [Creative Commons Attribution 4.0](https://creativecommons.org/licenses/by/4.0/) license.
