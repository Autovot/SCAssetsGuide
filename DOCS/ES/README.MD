# Guia conseguir los assets Star Citizen

> A partir del comprimido del juego, `Data.p4k`, conseguir los assets del mismo

> De momento solo voy hacer la guia para conseguir los modelos 3D simplemente.
> El audio se como conseguirlos pero es muy dificil saber que audio es que

## Juego

- [Star Citizen](https://robertsspaceindustries.com/download)

## Aplicaciones

- [dolkensp/unp4k](https://github.com/dolkensp/unp4k) - [[latest]](https://github.com/dolkensp/unp4k/releases/latest) - (`unp4k-suite-vX.XX.XX.zip`)
- [Markemp/Cryengine-Converter](https://github.com/Markemp/Cryengine-Converter) - [[latest]](https://github.com/Markemp/Cryengine-Converter/releases/latest) - (`cgf-converter.exe`)

### Aplicaciones opcionales para abrir los modelos

- [OpenCTM](http://openctm.sourceforge.net/?page=download) - (`OpenCTM-X.X.X-setup.exe`) - (`.obj`)
- [Blender](https://www.blender.org/download/) - (`.obj`, `.dae`)
- [FreeCAD](https://www.freecadweb.org/downloads.php) - (windows) - (`.dae`)

### Investigando

- [Madfish71/SCTextureConverter](https://github.com/Madfish71/SCTextureConverter)

## Requisitos

1. Star Citizen, si no lo tienes.
2. 300GB de espacio libre en un disco
3. Tener descargado las aplicaciones necesarias (de momento solo unp4k y Cryengine-converter)
4. El open ctm es opcional si no tienes

### File strcuture example

```text
APP
├─ unp4k-suite
│   ├─ unforge.exe
│   ├─ unp4k.exe
│   ├─ unp4k.gui.exe
│   └─ etc...
├─ Argovot.sh1
└─ cgf-converter.exeAPP
```

##