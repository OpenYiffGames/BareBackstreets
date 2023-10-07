# Bare Backstreets v0.7.3
## _Pin bypass patch_

### How to install:

- Download the patch [here](https://github.com/OpenYiffGames/BareBackstreets/releases/v0.7.3)
- Locate your BBS game directory and open it
- Go to ..\Bare Backstreets_Data\Managed
- Find and rename `JasonAfexGames.BareBackstreets.Runtime.dll` to `JasonAfexGames.BareBackstreets.Runtime_old.dll`
- Find and rename `TechSkullStudios.CodeRepository.Controllers.dll` to `TechSkullStudios.CodeRepository.Controllers_old.dll`
- Extract the DLL's from the patch into this same directory
- Open the game and it should skip the pin window
- Have fun! ;)

## Patching the DLL yourself:
The binaries are in IL code. You need to check them by yourself using a decompiler such as `IlSpy` or `DnSpy`.

