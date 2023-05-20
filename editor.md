# Text editor setup guide

Participants can use any text editors they like,
but the Academy's official editor is VSCodium
(or VSCode) for uniformity.

> VSCodium is the 100% open-source base of VSCode.
>
> VSCode is built on top of VSCodium, with added
> telemetry or other integration with Microsoft
> products which we will not be using.
>
> Both have the same basic features that we
> will be using during the course, so participants
> are free to use whichever they prefer.
>
> I prefer VSCodium because why add telemetry
> to the text editor?.

1. Installing VSCodium (or VSCodium)

Use a package manager to install either of
these:

```shell
# macOS
brew install vscodium;

# Windows
winget install -e --id VSCodium.VSCodium;

# Debian
apt install vscodium

# Arch AUR
paru -Syu vscodium
```

VSCodium-based family of desktop editors are extensible
via plugins called Extensions, through the in-app
_store_-like marketplace.

We will be installing VSCodium plugins via the in-app
Extensions tab to the left of the editor.

2. Install LSP server

Install VSCodium LSP plugins for JavaScript, TypeScript
from the Extensions tab of the app.

3. Setup ESLint linter

Install VSCodium ESLint plugin from the Extensions tab
of the app.

4. Setup Prettier formatter (optional, but recommended)

Install VSCodium Prettier plugin from the Extensions tab
of the app.
