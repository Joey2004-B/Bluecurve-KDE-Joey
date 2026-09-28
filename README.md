# Bluecurve-KDE
Red Hat Bluecurve theme ported to KDE Plasma 6.

In this fork, there are 3 ready-to-use Aurorae window decorations and an improved version of the Bluecurve Plasma theme from the original fork. As of right now, there isn't a color-scheme compatible version of the Bluecurve window decorations yet.


## Requirements (Most of them are required for compiling the non-Aurorae decoration from the original, noted with an *)
- Bluecurve GTK theme (see [neeeeow/Bluecurve](https://github.com/neeeeow/Bluecurve)).
- Bluecurve Qt theme (see [neeeeow/Bluecurve-Qt](https://github.com/neeeeow/Bluecurve-Qt)).
- KDE Plasma 6.3 or newer.
- Qt 6, KF6, KDecoration 3, and GTK 3.0 development libraries. *
- CMake. *

## Installation

### 1. Clone the repository
```
git clone https://github.com/neeeeow/Bluecurve-KDE.git
cd Bluecurve-KDE
```
### 2. Copy Themes
Copy the ```aurorae``` directory to ```~/.local/share/```.

You can copy/move the folder in a graphical file manager like Dolphin or run this command to do this:
```cp -r ~/.local/share```

### 3. Compile & install
```
mkdir build && cd build
cmake ..
make
sudo make install
```
