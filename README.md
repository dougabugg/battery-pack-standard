# battery-pack-standard
I want to design a standard "rechargable battery pack". Currently, we have standards for
disposable alkaline batteries, like "AA", "AAA", "PP3" (9-volt), and rechargable Nickel-
Metal Hydride (NiMH) are starting to become more popular, and we now have a multitude of
"smart devices" each their their own proprietary Lithium-ion batteries, and seem to cope
with "USB battery packs" to supplement devices with proprietary batteries. In addition,
there are power tools with removable rechargable batteries, but they are usually still
proprietary and limited to a single brand. My goal is to come up with a basic and open
source form factor for a "universal" rechargable battery pack, that can be "standardized"
and open, and that devices can be built to "just work" with it.

Now, I personally want to get the most out of my batteries. I want to reduce waste, and
encourage responsibly disposing or recycling of used cells. I also want the battery pack
to be extremely versatile and interchangeable. Ideally, there would be a single circuit
design, that can accommodate multiple independent cells, (each around 1 to 2 volts), and
a switched-mode power supply, and reliably and safely output a variable amount of power
within reasonable ranges for voltage and current. Think of it sort of like a bench-top
power supply, but limited to maybe 5 or 9 volts, and 1 or 2 amps, and powered by an array
of independent Li-ion or NiMH cells. The control circuitry could measure and record the
charging and discharging of each cell, in addition to temperature, and could advise when
any individual cell is failing and should be replaced.

There could be multiple form factors for the circuit design as well. For example, to
power a small LED head lamp, the circuitry may only support one or two cells, and would
have a small and light-weight footprint. For a battery pack capable of running a laptop,
the footprint of a car battery or toolbox might be tolerable.
