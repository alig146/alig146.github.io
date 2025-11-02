---
layout: post
title: The Scaling Laws of Particle Accelerators 
date: 2025-11-02 10:00:00
description: A study of the scaling laws of particle accelerators
tags: [physics, research, particle physics, colliders, ML]
categories: physics
featured: false
---

Before the advent of particle accelerators, searches in the subatomic world were mostly based on radioactive sources and cosmic rays. The history of colliders is long, but the first machines to use two accelerator beams in collisions were developed in the 1970s, and these are the types of machines we still use today.

Particle colliders may be relatively expensive compared to other machines used in physics, but in the more general sense of scientific endeavors, the amount of money spent to build colliders is not significant. For example, the LHC cost about $5 billion to build and led to the discovery of the Higgs boson, while in NASA's Artemis program, just one component, the Orion space capsule, has taken tens of billions of dollars to build and will probably never carry astronauts due to safety concerns. This is all to say that even with the large collaboration sizes and bureaucracy, physicists have still magically managed to push through it all and produce truly awesome scientific work.

But why do we need these expensive machines in the first place? The answer is twofold. First, via quantum mechanics, we know that to probe lower scales we need to go to higher energies. For example, if we want to really look into the workings of a nucleus, we can't rely on cosmic rays or radioactive experiments, colliders provide the energies necessary to truly probe smaller scales. Second, most particles of interest do not exist as free particles in nature; they must be created in the lab.

This drive toward higher energies has been remarkably successful. Physicists have built increasingly powerful colliders, leading to the discovery of 13 fundamental particles. The first scaling law was shown by Milton Stanley Livingston in 1954 when he made the now famous Livingston plot, where he showed that the laboratory energy of particle beams produced by accelerators has increased exponentially over time. This trend still applies to today's colliders. This is a great experimental achievement, and the discovery of all these new fundamental particles needed these increases in energy.

Yet energy alone doesn't tell the whole story. Other parameters are similarly important in particle discovery. One of these major parameters is the luminosity of the machine, defined as the interaction rate per second per unit cross section. Quantum mechanics is statistical by nature, so just going to higher energies will not give us a desired particle in every collision; we must collect enough data to make a statistically meaningful statement.

Here's where things get challenging. Luminosity, especially important in proton-proton collisions due to their composite structure, turns out to be a much harder problem than energy. In fact, luminosity has remained roughly constant over the energy range, with only the different iterations of the LHC leading to relatively substantial growth at higher energies. This is probably due to a combination of engineering and data analysis capabilities. This is the second scaling law but with a grain of salt. 

This leads us to our third scaling law: as the energy and luminosity increase, the detector hardware will reach its discrimination power, and the data analysis software will have to carry the rest of the weight to reach the physics goals of the experiment. As the number of possible reactions increases as a function of energy and luminosity, the hardware will just see an extremely dense picture of a collision, and from that alone not much can be said about the data. The data analysis step needs exponential growth to allow for increased analyzing power.

From my view, up to and somewhat through the first LHC run, analysis methods developed from the 1970s were sufficient enough to discover the Higgs at the given energy and luminosities. However, as the dream of finding a new particle at the current collider has toned down, more effort and manpower has gone into improving the software to increase the analysis potential of the existing and future data.

The major advancements which have seen the most improvement in analysis potential, such as sensitivity to various Higgs decay modes and couplings, have come from machine learning tools. And the promising part is that machine learning tools are improving exponentially, which will allow us to gain more from the data we collect, potentially more than previously thought possible.

Now, it will not allow us to claim discovery of a new particle, but it may allow us to get a hint of a potential new particle by probing the end tail of the probability distribution. ML tools will allow us to isolate and analyze more of the interesting data points, but at the end of the day we will still need to go to higher energies to be able to stare at the probability distribution at its peak if there is a new particle. Niobium-tin based superconducting magnets, better beam control, and machine learning tools will be part of the solutions that help the next generation of colliders, like the FCC at the 100 TeV scale, follow the scaling laws of colliders and hopefully the discovery patterns of the past as well.

---