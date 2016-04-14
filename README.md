# ORB-SLAM2 (for OSX)
**Authors:** [Raul Mur-Artal](http://webdiis.unizar.es/~raulmur/), [Juan D. Tardos](http://webdiis.unizar.es/~jdtardos/), [J. M. M. Montiel](http://webdiis.unizar.es/~josemari/) and [Dorian Galvez-Lopez](http://doriangalvez.com/) ([DBoW2](https://github.com/dorian3d/DBoW2))

* This is ORG-SLAM2 for Xcode & Max OSX. No drawing modules like Pangolin is needed.
Most of the port work comes from [his github](https://github.com/meiroo/ORBSLAM2-OSX) and [blog] (http://zhuanlan.zhihu.com/computercoil/20589372).

* Forked from https://github.com/raulmur/ORB_SLAM2 and https://github.com/meiroo/ORBSLAM2-OSX

# Usage
1. Download from github
2. Open Xcode/ORB_SLAM2.xcworkspace with Xcode
3. Enjoy it!

# Changes
* Pangolin removed, MapDrawer FrameDrawer removed.
* Cmake system removed, open Xcode/ORB_SLAM2.xcworkspace and build system with dependencies.
* Binnary dictionary to speed up loading (from https://github.com/poine/ORB_SLAM2)
* Camera capture instead of datasets
* OpenCV's camera calibration tools added 
