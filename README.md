# dense_point_cloud_from_360_images
This repository is for creating a dense point cloud from 360 degree equirectangular input images


This repo is fully based on the open source python codes provided by OpenSfM and Colamp

## How to use

### Step 1

Create a virtual environment

Install OpenSfM https://opensfm.org/docs/building.html 

Colmap https://colmap.github.io/ and 

Open3D http://www.open3d.org/docs/release/getting_started.html

### Step 2

Go to ./OpenSfM/opensfm/actions

Replace the file "export_colmap.py" with the "export_colmap.py" file downloaded from this repo

### Step 3

Create a Project directory

Place all 360 degree equirectangular images inside a directory named "images"

Copy the "config.yaml" file in the project directory

Open "360_image_to_dense_point_cloud.ipynb"

Change the "PROJECT_PATH"

Click "cell/Run All"

