<h1 align="center">  
    <img src="docs/dislib-logo-h-full.png" alt="The Distributed Computing Library" height="90px">    
</h1>

<h3 align="center">Distributed computing library implemented over PyCOMPSs programming model for HPC.</h3>

<p align="center">
  <a href="https://dislib.bsc.es/en/latest/?badge=latest">
    <img src="https://readthedocs.org/projects/dislib/badge/?version=stable"
         alt="Documentation Status"/>
  </a>  
  <a href="https://travis-ci.org/bsc-wdc/dislib">
    <img src="https://travis-ci.org/bsc-wdc/dislib.svg?branch=master"
         alt="Build Status">
  </a> 
  <a href="https://codecov.io/gh/bsc-wdc/dislib">
    <img src="https://codecov.io/gh/bsc-wdc/dislib/branch/master/graph/badge.svg"
         alt="Code Coverage"/>
  </a>
  <a href="https://badge.fury.io/py/dislib">
      <img src="https://badge.fury.io/py/dislib.svg" alt="PyPI version" height="18">
  </a>   
  <a href="https://badge.fury.io/py/dislib">
      <img src="https://img.shields.io/badge/python-3.5-blue.svg" alt="Python version" height="18">
  </a>       
</p>

<p align="center"><b>
    <a href="https://dislib.bsc.es">Website</a> •  
    <a href="https://dislib.bsc.es/en/stable/api-reference.html">Documentation</a> •
    <a href="https://github.com/bsc-wdc/dislib/releases">Releases</a>
</b></p>


## Introduction

The Distributed Computing Library (dislib) provides distributed algorithms ready to use as a library. So far, dislib is highly focused on machine learning algorithms, and it is greatly inspired by [Scikit-learn](https://scikit-learn.org/). However, other types of numerical algorithms might be added in the future. Dislib has been implemented on top of [PyCOMPSs programming model](http://compss.bsc.es), and it is being developed by the [Workflows and Distributed Computing group](https://github.com/bsc-wdc) of the [Barcelona Supercomputing Center](https://www.bsc.es/). The library also allows easy local development through docker. Once the code is finished, it can be run directly on any distributed platform without any further changes. This includes clusters, supercomputers, clouds, and containerized platforms. For more information on which infrastructures and architectures are supported refer to [Availability](#availability).



## Contents

- [Quickstart](#quickstart)
- [Availability](#availability)
- [Contributing](#contributing)
- [License](#license)


## Quickstart

Get started with dislib following our [quickstart guide](https://github.com/bsc-wdc/dislib/blob/master/QUICKSTART.md).

## Availability

Currently, the following supercomputers have already PyCOMPSs installed and ready to use. If you need help configuring your own cluster or supercomputer, drop us an email and we will be pleased to help.

- Marenostrum 4 - Barcelona Supercomputing Center (BSC)
- Minotauro - Barcelona Supercomputing Center (BSC)
- Nord 3 - Barcelona Supercomputing Center (BSC)
- Cobi - Barcelona Supercomputing Center (BSC)
- Juron - Jülich Supercomputing Centre (JSC)
- Jureca - Jülich Supercomputing Centre (JSC)
- Ultraviolet - The Genome Analysis Center (TGAC)
- Archer - University of Edinburgh’s Advanced Computing Facility (ACF)

Supported architectures:
- [Intel SSF architectures](https://www.intel.com/content/www/us/en/high-performance-computing/ssf-architecture-specification.html)
- [IBM's Power 9](https://www.ibm.com/it-infrastructure/power/power9-b)

## Contributing

Contributions are **welcome and very much appreciated**. We are also open to starting research collaborations or mentoring if you are interested in or need assistance implementing new algorithms.
Please refer [to our Contribution Guide](CONTRIBUTING.md) for more details.


## License

Apache License Version 2.0, see [LICENSE](LICENSE)
