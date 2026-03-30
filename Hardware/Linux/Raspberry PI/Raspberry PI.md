

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