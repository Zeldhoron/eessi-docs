---
hide:
- toc
json_ld:
  '@context': https://schema.org
  '@type': SoftwareApplication
  applicationCategory: DeveloperApplication
  description: pybind11 is a lightweight header-only library that exposes C++ types
    in Python and vice versa, mainly to create Python bindings of existing C++ code.
  license: Not confirmed
  name: pybind11
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
  softwareVersion: '[''pybind11/2.10.3-GCCcore-12.2.0'', ''pybind11/2.11.1-GCCcore-12.3.0'',
    ''pybind11/2.11.1-GCCcore-13.2.0'']'
  url: https://pybind11.readthedocs.io
---

pybind11
========


pybind11 is a lightweight header-only library that exposes C++ types in Python and vice versa, mainly to create Python bindings of existing C++ code.

https://pybind11.readthedocs.io
# Available modules


The overview below shows which pybind11 installations are available per target architecture in EESSI, ordered based on software version (new to old).

To start using pybind11, load one of these modules using a `module load` command like:

```shell
module load pybind11/2.11.1-GCCcore-13.2.0
```

*(This data was automatically generated on {{ generated_time }})*

| |aarch64/generic|aarch64/neoverse_n1|aarch64/neoverse_v1|aarch64/nvidia/grace|x86_64/generic|x86_64/amd/zen2|x86_64/amd/zen3|x86_64/amd/zen4|x86_64/intel/cascadelake|x86_64/intel/haswell|x86_64/intel/icelake|x86_64/intel/sapphirerapids|x86_64/intel/skylake_avx512|
| :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
|pybind11/2.11.1-GCCcore-13.2.0|x|x|x|x|x|x|x|x|x|x|x|x|x|
|pybind11/2.11.1-GCCcore-12.3.0|x|x|x|x|x|x|x|x|x|x|x|x|x|
|pybind11/2.10.3-GCCcore-12.2.0|x|x|x|x|x|x|x|x|x|x|x|x|x|
