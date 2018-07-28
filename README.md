# porter
Porter is a  tool for managing pkgsrc installations, originally designed for 
the Sanity Linux distribution

## Usage
Run `porter usage`
A `man` page will be coming soon.

## What does it do?
`porter` allows you to bootstrap a `pkgsrc` tree, update the tree within the 
same branch, and upgrade your installed packages.

## What does it run on?
`porter` was originally designed for Sanity Linux.
It should run properly on any Linux distribution, FreeBSD, NetBSD, macos,
and eventually I'll get around to adding Cygwin support.
I don't have a functional Cygwin install right now.
If you have one, lemme know.

## Errata
It probably won't fail appropriately right now if something breaks.
If it does a bad thing, add `set -ex` below `#!/bin/sh`, and add the
entire output to a GitHub issue.
This is a work in progress.