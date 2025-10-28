# Xraph Scoop Bucket

Official Scoop bucket for Xraph CLI tools on Windows.

## Installation

Add the bucket and install your desired tool:

```powershell
scoop bucket add xraph https://github.com/xraph/scoop-bucket
scoop install forge
```

Or install directly:

```powershell
scoop bucket add xraph https://github.com/xraph/scoop-bucket
scoop install xraph/forge
```

## Available Tools

- **forge** - Comprehensive backend framework for Go with enterprise-grade features

## Updating

To update tools installed from this bucket:

```powershell
scoop update
scoop update forge
```

Uninstalling

```powershell
scoop uninstall forge
scoop bucket rm xraph  # optional: remove the bucket if no longer needed
```

## Requirements

- Windows 7 SP1 or newer
- PowerShell 3+
- .NET Framework 4.5+ (for some tools)

## Contributing

Issues and contributions should be directed to the specific tool's repository.

## License

MIT
