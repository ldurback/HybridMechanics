# HybridMechanics

## PDE

<a href="https://www.codecogs.com/eqnedit.php?latex=i&space;\hbar&space;\frac{\partial}{\partial&space;t}&space;\psi&space;=&space;[-\frac{\hbar^2}{2m_Q}&space;\frac{\partial^2}{\partial&space;x_Q^2}&plus;V-i\hbar&space;(\frac{p_C}{m_C}\frac{\partial}{\partial&space;x_C}-\frac{\partial&space;V}{\partial&space;x_C}\frac{\partial}{\partial&space;p_C})]\psi" target="_blank"><img src="https://latex.codecogs.com/gif.latex?i&space;\hbar&space;\frac{\partial}{\partial&space;t}&space;\psi&space;=&space;[-\frac{\hbar^2}{2m_Q}&space;\frac{\partial^2}{\partial&space;x_Q^2}&plus;V-i\hbar&space;(\frac{p_C}{m_C}\frac{\partial}{\partial&space;x_C}-\frac{\partial&space;V}{\partial&space;x_C}\frac{\partial}{\partial&space;p_C})]\psi" title="i \hbar \frac{\partial}{\partial t} \psi = [-\frac{\hbar^2}{2m_Q} \frac{\partial^2}{\partial x_Q^2}+V-i\hbar (\frac{p_C}{m_C}\frac{\partial}{\partial x_C}-\frac{\partial V}{\partial x_C}\frac{\partial}{\partial p_C})]\psi" /></a>

## TDE

<a href="https://www.codecogs.com/eqnedit.php?latex=-i&space;\hbar&space;\frac{d}{dt}\psi=[\frac{1}{2}m_Q&space;\dot{x_Q}^2&space;&plus;&space;p_C&space;\dot{x_C}&space;-&space;\frac{p_C^2}{2m_C}&space;-V(x_Q,&space;x_C,&space;t)]\psi" target="_blank"><img src="https://latex.codecogs.com/gif.latex?-i&space;\hbar&space;\frac{d}{dt}\psi=[\frac{1}{2}m_Q&space;\dot{x_Q}^2&space;&plus;&space;p_C&space;\dot{x_C}&space;-&space;\frac{p_C^2}{2m_C}&space;-V(x_Q,&space;x_C,&space;t)]\psi" title="-i \hbar \frac{d}{dt}\psi=[\frac{1}{2}m_Q \dot{x_Q}^2 + p_C \dot{x_C} - \frac{p_C^2}{2m_C} -V(x_Q, x_C, t)]\psi" /></a>

## Notes:

<a href="https://www.codecogs.com/eqnedit.php?latex=\psi(x_Q&space;;&space;x_C,&space;p_C&space;;&space;t)" target="_blank"><img src="https://latex.codecogs.com/gif.latex?\psi(x_Q&space;;&space;x_C,&space;p_C&space;;&space;t)" title="\psi(x_Q ; x_C, p_C ; t)" /></a> is the hybrid quantum-classical wavefunction.

mQ and xQ are the variables for a 1D quantum system

mC, xC, and pC are the variables for a 1D classical system

V(xQ, xC, t) is the potential

## Proof of Galilean Invariance of PDE and TDE

Proof that these are the unique linear PDE and TDE that are 1st order in time, which describe a Galilean relativistic wave through a space (xQ; xC, pC; t).

#### Galilean Invariance

Consider a Galilean Transformation

x' = x + vt + x_0

t' = t + t_0

p' = p + mv

and its inverse transformation

x = x' - vt' - x_0

t = t' - t_0

p = p' - mv

<a href="https://www.codecogs.com/eqnedit.php?latex=\frac{\partial}{\partial&space;x'}&space;=&space;\frac{\partial&space;t}{\partial&space;x'}&space;\frac{\partial}{\partial&space;t}&space;&plus;\frac{\partial&space;x}{\partial&space;x'}&space;\frac{\partial}{\partial&space;x}&space;&plus;&space;\frac{\partial&space;p}{\partial&space;x'}&space;\frac{\partial}{\partial&space;p}&space;=&space;\frac{\partial}{\partial&space;x}" target="_blank"><img src="https://latex.codecogs.com/gif.latex?\frac{\partial}{\partial&space;x'}&space;=&space;\frac{\partial&space;t}{\partial&space;x'}&space;\frac{\partial}{\partial&space;t}&space;&plus;\frac{\partial&space;x}{\partial&space;x'}&space;\frac{\partial}{\partial&space;x}&space;&plus;&space;\frac{\partial&space;p}{\partial&space;x'}&space;\frac{\partial}{\partial&space;p}&space;=&space;\frac{\partial}{\partial&space;x}" title="\frac{\partial}{\partial x'} = \frac{\partial t}{\partial x'} \frac{\partial}{\partial t} +\frac{\partial x}{\partial x'} \frac{\partial}{\partial x} + \frac{\partial p}{\partial x'} \frac{\partial}{\partial p} = \frac{\partial}{\partial x}" /></a>

<a href="https://www.codecogs.com/eqnedit.php?latex=\frac{\partial}{\partial&space;t'}&space;=&space;\frac{\partial&space;t}{\partial&space;t'}&space;\frac{\partial}{\partial&space;t}&space;&plus;\frac{\partial&space;x}{\partial&space;t'}&space;\frac{\partial}{\partial&space;x}&space;&plus;&space;\frac{\partial&space;p}{\partial&space;t'}&space;\frac{\partial}{\partial&space;p}&space;=&space;\frac{\partial}{\partial&space;t}&space;-&space;v&space;\frac{\partial}{\partial&space;x}" target="_blank"><img src="https://latex.codecogs.com/gif.latex?\frac{\partial}{\partial&space;t'}&space;=&space;\frac{\partial&space;t}{\partial&space;t'}&space;\frac{\partial}{\partial&space;t}&space;&plus;\frac{\partial&space;x}{\partial&space;t'}&space;\frac{\partial}{\partial&space;x}&space;&plus;&space;\frac{\partial&space;p}{\partial&space;t'}&space;\frac{\partial}{\partial&space;p}&space;=&space;\frac{\partial}{\partial&space;t}&space;-&space;v&space;\frac{\partial}{\partial&space;x}" title="\frac{\partial}{\partial t'} = \frac{\partial t}{\partial t'} \frac{\partial}{\partial t} +\frac{\partial x}{\partial t'} \frac{\partial}{\partial x} + \frac{\partial p}{\partial t'} \frac{\partial}{\partial p} = \frac{\partial}{\partial t} - v \frac{\partial}{\partial x}" /></a>

<a href="https://www.codecogs.com/eqnedit.php?latex=\frac{\partial}{\partial&space;p'}&space;=&space;\frac{\partial&space;t}{\partial&space;p'}&space;\frac{\partial}{\partial&space;t}&space;&plus;\frac{\partial&space;x}{\partial&space;p'}&space;\frac{\partial}{\partial&space;x}&space;&plus;&space;\frac{\partial&space;p}{\partial&space;p'}&space;\frac{\partial}{\partial&space;p}&space;=&space;\frac{\partial}{\partial&space;p}" target="_blank"><img src="https://latex.codecogs.com/gif.latex?\frac{\partial}{\partial&space;p'}&space;=&space;\frac{\partial&space;t}{\partial&space;p'}&space;\frac{\partial}{\partial&space;t}&space;&plus;\frac{\partial&space;x}{\partial&space;p'}&space;\frac{\partial}{\partial&space;x}&space;&plus;&space;\frac{\partial&space;p}{\partial&space;p'}&space;\frac{\partial}{\partial&space;p}&space;=&space;\frac{\partial}{\partial&space;p}" title="\frac{\partial}{\partial p'} = \frac{\partial t}{\partial p'} \frac{\partial}{\partial t} +\frac{\partial x}{\partial p'} \frac{\partial}{\partial x} + \frac{\partial p}{\partial p'} \frac{\partial}{\partial p} = \frac{\partial}{\partial p}" /></a>

dx' = dx + vdt

dt' = dt

dx'/dt' = dx/dt + v

Assume the potential transforms with the Galilean transformation

V'(x',t') = V(x,t)

### Galilean Covariance of PDE

Start with the PDE

<a href="https://www.codecogs.com/eqnedit.php?latex=i&space;\hbar&space;\frac{\partial}{\partial&space;t}&space;\psi&space;=&space;[-\frac{\hbar^2}{2m_Q}&space;\frac{\partial^2}{\partial&space;x_Q^2}&plus;V-i\hbar&space;(\frac{p_C}{m_C}\frac{\partial}{\partial&space;x_C}-\frac{\partial&space;V}{\partial&space;x_C}\frac{\partial}{\partial&space;p_C})]\psi" target="_blank"><img src="https://latex.codecogs.com/gif.latex?i&space;\hbar&space;\frac{\partial}{\partial&space;t}&space;\psi&space;=&space;[-\frac{\hbar^2}{2m_Q}&space;\frac{\partial^2}{\partial&space;x_Q^2}&plus;V-i\hbar&space;(\frac{p_C}{m_C}\frac{\partial}{\partial&space;x_C}-\frac{\partial&space;V}{\partial&space;x_C}\frac{\partial}{\partial&space;p_C})]\psi" title="i \hbar \frac{\partial}{\partial t} \psi = [-\frac{\hbar^2}{2m_Q} \frac{\partial^2}{\partial x_Q^2}+V-i\hbar (\frac{p_C}{m_C}\frac{\partial}{\partial x_C}-\frac{\partial V}{\partial x_C}\frac{\partial}{\partial p_C})]\psi" /></a>

Substitute in the equations for the Galilean transformation

<a href="https://www.codecogs.com/eqnedit.php?latex=\inline&space;i&space;\hbar&space;(\frac{\partial}{\partial&space;t'}&plus;v\frac{\partial}{\partial&space;x'_Q}&plus;v\frac{\partial}{\partial&space;x'_C})&space;\psi&space;=&space;[-\frac{\hbar^2}{2m_Q}&space;(\frac{\partial}{\partial&space;x'_Q})^2&plus;V-i\hbar&space;(\frac{p'_C-m_C&space;v}{m_C}\frac{\partial}{\partial&space;x'_C}-\frac{\partial&space;V}{\partial&space;x'_C}\frac{\partial}{\partial&space;p'_C})]\psi" target="_blank"><img src="https://latex.codecogs.com/gif.latex?\inline&space;i&space;\hbar&space;(\frac{\partial}{\partial&space;t'}&plus;v\frac{\partial}{\partial&space;x'_Q}&plus;v\frac{\partial}{\partial&space;x'_C})&space;\psi&space;=&space;[-\frac{\hbar^2}{2m_Q}&space;(\frac{\partial}{\partial&space;x'_Q})^2&plus;V-i\hbar&space;(\frac{p'_C-m_C&space;v}{m_C}\frac{\partial}{\partial&space;x'_C}-\frac{\partial&space;V}{\partial&space;x'_C}\frac{\partial}{\partial&space;p'_C})]\psi" title="i \hbar (\frac{\partial}{\partial t'}+v\frac{\partial}{\partial x'_Q}+v\frac{\partial}{\partial x'_C}) \psi = [-\frac{\hbar^2}{2m_Q} (\frac{\partial}{\partial x'_Q})^2+V-i\hbar (\frac{p'_C-m_C v}{m_C}\frac{\partial}{\partial x'_C}-\frac{\partial V}{\partial x'_C}\frac{\partial}{\partial p'_C})]\psi" /></a>

Simplify

<a href="https://www.codecogs.com/eqnedit.php?latex=\inline&space;i&space;\hbar&space;(\frac{\partial}{\partial&space;t'}&plus;v\frac{\partial}{\partial&space;x'_Q})&space;\psi&space;=&space;[-\frac{\hbar^2}{2m_Q}&space;(\frac{\partial}{\partial&space;x'_Q})^2&plus;V-i\hbar&space;(\frac{p'_C}{m_C}\frac{\partial}{\partial&space;x'_C}-\frac{\partial&space;V}{\partial&space;x'_C}\frac{\partial}{\partial&space;p'_C})]\psi" target="_blank"><img src="https://latex.codecogs.com/gif.latex?\inline&space;i&space;\hbar&space;(\frac{\partial}{\partial&space;t'}&plus;v\frac{\partial}{\partial&space;x'_Q})&space;\psi&space;=&space;[-\frac{\hbar^2}{2m_Q}&space;(\frac{\partial}{\partial&space;x'_Q})^2&plus;V-i\hbar&space;(\frac{p'_C}{m_C}\frac{\partial}{\partial&space;x'_C}-\frac{\partial&space;V}{\partial&space;x'_C}\frac{\partial}{\partial&space;p'_C})]\psi" title="i \hbar (\frac{\partial}{\partial t'}+v\frac{\partial}{\partial x'_Q}) \psi = [-\frac{\hbar^2}{2m_Q} (\frac{\partial}{\partial x'_Q})^2+V-i\hbar (\frac{p'_C}{m_C}\frac{\partial}{\partial x'_C}-\frac{\partial V}{\partial x'_C}\frac{\partial}{\partial p'_C})]\psi" /></a>

Make the definition

<a href="https://www.codecogs.com/eqnedit.php?latex=\inline&space;\psi(x_Q&space;,&space;x_C,&space;p_C,&space;t)&space;=&space;e^{\frac{1}{i\hbar}(\frac{1}{2}mv^2t'&plus;mvx'_C&plus;mvx'_Q)}&space;\psi'(x'_Q,&space;x'_C,&space;p'_C,&space;t')" target="_blank"><img src="https://latex.codecogs.com/gif.latex?\inline&space;\psi(x_Q&space;,&space;x_C,&space;p_C,&space;t)&space;=&space;e^{\frac{1}{i\hbar}(\frac{1}{2}mv^2t'&plus;mvx'_C&plus;mvx'_Q)}&space;\psi'(x'_Q,&space;x'_C,&space;p'_C,&space;t')" title="\psi(x_Q , x_C, p_C, t) = e^{\frac{1}{i\hbar}(\frac{1}{2}mv^2t'+mvx'_C+mvx'_Q)} \psi'(x'_Q, x'_C, p'_C, t')" /></a>

And substitute

<a href="https://www.codecogs.com/eqnedit.php?latex=\inline&space;i&space;\hbar&space;(\frac{\partial}{\partial&space;t'}&plus;v\frac{\partial}{\partial&space;x'_Q})&space;e^{\frac{1}{i\hbar}(\frac{1}{2}mv^2t'&plus;mvx'_C&plus;mvx'_Q)}&space;\psi'" target="_blank"><img src="https://latex.codecogs.com/gif.latex?\inline&space;i&space;\hbar&space;(\frac{\partial}{\partial&space;t'}&plus;v\frac{\partial}{\partial&space;x'_Q})&space;e^{\frac{1}{i\hbar}(\frac{1}{2}mv^2t'&plus;mvx'_C&plus;mvx'_Q)}&space;\psi'" title="i \hbar (\frac{\partial}{\partial t'}+v\frac{\partial}{\partial x'_Q}) e^{\frac{1}{i\hbar}(\frac{1}{2}mv^2t'+mvx'_C+mvx'_Q)} \psi'" /></a> <a href="https://www.codecogs.com/eqnedit.php?latex=\inline&space;=&space;[-\frac{\hbar^2}{2m_Q}&space;(\frac{\partial}{\partial&space;x'_Q})^2&plus;V-i\hbar&space;(\frac{p'_C}{m_C}\frac{\partial}{\partial&space;x'_C}-\frac{\partial&space;V}{\partial&space;x'_C}\frac{\partial}{\partial&space;p'_C})]e^{\frac{1}{i\hbar}(\frac{1}{2}mv^2t'&plus;mvx'_C&plus;mvx'_Q)}&space;\psi'" target="_blank"><img src="https://latex.codecogs.com/gif.latex?\inline&space;=&space;[-\frac{\hbar^2}{2m_Q}&space;(\frac{\partial}{\partial&space;x'_Q})^2&plus;V-i\hbar&space;(\frac{p'_C}{m_C}\frac{\partial}{\partial&space;x'_C}-\frac{\partial&space;V}{\partial&space;x'_C}\frac{\partial}{\partial&space;p'_C})]e^{\frac{1}{i\hbar}(\frac{1}{2}mv^2t'&plus;mvx'_C&plus;mvx'_Q)}&space;\psi'" title="= [-\frac{\hbar^2}{2m_Q} (\frac{\partial}{\partial x'_Q})^2+V-i\hbar (\frac{p'_C}{m_C}\frac{\partial}{\partial x'_C}-\frac{\partial V}{\partial x'_C}\frac{\partial}{\partial p'_C})]e^{\frac{1}{i\hbar}(\frac{1}{2}mv^2t'+mvx'_C+mvx'_Q)} \psi'" /></a>

### Galilean Covariance of TDE

### The equations have the same solutions

### Uniqueness of the PDE and TDE
