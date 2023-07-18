# openEHR 4J

This project provides a collection of Maven packages with Java interface declarations for the classes defined in the corresponding [openEHR specifications](https://specifications.openehr.org/).

## Overview

The openEHR specifications are grouped into the categories "abstract specifications", "implementation technology specifications (ITS)", and "conformance specification". In each category are groups of specifications called Components.

The "abstract specifications" category contains "platform-independent UML information models, service interfaces, Antlr grammars etc;" (see [specifications.openehr.org](https://specifications.openehr.org)). For each Component in the "abstract specifications" category that has a stable release, this GitHub organisation has a repository with a version number that reflects the version number of the corresponding Component. Then each repository has a separate Maven package per specification.

| **Component**| **Repository** | **Packages** |
|---|---|---|
| [Archetype Model](https://specifications.openehr.org/releases/BASE/latest/architecture_overview.html#_archetype_model_component_am) | [openehr-am-4j](https://github.com/openehr4j/openehr-am-4j) | [Archetype Object Model 2](https://openehr4j.github.io/openehr-am-4j/javadocs/openehr-am-aom2/index.html) |
| [Base Model](https://specifications.openehr.org/releases/BASE/latest/architecture_overview.html#_base_component_base) | [openehr-base-4j](https://github.com/openehr4j/openehr-base-4j) | [Base Types](https://openehr4j.github.io/openehr-base-4j/javadocs/openehr-base-base-types/index.html), [Foundation Types](https://openehr4j.github.io/openehr-base-4j/javadocs/openehr-base-foundation-types/index.html), [Resource Model](https://openehr4j.github.io/openehr-base-4j/javadocs/openehr-base-resource-model/index.html)  |
| [Reference Model](https://specifications.openehr.org/releases/BASE/latest/architecture_overview.html#_reference_model_component_rm) | [openehr-rm-4j](https://github.com/openehr4j/openehr-rm-4j) | [Common](https://openehr4j.github.io/openehr-rm-4j/javadocs/openehr-rm-common/index.html), [Data Structures](https://openehr4j.github.io/openehr-rm-4j/javadocs/openehr-rm-data-structures/index.html), [Data Types](https://openehr4j.github.io/openehr-rm-4j/javadocs/openehr-rm-data-types/index.html), [Demographic](https://openehr4j.github.io/openehr-rm-4j/javadocs/openehr-rm-demographic/index.html), [EHR](https://openehr4j.github.io/openehr-rm-4j/javadocs/openehr-rm-ehr/index.html), [EHR Extract](https://openehr4j.github.io/openehr-rm-4j/javadocs/openehr-rm-ehr-extract/index.html), [Integration](https://openehr4j.github.io/openehr-rm-4j/javadocs/openehr-rm-integration/index.html), [Support](https://openehr4j.github.io/openehr-rm-4j/javadocs/openehr-rm-support/index.html) |
| [openEHR Terminology](https://specifications.openehr.org/releases/BASE/latest/architecture_overview.html#_terminology_in_openehr) | [openehr-term-4j](https://github.com/openehr4j/openehr-term-4j) | [Support Terminology](https://openehr4j.github.io/openehr-term-4j/javadocs/openehr-term-support-terminology/index.html) |

## Specifications

**[BASE](https://specifications.openehr.org/releases/RM/Release-1.1.0)**

- https://specifications.openehr.org/releases/BASE/Release-1.2.0/architecture_overview.html
- https://specifications.openehr.org/releases/BASE/Release-1.2.0/foundation_types.html
- https://specifications.openehr.org/releases/BASE/Release-1.2.0/base_types.html
- https://specifications.openehr.org/releases/1.0.2/requirements/iso18308_conformance.pdf

**RM**

https://specifications.openehr.org/releases/RM/Release-1.1.0

- https://specifications.openehr.org/releases/RM/Release-1.1.0/ehr.html
- https://specifications.openehr.org/releases/RM/Release-1.1.0/demographic.html
- https://specifications.openehr.org/releases/RM/Release-1.1.0/common.html
- https://specifications.openehr.org/releases/RM/Release-1.1.0/data_structures.html
- https://specifications.openehr.org/releases/RM/Release-1.1.0/data_types.html
- https://specifications.openehr.org/releases/RM/Release-1.1.0/support.html
- https://specifications.openehr.org/releases/RM/Release-1.1.0/integration.html
- https://specifications.openehr.org/releases/RM/Release-1.1.0/ehr_extract.html


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

Java is a trademark of [Oracle](https://www.oracle.com/legal/trademarks.html).
