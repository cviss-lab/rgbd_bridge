# Bridge RGB-D
 A LiDAR RGB-D Dataset of 5 Bridges near downtown Kitchener, Ontario. 
 Created with local LiDAR accumulation for evaluating metric depth monocular depth estimation.


## Data Collection Platform

![Alt text](./promo/fig_2.png "LiDAR Scanner")

We modeled our LiDAR scanner on that by R3LIVE authors. It uses the LiVOX Avia LiDAR, Intel Realsense Camera and Intel NUC for data collection.

The same LiDAR scanner can be seen on our YouTube Channel: CViSS LAB

Instructions to replicate, including our 3D STL files for mounting are available upon request.

## Data Format

This repository contains rgb images corresponding accumulated depth images (in KITTI format), intrinsics, poses and timestamps.

Each rgb image (in the rgb folder) has a corresponding depth image (in depth folder) of the same name.
Please note we remove the start of some sequences since at startup the Intel Realsense camera images are over saturated and were deemed unusable, additionally
the start of the dataset can contain many similar scenes as the inspector activates the scanner from phone app and stands still for several seconds to verify data collection is started.

## Data Links

| Bridge                | Google Drive Link                                                                     |
|-----------------------|---------------------------------------------------------------------------------------|
| Belmont St. (B1)      | https://drive.google.com/file/d/1WOfyBGpvxnMcwsETgrnHjVhOf3k8nCat/view?usp=drive_link |
| Iron Horse Trail (B2) | https://drive.google.com/file/d/14WyLNDA-kIxmn8oILWmV7smDfflLNuug/view?usp=drive_link |
| Park St.  (B3)        | https://drive.google.com/file/d/1WiDK-cePBXpT-W0a5X8G9nW1C4cA8uXK/view?usp=drive_link |
| King St. (B4)         | https://drive.google.com/file/d/1gxfHjmOpAAaxew2ygO4p8bl2IlWEayBO/view?usp=drive_link |
| Weber St. (B5)        | https://drive.google.com/file/d/1Qf1IhvJAm7iMNya51voMdPkvkRBrm8lN/view?usp=drive_link |

Below are RGB and colourized depth images. 

![Alt text](./promo/fig_5.png "Dataset Preview (Depth Maps Colorized)")

## Citation

Midwinter, M., Al-Sabbag, Z.A., Bajaj, R., & Yeum, C.M. (2024). Learning Monocular Depth Estimation for Defect Measurement from Civil RGB-D Dataset. Structural Health Monitoring. (Preprint)