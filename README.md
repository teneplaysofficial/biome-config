# @tenedev/biome-config

[![npm version](https://img.shields.io/npm/v/@tenedev/biome-config.svg?logo=npm&color=brightgreen)](https://www.npmjs.com/package/@tenedev/biome-config)
[![Downloads](https://img.shields.io/npm/dt/@tenedev/biome-config?logo=npm)](https://www.npmjs.com/package/@tenedev/biome-config)

## Installation

```bash
npm install -D @biomejs/biome @tenedev/biome-config
```

## Usage

Create a biome.json file in your project:

```json
{ "extends": ["@tenedev/biome-config"] }
```

That's it 🎉

## Available Presets

### `@tenedev/biome-config`

Main default configuration.

```json
{
  "extends": ["@tenedev/biome-config"]
}
```

### `@tenedev/biome-config/off-fmt`

Disables the formatter and keeps linting enabled.

```json
{
  "extends": ["@tenedev/biome-config/off-fmt"]
}
```
