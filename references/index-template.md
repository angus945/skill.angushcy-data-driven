# {SystemName} Data-Driven Design Overview

## Entity List

- [DefinitionTypeName]
  - Description of the definition type and its role in the system.
  - [./{DefinitionTypeName}\_Def.md](./{DefinitionTypeName}_Def.md)

## ER Diagram (Text)

ItemDef <-- InventoryEntryDef (N:1)
ItemDef <-- ShopEntryDef (N:1)
ItemDef --> EffectDef (1:N)

## Design Decision Log

- [Decision] Item effects separated into a standalone EffectDef, reason: ...
- [Pending] ...
