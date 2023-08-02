---
layout: article
title: The physics of superconductivity
---

*This article was brought to you by [generous Patreon Supporters](https://www.patreon.com/Higgsino).*

Superconductivity; an extremely cool but unexpected
phenomenon used for:

- Levitating objects
- MRI Scanners
- Quantum computers

.. and it might just one day completely revolutionize  how we transport energy.

<img src="intro.png"/>

<img src="atom.gif"/>

In this article I will tell you the Physics behind it and a little bit of the history as well.

**Don't like reading? Watch the video [here](https://www.youtube.com/watch?v=h6FYs_AUCsQ) instead**




## Temperature scales
Superconductivity was discovered in 1911 By Heike Kamerlingh Onnes. At the time, it was just made possible to liquefy Helium which produces extremely cold temperatures.
<img src='discovery.gif'/>

In the image below we have a Celsius scale. At zero, of course, water freezes. At 100 degrees Celsius water boils. At negative 273 degrees Celsius we have the absolute zero, and a little warmer is the liquid helium, but it is still extremely cold. To put things into perspective, liquid nitrogen is plotted as well. It's negative 195 degrees Celsius.
<img src='temperature_scale.gif'>
Let's switch units to Kelvin, by setting absolute zero as the zero point of the scale. This allows for better visualization. To conclude, it was possible to reach temperatures down to 3 Kelvin using liquid helium!
<img src='temperature_scale_kelvin.gif'>
 Now for my American friends, here is the same scale but with Fahrenheit instead just so you can get a feeling of the temperatures. 
<img src='temperature_scale_fahrennheit.gif'>

We can use the new extremely cold temperatures on circuits.

## Basics of conductivity
So here we have a battery and we have a cable connecting it. That will of course induce a flow of electrons, depicted in red.
<img src='basic_circiut.gif'>

If we zoom in on this cable we will see the metallic lattice, with protons depicted in blue and electrons in red again. The electrons are loosely bound to the nucleus such that they will move easily when they feel a potential. 
<img src='basic_circiut_flow_of_electrons.gif'>

Now compare that to an insulator: Their electrons are strongly bound to the nucleus so it won't conduct. Unless we give it enough energy.
<img src='strongly_bound_electron.gif'>

This happens during a thunder storm. You wouldn't say atmospheric air is a conductor but there is just too much energy in the system. So the air will conduct indeed.

## Temperature and resistance
If we got back and take a look at the cable again of course it was a bit of an idealized model because we have temperature in the system. This means that we will have random movements. The random movements will cause particles to collide and lose energy into thermal energy.
<img src='increasing_heat_in_circiut.gif'>
So a higher temperature will cause more energy loss and, in turn, bigger resistance in the cable.

<img src='increase_heat_digram.gif'>

Actually, at the time it was not known what would happen if we decreased the temperature in a circuit

Would the resistance:
- drop to zero, as the temperature reaches zero? 
- reach a constant resistance?
- or maybe even increase as the temperature dropped?

These unknown scenarios are depicted in the graph below.
<img src='decrease_heat_cicout_3_options.gif'>
It wasn't known at the time, but now with the extremely cold liquid helium we can just take our system, take a look at a fraction of the cable, apply extremely cold liquid
helium to it, and measure what happens to the resistance in that area.
<img src='liquid_helium_in_circiut.gif'>

**Are you ready?**

Because for some materials this happened: after being cooled down under some specific temperature, called the critical temperature, denoted "Tc" there is absolutely *no resistance at all*. No one ever saw this result coming. 
<img src='critical_temperture.gif'>

Okay we will get to the physics in a second, I just wan't to point out that we know there is NO resistance at all in the conductor. There could be just an extremely small resistance, but there is none.

We know this because we can create a ring out of superconductive material, let a current run, leave the system for years and come back later to check the intensity of the current.
<img src='cooling_down_many_years.gif'>

This has been done, but there is no measurable loss of the intensity of the current proving zero resistance (at least within the uncertainty of the measurements).

Also I want to point out that superconductivity is not really a rare phenomenon. Here in the periodic table I marked all the superconductive materials. You can see that superconductive materials are actually quite common.
<img src='periodic_system_of_superconductivity.gif'>
## Superconductivity explanation

Okay so now we will get to the why there is no resistance. Let's come back to our conductor and observe just one electron and assume the conductor has been cooled down by liqiud helium, such that the thermal vibrations are negligible
<img src='cooled_of_circiut.gif'>

As the electron is being pulled to the positive side of the battery, it flies in-between atoms of the lattice. These atoms are positively charged because they have lost their electron to the conduction. This means that the electron will cause a slight attraction of the atom, since it's negatively charged and the atoms are positively charged.
<img src='clumping_together_protons_in_lattice.gif'>


If you have positive atoms clump together in a local disturbance, the area is a bit more positive.
<img src='more_protons_in_clumb_is_positive.gif'>

Now, a new electron flying in will be attracted to this local disturbance, because it is slightly more positively charged.
<img src='net_charge_increase.gif'>

You would probably expect, these two negative electrons should repel each other, since like charges repel. But they don't because, in reality, many more atoms in the lattice are a part of this disturbance and the attraction happens over hundred to thousand of atoms.
<img src='net_attraction_on_electron.gif'>

The attraction causes these two electrons to go together and bind in what is called a "cooper pair". But this bond is extremely weak, and even thermal vibrations will break it. That's why we need the liquid helium.
<img src='cooper_pair.gif'>

When two electrons go into a cooper pair, something interesting happens. Electrons are usually what is called a fermion particle. There is another type of particle called the boson for example a photon. I am not going into details about this, but being a fermion like the electron means that no two particles can be in the same state. Depicted below is the energy level of a molecule. The electrons of the molecule, which are fermions, are being forced to be in different energy states in the molecule. But if they were bosons they could all just fall down to the lowest energy state. 
<img src='bosons_vs_fermions.gif'>

If electrons were normally bosons, no chemical reactions would ever occur. All electrons would just clump down to the lowest energy state in the molecule, and wouldn't be interested in undergoing any reaction. So we are in luck that electrons are fermions. But when two electrons go into a cooper pair, they are still fermions, but they act together as a boson. That means all the cooper pairs clump into the lowest energy level and will all be in the same state, because they are boson now, and not fermions anymore.

The cooper pairs, now being bosons in a superconductor, can behave as one big group of particles in the same state. Because the cooper pairs bond over a distance, more cooper pairs become overlapped. This new big overlap becomes entangled and now behaves as a large network of interactions.  This network of interactions will be attracted to a potential in a circuit and therefore it will conduct. The collective behavior of all the electrons in the network and in the solid prevents any further collision with the lattice. If it were about to collide with an atom, the network can just recombine into new cooper pairs. To have resistance the whole network would have to collide with the whole lattice, and that's just too unlikely to happen... So there is none.
<img src='cooper_pairs_movement.gif'>


Another way to think of superconductvity and cooper pairs is the current has to be resistance-less because you can't take any energy from a system that's already in its ground state, which these cooper pair bosons are.

So superconductivity is a strange quantum dance of copper pairs, electrons and vibration in the lattice.
<img src='superconductive_dance.gif'>

## Meissner effect and applications

There is much more to a superconductor than just zero resistance. Let's first take a look at the magnetic properties. If we put a normal magnet here, the magnetic fields are often drawn like this.
<img src='magnetic_field.gif'>

They represent the direction and the strength of the magnetic field. So if we have other magnets, they would certainly be affected by the magnetic field and would align like this:
<img src='magnetcs_aligning_field.gif'>

If we have normal matter like this little cylinder here, and put it next to a magnet, the magnetic field would just pass right through it like nothing happened.

<img src='cylineder_not_agnetic.gif'>


But if we replace the cylinder with a superconducting cylinder, the cylinder would just repel the magnetic field, it will not have any magnetic field inside of it.

<img src='cylinder_supercondcutive.gif'>


This happens because the electrons inside the superconductor create small vertices that repels the magnetic field. Kind of like really  small electron coils. This is called the Miessner effect.

<img src='superconductive_meisner_effect.gif'>
Now we are actually ready to create really fast, levitating, magnetic superconductor trains. Because if we have a magnet up on a superconductor, the superconductor refuses have the magnetic fields inside of it, causing the magnet to levitate.

<img src='meisner_effect_levitating.gif'>
There are two types of superconductors: Type 1 and type 2. Very creative names, I know.. 

But what we talked about until now is all governed by type 1 superconductors.

Sadly, we don't know how a type 2 superconductor works. And that' is really a shame because type 2 superconductors have the same properties as type 1, but it works at higher temperatures and have other properties such as flux pinning.  If we knew more about type 2, we could speed up the search for finding a superconductor that works at normal pressure and temperatures. As supercondcutors can massively speed up transportation, circuits in a computer and also solve the global energy crisis it is the golden goal in the field of superconductivity. Currently, the LK-99 is promising, but the results aren't thoroughly tested yet. 

- - - - - - 

Thanks for reading my article!

If you want to support me you can [sign up for the newsletter](https://mailchi.mp/fdc0fcc5cefe/higgsinophysics), [subscribe](https://www.youtube.com/@Higgsinophysics) to my YouTube channel, [follow](https://medium.com/@higgsino) me on medium or [become my patreon](https://www.patreon.com/Higgsino).

See you.

