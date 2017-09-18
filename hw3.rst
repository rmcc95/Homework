Basic measurement units:
=====================================================
*1 meter = 39.37 inches
-1 in = 2.54cm
-1m = 100 cm = (100cm/2.54cm) = 39.37in
*1 mile = 5280 feet
*1 mile = 1609.75 meters
-1m = 3.28ft
-5280ft/3.28ft=1609.75m
*Circumference of the Earth = 3958.8 miles
-ref: https://solarsystem.nasa.gov/planets/earth/facts

Basic terminology
=====================================================
*yotta something = 1*10^(24) times something
*kilo something = 1000 times something
*Hecto something = 100 times something
*deca something = 10 times something
*something = something (duh!)
*milli something = 1/1000 of something
*micro something = 1/1,000,000 of something
*nano something = 1/1,000,000,000 of something
*pico something = 1/1000000000000 of something

What is the speed of light?
======================================================
*Speed of light = 186282 mps (miles per second)
	-ref: https://www.google.com/search?q=speed+of+light+in+miles+per+second&oq=speed+of+light+in+miles+per+second&aqs=chrome..69i57j6j0.5429j0j4&sourceid=chrome&ie=UTF-8

*Speed of light = 2.998e+5 kps (kilometers per second)
	-ref: https://www.google.com/search?q=speed+of+light+in+meters+per+second&oq=speed+of+light+in+meters+per+second&gs_l=psy-ab.3..0i20k1j0l2j0i5i30k1.122506.124465.0.124934.9.9.0.0.0.0.310.1276.0j3j2j1.6.0....0...1.1.64.psy-ab..6.3.626...0i7i30k1.0.brLmceZ2sxA
	-I divided the meters per second by 1000 to get my answer above in kilometers per second.

How far an electronic signal can move through a wire:
======================================================
*In one nanosecond = 11.8 inches
	-(1.18*10^(10))in * (1*10^(-9))secs = 11.8in
	-Speed of light in inches per second:
	-ref :https://www.google.com/search?q=speed+of+light+in+inches+per+second&oq=speed+of+light+in+inches+per+second&gs_l=psy-ab.3..0j0i5i30k1.27935.29784.0.30106.11.11.0.0.0.0.129.928.9j1.10.0....0...1.1.64.psy-ab..2.9.835...0i7i30k1j0i8i7i30k1j0i7i5i30k1j0i8i30k1.0.qgAb1x_pckI

*In one microsecond = 983.3 feet
	-11.8in * 1000 = 11800in/microsecond
	-11800in/12in = 983.3ft

*In one millisecond = 186.2 miles
	-983.3ft * 1000 = 983,300ft/ms
	-983,300ft / 5280ft = 186.2mi/ms
	
*In one second = 186,200 miles
	-186.2*1000 = 186,200mi/s

*In one second = 47 times around the Earth!
	-186,200mi / 3958.8mi = 47

Intel i7-7700, 7th Generation Pentium chip
=======================================================
*Manufacturing Process = <14>nm
	
*Transistor Count = 1,400,000,000 transistors
	
*Die Size: 264mm^2
	
*Number of cores = 4
	
*Number of threads = 8
	
*Maximum (turbo) clock frequency = 4.20 GHz.
	
*Maximum memory = 64 GB.
	
*Distance between transistors = 13,731 nanometers.
	-sqrt(1.4billion) = 37417 transistors on each side of the square chip.
	-sqrt(264mm^2) = 16.24mm side length of the chip.
	-(16.24mm / 37417 transistors) = 13,731 nanometers between transistors.
	
*Time to move electrons between adjacent transistors = 0.0458 picoseconds.
	-Electrons move at 2.998*(10^17) nanometers/sec.
	-(13731 / 2.998*(10^17)) = 0.0458 picoseconds.
	
	-Ref for manufacturing process, # of cores, # of threads, max clock freq, max mem:
	+https://ark.intel.com/products/97128/Intel-Core-i7-7700-Processor-8M-Cache-up-to-4_20-GHz
	-Die size:
	+264mm^2 as provided in the assignment instructions.
	-Transistor count:
	+1.4billion as provided in the assignment instructions.

Counting up
=======================================================
The current Pentium processor uses 64-bit “registers”. Assuming your processor is ticking away at a rate of 2.7 GHz, how long will it take to reach the biggest number 
the register can hold (Hint: the biggest number is 2^64 - 1):

	Time until the register hit the maximum value = 216.65 years
	(((2^64)-1)/(2.7GHz)/(31536000sec)) = 216.65 years
	