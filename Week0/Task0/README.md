# RISC-V Reference SoC Tapeout Program VSD  

<ins> Installation of Tools Required to Tapeout**</ins>
+ System Requirement
   + 6GB RAM, 
   + 50 GB HDD
   + Ubuntu 20.04+
   + 4vCPU
   
+ Yosys Installation (It is RTL Synthesis Tool )
  <ins> To Install Yosys execute following commands on Linux Terminal </ins>
   + $ git clone https://github.com/YosysHQ/yosys.git
   + $ cd yosys 
   + $ sudo apt install make # (If make is not installed please install it) 
   + $ sudo apt-get install build-essential clang bison flex \
    libreadline-dev gawk tcl-dev libffi-dev git \
    graphviz xdot pkg-config python3 libboost-system-dev \
    libboost-python-dev libboost-filesystem-dev zlib1g-dev
   + $ make 
   + $ sudo make install
+ Yosys installation verification
<img width="1255" height="861" alt="yosys" src="https://github.com/user-attachments/assets/02eea897-28bd-455e-8485-d42f543e9145" />


+ Iverilog Installation (It is Verilog Simulator which Compiles and simulates Verilog designs for functional verification)
  + $ sudo apt-get install iverilog
+ Iverilog Installation verfication
  
<img width="1297" height="863" alt="iverilog" src="https://github.com/user-attachments/assets/bcc90648-6a63-41b4-a515-2030057ba8a7" />

+ GTKWave ( Waveform Viewer)
   + $ sudo apt update
   + $ sudo apt install gtkwave

<img width="1287" height="857" alt="gtkwave" src="https://github.com/user-attachments/assets/a00fe908-931a-4ce8-bf47-3853a606d0ee" />


+ Ngspice – Circuit Simulator
  + $ sudo apt update
  + $ sudo apt install ngspice
 
<img width="1281" height="685" alt="ngspice" src="https://github.com/user-attachments/assets/4fba0466-19fe-4a5e-974c-cf3b7bab0c2e" />

 + Magic VLSI – Layout Tool
   # Install required dependencies

+ $ sudo apt-get install m4
+ $ sudo apt-get install tcsh
+ $ sudo apt-get install csh
+ $ sudo apt-get install libx11-dev
+ $ sudo apt-get install tcl-dev tk-dev
+ $ sudo apt-get install libcairo2-dev
+ $ sudo apt-get install mesa-common-dev libglu1-mesa-dev
+ $ sudo apt-get install libncurses-dev

# Clone Magic repository
 + git clone https://github.com/RTimothyEdwards/magic
 + cd magic

# Configure build
+ ./configure

# Build Magic
+ make

# Install system-wide
 + $sudo make install

# Installation Verification
<img width="1297" height="899" alt="magic" src="https://github.com/user-attachments/assets/cf726ff2-93d8-48c0-8e50-3f91a13ad064" />
