# yarn

[![Build Status](https://drone.osshelp.ru/api/badges/ansible/yarn/status.svg)](https://drone.osshelp.ru/ansible/yarn)

This role installs Yarn from official repositories (stable/rc/nightly).

## Usage (example)

```yaml
    - role: nodejs
    - role: yarn
```

The Yarn needs an installed Node.js.

## Available parameters

| Param | Description |
| -------- | -------- |
| `yarn_version` | Yarn version `(stable/rc/nightly)`. Default: `stable` |

## FAQ

None, so far.

## Useful links

- [Official documentation](https://classic.yarnpkg.com/en/docs)

## TODO

None, so far.

## License

GPL3

## Author

OSSHelp Team, see <https://oss.help>
