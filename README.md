# RRFS Real-Time Monitoring & Notes

This repository provides personal technical notes and links to RRFS real-time prototype experiments, monitoring tools, data assimilation diagnostics, and related resources.

**Disclaimer:** These are personal notes on GSL/AVID RRFSv2 prototype real-time experiments and related resources. This is not an official NOAA/GSL project description or documentation.

## RRFSv2 Real-Time Prototype Experiments

- **RRFSv2X**: Baseline real-time prototype, including deterministic and ensemble runs.
- **RRFSv2b**: Deterministic and ensemble runs, focusing on atmospheric blending.
- **RRFSv2c**: Deterministic experiment focusing on the Noah-MP land surface model; currently uses background-error covariance from the RRFSv2b ensemble.
- **RRFSv2s**: Prototype experiment focusing on smoke and dust.


## Real-Time Monitoring & Diagnostics (by GSL and Collaborators)

- [LINK](https://rapidrefresh.noaa.gov/hrrr/MPAS/Welcome.cgi?dsKey=mpas_rrfsv2x_ursa) **RRFSv2X Graphics and Change Logs**: Experimental forecast graphics and links to change logs.
- [LINK](https://rrfsx.github.io/workflow_status/) **RRFSv2X and RRFSv2b Workflow Status**: Real-time workflow status for RRFS prototypes.
- [LINK](https://rapidrefresh.noaa.gov/pyDAmonitor/rrfsv2x/mostrecent/) **RRFSv2X pyDAmonitor**: Real-time data assimilation diagnostics, including observation counts, minimization, and JEDI configurations and logs.


## Real-Time Monitoring & Diagnostics (Developed/Maintained by Me)

- **RRFS Ensemble Monitor**: Near-real-time monitoring of ensemble statistics for near-surface and soil variables.
  - [LINK](https://liaofanlin-noaa.github.io/rrfs_monitor/) **Current Monitor**: Ensemble spread and extreme values.
  - [LINK](https://liaofanlin-noaa.github.io/rrfs_monitor/time_series.html) **Time Series**: Historical time series of ensemble statistics and extremes.
- **RRFS Workflow Status and Change Logs**: Real-time workflow monitoring and experiment documentation.
  - [LINK](https://liaofanlin-noaa.github.io/workflow_status/) **Workflow Status**: Real-time workflow monitoring for RRFSv2b-enkf, RRFSv2c-det, and RRFSv2s-det.
  - [LINK](https://liaofanlin-noaa.github.io/workflow_status/rrfsv2c_change_log.txt) **RRFSv2c Change Log**: Record of experiment configurations and updates.

Additional experiment notes and change logs may be linked here as they become publicly available.

## Related Resources

- [LINK](https://github.com/LiaofanLin-NOAA/rrfs_monitor) **RRFS Ensemble Monitor Repository**: Source code for the real-time ensemble monitoring webpage.
- [LINK](https://github.com/LiaofanLin-NOAA/workflow_status) **Workflow Status Repository**: Source code for workflow status monitoring.

