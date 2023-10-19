# EHT M87 Polarized Data

**Authors:** The Event Horizon Telescope Collaboration et al.

**Date:** November, 2023

**Primary Reference:** [The Event Horizon Telescope Collaboration, et al. 2023, ApJL, ___, L___ (M87 Paper IX)](https://doi.org/10.3847/2041-8213/______)

**Data Product Code:** [2023-D01-01](https://eventhorizontelescope.org/for-astronomers/data)

**Brief Description:**

This is a release of calibrated polarimetric data from the Event
Horizon Telescope observations of M87 in 2017.

It consists of 24 data sets covering the 4 observing days (April
5,6,10,11), two frequency bands (high and low) and two calibration
pipelines (HOPS and CASA).

All datasets include absolute EVPA calibration from ALMA and
parallactic angle rotation.

We provide two versions of the HOPS calibrated data.
The base version ("*_hops_ALMArot.uvfits") has no D-term
calibration applied.
The second version ("*_hops_zbl-dtcal+selfcal") has
zero-baseline-derived D-terms (covering ALMA, APEX, SMA, and JCMT)
corrected, but the remaining stations are not corrected.
In addition, this version has all visibility amplitudes and phases
self-calibrated to fiducial images Stokes I images of M87 from the
SMILI pipeline (EHTC+ Paper IV, 2019).
Both versions of the HOPS data have had the relative R/L complex
gains calibrated with a global, multi-source fit (Steel+ 2019).

The CASA data has had all​ D-terms corrected to their reported
values in EHTC+ Paper VII, 2021. It has not been self-calibrated.
The R/L complex gains have been calibrated assuming the intrinsic
Stokes V visibilities are zero. 

**File Name Convention:**

The data files are named in the following convention:

    [Data-Release-Tag]_[Source]_[year]_[day-of-year]_[band]_[pipeline]_[stage].[format]

where datasets without self-calibration has
`[stage]` = `ALMArot` for HOPS and
`[stage]` = `EVPA_rotation+dcal+ampscale+netcal+10s-avg+RLgain-amp` for CASA;
datasets with self-calibration and zero baseline D-term calibration has
`[stage]` = `zbl-dtcal+selfcal` for HOPS.

**Station Code Table:**

| UVFITS Code | Station Name                  | Location |
| ----------- | ----------------------------- | -------- |
| AA          | ALMA                          | Chile    |
| AP          | APEX                          | Chile    |
| AZ          | Submillimeter Telescope       | Arizona  |
| JC          | James Clerk Maxwell Telescope | Hawai'i  |
| LM          | Large Millimeter Telescope    | Mexico   |
| PV          | IRAM                          | Spain    |
| SM          | Submillimeter Array           | Hawai'i  |

**References:**

- [EHT Collaboration Data Portal Website](https://eventhorizontelescope.org/for-astronomers/data)
- [The Event Horizon Telescope Collaboration, et al. 2019a, ApJL, 875, L1 (M87 Paper I)](https://doi.org/10.3847/2041-8213/ab0ec7)
- [The Event Horizon Telescope Collaboration, et al. 2019b, ApJL, 875, L2 (M87 Paper II)](https://doi.org/10.3847/2041-8213/ab0c96)
- [The Event Horizon Telescope Collaboration, et al. 2019c, ApJL, 875, L3 (M87 Paper III)](https://doi.org/10.3847/2041-8213/ab0c57)
- [The Event Horizon Telescope Collaboration, et al. 2019d, ApJL, 875, L4 (M87 Paper IV)](https://doi.org/10.3847/2041-8213/ab0e85)
- [The Event Horizon Telescope Collaboration, et al. 2019e, ApJL, 875, L5 (M87 Paper V)](https://doi.org/10.3847/2041-8213/ab0f43)
- [The Event Horizon Telescope Collaboration, et al. 2019f, ApJL, 875, L6 (M87 Paper VI)](https://doi.org/10.3847/2041-8213/ab1141)
- [The Event Horizon Telescope Collaboration, et al. 2021a, ApJL, 910, L12 (M87 Paper VII)](https://doi.org/10.3847/2041-8213/abe71d)
- [The Event Horizon Telescope Collaboration, et al. 2021b, ApJL, 910, L13 (M87 Paper VIII)](https://doi.org/10.3847/2041-8213/abe4de)
- [The Event Horizon Telescope Collaboration, et al. 2023, ApJL, ___, L__ (M87 Paper IX)](https://doi.org/10.3847/2041-8213/______)
- [Blackburn, L., Chan, C.-k., Crew, G., et al. 2019, arXiv:1903.08832](https://ui.adsabs.harvard.edu/abs/2019arXiv190308832B/abstract)
- [Janssen, M., Goddi, C., van Bemmel, I., et al. 2019, arXiv:1902.01749](https://ui.adsabs.harvard.edu/abs/2019arXiv190201749J/abstract)
- [Issaoun, S., Folkers, T., Blackburn, L., et al. 2017, EHT Memo 2017-CE-02](https://eventhorizontelescope.org/for-astronomers/memos)
- [Janssen, M., Blackburn, L., Issaoun, S., et al. 2019, EHT Memo 2019-CE-01](https://eventhorizontelescope.org/for-astronomers/memos)
- [Wielgus, M., Blackburn, L., Issaoun, S., et al. 2019, EHT Memo 2019-CE-02](https://eventhorizontelescope.org/for-astronomers/memos)
