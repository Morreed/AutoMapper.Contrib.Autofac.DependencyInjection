# [3.1.0](https://www.nuget.org/packages/AutoMapper.Contrib.Autofac.DependencyInjection/3.1.0) (2020-02-22)

## Features

* Update `Autofac` to version `5.1.1`
* Expose `MapperConfiguration` as `IConfigurationProvider` as well

## Chore

* Optimize registration process and make sure that `AutoMapper` assemblies are excluded when scanning for types

# [3.0.0](https://www.nuget.org/packages/AutoMapper.Contrib.Autofac.DependencyInjection/3.0.0) (2020-01-29)

## Breaking changes

* `Autofac` has been updated to `5.0.0`. The release of `Autofac` contains breaking changes, mostly making the container immutable. You can read more about the changes [here](https://www.paraesthesia.com/archive/2020/01/27/autofac-5-released/).

# [2.0.1](https://www.nuget.org/packages/AutoMapper.Contrib.Autofac.DependencyInjection/2.0.1) (2019-12-26)

## Chore

* Update `Autofac` to version `4.9.4`

# [2.0.0](https://www.nuget.org/packages/AutoMapper.Contrib.Autofac.DependencyInjection/2.0.0) (2019-08-12)

## Breaking changes

* `AutoMapper` has completely removed all static-apis. If you still rely on any of them, please check out this [migration-guide](https://docs.automapper.org/en/stable/9.0-Upgrade-Guide.html).

## Chore

* Update `AutoMapper` to version `9.0.0`

# [1.0.1](https://www.nuget.org/packages/AutoMapper.Contrib.Autofac.DependencyInjection/1.0.0) (2019-06-13)

## Chore

* Update `AutoMapper` to version `8.1.1`

# [1.0.0](https://www.nuget.org/packages/AutoMapper.Contrib.Autofac.DependencyInjection/1.0.0) (2019-05-16)

## Intial Release

* Allow `AutoMapper` and it's components to be registered via an extension method for Autofac.

## Additional Note

This package is the same as the latest version from CleanCodeLabs.AutoMapper.Extensions.Autofac.DependencyInjection. It has been moved to this repository and will be continued to be mantained here.