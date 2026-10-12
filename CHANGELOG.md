# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.1.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## Unreleased

### Changed
- Vervoersknooppunten AP: Apply PascalCase and CamelCase
- Vervoersknooppunten AP: Replace http://schema.org with https://schema.org
- Vervoersknooppunten AP: Replace abbreviations
- Vervoersknooppunten AP: Capitalise sentences

### Added
- Vervoersknooppunten AP: Add definition for Enum "Toegankelijkheidstype"
- Vervoersknooppunten AP: Add label and definition for Enum "Hoppinpunttype"

## 2025-01-02

- Added extra semicolon to stakeholders
- Removed unused Site class from project

## 2025-01-07

- Remove package Mirror since this package did not have a baseUri and was not used in the package itself
- Delete Element from OSLO-OpenbaarDomein due to duplicates in labels with context-generator
- Added package tag (INSPIRE-Netwerk) to Netwerkelement due to duplicates in labels with context-generator
- Added package tag (OSLO-Generiek) to Plaats due to duplicates in labels with context-generator
- Delete CivicStructure from schema.org package since it wasn't being used anywhere and caused conflicts due to duplicates in labels with context-generator
- Delete Dienst from schema.org package since it wasn't being used anywhere and caused conflicts due to duplicates in labels with context-generator
- Deleted Schema.org package since it was empty after deleting previous classes
- Deleted Straatmeubilair from package OSLO-Infrastructuurelementen since it wasn't being used anywhere and caused conflicts due to duplicates in labels with context-generator
- Added package tag (INSPIRE-Netwerk) to Knoop due to duplicates in labels with context-generator
- Added package tag (INSPIRE-Netwerk) to Netwerk due to duplicates in labels with context-generator
