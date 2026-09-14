<p align="center">
  <img src="https://raw.githubusercontent.com/rodolphe37/easy-ci/main/src/easy_ci/resources/icon.png" alt="Easy CI" width="120">
</p>

<h1 align="center">Homebrew tap for Easy CI</h1>

<p align="center">
  <a href="https://github.com/rodolphe37/easy-ci">Easy CI</a> — monitor, edit and generate your CI/CD pipelines (GitHub Actions, GitLab CI/CD, Bitbucket Pipelines) from one desktop app.
</p>

## Install

```bash
brew tap rodolphe37/easy-ci
brew install --cask easy-ci
```

## Update / uninstall

```bash
brew upgrade --cask easy-ci
```

```bash
brew uninstall --cask easy-ci
```

Easy CI is not code-signed: Homebrew keeps the quarantine flag, so the first launch needs a right-click › **Open** (or `xattr -dr com.apple.quarantine /Applications/EasyCI.app`). For an install without that warning, use the script instead:

```bash
curl -fsSL https://raw.githubusercontent.com/rodolphe37/easy-ci/main/packaging/macos/install.sh | bash
```

## How this tap is maintained

`Casks/easy-ci.rb` is updated automatically by the [release workflow](https://github.com/rodolphe37/easy-ci/blob/main/.github/workflows/release.yml) of the main repository after each release (version and SHA-256 of both macOS archives). Please open issues and pull requests on [rodolphe37/easy-ci](https://github.com/rodolphe37/easy-ci/issues).
