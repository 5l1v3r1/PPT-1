# Performance Prediction Toolkit (PPT)
Predict the performance of physics codes

# Authors
1. Gopinath (Nath) Chennupati (gchennupati@lanl.gov)
2. Nanadakishore Santhi (nsanthi@lanl.gov)
3. Stephen Eidenbenz (eidenben@lanl.gov)
4. Robert Joseph (Joe) Zerr (rzerr@lanl.gov)
5. Massimiliano (Max) Rosa (maxrosa@lanl.gov)
6. Richard James Zamora (rjzamora@lanl.gov)
7. Eun Jung (EJ) Park (ejpark@lanl.gov)
8. Balasubramanya T (Balu) Nadiga (balu@lanl.gov)
###### Non-LANL Authors
9. Jason Liu (luix@cis.fiu.edu)
10. Kishwar Ahmed
11. Mohammad Abu Obaida

# Installation

###### Dependencies
PPT depends on another LANL licensed open source software package named SIMIAN PDES located at https://github.com/pujyam/simian.

**Simian** relies on python package _greenlet_
_pip install greenlet_

PPT installation is simple, just checkout the code as follows
> git clone https://github.com/lanl/PPT.git

# Usage
Let's assume the PPT is cloned into your home directory (/home/user/PPT)
In the _code_ directory PPT is organized in three main layers:

1. **hardware** -- contains the models for various CPUs and GPUs, interconnects,
2. **middleware** -- contains the models for MPI, OpenMP, etc.
3. **apps** -- contains various examples. These examples are the stylized pseudo (mini) apps for various open sourced physics codes.

####### Runnning PPT in _Serial mode_

For example, we run SNAP simulator in serial with one of the PPT hardware models as follows:

> cd ~/PPT/code/apps/snapsim

> python snapsim-orig.py in >> out

where, _in_ and _out_ in the above command are input and output files of SNAPsim.

# Classification
PPT is Unclassified and contains no Unclassified Controlled Nuclear Information. It abides with the following computer code from Los Alamos National Laboratory
* Code Name: Performance Prediction Toolkit, C17098
* Export Control Review Information: DOC-U.S. Department of Commerce, EAR99
* B&R Code: YN0100000

# License
Copyright (c) 2017, Los Alamos National Security, LLC
All rights reserved.
Copyright 2017. Los Alamos National Security, LLC. This software was produced under U.S. Government contract DE-AC52-06NA25396 for Los Alamos National Laboratory (LANL), which is operated by Los Alamos National Security, LLC for the U.S. Department of Energy. The U.S. Government has rights to use, reproduce, and distribute this software.  NEITHER THE GOVERNMENT NOR LOS ALAMOS NATIONAL SECURITY, LLC MAKES ANY WARRANTY, EXPRESS OR IMPLIED, OR ASSUMES ANY LIABILITY FOR THE USE OF THIS SOFTWARE.  If software is modified to produce derivative works, such modified software should be clearly marked, so as not to confuse it with the version available from LANL.

 Additionally, redistribution and use in source and binary forms, with or without modification, are permitted provided that the following conditions are met:
 1. Redistributions of source code must retain the above copyright notice, this list of conditions and the following disclaimer.

 2. Redistributions in binary form must reproduce the above copyright notice, this list of conditions and the following disclaimer in the documentation and/or other materials provided with the distribution.

 3. Neither the name of Los Alamos National Security, LLC, Los Alamos National Laboratory, LANL, the U.S. Government, nor the names of its contributors may be used to endorse or promote products derived from this software without specific prior written permission.


  THIS SOFTWARE IS PROVIDED BY LOS ALAMOS NATIONAL SECURITY, LLC AND CONTRIBUTORS "AS IS" AND ANY EXPRESS OR IMPLIED WARRANTIES, INCLUDING, BUT NOT LIMITED TO, THE IMPLIED WARRANTIES OF MERCHANTABILITY AND FITNESS FOR A PARTICULAR PURPOSE ARE DISCLAIMED. IN NO EVENT SHALL LOS ALAMOS NATIONAL SECURITY, LLC OR CONTRIBUTORS BE LIABLE FOR ANY DIRECT, INDIRECT, INCIDENTAL, SPECIAL, EXEMPLARY, OR CONSEQUENTIAL DAMAGES (INCLUDING, BUT NOT LIMITED TO, PROCUREMENT OF SUBSTITUTE GOODS OR SERVICES; LOSS OF USE, DATA, OR PROFITS; OR BUSINESS INTERRUPTION) HOWEVER CAUSED AND ON ANY THEORY OF LIABILITY, WHETHER IN CONTRACT, STRICT LIABILITY, OR TORT (INCLUDING NEGLIGENCE OR OTHERWISE) ARISING IN ANY WAY OUT OF THE USE OF THIS SOFTWARE, EVEN IF ADVISED OF THE POSSIBILITY OF SUCH DAMAGE.
