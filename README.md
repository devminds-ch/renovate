# Renovate for GitHub by [devminds GmbH](https://devminds.ch)

This repository contains the shared [Renovate](https://docs.renovatebot.com/) preset for GitHub projects maintained by devminds GmbH.


## Usage

Add the preset to your project's `renovate.json`:

```json
{
  "$schema": "https://docs.renovatebot.com/renovate-schema.json",
  "extends": ["github>devminds-ch/renovate"]
}
```

Keep project-specific rules in the project's own `renovate.json`.
