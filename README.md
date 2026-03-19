# BEbags

BEbags is a MacroQuest Lua script for AscendantEQ that combines the contents of all carried bags into one easy-to-read window and includes a synced bank browser.

## Features

- Unified inventory view across all carried bags
- Synced bank view with automatic bank snapshot refresh while banking
- Deposit button that prefers existing partial stacks before using an empty slot
- Double left click to inspect an item
- Right click to use/click items
- Ctrl + right click to vendor-sell the full stack while a merchant window is open
- Quick launcher with left / right / middle click actions
- Sorting by bag order, value, and item name
- Slot usage display (`used/total`)
- Diablo-style UI theme with config and help windows
- Saved settings and cached bank snapshot files

## Requirements

- MacroQuest with Lua enabled
- AscendantEQ-compatible UI behavior
- The `mq` and `ImGui` Lua modules available in MacroQuest

## Installation

1. Copy `BEbags.lua` into your MacroQuest `lua` folder.
2. Start the script in game with:

```text
/lua run BEbags
```

## Commands

```text
/BEbags                  Toggle config window
/BEbags config           Toggle config window
/BEbags packed           Set packed mode
/BEbags full             Set full mode
/BEbags showempty        Show empty slots in full mode
/BEbags hideempty        Hide empty slots in full mode
/BEbags inventory        Switch to inventory view
/BEbags bank             Switch to bank view
/BEbags deposit          Auto-deposit the cursor item
/BEbags depositmode      Toggle manual deposit mode
/BEbags syncbank         Manually sync bank snapshot
/BEbags save             Save settings
/BEbags reset            Reset defaults
/BEbags autoresize on    Enable auto resize
/BEbags autoresize off   Disable auto resize
/BEbags value on         Show value bar
/BEbags value off        Hide value bar
/BEbags right on         Enable right click actions
/BEbags right off        Disable right click actions
/BEbags show             Show main window
/BEbags hide             Hide main window
/BEbags toggle           Toggle main window
/BEbags launcher show    Show launcher
/BEbags launcher hide    Hide launcher
/BEbags help             Toggle help window
```

## Launcher controls

- **Left click:** show or hide the main window
- **Right click:** open or close config
- **Middle click:** open quick actions

## How bank syncing works

- Open a bank window and BEbags will automatically refresh the bank snapshot.
- While the bank is open, the bank view is live.
- Away from the bank, the bank view shows the most recently synced snapshot.
- Cached bank view is browse-only.

## Notes

- Bank deposits require the bank window to be open.
- Cached bank entries are not interactive.
- Some behavior depends on AscendantEQ and MacroQuest UI/window naming.

## Files created by the script

BEbags writes these files in your MacroQuest config directory:

- `BEbags_settings.lua`
- `BEbags_bank_cache.lua`

## GitHub release checklist

Recommended repository contents:

```text
BEbags.lua
README.md
LICENSE
CHANGELOG.md
.gitignore
```

## Credits

Created by BlackeagleEQ with iterative design and implementation support from ChatGPT.
