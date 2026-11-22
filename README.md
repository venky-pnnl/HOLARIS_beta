# HOLARIS beta

Windows installers for the HOLARIS manuscript beta archive.

[Download page](https://venky-pnnl.github.io/HOLARIS_beta/) · [GitHub Release](https://github.com/venky-pnnl/HOLARIS_beta/releases/tag/manuscript-beta) · [SHA-256 checksums](https://github.com/venky-pnnl/HOLARIS_beta/releases/download/manuscript-beta/SHA256SUMS.txt)

| Application | Version | Windows installer | Setup BAT inside ZIP |
|---|---|---|---|
| HOLARIS Command Center | V269 | [HOLARIS_Command_Center_V269_Windows.zip](https://github.com/venky-pnnl/HOLARIS_beta/releases/download/manuscript-beta/HOLARIS_Command_Center_V269_Windows.zip) | `Install.bat` |
| FaradaIQ mMZI | v109 | [FaradaIQ_mMZI_V109_Windows.zip](https://github.com/venky-pnnl/HOLARIS_beta/releases/download/manuscript-beta/FaradaIQ_mMZI_V109_Windows.zip) | `FaradaIQ_mMZI_v109/Install_FaradaIQ_mMZI_v109_Windows.bat` |
| FaradaIQ mMZI Motion Control | V053 | [FaradaIQ_mMZI_Motion_Control_V053_Windows.zip](https://github.com/venky-pnnl/HOLARIS_beta/releases/download/manuscript-beta/FaradaIQ_mMZI_Motion_Control_V053_Windows.zip) | `FaradaIQ_mMZI_Motion_v053/Install_FaradaIQ_mMZI_Motion_v053.bat` |
| FaradaIQ HyperspectralCam | v057 | [FaradaIQ_HyperspectralCam_V057_Windows.zip](https://github.com/venky-pnnl/HOLARIS_beta/releases/download/manuscript-beta/FaradaIQ_HyperspectralCam_V057_Windows.zip) | `FaradaIQ_HyperspectralCam_v057/Install.bat` |
| FaradaIQ Spectra Forge | v139 | [FaradaIQ_Spectra_Forge_V139_Windows.zip](https://github.com/venky-pnnl/HOLARIS_beta/releases/download/manuscript-beta/FaradaIQ_Spectra_Forge_V139_Windows.zip) | `Install.bat` |

## Install

Download and extract the complete ZIP to a short local path, then run the setup BAT shown above.

The Command Center installer is reconstructed from its versioned installed folder and restores its private environments using the destination PC’s matching base Python. Setup reports missing Python versions.
Configure the instrument drivers and hardware settings needed on the destination PC.
