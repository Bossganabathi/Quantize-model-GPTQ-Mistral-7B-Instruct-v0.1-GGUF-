# GPTQ: Generalized Post-Training Quantization
1. The method is that it will try to compress all weights to a 4-bit quantization by minimizing the mean squared error to that weight.
2. During inference, it will dynamically dequantize its weights to float16 for improved performance whilst keeping memory low
