# vtk-volume-render-bounds-bug
Volume rendering code to debug first and last slice rendering


## Full head

### Nearest neighbor interpolation
![head-nearest](img/head-nearest.png)

### Linear interpolation
![head-linear](img/head-linear.png)


## Test dicom
![test-dicom](img/test-dicom.png)


### Test DICOM Nearest neighbor interpolation 
shows only 9 bars

![test-dicom-nearest](img/test-dicom-nearest.png)

### Test DICOM Linear interpolation
shows 10 bars but the thickness of the bar in the first and last is not consistent with the rest

![test-dicom-linear](img/test-dicom-linear.png)

