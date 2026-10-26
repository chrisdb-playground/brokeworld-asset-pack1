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

### Illicit Criminal Enterprise & Hash Production Nodes
- `assets/hash_grower.png`: Hash Cultivation / Growing Plantation node sprite.
- `assets/hash_process.png`: Hash Processing & Extraction Laboratory node sprite.
- `assets/hash_dealer.png`: Street-level Hash Dealership & Distribution Front node sprite.

### Voyage Vehicles
- `assets/broke_world_voyage_boat.png`: Maritime crossing vessel for Channel and Mediterranean sea voyages.
- `assets/broke_world_voyage_van.png`: Overland transport van for continental transit routes.

### Machine Animations & UI
Only the four machine sheets and their matching icons loaded by Broke World's
`src/presentation/BrokeScene.ts` are included:

| Machine | Sheet in `assets/graphics/entity/` | Icon in `assets/graphics/icons/` |
| --- | --- | --- |
| Crusher | `crusher/crusher-mk3-hr-animation.png` | `crusher-mk3.png` |
| Pressure tank | `pressure-tank/pressure-tank-mk1-north-hr-animation.png` | `pressure-tank-mk1.png` |
| Logistics hub | `logistics-hub/logistics-hub-mk1-hr-animation.png` | `logistics-hub-mk1.png` |
| Industrial press | `industrial-press/industrial-press-mk1-north-hr-animation.png` | `industrial-press-mk1.png` |

The pack contains 25 PNG files in total. Unused machine variants, shadow,
emission, frozen, and icon sprites are excluded.

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
