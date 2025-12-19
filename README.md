# ResoniteUserRepository
Package Repository for Resonite
# Package Requirements
- releases
# Formatting
## releases
```
<version>=<resoniteURL>|<dependency1>,<dependency2>,...
<version>=<resoniteURL>|<dependency1>,<dependency2>,...
```
### dependency format
```
<package_name>@<version_constraint>
```
Example: `examplepackage@1.*`
#### version_constraint format
| Pattern             | Meaning                                |
| ------------------- | -------------------------------------- |
| `*`                 | Any version                            |
| `1.*`               | Any version with major = 1             |
| `1.2.*`             | Any version with major = 1, minor = 2  |
| `1.2.3`             | Exact version                          |
| `1.x.3`             | Major = 1, patch = 3, minor any        |
| `^1.2.0` (optional) | Compatible versions (future expansion) |
### [releases Example](https://raw.githubusercontent.com/CatShark/ResoniteUserRepository/main/packages/package_name/releases)
## latest
```
<version>
```
### [latest Example](https://raw.githubusercontent.com/CatShark/ResoniteUserRepository/main/packages/package_name/latest)
## info
```
name=<name>
author=<author>
description=<description>
license=<license>
homepage=<url>
```
### [info Example](https://raw.githubusercontent.com/CatShark/ResoniteUserRepository/main/packages/package_name/info)