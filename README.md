![License: MIT](https://img.shields.io/badge/license-MIT-green)

Copyright (c) 2023 Jingjing Wang

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

The software is provided "as is", without warranty of any kind, express or implied, including but not limited to the warranties of merchantability, fitness for a particular purpose and noninfringement. In no event shall the authors or copyright holders be liable for any claim, damages or other liability, whether in an action of contract, tort or otherwise, arising from, out of or in connection with the software or the use or other dealings in the software.

# RT_MRMT_DSA_BG

This code is developed to explore the microbial-catalyzed denitrification processes in a woodchip bioreactor at the Kiruna pilot site. It was developed based on the previous code RT_MRMT_DSA which can be freely downloaded from https://github.com/Jingjingwangxiang/RT_MRMT_DSA. 

It was published in the Journal of Hydrology on June 2023, with a manuscript titled "Multirate mass transfer simulation of denitrification in a woodchip bioreactor", you are warmly welcome to visit it through the website https://doi.org/10.1016/j.jhydrol.2023.129863. 

Developer: Jingjing Wang

Contact detail: Department of Civil and Environmental Engineering, Universitat Politécnica de Catalunya (UPC), Jordi Girona 1-3, 08034 Barcelona, Spain

Geosciences Department, Institute of Environmental Assessment and Water Research (IDAEA), Severo Ochoa Excellence Center, Spanish Scientific Research Council (CSIC), Jordi Girona, 18-26, 08034 Barcelona, Spain 

Email: jingjingwangxiang@126.com or jingjing.wang.xiang@gmail.com 

Year first available: March, 2023

Latest version: updated on March, 2023 

Hardware required: The code was run on a computer with 12th Gen Intel(R) Core(TM) i7-12700KF 3.60 GHz, 32GB Installed memory (RAM), 64-bit Operating System, x64-based processor.

Software development platform: Microsoft Visual Studio 2022 

Program language: object-oriented programming FORTRAN2003

Compiler: Intel oneAPI 2022 

Library: Intel Math Kernel Library (Intel® MKL).

To solve the system equation (14), we call routine dgbtrf() to compute the LU factorization of the left-hand side matrix of system equation (14), then we call routine dgbtrs() to solve the linear system with the LU-factored square coefficient matrix returned by routine dgbtrf().

Details on how to access the open-source code: the source code can be freely downloaded from GitHub on the public repository https://github.com/Jingjingwangxiang/RT_MRMT_DSA_BG.git 
