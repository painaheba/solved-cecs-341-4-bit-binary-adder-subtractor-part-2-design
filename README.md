Download Link: https://assignmentchef.com/product/solved-cecs-341-4-bit-binary-adder-subtractor-part-2-design
<br>



<strong>Waveform:</strong>

<strong>Steps Taken For Results:</strong>

The lab prompts us to create a 4-bit binary Adder-Subtractor circuit using the Vivado IP Integrator tool. To do so, we first had to take preliminary steps to get to the end result. We must take into account that a 4-bit binary Adder-Subtractor consists of four total full adder modules. A full adder adds three inputs and produces two outputs. Being able to understand the concept behind the full adder assists us in determining what they could be used for in a 4-bit binary Adder-Subtractor circuit. In a 4-bit binary Adder-Subtractor circuit, the full adders are in charge of taking input, checking for overflow, and committing one-bit addition. In addition to the full adders, other parts of a 4-bit binary Adder-Subtractor circuit consists of include inputs, XOR gates, slicers, and a concatenator. There are two inputs that take in 4-bit values. One input will take care of determining whether the circuit will perform addition or subtraction. There are a total of four XOR gates that pass the input into the full adder. Before being passed into the full adder, however, these bits are sliced by the slicers. The full adders will then perform 1-bit addition and will pass on any carry bits into the other full adders. The sum of these full adders is then concatenated through the concatenator, which then presents us with the result. Being able to understand the way a 4-bit Adder-Subtractor circuit works allowed our team to construct a block diagram using the IP Integrator Tool in Vivado. My team and I used the diagram below to also aid us along the way in producing the block diagram.