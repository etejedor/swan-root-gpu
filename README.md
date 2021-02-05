# Interactive use of GPU-accelerated libraries with SWAN and ROOT

SWAN users can now attach GPU resources to their sessions. They do so by selecting a GPU-enabled LCG release, which contains a set of libraries that have been compiled with GPU support (e.g. tensorflow) together with the Nvidia CUDA libraries and compiler suite.

This opens the door to interactively loading GPU-powered libraries from a C++ or Python notebook with ROOT and invoking them right away, thus exploiting the GPU resources!

Click on the link below to open the demonstration notebooks (C++ and Python) in SWAN. In the SWAN web form, before starting your session, select the `99 Cuda 10.1 Python3` software stack.

. |open-swan| image::  http://swanserver.web.cern.ch/swanserver/images/badge_swan_white_150.png
    :target: https://swan-k8s.cern.ch/hub/spawn?projurl=https://github.com/etejedor/swan-root-gpu.git
    :alt: Open in SWAN
