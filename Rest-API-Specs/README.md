# Spec Requirements

Specs must meet the following requirements:

- Follow the OpenAPI 2.0 specification
- Include an `operationId` for Fortellis to assign a unique ID to that endpoint
- Conform to current Fortellis standards

For more information on the spec, please see the [Open API Specification](https://github.com/OAI/OpenAPI-Specification/blob/master/versions/2.0.md).

## Swagger Version

Include the swagger version at the top of the file.

```yaml
swagger: '2.0'
```

## Info

Include an info section with the following information:

- Version
- Title
- Description
- Contact
  - Name
  - URL
  - Email

```yaml
info:
  version: '47.0.0'
  title: Fortellis Sample Application
  description: Provide a really good description.
  contact:
    name: Developer Evangelists
    url: https://fortellis.io/contact-us
    email: support@fortellis.io
```

### Version

You must include the semantic version of the spec within the `info` section.

### Title

Consider the following when creating a spec title:

- You must include the title in the spec.
- Users see the title from the spec when they view your API on Fortellis.

### Description

- Product Name - Root Domain - API Name
- A description of what the API does
- The intended audience of this API
