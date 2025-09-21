## Classical Mechanics

Classical mechanics is the **branch of physics that studies the motion of macroscopic objects and the forces that affect them,** primarily **using Newton's laws of motion.** It **describes how objects move under the influence of forces and predicts their future and past states with accuracy for everyday phenomena.** Classical mechanics is an approximation that breaks down at very small scales (quantum mechanics) and at speeds approaching the speed of light (relativistic mechanics).
**Key Concepts**
* Newton's Laws of Motion: The **foundation of classical mechanics, these laws describe the relationship between an object's motion and the forces acting upon it.**
* Force: An **influence that can cause an object to change its velocity.** 
* Motion: **The change in an object's position over time.**
* Determinism: If you know the **current state of an object and the forces acting on it, you can predict its future and past motions using classical mechanics.**
**Applications and Limits**
* Applicability: Classical mechanics **accurately describes the motion of everyday objects, from projectiles to celestial bodies like planets and galaxies.** 
* Limits: It is not suitable for phenomena at extremely small scales (subatomic particles) or at very high speeds close to the speed of light, where quantum mechanics and relativity are required. 
**Example** 
**Predicting the trajectory of a baseball or the orbit of a planet are classic examples of problems solved by classical mechanics.**
In essence, classical mechanics provides a powerful framework for understanding the physical world at human scales, but it is essential to recognize its limitations when dealing with the very small or the very fast.

### Newton’s laws
Newton's Three Laws of Motion describe the **relationship between an object's motion and the forces acting on it:**

* **First Law of Motion (Law of Inertia):** **An object at rest stays at rest, and an object in motion stays in motion with the same velocity, unless acted upon by a net external force.**
  Statement: An object maintains its state of rest or constant velocity unless a net external force acts upon it.
* Concept: Objects tend to maintain their current state of motion. If something is still, it will remain still, and if it's moving, it will continue moving at a constant speed and in a constant direction unless a force interferes.
Example: A book on a table will stay there unless someone pushes it or another force acts on it.


* **Second Law of Motion (Law of Acceleration):**
Statement: **An object's acceleration is directly proportional to the net force and inversely proportional to its mass, acting in the same direction as the force.**(an object's acceleration is proportional to its net force ex: u pushing an object directly affects the acceleration of an object  meancwhile its acceleration is inversely proportional to its mass, the higher the mass the weaker the acceleration depending on the force)
  The acceleration of an object is directly proportional to the net force acting on it and inversely proportional to its mass (F=ma).
  Example: **Pushing an empty cart is easier than a full one because the less massive cart accelerates more quickly with the same force.**
Playing baseball: When a baseball player hits a ball with a bat, the **bat applies a force to the ball, causing it to accelerate. The harder the player hits the ball (more force), the greater the acceleration, and the farther the ball travels.**
Catching a ball: A baseball player catching a ball instinctively moves their hand backward. By increasing the time it takes to stop the ball's momentum, they reduce the force exerted on their hand (\(F=\Delta p/\Delta t\)).
1. "Acceleration is directly proportional to the net force"
What this means: The more force you use, the more an object will accelerate.
In other words: If you push something harder, it will speed up faster.
Analogy: Imagine pushing a shopping cart. If you push it gently, it moves slowly. If you give it a hard shove, it speeds up quickly. 
2. "Acceleration is inversely proportional to its mass" (the higher the mass the weaker the force thats what inversely means)
What this means: The more mass an object has, the harder it is to accelerate. Or, with the same force, a heavier object will accelerate less than a lighter one.
In other words: For the same amount of effort, a lighter object speeds up more than a heavier one.
Analogy: Imagine pushing two shopping carts with the same amount of effort. One is empty, and one is full of groceries. The empty cart accelerates much more easily and quickly than the full one, which resists the change in motion because of its greater mass.

* **Third Law of Motion (Law of Action-Reaction):**
* **For every action, there is an equal and opposite reaction.** Forces occur in pairs, so if object A exerts a force on object B, B exerts an equal and opposite force on A.
Important point: These forces act on different objects and do not cancel out.
Example: **A rocket pushes gas down (action), and the gas pushes the rocket up (reaction). When walking, your feet push backward on the ground (action), and the ground pushes forward on your feet (reaction).**
Swimming: **A swimmer pushes the water backward with their arms and legs (action). The water, in turn, pushes the swimmer forward with an equal and opposite force (reaction).**
A rocket launch: A rocket's engine expels hot gases downward at high velocity (action). The expelled gases push the rocket upward with an equal and opposite force, known as thrust (reaction).
Jumping off a boat: When you jump from a small boat to a dock (action), the **boat moves away from the dock (reaction).** This is because your **force on the boat causes the boat to exert an equal and opposite force on you, propelling you forward.**

### Oscillators & waves (mass-spring, pendulum, wave equation).
**What are Oscillations?**
Oscillations are repetitive movements of a system about an equilibrium position, while waves are disturbances that transfer energy through a medium via these oscillations. The relationship is fundamental: oscillations create waves, and the individual particles in a medium oscillate as a wave passes through. 

**What are Oscillators?**
A simple harmonic oscillator (SHO) is a system where the restoring force is directly proportional to the displacement from equilibrium. This relationship produces a characteristic sinusoidal motion



**Mass-spring System**
A mass attached to a spring is a classic example of an SHO, where the restoring force comes from the spring obeying Hooke's Law. 
*   **Restoring Force:**
    $$F = -kx$$
*   **Equation of Motion:**
    $$-kx = m\frac{d^2x}{dt^2} \implies \frac{d^2x}{dt^2} + \frac{k}{m}x = 0$$
*   **Angular Frequency ($\omega$):**
    $$\omega = \sqrt{\frac{k}{m}}$$
*   **Period ($T$) and Frequency ($f$):**
    $$T = 2\pi\sqrt{\frac{m}{k}} \quad \text{and} \quad f = \frac{1}{T} = \frac{1}{2\pi}\sqrt{\frac{k}{m}}$$


### Hooke's Law

States that **if you apply a force to a spring, then the force stretches spring.** And if you don't stretch too much, **Hooke's law says that the amount of force you apply is proportional to the stretch.** So, that means that **if you apply twice the force, you get twice the stretch.**

## Simple pendulum
For small angular displacements ($\theta$), a simple pendulum behaves as a simple harmonic oscillator.

*   **Equation of Motion (for small angles):**
    $$\frac{d^2\theta}{dt^2} + \frac{g}{L}\theta = 0$$
*   **Angular Frequency ($\omega$):**
    $$\omega = \sqrt{\frac{g}{L}}$$
*   **Period ($T$):**
    $$T = 2\pi\sqrt{\frac{L}{g}}$$

**Pendulum**
a pendulum is a simple yet powerful example of an oscillator that demonstrates how a system with a restoring force can produce periodic, or oscillatory, motion. This oscillating motion can, in turn, be used to generate waves.

Pendulums as oscillators
The simple pendulum consists of a point mass (the bob) attached to a light, inextensible string of a fixed length and suspended from a pivot. 
Restoring force: When the pendulum bob is displaced from its equilibrium position (hanging straight down), gravity creates a restoring force that pulls the bob back towards equilibrium.
Simple harmonic motion (SHM): For small displacements (less than about 15°), this restoring force is directly proportional to the displacement. In this case, the pendulum's motion is a close approximation of simple harmonic motion, a type of oscillation that follows a predictable sinusoidal pattern.
Energy conversion: A swinging pendulum demonstrates the conservation of energy. As it swings down, its gravitational potential energy is converted into kinetic energy, reaching maximum kinetic energy at the bottom of its swing. This kinetic energy is then converted back into potential energy as the pendulum swings up to its maximum height on the other side. 
The link to waves
While a single pendulum is an oscillator, a series of pendulums can illustrate wave phenomena. A "pendulum wave" machine uses several pendulums of slightly different lengths, and therefore slightly different oscillation periods. 
Constructing a wave: When all the pendulums are started at the same time, their different periods cause them to gradually fall out of sync, creating the illusion of a complex wave pattern moving through the pendulums. The longest pendulums swing the slowest, while the shortest ones swing the fastest.
Periodic repetition: Because each pendulum completes a different number of oscillations in a specific amount of time, they will eventually all align again, and the beautiful, complex wave pattern will repeat.
Wave characteristics: This demonstration effectively illustrates fundamental wave characteristics, such as amplitude, wavelength, and frequency, through the visible, synchronized motion of individual oscillators. 
In summary, the pendulum serves as a foundational mechanical example of an oscillator. By understanding the forces and energy conversions that govern its periodic motion, we gain insight into the principles of simple harmonic motion. Furthermore, by observing how multiple pendulums interact, we can visually grasp how simple oscillations can combine to create complex, periodic waves. 


## The wave equation
A mass attached to a spring is a classic example of a simple harmonic oscillator.
A wave is a disturbance that carries energy through a medium. Oscillating particles within the medium transmit this energy from one point to another. The wave equation describes how this disturbance propagates. 

Transverse wave on a string
For a one-dimensional transverse wave, such as one traveling along a stretched string, the wave equation can be derived by applying Newton's second law to a small segment of the string. 
Derivation: By considering the net vertical force on a small segment of string and using the small-angle approximation, the wave equation is:

The one-dimensional transverse wave equation can be expressed as:
$$\frac{\partial^2y}{\partial x^2} = \frac{1}{v^2}\frac{\partial^2y}{\partial t^2}$$

*   The wave speed ($v$) on a string is given by:
    $$v = \sqrt{\frac{T}{\mu}}$$
*   A general solution for a sinusoidal wave is:
    $$y(x,t) = A\sin(kx - \omega t + \phi)$$

The key link between oscillators and waves is the motion of the particles in the medium. SHM within a wave: As a wave propagates, individual particles of the medium undergo simple harmonic motion. For a transverse wave on a string, each point on the string oscillates up and down, even though the wave itself moves horizontally.Wave velocity vs. particle velocity: It is crucial to distinguish between the velocity of the wave (\(v\)), which is the speed at which the disturbance propagates, and the velocity of the oscillating particles in the medium (\(v_{y}\)), which is transverse to the wave's motion. 


### Central forces (Kepler problem → conservation laws).

In a central force problem, an object moves under a force that is always directed toward or away from a fixed point and whose magnitude depends only on the distance from that point.(Gravity in planetary motion) The Kepler problem is the classic example, which describes the orbital motion of a planet under the Sun's inverse-square gravitational force. 

### What is a Central Force?

A central force is a force that is always directed toward or away from a fixed point (the center of force) and whose magnitude depends only on the distance from that point.

The force vector can be expressed as:

$$
\\mathbf{F}(\\mathbf{r}) = f(r)\\hat{\\mathbf{r}}
$$

where:
* $\\mathbf{F}$ is the force vector.
* $f(r)$ is a scalar function that depends only on the distance $r$.
* $\\hat{\\mathbf{r}}$ is the radial unit vector.

### The Kepler Problem

The Kepler problem is the classic example of central force motion, specifically describing the motion of two bodies interacting via an inverse-square law force, like gravity.

The gravitational force is given by:

$$
F(r) = -\\frac{G M m}{r^2}
$$

where:
* $G$ is the gravitational constant.
* $M$ and $m$ are the masses of the two bodies.
* $r$ is the distance between their centers.

### Conservation Laws in Central Force Motion

In any central force problem, the following fundamental conservation laws apply.

#### 1. Conservation of Angular Momentum

Since a central force is always directed radially, it produces zero torque ($\\tau$) about the center of force.

$$
\\tau = \\mathbf{r} \\times \\mathbf{F} = \\mathbf{r} \\times (f(r)\\hat{\\mathbf{r}}) = 0
$$

According to Newton's second law for rotation, torque is the rate of change of angular momentum ($\\mathbf{L}$).

$$
\\frac{d\\mathbf{L}}{dt} = \\tau = 0
$$

This implies that the angular momentum vector $\\mathbf{L}$ is constant (conserved).

$$
\\mathbf{L} = \\mathbf{r} \\times \\mathbf{p} = \\text{constant}
$$

**Implications:**
* **Planar Motion:** The conservation of $\\mathbf{L}$ means the motion is confined to a single plane perpendicular to $\\mathbf{L}$.
* **Kepler's Second Law:** This law, which states that a line segment joining a planet and the Sun sweeps out equal areas over equal intervals of time, is a direct consequence of angular momentum conservation:

$$
\\frac{dA}{dt} = \\frac{1}{2}r^2\\dot{\\theta} = \\frac{L}{2m} = \\text{constant}
$$

Everyday examples of torque
Opening a door
With torque: You push on the door handle, which is far from the hinges. This creates a large torque that easily rotates the door on its hinges.
Without torque: If you were to push on the door right at the hinge (where the distance from the pivot is zero), you would create no torque, and the door would not rotate, no matter how hard you pushed. 
Using a wrench
With torque: To loosen a stubborn bolt, you apply a large force to the end of a long wrench handle. The distance from the center of the bolt (the pivot) to your hand is the lever arm. The longer the lever arm, the more torque you can apply for the same amount of force.
Changing torque: By using a longer wrench, you can generate more torque without applying more force, making it easier to turn the bolt. 
Riding a bicycle
With torque: As you pedal, you apply a downward force on the bicycle pedals, which are attached to the cranks. This force creates a torque around the sprocket, which is transmitted to the wheel through the chain, causing the wheel to rotate.
Changing torque: A bicycle's gears are a system for varying torque. You can use a lower gear to apply a greater torque to climb a steep hill or a higher gear to apply less torque to move at a higher speed on flat ground. 

#### 2. Conservation of Energy

If the central force is also conservative, the total mechanical energy ($E$) of the system is conserved. A conservative force can be written as the negative gradient of a potential energy function, $V(r)$.

$$
\\mathbf{F} = -\\nabla V(r)
$$

The total energy is:

$$
E = T + V(r)
$$

In polar coordinates:

$$
E = \\frac{1}{2}m(\\dot{r}^2 + r^2\\dot{\\theta}^2) + V(r)
$$

Substituting angular momentum $L = mr^2\\dot{\\theta}$ gives the **effective potential energy** $V_{eff}(r)$:

$$
E = \\frac{1}{2}m\\dot{r}^2 + \\left( \\frac{L^2}{2mr^2} + V(r) \\right) = \\frac{1}{2}m\\dot{r}^2 + V_{eff}(r)
$$

The orbit shape is determined by $E$:
* $E < 0 \\implies$ bound, elliptical (or circular) orbit.
* $E = 0 \\implies$ unbound, parabolic orbit.
* $E > 0 \\implies$ unbound, hyperbolic orbit.

#### 3. Conservation of the Laplace-Runge-Lenz (LRL) Vector

For an inverse-square law force, an additional conserved quantity exists: the LRL vector $\\mathbf{A}$.

$$
\\mathbf{A} = \\mathbf{p} \\times \\mathbf{L} - mk\\hat{\\mathbf{r}}
$$

where $k$ is the constant of proportionality ($F = k/r^2$). For gravity, $k = GMm$.

**Significance:**
* **Kepler's First Law:** Conservation of the LRL vector proves that the orbit is a conic section (ellipse, parabola, or hyperbola).
* **Orbit Shape and Orientation:** The magnitude of $\\mathbf{A}$ determines eccentricity, and its direction points along the major axis towards periapsis.

### Connecting Conservation Laws to Kepler's Laws

* **Kepler's 1st Law (Law of Ellipses):** Orbits are ellipses with the Sun at one focus. The LRL vector conservation proves this.
* **Kepler's 2nd Law (Law of Equal Areas):** A direct result of angular momentum conservation. Areal velocity is constant.
* **Kepler's 3rd Law (Law of Periods):** $T^2 \\propto a^3$. Energy and angular momentum conservation allow this, but the inverse-square force law gives the exact proportionality.
"

Newton's laws of rotation describe how rotating bodies behave, analogous to his laws of linear motion. The rotational version of Newton's first law states that a body will maintain its state of rotational motion (rest or constant angular velocity) unless acted upon by a net external torque. Newton's second law for rotation states that the net torque (Στ) on a body is equal to the product of its moment of inertia (I) and its angular acceleration (α), expressed as Στ = Iα. Newton's third law for rotation states that for every action torque, there is an equal and opposite reaction torque. 
Here are the rotational forms of Newton's laws:
Newton's First Law for Rotation
Concept: A body in a state of rotational rest will remain at rest, and a body in a state of rotational motion will continue to rotate with a constant angular velocity, unless acted upon by a net external torque. 
In essence: Just like in linear motion, an object's tendency to stay at rest or in uniform motion continues without an external force, but in rotational motion, it is a net external torque that causes a change in rotation. 
Newton's Second Law for Rotation
Concept: This law relates the net torque applied to an object to its resulting angular acceleration and its rotational inertia. 
Formula: Στ = Iα 
Στ (Sigma Tau): The net torque acting on the object. Torque is the rotational equivalent of a force and is a measure of how much an object is likely to rotate. 
I: The moment of inertia. This is the rotational equivalent of mass and indicates an object's resistance to changes in its rotational motion. 
α (alpha): The angular acceleration. This is the rate of change of the object's angular velocity. 
Newton's Third Law for Rotation 
Concept: For every torque exerted by one object on another, there is an equal and opposite torque exerted by the second object on the first.
In essence: When object A applies a torque on object B, object B will apply an equal and opposite torque on object A.

### Noether's Theorem
Noether's theorem establishes a fundamental connection between **the symmetries of a physical system and its conserved quantities.** Put simply, **for every continuous symmetry of a system's action, there is a corresponding conservation law.**

**The theorem is typically formulated in the context of Lagrangian mechanics and applies to continuous, differentiable symmetries of a system's "action".**

### What is the action?
The action $$(\(S\))$$ is a **quantity calculated for a given path, or trajectory, that a system can take from an initial state to a final state over a period of time. It is defined as the integral of the Lagrangian $$(\(L\))$$ over time.The Lagrangian is the difference between the system's kinetic energy $$(\(T\))$$ and its potential energy $$(\(V\))$$, so $$\(L=T-V\)$$. In simpler terms, you can think of the action as a value assigned to an entire path of a particle's motion. For a given starting point and a given ending point, there is an infinite number of possible paths a particle could take. The principle of least action says that the path it actually takes is the one for which the action is the smallest possible value. 

Imagine you have a hiking map with elevation data, and you want to find the easiest path from one point to another. You can define the "effort" of your hike as the total uphill distance minus the total downhill distance.
Action: Your effort for a given path.
Lagrangian: The difference between your "kinetic energy" (walking forward) and your "potential energy" (the altitude).
Principle of least action: The path that requires the least overall effort is the one you would naturally gravitate toward. 

**Core concepts**
* **Symmetry:** **A symmetry is a transformation that leaves a system's action unchanged. In physics, the action is a quantity calculated from a system's Lagrangian (the difference between kinetic and potential energy), and the system's physical path is the one that minimizes this action. (When a physical path is said to minimize an action, it refers to the principle of least action, a foundational concept in physics. The principle states that the actual path a physical system takes between two points in time is the one that minimizes a specific quantity called the "action". )**
* **Continuous symmetry:** This is a transformation that can be varied smoothly by an infinitesimal amount. **It is the continuous nature of the symmetry that distinguishes it from discrete symmetries, such as parity (mirror-image) transformations.**
* **Conservation law:** A conservation law states that a **particular measurable property of an isolated physical system, such as energy or momentum, does not change over time.**
* **Action principle:** In **Lagrangian mechanics, a system's physical trajectory is the one that follows the path of "least action". For a symmetry to exist, a transformation must leave this action invariant.**
Key examples
Noether's theorem provides a deep understanding of why certain physical properties are conserved. The three most famous examples correspond to basic symmetries of space and time: 
Conserved Quantity 	Corresponding Continuous Symmetry	Explanation
Conservation of Energy	Time-translation invariance	If the laws of physics are the same today as they are tomorrow, then the total energy of a closed system is conserved. The system's action does not change if it is shifted forward or backward in time.
Conservation of Linear Momentum	Spatial-translation invariance	If the laws of physics are the same here as they are somewhere else, then the total linear momentum of a closed system is conserved. The action is invariant under a uniform shift in position.
Conservation of Angular Momentum	Rotational invariance	If the laws of physics are the same no matter how you orient your system, then the total angular momentum of a closed system is conserved. The action is invariant under rotation.
Significance and implications
Beyond classical mechanics: While first proven for classical systems, the theorem applies broadly across many fields of physics, including quantum mechanics, special relativity, and quantum field theory. In quantum field theory, it links global continuous symmetries to conserved "currents".
Predictive power: The theorem allows physicists to predict conserved quantities based on the known symmetries of a system, without needing to know the specific details of its dynamics. Conversely, if a system is found to conserve a quantity, it implies the existence of an underlying symmetry.
Structure of physical laws: Instead of being disconnected facts, conservation laws are revealed to be a direct consequence of the symmetries inherent in the fundamental laws of nature. This shifts the focus from studying forces and interactions to understanding the symmetries that govern them. For instance, the theory of general relativity does not possess a time-translation symmetry in curved space-time, which is why energy is not always a globally conserved quantity in that context. 

# Examples of Continuous Symmetries and Action Principles

---

### 1. Time-translation invariance → Conservation of energy  

**Continuous symmetry:**  
The laws of physics are the same today as they will be tomorrow. The Lagrangian of a system does not explicitly depend on time. If you calculate the action for a path today, it will be identical to the action for the same path translated to a different time.  

**Action principle:**  
For a system like a ball in a gravitational field, the Lagrangian is  

$$
L = \tfrac{1}{2} m v^{2} - m g h
$$  

The action is  

$$
S = \int \Big(\tfrac{1}{2} m v^{2} - m g h\Big) \, dt
$$  

If this action is invariant under time shifts  
$$t \;\to\; t + \delta t,$$  
the principle of least action implies that the total energy  

$$
E = \tfrac{1}{2} m v^{2} + m g h
$$  

of the ball is conserved.  

---

### 2. Spatial-translation invariance → Conservation of linear momentum  

**Continuous symmetry:**  
The laws of physics are the same everywhere in space. The Lagrangian of a system does not depend on the absolute position of the system (e.g., \(x, y, z\)) but only on the relative positions and velocities.  

**Action principle:**  
For a system of free particles, the Lagrangian depends on velocities \(\dot{x}\) but not on absolute positions \(x\). The action  

$$
S = \int L(x, \dot{x}, t) \, dt
$$  

is unchanged if you shift the entire system by a constant vector  

$$
\vec{x} \;\to\; \vec{x} + \vec{a}.
$$  

This symmetry, via the action principle, leads to conservation of the total linear momentum.  

---

### 3. Rotational invariance → Conservation of angular momentum  

**Continuous symmetry:**  
The laws of physics are the same regardless of orientation in space. The Lagrangian is invariant under continuous rotations about any axis.  

**Action principle:**  
For a central force problem (e.g., a planet orbiting the sun), the Lagrangian depends only on the distance between the bodies, which is unaffected by a global rotation. The action principle, applied to such a Lagrangian, guarantees conservation of total angular momentum.  

---

### 4. U(1) gauge symmetry → Conservation of electric charge  

**Continuous symmetry:**  
In quantum field theory, the electromagnetic Lagrangian is symmetric under a local U(1) gauge transformation (the transformation can differ at each point in spacetime).  

**Action principle:**  
The electromagnetic action must be invariant under this U(1) transformation. Applying the principle of least action to the corresponding Lagrangian density produces Maxwell’s equations and demonstrates conservation of electric charge.  

---

## The General Idea  

In all these cases, the process linking symmetry to conservation via the action principle follows the same flow:

1. Start with a physical assumption about the universe (e.g., time doesn’t matter, location doesn’t matter).  
2. Translate the assumption into a mathematical symmetry of the Lagrangian and action.  
3. Use the calculus of variations (the mathematical tool for the action principle) to show that this symmetry leads to a specific conserved quantity.  

Lagrangian mechanics (principle of least action, generalized coordinates, Euler–Lagrange equations). Hamiltonian mechanics (phase space, canonical transformations, Poisson brackets).

30 mins: Classical Electromagnetism overview Statistical Mechanics / Thermodynamics (lean version) Laws of thermodynamics (just principles, no Carnot engine details).

30mins review, quiz




Lagrangian mechanics (principle of least action, generalized coordinates, Euler–Lagrange equations).

Hamiltonian mechanics (phase space, canonical transformations, Poisson brackets).

Noether’s theorem (symmetries → conservation laws).

📌 Math needed: Calculus (differentiation, integration, series), ODEs, vector calculus, linear algebra.

2. Classical Electromagnetism (minimal but crucial)

You don’t need circuits, but you do need fields. This is the seed of quantum field theory.

Maxwell’s equations (differential form, vector calculus).

Wave equation & electromagnetic waves (light as EM wave).

Gauge symmetry (vector/scalar potential, gauge transformations).

Energy & momentum in fields (Poynting vector, stress tensor).

📌 Math needed: Vector calculus (divergence, curl, Laplacian), PDEs, Fourier analysis.

3. Classical Wave Theory

This is the bridge to quantum mechanics.

Harmonic oscillator (already in mechanics, but emphasized).

Superposition & Fourier analysis (modes, wave packets).

Normal modes of coupled systems (matrices, eigenvalues).

Continuous systems (string, membrane, wave equation).

4. Statistical Mechanics / Thermodynamics (lean version)

This part feels boring to many, but it’s the language of ensembles, entropy, and quantum many-body physics.

Laws of thermodynamics (just principles, no Carnot engine details).

Microstates & macrostates (statistical ensembles).

Boltzmann distribution & partition function.

Entropy as information measure.

Fluctuations & thermodynamic limit.

📌 Math needed: Probability, combinatorics, logarithms, some calculus of variations.

5. Classical Field Theory (gateway to QFT & GR)

Where mechanics + E&M generalize.

Lagrangian density for fields (Klein–Gordon, Maxwell).

Euler–Lagrange equations for fields.

Energy-momentum tensor.

Lorentz invariance in classical fields.


Lagrangian & Hamiltonian mechanics (very relevant for QM/QFT).

Maxwell’s equations & wave solutions (for EM force in QM/QFT).

thermodynamics/stat mech basics
quantum stat mech overview
