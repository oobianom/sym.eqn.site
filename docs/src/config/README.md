---
sidebar: auto
---

# Functions

## envir.prep

- Arguments: `none`
- Description: `Initialize and load library path for package`
- Return type: `NULL`
- Examples: `if(interactive()){
             envir.prep()
             }`

## insert.Symbol.Raw

- Arguments" `symbolid, type = letters[1:4]`
- Description: `Add selected symbol to page`
- Return type: `Inclusion of symbol on page`
- Examples: `if(interactive()){
             insert.Symbol.Raw("sample copied")
             insert.Symbol.Raw("rpkg.net","a")
             }`


## symbol.equation.ui

- Arguments" `none`
- Description: `Assembles the interface for the symbols builder in the Viewer`
- Return type: `Inclusion of symbol on page`
- Examples: `if(interactive()){
             symbol.equation.ui()
             }`


## symbol.equation.ui2

- Arguments" `none`
- Description: `Assembles the interface for the symbols builder as a Modal`
- Return type: `Inclusion of symbol on page`
- Examples: `if(interactive()){
             symbol.equation.ui2()
             }`


