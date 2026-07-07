### Install Fortran compiler (Linux, WSL):
sudo apt update
sudo apt install gfortran

### Verify:
gfortran --version

### Compile:
fgortran hello.f90 -o hello

### Run:
./hello
