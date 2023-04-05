# CommonLibSSE-NG Plugin Template

This is a basic plugin template using CommonLibSSE-NG.

### Requirements
* [XMake](https://xmake.io) [2.7.4+]
* C++20 Compiler (MSVC, Clang?)

## Getting started
```bat
git clone https://github.com/Qudix/template-commonlibsse-ng
cd template-commonlibsse-ng
```

### Building
To build the project, run the following command:
```bat
xmake build
```

> ***Note:*** *This will generate a `build/windows/` directory in the **project's root directory** with the build output.*

### Upgrading Packages (Optional)
To upgrade the project's dependencies, run the following commands:
```bat
xmake repo --update
xmake require --upgrade
```

### Project Generation (Optional)
If you want to generate a Visual Studio project, you can run the following command:
```bat
xmake project -k vsxmake
```

> ***Note:*** *This will generate a `vsxmakeXXXX/` directory in the **project's root directory** using the latest version of Visual Studio installed on the system.*

### Build Output (Optional)
If you want to redirect the build output, you can set one of or both of the following environment variables:

- Path(s) to a Skyrim install folder: `SKYRIM_PATH`

- Path(s) to a Mod Manager mods folder: `SKYRIM_MODS_PATH`

> ***Note:*** *Both variables support semicolon (`;`) seperated paths for multiple game installs or `mods` folders.*

## Documentation
Please refer to the [Wiki](../../wiki/Home) for more advanced topics.
