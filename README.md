# Broke World — Asset Pack 1

Static graphics, spritesheets, entity animations, and tile assets for **Broke World**.

## Contents

### Regional Floor Tiles
- `assets/uk_floor.png`: Seamless floor tile texture for the United Kingdom region.
- `assets/french_floor_tile.png`: Cobblestone / paved floor tile texture for the West Europe (France) region.
- `assets/sandy.png`: Desert / arid floor tile texture for the North Africa region.
- `assets/water-tile.png`: Animated water tile texture for maritime crossings (English Channel & Mediterranean Sea).

### Regional Building & Entity Sprites
- **United Kingdom**:
  - `assets/uk_hq.png`: United Kingdom Syndicate Regional Headquarters.
  - `assets/uk_recruiter.png`: United Kingdom Scout Recruiter node.
  - `assets/uk_depot.png`: United Kingdom Stash Depot node.
- **West Europe (France)**:
  - `assets/french_hq.png`: European Operations Regional Headquarters.
  - `assets/french_recruiter.png`: European Scout Recruiter node.
  - `assets/france_workshop.png`: European Workshop / Safehouse node.
- **North Africa**:
  - `assets/morrocan_hq.png`: Moroccan / North African Operations Regional Headquarters.
  - `assets/morrocan_recruiter.png`: Moroccan / North African Scout Recruiter node.

### Voyage Vehicles
- `assets/broke_world_voyage_boat.png`: Maritime crossing vessel for Channel and Mediterranean sea voyages.
- `assets/broke_world_voyage_van.png`: Overland transport van for continental transit routes.

### Machine Animations & UI
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
