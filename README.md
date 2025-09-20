# RISC-V-SOC-TAPEOUT-PROGRAM-VSD-Week0-Task0
RISC-V Reference SoC Tapeout Program VSD

## Software Required
Virtual box:Version 7.2.2 r170484      
Ubantu:ubantu-24.043-desktop-amd64        

## **System Requirements**
8 GB RAM     
40 GB HDD     

### **Configuring virtual box to mount and install Ubantu**
1)Sudo apt_get install git     
2) git clone https://github.com/kunalg123/vsdflow.git     
3) cd vsdflow     
4) chmod 777 opensource_eda_tool_install.sh     
5) sudo /opensource_eda_tool_install.sh     
6) ./vsdflow spi_slave_design_details.csv      
7) ./vsdflow picorv32_design_details.csv      

### ***EDA Tools Installation***
#### <ins>*Yosys*</ins>
bash
$ sudo apt-get update      
$ git clone https://github.com/YosysHQ/yosys.git       
$ cd yosys       
$ sudo apt install make               # If make is not installed     
$ sudo apt-get install build-essential clang bison flex \      
    libreadline-dev gawk tcl-dev libffi-dev git \       
    graphviz xdot pkg-config python3 libboost-system-dev \        
    libboost-python-dev libboost-filesystem-dev zlib1g-dev       
$ make config-gcc            
$ git submodule update --init --recursive      
$ make        
$ sudo make install      
'''        
![YOSYS Screenshots](images/YOSYS.png)     

#### <ins>*Iverilog*</ins>
bash      
$ sudo apt-get update       
$ sudo apt-get install iverilog      

![IVERILOG Screeenshots](images/IVERILOG.png)      

#### <ins>*gtkwave*</ins>     
bash      
$ sudo apt-get update      
$ sudo apt install gtkwave       

![GTKWAVE Screenshots](images/GTKWAVE.png)          


