# Astro 513 Final Project

This is the repository with everything from my Astro513 repository

These are some things you will find

## 1. An Athena++ Set-Up guide

This is something I put together while arduously setting up the code on my local Steward machine. The upside is that hopefully no one else will have to go through the same pain.

## 2. Code

This folder is complete with all the code I developed for Athena++ and for this project (this was often the same thing). 

### 2.1. InitialConditions.ipynb
This jupyter notebook contains each of the three accretion disk derivations from the ground up. This was the core of my project. 
---->>> The notebook can be self-consistently run, so you can just hit run all and it should produce some nice plots comparing the three solutions

### 2.2 gr_torus.cpp

This is what Athena++ call a 'problem generator'. It definitely was one for me personally.
Here, I modify the existing torus solution to also implement a Power-Law accretion disk according to Penna et al. 2013 and that can easily also be adapted to Chakrabarti 1985. Integrating this with Athena++ was the really hard part - there are a lot of moving parts in that code.

### 2.3 athena_analysis.ipynb
This is the code I wrote to read in and analyze the results of the simulations. The least taxing part of this project.

## 3. Presentation
The presentation I gave to the class

## 4. ReligiousBlackHoles.pdf
The final paper
