<p align="center">
  <img width="501" alt="Image" src="https://github.com/user-attachments/assets/0e7a443c-676a-4f4c-8ca7-ee9c6a2a6fd9" />
</p>
<p align="center"> <img width="640" height="358" alt="Image" src="https://github.com/user-attachments/assets/433dcde1-5f30-40a1-88f3-67368e3eb9ea" /> </p>

---

Zero Sum is an Rojo alternative that addresses lot of the problems and overhead with using an VSCode-to-Studio tool by giving you full control of the synchronization process. It's designed to be safe by default without aggressively deleting/overwriting files.

## Why Zero Sum?
* **No terminal setups**: Open launcher and sync and manage your projects
* **True two-way sync**: self explanatory, edit scripts and properties without script conflicts.
* **Selective sync**: Choose what descendants to sync on notice, no more nuking your entire local workspace for pulling a repo
* **Proper MeshPart support**: Reliable implementation of MeshPart serialization to be used for ingame assets and maps.
* **Duplicate Instances**: Reliably distinguishes instances with the same name
* **Properties**: Instances have fully editable properties regardless of the class

## Compatibility:
* **Native luau-lsp support**: Creates and keeps track of the sourcemap.json for you without needing to rely on LSP Studio-side plugin.
* **Native Script Sync support**: Coexists alongside Roblox's Script Sync feature without fighting for authority.
* Best accompanied with **"Verde" by Dvitash** which recreates the Explorer/Properties tab from Roblox Studio and brings it to VSCode.

## Credits:

This wouldn't be possible without [Rojo](https://github.com/rojo-rbx/rojo), [Lync](https://github.com/Iron-Stag-Games/Lync), [Argon](https://github.com/argon-rbx/argon) which this project was heavily modeled after + [rbx-dom](https://github.com/rojo-rbx/rbx-dom) which it's heavily built upon. This project was created with the help of AI with some minor tweaks of mine. This is meant to be a internal tool for myself and being shared publicly incase others find it helpful.
