# Changelog

## [1.7.2](https://github.com/Nandoby/LazyVim/compare/v1.7.1...v1.7.2) (2025-04-06)


### Bug Fixes

* **leap:** don't use the x and X mappings in visual mode ([3bce81f](https://github.com/Nandoby/LazyVim/commit/3bce81fc566ef3c3b369a9bd85e0051c544047a3))

## [1.7.1](https://github.com/Nandoby/LazyVim/compare/v1.7.0...v1.7.1) (2025-04-06)


### Bug Fixes

* **lsp:** remove debug ([3cd44cc](https://github.com/Nandoby/LazyVim/commit/3cd44cc949aed5550ce636404859eca5267f5b49))

## [1.7.0](https://github.com/Nandoby/LazyVim/compare/v1.6.0...v1.7.0) (2025-04-06)


### Features

* **bufferline:** added keymaps to pin and delete non-pinned buffers. ([6ab9cc3](https://github.com/Nandoby/LazyVim/commit/6ab9cc3926cd1ac4bcd68fae8af82811cc9768d9))


### Bug Fixes

* **lsp:** dont use expr=true for lsp rename. ([ea1d811](https://github.com/Nandoby/LazyVim/commit/ea1d811a8ccceefcbf2bfd9d66decf2ecdca22a9))

## [1.6.0](https://github.com/Nandoby/LazyVim/compare/v1.5.0...v1.6.0) (2025-04-06)


### Features

* **lsp:** allow disabling autoformat for certain buffers ([99e6608](https://github.com/Nandoby/LazyVim/commit/99e6608b9af4101d06a6c8269ffe22d8116156f2))

## [1.5.0](https://github.com/Nandoby/LazyVim/compare/v1.4.0...v1.5.0) (2025-04-06)


### Features

* **autocmds:** add groups to autocmds ([b5d11a3](https://github.com/Nandoby/LazyVim/commit/b5d11a3516d7c09aa3f42bad4fed7598376df758))
* **trouble:** keymaps for trouble quicklist / loclist ([21bcd91](https://github.com/Nandoby/LazyVim/commit/21bcd911306b18c02004a1be43cc7a9f26d0a77e))


### Bug Fixes

* **plugins:** lazy-loading on BufReadPre or BufReadPost, should also use BufNewFile ([da2d466](https://github.com/Nandoby/LazyVim/commit/da2d466b36835eb9d31abda4c5f6c270e863cb9c))

## [1.4.0](https://github.com/Nandoby/LazyVim/compare/v1.3.4...v1.4.0) (2025-04-06)


### Features

* **icons:** add copilot icon ([6e3298f](https://github.com/Nandoby/LazyVim/commit/6e3298f3889309d3cc02a3cda34159a2142f733e))


### Bug Fixes

* **keymaps:** move lines with silent and without triggering cmdline ([8371c5c](https://github.com/Nandoby/LazyVim/commit/8371c5c90d77b70e5a8b816f4e6ca09b4ec4d956))
* **keymaps:** silent by default ([05f67d5](https://github.com/Nandoby/LazyVim/commit/05f67d54302edf7347c79233e149a838092596b0))
* **lsp:** properly merge lsp client capabilities ([b6ded22](https://github.com/Nandoby/LazyVim/commit/b6ded22729aed0bd1dd2649cee4361827f51a7a1))
* **mini.indent:** no need to disable indent in alpha dashboard config ([147f453](https://github.com/Nandoby/LazyVim/commit/147f45309b671533900fa73db842345600880c52))
* **mini.surround:** use merged plugin spec to build keys. ([8eaac12](https://github.com/Nandoby/LazyVim/commit/8eaac12bdb1da78d5d940686731241f03d20e8e6))
* **typescript:** typescript extras Keymaps ([01a18bd](https://github.com/Nandoby/LazyVim/commit/01a18bda04d7260b613b38c67a12d8ece0a08d24))

## [1.3.4](https://github.com/Nandoby/LazyVim/compare/v1.3.3...v1.3.4) (2025-04-04)


### Bug Fixes

* **mini.ai:** load ai on VeryLazy. Keymaps interfer with which-key ([9a0f3f3](https://github.com/Nandoby/LazyVim/commit/9a0f3f30bee8663bfdd06a9d0460488881878797))
* **noice:** scroll doc window in normal, insert and select mode ([c58d477](https://github.com/Nandoby/LazyVim/commit/c58d477d3b8c23c7ecfdd91afb4314578ba661fc))
* **nvim-navic:** use kinds icons for navic ([ba5e62b](https://github.com/Nandoby/LazyVim/commit/ba5e62b6da427e7f16b37ae9b18fef3425d9b00a))

## [1.3.3](https://github.com/Nandoby/LazyVim/compare/v1.3.2...v1.3.3) (2025-04-04)


### Bug Fixes

* **lualine:** fixed neo-tree extension ([2b75bfb](https://github.com/Nandoby/LazyVim/commit/2b75bfbc3770e8cb7235c28688122e1faa7c57cc))
* **neo-tree:** disable the `&lt;space&gt;` mapping (you can use `<cr>` instead), to make sure `<leader>` mappings still work ([1c8f528](https://github.com/Nandoby/LazyVim/commit/1c8f5285779b8dea85c12e4970c04942209d6343))
* **neo-tree:** dont change cwd when opening neo-tree ([2735b65](https://github.com/Nandoby/LazyVim/commit/2735b6545f2f8a85f3a0fc3477bb6ac94f531bf1))

## [1.3.2](https://github.com/Nandoby/LazyVim/compare/v1.3.1...v1.3.2) (2025-04-03)


### Bug Fixes

* **bufferline:** plugin was renamed from nvim-bufferline.lua -&gt; bufferline.nvim ([726e00f](https://github.com/Nandoby/LazyVim/commit/726e00feac60877c2645ff57c36b3d5bc83689c2))
* **config:** don't set options to their defaults ([93200fe](https://github.com/Nandoby/LazyVim/commit/93200fe67827f77c29e0b8ce904ecba5db5fc2f6))
* **config:** return defaults when setup was not run yet ([24d0cd3](https://github.com/Nandoby/LazyVim/commit/24d0cd3515c3bc539b2db36d2ec9e1dad33f7009))
* **illuminate:** delete `]]` and `[[` keymaps set by ftplugins ([8ce2264](https://github.com/Nandoby/LazyVim/commit/8ce22648604c7cca546e0edd30445fecb41735f4))

## [1.3.1](https://github.com/Nandoby/LazyVim/compare/v1.3.0...v1.3.1) (2025-04-03)


### Bug Fixes

* **lsp:** again ([34da8ba](https://github.com/Nandoby/LazyVim/commit/34da8baac7b76b8e744d80b1e5d1eff2864dacca))
* **lsp:** check for nvim-cmp instead of cmp ([0d83155](https://github.com/Nandoby/LazyVim/commit/0d83155f4cc59e3c136594745cb114a9f5fef0e9))

## [1.3.0](https://github.com/Nandoby/LazyVim/compare/v1.2.0...v1.3.0) (2025-04-03)


### Features

* added deactivate for neo-tree and noice ([5f1411f](https://github.com/Nandoby/LazyVim/commit/5f1411fba91f644ccbe4bd11ad18bc4ed5c24574))
* **health:** added some simple health checks ([9a18aea](https://github.com/Nandoby/LazyVim/commit/9a18aea54fba08512684d80faeeb0ef4ba8ae4c9))
* **keymaps:** do not create keymaps when a lazy keys handler exists ([355ea64](https://github.com/Nandoby/LazyVim/commit/355ea645448388504a47a7e56bac34efc64798d2))


### Bug Fixes

* **lsp:** `]w` now work as expected ([2a7bbb4](https://github.com/Nandoby/LazyVim/commit/2a7bbb4c286bf860fdf6938736658565f360e9d3))
* **lsp:** only load cmp-nvim-lsp when cmp is enabled ([9458521](https://github.com/Nandoby/LazyVim/commit/945852112730f3edbae1d23ab039946681c1f3b0))
* **options:** don't set GUI font. Fixes ([13563ef](https://github.com/Nandoby/LazyVim/commit/13563efe82fabf127786b27fa99184d0f59eee98))
* **telescope:** bind hidden/ignore to `&lt;a-i&gt;`, `<a-h>` instead of `<c-i>` since thats the same as `<tab>`. ([8052dd7](https://github.com/Nandoby/LazyVim/commit/8052dd73c43bfb21361737bdd001bf98dc43f3b1))

## [1.2.0](https://github.com/Nandoby/LazyVim/compare/v1.1.0...v1.2.0) (2025-04-02)


### Features

* **extras:** added extra for mini.animate. Highly recommended! ([df2d279](https://github.com/Nandoby/LazyVim/commit/df2d279539604cbf56ad5da7401ad1e0ea367772))

## [1.1.0](https://github.com/Nandoby/LazyVim/compare/v1.0.0...v1.1.0) (2025-04-02)


### Features

* install latest stable release of lazy.nvim and LazyVim ([9cf366d](https://github.com/Nandoby/LazyVim/commit/9cf366d90ab2b71346d6cef1c2cae1d3867fab85))
* **lsp:** make it easier to customize LSP keymaps ([c4dd360](https://github.com/Nandoby/LazyVim/commit/c4dd36006fcc30616b0314ed43edca9dc08cda64))
* **lsp:** setup lsp servers not supported by mason-lspconfig and added mason=false to skip server setup by mason ([af5682f](https://github.com/Nandoby/LazyVim/commit/af5682f4c9d9d0edc144f24ae7d949fc34708ca0))


### Bug Fixes

* **core:** use lazy.nvim version configured by the user ([228b442](https://github.com/Nandoby/LazyVim/commit/228b442008365b552a3b8f346fc593569badbc87))
* **indent-blankline:** load on BufReadPost to prevent neo-tree errors ([39f47f9](https://github.com/Nandoby/LazyVim/commit/39f47f9f196d000dea0e11db7e140b79e1fc0b80))
* **keymaps:** switch `&lt;leader&gt;gg` and `<leader>gG` to be consistent with the other keymaps ([8116c27](https://github.com/Nandoby/LazyVim/commit/8116c27e07ec9891728c8c1ac0d38642b0d2f30f))
* **treesitter:** dont add to ensure_installed when "all" ([3f81439](https://github.com/Nandoby/LazyVim/commit/3f81439b839d630406b43ad31a12f6da1069fa34))

## [1.0.0](https://github.com/Nandoby/LazyVim/compare/v0.4.0-alpha...v1.0.0) (2025-04-01)


### Features

* 1.0.0 release ([2a154d4](https://github.com/Nandoby/LazyVim/commit/2a154d4aa4d842618a5ea26ce2356e6e6ce2b8ec))

## [0.4.0-alpha](https://github.com/Nandoby/LazyVim/compare/v0.3.0-alpha...v0.4.0-alpha) (2025-04-01)


### ⚠ BREAKING CHANGES

* **buffer:** remove `<leader>b]` in favor of `]b` and `[b`
* **treesitter:** use `<bs>` in visual mode to shrink delection

### Features

* **buffer:** remove `&lt;leader&gt;b]` in favor of `]b` and `[b` ([a6c88a2](https://github.com/Nandoby/LazyVim/commit/a6c88a21e5e15bfd8e67e1574fc8f2197dbe8d2e))
* **keymaps:** added `[b` and `]b` to switch buffers ([b882d52](https://github.com/Nandoby/LazyVim/commit/b882d52caa475a07d2dd61d3bf86756ae7e0e450))
* **lsp:** ignore lsp servers where setting is set to `false` ([b34cb14](https://github.com/Nandoby/LazyVim/commit/b34cb1440de01c6621509a60a680218fbffccbda))


### Bug Fixes

* **lsp:** there is no declaration in telescope, use vim.lsp ([6b9d426](https://github.com/Nandoby/LazyVim/commit/6b9d426747b134064e9cbf6d1261226d90aa516d))


### Code Refactoring

* **treesitter:** use `&lt;bs&gt;` in visual mode to shrink delection ([40183fc](https://github.com/Nandoby/LazyVim/commit/40183fc0f7dc9a660d03e87bab9102e3a8a4b8a8))

## [0.3.0-alpha](https://github.com/Nandoby/LazyVim/compare/v0.2.2-alpha...v0.3.0-alpha) (2025-03-30)


### ⚠ BREAKING CHANGES

* **todo:** `<leader>xtt` => `<leader>xT`
* **todo:** moved search todo to `<leader>st`
* **telescope:** moved search diagnostics to `<leader>sd`

### Bug Fixes

* **keymaps:** added inspect to `&lt;leader&gt;ui` ([0b2c7c0](https://github.com/Nandoby/LazyVim/commit/0b2c7c00216718f81744f35b16c9c81087fcceb0))


### Code Refactoring

* **telescope:** moved search diagnostics to `&lt;leader&gt;sd` ([1f2a066](https://github.com/Nandoby/LazyVim/commit/1f2a0661672c050c957ad90eb2f6f4f21dda9a28))
* **todo:** `&lt;leader&gt;xtt` => `<leader>xT` ([6c41e06](https://github.com/Nandoby/LazyVim/commit/6c41e0627ece6e731e8c0919c35689fb607252f3))
* **todo:** moved search todo to `&lt;leader&gt;st` ([365cf86](https://github.com/Nandoby/LazyVim/commit/365cf86eaf03f6c3f640b36b88283c26c1d4855b))

## [0.2.2-alpha](https://github.com/Nandoby/LazyVim/compare/v0.2.1-alpha...v0.2.2-alpha) (2025-03-30)


### Bug Fixes

* **windows:** set version=false for treesitter. Last release is too old and broken n Windows ([2d5c2ee](https://github.com/Nandoby/LazyVim/commit/2d5c2ee1dc95964ac582cd9c45c701b929c7bf3d))

## [0.2.1-alpha](https://github.com/Nandoby/LazyVim/compare/v0.2.0-alpha...v0.2.1-alpha) (2025-03-30)


### Features

* **keymaps:** added shortcuts for split and vsplit `&lt;leader&gt;` and `<leader>|` ([75518ba](https://github.com/Nandoby/LazyVim/commit/75518babfd6e38f8493f97d0557f28d59fec1894))
* **mini.surround:** added lazy keys with descriptions to mini.surround ([48c12fd](https://github.com/Nandoby/LazyVim/commit/48c12fd5ea8d155f66b3cd2165d0c3a947c14660))
* **telescope:** added mappings for grep_string `&lt;leader&gt;sw` and colorscheme `<leader>uC` ([859042d](https://github.com/Nandoby/LazyVim/commit/859042d02daf152b3ec24ae4e80ff40345002052))
* **treesitter:** added incremental selection ([916d4b6](https://github.com/Nandoby/LazyVim/commit/916d4b64dad32c5285f6ca30b6a95d028dd9a49a))


### Bug Fixes

* **version:** don't use version for schemastore and nvim-cmp. Last version is too old ([2c27f52](https://github.com/Nandoby/LazyVim/commit/2c27f526b39ec529ad85689f79b5f1e79fe92279))

## [0.2.0-alpha](https://github.com/Nandoby/LazyVim/compare/v0.1.0-alpha...v0.2.0-alpha) (2025-03-30)


### ⚠ BREAKING CHANGES

* **telescope:** moved most `help` keymaps under `<leader>s` (search)
* **neotree:** keymaps are now under `<leader>fe` and `<leader>fE`
* **noice:** noice keymaps are now under `<leader>sn`
* **keymaps:** terminal keymaps are now under `<leader>ft` and `<leader>fT`
* **keymaps:** redraw is now mapped to `<leader>ur` (UI redraw)
* **keymaps:** toggle keymaps can now be found under UI `<leader>u`
* **colorscheme:** LazyVim now loads the colorscheme configured with config.colorscheme. See the docs for more info
* **config:** LazyVim can now be configured like any other plugin with {"LazyVim/LazyVim", opts = ... }. config.settings is deprecated
* **keymaps:** remove keymaps for [p and ]p

### Features

* added vim-repeat. Fixes [#56](https://github.com/Nandoby/LazyVim/issues/56) ([d244117](https://github.com/Nandoby/LazyVim/commit/d244117831a9084cd959b3588affd6fb00e1a7dc))
* **autocmds:** rebalance windows on resize ([7bb3042](https://github.com/Nandoby/LazyVim/commit/7bb30429d766dd90f1dce698dfffdc0b75a29557))
* **colorscheme:** LazyVim now loads the colorscheme configured with config.colorscheme. See the docs for more info ([1075f10](https://github.com/Nandoby/LazyVim/commit/1075f10c245a6cad646d554e8c80ddce8b803bbf))
* **config:** LazyVim can now be configured like any other plugin with {"LazyVim/LazyVim", opts = ... }. config.settings is deprecated ([6abb8e2](https://github.com/Nandoby/LazyVim/commit/6abb8e2db1f814369ff58eb31d33a3bc6c151dc8))
* **config:** show an error when the needed version of `lazy.nvim` is too old ([4c1f3bb](https://github.com/Nandoby/LazyVim/commit/4c1f3bbc87da115d928e7563587e28ab26cad136))
* **keymaps:** added `&lt;leader&gt;r` to redraw and clear hlsearch ([0569009](https://github.com/Nandoby/LazyVim/commit/056900951e6979f7cca2492b03e98c39cb18a9e9))
* **keymaps:** redraw is now mapped to `&lt;leader&gt;ur` (UI redraw) ([34604f7](https://github.com/Nandoby/LazyVim/commit/34604f71585dad2e52757b78e0a859d98a5eb378))
* **keymaps:** remove keymaps for [p and ]p ([409024c](https://github.com/Nandoby/LazyVim/commit/409024cf0d091046bf0fd184b0c10f63cf6d0cfd))
* **keymaps:** toggle keymaps can now be found under UI `&lt;leader&gt;u` ([5f4e01d](https://github.com/Nandoby/LazyVim/commit/5f4e01d6e38a4c1a82f99ede07724b6d77942d9e))
* **lsp:** added `&lt;c-k&gt;` for signature help in insert mode ([d5867b2](https://github.com/Nandoby/LazyVim/commit/d5867b26463c99138c6cd85fe1b04e4e5cb2145f))
* **lsp:** added `opts.autoformat` to be able to disable autoformat by default. Fixes ([df36446](https://github.com/Nandoby/LazyVim/commit/df364469d67578fc154d062a44b1b9effc6e790c))
* **lsp:** allow overriding options for vim.lsp.buf.format ([6714c5b](https://github.com/Nandoby/LazyVim/commit/6714c5b7ca2a8b6526befb00b09b55b35a08f2b4))
* **lsp:** make diagnostics configurable with `{"neovim/nvim-lspconfig", opts = {diagnostics = {}}}`. Fixes ([d0cf306](https://github.com/Nandoby/LazyVim/commit/d0cf3061904fab597435eda35600b4ad226764e4))
* **neo-tree:** added `&lt;leader&gt;e` and `<leader>E` to toggle neo-tree ([9ab4075](https://github.com/Nandoby/LazyVim/commit/9ab4075dcc13c9c48645730211a708703b840d9c))
* **neo-tree:** load neo-tree when specifying a directory on the cmdline ([260bd8a](https://github.com/Nandoby/LazyVim/commit/260bd8a61759c423464ced4ad2252eeac633476e))
* **notify:** delay notifs till replaced or at most 500ms to prevent more prompts ([fa563f3](https://github.com/Nandoby/LazyVim/commit/fa563f350ee9915095e4bb52e3ef64a94ff11e37))
* **notify:** lazy-load nvim-notify to show proper notifs before Noice loads ([78b3e50](https://github.com/Nandoby/LazyVim/commit/78b3e50b5921b1a0e69e945fcad999bae6878ecf))
* **util:** use lazy's notify instead of `vim.notify` ([7720962](https://github.com/Nandoby/LazyVim/commit/77209624c61569a9ccb96c9abbcb6f5295611dc1))


### Bug Fixes

* add tsx treesitter to typescript lang module ([bd64985](https://github.com/Nandoby/LazyVim/commit/bd64985b3d05921e40ce7159b8426bf34402fdfa))
* **autocmds:** load autocmds during startup when argc &gt; 0 ([b8ee373](https://github.com/Nandoby/LazyVim/commit/b8ee373108637dd527ba0ead876724da1bf9d2de))
* **bufferline:** load bufferline on VeryLazy event ([693b060](https://github.com/Nandoby/LazyVim/commit/693b06047fbfd90b9ffc7257d9d7fde7e4954c87))
* **format:** typo timeout -&gt; timeout_ms ([489acb5](https://github.com/Nandoby/LazyVim/commit/489acb56ab2c8afa7dd2bfd89636efb236efdbb9))
* **json:** correct case for SchemaStore.nvim ([d85b143](https://github.com/Nandoby/LazyVim/commit/d85b1434e54e9762bf37fd150231f1ce7aa58f35))
* **keymaps:** `&lt;leader&gt;ur` now does the same as Neovim's better `<c-l>` ([198c618](https://github.com/Nandoby/LazyVim/commit/198c618a3cb1c5ef033b5a6017cf6c3eb35e2353))
* **keymaps:** add missing wk entries for buffer switching; lowercase UI in menu ([22b1f84](https://github.com/Nandoby/LazyVim/commit/22b1f849dba85ad385566a79973e9985951ffcfe))
* **keymaps:** Add unique keymap to toggle relative number ([9c5a174](https://github.com/Nandoby/LazyVim/commit/9c5a174d73b72c11f66140ad009868981fe4ce61))
* **keymaps:** Resolve comment after PR got merged ([88f6ea8](https://github.com/Nandoby/LazyVim/commit/88f6ea887dccbaf7c980cb7603930ce6c6cea148))
* **lsp:** `]d` & `[d` was reversed ([6ccff47](https://github.com/Nandoby/LazyVim/commit/6ccff47892a8643cdee6d5b79befa3296c77be5e))
* **luasnip:** don't set remap=true for `&lt;tab&gt;`. Fixes ([f74bdde](https://github.com/Nandoby/LazyVim/commit/f74bdde2f8f74c31ee58db9fec05d2e52a0886e7))
* **neodev:** use opts instead of config ([1f2b32d](https://github.com/Nandoby/LazyVim/commit/1f2b32d8b49a1553da523fba5dea8c1e330fcdc7))
* **options:** set options with `vim.set_global` ([f87a067](https://github.com/Nandoby/LazyVim/commit/f87a067b32432372521c93ceda55eb3b5405724f))
* **options:** use `vim.opt` and trigger Lazy ui reload when needed. Fixes ([86f369f](https://github.com/Nandoby/LazyVim/commit/86f369f940804fd38aefa9a5c3da906306df7006))
* **plugins:** fix the laziness of all plugins to still work as intended with `config.defaults.lazy = false`. Fixes ([e707bc9](https://github.com/Nandoby/LazyVim/commit/e707bc95ac92e3598ba62765b30ef7e0ce3a6e15))
* **telescope:** highlights are now under `&lt;leader&gt;sH` ([ebf17cb](https://github.com/Nandoby/LazyVim/commit/ebf17cb41cb4c990eb91e41ebd28121c49ac2b93))
* **typescript:** only set ts keymaps for tsserver ([e57e855](https://github.com/Nandoby/LazyVim/commit/e57e8550afdd60e5405e9352ad7820e3af82460e))
* **typescript:** properly check client.name is on_attach ([186cdbf](https://github.com/Nandoby/LazyVim/commit/186cdbf5d01103c3226393ba1477251fb2fdf605))
* **util:** prevent loop for now. Still need to figure out what's causing it ([082f56f](https://github.com/Nandoby/LazyVim/commit/082f56f1891e05a585e615a63dfb4d3664a72f0a))
* **util:** proper fix for lazy notify ([30ee0af](https://github.com/Nandoby/LazyVim/commit/30ee0af4817a7426ef94ae70bbad0bc7f57ce2e0))


### Performance Improvements

* **neodev:** enable experimental pathStrict setting for better sumneko performance ([664f791](https://github.com/Nandoby/LazyVim/commit/664f791b1f36f9b95aacaafb5dd340410dddb084))


### Code Refactoring

* **keymaps:** terminal keymaps are now under `&lt;leader&gt;ft` and `<leader>fT` ([534f644](https://github.com/Nandoby/LazyVim/commit/534f644d8e9d9cc4834912e56ba2bd1b90dd65f7))
* **neotree:** keymaps are now under `&lt;leader&gt;fe` and `<leader>fE` ([cec2fa1](https://github.com/Nandoby/LazyVim/commit/cec2fa103131ba566772877a9caf804f2419bdf3))
* **noice:** noice keymaps are now under `&lt;leader&gt;sn` ([1217a35](https://github.com/Nandoby/LazyVim/commit/1217a359f949508e11c48ba53e14e632d787e2b8))
* **telescope:** moved most `help` keymaps under `&lt;leader&gt;s` (search) ([ff49685](https://github.com/Nandoby/LazyVim/commit/ff4968542e9aa4ec5b80fc4e1b15a8d5aedc7e9c))

## 0.1.0-alpha (2025-03-29)


### ⚠ BREAKING CHANGES

* **plugins:** plugins now use lazy.nvim's new `opts` property to make it far easier to override options
* **init:** disable init.lua and show a message on how to use LazyVim
* **lsp:** move servers to lspconfig plugin spec
* **keymaps:** switching buffers now uses shift + hl keys
* **keymaps:** resizing windows now uses ctrl + arrow keys
* **keymaps:** move to window now uses ctrl hjkl
* **lsp:** move signature help from `<-k>` to `gK`

### Features

* added leap and flit ([406475b](https://github.com/Nandoby/LazyVim/commit/406475b3e74fff8e554a9ee35b7733d509a70a89))
* added mini.ai for better text objects ([25f8f83](https://github.com/Nandoby/LazyVim/commit/25f8f83d2dd7052ade7163e58b2f891843bbfc47))
* added mini.indentscope ([9504d50](https://github.com/Nandoby/LazyVim/commit/9504d5024130b4c5969964efe5a528a6125d2c02))
* added mini.surround ([480ddef](https://github.com/Nandoby/LazyVim/commit/480ddef0f3d8c4b0d220266853e93d245be7866f))
* added persistence ([de2badb](https://github.com/Nandoby/LazyVim/commit/de2badb542c2edc314a89332cd560d92543b8b1c))
* added todo-comments & trouble ([0499caa](https://github.com/Nandoby/LazyVim/commit/0499caa8495d2b426e2809deaff1e9b6bacfd4df))
* added trouble ([a86fbc5](https://github.com/Nandoby/LazyVim/commit/a86fbc5ffb1ff56a18daf8076d50ca0e68c3a042))
* **alpha:** added lazy shortcut ([fd275e2](https://github.com/Nandoby/LazyVim/commit/fd275e2d7bec32b48b161a7d2d57563ff9a9cede))
* **alpha:** added shortcut to restore session ([8573fca](https://github.com/Nandoby/LazyVim/commit/8573fca478f9bff3c5ad17b77a2b5575c613fe85))
* **alpha:** improved colors ([4484684](https://github.com/Nandoby/LazyVim/commit/4484684f52784e0ffc353efde685fa245e0475ca))
* **alpha:** load on VimEnter so we can track its performance ([966b875](https://github.com/Nandoby/LazyVim/commit/966b875b003d414487b984bf28cf91601cd8bc48))
* **autocmds:** checktime on TermLeave and TermClose ([fca4892](https://github.com/Nandoby/LazyVim/commit/fca48921d5712868107a38fb3758ee644e3426dc))
* **autocmds:** set spell and wrap for markdown ([d9da7f9](https://github.com/Nandoby/LazyVim/commit/d9da7f91e3544ffa214b19686993b7004445180b))
* **bufferline:** added diagnostic icons ([5f6c008](https://github.com/Nandoby/LazyVim/commit/5f6c008817b33a56521c0095e723d129765690cd))
* **cmp:** added cmp-emoji ([f0aae67](https://github.com/Nandoby/LazyVim/commit/f0aae67ac8b5e8179bc563e27da82b87b4437111))
* **cmp:** added kind icons ([f0946c4](https://github.com/Nandoby/LazyVim/commit/f0946c48d6cfb3fea72be8d5d1653c253db4b9a6))
* **cmp:** better tab behavior for cmp and luasnip ([d021860](https://github.com/Nandoby/LazyVim/commit/d021860fa8daa38ec50d2c753807bb10c28177e6))
* **cmp:** ghost text ([194d82e](https://github.com/Nandoby/LazyVim/commit/194d82e789e6086bb250e78d7eb075bb52b16141))
* **diagnostics:** added icons ([d77b2f4](https://github.com/Nandoby/LazyVim/commit/d77b2f42e964511fcb4fcf6c364bdc65e985f51f))
* **editor:** added mini.bufremove ([4b0e489](https://github.com/Nandoby/LazyVim/commit/4b0e489d398e7ec5e13216f6465878c0156b8fe1))
* **git:** added lazygit ([81ee568](https://github.com/Nandoby/LazyVim/commit/81ee568b2422967579d9014f232ed6c1f20af5f6))
* **gitsigns:** added gitsigns keymaps ([f7473cf](https://github.com/Nandoby/LazyVim/commit/f7473cf6e301c7981cb968fc5e4756a1e3f1929f))
* **illuminate:** added illuminate ([fee2f01](https://github.com/Nandoby/LazyVim/commit/fee2f0180be638507f59fd65c61fd5e9fc351883))
* **indent-blankline:** better defaults ([48f220e](https://github.com/Nandoby/LazyVim/commit/48f220e380155aba3ded172dce3e28ee6ab47683))
* **init:** disable init.lua and show a message on how to use LazyVim ([9f78306](https://github.com/Nandoby/LazyVim/commit/9f78306f347cfe1cd54b7637bdfdfe67b08ef7e2))
* **keymaps:** added floating terminal ([60f1e9b](https://github.com/Nandoby/LazyVim/commit/60f1e9b7c367b295a9b74d62b0952f02739ed32a))
* **keymaps:** added keymaps for lazygit, new file and vim.show_pos ([cd50fed](https://github.com/Nandoby/LazyVim/commit/cd50fed303fcbde37f183628c74fb09a7e17374a))
* **keymaps:** added missing descriptions ([a9403c0](https://github.com/Nandoby/LazyVim/commit/a9403c08468c250f9ccb42f08393d05a81d3ff49))
* **keymaps:** added missing descriptions ([d848a70](https://github.com/Nandoby/LazyVim/commit/d848a70c74fb7ed8edc4673e72239f2b1207c451))
* **keymaps:** added more keymaps ([8f28f3f](https://github.com/Nandoby/LazyVim/commit/8f28f3fb73e59035a18511da6886523ba64c71d3))
* **keymaps:** added toggle for diagnostics and conceal ([28b85e1](https://github.com/Nandoby/LazyVim/commit/28b85e1e54a7e71085ebe6a2659694741ed22db7))
* **keymaps:** better jk ([40f2d90](https://github.com/Nandoby/LazyVim/commit/40f2d9049092f9b103599341c7d97329e0d0daf0))
* **keymaps:** more keymaps ([3d67cb1](https://github.com/Nandoby/LazyVim/commit/3d67cb18db2bad1cad122ce5395c78583d83258d))
* **keymaps:** move to window now uses ctrl hjkl ([a22436b](https://github.com/Nandoby/LazyVim/commit/a22436b98366b6f5e16da4f2149c08a275933c89))
* **keymaps:** resizing windows now uses ctrl + arrow keys ([45d4d21](https://github.com/Nandoby/LazyVim/commit/45d4d215072186f8d5e7ace9cbfcc12447bba5f3))
* **keymaps:** switching buffers now uses shift + hl keys ([7ed321e](https://github.com/Nandoby/LazyVim/commit/7ed321e2850be78183622e99d753ed8ab027ea75))
* **keymaps:** use regular jk when specifying a count ([f214ac1](https://github.com/Nandoby/LazyVim/commit/f214ac135a67f57eb7eedab1506aa3928c0db7df))
* **lang:** added json support ([bb1b613](https://github.com/Nandoby/LazyVim/commit/bb1b6136dea2feb5da11a984a1051afffac18e27))
* **lazy:** use lazy.nvim HEAD for now till this repo is more stable ([b5258e2](https://github.com/Nandoby/LazyVim/commit/b5258e27600c32403b66a5b71294e1df2bd87bb3))
* **lsp:** allow for custom lsp server setup ([084f981](https://github.com/Nandoby/LazyVim/commit/084f981f32ce974d6eebbe55c1be3efec4e8eff5))
* **lspconfig:** better setup with mason-lspconfig.setup_handlers ([ed1a423](https://github.com/Nandoby/LazyVim/commit/ed1a423e61c13bfadee85fa869d37f2f67318ae7))
* **lsp:** move signature help from `&lt;-k&gt;` to `gK` ([64dd9a5](https://github.com/Nandoby/LazyVim/commit/64dd9a5b9c4729389b990d629abbce3ad69b53a8))
* **lualine:** better lualine with git status, diagnostics and navic lsp information ([682c53f](https://github.com/Nandoby/LazyVim/commit/682c53fcffc0d27bc25faa15bb87e489664d8b7f))
* **lualine:** better lualine with lazy.nvim updates and some noice components ([2b3bebd](https://github.com/Nandoby/LazyVim/commit/2b3bebd064bd9d5bf5658a68ca17bebec2063f3c))
* **lualine:** enabled globalstatus ([0a18217](https://github.com/Nandoby/LazyVim/commit/0a182170793fa90a5c59f859e01b6f98d698e677))
* **mason:** added keymap ([6c9627d](https://github.com/Nandoby/LazyVim/commit/6c9627dc66cb7ce3a877925316de6e207370dc9c))
* **mason:** you can now supply a list of tools you want to have installed ([8e63e21](https://github.com/Nandoby/LazyVim/commit/8e63e2192c6ef6a36a2028291e431bb18f641ec0))
* **neo-tree:** use util.get_root when opening neo-tree ([15a28c9](https://github.com/Nandoby/LazyVim/commit/15a28c99bd8f3192d539ea186a7752e2984b8035))
* **notify:** added keymap to dismiss all notifications ([957bec7](https://github.com/Nandoby/LazyVim/commit/957bec7d644aa9f61fe8027bebc8ee8dd9209d93))
* **notify:** better defaults ([759d832](https://github.com/Nandoby/LazyVim/commit/759d832cf7d7a0fd84eb4fc0f07d11edcbef50be))
* **options:** winminwidth ([7715ff2](https://github.com/Nandoby/LazyVim/commit/7715ff22cd6f842af62a020d8ce402fac1186243))
* **settings:** better default icons ([4a9ed2e](https://github.com/Nandoby/LazyVim/commit/4a9ed2e2285d9a5a50c44e6ba70b30433defa178))
* **spectre:** search and replace in multiple files ([7634804](https://github.com/Nandoby/LazyVim/commit/7634804abee10e4d7ae4b286ee70395a91f343ff))
* **startuptime:** better defaults ([a5aea5f](https://github.com/Nandoby/LazyVim/commit/a5aea5f6321bf40fdc63939360d3fffae3da0db3))
* **telescope:** added a gazillian mappings for Telescope ([4dcf319](https://github.com/Nandoby/LazyVim/commit/4dcf3197ed6a626b400b9fab6e485bdade7b43a5))
* **telescope:** added more mappings ([c4840c0](https://github.com/Nandoby/LazyVim/commit/c4840c0d8904be1a0e6bfde83aef4a8cdb1db670))
* **telescope:** better defaults ([b7dbcbc](https://github.com/Nandoby/LazyVim/commit/b7dbcbc6fe1bcc18acab43c1e8ecc2a05dcff4f2))
* **telescope:** use git_files or find_files for `files` ([d67d96c](https://github.com/Nandoby/LazyVim/commit/d67d96c9c6651d65520a07aac42de2fbff38bd4a))
* **terminal:** double escape to enter normal mode ([15f6c2a](https://github.com/Nandoby/LazyVim/commit/15f6c2ac0174be75f937ef16e6eed3da8a6ef335))
* **treesitter:** don't use auto_install. Use `ensure_installed` instead ([085c60e](https://github.com/Nandoby/LazyVim/commit/085c60e77919835fe1ca3aeecb66cb7a7f4a89ef))
* **typescript:** added extras for typescript ([e6d8fab](https://github.com/Nandoby/LazyVim/commit/e6d8fab2d7ee0dfc044345dbfcfca25d6f416c59))
* **ui:** added noice ([b754726](https://github.com/Nandoby/LazyVim/commit/b754726b62b46c9afef50d8c17351c54c3c3f5ff))
* **util:** added vim-startuptime ([13f2b2e](https://github.com/Nandoby/LazyVim/commit/13f2b2e9d602f84fe34d3ae09ea1191dd3a2a020))
* **util:** float_term using lazy's API ([1bbff30](https://github.com/Nandoby/LazyVim/commit/1bbff30ec4a04f3d6168b2863b8947fed12a4353))
* **util:** telescope helper ([d577508](https://github.com/Nandoby/LazyVim/commit/d5775087a715503f1d2cec95f4176685003ad3ba))
* **util:** util.get_root ([00aacbb](https://github.com/Nandoby/LazyVim/commit/00aacbb1b598696d2991707fa3053997ea6aa833))
* **util:** util.on_attach ([cfd62bd](https://github.com/Nandoby/LazyVim/commit/cfd62bde45775d4e6277acb1861e584833bfc7aa))
* **which-key:** added more group names ([755028a](https://github.com/Nandoby/LazyVim/commit/755028a7e36798c7811acb409359bb919da1b940))
* **which-key:** added more group names ([a07f267](https://github.com/Nandoby/LazyVim/commit/a07f2672090b889122e100ba35cd0afc3e3ce142))
* **which-key:** defined some groups ([5115a81](https://github.com/Nandoby/LazyVim/commit/5115a817e0a11d230e523fd689643134e5d13681))


### Bug Fixes

* **alpha:** make alpha and lazy ui behave with each other ([0af2a41](https://github.com/Nandoby/LazyVim/commit/0af2a41746de4517fc55f9bf9555a0b5919ace49))
* **alpha:** make sure alpha renders when Lazy is open after installing missing plugins ([6573124](https://github.com/Nandoby/LazyVim/commit/6573124eb6cd0471b0a5a75f23cab1b1ceaf8e68))
* **autocmds:** better way of opening file at last location ([cb68507](https://github.com/Nandoby/LazyVim/commit/cb68507b1c5c4aba1f1852fa4f1245772ef62e75))
* **autoformat:** make buf part of the autocmd group name ([6bb778b](https://github.com/Nandoby/LazyVim/commit/6bb778b292a5c99dd448c318f5e60721b5aa038f))
* **cmp:** preselect entries ([ee9de3b](https://github.com/Nandoby/LazyVim/commit/ee9de3b959f34d71e946a077f0734a8ec9241f1e))
* dont disable any builtins ([8993e58](https://github.com/Nandoby/LazyVim/commit/8993e58ceb12bf0d07341d119493c1e826256505))
* **editor:** gitsigns prev/next hunk keymap ([d51c2ab](https://github.com/Nandoby/LazyVim/commit/d51c2ab2d5313692653fe10cca38e884771e868d))
* **editor:** typo and consistency ([#12](https://github.com/Nandoby/LazyVim/issues/12)) ([aedd7b9](https://github.com/Nandoby/LazyVim/commit/aedd7b9172fd449776e176443b94725285f28667))
* fixed highlight on yank ([d287d2a](https://github.com/Nandoby/LazyVim/commit/d287d2a4ecb743b0ecfb6a507829b2fa8ed303c5))
* **indentscope:** added extra filetypes to exclude ([94765cb](https://github.com/Nandoby/LazyVim/commit/94765cbbeb9e4c757373f8537821d5277025850d))
* **indentscope:** Turn off indentscope in Mason ([d7c6c93](https://github.com/Nandoby/LazyVim/commit/d7c6c93463eda135cb31fc2d2f6775e1bd91fcfc))
* **keymaps:** only add vim.show_pos on nightly ([5a2b497](https://github.com/Nandoby/LazyVim/commit/5a2b4978837cb8d24c0b56490313c6037954cb1c))
* **keymaps:** use update instead of write when saving. Fixes [#9](https://github.com/Nandoby/LazyVim/issues/9) ([837f2a9](https://github.com/Nandoby/LazyVim/commit/837f2a95cee8786c676aa92947578cdf20e3419e))
* lazy bootstrap code checked lazypath twice ([e021a0a](https://github.com/Nandoby/LazyVim/commit/e021a0a4805af55d597491b5f53433ed739842cf))
* **leap:** force setting keymaps for leap to make gs work ([1940230](https://github.com/Nandoby/LazyVim/commit/194023052763b1e78357d2f4f0efe809cf6ce6d4))
* load mini.pairs ([eb70d71](https://github.com/Nandoby/LazyVim/commit/eb70d7153ba85454e4dce29ced0f42d351bb8f78))
* **luasnip:** fixed luasnip keymaps ([36b7dd6](https://github.com/Nandoby/LazyVim/commit/36b7dd61fe5a99b97c74c2814b6771a0ebb3311a))
* **luasnips:** better defaults for &lt;tab&gt; behavior ([61bb253](https://github.com/Nandoby/LazyVim/commit/61bb253e6be99d809b9f45653cf685cc304512ea))
* **mini:** dont use version for indentscope and starter for now till 0.7.0 is released ([eb6655e](https://github.com/Nandoby/LazyVim/commit/eb6655e80d2d2240aee805a620b9b48c09fdc7b2))
* **options:** only set splitkeep on Neovim 0.9.0 ([5c30ee7](https://github.com/Nandoby/LazyVim/commit/5c30ee7639cfc93dbd8324a06407e6c75e65675b))
* **persistence:** fixed stop session keymap description ([a23ee48](https://github.com/Nandoby/LazyVim/commit/a23ee485e51650b698ccdc52fcc53c0a767cc950))
* provide LSP server name in setup function ([1c7f09d](https://github.com/Nandoby/LazyVim/commit/1c7f09d78553a22baae37b51331e2bb4b8cf0c45))
* **save:** change to write again to trigger auto-formatting ([57c3456](https://github.com/Nandoby/LazyVim/commit/57c3456921737a022c84b9a96159d59c776b9b73))
* **telescope:** always create a new opts object to prevent caching ([ad830ed](https://github.com/Nandoby/LazyVim/commit/ad830edc129a645f1186f493a4ddb7fb39ac226b))
* **util:** added space in msg when toggling ([0bf310a](https://github.com/Nandoby/LazyVim/commit/0bf310a2ed1ec43c555b768a971885a7cc1b550a))
* **which-key:** set group names for `n` and `v` ([baf4c09](https://github.com/Nandoby/LazyVim/commit/baf4c09af490514e6387986af4f84b732c145125))


### Performance Improvements

* disable some builtin plugins that are replaced by another plugin ([d3d26ff](https://github.com/Nandoby/LazyVim/commit/d3d26ff061e93fed2721fbc810ee70f943a806c1))
* **dressing:** lazy-load on vim.ui function call ([a0db9cc](https://github.com/Nandoby/LazyVim/commit/a0db9cce863622d13ad612efc5bd316ca10767c9))
* lazy-load nvim-notify ([99689a5](https://github.com/Nandoby/LazyVim/commit/99689a51cd6f33de29b1a7fc355f428e5fc4a459))
* load keymaps and autocmds on VeryLazy ([4efd5b5](https://github.com/Nandoby/LazyVim/commit/4efd5b59a51216e87d45e5ae121a5e7cce0c43f7))
* setup which-key inside `config()` and load autocmds and keymaps as normal ([3650fd2](https://github.com/Nandoby/LazyVim/commit/3650fd20d3d669886d2ac44dc81c2f83fa59f264))
* **tokyonight:** use tokyonight api to load colorscheme on startup ([ec662be](https://github.com/Nandoby/LazyVim/commit/ec662be1646b466f7ff0f29a1906e9148a7f160d))


### Code Refactoring

* **lsp:** move servers to lspconfig plugin spec ([4882e3f](https://github.com/Nandoby/LazyVim/commit/4882e3fa477667ffe54e0d22f9c642c62259de8d))
* **plugins:** plugins now use lazy.nvim's new `opts` property to make it far easier to override options ([0506744](https://github.com/Nandoby/LazyVim/commit/050674408b11794be7b5ef97a1633c2f2c3baef0))
