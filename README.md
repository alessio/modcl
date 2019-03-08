# modcl
Dumb tool to maintain modular changelogs

```
$ ./modcl -help
usage: modcl DIRECTORY COMMAND

Commands:
    init
    add SECTION STANZA            Add an entry file.
                                  Read from stdin until it
                                  encounters EOF.
    generate [VERSION]            Generate a changelog in
                                  Markdown format and print it
                                  to stdout. VERSION defaults
                                  to UNRELEASED.

    Sections             Stanzas
         ---                 ---
    breaking                gaia
    features             gaiacli
improvements            gaiarest
    bugfixes                 sdk
                      tendermint

```
