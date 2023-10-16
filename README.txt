EHT M87 Polarized Data
=========================

===========
Background
===========

This is a release of calibrated polarimetric data from the Event Horizon Telescope observations of M87 in 2017. 

It consists of 24 data sets covering the 4 observing days (April 5,6,10,11), two frequency bands (high and low) and two calibration pipelines (HOPS and CASA). 

All datasets include absolute EVPA calibration from ALMA and parallactic angle rotation. 

For the HOPS calibrated data, we have also provided a second version of each data set with both zero-baseline-derived D-terms (covering ALMA, APEX, SMA, and JCMT) and Stokes I self-calibration applied.  

=================================
Datasets without self-calibration 
=================================

April 5 data:
hops_data/April05/hops_lo_3597_M87+ALMArot.uvfits
hops_data/April05/hops_hi_3597_M87+ALMArot.uvfits

casa_data/April05/M87_calibrated.uvf.spw0to31+EVPA_rotation+dcal+ampscale+netcal+10s_avg+RLgain_amp.uvfits
casa_data/April05/M87_calibrated.uvf.spw32to63+EVPA_rotation+dcal+ampscale+netcal+10s_avg+RLgain_amp.uvfits

April 6 data:
hops_data/April06/hops_lo_3598_M87+ALMArot.uvfits
hops_data/April06/hops_hi_3598_M87+ALMArot.uvfits

casa_data/April06/M87_calibrated.uvf.spw0to31+EVPA_rotation+dcal+ampscale+netcal+10s_avg+RLgain_amp.uvfits
casa_data/April06/M87_calibrated.uvf.spw32to63+EVPA_rotation+dcal+ampscale+netcal+10s_avg+RLgain_amp.uvfits

April 10 data:
hops_data/April10/hops_lo_3600_M87+ALMArot.uvfits
hops_data/April10/hops_hi_3600_M87+ALMArot.uvfits

casa_data/April10/M87_calibrated.uvf.spw0to31+EVPA_rotation+dcal+ampscale+netcal+10s_avg+RLgain_amp.uvfits
casa_data/April10/M87_calibrated.uvf.spw32to63+EVPA_rotation+dcal+ampscale+netcal+10s_avg+RLgain_amp.uvfits

April 11 data:
hops_data/April11/hops_lo_3601_M87+ALMArot.uvfits
hops_data/April11/hops_hi_3601_M87+ALMArot.uvfits

casa_data/April11/M87_calibrated.uvf.spw0to31+EVPA_rotation+dcal+ampscale+netcal+10s_avg+RLgain_amp.uvfits
casa_data/April11/M87_calibrated.uvf.spw32to63+EVPA_rotation+dcal+ampscale+netcal+10s_avg+RLgain_amp.uvfits

===================================================================
Datasets with self-calibration and zero baseline D-term calibration 
===================================================================

April 5 data:
hops_data/April05/hops_lo_3597_M87+zbl-dtcal_selfcal.uvfits
hops_data/April05/hops_hi_3597_M87+zbl-dtcal_selfcal.uvfits

April 6 data:
hops_data/April06/hops_lo_3598_M87+zbl-dtcal_selfcal.uvfits
hops_data/April06/hops_hi_3598_M87+zbl-dtcal_selfcal.uvfits

April 10 data:
hops_data/April10/hops_lo_3600_M87+zbl-dtcal_selfcal.uvfits
hops_data/April10/hops_hi_3600_M87+zbl-dtcal_selfcal.uvfits

April 11 data:
hops_data/April11/hops_lo_3601_M87+zbl-dtcal_selfcal.uvfits
hops_data/April11/hops_hi_3601_M87+zbl-dtcal_selfcal.uvfits

