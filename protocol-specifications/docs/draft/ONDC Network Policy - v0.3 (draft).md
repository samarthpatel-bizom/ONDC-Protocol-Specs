# ONDC Network Policy - v0.3 (draft)



## 1. Overview

ONDC will define network policies that will govern the operation of the network, for each of the following:

- Registration of Participants
- Data Privacy and Security
- [Payment and Settlement Protocol](https://docs.google.com/document/d/1V0zqFAS4bQP9tXBAOaPZq5PX8cTbKx6wKAoYZFlYURU/edit)
- Use-cases for different domains
- Open Data Protocol
- Transaction Authentication & Non-repudiation
- Grievances & Disputes
- Frauds

A subset of the above network policies have been codified, in the form of an “ONDC Protocol” commerce layer on top of the underlying Beckn protocol, and includes the following:

- Baseline configurations (for codification of domains supported, validity of message requests for APIs, codification of city / country / currency / language);
- ONDC Schema Policy - defines an optimal set of mandatory attributes and additional non-standard attributes to meet statutory and other functional requirements. Non-standard attributes are namespaced and prefixed by “./ondc-”;
- Error Codes

ONDC Protocol includes the following:

- ONDC Protocol Core API - this is the core API from which the domain specific APIs (below) are derived. Links are below:
  - [Github](https://github.com/Open-network-for-digital-commerce/ONDC-Protocol/blob/master/protocol-specifications/core/v0/api/core.yaml)
  - SwaggerHub
- ONDC Protocol API for Retail (hyperlocal) - this is the API for retail (hyperlocal). Links are below:
  - [Github](https://github.com/Open-network-for-digital-commerce/ONDC-Protocol/blob/master/protocol-specifications/core/v0/api/retail-hyperlocal.yaml)
  - SwaggerHub
- ONDC Protocol API for Retail (Food & Beverage) - this is the API for retail (food & beverage). Links are below:
  - [Github](https://github.com/Open-network-for-digital-commerce/ONDC-Protocol/blob/master/protocol-specifications/core/v0/api/retail-f%26b.yaml)
  - SwaggerHub
- ONDC Protocol API for Logistics - this is the API for Logistics. Links are below:
  - [Github](https://github.com/Open-network-for-digital-commerce/ONDC-Protocol/blob/master/protocol-specifications/core/v0/api/logistics.yaml)
  - Swaggerhub
- ONDC Error Codes. Links are below:
  - [Github](https://github.com/Open-network-for-digital-commerce/ONDC-Protocol/blob/master/protocol-specifications/docs/draft/Error&nbsp;Codes.md)

ONDC Protocol will continue to evolve with the ONDC network. All issues, related to the ONDC Protocol APIs, should be logged to [Github](https://github.com/Open-network-for-digital-commerce/ONDC-Protocol/issues)