# zx.star.is
TNFS browser for the ZX Spectrum.

<img width="50%" src="https://user-images.githubusercontent.com/35402248/149202830-f9b31830-a6d4-485c-9326-7a6ecd237b38.png"/>

## Usage
- Browse files by using `opqa` or `cursor` keys.
- Select files by pressing `enter`.
- `.sna` or `.tap` files are detected automatically and mounted with the appropiate basic commands.
- You can inspect the source code by inspecting the basic listing (`shift+spc`, then `K+enter`).
- Boot into 128 or 48 basic by typing `1` or `4`.
- Exit to a different TNFS server by typing `X`.
- Hint: press `shift+enter` to mount tape and boot into 128 basic. you can either load from there, go 48 or USR0.

## Testing on ZX emulator
1. Launch [es.pectrum](https://www.habisoft.com/espectrum/) emulator.
2. Enable Spectranet device on settings, if not already enabled.
3. Go to basic, type `%fsconfig + ENTER`. Hint: `%` is `CTRL+5`.
4. `A` -> `0 + ENTER` -> `zx.star.is + ENTER` -> `C` -> `D`.
5. Reboot emulator `F12`. It should proceed into a custom menu similar to the image pictured above.

<img width="50%" src="https://user-images.githubusercontent.com/35402248/149204271-1d0d2a14-1310-49d8-98fd-f9b6877b81ec.png"/>

## Testing on real hardware
- Tutorial: https://www.youtube.com/watch?v=PmLN2xcRgMw
- Hardware: https://www.bytedelight.com/?page_id=3515
- Firmware: https://github.com/spectrumero/spectranet
- Wiki: http://spectrum.alioth.net/doc/index.php/Main_Page
- Note: Spectranet device required.

## License
Public domain.
