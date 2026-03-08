# Homebrew Tap — MillerMedia

This is the official [Homebrew](https://brew.sh) tap for tools by [MillerMedia](https://github.com/MillerMedia).

## Available Packages

| Package | Type | Description |
|---|---|---|
| [awtest](https://github.com/MillerMedia/awtest) | Cask | AWS credential permission scanner for security assessments |
| [kneejerk](https://github.com/MillerMedia/Kneejerk) | Formula | Scan environment variables from React websites |

## Installation

### Add the tap

```sh
brew tap MillerMedia/tap
```

### Install packages

```sh
# AWTest — AWS credential scanner
brew install --cask awtest

# Kneejerk — React env variable scanner
brew install kneejerk
```

### One-liner (no separate tap step)

```sh
brew install --cask MillerMedia/tap/awtest
brew install MillerMedia/tap/kneejerk
```

## Updating

```sh
brew update
brew upgrade --cask awtest
brew upgrade kneejerk
```

## Documentation

- [AWTest documentation](https://github.com/MillerMedia/awtest)
- [Kneejerk documentation](https://github.com/MillerMedia/Kneejerk)
- [Homebrew documentation](https://docs.brew.sh)
