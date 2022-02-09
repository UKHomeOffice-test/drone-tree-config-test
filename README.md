# drone-tree-config-test

- single .drone.yml file in root: OK
- .drone.yml file in root and tenant-a/.drone.yml -> fail (linter: duplicate pipeline names)
- tenant-a pipeline only with changes in resources: OK
- adding 2 new pipelines for tenants b and c -> fail (linter: duplicate pipeline names)
- tenant c resources changes: OK
- tenant c pipeline changes: OK
