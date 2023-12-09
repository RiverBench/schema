# SHACL libs for profiles

This directory contains reusable SHACL shapes (libs) for profile definitions.

Each lib is defined in a separate file, and the file name is the same as the lib name, under the `lib:` namespace. For example:

```turtle
@prefix lib:     <https://w3id.org/riverbench/temp/lib#> .
@prefix rb:      <https://w3id.org/riverbench/schema/metadata#> .
@prefix sh:      <http://www.w3.org/ns/shacl#> .
@prefix stax:    <https://w3id.org/stax/ontology#> .

lib:example
    sh:targetClass rb:Distribution ;
    # define the shape here...
.
```
