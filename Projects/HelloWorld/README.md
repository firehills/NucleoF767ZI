* Building

mkdir build
cd build
cmake -G "Unix Makefiles" -DCMAKE_TOOLCHAIN_FILE="cmake/cortex_m7.cmake" ..
make -j8
