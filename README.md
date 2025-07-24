# Scoop NI Bucket

A [Scoop](https://scoop.sh/) bucket for National Instruments software packages.

## What is Scoop?

Scoop is a command-line installer for Windows that makes it easy to install and manage software packages. It focuses on open-source, command-line tools and provides a simple way to keep them updated.

## Installation

To add this bucket to your Scoop installation:

```powershell
scoop bucket add ni https://github.com/ni-kismet/scoop-ni
```

## Available Packages

### SystemLink Integrator CLI (slcli)

A command-line interface for SystemLink Integrator.

**Installation:**

```powershell
scoop install ni/scoop-slcli
```

**Description:** SystemLink Integrator CLI  
**Homepage:** https://github.com/ni-kismet/systemlink-cli  
**License:** MIT

## Usage

After adding the bucket, you can install any package using:

```powershell
scoop install ni/<package-name>
```

To update packages:

```powershell
scoop update <package-name>
```

To see all available packages in this bucket:

```powershell
scoop search ni/
```

## Contributing

Contributions are welcome! If you'd like to add a new package or update an existing one:

1. Fork this repository
2. Create a new JSON manifest file in the `bucket/` directory
3. Follow the [Scoop manifest format](https://github.com/ScoopInstaller/Scoop/wiki/App-Manifests)
4. Submit a pull request

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Links

- [Scoop Website](https://scoop.sh/)
- [Scoop Documentation](https://github.com/ScoopInstaller/Scoop/wiki)
- [Creating App Manifests](https://github.com/ScoopInstaller/Scoop/wiki/App-Manifests)
