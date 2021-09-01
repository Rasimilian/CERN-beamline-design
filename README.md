# CERN-beamline-design

A program to design a beamline and to simulate beam motion.

SimulationMadx is a Jupyter file. It uses 3 files with structures.
Files with structures:
	Beamline_3qdoublets_6.3m_3m.txt - with 6 quadrupoles
	Beamline_2qdoublets_5m_2.6m.txt - with 4 quadrupoles, upper branch of the beamline
	Beamline_3qdoublets_5m_1.36m.txt - with 4 quadrupoles, lower branch of the beamline

During the execution, 3 log files are created:
	internal_mag_pot.txt
	trackingone.txt - tracking information
	twiss - twiss parameters

For MAD-X commands see User's Reference Manual.
