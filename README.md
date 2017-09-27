# GPGPU cheatsheet

CUDA and Metal comparison

In the future: OpenCL

| CUDA C          | Metal Shading Language            |
| --------------- | --------------------------------- |
| grid            | grid                              |
| block           | threadgroup                       |
| thread          | thread                            |
| warp            | SIMD group, warp or wavefront     |
| \_\_global\_\_  | kernel                            |
| threadIdx       | thread\_position\_in\_threadgroup |
| blockDim        | threads\_per\_threadgroup         |
| blockIdx        | threadgroup\_position\_in\_grid   |
| gridDim         | ?                                 |
| ?               | thread\_position\_in\_grid        |
| ?               | simdgroup\_index\_in\_threadgroup |
| ?               | thread\_index\_in\_simdgroup      |
| \_\_syncthreads | threadgroup\_barrier              |
| shared memory   | threadgroup memory                |
| constant memory | constant memory                   |
| global memory   | device memory                     |
| ?               | thread memory                     |
