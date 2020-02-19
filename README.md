<h1 align="center">schemas</h1>

<p align="center">
    Schemas used for data validation.
</p>

<br>


## Introduction

This repository contains schemas for data validation. All schemas inside the ```public``` folder are available at https://schemas.ambimax.de/.


## Adding a schema

To add a schema, simply commit them in a new branch inside the public folder. They will be available when merged to master.

The folder structure should make sense. One convention would be to put them into ```public/[context]/[year]/[month]/[schema].json```.


## Updating a schema

Schemas should be immutable. To update a schema, put the updated schema into a new folder.

One exception are dev.[schema].json files. Those are **NOT** and **SHOULD NOT** be expected to be immutable. Dev-Schemas are also published on non-master branches.


## Useful links

* [Understanding JSON Schema](https://json-schema.org/understanding-json-schema/)


## Author Information

- [Tobias Faust](https://github.com/FaustTobias), [ambimax® GmbH](https://ambimax.de)
