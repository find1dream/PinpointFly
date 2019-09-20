To use the code, you need:
1. download opencv 3.0 from https://github.com/opencv/opencv/releases/tag/3.0.0
2. download opencv_contrib from https://github.com/opencv/opencv_contrib/releases/tag/3.0.0
3. replace `opencv-3.0.0/platforms/ios/build_framework.py` with build_framework.py from https://gist.github.com/atinfinity/ccf4fc657c7def583b8e
4. in terminal, run `cd ~/<my_working_directory>
python opencv-3.0.0/platforms/ios/build_framework.py --contrib opencv_contrib-3.0.0 ios`

you can get `opencv2.framework`

Make a file named `Frameworks`, and put `opencv2.framewor` into `Frameworks`.

Then you can use the code
