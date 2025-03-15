**Test Environment:**

VirtualBox 7.0.18

Ubuntu 22.04.4

Python 3.10.12

Mbed CLI 1.10.4

GNU Arm Embedded Toolchain 6-2017-q2-update (https://developer.arm.com/downloads/-/gnu-rm)

Mbed 2: mbed library release version 165 (https://os.mbed.com/users/mbed_official/code/mbed/)

NUCLEO-F401RE (STM32F401RE)

-------------

**Test Commands:**

cd mbed2-project-template

mbed config GCC_ARM_PATH "/home/{USER NAME}/{GNU Arm Embedded Toolchain Directory}/bin"

pip install -r .temp/tools/requirements.txt

mbed compile -m NUCLEO_F401RE -t GCC_ARM

-------------

**Hotfix for Compilation Error:**

pip install fuzzywuzzy==0.18.0 intelhex==2.3.0 Jinja2==2.11.3 jsonschema==2.6.0 pyelftools==0.27
