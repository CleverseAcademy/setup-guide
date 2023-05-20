# Setup guide

This is a guide for installing software required for Cleverse Academy.

## Operating systems

Participants can use any of the systems we prefer -
macOS, Windows, Linux, or even BSDs.

> The officially support systems are macOS, Windows, and Linux.

The software tools we select for the courses are available in all
officially supported systems.

Out staff can help you troubleshoot on both macOS and Linux platforms,
but we may lack neccessary in-depth knowledge for a Windows system,
but Windows should be a non-issue.

## Package managers

A package manager is a software which installs and
maintains other software as well as their
dependencies on your systems.

Our staff recommends using a [_package manager_](https://en.wikipedia.org/wiki/Package_manager)
to install software during the course.

This is to avoid duplicate files, outdated dependencies,
and to be able to quickly sync software versions safely.

Different package managers are available on different
platforms. Our recommended package managers for different
operating systems are:

- macOS - [Homebrew](https://brew.sh)

- Windows 10/11 - [winget](https://learn.microsoft.com/en-us/windows/package-manager/winget/)

  > [Chololatey](https://chocolatey.org) can also be used,
  > but we recommend winget nonetheless.

- Linux distros - whatever comes with your system should be fine.

We will be using the package manager to install system software
we use to write our code, as opposed to development
packages (libraries), which are software we use in our code.

## Text editor

A text editor is a software with which we write text.

Notepad is also an editor, but modern developer editors
like VSCodium or NeoVim will have more features geared
towards programmers.

See the [text editor setup guide](./editor.md)
for more details.

## Languages

The programming languages for the course are JavaScript
and TypeScript.

Both run in Node.js runtime, so we'll need a Node.js
on your system.

Use the system package manager to install Node.js,
as well as NPM, the separate package manager for
development.

See [Node.js](./node.md) for more details.
