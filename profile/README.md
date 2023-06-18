# openEHR Java API [![Stability: Experimental](https://masterminds.github.io/stability/experimental.svg)](https://masterminds.github.io/stability/experimental.html)

This project provides a collection of Maven packages with Java interface declarations for the classes defined in the corresponding [openEHR specifications](https://specifications.openehr.org/).

## Overview

The openEHR specifications are grouped into the categories _abstract specifications_, _implementation technology specifications (ITS)_, and _conformance specification_. In each category are groups of specifications called Components.

The _abstract specifications_ category contains "platform-independent UML information models, service interfaces, Antlr grammars etc;" (see [specifications.openehr.org](https://specifications.openehr.org)). The _openERH Java API_ makes the UML information models accessible for applications using the Java programming language, without providing an implementation.

For each Component with a stable release, this GitHub organisation has a repository with a version number that reflects the Component version number. Then each repository has a separate Maven package for the specifications in the corresponding Component.

| **Repository** | **Component** | **Packages** |
|---|---|---|
| [openehr-am-java](https://github.com/openehr-java-api/openehr-am-java) | [Archetype Model](https://specifications.openehr.org/releases/BASE/latest/architecture_overview.html#_archetype_model_component_am)  | Archetype Object Model 2 |
| [openehr-base-java](https://github.com/openehr-java-api/openehr-base-java) | [Base Model](https://specifications.openehr.org/releases/BASE/latest/architecture_overview.html#_base_component_base)  | Foundation Types, Base Types |
| [openehr-rm-java](https://github.com/openehr-java-api/openehr-rm-java) | [Reference Model](https://specifications.openehr.org/releases/BASE/latest/architecture_overview.html#_reference_model_component_rm) | EHR, Demographic, EHR Extract, Data Structures, Data Types, Integration |
| [openehr-term-java](https://github.com/openehr-java-api/openehr-term-java) | [openEHR Terminology](https://specifications.openehr.org/releases/BASE/latest/architecture_overview.html#_terminology_in_openehr)  | Support Terminology |

## References

**openEHR website**

- [Homepage | openehr.org](https://www.openehr.org) 
- [Custom search - openehr.org | cse.google.com](https://cse.google.com/cse?cx=b137c0ed42c6742ba) 
- [Custom search - specifications.openehr.org | cse.google.com](https://cse.google.com/cse?cx=25af888cc5a66491c)
- [All Components | specifications.openehr.org](https://specifications.openehr.org/components)
- [Development Baseline | specifications.openehr.org](https://specifications.openehr.org/development_baseline)
- [openEHR Portal - UML | specifications.openehr.org](https://specifications.openehr.org/releases/UML/latest/index.html)

**openEHR Java implementations**

- [The openEHR Java Reference Implementation Project | openehr.org](https://www.openehr.org/publications/health_ict/R-Chen-etal-openEHR-Java-Impl-Medinfo2007-2007-03-31.pdf)
- https://github.com/openEHR/java-libs
- https://github.com/ehrbase/ehrbase
- https://github.com/openEHR/archie

**Separate Abstractions pattern**

- [Java Application Architecture, Kirk Knoernschild, 2012](https://www.google.com/books/edition/Java_Application_Architecture/iOtwFoU1Dt4C?hl=en), p. 237 ff.
- [Patterns of Modular Architecture | dzone.com](https://dzone.com/refcardz/patterns-modular-architecture)
- [Modularity Patterns with JPMS | opus.ch](https://opus.ch/modularity-patterns-with-jpms-abstractions)

## Legal notice

openEHR is a trademark of [openEHR International](https://openehr.org/about/contacts).

The specifications are distributed under the [Attribution-NoDerivs 3.0 Unported (CC BY-ND 3.0)](https://creativecommons.org/licenses/by-nd/3.0/deed.en_GB) license.

This project transpiles the specification to the Java programming language, under the assumption that it is allowed usage according to the "Principles" section in their Intellectual Property notice: https://openehr.org/governance/intellectual_property.

This project is not affiliated nor endorsed by openEHR International.

Also see: [Allowed use of openEHR specification intellectual property for client SDKs | discourse.openehr.org](https://discourse.openehr.org/t/allowed-use-of-openehr-specification-intellectual-property-for-client-sdks/4001/1)
