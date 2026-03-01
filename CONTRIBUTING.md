# Contributing to RAM Coffers

Thank you for contributing to this **NUMA-distributed weight banking** project for IBM POWER8!

## Quick Start

### 1. Fork and Clone
```bash
git clone https://github.com/YOUR_USERNAME/ram-coffers.git
cd ram-coffers
```

### 2. Build Requirements
- C compiler (gcc)
- make
- IBM POWER8 system (ppc64le) with NUMA topology

### 3. Build and Test
```bash
make
make test  # Run benchmarks
```

### 4. Submit a PR
1. Create branch: `git checkout -b feature/your-feature`
2. Make changes
3. Push: `git push origin feature/your-feature`
4. Open PR on GitHub

## Code Style
- C99 standard
- 4-space indent (no tabs)
- Clear variable names

## NUMA Considerations
This project targets **IBM POWER8** with NUMA topology. Please:
- Test on real hardware when possible
- Note your NUMA configuration in PRs
- Consider memory locality in optimizations

Thanks for contributing! 🚀
