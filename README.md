# frame_copy_decoder_HEVC
This repositary contains a linux build of the HEVC HM decoder. The standard HEVC decoder which does not support packet losses has been modified to support slice copy based error concealment. The usage of the executable is SLICE_COPY_DECODER -b input.bin where input.bin is the corrupted HM encoded bit stream.
