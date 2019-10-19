# Testcafe GitHub Action

This action executes your [testcafe](https://devexpress.github.io/testcafe/) command inside a container that has all popular browsers pre-installed.

## Usage

See [action.yml](action.yml)

```yaml
steps:
  - uses: actions/checkout@master
  - uses: actions/setup-node@master
    with:
      node-version: "10.x"
  - uses: Meemaw/testcafe-action@master
    with:
      args: "chrome:headless ./tests"
```

## License

The scripts and documentation in this project are released under the [MIT License](LICENSE)
