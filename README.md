# Ising-Model
A simple time evolution of an Ising Model. Completed under the supervision of Dr. Carl Michal at UBC

This code was originally written in sections, thus we see that the code are within blocks, with each blocks completeing a section of what we want it to do. 
We are working with a square grid of electrons, with either spin 1 or -1. We worked with mu = 1, but this code can also work with different values of mu, and with different grid sizes. We assume ther are no external fields, which simplifies the hamiltonian into H(\sigma )=-J \sum \sigma _{i}\sigma _{j}. In this code, we also assumed J = 1. 
The edges are delt as periodic boundary conditions. 

in this code, we have defined the function to calculate energy of the system, hamiltonian(), and the function to randomly flip a element of the grid, flip(). These funcitons feeds into the code that did the time evolution, time_evo(). 

In the last 2 sections, we can calculate the average magnetic moment of a list of temperature through curie_temperature(), then plot the average magnetic moment to estimate the curie temperature. 

The last section give us the ability to generate a animation of the time evolution of the grid. 
