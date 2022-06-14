# ABECIS-Results

These are the results for our paper "Developing a Free and Open-source Automated Building Exterior Crack Inspection Software for Construction and Facility Managers" by P. Ko, S. A. Prieto, B. García de Soto from [S.M.A.R.T. Construction Research Group](https://nyuad.nyu.edu/en/research/faculty-labs-and-projects/smart-construction-research-group.html) at New York University Abu Dhabi

The following contains the Intersection Over Union evaluation for images taken in 
- Indoor Lab Controlled Environment, using DJI Matrice 300 RTK Drone (14 images)
- Outdoor Construction Site Environment, using Android Smartphone (14 images)
- Outdoor University Campus, using DJI Matrice 300 RTK Drone (14 images)

Moreover, length estimation Indoor Lab Controlled Environment is also included below.

IOU of 1 means perfect prediction and 0 means all predictions are wrong.

## IOU

### Indoor - Lab

|Image Name   |Image|IOU (Largest to Smallest)|
|-------------|-----|-----|
|lab_00017.jpg|<img src="lab/lab_00017.jpg" alt="img" width="200"/>|0.999|
|lab_00001.jpg|<img src="lab/lab_00001.jpg" alt="img" width="200"/>|0.962|
|lab_00003.jpg|<img src="lab/lab_00003.jpg" alt="img" width="200"/>|0.929|
|lab_00004.jpg|<img src="lab/lab_00004.jpg" alt="img" width="200"/>|0.853|
|lab_00002.jpg|<img src="lab/lab_00002.jpg" alt="img" width="200"/>|0.804|
|lab_00008.jpg|<img src="lab/lab_00008.jpg" alt="img" width="200"/>|0.773|
|lab_00012.jpg|<img src="lab/lab_00012.jpg" alt="img" width="200"/>|0.694|
|lab_00018.jpg|<img src="lab/lab_00018.jpg" alt="img" width="200"/>|0.678|
|lab_00006.jpg|<img src="lab/lab_00006.jpg" alt="img" width="200"/>|0.665|
|lab_00022.jpg|<img src="lab/lab_00022.jpg" alt="img" width="200"/>|0.642|
|lab_00007.jpg|<img src="lab/lab_00007.jpg" alt="img" width="200"/>|0.642|
|lab_00011.jpg|<img src="lab/lab_00011.jpg" alt="img" width="200"/>|0.554|
|lab_00019.jpg|<img src="lab/lab_00019.jpg" alt="img" width="200"/>|0.509|
|lab_00021.jpg|<img src="lab/lab_00021.jpg" alt="img" width="200"/>|0.505|


### Outdoor - Construction Site

|Image Name   |Image|IOU (Largest to Smallest)|
|-------------|-----|-----|
|outdoor_site_00197.jpg|<img src="outdoor_site/outdoor_site_00197.jpg" alt="img" width="200"/>|0.968|
|outdoor_site_00200.jpg|<img src="outdoor_site/outdoor_site_00200.jpg" alt="img" width="200"/>|0.967|
|outdoor_site_00187.jpg|<img src="outdoor_site/outdoor_site_00187.jpg" alt="img" width="200"/>|0.946|
|outdoor_site_00201.jpg|<img src="outdoor_site/outdoor_site_00201.jpg" alt="img" width="200"/>|0.903|
|outdoor_site_00168.jpg|<img src="outdoor_site/outdoor_site_00168.jpg" alt="img" width="200"/>|0.848|
|outdoor_site_00169.jpg|<img src="outdoor_site/outdoor_site_00169.jpg" alt="img" width="200"/>|0.839|
|outdoor_site_00003.jpeg|<img src="outdoor_site/outdoor_site_00003.jpeg" alt="img" width="200"/>|0.252|
|outdoor_site_00001.jpeg|<img src="outdoor_site/outdoor_site_00001.jpeg" alt="img" width="200"/>|0.120|
|outdoor_site_00002.jpeg|<img src="outdoor_site/outdoor_site_00002.jpeg" alt="img" width="200"/>|0.089|
|outdoor_site_00178.jpg|<img src="outdoor_site/outdoor_site_00178.jpg" alt="img" width="200"/>|0.000|
|outdoor_site_00136.jpg|<img src="outdoor_site/outdoor_site_00136.jpg" alt="img" width="200"/>|0.000|
|outdoor_site_00174.jpg|<img src="outdoor_site/outdoor_site_00174.jpg" alt="img" width="200"/>|0.000|
|outdoor_site_00195.jpg|<img src="outdoor_site/outdoor_site_00195.jpg" alt="img" width="200"/>|0.000|
|outdoor_site_00177.jpg|<img src="outdoor_site/outdoor_site_00177.jpg" alt="img" width="200"/>|0.000|


### Outdoor - Drone

|Image Name   |Image|IOU (Largest to Smallest)|
|-------------|-----|-----|
|outdoor_drone_00006.jpg|<img src="outdoor_drone/outdoor_drone_00006.jpg" alt="img" width="200"/>|0.972|
|outdoor_drone_00008.jpg|<img src="outdoor_drone/outdoor_drone_00008.jpg" alt="img" width="200"/>|0.970|
|outdoor_drone_00016.jpg|<img src="outdoor_drone/outdoor_drone_00016.jpg" alt="img" width="200"/>|0.970|
|outdoor_drone_00010.jpg|<img src="outdoor_drone/outdoor_drone_00010.jpg" alt="img" width="200"/>|0.968|
|outdoor_drone_00004.jpg|<img src="outdoor_drone/outdoor_drone_00004.jpg" alt="img" width="200"/>|0.963|
|outdoor_drone_00018.jpg|<img src="outdoor_drone/outdoor_drone_00018.jpg" alt="img" width="200"/>|0.962|
|outdoor_drone_00109.jpg|<img src="outdoor_drone/outdoor_drone_00109.jpg" alt="img" width="200"/>|0.962|
|outdoor_drone_00115.jpg|<img src="outdoor_drone/outdoor_drone_00115.jpg" alt="img" width="200"/>|0.954|
|outdoor_drone_00065.jpg|<img src="outdoor_drone/outdoor_drone_00065.jpg" alt="img" width="200"/>|0.796|
|outdoor_drone_00067.jpg|<img src="outdoor_drone/outdoor_drone_00067.jpg" alt="img" width="200"/>|0.720|
|outdoor_drone_00058.jpg|<img src="outdoor_drone/outdoor_drone_00058.jpg" alt="img" width="200"/>|0.550|
|outdoor_drone_00062.jpg|<img src="outdoor_drone/outdoor_drone_00062.jpg" alt="img" width="200"/>|0.502|
|outdoor_drone_00072.jpg|<img src="outdoor_drone/outdoor_drone_00072.jpg" alt="img" width="200"/>|0.430|
|outdoor_drone_00070.jpg|<img src="outdoor_drone/outdoor_drone_00070.jpg" alt="img" width="200"/>|0.370|


## Length Estimation

<img src="wall_measured.png" alt="img" width="400"/>

As seen above, the measured total length of cracks on the mockup wall is

49.5 + 12 + 41 + 33 + 9.5 + 23.5 + 20 = **188.5 cm**

Below are the results to estimate the total length on the mockup wall using Pixels Per Metric Ratio, sorted by aascending Percentage Error.

|Image Name         |Image|Estimate Total Length (pixels)|Pixels Per Metric Ratio|Estimate Total Length (cm)| % Error|
|-------------|-----|------------|-----|-------|---------|
|lab_00008.jpg|<img src="lab/lab_00008.jpg" alt="img" width="200"/>|611         |30.55|186    |1        |
|lab_00022.jpg|<img src="lab/lab_00022.jpg" alt="img" width="200"/>|168         |8.4  |183    |2        |
|lab_00007.jpg|<img src="lab/lab_00007.jpg" alt="img" width="200"/>|169         |8.45 |194    |2        |
|lab_00002.jpg|<img src="lab/lab_00002.jpg" alt="img" width="200"/>|727         |36.35|202    |7        |
|lab_00017.jpg|<img src="lab/lab_00017.jpg" alt="img" width="200"/>|669         |33.45|173    |8        |
|lab_00001.jpg|<img src="lab/lab_00001.jpg" alt="img" width="200"/>|595         |29.75|207    |9        |
|lab_00012.jpg|<img src="lab/lab_00012.jpg" alt="img" width="200"/>|609         |30.45|209    |10       |
|lab_00003.jpg|<img src="lab/lab_00003.jpg" alt="img" width="200"/>|185         |9.25 |164    |12       |
|lab_00018.jpg|<img src="lab/lab_00018.jpg" alt="img" width="200"/>|604         |30.2 |219    |16       |
|lab_00019.jpg|<img src="lab/lab_00019.jpg" alt="img" width="200"/>|173         |8.65 |232    |23       |
|lab_00004.jpg|<img src="lab/lab_00004.jpg" alt="img" width="200"/>|659         |32.95|253    |34       |
|lab_00021.jpg|<img src="lab/lab_00021.jpg" alt="img" width="200"/>|136         |6.8  |286    |51       |
|lab_00011.jpg|<img src="lab/lab_00011.jpg" alt="img" width="200"/>|150         |7.5  |290    |53       |
|lab_00006.jpg|<img src="lab/lab_00006.jpg" alt="img" width="200"/>|516         |25.8 |364    |93       |





