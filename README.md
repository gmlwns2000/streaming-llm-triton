# Streaming-LLM with OpenAI Triton
OpenAI triton implementation of streaming LLM

You can now batch inference with streaming LLM and backward :D

## Implementation

This implementation uses the Sparse COO format to store attention scores of the streaming LLM scheme.

Also, RoPE is inlined inside of the GPU kernel, so you do not need to handle the rope yourself!

## This code is not fully optimized yet ... but correctly working!

- Utilize TensorCore
- L2 Cache Optimization
- and more
