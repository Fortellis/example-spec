# Asynchronous Spec Requirements

Specs must meet the following requirements:

- Follow the [AsyncAPI](https://www.asyncapi.com) 2.0 specification
- Conform to current Fortellis standards for [Designing an Asynchronous API](https://docs.fortellis.io/docs/tutorials/event-relay/tutorial-design-an-async-api/)

For more information on the spec, please see the [AsyncAPI Specification 2.0.0](https://www.asyncapi.com/docs/specifications/v2.0.0).

## Swagger Version

Include the `asyncapi` version at the top of the file.

```yaml
asyncapi: '2.0.0'
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
