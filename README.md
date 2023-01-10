# Radial Engine

This model is an assembly of many different parts of a five cylinder radial engine. A pair of two counter-rotating propeller blades are powered by the crankshaft of this engine.

![animation](images/animation.gif)

## Engine Block

The radial engine consists of five cylinders pointing outwards in a ring around a combustion chamber. Each cylinder contains a piston which can freely slide within the cylinder. Each piston is pinned to a connecting rod which can freely pivot underneath the piston. The other end of each connecting rod is pinned to a circular hub which all the connecting rods are pinned to. It is important to note that the first piston (top piston) is pinned to a rigid connecting rod which is a part of the hub. This helps to keep the connecting rods from colliding and helps the hub follow the correct path of motion.

## Crankshaft

Connected to the connecting rod hub are two counterweights. The first counterweight sits behind the hub and spins around an axle located in the center of the back of the engine block. This counterweight has a off-cenetered shaft that slides through the connecting rod hub and attaches to the frontal counterweight. The frontal counterweight is directly connected to the crankshaft which goes on the spin the propellers. The spinning axis of the crankshaft is inline with the axis on which the rear counterweight spins. As the pistons fire, the hub moves in a circular motion around the center of the engine block. This motion drags the counterweights around the center of the engine block with the hub. This is what causes the crankshaft to spin.

## Combustion

The piston firing sequence in a radial engine fires in order of every other piston. If the pistons were numbered counterclockwise with Piston 1 being at the top, the strokes would follow the following pattern. If Piston 1 begins by firing, the pistons will then fire in order of 3, 5, 2, and 4 before going back to Piston 1 and repeating. While the odd numbered pistons are going on their combustion strokes, the even numbered pistons will be on their intake stroke. Similarly, when the odd numbered pistons are on their exhaust strokes, the even numbered pistons are on their compression strokes. Likewise, when the even numbered pistons are on their combustion and exhaust strokes, the even numbered pistons are on their intake and compression strokes respectively. This combustion sequence is what pushes the connecting rod hub around the engine block producing torque on the crankshaft.

## Counter-Rotating Propellers

The propellers which the radial engine powers were modelled after the propellers of Tu-95 Bear, a Cold War era aircraft. These propellers are powered by the same engine, but spin in opposite directions. This effect is achieved through a series of bevel gears which invert the direction of rotation. The rear propeller is attached to the last gear in the gear box. This gear is connected to the first gear in the gearbox through an intermediary bevel gear which inverts the direction of the spin. The first gear is connected directly to the crankshaft and spins in unison with it. Therefore, when the crankshaft spins, the rear propeller spins in the opposite direction. The front propeller is connected directly to the crankshaft. The crankshaft extends through the rear propeller which has a hole in its center. Since the crankshaft is nested inside of the rear propeller, it allows the front propeller to spin independently, and thus, in the opposite direction. Overall, this allows both propellers to spin in opposite directions while powered by the same radial engine.

# Model

## Isometric View
![Isometric View](images/iso.png)

## Side View
![Side View](images/side.png)

# Rear View
![rear View](images/rear.png)