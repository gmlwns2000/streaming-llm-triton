# Streaming-LLM with OpenAI Triton
OpenAI triton implementation of streaming LLM

You can now batch inference with streaming LLM and backward :D

## Implementation

This implementation using Sparse COO format, to store attention scores of streaming LLM scheme.

Also RoPE is inlined inside of GPU kernel, so you do not need to handle rope your self!.
