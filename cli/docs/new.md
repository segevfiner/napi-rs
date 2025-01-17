# New

> This file is generated by cli/codegen. Do not edit this file manually.

Create a new project with pre-configured boilerplate

## Usage

```sh
# CLI
napi new <path> [--options]
```

```typescript
// Programatically
import { NapiCli } from '@napi-rs/cli'

new NapiCli().new({
  // options
})
```

## Options

| Options              | CLI Options              | type     | required | default | description                                                                      |
| -------------------- | ------------------------ | -------- | -------- | ------- | -------------------------------------------------------------------------------- |
|                      | --help,-h                |          |          |         | get help                                                                         |
| path                 | <path>                   | true     | string   |         | The path where the napi-rs project will be created.                              |
| name                 | --name,-n                | string   | false    |         | The name of the project, default to the name of the directory if not provided    |
| minNodeApiVersion    | --min-node-api,-v        | number   | false    | 4       | The minimum Node-API version to support                                          |
| license              | --license,-l             | string   | false    | 'MIT'   | License for open-sourced project                                                 |
| targets              | --targets,-t             | string[] | false    | []      | All targets the crate will be compiled for.                                      |
| enableDefaultTargets | --enable-default-targets | boolean  | false    | true    | Whether enable default targets                                                   |
| enableAllTargets     | --enable-all-targets     | boolean  | false    | false   | Whether enable all targets                                                       |
| enableTypeDef        | --enable-type-def        | boolean  | false    | true    | Whether enable the `type-def` feature for typescript definitions auto-generation |
| enableGithubActions  | --enable-github-actions  | boolean  | false    | true    | Whether generate preconfigured GitHub Actions workflow                           |
| dryRun               | --dry-run                | boolean  | false    | false   | Whether to run the command in dry-run mode                                       |
