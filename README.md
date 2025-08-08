# irt-irtpro
This code suite automates IRT calibration using IRTPro 6.0 software. This particular code assumes calibration using both 2-parameter (2PL) and Generalized Partial Credit (GPC) models, but modifications can be made to accommodate other IRT models, such as 3PL.

The code is internally self-documented.

The code can be executed in a variety of ways:
1) Via a control panel (00_CONTROL_PANEL.sas) module that provides user defined inputs and will automatically call each module in sequence. No other module needs to be executed if this module is run.
2) As a series of standalone modules, executed in sequence (01-04).
3) As an Enterprise Guide project that provides further automation and visualization options.


