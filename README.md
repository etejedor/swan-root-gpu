# Interactive use of GPU-accelerated libraries with SWAN and ROOT

SWAN users can now attach GPU resources to their sessions. They do so by selecting a GPU-enabled LCG release, which contains a set of libraries that have been compiled with GPU support (e.g. tensorflow) together with the Nvidia CUDA libraries and compiler suite.

This opens the door to interactively loading GPU-powered libraries from a C++ or Python notebook with ROOT and invoking them right away, thus exploiting the GPU resources!

Click on the link below to open the demonstration notebooks (C++ and Python) in SWAN. In the SWAN web form, before starting your session, select the `99 Cuda 10.1 Python3` software stack.

<a href="https://swan-k8s.cern.ch/user-redirect/download?projurl=https://github.com/etejedor/swan-root-gpu.git" target="_blank"><img src="http://swanserver.web.cern.ch/swanserver/images/badge_swan_white_150.png" alt="Open in SWAN"/></a>
