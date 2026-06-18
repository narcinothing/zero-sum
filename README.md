<p align="center"> <img width="501" height="116" alt="Image" src="https://github.com/user-attachments/assets/0e7a443c-676a-4f4c-8ca7-ee9c6a2a6fd9" /> </p>
<p align="center"> <img width="640" height="358" alt="Image" src="https://github.com/user-attachments/assets/433dcde1-5f30-40a1-88f3-67368e3eb9ea" /> </p>

---

Zero Sum is an Rojo alternative that addresses lot of the problems and overhead with using an VSCode-to-Studio tool while allowing full control of the synchronization process. It's designed to be safe by default without aggressively deleting/overwriting files.

## Why "Zero Sum"?
* **No terminal setups**: Open launcher and sync and manage your projects
* **True two-way sync**: self explanatory, edit scripts and properties without script conflicts.
* **Selective sync**: Choose what descendants to sync on notice, no more nuking your entire local workspace for pulling a repo
* **Duplicate Handling**: Uses the internal IDs of instances instead of names to manage sourcemaps.
* **Proper MeshPart support**: Reliable implementation of MeshPart serialization to be used for ingame assets and maps.
* **Duplicate Instances**: Reads the Unique ID of instances to keep track of duplicated instances instead of relying on the name.

## Compatibility:
* **Native luau-lsp support**: Creates and keeps track of the sourcemap.json for you without needing to rely on LSP Studio-side plugin.
* **Native Script Sync support**: Coexists alongside Roblox's Script Sync feature without fighting for authority.
* Best accompanied with **"Verde" by Dvitash** which recreates the Explorer/Properties tab from Roblox Studio and brings it to VSCode.
