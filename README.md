# Veyosy CS2 Config

**Latest stable version: `v1.0`**

[Download v1.0 ZIP](https://github.com/Veyosy/veyosy-cs2-config/archive/refs/heads/v1.0.zip) · [Download autoexec.cfg](https://raw.githubusercontent.com/Veyosy/veyosy-cs2-config/v1.0/autoexec.cfg) · [Release notes](./RELEASE_NOTES.md)

Personal Counter-Strike 2 configuration by **Veyosy**.

A clean `autoexec.cfg` with my binds, crosshair, viewmodel, radar, HUD, sound and gameplay settings.

## Main settings

| Setting | Value |
|---|---|
| Sensitivity | `1.0` |
| Zoom sensitivity | `1.0` |
| Viewmodel FOV | `68` |
| Viewmodel X / Y / Z | `2.5 / 2.0 / -2.0` |
| FPS limit | `999` |
| UI FPS limit | `200` |
| Max matchmaking ping | `150 ms` |
| First-person tracers | `Off` |
| Enemy team voice | `Muted` |

## Crosshair

| Setting | Value |
|---|---|
| Style | `4` |
| Size | `1` |
| Thickness | `1` |
| Gap | `-4` |
| Dot | `Off` |
| Outline | `Off` |
| Alpha | `255` |

## Binds

| Key | Action |
|---|---|
| `4` | C4 |
| `F` | Flashbang |
| `Q` | Smoke grenade |
| `Mouse 4` | Molotov / Incendiary |
| `Mouse 5` | HE grenade |
| `J` | Toggle voice |
| `T` | Inspect weapon |
| `Space` | Push-to-talk |
| `Mouse Wheel Up` | Jump |
| `Mouse Wheel Down` | Jump |

## Installation

1. Download `autoexec.cfg`.
2. Put it into:

   ```text
   ...\Steam\steamapps\common\Counter-Strike Global Offensive\game\csgo\cfg\
   ```

3. Start CS2.
4. Open the developer console and run:

   ```text
   exec autoexec
   ```

If you prefer, add this to CS2 launch options in Steam:

```text
+exec autoexec.cfg
```

When the config loads correctly, the console should show:

```text
[AUTOEXEC] Veyosy config LOADED
```

## Updating

Replace the old `autoexec.cfg` with the newest stable version from this repository.

See [`CHANGELOG.md`](./CHANGELOG.md) for version history.

## Notes

This is **my personal setup**, not a universal "best CS2 config". Some settings and binds are preference-based, so feel free to change them.

---

**Veyosy** // CS2 // v1.0
