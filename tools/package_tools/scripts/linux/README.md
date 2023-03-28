# build sdk

1. installed opencv (you can skip this step if you have installed it)
   in sdk folder:

   `./install_opencv.sh`

2. set environment variable and path
   in sdk folder:

   `source ./set_env.sh` \
   (you have to additionally install cuda and cudnn if you use sdk cuda version)

3. build sdk
   in sdk folder:

   `./build_sdk.sh` \
   (if you installed opencv by ./install_opencv.sh)

   or

   `./build_sdk.ps1 "path/to/folder/of/OpenCVConfig.cmake"` \
   (if you installed opencv yourself)

   the executable will be generated in: `bin/`