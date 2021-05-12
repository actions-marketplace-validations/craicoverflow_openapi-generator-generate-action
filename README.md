# install-git-chglog

This action installs and runs [OpenAPI Generator](https://openapi-generator.tech/).

## Usage

See [action.yaml](https://craicoverflow/openapi-generator-action/blob/main/action.yml)

Basic:

```yaml
steps:
- uses: actions/openapi-generator-action@main
  with:
    generator: 'go'
    input: petstore.yaml
```

## License

The scripts and documentation in this project are released under the [MIT License](LICENSE).

## Contributions

Are welcome.