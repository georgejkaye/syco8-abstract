# syco8-abstract

Extended abstract for my talk at SYCO 8, 'Normalisation by evaluation for digital circuits'

## Setting up

This project uses *submodules* to share diagrams and things between repos.
To make sure you have them all pulled, do this to initialise them:

```sh
git submodule update --init
```

Occasionally you might want to do this to update the submodules:

```sh
git submodule foreach git pull origin main 
```

## GitHub actions

Every time you push with a head commit that starts with `[build]`, the latex will be compiled and put in a release.

## Latest release

* [PDF file](https://github.com/georgejkaye/syco8-abstract/releases/latest/download/syco8-abstract.pdf)
* [Project package](https://github.com/georgejkaye/syco8-abstract/releases/latest/download/syco8-abstract.zip)
