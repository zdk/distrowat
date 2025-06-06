# distrowat

Fetch distro info `¯*(ツ)*/¯`

# Installation

## using curl:

`curl -fsSL https://raw.githubusercontent.com/zdk/distrowat/refs/heads/main/install.sh | sudo bash`

## using `homebrew`:

```bash
brew tap zdk/tools
brew install distrowat

```

## using `dkpg`:

`curl -LO https://github.com/zdk/distrowat/releases/download/v0.9.0/distrowat_0.9.0_all.deb`

`dpkg -i distrowat_0.9.0_all.deb`

# Usage

- Run `distrowat` on your OS

  - `distrowat all`

- Get distro info in JSON, run

  - `distrowat --json all`

And, the following command are some examples:

> ### all info

```
> distrowat all

╔════════════════════════════╗
║     System Information     ║
╠════════════════════════════╣
║ Distribution: Ubuntu       ║
║ Version:      25.04        ║
║ ID:           ubuntu       ║
║ Pretty Name:  Ubuntu 25.04 ║
║ Codename:     plucky       ║
╟────────────────────────────╢
║ Release Date: 2025-04-17   ║
║ End of Life:  2026-01-15   ║
╚════════════════════════════╝
```

> ### disto name

```
> distrowat name
> Ubuntu

```

> ### codename

```
> distrowat codename
> jammy

```

> ### version

```

> distrowat version
> 22.04

```

> ### pretty format name

```
> distrowat pretty
Pretty Name: Ubuntu 25.04
```

> ### json output

```
> distrowat --json all
{
  "name": "Ubuntu",
  "version": "25.04",
  "id": "ubuntu",
  "pretty": "Ubuntu 25.04",
  "codename": "plucky",
  "release_date": "2025-04-17",
  "end_of_life": "2026-01-15"
}
```
