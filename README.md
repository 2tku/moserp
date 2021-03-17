# MosErp
Microservices based Open Source ERP System

Be aware that this repository is no longer maintained and wokrs only as a very old example of microservices with spring boot!


Most ERP Systems are incredible big monolithic pieces of software.
For most small companies this is just overkill. If you need for example only a product management application or an inventory management, you have to use it all.

This projects aims at creating small microservices for each area.

See the Wiki for more details.

## Status
[![Build Status](https://travis-ci.org/thomasletsch/moserp.svg)](https://travis-ci.org/thomasletsch/moserp)

Status: NOT MAINTAINED AND OUT OF DATE!

---
My note:

``` lua
backend
├── common
|   ├── common-domain
|   ├── common-base
|   ├── common-structure
|   ├── common-json-schema
├── infrastructure
|   ├── config-service
|   ├── gateway-service
|   ├── registry-service
|   ├── authentication-service
├── environment-module
|   ├── environment-domain
|   ├── environment
├── facility-module
|   ├── facility-domain
|   ├── facility
├── product-module
|   ├── product-domain
|   ├── product
├── customer-module
|   ├── customer-domain
|   ├── customer
├── inventory-module
|   ├── inventory-domain
|   ├── inventory
├── sales-module
|   ├── sales-domain
|   ├── sales
├── order-module
|   ├── order-domain
|   ├── order
```