# GitHub Action: add-nuget-source

Wraps the "nuget add source" command in a GitHub action.

## Usage V1

``` yaml
      - uses: stephen-atkinson/add-nuget-source@v1
        with:
          source: https://nuget.pkg.github.com/stephen-atkinson/index.json
          username: abc
          password: 123
```
