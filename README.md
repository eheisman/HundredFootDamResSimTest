# HundredFootDamResSimTest
Sample ResSim Watershed for Tests

## Purpose
This HEC-ResSim watershed is designed to provide a very basic compute test to validate that HEC-ResSim builds can be computed in  various environments.

## History
This was initially developed for confirming the ability to compute HEC-ResSim models in the HEC-WAT environment on Windows.  This version has had the HEC-WAT components removed.  It is not based on any real watershed and was developed only for the purpose of confirming compute functionality in the software.

## Key features
This watershed has a single simulation called `TestSimWY2007` that computes the WY2007 (01Oct2006-30Sept2007) time window on a six hour basis.  It uses a ResSim alternative called `RSAlt1_S` with network `N1`.  Running this ismulation and/or creating a similar simulation should be done to validate the ability to compute.  The simulation as provided includes model results which can be compared to confirm that the compute produces identical results.
