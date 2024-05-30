[![build](https://github.com/opspec-pkgs/opencontainers.image.build-tar/actions/workflows/build.yml/badge.svg)](https://github.com/opspec-pkgs/opencontainers.image.build-tar/actions/workflows/build.yml)


# Problem statement

Builds an open container initiative (OCI) image and outputs it as a tar.

# Example usage

## Visualize

```shell
opctl ui github.com/opspec-pkgs/opencontainers.image.build-tar#1.0.0
```

## Run

```
opctl run github.com/opspec-pkgs/opencontainers.image.build-tar#1.0.0
```

## Compose

```yaml
op:
  ref: github.com/opspec-pkgs/opencontainers.image.build-tar#1.0.0
  inputs:
    instructions:  # 👈 required; provide a value
  ## uncomment to override defaults
  #   cacheDir: /default_cache
  #   context: /default_context
  #   contextIgnore: /default_context_ignore
  #   password: " "
  #   registry: "docker.io"
  #   username: " "
  outputs:
    imageTar:
```

# Support

join us on
[![Slack](https://img.shields.io/badge/slack-opctl-E01563.svg)](https://join.slack.com/t/opctl/shared_invite/zt-51zodvjn-Ul_UXfkhqYLWZPQTvNPp5w)
or
[open an issue](https://github.com/opspec-pkgs/opencontainers.image.build-tar/issues)

# Releases

releases are versioned according to
[![semver 2.0.0](https://img.shields.io/badge/semver-2.0.0-brightgreen.svg)](http://semver.org/spec/v2.0.0.html)
and [tagged](https://git-scm.com/book/en/v2/Git-Basics-Tagging); see
[CHANGELOG.md](CHANGELOG.md) for release notes

# Contributing

see
[project/CONTRIBUTING.md](https://github.com/opspec-pkgs/project/blob/main/CONTRIBUTING.md)
