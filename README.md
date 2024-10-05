# PARKING_LOT_USING_COUNTER
# Ojective
The objective of using a counter system in a parking lot is to manage and monitor the number of vehicles entering and exiting the facility, ensuring that parking space is utilized efficiently and effectively.
# Tools & technologies
Hex D Flip Flop, 2:1 Mux, Shift Register, Bcd TO 7 Segment Decoder,  
Intigrated Curcuits –  
74HC157 (Quad- 2:1 MUX)  
74HC174 (Hex D flip flop)  
74LS47 (Bcd TO 7 Segment Display Driver)
# Working Principle
- Sensors at entry and exit points to detect vehicles.
- Counter to track the number of cars in the parking lot.
- Display showing available spots or "full" status.
- Automated gates controlled by the counter.
- Optional integration with apps for real-time parking availability.
# Constrction
- The circuit leverages d flip-flops as shift register.
- As we require up and down counter both implemented in the same circuitry, we are using 2:1 multiplexers in order to select increment or decrement as per the sensor output.
- By default our circuit is designed for decreasing counter and by switching it using an increment button or signal we toggle the selection line of multiplexers.
- At starting (when count is 0), decrement operation is made disabled by an application of pnp transistor.
- Similarly when the count is 9, increment option is made disabled.
- When all the states are zero, 1 is inserted at 1b input of the ‘lsb’ mux.
# Output
The output of the parking lot system using a counter, assumed the system tracks the number of cars entering and leaving the parking lot but its showing an error of skipping 1 digit in 7 segment display.
# Future Improvements
We have to take a look on the issues regarding the skipped digit on 7 segment display.
# Applications
Real-time Monitoring of Parking Spaces, Traffic Flow Management, Smart City Integration.
