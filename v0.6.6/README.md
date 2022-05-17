# Bare Backstreets v0.6.6
## _Login bypass patch_

### How to install:

- Download the patch [here](https://github.com/OpenYiffGames/BareBackstreets/releases/v0.6.6)
- Locate your BBS game directory and open it
- Go to ..\Bare Backstreets_Data\Managed
- Find and rename `JasonAfexGames.BareBackstreets.Runtime.dll` to `JasonAfexGames.BareBackstreets.Runtime_old.dll
- Extract the `JasonAfexGames.BareBackstreets.Runtime.dll` from the patch into this same directory
- Open the game and any password should let you get the full content
- Or you can try to use the password `5378`
- Have fun! ;)

## Patching the DLL yourself:
The binaries are in IL code. If you know what you are doing you can check these two functions `RVA:0x00034DC0` and `RVA: 0x00034E38` and patching then is
really straightforward

