# Pinttrs

*Pint meets attrs*

## Motivation

The amazing [`attrs`](https://www.attrs.org) library is a game-changer when it 
comes to writing classes. Its initialisation sequence notably allows for 
automated conversion and verification of attribute values. This package is an 
attempt at designing a system to apply units automatically and reliably to 
attributes with [Pint](https://pint.readthedocs.io).

Features:

- Automatic attachment of predefined units to unitless values
- Verification of units compatibility for united values
- Dynamic fetching of units from a registry
- Unit-enabled deserialisation of objects
