<h1 align="center">kir68k/random-stuff :3</h1>
<p align="center">
    <img src="https://seal.stylism.moe/get/@kir68k.gh.random-stuff?theme=asoul" />
</p>
<p align="center">
    <i>εντροπία ⛥ impermanence</i><br>
</p>
<p align="center">
    <a href="https://spdx.org/licenses/ISC.html">
        <img src="https://img.shields.io/badge/License-ISC-FF4783.svg">
    </a>
</p>

## What is this
Small random things I made either years ago or around when this repo was made, that don't necessarily deserve having their own repo, unless I believe that's appropriate.

### Dir structure
The directory structure should be as follows:
```
random-stuff
├── language-name
│   ├── .gitignore
│   ├── .envrc
│   ├── .language-specific-file
│   ├── flake.lock
│   ├── flake.nix
│   └── project-name
│       ├── build-files
│       └── src
│           ├── random.mod
│           └── random.hi
├── LICENSE.md
└── README.md
```
This lets me have a [Nix](https://nixos.org/) shell flake, loaded through [direnv](https://direnv.net/), and gitignore per language.

### Requirements
That means, to properly use this repo, the following are required:
- Nix, with flakes/experimental-features enabled\
And the following are recommended:
- Direnv

Direnv here is used to automatically load a Nix shell, set up with any tools needed for a given language.

## Licensing
Everything here is licensed under the ISC License.

<hr>

<p align="center">
    Nya~ :3
</p>
