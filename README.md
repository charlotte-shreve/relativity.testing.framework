# Relativity.Testing.Framework

:+1::tada: Welcome to Relativity.Testing.Framework! :tada::+1:

The [Relativity.Testing.Framework](https://github.com/relativitydev/relativity.testing.framework) and [Relativity.Testing.Framework.Api](https://github.com/relativitydev/relativity.testing.framework.api) are repositories that comprise Relativity.Testing.Framework.

At a high level, Relativity.Testing.Framework handles configuration management and object models, while Relativity.Testing.Framework.Api handles the interactions with the Relativity APIs.

This repository contains a C#/NuGet library that abstracts out common functionality for test setup and teardown.

## Table of Contents

- [Relativity.Testing.Framework](#relativitytestingframework)
  - [Table of Contents](#table-of-contents)
  - [Supported Relativity Versions](#supported-relativity-versions)
  - [Documentation](#documentation)
  - [Where to get help](#where-to-get-help)
  - [Build Tasks](#build-tasks)
  - [Local Testing](#local-testing)
    - [Unit Testing](#unit-testing)
  - [Contributing](#contributing)
  - [Maintainers](#maintainers)
  - [Reporting Issues and Adding Feature Enhancements](#reporting-issues-and-adding-feature-enhancements)

## Supported Relativity Versions

- Official support is only provided for the following versions.
  - RelativityOne current and preview versions
  - Relativity Server 2022 (12.1) and later

## Documentation

For more details and common usage patterns check out [our documentation](https://relativitydev.github.io/relativity.testing.framework/).

## Where to get help

- For general help and questions, please start a [Discussion](https://github.com/relativitydev/relativity.testing.framework/discussions).

## Build Tasks

This repository builds with the [dotnet sdk](https://dotnet.microsoft.com/download).
It supports standard tasks like `dotnet build`, `dotnet test`, and `dotnet pack`.

## Local Testing

### Unit Testing

Run through the standard compile and (unit) test tasks. These can be done without any external environment to test on.

```PowerShell
dotnet build source
dotnet test source
```

## Contributing

See [CONTRIBUTING.md](https://github.com/relativitydev/relativity.testing.framework/blob/master/CONTRIBUTING.md).

## Maintainers

The Developer Environments team is the primary care-taker of this repository.

## Reporting Issues and Adding Feature Enhancements

For bug reports or feature enhancements, please create an [Issue](https://github.com/relativitydev/relativity.testing.framework/issues) using the respective template. Before reporting an issue, please follow these guidelines. It helps us in understanding the request and provide a quicker response time.

- Determine if it's a bug report or a feature enhancement.
- Perform a quick search in the [issue tracker](https://github.com/relativitydev/relativity.testing.framework/issues) to see if the issue has already been reported. If it has, add a comment to the existing issue instead of opening a new one.
- If you find a **Closed** issue that seems like it is the same thing that you're experiencing, open a new issue and include a link to the original issue in the body of your new one.
