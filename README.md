# PyTorch_Optimizations

### NumPy* and PyTorch* Optimizations

#### Objective: 

Describe how  Intel SIMD and Cache optimization provided by Intel oneMKL-DNN as well as the Intel Extensions for PyTorch can accelerate your pytorch workloads especially prior to training loop or during post processing. Also explore how to use Intel Extensions to PyTorch and how to access Intel GPU for PyTorch

### Replacing Inefficient code
![SLowWadeWater.PNG](Assets/SlowWadeWater.png)

### Preparation to run on Intel DevCloud

- mkdir **NumPyPyTorchOpt**
- cd **NumPyPyTorchOpt**
- source  source /opt/intel/oneapi/setvars.sh > /dev/null 2>&1 --force 
- conda activate pytorch
- git clone https://github.com/IntelSoftware/PyTorch_Optimizations.git
- cd  PyTorch_Optimizations


This workshop is designed to be used on the DevCloud and includes details on submitting batch jobs on the DevCloud environment.

License
Code samples are licensed under the MIT license. See License.txt for details. Third party program Licenses can be found here: third-party-programs.txt
