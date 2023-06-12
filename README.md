# FractalStreamPlayer
a Max instrument for turning the Logistic Map Equation into Music. For use in other patches


This patch stems from my lifelong obsession with a simple fractal equation, x’=rx(1-x), aka the logistic map or logistic difference equation. Where 0<r<4 and 0<x<1, or each iteration of the equation, the new x value is put back into the equation, and fed out into the shaping curve functions above to generate note pitch, velocity, duration and rhythm. For some values of r, x does really interesting stuff. More math here: https://chaos-equations.com/ldf/ldf.htm. 


This instrument has allowed me to play with lots of different ways of creating the r value: sensors, video feeds, pitch tracking of acoustic instruments, scores, etc. It typically evokes feelings of “balance,” either the desire to achieve it, or the tension of leaving it, or the thrill of bouncing back and forth. 

It's designed for maximal reuse within other patches as projects. You'll want to include it in another patch that provides the r value and the initial x value. It has its own noteout, or it can feed midi and/or raw x values out.

NOTE: somewhere in a Max version change, the layout of this patch's Patching mode got really messed up. I'll fix that soon.
