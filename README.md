# jetson-experiements

Possible ideas for computationally intensive programs to run:
- Particle simulation
- Multi-agent behavioural simulation
- Evolution something something

Keep in mind that the quad-core CPU. If the memory load the GPU computation is low, could have each cpu manage it's own set of computations, feed them into a single stream.
- Could have multiple threads track the real-time input from different sensors or actuators.
- Should be a visual/behavioural end-result that takes advantage of the fact that the system is small and full of pins.

Good place to start:
- Simple program that does some large computation, and on completion blinks an LED? Only CPU has access to memory space with GPIO afaik, but that should work.
