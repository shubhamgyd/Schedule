# Bit-plane coding in image compression

1. Bit-plane coding breaks down an image into its `binary components.`

2. Each pixel value (usually 8-bit grayscale) is represented by `multiple binary planes`.

3. Most Significant Bit (MSB) plane holds the most critical image details, while Least Significant Bit (LSB) planes control finer details.

4. By discarding `less significant bit-planes`, we can achieve compression while sacrificing some image fidelity.

5. This allows for a `progressive reconstruction` of the image. Decoding only a few planes reveals a rough version, and adding more planes improves the quality.