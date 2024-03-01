# ECMAScript - Source Maps Task Group (TC39-TG4)

This repository contains documents, agendas, and notes for the [ECMAScript - Source maps Task Group (TC39-TG4)](https://ecma-international.org/task-groups/tc39-tg4).

See [Scope](#scope) for our mandate.

## Specification

- [Source Map Specification](https://github.com/tc39/source-map-spec)
- [Source Map RFCs](https://github.com/tc39/source-map-rfc)
- [Source Map Tests](https://github.com/tc39/source-map-tests)

## Meetings

Meetings are bi-weekly. The meetings appear on the [TC39 private calendar](https://github.com/tc39/Reflector#tc39-private-calendar).

## Folks

- Convenors: [Jonathan Kuperman](https://github.com/jkup), [Daniel Ehrenberg](https://github.com/littledan)
- Secretaries: [Samina Husain](https://github.com/SaminaHusain), [Istvan Sebestyen](https://github.com/ecmageneva)

## Scope

To improve and evolve the existing informal source map specification into an Ecma standard. This specification defines a JSON-based format describing a mapping of compiled/optimized code (including CSS and ECMAScript® code) into its original source, including metadata such as the mapping of certain names. The goal is to improve the development/debugging experience of source map usage, including for ECMAScript®.

### Programme of work

1. To complete and correct the existing source map specification, including:
   - To define the source map specification strongly enough that it can be determined whether both producers and consumers are “conformant”, leading to well-defined fixes.
   - To produce a conformance test suite against this stronger definition.
   - To evolve the existing source map specification rather than creating a new system (e.g., based on DWARF).
1. On that basis, to improve source map expressiveness in various ways, including:
   - To create additional source map capabilities for improving the mapping of names, including function, variable, and property mappings.
   - To improve the association of a source map to the code it refers to, with various possible mechanisms.
