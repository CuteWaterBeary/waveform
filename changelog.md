## Changes in 1.7.0-beta1
- Add the ironically missing-until-now waveform display mode (experimental)
- Add 'Pulse' render mode
- Add option to continue processing audio while source is muted
- Add option to adjust maximum volume normalization gain
- Add option to adjust rotation of radial display
- Add Traditional Chinese localization (#44 thanks to Kai Lee)
- Add Italian localization (thanks to Peppe73)
- Attempt to mitigate A/V desync in some setups
- Fix spectrum accuracy, **spectrum graphs will appear slightly "louder" now.**
- Increase 'FFT Size' limit

## Installation
### Windows
Either  
- Use the installer and select your OBS folder.  
or  
- Extract Waveform\_v#.#.#\_x86\_64.zip to the *root* of your OBS folder (e.g. `C:\Program Files (x86)\obs-studio`).

### Linux (Ubuntu 20.04, Flatpak)
<details>
<summary>Click for instructions</summary>

#### Prebuilt Binaries
- Download Waveform\_v#.#.#\_Ubuntu\_x86\_64.deb and install it using your distro's package manager (Debian/Ubuntu only).  

#### Flatpak
- `flatpak install flathub com.obsproject.Studio.Plugin.waveform`  

#### Source Build
- Step-by-step instructions in the [readme](https://github.com/phandasm/waveform/blob/master/README.md#linux).  

Note: Should work for most distros, but do not mix with the .deb package above.
</details>

### MacOS (11.0+, OBS 28+)
<details>
<summary>Click for instructions</summary>

#### Intel Macs
- **Uninstall waveform versions prior to 1.6.0**
- Download Waveform\_v#.#.#\_MacOS\_x86\_64.pkg and run it.  

#### ARM64/Apple Silicon Macs
- Download Waveform\_v#.#.#\_MacOS\_arm64.pkg and run it.  
Note: Use the ARM version only if you have a native ARM build of OBS.
</details>

### [OBS Music Edition 27.2.4 (Windows x64)](https://github.com/pkviet/obs-studio/releases/tag/v27.2.4)
<details>
<summary>Click for instructions</summary>

- Extract for\_OBS\_ME\_only.zip to the *root* of your OBS ME folder (e.g. `C:\Program Files\obs-studio-ME`).
</details>
