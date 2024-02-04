This project presents a simple arithmetic logic unit (ALU) implemented in Verilog. The ALU
takes in a bit stream and a clock signal as inputs, and performs a simple operation on two
4-bit values, "a" and "b". The "out" output is connected to the "out_reg" register and will
change on the rising edge of the clock signal.
The project utilises a state machine to control the operation, where the current state is stored
in the "cur_state" register and the next state is stored in the "next_state" register. The state
machine has 11 possible states, represented by the parameters "S0" to "S15". The "count"
register is used to keep track of the number of bits received in the bit stream.
The operation performed is determined by the current state and the bit stream input. The
possible operations include loading values to the registers and performing operations like
adding, subtracting, bitwise OR and bitwise AND .The final result is stored in the "buffer"
register and is assigned to the "out_reg" register when the operation is complete.
Overall, this project provides a basic understanding of how to implement a simple ALU in
Verilog and how to use state machines to control the operations. It can be used as a starting
point for more complex digital systems that require arithmetic operations.
