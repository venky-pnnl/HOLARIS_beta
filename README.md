# HOLARIS beta

**[Open the HOLARIS beta website](https://venky-pnnl.github.io/HOLARIS_beta/)**

HOLARIS beta is Windows software for multimodal laboratory experiments. It coordinates instrument motion, interferometry, hyperspectral imaging, and Raman spectroscopy within a common experiment session. Workflow events and instrument records help you trace what happened before, during, and after a change in experimental conditions.

[Workflow overview](https://venky-pnnl.github.io/HOLARIS_beta/#overview) · [Example dataset](https://venky-pnnl.github.io/HOLARIS_beta/#dataset) · [Windows downloads](https://venky-pnnl.github.io/HOLARIS_beta/#downloads)

## How the apps work together

1. **Plan and run the sequence in Command Center.** Define the order of motion and acquisition steps and record operator checkpoints.
2. **Record the stimulus or stage motion.** Motion Control positions the magnet and supported stages. Encoder readbacks show when the stage moved and reached its target.
3. **Compare the measurements.** Use acquisition timestamps and workflow records to relate optical phase, wavelength-resolved images, and Raman spectra to the conditions under which they were collected.

## Windows apps and downloads

| Application | Version | What it does | Installer | Setup BAT inside ZIP |
| --- | --- | --- | --- | --- |
| **HOLARIS Command Center** | V269 | Define the workflow, coordinate supported steps across apps, and record when motion, acquisitions, and operator checkpoints occur. | [Download ZIP](https://github.com/venky-pnnl/HOLARIS_beta/releases/download/manuscript-beta/HOLARIS_Command_Center_V269_Windows.zip) | `Install.bat` |
| **FaradaIQ mMZI** | v109 | Capture off-axis Mach–Zehnder interferograms and reconstruct optical phase to follow where and when the sample response changes. | [Download ZIP](https://github.com/venky-pnnl/HOLARIS_beta/releases/download/manuscript-beta/FaradaIQ_mMZI_V109_Windows.zip) | `FaradaIQ_mMZI_v109/Install_FaradaIQ_mMZI_v109_Windows.bat` |
| **FaradaIQ mMZI Motion Control** | V053 | Position supported stages and the magnet, repeat approach and retraction moves, and record measured position through encoder readbacks. | [Download ZIP](https://github.com/venky-pnnl/HOLARIS_beta/releases/download/manuscript-beta/FaradaIQ_mMZI_Motion_Control_V053_Windows.zip) | `FaradaIQ_mMZI_Motion_v053/Install_FaradaIQ_mMZI_Motion_v053.bat` |
| **FaradaIQ HyperspectralCam** | v057 | Collect spectral information at each image pixel and map wavelength-dependent transmission or emission across the sample. | [Download ZIP](https://github.com/venky-pnnl/HOLARIS_beta/releases/download/manuscript-beta/FaradaIQ_HyperspectralCam_V057_Windows.zip) | `FaradaIQ_HyperspectralCam_v057/Install.bat` |
| **FaradaIQ Spectra Forge** | v139 | Acquire Raman spectra and time series to compare vibrational bands under different sample or field conditions. | [Download ZIP](https://github.com/venky-pnnl/HOLARIS_beta/releases/download/manuscript-beta/FaradaIQ_Spectra_Forge_V139_Windows.zip) | `Install.bat` |

[SHA-256 checksums](https://github.com/venky-pnnl/HOLARIS_beta/releases/download/manuscript-beta/SHA256SUMS.txt)

## Example dataset · S000038

This experiment followed three magnet approach–retraction cycles in nominally 1 M aqueous dysprosium nitrate, Dy(NO₃)₃. The dataset includes native instrument data, acquisition metadata, workflow records, file manifests, and checksums.

| Application | Records in S000038 | What to look for |
| --- | --- | --- |
| Command Center | Workflow steps, event timestamps, and acquisition metadata | Reconstruct the sequence and identify which measurements belong to each step. |
| Motion Control | Magnet-stage encoder readbacks | Find when the magnet approached, reached position, and retracted. |
| mMZI | Native interferogram stacks, reference frames, wrapped phase maps, and camera timestamps | Align camera timestamps with encoder readbacks to examine phase changes during measured motion. |
| HyperspectralCam | White-light transmission and He–Cd-excited Dy³⁺ emission scans | Examine the spatial distribution of transmission and dysprosium emission. |
| Spectra Forge | Raman kinetic series before approach, at the cuvette, and after retraction | Compare vibrational bands across the three magnet positions. |

[View the dataset on Zenodo](https://zenodo.org/records/24433153) · [DOI 10.5281/zenodo.24433153](https://doi.org/10.5281/zenodo.24433153)

## Install on Windows

1. Download the ZIP for the application you need and extract it to a short local path.
2. Run the **Setup BAT inside ZIP** shown in the app table. Command Center V269 requires Python 3.12 and uses it to restore its private environments.
3. Configure the drivers and hardware settings required by your instruments.

## Acknowledgment

We acknowledge support from the [Non-Equilibrium Transport Driven Separations (NETS) Initiative](https://www.pnnl.gov/projects/nets) at Pacific Northwest National Laboratory (PNNL).
