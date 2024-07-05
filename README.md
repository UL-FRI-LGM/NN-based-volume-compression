# Neural-network-based Volume Compression

This repository contains the code for lossy compression of volumetric (voxel) data with neural networks.
All computing was done via Google Colab on the free tier CPU runtime, using python and various libraries, mostly PyTorch and Numpy.
The folders contain mostly the same jupyter notebook files, but changed to fit each model the folder is named after.

The models were obtained from [https://drive.google.com/drive/folders/1vxAHxXPUj9Z-xBkygZKXBKXbI4oDwGn3](https://klacansky.com/open-scivis-datasets/) and can be viewed with VPT, found on [https://github.com/terier/vpt](https://github.com/terier/vpt), which also has a link to a hosted working demo.

The volumes used:
- tooth: tooth_103x94x161_1x1x1_uint8 (uncompressed: 1.48MB, as a zip: 879kB)
- bonsai: bonsai_256x256x256_1x1x1_uint8 (uncompressed: 16MB, as a zip: 3.14MB)
- body: body_512x512x226_1x1x1_uint8  (uncompressed: 56.5MB, as a zip: 8.25MB)
All volumes used are binary files containing uint8 values and have to be reshaped to the dimensions specified in the file name.
