# Scarlet Carson

## Identity

Scarlet Carson is a rose-lit train moving through blue-black night: mask ivory catches the light, brass steadies the room, and crimson roses draw the eye. It should feel cinematic, intimate and watchful, not neon, glossy, cozy or ornamental.

## Palette source

The palette comes from the roses in film frame 2:02:57.

| Role | Colour | Use |
| --- | --- | --- |
| Night ground | `#161922`; `#222532` raised surface | Windows, bars and panels |
| Mask ivory | `#E4DAC4` | Reading text and selected-row text |
| Dim steel | `#7D8797` | Quiet labels, dividers and frames |
| Rose crimson | `#BE1440` | Focus marks, active indicators and selection outlines |
| Wine | `#7A142C` | Selected rows and selection fills |
| Error red | `#F0444A` | Errors and urgent states only |
| Brass | `#BF9A6E`; `#CDB884` | Warm support and graph highlights |
| Rose leaves | `#8FB38E` | Green and success roles |
| Night lavender and blue | `#A8A9D0`; `#8592B8` | Cool support and information roles |
| Wine brown | `#5D1537` | Dark support shade |
| Lifted shades | `bright_*` keys | Lighter steps of their matching palette hues |

## Surfaces

- Hyprland uses a solid dim-ivory active border (`#B8AE96`) and a barely visible inactive border (`rgba(34384a88)`). Red never frames a window.
- The bar shares the window ground. Active workspace and active indicators use crimson sparingly.
- Menu and launcher selected rows use wine fill, mask-ivory text and a 1px crimson outline. Borders stay solid.
- Cava alone uses a colour ramp: wine through crimson and brass to ivory. btop uses muted frames, wine-to-crimson-to-brass graphs, wine selection and brass upload.
- GTK, Zen, Zed and Base24 use the same roles. Icons use Yaru-red.
- In Vencord, crimson marks states and focus; it never draws structural frames or dividers.

## Wallpapers

The seven backgrounds move from the station and dominoes to the rose train, tunnel and Westminster, then up to Lady Justice and a rooftop window:

- `01-station.png`
- `02-dominoes.png`
- `03-rose-train.png`
- `04-tunnel.png`
- `05-westminster.png`
- `06-justice.png`
- `07-rooftops.png`

## Guardrails

Keep large surfaces blue-black and keep crimson rare. Reserve error red for errors and urgency; use crimson only for focus, active markers and selection outlines. Keep other surfaces flat, with Cava's requested ramp as the single gradient. Do not add extra backgrounds, Lua files or terminal configuration files.
