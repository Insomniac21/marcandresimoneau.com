# Components

## Headings

# Title
## Subtitle
### Section
#### Subsection


## Text formatting

**Bold text**
*Italic text*
~~Strikethrough~~
`Inline code`

![Alt text](path/to/image.png)

![Postman Screenshot](assets/img/postman-example.png)

## Links

[Link text](https://example.com)

[See Authentication Guide](authentication.md)

## Block quotes

> **Note:** This action requires authentication.

> **Tip:** Use environment variables to avoid repeating values.

> **Warning:** Do not expose your API key publicly.


## Code blocks

```json
{
  "id": 1,
  "name": "Marc-André"
}
```

```bash
curl -X GET https://api.example.com/users
```

```js
console.log("Hello world");
```

## Lists

- Item one
- Item two
- Item three

1. Step one
2. Step two
3. Step three

## Tables

| Section        | Description                                      |
|----------------|--------------------------------------------------|
| Introduction   | Briefly presents the topic and context.          |
| Installation   | Steps to install or configure the tool.          |
| Usage          | How to use the main feature.                     |
| Examples       | Concrete cases, screenshots, scenarios.          |
| Notes          | Tips, limitations, internal links.               |


| Element              | Description                                               | Example                          |
|----------------------|-----------------------------------------------------------|----------------------------------|
| Endpoint             | URL of the API or targeted resource                       | /api/users                       |
| Method               | HTTP request type                                         | GET, POST, PUT, DELETE           |
| Authentication       | Required auth type                                        | Bearer Token                     |
| Parameters           | Required or optional parameters                           | userId, limit, sort              |
| Request Body         | JSON structure sent to the server                         | {"name": "Marc"}                 |
| Expected Response    | Format of the returned data                               | {"id": 1, "name": "Marc"}        |
| Error Codes          | Possible errors and explanations                          | 400, 401, 404, 500               |

| Section            | Purpose                                                | Typical Content                                 |
|--------------------|--------------------------------------------------------|-------------------------------------------------|
| Overview           | Summarize the tool and what it is used for             | Short description, screenshot                   |
| Features           | List the main capabilities                             | Tests, collections, environments                |
| Workflow           | Explain how the tool is used in a real context         | Steps, diagrams, examples                       |
| Best Practices     | Tips for using the tool effectively                    | Naming, organization, security                  |
| Known Issues       | Common errors and how to fix them                      | Auth issues, variables, environments            |

## Dividers

---

## Front matters template

---
title: "Component Name"
description: "Short description of what this component does."
last_updated: 2026-05-31
version: "1.0.0"
---


