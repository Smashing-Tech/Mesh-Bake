# Mesh bake

This is a C(++) implementation of a mesh file generator for Smash Hit. It supports the standard features in the Smash Hit baker as well as the legacy lighting extensions from Smash Hit Blender Tool's python baker.

## Goals

### Overall

* Have the best possible compatibility with default smash hit levels &mdash; this will always take precedence over not being compatible
  * More reversing of the default baker is needed to make sure we get things right

### Large

* Use a pipeline based architecture for better maintainability
* Investigate and implement more optimisation techinques &mdash; for example, space partitioning
* Faster bake times in general &mdash; should bake even large levels in less than 1 second

### Specific

* Support for legacy SHBT extensions (just lighting atm, but more may be added in future 2.x releases)
* New more roubust and theoretically based lighting system
* Use a custom binary xml format for easier parsing on the baker side

## Progress

Nothing has been done yet!
