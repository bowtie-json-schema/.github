# Bowtie

The world of [JSON Schema](https://json-schema.org) is vast.
The specification has seen incredible adoption, both for use directly by end-users in applying constraint-based validation, as well as within other specifications like [OpenAPI](https://www.openapis.org/) and [AsyncAPI](https://www.asyncapi.com/) which depend on it.

With this growth, or perhaps a *cause* of the growth, is a [large ecosystem of tools](https://json-schema.org/implementations) which implement the JSON Schema specification(s).

Doing so isn't easy!
And whilst we have an [extensive test suite](https://github.com/json-schema-org/JSON-Schema-Test-Suite) with good coverage of the specification, support still varies across implementations.

[Bowtie](../../bowtie-json-schema) is a tool designed to surface and compare differences across implementations, identifying ways in which they differ from the test suite (and transitively the specification) in the hopes that this information is both useful to end-users (who choose between implementations and rely on their correctness) as well as to implementers (who need information about implementation gaps in order to address them).

This organization houses the Bowtie tool, along with some additional related repositories.

An introductory post to Bowtie is [also featured on the JSON Schema blog](https://json-schema.org/blog/posts/bowtie-intro).
