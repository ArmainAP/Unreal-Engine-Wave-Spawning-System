
# Wave Spawning System Plugin for Unreal Engine

Welcome to the **Wave Spawning System**, a plugin for Unreal Engine designed to streamline and enhance the process of creating enemy waves in your game. 

## Features

### DataTable Driven Workflow
- Easily set up, organize and define wave configurations in a single DataTable asset.
- Update wave configurations quickly without modifying blueprints or code.

### Batching System for spawning
- Define clusters of actors (batches) within a wave for granular control.
- Customize each batch independently.

### 🌍 **Multiple Spawning Modes**
1. **Fixed Location Spawn Points**: Use pre-defined spawn points for precise enemy placement.
2. **Randomized Spawning Volumes**: Generate spawn locations randomly within a designated area.

## How It Works

### Wave Composition
- Waves are composed of **batches**, each representing a group of actors.
- Define batches in the DataTable, specifying parameters for each to create diverse and challenging enemy waves.

### Spawning Logic
- Waves progress over time, with each batch spawning its units according to the configured parameters.
- Supports simultaneous and staggered spawning for dynamic gameplay.

## Setup Instructions

1. **Install the Plugin**:
   - Copy the plugin to your Unreal Engine project’s `Plugins` folder.
   - Enable the plugin in the **Edit > Plugins** menu.

2. **Create a DataTable**:
   - Use the provided Wave Configuration DataTable template.
   - Define your wave structure, including batch parameters and spawn modes.

3. **Place Spawn Actors**:
   - Add **Spawn Points** for fixed-location spawning or **Spawning Volumes** for randomized spawning to your level.

4. **Configure and Test**:
   - Reference the DataTable in the Wave Spawning System actor.
   - Customize the wave progression to match your game’s design.
   - Playtest to refine spawn positions, timings, and difficulty.

## Contributing

We welcome contributions! If you have a feature request, bug report, or want to improve the plugin, please open an issue or send a pull request.

## License

This project is released under the AGPL-3.0 license.

If you require a different license or have questions related to licensing, please reach out to adrian.popoviciu@katcodelabs.com.

## Credits

Created by Adrian-Marian Popoviciu. A special thanks to the Unreal Engine community for their valuable feedback and contributions.
