# Color settings

Color settings referencing [ECI profiles](https://github.com/grommasdietz/color-profiles-eci/) for Adobe CC. 

## Configuration

Both configurations preserve embedded profiles on RGB and CMYK by default. And ask for action on opening and pasting images with mismatching or missing profiles. 

### Working Spaces
#### ECI Coated
RGB: `eciRGB v2`  
CMYK: `PSO Coated v3 (FOGRA52)`  

#### ECI Unoated
RGB: `eciRGB v2`  
CMYK: `PSO Uncoated v3 (FOGRA52)`  

## Installation

Copy all folders and files to the corresponding paths:

### Preparation
1. Copy the files from the given folder structure to the listed paths:

#### MacOS
```
*/Library/Application Support/Adobe/Color/Settings* 
```

1. Copy the path and use `⇧ Shift + ⌘ Command + G` on finder for "Go to folder…". Then paste and enter to open Settings folder.
2. Copy the folders from the downloaded repository, go to the Settings folder and use `⌥ Option/Alt + ⌘ Command + V` to merge.

#### Windows
```
*C:\Program Files\Common Files\Adobe\Color\Settings*
```
### Activation
1. Open Bridge
2. Choose `Edit > Color Settings`
3. Choose `ECI Coated.csf` or `ECI Uncoated.csf` color setting from the list,
4. select Apply
