# lics2022

Extended abstract for my talk at SYCO 8, 'Normalisation by evaluation for digital circuits'

## Setting up

This project uses *submodules* since I share lots of figures between projects.
After pulling the project, use this to grab the latest content:

```sh
git submodule update --init
```

You may also want to run this whenever you pull.

```sh
git submodule foreach git pull origin main 
```

## GitHub actions

Every time you push with a head commit that starts with `[build]`, the latex will be compiled and put in a release.

## Latest release

* [PDF file](https://github.com/georgejkaye/syco8-abstract/releases/latest/download/syco8-abstract.pdf)
* [Project package](https://github.com/georgejkaye/syco8-abstract/releases/latest/download/syco8-abstract.zip)
