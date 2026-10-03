# Lumen Restyled

<p align="center">
  <img alt="Version" src="https://img.shields.io/badge/version-1.0-7c5cff?style=for-the-badge">
  <img alt="Language" src="https://img.shields.io/badge/Luau-Roblox-00A2FF?style=for-the-badge&logo=roblox">
  <img alt="Library" src="https://img.shields.io/badge/UI-Lumen%20Restyled-24c76a?style=for-the-badge">
</p>

## Window

### `Window(options)`

Creates the main window and returns the object used to add tabs, panels, and dock buttons.

```lua
Lumen:Window({
	Title = "A Hub";
	Footer = "A Footer";
})
```

| Option | Type |
| --- | --- |
| `Title` | `string` |
| `Footer` | `string` |


## Tabs and subtabs

### Standard tab

```lua
local Page = Window:Page({Icon = "house"})
```

### Subtabs

```lua
local SubPage = Page:SubPage({ Name = "SubPage" })
```

