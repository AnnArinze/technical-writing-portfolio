# Technical writing documentation

Within this portfolio, we see examples of the following touch points

- Api documentation (yaml/json)
- installation guide
- white paper
- user manual
- Request for proposal
- Request for comments (RFCs)
- architecture decision record

## Api documentation (yaml/json)

### yaml
The tags defined within the api document, to which all the apis belong
```yaml
tags:
  - name: auth
    description: Everything operation about auth
    externalDocs:
      description: Find out more
      url: http://swagger.io
  - name: user
    description: Everything operation about users
    externalDocs:
      description: Find out more
      url: http://swagger.io
```
An example documentation in yaml can be found [here](./api-documentation.yaml)
### json
```json
```
n example documentation in json can be found [here](./api-documentation.json)

## Architechtural decision records (ADR)

An Architecture Decision Record (ADR) is a document that captures important architectural decisions made in a project, along with their context and consequences. ADRs are commonly written in Markdown to make them easy to read and version control. Below is an example of an ADR for a hypothetical technical project change.
An example can be found [here](./adr.md).