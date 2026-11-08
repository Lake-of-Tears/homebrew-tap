# Lake of Tears Homebrew Tap 🍺

The official Homebrew tap for Lake of Tears developer tools and CLIs.

---

## Available Formulae

| Formula | Description |
|---|---|
| **[`angler`](Formula/angler.rb)** | The official Lake of Tears CLI — cast queries, launch clusters, inspect catalogs, and reel in data. |

---

## Installation

### 1. Tap and Trust (macOS & Linux)

For Homebrew 7.0+:

```bash
brew tap Lake-of-Tears/tap
brew trust lake-of-tears/tap
brew install angler
```

### 2. Single-Command Install

```bash
brew install Lake-of-Tears/tap/angler
```

---

## Upgrades

Keep your CLI up to date with the latest releases:

```bash
brew update
brew upgrade angler
```

---

## Verification

```bash
angler version
angler --help
```
