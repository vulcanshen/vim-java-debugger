# Changelog

## [1.0.0] - 2026-04-03

### Added

- DAP adapter backend implementing the Debug Adapter Protocol via JDI
- Single-file Java project debugging with incremental compilation
- Breakpoint support (set, toggle, deferred breakpoints for unloaded classes)
- Execution control: continue, step over, step into, step out, pause
- Variable inspection (local scope)
- Stack trace display with correct source path resolution
- stdout forwarding to DAP console
- Breakpoint persistence across Neovim sessions
- Debug mode keymaps (single-key shortcuts during debug session)
- which-key integration for keymap group display
- Customizable breakpoint signs (red dot for breakpoints, arrow for stopped line)
- Automatic project type detection (Maven, Gradle, single file)
- Compiled `.class` files stored in `.vim-java-debugger/build/` to avoid polluting project directory
- `config.status()` API for statusline integration
- Example lazy.nvim plugin spec (`vim-java-debugger.lua`)
