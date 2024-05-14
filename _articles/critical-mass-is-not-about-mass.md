---
layout: article
title: Why the critical mass is not about mass
---

## Into
The concept of the critical mass in nuclear physics, is to determine whether you have a stable configuration or an exponentially increasing power source. 

Some scientist were hard at work in order to release the exponential power in the trinity test - the first atomic device, while others were hard at work in the Chernobyl accident to try and stop exponential power. 

But today I will explore why the critical mass causes is a very vague concept, and it is no really about the mass. I am going to visualize this with the help of simulations that captures real physics. You will be able to understand core principles in nuclear power plants, and atomic devices.

*Please note; I am not here to talk about the ethics or politics regarding nuclear devices and atomic power plants waste products. I am a physicist and I want to educate the curious mind. Furthermore, I also believe, tackling these issues begins with understanding of the engineering and natural science.*


Prefer to watch? This article is available in a video format here (click the link on the image): 
[![IMAGE ALT TEXT](http://img.youtube.com/vi/ojkeBfOckIk/0.jpg)](http://www.youtube.com/watch?v=ojkeBfOckIk "Critical Mass Misconception | Atomic Bombs and Nuclear Reactors Simulated")


## Nuclear fission and critical mass
First, what is the "critical mass" and why does the concept only kinda make sense? 

Let's understand induced fission, learning with uranium-235 as a concrete example to understand.

<p align="center"><img src="/img/loading.gif" alt="" data-echo="1_nukemap_hydrogen_reveal_elelment.gif"></p>

We can see it has 92 protons and 143 protons. The sum is 235 nuclei in total. 

Uranium-235 has the special property it can undergo indeed fission. When this fissionable material, is hit by a free neutron, the uranium unstable and will split into two smaller daughter nuclei, Krypton and Barium and also 3 new secondary free neutrons. While releasing a great amount of energy in the process.

<p align="center"><img src="/img/loading.gif" alt="" data-echo="1_uranium_fission2.gif"></p>


These 3 new free neutrons can strike other uranium-235 nuclei, multiplying exponentially creating a nuclear chain reaction and releasing an insane amount of energy. One neutron becomes tree neutrons, becomes nine neutrons becomes 27... after 51 generations we will have 2 million * billion * billion neutrons-uranium interactions or one kg of uranium will have been split. Enough to wipe out a big city.  
 
<p align="center"><img src="/img/loading.gif" alt="" data-echo="duplicator_line.gif"></p>


However, it is also possible for the secondary neutrons released to just escape the uranium material without hitting any new nuclei. 

<p align="center"><img src="/img/loading.gif" alt="" data-echo="1_uranium_fission2_no_fission_no_intro.gif"></p>

This chance of escaping depends on how much material we have - if we have too little mass, the neutrons released in the material boundary will have a high probability of escaping, we will therefore need a minimum amount of mass to get the chain reaction started, this is the concept of the critical mass.

<p align="center"><img src="/img/loading.gif" alt="" data-echo="ball.png"></p>

But we can do a lot of things to influence how much mass we need, We will explore this topic later in the article. 


## Building the Simulation and Understanding Criticality

To better illustrate what is going on, I will switch old representation out, instead of showing fission like this:

<p align="center"><img src="/img/loading.gif" alt="" data-echo="1_uranium_fission2.gif"></p>

I will again show the neutron as black, but now the enriched uranium nucleon is just dark blue. Upon induced fission, I will change the color to light blue.  

<p align="center"><img src="/img/loading.gif" alt="" data-echo="2_show_new_syntax.gif"></p>

Of course my animation should show 2 new daughter nucleons fission product flying away after releasing 3 neutrons, but it is not important for the physics point I am trying to make. Just think of it as has potential to fission, or not. 

In the simulation, undergoing fission will release 3 neutrons in a random direction as in reality as well. 

Now, with this new setup we can try an experiment. Let's surround a neutron with lots of Enriched uranium and see what happens.

<p align="center"><img src="/img/loading.gif" alt="" data-echo="2_exponential_test_controlled_count2.gif"></p>

You just saw a single neutron using induced fission to multiply into 1708 neutrons. Instead of the term "critical mass" we can use so-called Multiplication Factor, to tells us about the criticality state of the system. Denoted as k.
It is defined as:

<p align="center"><img src="/img/loading.gif" alt="" data-echo="k1.png"></p>

If k = 1, it means for neutron produced will only produce one new neutron on average. This is the ideal scenario for a nuclear power plant. We have constant power. We call this critical.



<p align="center"><img src="/img/loading.gif" alt="" data-echo="test.gif"></p>


If k under 1, it means each neutron produced does not produce a new one on average, and the reaction is dying out. Subcritical

<p align="center"><img src="/img/loading.gif" alt="" data-echo="test2.gif"></p>

if k is over 1 it means each neutron produced generates even more. This is called supercritical, and we want to maximize that number in an atomic bomb. We saw k over 1 in this example before (where a single neutron multiplied into 1708 neutrons): 

<p align="center"><img src="/img/loading.gif" alt="" data-echo="2_exponential_test_controlled_count2.gif"></p>

To summarize, this is the different scenarios of fission, depending on the k value:
<p align="center"><img src="/img/loading.gif" alt="" data-echo="k2.png"></p>

I can count the number of neutrons from the example we just saw(where a single neutron multiplied into 1708 neutrons), and then plot this Multiplication Factor k for chain reaction experiment we just saw.

<p align="center"><img src="/img/loading.gif" alt="" data-echo="2_graph_k.gif"></p>

You can see it is super critical in the start, the situation is never stable at k equals 1, and quickly reaches subcritical and the process stops. Let's see what influences this criticality factor, more than just the mass.

## Factors of criticality

### Purity
To get a critical assembly, one obvious thing we can change is the purity. So far in the simulation, we have assumed 100% pure uranium 235. This would be weapons-grade uranium. 

<p align="center"><img src="/img/loading.gif" alt="" data-echo="purityW.gif"></p>

But when you extract uranium, only 1about 1% will be the isotope U235 and the rest is a non-fissile uranium isotope.

<p align="center"><img src="/img/loading.gif" alt="" data-echo="purityN.gif"></p>

You must refine and enrich the material with expensive centrifuges before you can feasibly use it in a fission process.

The presence of impurities, such as non-fissile isotopes, can absorb neutrons or simply decrease the chance of a neutron hitting a fissile nucleus. Both examples will hinder the chain reaction. Here you can see a failed attempt of a chain reaction, duo to low purity:

<p align="center"><img src="/img/loading.gif" alt="" data-echo="3_control_rods_stabile_test_too_low_purity.gif"></p>

Historical remark: early discussion about a nuclear bomb was deemed unfeasible, as you would need 44 tons of natural uranium to sustain a critical chain reaction. It was first later when the highly fissile Uranium 235 was used in calculations that got scientist extremely worried about the possibilities of a new super weapon.  

Anyway, for a power plant, low enriched uranium is used, and only about 5% enrichment is needed for a power plant. 

<p align="center"><img src="/img/loading.gif" alt="" data-echo="purityL.gif"></p>

The aim is of course to keep the criticality stable at around k = 1. Let's try that in the simulation. 

First I'll introduce two new features in the simulation, just for the purpose of simulating a nuclear power plant. First we have control rods, depicted as black rectangles.

<p align="center"><img src="/img/loading.gif" alt="" data-echo="3_control_rods_introRods.gif"></p>


Control rods are made of elements with high neutron capture property, that does not decay themselves. Boron is a has this property. These rods can quickly stop an out of control process:


<p align="center"><img src="/img/loading.gif" alt="" data-echo="3_control_rods_stabile_put_out.gif"></p>

Secondly, lets introduced the feature to magically enrich used-up uranium. 

<p align="center"><img src="/img/loading.gif" alt="" data-echo="3_control_rods_intro_enrich.gif"></p>

Let's use these concept to run a nuclear reactor and keep it enriched to around 5% purity. I'll also use control rods to limit the amount of neutrons to 40. This file is a bit big, so I have to link you to a YouTube video(click the link on the image):

[![IMAGE ALT TEXT](http://img.youtube.com/vi/QAdPTdouPDU/0.jpg)](http://www.youtube.com/watch?v=QAdPTdouPDU "Control Rods Nuclear Reactor Simulation")


It is actually very hard to keep the neutron-density approximately constant. Because as soon as we are tipping to either sub critical or super critical we have an exponential increasing or decreasing situation respectively. I have to use two methods that some nuclear power-plants also use to keep the neutrons in check, that is first reactor grade low-enriched uranium and secondly control rods.

### Shape 

Another thing we can do to influence the criticality, is the shape of the fissile mass we have. Depending on the geometry, the criticality is highly effected. For example, a thin cylinder or in 2d a simple line is a terrible configuration for a chain reaction. The high surface area and low volume causes too many neutrons escapes the material. 

<p align="center"><img src="/img/loading.gif" alt="" data-echo="3_shape_thin_rod.gif"></p>

Power plants fuel rods are shaped as a long thin cylinder, but the high surface area and low volume is used for easily getting water in and distribute the heat to the turbine, than for maintaining criticality k=1. 

But atomic devices use normally uses a sphere. A sphere is the optimal way to pack fissile material for super criticality because it has the lowest Surface-area-to-volume ratio.

Shape is what the atomic devices "little boy" used as the trigger mechanism. Before firing the shape engineered set such that, the two clumps are sub critical, and every loose neutron in the material would quickly decay not causing a premature detonation. But after triggering firing two clumps of uranium together, the systems shape will be in a supercritical state, and loose neutron will set off an atomic blast. 

<p align="center"><img src="/img/loading.gif" alt="" data-echo="3_shape_little_boy.gif"></p>


### Density 

I can arrange these nuclei more neatly packed, such as in the hexagonal structure. It is the optimal way to pack circles as tightly as possible. Of course this is just me playing around showing you the affect of density pretending Uranium nuclei are circles. This has nothing to do with real uranium as they would form in some metallic lattice structure. Anyway let's try the simulation again with the hexagonal structure.

<p align="center"><img src="/img/loading.gif" alt="" data-echo="2_exponential_test_hexi_count.gif"></p>

If I plot the k factor over time again, you can see we had a much, much more violently supercritical state. This is exactly the principle of implosion bombs such as the device used in the Trinity device shown in the Oppenheimer movie. The device has the fissile core surrounded by TNT-like explosives, to decrease the density of the fissile core. Before the explosion, the fissile core is subcritical. But after the explosion the core is imploded and the high density means stray neutrons will release a super critical chain reaction.

<p align="center"><img src="/img/loading.gif" alt="" data-echo="3_density_implosion.gif"></p>

This is especially a smart move in an atomic bomb, since the nuclear reaction scattering fission fragments increases the pressure destroying the core and decreasing the density.

I can simulate that, if I add this scattering property. Now uranium-on-uranium collisions will transfer momentum and the same will a neutron-uranium collision. Let's run a chain reaction again with this property.

<p align="center"><img src="/img/loading.gif" alt="" data-echo="4_scattering_property.gif"></p>

You can see the fissile clump disintegrates.  In the animation some uranium nuclei wasn't hit by a neutron and we had wasted potential. If too much fissile material goes to waste you will have a much, much lower yield and maybe just a small meltdown instead of a nuclear explosion. This failed explosion is called a fizzle. 

<p align="center"><img src="/img/loading.gif" alt="" data-echo="4_force_outwards_test.gif"></p>

You can see, if I use explosions like the fat man and trinity device, I can crush the core via implosion and create a low density and an inwards force, combatting the nuclear scattering pressure. This increases the fissile yield and combats the fizzle issue.

<p align="center"><img src="/img/loading.gif" alt="" data-echo="3_density_implosion_neutron.gif"></p>

### Bonus tricks effecting the criticality

There are other tricks used in an atomic device to bring down the minimum required mass and enhance the criticality. The first thing is to use a neutron initiator: that is a reaction of polonium and beryllium that have the property to burst out a lot of neutrons. 

<p align="center"><img src="/img/loading.gif" alt="" data-echo="5_1_bonus_neutron_initati.gif"></p>

Secondly, we can use a strong shell around the fissile material called a tamper, this tamper tries to withhold the outgoing force, just for a tiny, tiny timescale to allow even more neutrons to fission before the material destroys itself.  I will depict the tamper as a black circle and allow a few hits before it is destroyed. 

<p align="center"><img src="/img/loading.gif" alt="" data-echo="5_2_bonus_tamper_show.gif"></p>

Let's try running a fission experiment again with this tamper. You will see this time we managed to fission all the fissile material.

<p align="center"><img src="/img/loading.gif" alt="" data-echo="5_2_bonus_tamper.gif"></p>

Finally, we can add a neutron reflector, this simply brings neutron back into play again by, by letting neutrons bounce on material such as graphite. Thereby not allowing them to escape. This will be smart to use in an atomic device, but hopefully nobody would ever put graphite on the tip of control rods.

I will hit this neutron reflector depicted as yellow. It will be destroyed together with the tamper. 

<p align="center"><img src="/img/loading.gif" alt="" data-echo="5_3_bonus_neutron_reflector.gif"></p>

Putting all tricks we learned together, we get the gadget used in the trinity test: the first atomic bomb. Same principles still used today in modern bombs.

<p align="center"><img src="/img/loading.gif" alt="" data-echo="5_4_all_together_bomb.gif"></p>

## Conclusion
I tried my best to keep the simulation clear without too many distractions. But for clarity I did not talk about:
- cross-section absorption (temperature), the concept of fast and slow neutrons with moderation.
- Secondary neutrons, secondary fission products influencing
- decay branches.


But now you know that the term "critical mass" can be a bit misleading. I've demonstrated that nuclear reactions are not solely governed by mass but are influenced by a range of factors that determines the behavior of fissile materials. 


## More 
If you liked the content, you might also like my simulation and physics explanation of lasers. Read it here:
[https://higgsino.io/articles/laser](https://higgsino.io/articles/laser)

Consider supporting me with a cup of coffee: 
[https://ko-fi.com/higgsino](https://ko-fi.com/higgsino)

Become a Patreon, support whatever you like pr creation I make:
[https://www.patreon.com/Higgsino](https://www.patreon.com/Higgsino)

Subscribe:
[https://www.youtube.com/@Higgsinophysics](https://www.youtube.com/@Higgsinophysics)