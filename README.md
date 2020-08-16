# RISC_V-Simulator
CS-204 Group Project, RISC-V SIMULATOR
-----------Requirements------------------

	-PyQt5 (for GUI): pip install PyQt5
	-BitString python library: pip install bitstring 

-----------------Team-------------------

	- Jeevant Kumar Sah - 2018CSB1097
	- Mithilesh Kumar   - 2018CSB1101
	- Aman Singh Khuswaha - 2018CSB1071
	- Siddharth Nayak - 2018CSB1125
	- Mohan Joshi     - 2018CSB1102

---------------------------------------
Phase 1:-
Takes "read_file.asm" as input
	 file for processing.
	-Outputs machine code in "write_file.
	 mc".

Phase 2:-
Implemented data path and control paths to run the Instructions.
Implemented all stages i.e. Fetch, Execute, Decode, Memory, Writeback
Implemented inter state buffers, memory unit and register files for the same

Phase 3:-
Implemented pipeline structure with and without data forwarding

Features:-
    Functionality to switch between 
        1. Non- pipelined
        2. Pipelined with stalls
        3. Pipelined with Data forwarding
    
    Functionality to output register values and values of the inter state buffers

    Functionality to run cycle by cycle

    Give out number of mispredictions, number of stalls etc.

    Print register values and inter state buffers after every cycle.

Instructions not supported:-
    - auipc, lui and pseudo instructions not handled.
    - Assumption, code would be free of the syntax errors.


GUI :- Electron framework
            - Node JS backend
            - HTML CSS frontend
