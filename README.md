# HOLARIS beta

HOLARIS beta coordinates multimodal laboratory workflows on Windows. It brings instrument motion, interferometry, hyperspectral imaging, and Raman spectroscopy into the same experimental session so observations can be traced to workflow steps and sample conditions.

[Download page](https://venky-pnnl.github.io/HOLARIS_beta/) · [SHA-256 checksums](https://github.com/venky-pnnl/HOLARIS_beta/releases/download/manuscript-beta/SHA256SUMS.txt)

| Application | Version | Windows installer | Setup BAT inside ZIP |
|---|---|---|---|
| HOLARIS Command Center | V269 | [HOLARIS_Command_Center_V269_Windows.zip](https://github.com/venky-pnnl/HOLARIS_beta/releases/download/manuscript-beta/HOLARIS_Command_Center_V269_Windows.zip) | `Install.bat` |
| FaradaIQ mMZI | v109 | [FaradaIQ_mMZI_V109_Windows.zip](https://github.com/venky-pnnl/HOLARIS_beta/releases/download/manuscript-beta/FaradaIQ_mMZI_V109_Windows.zip) | `FaradaIQ_mMZI_v109/Install_FaradaIQ_mMZI_v109_Windows.bat` |
| FaradaIQ mMZI Motion Control | V053 | [FaradaIQ_mMZI_Motion_Control_V053_Windows.zip](https://github.com/venky-pnnl/HOLARIS_beta/releases/download/manuscript-beta/FaradaIQ_mMZI_Motion_Control_V053_Windows.zip) | `FaradaIQ_mMZI_Motion_v053/Install_FaradaIQ_mMZI_Motion_v053.bat` |
| FaradaIQ HyperspectralCam | v057 | [FaradaIQ_HyperspectralCam_V057_Windows.zip](https://github.com/venky-pnnl/HOLARIS_beta/releases/download/manuscript-beta/FaradaIQ_HyperspectralCam_V057_Windows.zip) | `FaradaIQ_HyperspectralCam_v057/Install.bat` |
| FaradaIQ Spectra Forge | v139 | [FaradaIQ_Spectra_Forge_V139_Windows.zip](https://github.com/venky-pnnl/HOLARIS_beta/releases/download/manuscript-beta/FaradaIQ_Spectra_Forge_V139_Windows.zip) | `Install.bat` |

## Explore an experiment dataset

Zenodo record S000038 documents three magnet approach–retraction cycles in nominally 1 M aqueous dysprosium nitrate. Command Center workflow records provide the sequence and acquisition context. Stage encoder readbacks can be aligned with mMZI camera timestamps to compare optical phase with measured motion. Raman kinetic series and hyperspectral transmission and emission scans provide complementary spectral observations.

[View dataset on Zenodo](https://zenodo.org/records/24433153) · [DOI 10.5281/zenodo.24433153](https://doi.org/10.5281/zenodo.24433153)

## Install

Download and extract the complete ZIP to a short local path, then run the setup BAT shown above.

The Command Center installer is reconstructed from its versioned installed folder and restores its private environments using the destination PC’s matching base Python. Setup reports missing Python versions.
Configure the instrument drivers and hardware settings needed on the destination PC.
