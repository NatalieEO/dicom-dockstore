# dicom-dockstore

Experiment with wrapping a version of the DICOM viewer in a .dockstore.yml

Based on a modified version of [dicom-cloudtop](https://github.com/heliumplusdatastage/app-support-prototype/tree/develop/dockstore-yaml-proposals/dicom-cloudtop). This runs using docker-compose, not Tycho.

## Data

The viewer displays DCM and DICOM files. The application expects those files to be in the directory specified by
the DATA_DIR environment variable..
