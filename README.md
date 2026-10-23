# Broke World — Asset Pack 1

Static graphics, spritesheets, entity animations, and tile assets for **Broke World**.

## Contents

- `assets/sandy.png`: Background floor tile texture.
- `assets/water-tile.png`: Region dividing water tile texture.
- `assets/graphics/entity/`: High-resolution machine animations (crushers, pressure tanks, logistics hubs, industrial presses, etc.).
- `assets/graphics/icons/`: UI and map entity icons.

## Usage in Broke World

When installing dependencies in the main `brokeworld` repository:

```json
{
  "dependencies": {
    "brokeworld-asset-pack1": "git+ssh://git@github.com/chrisdb-playground/brokeworld-asset-pack1.git"
  }
}
```

Running `npm install` in `brokeworld` will automatically copy the assets from `node_modules/brokeworld-asset-pack1/assets` into `public/` via the postinstall script.
