# WARFRONT FIVE — Version 2.0 (Arcade Unit Gallery + Color Lab)

Five-player fictional multiplayer strategy game using real-world OpenStreetMap geography as a *visual backdrop*. All missile and vehicle actions are virtual game effects, not real targeting or control.

## What's new

- Five selectable catalog tabs: ATV, UAV, Tanks, Missiles, Other Vehicles.
- Seven uploaded user missile photographs are used as actual thumbnail images on the missile tab. The historical missile names are **illustrative game references** and are not claimed to be verified identifications of the items in each picture.
- Choose a missile item, press **PLACE SELECTED GAME ITEM**, and tap the map to display a temporary **fictional visual effect** for all five participants. Choosing a vehicle places a simulated marker.
- New **COLOR & SIGNAL FX** panel: Grit, Grit Size, Hue, Saturation, Brightness, and Glitch.
- Switch filter target between **FULL GAME INTERFACE** and **WAR CAM ONLY**. Profiles save locally in the browser. Reset is available.
- Previous public team chat, five-player cap, Red/Blue teams, calls and permission-controlled camera sharing are retained.
- No changes to real devices or real aircraft; no tactical or missile performance information is represented by the game.

## Run locally

Requires Node.js 18+. No npm dependencies:

```bash
npm start
```

Then visit `http://localhost:3000`.

## Deploy via GitHub + Render

1. Create a GitHub repository and upload the contents of this folder, keeping `public/assets` intact.
2. Create a Render Web Service and connect the repository.
3. Build command: `npm install`; start command: `npm start`.
4. Open the generated HTTPS link in a browser. The map tile service requires internet access.

## Limitations

Camera/microphone permission requires HTTPS (outside localhost). Peer-to-peer WebRTC may need a TURN relay on some networks. This is a prototype: no verified accounts, no persistent game database, and no production reliability guarantees. Game sessions and history reset on server restart. Some browsers may not support every call mode.
