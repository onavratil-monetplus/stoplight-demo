# My Markdown Showcase

The beginning of an awesome article...


### You may try some sample request...

```yaml http
method: get
url: 'https://todos.stoplight.io/todos'
headers:
  Content-Type: application/json
body:
  some: data

```

### Or describe json schema

```json json_schema
type: object
description: My doc for this schema
properties:
  id: 
    type: number
    description: Unique entity identifier
  name:
    type: string
    description: Optional human-readable name
required:
  - id
examples:
  Example1:
    id: 10
    name: Rabbit
  Example2:
    id: 1134
```