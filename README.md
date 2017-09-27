# GPGPU cheatsheet

CUDA and Metal comparison

In the future: OpenCL

| CUDA C          | Metal Shading Language         |
| --------------- | ------------------------------ |
| grid            | grid                           |
| block           | threadgroup                    |
| thread          | thread                         |
| warp            | SIMD group, warp or wavefront  |
| __global__      | kernel                         |
| threadIdx       | thread_position_in_threadgroup |
| blockDim        | threads_per_threadgroup        |
| blockIdx        | threadgroup_position_in_grid   |
| gridDim         | ?                              |
| ?               | thread_position_in_grid        |
| ?               | simdgroup_index_in_threadgroup |
| ?               | thread_index_in_simdgroup      |
| __syncthreads   | threadgroup_barrier            |
| shared memory   | threadgroup memory             |
| constant memory | constant memory                |
| global memory   | device memory                  |
| ?               | thread memory                  |
