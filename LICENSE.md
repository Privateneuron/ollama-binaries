# Ollama Binaries (IPEX-LLM Fork) - License Attribution

Official repository for optimized Ollama binaries with Intel GPU support.

---

## Core Projects

### IPEX-LLM (Intel Extension for PyTorch)
- **License**: Apache 2.0
- **Repository**: https://github.com/intel-analytics/ipex-llm
- **Copyright**: Intel Corporation
- **Purpose**: Intel optimizations for LLM inference on CPUs and GPUs

### Ollama
- **License**: MIT
- **Repository**: https://github.com/ollama/ollama
- **Copyright**: Ollama Contributors
- **Purpose**: LLM runtime and model management platform

---

## Hardware-Specific Optimizations

### Intel Arc Alchemist GPU (A770 & A750)
- **Binaries**: `ollama-inteligpu&a770.zip`
- **Optimization**: IPEX-LLM with Arc GPU acceleration
- **License**: Apache 2.0 (IPEX-LLM)
- **Driver Requirements**: Intel Arc GPU drivers
- **Performance**: 2-4x speedup over CPU

### Intel Integrated GPU (iGPU)
- **Binaries**: `ollama-otherintel.zip`
- **Supported**: 12th Gen Intel Core (Alder Lake) and newer
- **Optimization**: IPEX-LLM with iGPU support
- **License**: Apache 2.0 (IPEX-LLM)
- **Performance**: 1.5-2x speedup over CPU

---

## Build Dependencies

### Python Libraries
- **PyTorch**: BSD License - https://github.com/pytorch/pytorch
- **Intel Extension for PyTorch (IPEX)**: Apache 2.0 - https://github.com/intel-analytics/ipex-llm
- **NumPy**: BSD License - https://github.com/numpy/numpy
- **Transformers**: Apache 2.0 - https://github.com/huggingface/transformers

### Intel SDK Components
- **Intel Arc GPU Compiler**: Intel Software License
- **Intel Graphics Compiler**: MIT License
- **Intel GPUOpen**: Apache 2.0 / MIT

### System Libraries
- **SYCL**: Apache 2.0 with LLVM Exception
- **OpenCL Headers**: Khronos License

---

## License Terms Summary

### Apache 2.0 (IPEX-LLM & Dependencies)
```
You are free to:
- Use for commercial and private purposes
- Modify the source code
- Distribute copies and modifications

You must:
- Include a copy of the license
- Provide prominent notices of changes
- Include a notice of the original source code
```

### MIT (Ollama & Dependencies)
```
You are free to:
- Use, modify, and distribute
- Use commercially

You must:
- Include the original license
- Include a copy of the license with distributed software
```

---

## Repository Information

**Repository**: https://github.com/Privateneuron/ollama-binaries
**Based On**: Intel Analytics & Ollama Projects
**Maintained By**: Privateneuron
**License**: Apache 2.0 (for build modifications & binaries)

---

## Contributing

If you contribute to this repository, you agree that your contributions will be licensed under the same license terms (Apache 2.0).

---

## Disclaimer

These binaries are provided as-is. Users are responsible for:
- Ensuring GPU drivers are up to date
- Complying with the licenses of underlying projects
- Testing compatibility with their hardware
- Following Intel and Ollama project licensing requirements

---

## Attribution

This project builds upon the excellent work of:

- **Intel Analytics Team** - IPEX-LLM optimization framework
- **Ollama Contributors** - Core LLM runtime
- **Open Source Community** - Supporting libraries and tools

---

## How to Check Compliance

Before using these binaries in production:

1. **Review IPEX-LLM License**: https://github.com/intel-analytics/ipex-llm/blob/main/LICENSE
2. **Review Ollama License**: https://github.com/ollama/ollama/blob/main/LICENSE
3. **Check GPU Driver Compatibility**: Intel Arc GPU drivers for your system
4. **Verify Legal Requirements**: Ensure compliance with your jurisdiction's software licensing laws

---

**Last Updated**: January 21, 2026
