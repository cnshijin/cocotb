**cocotb** is a coroutine based cosimulation library for writing VHDL and Verilog testbenches in Python.


* Skim the introductory presentation: http://potential.ventures
* Read the [documentation](http://cocotb.readthedocs.org)
* Get involved: [Raise a bug / request an enhancement](https://github.com/potentialventures/cocotb/issues/new) (Requires a GitHub account)
* Get in contact: [E-mail us](mailto:cocotb@potentialventures.com)
* Follow us on twitter: [@PVCocotb](https://twitter.com/PVCocotb)

## Quickstart

    # Install pre-requisites (waveform viewer optional)
    sudo yum install -y iverilog python-devel gtkwave
    
    # Checkout git repositories
    git clone https://github.com/potentialventures/cocotb.git
    
    # Run the tests...
    cd cocotb/examples/endian_swapper/tests
    make
    
    # View the waveform
    gtkwave sim_build/waveform.vcd