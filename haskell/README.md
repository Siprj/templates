# How to use this template

## Cloning


```bash
git clone https://github.com/Siprj/templates ~/.pi_templates/templates
pi init templates/haskell ${PROJECT_NAME}
```

## CI

Change `tested-with` to what ever suits you and regenerate the Haskell CI with:

Get supported GHC versions:
```
haskell-ci list-ghc
```

Regenerate workflows:

```
haskell-ci github cabal.project
```

## Last thing

Modify the README to suit your needs! :)

# Commit messages

Commit messages are check against the
[Conventional Commits](https://www.conventionalcommits.org/en/v1.0.0/)
specification. The tool used to do the checks is [Convco](https://convco.github.io/)
which can be used on the local machine to create commits and to prepare changelogs.
