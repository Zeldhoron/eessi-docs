---
hide:
- toc
json_ld:
  '@context': https://schema.org
  '@type': SoftwareApplication
  applicationCategory: DeveloperApplication
  description: Numba is an Open Source NumPy-aware optimizing compiler forPython sponsored
    by Continuum Analytics, Inc. It uses the remarkable LLVMcompiler infrastructure
    to compile Python syntax to machine code.
  license: Not confirmed
  name: numba
  offers:
    '@type': Offer
    price: 0
  operatingSystem: LINUX
  review:
    '@type': Review
    author:
      '@type': Organization
      name: EESSI
    reviewBody: Application has been successfully made available on all architectures
      supported by EESSI
    reviewRating:
      '@type': Rating
      ratingValue: 5
  softwareRequirements: See https://www.eessi.io/docs/ for how to make EESSI available
    on your system
  softwareVersion: '[''numba/0.58.1-foss-2023a'']'
  url: https://numba.pydata.org/
---

numba
=====


Numba is an Open Source NumPy-aware optimizing compiler forPython sponsored by Continuum Analytics, Inc. It uses the remarkable LLVMcompiler infrastructure to compile Python syntax to machine code.

https://numba.pydata.org/
# Available modules


The overview below shows which numba installations are available per target architecture in EESSI, ordered based on software version (new to old).

To start using numba, load one of these modules using a `module load` command like:

```shell
module load numba/0.58.1-foss-2023a
```

*(This data was automatically generated on {{ generated_time }})*

| |aarch64/generic|aarch64/neoverse_n1|aarch64/neoverse_v1|aarch64/nvidia/grace|x86_64/generic|x86_64/amd/zen2|x86_64/amd/zen3|x86_64/amd/zen4|x86_64/intel/cascadelake|x86_64/intel/haswell|x86_64/intel/icelake|x86_64/intel/sapphirerapids|x86_64/intel/skylake_avx512|
| :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
|numba/0.58.1-foss-2023a|x|x|x|x|x|x|x|x|x|x|x|x|x|


### numba/0.58.1-foss-2023a

This is a list of extensions included in the module:

llvmlite-0.41.1, numba-0.58.1