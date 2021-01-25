**MTCNN Face detection algorithm's C++ implementation with NVIDIA TensorRT Inference acceleration SDK.**

mkdir build && cd build  
cmake -DCMAKE_BUILD_TYPE=Release ..  
make -j${nproc}  
./main