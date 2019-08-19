set(SOURCE_FILES
    "glslUtility.hpp"
    "glslUtility.cpp"
    "kernel.h"
    "kernel.cu"
    )

# IMPORTANT: Edit -arch to your GPU's sm version.
# e.g: compute compatibility 3.5 --> sm_35
cuda_add_library(src
    ${SOURCE_FILES}
    OPTIONS -arch=sm_20
    )
