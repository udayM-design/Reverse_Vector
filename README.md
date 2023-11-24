# Caravel User Project

[![License](https://img.shields.io/badge/License-Apache%202.0-blue.svg)](https://opensource.org/licenses/Apache-2.0) [![UPRJ_CI](https://github.com/efabless/caravel_project_example/actions/workflows/user_project_ci.yml/badge.svg)](https://github.com/efabless/caravel_project_example/actions/workflows/user_project_ci.yml) [![Caravel Build](https://github.com/efabless/caravel_project_example/actions/workflows/caravel_build.yml/badge.svg)](https://github.com/efabless/caravel_project_example/actions/workflows/caravel_build.yml)

| :exclamation: Important Note            |
|-----------------------------------------|

## Please fill in your project documentation in this README.md file 

Refer to [README](docs/source/index.rst#section-quickstart) for a quickstart of how to use caravel_user_project

Refer to [README](docs/source/index.rst) for this sample project documentation. 

Refer to the following [readthedocs](https://caravel-sim-infrastructure.readthedocs.io/en/latest/index.html) for how to add cocotb tests to your project. 

### Cloning and Setup
```
git clone https://github.com/udayM-design/Reverse_Vector.git
mkdir ~/asic
export OPENLANE_ROOT=~/asic/openlane
export PDK_ROOT=~/asic/pdk
cd Reverse_Vector/
make setup

ls $PDK_ROOT
ls $OPENLANE_ROOT
ls openlane/
make user_proj_example
ls gds/
klayout gds/user_proj_example.gds
```
![clonning](https://github.com/udayM-design/Reverse_Vector/assets/93391726/0565beb5-f4d6-4895-ac48-f8e5f8c2a4e2)
![12](https://github.com/udayM-design/Reverse_Vector/assets/93391726/fe6f5c8e-0a64-46f2-b771-7615979fe06b)
#
#### Creating ssh key
![sshkeygen](https://github.com/udayM-design/Reverse_Vector/assets/93391726/4b3635ef-6754-429d-b9c5-6ab5848f7546)
#
#### MPW Precheck
![MPW_precheck1](https://github.com/udayM-design/Reverse_Vector/assets/93391726/716eed67-3a19-4833-9376-1070292f7675)
![MPW_precheck2](https://github.com/udayM-design/Reverse_Vector/assets/93391726/dc535e94-d9d9-4d3d-a960-22d1233008be)


