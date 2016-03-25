# Verilog-CPU-Design
Verilog Cpu Assembler
CSE 315
DIGITAL LOGIC DESİGN
TERM PROJECT 
2015 

           The table shown below  has information about the instruction set architecture which 
           we have designed for the term project.  There used 4 bits to implement op codes of instructions and
           used 3 bits to implement 8 registers. 
           Register Example : R0 = 000, R2 = 010, R7 = 111.
           For x values in the table, in assembler there have inserted 0 values. 
           Example Instructions : 
           ADD R0,R1,R2 = 0000000001010000b = 0050h
           ADDI R3,R5,2  = 0001011101000010b = 1742h

INS	[ 15:12 ]	[ 11:9 ]	[ 8:6 ]	[ 5:3 ]	[ 2:0 ]
ADD	  0000    	DR	      SR1	    SR2	     X
AND	  0010     	DR	      SR1	    SR2	     X
ADDI	0001	    DR	      SR1	       IMM6
ANDI	0011	    DR	      SR1	       IMM6
CMP	  0100	    REG1	    REG2      	X
CMPI	0101    	REG1	          IMM9
JUMP	1110    	X	            ADDRESS9
LD	  0110    	DR	          ADDRESS9
ST	  1000	    SR	          ADDRESS9
JE	  1001	    X           	ADDRESS9
JA	  1010	    X            	ADDRESS9
JB	  1011	    X           	ADDRESS9
JAE	  1100    	X           	ADDRESS9
JBE  	1101    	X	            ADDRESS9


