# image test in batch size for Caffe framework.
C++ interface for image test in batch size for Caffe deep learning framework. It supports GPU/CPU computation. It contains several facinating features that eases your usage:
1. supports multiple feature extraction, you just have to present multiple layers' name in the <code>layer_name</code> argument.
2. flexible change between GPU and CPU computation. <code>backend_mode</code> controls this choice, while 1 means GPU, 0 means CPU.
3. GFLAGS/GLOG parameter/logging system.

# Acknowledgement
1. Yuhang would like to thank his colleague B. Liu for his first version implementation. Here, I simplified the 
