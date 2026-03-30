---
type: folder
scope: hardware
status: active
---
# Linux

Kurze Beschreibung dieses Bereichs.

## Inhalt
%% Begin Waypoint %%
- [[Big Tower]]
- [[Dell]]
- [[HP Schule]]
- [[Midi Tower]]

%% End Waypoint %%

```base
filters:
  and:
    - file.folder == this.file.folder
    - file.ext == "md"
    - file.path != this.file.path

views:
  - type: list
    name: Dateien
    order:
      - file.name

```