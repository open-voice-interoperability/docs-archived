# 3. vrs-integration

Date: 2021-03-10

## Status

In progress

Supercedes [](0002-vrs-type.md)

## Context

Identify the components the VRS will integrate with that includes the parameters that needed to be passed. 



## Decision

Components that will call the VRS are the following:
### 1. Voice Assistant Platform (VAS)
- Search for registered names (GET)

### 2. VRS User Interface for registration, searching, and updating status
- Register new names (post)
- Update information for current registered names (PUT)
- Cancel registration for current registered names (PUT)
- Search for registered names (GET)

### 3. Local VRS resolver (Internet Of Things)
- Search for registered names (GET)

![](component_assets/vrs_003_01.png?raw=true "Fig. 1 - VRS Integrations")

## Consequences

//TODO
