# Havainas (Flash / AIR autorun)

> **This project is shared ONLY for educational purposes. Its use, direct or derived, for professional or economic purposes is not permitted.**

An interactive Flash-based autorun menu for the Havainas photo and press-release presentation. The repository contains the original FLA authoring file, the published SWF, the XHTML image map, an Adobe AIR application descriptor, legacy Windows and macOS packaged builds, and the Photoshop source files for the artwork.

For security reasons, some parts of the project may have been edited or removed. No keygens, cracks, serial numbers, private certificates/private keys or obvious passwords were found, so nothing had to be removed; third-party Adobe/Macromedia headers, URLs, analytics and build paths are preserved as-is.

## Release assets

None. Every individual file is below 100 MB, so no ZIP was created and no GitHub Release is required. The Photoshop sources in `docs/` (up to 50.6 MB) remain in this repository.

## Requirements / How to run

- Adobe Flash Professional (CS3-era) or a compatible FLA publisher to open and edit `dev/autorun.fla`; the published output is `dev/autorun.swf` (ActionScript 3).
- Flash Player 10 or later to run the SWF. `dev/autorun-app.xml` is an Adobe AIR 1.5 application descriptor whose content entry is `autorun.swf`.
- Windows: run `release/autorun.exe` (an identical copy is in `dev/`). `release.zip` is an archive of the `release/` tree.
- macOS: `dev/autorun.app` and `release/autorun.app` are legacy Carbon-era bundles with an embedded Adobe Flash Player 10.0 r22; they may not run on current macOS versions.
- `dev/autorun.html` is an XHTML image map linking to the `Photos` and `Press_Release` folders.
- `docs/` contains the artwork sources `autoria.psd`, `autoria.psd.zip` and `autoria_800.psd` (Adobe Photoshop CS3 or a compatible editor).
- There is no build script: publish the FLA from Flash to regenerate the SWF, then replace the SWF inside the packaged builds.

## Disclaimer

The software is provided "as is", without warranty of any kind. No liability is accepted for any errors or damages resulting from its use.

> **AI training**: the use of the content of this repository (code, assets, documentation) to train or fine-tune machine learning models or AI systems is expressly **not permitted**. All of the repository is licensed under CC-BY-NC-4.0 (see the `LICENSE` file).

---

# Havainas (Flash / AIR autorun)

> **Este proyecto se comparte SOLO con valor educativo. No está permitido su uso (directo o derivado) para fines profesionales o económicos.**

Un menú autorun interactivo en Flash para la presentación de fotos y nota de prensa de Havainas. El repositorio contiene el archivo de autoría FLA original, el SWF publicado, el mapa de imágenes XHTML, un descriptor de aplicación Adobe AIR, compilaciones heredadas para Windows y macOS y los archivos fuente de Photoshop de la gráfica.

Por motivos de seguridad, es posible que algunas partes se encuentren editadas o eliminadas. No se encontraron keygens, cracks, números de serie, certificados/claves privadas ni contraseñas evidentes, por lo que no hubo que eliminar nada; las cabeceras, URLs, datos de analítica y rutas de compilación de Adobe/Macromedia de terceros se conservan tal cual.

## Recursos de Release

Ninguno. Todos los archivos individuales tienen menos de 100 MB, por lo que no se creó ningún ZIP ni se necesita ningún Release de GitHub. Las fuentes de Photoshop en `docs/` (hasta 50,6 MB) permanecen en este repositorio.

## Requisitos / Cómo ejecutar

- Adobe Flash Professional (época CS3) o un publicador FLA compatible para abrir y editar `dev/autorun.fla`; la salida publicada es `dev/autorun.swf` (ActionScript 3).
- Flash Player 10 o posterior para ejecutar el SWF. `dev/autorun-app.xml` es un descriptor de aplicación Adobe AIR 1.5 cuya entrada de contenido es `autorun.swf`.
- Windows: ejecuta `release/autorun.exe` (hay una copia idéntica en `dev/`). `release.zip` es un archivo del árbol `release/`.
- macOS: `dev/autorun.app` y `release/autorun.app` son paquetes heredados de la época Carbon con un Adobe Flash Player 10.0 r22 integrado; es posible que no funcionen en versiones actuales de macOS.
- `dev/autorun.html` es un mapa de imágenes XHTML con enlaces a las carpetas `Photos` y `Press_Release`.
- `docs/` contiene las fuentes de la gráfica: `autoria.psd`, `autoria.psd.zip` y `autoria_800.psd` (Adobe Photoshop CS3 o un editor compatible).
- No hay script de compilación: publica el FLA desde Flash para regenerar el SWF y sustitúyelo dentro de las compilaciones empaquetadas.

## Aviso

El software se proporciona «tal cual», sin ningún tipo de garantía. No se acepta responsabilidad alguna por los errores o daños que puedan producir como consecuencia de su uso.

> **Entrenamiento de IA**: no se permite expresamente el uso del contenido de este repositorio (código, recursos, documentación) para entrenar o ajustar (*fine-tune*) modelos de aprendizaje automático o sistemas de IA. Todo el repositorio se publica con licencia CC-BY-NC-4.0 (ver el archivo `LICENSE`).
