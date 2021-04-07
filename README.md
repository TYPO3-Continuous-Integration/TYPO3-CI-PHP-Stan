# TYPO3 PHPStan Github Action

This action checks PHP code of your TYPO3 extension.

## Inputs

### `Files`

Files you want to lint. Default `Classes`.

### `ConfigFile`

Files you want to lint. Default `/.configuration/phpstan.neon`.

## Example usage

```
uses: typo3-continuous-integration/typo3-ci-phpstan@v1
with:
  files: 'Classes'
  config_file: '/.configuration/phpstan.neon'
```
