# Data Connectors Schema

Draft schema for [Data Connectors](https://learn.microsoft.com/en-us/azure/sentinel/data-connector-ui-definitions-reference) definition files.

## Getting started

1. In a new JSON file, add the following property at the top of the file: 

```json
{
    "$schema": "https://raw.githubusercontent.com/camilo86/DataConnectorSchema/refs/heads/main/schema.json",
    ...
}
```

2. Tab through all of the properties you need to define in the definition file. (PS. This works really well with modern editors like Visual Studio Code)

## Examples

> **Note:** The examples in this repo do not make use of the GitHub URL shown in the Getting Started section. They refer to the relative path to the schema file (this just makes it easy to work with when testing schema changes locally.)

 See the [examples](./examples/) folder for connectors built using this schema.
