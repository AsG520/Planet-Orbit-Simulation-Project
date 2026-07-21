# Planet-Orbit-Simulation-Project

Visual of Simulation

Features in Simulation
- Real time animation using a timer.
- 2D representation of planet orbits in our solar system.
- Motion of planets are broken into horizontal and vertical components.
- Implementation of attraction force between different planets.
- Includes estimated real masses of planets.

Physics & Math Concepts in Simulation
- Newton's Law of Universal Gravitation (Fg) = G * m1 * m2 / r_2
- Trigonometric Functions (Sine, Cosine, & Tangent).

How it Works
- Planet class defines other planets orbiting around the sun.
- Paint method draws the plants onto the frame with their specific positions and colors.
- Velocity of planets are updated from Newton's Law of Universal Gravitation, which then is updating the position variable for each planet.
- Programs initializes variables for each planet and window screen.
- Has animation with the user of Java Timer.
- Sets a PlanetOrbitSimulation panel, which is extended in the JPanel from the public class.

Requirements
- Java (JDK or higher).
- IDE (e.g., VS Code, Eclipse, or IntelliJ).

How to Run
- Copy the code into a Java file named "PlanetOrbitSimulation.java".
- Compile the program: "javac PlanetOrbitSimulation.java".
- Run the program: "java PlanetOrbitSimulation".
