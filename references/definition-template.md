---
definition-type-name: "{DefinitionTypeName}"
persistence-format: [Json | Xml | Csv | Other (allow multiple)]
programming-language: [C# | C++ | GDScript | Other (allow multiple)]
referenced-by: 
[
  "{ReferencingDefinitionTypeName}"
]
references: 
[
  "{ReferencedDefinitionTypeName}"
]
---

# {DefinitionTypeName}

## Description

<!-- Provide a concise description of what this definition type represents in the context of the system. -->

## 2. Field List

| Field Name  | Type   | Optional | Description                               |
| ----------- | ------ | -------- | ----------------------------------------- |
| id          | string | x        | Unique identifier for each defined entity |
| displayName | string | o        | Display name shown to the player          |
| ...         |        |          |                                           |

Type list: `string / int / float / bool / enum / ref_string / ref_list / other (specify)`

## 3. Relationship List (Reference Mapping)

Referenced by:

| DefTypeName | Description of Relationship |
| ----------- | --------------------------- |
| ...         | ...                         |

References:

| DefTypeName | Description of Relationship |
| ----------- | --------------------------- |
| ...         | ...                         |

## 4. Persistence Examples

<!-- Output sample data in the format specified by `persistence-format` (e.g., Json, Xml, Csv) showing how an instance of this Def would be stored. -->

## 5. Code Integration Example

<!-- Output a code snippet showing how this Def is loaded and accessed in the programming language specified by `programming-language`. -->
