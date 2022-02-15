# voxwriter
Blender 2.8 addon to export to the MagicaVoxel .vox format

Exports the selected object to a .vox and optionally creates a palette

### Installation
First download the latest release zip

To install, click "Install..." in Blender Preferences > Add-ons and select the zip.

# TODO

- doesn't support emissive -> glow
- doesn't support emissive image maps
- doesn't support alpha maps
- does it even support diffuse?
- does it support procedural textures?
- need to apply modifiers before voxelisation
- correct palettezation can't be done in one pass
- chunking into 256^3 sections
- bresenham rectification--jagged lines/sampling bias
- topology-aware voxelization--if geometry too thin
- consider working from andstor/voxelizer instead, as GLTF is a more widely supported interchange format and a radically smaller feature set, fewer cases to consider