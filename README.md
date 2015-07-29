Neovim `ghc-mod` Integration
============================

This plugin offers [GhcMod][] support for [Neovim][]. It's still in a very early stage.

* `GhcModCaseSplit`: split the pattern variable under the cursor (saves current file)
* `GhcModAddDecl`: inserting function declaration based on type signature under the cursor (saves current file)
* `GhcModRefine`: prompts for an expression and refines the hole under the cursor (saves current file)

This feature requires `ghc-modi`.

You can configure an explicit path to your `ghc-modi` binary if needed by setting `g:ghc_modi_executable`.

[Demo][]

[Neovim]: http://neovim.io
[GhcMod]: http://www.mew.org/~kazu/proj/ghc-mod/en/
[Demo]: https://vimeo.com/134767975
