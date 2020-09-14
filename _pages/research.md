---
layout: archive
title: "Research"
permalink: /research/
author_profile: true

---

{% include base_path %}

Young massive clusters (YMCs, sometimes known as [super star clusters](https://en.wikipedia.org/wiki/Super_star_cluster)) are recently formed astronomical objects in galaxies. They are commonly thought as the building blocks of galaxies and the small but excellent star-making factories, yet how they are born is still not fully understood. Being young and massive, YMCs lie somewhere in between [globular clusters](https://en.wikipedia.org/wiki/Globular_cluster) and [open clusters](https://en.wikipedia.org/wiki/Open_cluster) in the mass-age spectrum. A YMC is typically 10,000 times more massive than the Sun and 10,000 times denser than the outer space. It has age less than 100 million years, very young with respect to the age of the universe. A relatively well known YMC in our galaxy is [Westerlund 1](https://en.wikipedia.org/wiki/Westerlund_1) as shown below (image credit: ESO).

<img src="/images/westerlund1.jpg" alt="ESO Westerlund 1" width="500">

There are a few ways YMCs can be formed, both in theory and in observation, but one that I'm interested in is their formation through collisions of [giant molecular clouds](https://en.wikipedia.org/wiki/Molecular_cloud#Giant_molecular_clouds). These clouds can be hundreds of light-years in size and as massive as 1,000,000 solar masses, so there's plenty of gas available for star formation when the clouds interact. The cloud-cloud collision model can explain why there are more YMCs observed in interacting galaxies like [Antennae](https://en.wikipedia.org/wiki/Antennae_Galaxies) as compared to the quiescent Milky Way, since cloud-cloud collisions are more frequent in the highly dynamic environment.

In my research, I use [PHANTOM](https://phantomsph.bitbucket.io/), a [smoothed particle hydrodynamics](https://en.wikipedia.org/wiki/Smoothed-particle_hydrodynamics) code for astrophysics to perform my cloud-cloud collision simulations. Together with my supervisor [Prof Clare Dobbs](http://emps.exeter.ac.uk/physics-astronomy/staff/cld214), we investigate the initial conditions, notably the collision speed, the level of turbulence, and the initial density of the clouds needed to form massive clusters. One of my analysis involves using clustering algorithm like [DBSCAN](https://en.wikipedia.org/wiki/DBSCAN) to quantify the clusters formed in the simulations. Recently, I work with [Dr Steven Rieder](http://emps.exeter.ac.uk/physics-astronomy/staff/sr621) to use [AMUSE](https://amusecode.github.io/) to recreate some of my previous PHANTOM simulations, in hope of creating clusters that better resemble real massive stellar clusters.

![Nice Simulation Pic](/images/pic_for_front.png)

An 18,000 solar mass cluster formed through the collision of two giant molecular clouds at about 20 km/s relative to each other. The simulation was done using PHANTOM (Price et al. 2018) and visualised using [SPLASH](http://users.monash.edu.au/~dprice/splash/index.html) (Price 2007).
