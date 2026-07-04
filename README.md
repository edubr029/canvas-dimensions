<a href="https://modrinth.com/datapack/canvas-dimensions"><img src="https://raw.githubusercontent.com/edubr029/canvas-dimensions/refs/heads/main/pack.png" width="128" align="left"></a>

# Canvas Dimensions

A data pack that adds three flat utility dimensions for building, redstone testing, and creative projects.

## Dimensions

| Dimension | Description | Quick Command |
|-----------|-------------|---------------|
| Void | Empty void with a stone start platform | `/function canvas:tp_void` |
| Redstone | Bedrock + stone + sandstone flatworld, desert biome | `/function canvas:tp_redstone` |
| Plains | Bedrock + stone + dirt + grass flatworld with villages, lakes, and structures | `/function canvas:tp_plains` |

## Usage

### Dialog Menu

Open the dimension picker dialog:

```
/function canvas:menu
```

The dialog is also available from the **pause menu** (press Esc) and the **Quick Actions** hotkey — no command needed.

### Quick Teleport

For players who prefer commands over the dialog:

| Command | Action |
|---------|--------|
| `/function canvas:tp_void` | Teleport to Void |
| `/function canvas:tp_redstone` | Teleport to Redstone |
| `/function canvas:tp_plains` | Teleport to Plains |
| `/function canvas:tp_overworld` | Return to Overworld |
| `/function canvas:menu` | Open dimension picker dialog |

## Installation

1. Download the `.zip` file
2. Place it in your world's `datapacks/` folder
   - **Singleplayer**: `.minecraft/saves/<world>/datapacks/`
   - **Multiplayer**: `<server>/world/datapacks/`
3. Open the world (world generation changes require reopening the world — `/reload` is not sufficient for dimensions)

## Compatibility

- **Java Edition 26.1 – 26.2** (pack format 101.1 – 107)

