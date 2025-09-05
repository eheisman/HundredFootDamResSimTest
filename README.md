# HundredFootDamResSimTest
Sample ResSim Watershed for Tests

## Purpose
This HEC-ResSim watershed is designed to provide a very basic compute test to validate that HEC-ResSim builds can be computed in  various environments.

## History
This was initially developed for confirming the ability to compute HEC-ResSim models in the HEC-WAT environment on Windows.  This version has had the HEC-WAT components removed.  It is not based on any real watershed and was developed only for the purpose of confirming compute functionality in the software.

## How to use this test.
This watershed has a single simulation called `TestSimWY2007` that computes the WY2007 (01Oct2006-30Sept2007) time window on a six hour basis.  It uses a ResSim alternative called `RSAlt1_S` with network `N1`.  Running this ismulation and/or creating a similar simulation should be done to validate the ability to compute.  The simulation as provided includes model results which can be compared to confirm that the compute produces identical results.

This test in itself is not intended to be used for any other purpose, and is expected to be modified for each indivudal application.

## Contributing
Contact author if you would like to make a change.  This model should not be modified to support additional features.  If that is required, please create a fork and maintain separately.
