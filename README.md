# Asymmetric Inter-Channel Decorrelation

Pre-quantization channel redistribution in lossy image pipelines.

## Papers

**Method & Single-Image Results**
- `baetzel_2026_asymmetric_interchannel_decorrelation.pdf`
- Inter-channel correlation below r = 0.01, spatial autocorrelation above ρ = 0.991, 33.3% BPP reduction

**Kodak Benchmark — Complete 24-Image Analysis**
- `baetzel_2026_kodak_benchmark_interchannel_decorrelation.pdf`
- 52.8% mean decorrelation across the Kodak Lossless True Color Image Suite
- No encoder modification, no neural network, no machine learning

## Key Results

| Metric | Value |
|--------|-------|
| Mean decorrelation (24 images) | 52.8% (0.848 → 0.400) |
| Median decorrelation | 61.0% |
| Blue channel mean < 5.0 | 16/24 images |
| Resolution invariance (Δ) | 0.000047 |
| Best single image (kodim11) | 77.3% reduction |

## Contact

Jasmine Baetzel — info@jasminebaetzel.com

## Source

Benchmark images: [Kodak Lossless True Color Image Suite](http://r0k.us/graphics/kodak/)