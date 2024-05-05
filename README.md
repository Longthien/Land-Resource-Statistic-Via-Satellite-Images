# Land-Resource-Statistic-Via-Satellite-Images

This repository provides functionality for calculating the area within an administrative boundary using satellite images. The code is specifically tailored for this application.

#Key functions:

1. geo_func.py: It includes various geometry functions to support the manipulation of geometric data. For example, it can split a large
2. polygon into smaller squares and read geometry data from the dataset.
3. render_mask.py: This function maps the boundary and the image to determine whether pixels fall within the boundary.
4. render_report.py: It calculates the area based on the mask and annotation images.
5. Satellite_Image_Collector.py: This function installs satellite images based on the provided coordinates of the top-left and bottom-right points.


The public dataset available is from District 12, Da Lat City. You can access the dataset through the following link: [District 12, Da Lat city dataset](https://drive.google.com/drive/folders/1HUd84yzf88tOZmYqmIrJKK7QrD2dwGMx)
