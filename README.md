# Foxhole OAS

[Foxhole War API](https://github.com/clapfoot/warapi) as an OpenAPI document.

## Schema URL

```text
https://raw.githubusercontent.com/jonahsnider/foxhole-oas/main/openapi.yml
```

## Documentation

Markdown documentation is generated with [OpenAPI Generator](https://github.com/OpenAPITools/openapi-generator).

[**You can read it here**](./docs/README.md).

## Contributors

### Generating the documentation

Run this command to generate the documentation:

```sh
openapi-generator-cli generate -g markdown -i ./openapi.yml -o docs
```
