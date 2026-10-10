# Third-party notices

PC Monitor is freeware by Artur Słaboszewski (see `LICENSE.txt` / `LICENCJA.txt`). It bundles the following
third-party components, which remain under their own licences. Their full texts are in the `licenses` folder
next to this file.

| Component | Version | Licence | Used for | Licence text |
|---|---|---|---|---|
| [Python](https://www.python.org) | 3.13.16 | PSF-2.0 (with the licences of the bundled libraries) | the runtime | `licenses/python/` |
| [psutil](https://github.com/giampaolo/psutil) | 7.2.2 | BSD-3-Clause | CPU, memory, disk and process readings | `licenses/psutil/` |
| [nvidia-ml-py (pynvml)](https://pypi.org/project/nvidia-ml-py/) | 13.615.71 | BSD-3-Clause | NVIDIA GPU readings (NVML) | `licenses/nvidia-ml-py/` |
| [Pillow](https://github.com/python-pillow/Pillow) | 12.3.0 | MIT-CMU (HPND) | the notification area icon | `licenses/pillow/` |
| [pystray](https://github.com/moses-palmer/pystray) | 0.19.5 | LGPL-3.0 | the notification area icon and its menu | `licenses/pystray/` |
| [six](https://github.com/benjaminp/six) | 1.17.0 | MIT | used by pystray | `licenses/six/` |
| [PyInstaller bootloader](https://pyinstaller.org) | 6.22.3 | GPL-2.0 with the bootloader exception | starts the program | `licenses/pyinstaller/` |

## pystray (GNU LGPL v3)

pystray is shipped as plain Python source files in `_internal\pystray\`, outside the program's archive, so
it can be replaced with a modified or newer compatible version. Its source code is available at
https://github.com/moses-palmer/pystray (the version listed above).

The installer is built with Inno Setup (https://jrsoftware.org/isinfo.php), whose licence permits this use.
