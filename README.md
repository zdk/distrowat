# distrowat

Why `distrowat` ?

Just because I am always forget how to get os info.

# Installation

`curl -fsSL https://raw.githubusercontent.com/zdk/distrowat/refs/heads/main/install.sh | sudo bash`

# Usage

Use it with the `distrowat` cli

`distrowat --help` for the current available command

The following command are some examples:

## get all info

```
> distrowat all

╔═════════════════════════════════════════╗
║           System Information            ║
╠═════════════════════════════════════════╣
║ Distribution: macOS                     ║
║ Version:      14.5                      ║
║ ID:           macos                     ║
║ Pretty Name:  macOS Sonoma 14.5 (23F79) ║
║ Codename:     sonoma                    ║
╚═════════════════════════════════════════╝

```

## disto name

```
> distrowat name
Ubuntu
```

## codename

```
> distrowat codename
jammy
```

## version

```
> distrowat version
22.04
```

## pretty name

```
> distrowat pretty
Ubuntu 22.04.3 LTS
```
