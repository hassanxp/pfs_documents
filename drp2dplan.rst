###########
2D DRP Plan
###########

Introduction
============

Aim
---

This document describes the current working plan for DRP development, 
covering the period from October 2018 until the end of operations.

Notes
-----

Each 2D-DRP release is named according to an incremental version number of the form <major>.<minor> . 
For historical reasons, the initial version described in this plan is 4.0 .


2DDRP-4.0 (Sep 2018)
====================

This is the initial release of the pipeline. Used for SM1 r-channel testing at LAM.

- Basic functionality
- Low-level test harness.

2DDRP-5.0 (Apr 2019)
====================

Initial end-to-end demonstration of pipeline. Integration test incorporates the 2D simulator,
that provides test quartz, arcs and science data. 

- all 3 arms (R, B and NIR) processed 
- 3 arms merged
- initial flat-fielding in accordance to new framework
- detector map generated
- initial flux calibration (TBC)
- more complete test harness

2DDRP-6.0 (Sep 2019)
====================

Version for early PSF commissioning. Sky data from LAM used for PSF model color dependence

- Initial 2D PSF model with color dependence
- Initial telluric correction
- Initial sky subtraction (to 2% TBC level)

2DDRP-7.0 (Mar 2020)
====================

Updated version for commissioning, with improvements based on acquired data during the early commissioning phase.

- Updated 2D PSF model
- Improved telluric modelling
- Updated sky subtraction (to 1% TBC error level)
- Performance (speed) improved 

2DDRP-8.0 (Sep 2020)
====================

Intermediate release with bug fixes.


2DDRP-9.0 (Jan 2021)
====================

Further improvements, bug fixes

- Bug fixes
- Missing functions
- Refactoring
- Performance (speed) improvements
- sky subtraction to 0.5% error level




