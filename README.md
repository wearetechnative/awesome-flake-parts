# Awesome Flake Parts [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

A curated list of awesome [flake-parts](https://flake.parts/) resources, modules, and examples. Flake-parts is a framework for writing Nix Flakes that provides a modular approach to flake configuration.

## Contents

- [Official Resources](#official-resources)
- [Tutorials](#tutorials)
- [Blog Posts](#blog-posts)
- [Flake Modules](#flake-modules)
- [Example Projects](#example-projects)
- [Community](#community)

## Official Resources

- [flake-parts Website](https://flake.parts/) - Official documentation and guides.
- [flake-parts Repository](https://github.com/hercules-ci/flake-parts) - Source code and issue tracker.
- [API Reference](https://flake.parts/options.html) - Comprehensive options reference.

## Tutorials

- [flake-parts to set up nodejs devshell](https://blog.eigenvalue.net/2024-flake-parts-nodejs-devshell/) - Tutorial about using flake-parts to set up a nodejs devshell.
- [Flake-parts: writing custom flake modules](https://vtimofeenko.com/posts/flake-parts-writing-custom-flake-modules/) - Primer on writing flake-parts reusable flake modules.

## Blog Posts

- [Refactoring My Infrastructure As Code Configurations](https://not-a-number.io/2025/refactoring-my-infrastructure-as-code-configurations/) - About a migration from host-centric to feature centric nixos configuration.

## Flake Modules

### Official Modules

- [flake-parts/modules](https://github.com/hercules-ci/flake-parts/tree/master/modules) - Built-in modules.

### Community Modules

- [hercules-ci-effects](https://github.com/hercules-ci/hercules-ci-effects) - CI/CD integration for flake-parts.
- [treefmt-nix](https://github.com/numtide/treefmt-nix) - Declarative formatter configuration.
- [devshell](https://github.com/numtide/devshell) - Improved developer shells.
- [pre-commit-hooks-nix](https://github.com/cachix/pre-commit-hooks.nix) - Git pre-commit hooks integration.
- [nixos-flake](https://github.com/srid/nixos-flake) - Opinionated NixOS configuration with flake-parts.
- [flake-root](https://github.com/srid/flake-root) - Discover project root directory.
- [nix-gaming](https://github.com/fufexan/nix-gaming) - Gaming tools and configurations.
- [community.flake.parts](https://github.com/flake-parts/community.flake.parts) - A Community website with links to several flake-module projects.
- [services flake](https://github.com/juspay/services-flake) -  NixOS-like services for Nix as flake modules.

## Related Patterns, Frameworks, Utilities and Libraries

- [The Dendritic Pattern](https://github.com/mightyiam/dendritic) - Nix flake-parts usage pattern in which every Nix file is a flake-parts module.
- [Unify](https://codeberg.org/quasigod/unify/) - Framework for unifying multiple types of Nix configurations.
- [import-tree](https://github.com/vic/import-tree) - Import all nix files in a directory tree.

## Personal Dotfiles & Infra repo's

- [srid/nixos-config](https://github.com/srid/nixos-config) - NixOS configuration with flake-parts.
- [vic/vix](https://github.com/vic/vix) - Vic's *Nix config with flake-parts and [import-tree](https://github.com/vic/import-tree).
- [mightyiam/infra](https://github.com/mightyiam/infra) - Shahar "Dawn" Or (mightyiam)'s personal Nix-powered IT infrastructure repository.
- [quasigod/nixconfig](https://codeberg.org/quasigod/nixconfig) - NixOS and Home Manager configurations with flake-parts and [unify](https://codeberg.org/quasigod/unify/).

## Community

- [GitHub Discussions](https://github.com/hercules-ci/flake-parts/discussions) - Q&A and discussions.

## Contributing

Contributions welcome! Read the [contribution guidelines](CONTRIBUTING.md) first.

## License

[![CC0](https://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0)

To the extent possible under law, the authors have waived all copyright and related or neighboring rights to this work.
