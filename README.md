# Usage
This repositary contains a linux build of the HEVC HM decoder. The standard HEVC decoder which does not support packet losses has been modified to support slice copy based error concealment. The usage of the executable is SLICE_COPY_DECODER -b input.bin where input.bin is the corrupted HM encoded bit stream.

# Publications
G. Kulupana, D. S. Talagala, H. K. Arachchi, and A. Fernando, “Error resilience aware motion estimation and mode selection for HEVC video transmission,” in IEEE International Conference on Consumer Electronics (ICCE), Las Vegas, pp. 85–86, Jan. 2016.
