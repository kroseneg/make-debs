# Make DEBs for binary Eclipse releases

## Usage

`./make-eclipse-deb [<arch> <flavour>]`

If you run the script without parameters it will fetch possible archs and flavours


## sources.list
```
# amd64
deb [trusted=yes] file:///data/deb/ eclipse/amd64/

# arm64
deb [trusted=yes] file:///data/deb/ eclipse/arm64/
```
