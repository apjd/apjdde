---
layout: post
title: The meaning of the Electric Displacement
description:
summary: The electric displacement $$D$$ describes the strength of the electric field inside a material.
tags: [physics]
---

Consider the simplest capacitor as shown in the figure. Between the two plates a dielectric material (non-conductor) is placed. As the electric field of the capacitor passes through the material, it induces electric dipole moments. The sum of the induced dipole moments per volume is called <em>Polarization</em>:

$$P = \frac{\sum{ex(t)}}{V}$$,

with $$x(t)$$ being the distance between the positive core of the atom and the electron with charge $$e$$ and volume $$V$$.

Now these small dipole moments are microscopic capacitors by themselves and induce an electrical field that has the opposite direction compared to the external electric field. This leads to a decreased electric field inside of the material.

The strength of the field inside the material is described by the <em>electric Displacement</em> $$D$$:

$$D = \epsilon_0 E + P$$

$$D$$ has the unit of charge per area.

Now the polasization by itself depends on the external field:

$$P = \epsilon_0 \chi E$$

$$\chi$$ is material-dependent and describes how "easily" can dipole moments be induced in the material. With this equation we get for the electric displacement:

$$D = E(\epsilon_0 + \epsilon_0 \chi)$$

We define the relative permeability as $$\epsilon = 1 + \chi$$ and finally get for the displacement field:

$$D = \epsilon_0 \epsilon E$$

This equation describes the strength of the electric field inside a material.




![capacitor](/assets/images/capacitor.svg){:height="50%" width="50%"}
