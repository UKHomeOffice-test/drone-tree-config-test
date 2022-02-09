# drone-tree-config-test

- single .drone.yml file in root: OK
- .drone.yml file in root and tenant-a/.drone.yml -> fail (linter: duplicate pipeline names)