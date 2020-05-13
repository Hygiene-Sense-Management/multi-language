# Multi-Language Package

## Introduction
This package provides helpers to deal with multi-language content in .NET projects.

The API documentation of the helpers from the **multi-language package** can be found [here](api/index.md).

## Concept
The **multi-language package** supports the creation of `Phrases`, which can have `Translations`. These translations consist of a `LanguageTag` and a corresponding `Value`. 
The `Value` represents the actual translation. A `Phrase` cannot contain multiple `Translations` with the same `LanguageTag`.