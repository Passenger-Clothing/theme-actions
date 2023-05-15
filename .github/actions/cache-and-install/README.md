# Passenger-Clothing/cache-and-install-action

[About this repo](#about-this-repo) | [Usage](#usage) | [Configuration](#configuration)

## About this repo

Cache and install, optionally generates production build.

## Usage

```yml
- name: "Cache and install"
  uses: Passenger-Clothing/theme-actions/.github/actions/cache-and-install@main
  with:
    build: true # optional, defaults to `false`
```

## Configuration

The `Passenger-Clothing/cache-and-install-action` accepts the following arguments:

- `build` - (optional, default: `false`) Generate production build
