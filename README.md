# Color Settings: ECI

Color settings referencing [ECI color profiles](https://github.com/grommasdietz/color-profiles-eci/) for Adobe Creative Cloud applications. 

## Configuration

Both configurations preserve embedded profiles on RGB and CMYK by default. They ask for action on opening and pasting images with mismatching or missing profiles. 

### Working Spaces
#### ECI Coated
RGB: `eciRGB v2`  
CMYK: `PSO Coated v3`  

#### ECI Unoated
RGB: `eciRGB v2`  
CMYK: `PSO Uncoated v3 (FOGRA52)`  

## Installation

### Preparation
Copy the files from the given folder structure to the corresponding paths:

#### MacOS
```
/Library/Application Support/Adobe/Color/Settings
```

1. Copy the path and use `⇧ Shift` `⌘ Command` `G` on finder for `Go to folder…`. Paste and enter to open the corresponding folder.
2. Copy the folders from the downloaded repository, go to the corresponding folder and use `⌥ Option/Alt` `⌘ Command` `V` to merge.

#### Windows
```
C:\Program Files\Common Files\Adobe\Color\Settings
```

> [!WARNING]  
> Please note that the color settings have been only tested on macOS so far.

### Activation
1. Open Adobe Bridge
2. Go to `Edit > Color Settings` in the menu bar
3. Choose `ECI Coated` or `ECI Uncoated` color setting from the list
4. Select `Apply`
