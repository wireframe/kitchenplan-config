# Kitchenplan Configuration

This is a Kitchenplan configuration repository. This repository contains all configuration to install and configure our OSX workstations. More information about Kitchenplan and on how to use it can be found in the [Kitchenplan README](https://github.com/kitchenplan/kitchenplan).

## Installation

```bash
$ sudo gem install kitchenplan
```

## Configuration

Ensure that there is a configuration file in the git repository that matches your operating systems username (ex: `config/people/ryansonnek.yml`)

## Usage

After installing the kitchenplan gem, run the `setup` command and follow the given instructions:

```bash
$ kitchenplan setup https://github.com/wireframe/kitchenplan-config.git
$ kitchenplan provision
```

## Updating

Running these commands will pull down the latest cookbooks and install recent changes.

```bash
$ cd /opt/kitchenplan
$ kitchenplan setup
$ kitchenplan provision
```
