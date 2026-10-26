# Composer Components _(composer_components)_

[![standard-readme compliant](https://img.shields.io/badge/readme%20style-standard-brightgreen.svg?style=flat-square)](https://github.com/RichardLitt/standard-readme)

Shared Blazor and Razor component library powering the Composer ecosystem.

Composer Components provides reusable UI elements, responsive navigation bars, menus, and layout structures shared across Composer web apps and .NET MAUI clients.

## Table of Contents

- [Background](#background)
- [Install](#install)
- [Usage](#usage)
- [Maintainers](#maintainers)
- [Contributing](#contributing)
- [License](#license)

## Background

Maintaining unified look-and-feel across browser applications and native mobile/desktop platforms requires single-source UI architecture. Composer Components extracts core Blazor templates and styles into a modular Razor class library.

## Install

Add reference from your Blazor or MAUI project:

```xml
<ItemGroup>
  <ProjectReference Include="..\composer_components\Composer.Component.csproj" />
</ItemGroup>
```

Or build directly:

```bash
dotnet build Composer.Component.csproj
```

## Usage

Reference namespace in your _Imports.razor:

```azor
@using Composer.Component.Areas.Layout.Component
```

Render components in Razor views:

```azor
<MenuBar />
<NavMenu />
```

## Maintainers

[@Nevitash](https://github.com/Nevitash)

## Contributing

PRs accepted. Please open an issue first to discuss component contract updates or new design primitives.

## License

[MIT](LICENSE)
