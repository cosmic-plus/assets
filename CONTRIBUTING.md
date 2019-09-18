**assets /**
[Readme](https://cosmic.plus/#view:assets)
• [Contributing](https://cosmic.plus/#view:assets/CONTRIBUTING)
• [Changelog](https://cosmic.plus/#view:assets/CHANGELOG)

# Contributing

Welcome to new contributors! This project is open to input & edits.

## Bug Reports & Feature Requests

Please use the [dedicated form](https://github.com/cosmic-plus/assets/issues/new/choose).

## Pull Requests

1. Fork [assets](https://github.com/cosmic-plus/assets).
2. Commit your changes to the fork
3. Create a pull request.

If you want to implement a new feature, please get in touch first:
[Keybase](https://keybase.io/team/cosmic_plus),
[Telegram](https://t.me/cosmic_plus), [Email](mailto:mister.ticot@cosmic.plus).

## Project Structure

Assets are sorted by type: `html/`, `scss/` and `svg/`.

## Workflow

**Clone:**

```
git clone https://git.cosmic.plus/assets
```

**Commit:**

```
git ci ...
```

Please sign your commits with your PGP key.

**Release:**

First of all update the package version into `package.json`.

```
export version={semver}
npm run make-release
npm run publish-release
```

Please sign your commits and tags with your PGP key.

## Scripts

Those helpers require a POSIX shell.

- `npm run lint`: Lint meta files.
- `version={semver} npm run make-release`: Build & locally commit release.
- `version={semver} npm run publish-release`: Tag, push & publish release.
