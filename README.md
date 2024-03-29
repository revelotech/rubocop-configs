# Rubocop Configs
This repo contains Rubocop's config files to be enherited by other projects.
We aim to easily maintain and distribute new cop rules that must be used across all of our Ruby and/or Rails projects, but respect each projects autonomy at the same time.

## How it works
For reference on how to inherit this files, please check the [official Rubocop documentation](https://docs.rubocop.org/rubocop/configuration.html#inheriting-configuration-from-a-remote-url).

Within this repo, you will find different YAML files meant for Rubocop and its differents extensions.

- [X] [Rubocop](/rubocop.yml)
- [X] [Rubocop Rails](/rubocop_rails.yml)
- [X] [Rubocop Performance](/rubocop_performance.yml)
- [X] [Rubocop Rspec](/rubocop_rspec.yml)

**TODO:**
- Improve Rubocop base config
