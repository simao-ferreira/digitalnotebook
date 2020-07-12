# Homebrew 

Homebrew is a open-source terminal package manager installation system, mostly used to install applications to macOS systems. (although also works on linux.)

Language: Ruby
Site: https://brew.sh/

## Glossary

Brew allows installation of mostly terminal based application.

Cask is an extension to manage and install graphical applications through brew.

Cellar is the folder used by brew to install the applications

Formula is the package definition of an application

Formulae is the online package browser for homebrew packages

Keg (unsure) binary packages ready to install

Taps adds more repositories to brew formulas

## Commands

General commands
```
# brew list
# brew search <application>
# brew install <application>
# brew cask install <application>
# brew info <application>
```

Update brew installed software
```
# brew update
```

Upgrade homebrew itself
```
# brew upgrade
```

## TIL

Brew allows the installation of different versions of the same application, to move between them
```
# brew switch <application> <version>
```


