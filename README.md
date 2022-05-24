# Qualisys JSON / YAML schemas

This repository contains JSON Schemas used to validate and give hints on writing YAML and JSON files for Qualisys products and services.

## calqulus-pipeline.schema.json
This schema is used to validate and provide hints for [Calqulus pipelines](https://github.com/qualisys/Calqulus-Steps/) ([documentation](https://github.com/qualisys/Calqulus-Steps/blob/main/docs/index.md)). It is registered on the [JSON Schema Store](https://www.schemastore.org/json/) and should automatically be applied for all files following the pattern `*.calqulus.yaml` or `*.calqulus.yml`, like the pipelines found in our official [Calqulus-Pipelines](https://github.com/qualisys/Calqulus-Pipelines) repository.

## paf-module.schema.json
This schema is used for Settings.paf files for Qualisys PAF Modules. It is registered on the [JSON Schema Store](https://www.schemastore.org/json/) so as long as you have configured your editor to treat `.paf` files as YAML files, it should automatically be used.