![image](https://github.com/cabelo/opensuse-for-intel-arc/assets/675645/a5d558bc-ed5d-4741-aa24-d6ad2d9bafe1)

# opensuse-for-intel-arc
Individual initiative in Brazil of the world's first Linux image with native kernel 6.2-rc5 or higher with Intel ARC stable open source driver. All GPU detection procedure takes place automatically during installation.

# Intel Technologies
oneAPI, Intel Arc, Intel Integrated Graphics, Intel NUC, Intel Python, MKL, Movidius NCS, Intel CPU, OpenVINO, 9th Gen Intel® Core™ Processors, 11th Gen Intel® Core™ Processors, 12th Gen Intel® Core™ Processors, Intel® Iris® Xe MAX, 10th Gen Intel® Core™ Processors 

## Overview / Usage

**Attention! **You acknowledge that using the Linux Image Beta is at your own risk.

I was very impressed with the performance and with the low consumption and heating during the tests of the ARC 750 GPU with openvino. As i am an openSUSE Linux Ambassador and responsible for the engineering work to build the openSUSE Linux for Innovators images on AWS. So I decided to build a Linux with Kernel 6.2, firmwares and stable Intel ARC card drivers.
## Methodology / Approach

Below are the completed and pending tasks for the Linux for ARC image based on the openSUSE Leap 15.4 distribution.

v300.0 This is a patch release containing the following changes:

    Added kernel 6.2.7

v247.3 This is a patch release containing the following changes:

    Added kernel 6.2-rc8

v246.3 This is a patch release containing the following changes:

    Added kernel 6.2-rc7
    Added Firmwares 20230125 version

v245.3 This is a patch release containing the following changes:

    Added kernel 6.2-rc6

v244.3 This is a patch release containing the following changes:

    Added kernel 6.2-rc5
    Added Firmwares 20230110 version

TODO in Linux image:

    Build the latest oneAPI Level Zero
    Build the latest oneAPI DNN
    Build the lastest oneAPI VPL
    Build the latest oneAPI TBB
    Build the latest oneAPI DAL
    Build the latest oneAPI MKL
    Build the latest Ray Tracing
    Build the latest openCV optimized with avx512, sse4_2 and GNA
    Config pre-installed all oneAPI packages

Technologies Used

Main technologies:

    openSUSE
    openCV
    oneAPI
    openVINO
    and others

Repository: https://build.opensuse.org/project/show/home:cabelo:intel
