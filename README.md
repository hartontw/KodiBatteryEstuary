# Battery Indicator

Simple battery indicator for Kodi's estuary skin.

### Instalation

1. **Find** skin estuary folder
- Linux: ```/usr/share/kodi/addons/skin.estuary```
2. **Backup** ```media/Textures.xbt``` ```xml/Includes.xml```
2. **Choose** color style folder
3. **Copy** ```skin.estuary``` folder an overwrite original files

### Customization

Raw images are includes.

1. **Create** new folder and name it ```skin.estuary```
2. **Clone** or download [xmbc](https://github.com/xbmc/xbmc)
3. **Copy** xmbc ```media``` folder inside step 1 created folder
4. **Create** a new folder called ```battery``` inside media folder
5. **Put** your images named 0%.png to 100%.png inside ```battery``` folder
5. **Pack** ```skin.estuary``` folder using Kodi [TexturePacker](https://kodi.wiki/view/TexturePacker)
6. **Replace** original ```Texture.xbt``` file with the generated one
