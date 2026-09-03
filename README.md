# ME F216 — Torsion Test: Modulus of Rigidity

## About the Experiment

The torsion test is used to study the behaviour of a material when subjected to a twisting moment (torque). In this experiment, a circular specimen is subjected to gradually increasing torque, and the corresponding angle of twist is measured.

The experiment is used to determine the **modulus of rigidity (G)** of the material and to observe its behaviour from the initial elastic region through plastic deformation and, eventually, failure.

The experiment is based on the torsion relation:

$$
\frac{T}{J}=\frac{\tau}{R}=\frac{G\theta}{L}
$$

where:

- T = applied torque
- J = polar moment of inertia of the specimen cross-section
- $\tau$ = shear stress
- R = outer radius of the specimen
- G = modulus of rigidity
- $\theta$ = angle of twist in radians
- L = gauge length of the specimen

For a solid circular specimen,

$$
J=\frac{\pi d^4}{32}
$$

where d is the specimen diameter.

---

## Modulus of Rigidity

Within the initial elastic or proportional region, the applied torque is approximately proportional to the angle of twist:

$$
T=m\theta
$$

where m is the slope of the torque–twist curve.

Combining this relation with the torsion equation gives:

$$
G=\frac{mL}{J}
$$

Therefore, the modulus of rigidity is obtained from the **slope of the initial linear portion** of the torque–twist curve.

The angle of twist must be expressed in **radians** when calculating G.

---

## Torque–Twist Behaviour

As the torque is increased, the specimen typically passes through different stages of deformation:

1. **Elastic / proportional region**  
   Torque and angle of twist show an approximately linear relationship. The slope of this region is used to determine G.

2. **Yielding and plastic deformation**  
   The relationship becomes nonlinear as the material begins to undergo permanent deformation.

3. **Strain hardening**  
   For materials such as mild steel, the torque may increase again as the material undergoes further plastic deformation.

4. **Failure**  
   With continued twisting, the specimen eventually reaches its failure condition.

The complete torque–twist curve therefore provides information about the deformation behaviour of the material, while the initial linear portion is particularly important for determining the modulus of rigidity.

---

## Using This Analysis Tool

This tool is intended to assist with the analysis of the readings obtained during the torsion test.

Enter:

- Specimen diameter \(d\)
- Gauge length \(L\)
- Torque readings
- Corresponding angles of twist

The tool converts the measured quantities into the units required for the calculation, determines the slope of the selected initial region using linear regression, and calculates the modulus of rigidity \(G\).

It also plots:

- The selected elastic/proportional region with its fitted line
- The complete torque–twist curve
- The experimental readings used in the analysis

The processed readings can also be downloaded for further analysis.

---

## Selecting the Elastic Region

The number of points used for calculating \(G\) should **not be treated as a fixed universal value**.

Start with the initial readings and examine the torque–twist curve. Try a few nearby choices for the number of points used in the regression and check whether:

- the selected points appear physically linear,
- the fitted line represents the initial portion of the curve appropriately,
- the calculated value of \(G\) is reasonable, and
- the result is reasonably consistent when nearby points are included or excluded.

A high \(R^2\) value alone does not establish that a set of readings belongs to the elastic region. Physical interpretation of the torque–twist curve is also necessary.

---

## Units and Conversions

The analysis uses:

$$
1\ \text{kgf·cm}=98.0665\ \text{N·mm}
$$

and

$$
1\ \text{kgf·m}=9806.65\ \text{N·mm}
$$

The angle of twist entered in degrees is converted to radians for calculating the modulus of rigidity.

---

## Objective

The main objectives of the experiment are to:

- Study the behaviour of a circular specimen under torsional loading.
- Measure the angle of twist produced by an applied torque.
- Determine the modulus of rigidity \(G\) from the initial linear torque–twist relationship.
- Plot and interpret the torque–twist curve.
- Observe the transition from elastic deformation to plastic deformation and eventual failure.
