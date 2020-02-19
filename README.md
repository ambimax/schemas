<h1 align="center">schemas</h1>

<p align="center">
    Schemas used for data validation.
</p>

<br>


## Introduction

This repository contains schemas for data validation. All schemas inside the ```schemas``` folder can be used for data validation and are available at https://github.com/ambimax/schemas/blob/master/schemas/.


## Adding a schema

To add a schema, simply commit them in a new branch inside the schemas folder. They will be available at the above URL when merged to master.

The folder structure should make sense. One convention would be to put them into ```schemas/[context]/[year]/[month]/[schema].json```.


## Updating a schema

Schemas should be immutable. To update a schema, put the updated schema into a new folder.

One exception are schemas on non-master branches. Those are **NOT** and **SHOULD NOT** be expected to be immutable. They can be accessed via https://github.com/ambimax/schemas/blob/[branch-name]/schemas/.


## Useful links

* [Understanding JSON Schema](https://json-schema.org/understanding-json-schema/)
* Node.js
    * [ajv](https://www.npmjs.com/package/ajv): used for validating schemas
    * [json-schema-ref-parser](https://www.npmjs.com/package/json-schema-ref-parser): used to download schemas for offline use (should be the go-to method for validation)
* PHP
    * [justinrainbow/json-schema](https://github.com/justinrainbow/json-schema): used for validating schemas


## Author Information

- [Tobias Faust](https://github.com/FaustTobias), [ambimax® GmbH](https://ambimax.de)
