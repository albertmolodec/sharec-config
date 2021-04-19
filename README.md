# My [sharec](https://github.com/lamartire/sharec) config

## Installation

```sh
npm i -D @albertmolodec/sharec-config
```

# Bugs

This version has a problem with configs dependencies. They are don't installing to project correctly. So, I moved dependencies to root's `package.json`.

## Contributing

1. Make changes.
2. Bump version in `package.json` according to SemVer.
3. Stage.
4. Commit.
5. Create the same tag as package version with previx: `vX.Y.Z`.
6. Push.

GitHub Actions will create new release and publish it to [GitHub Package Registry](https://github.com/albertmolodec/sharec-config/packages).