# pendulum-simulation
A simulation of a pendulum with air resistance using non-linear differential equations for a high school senior year physics project.

## Mathmatical Models

Assume that the net force vector is perpendicular to the attached string and that the measurement of theta starts at the state of least potential energy within the given the system.

<img src="https://latex.codecogs.com/gif.latex?\ddot{\theta}=\frac{gsin(\theta)}{L}&plus;\frac{c\dot{\theta}L}{m}&space;\&space;\&space;\&space;\&space;\theta<0\cup\dot{\theta}&space;<0" title="\ddot{\theta}=\frac{gsin(\theta)}{L}+\frac{c\dot{\theta}^2 L}{m} \ \ \ \ \theta<0\cup\dot{\theta} <0" />
<img src="https://latex.codecogs.com/gif.latex?\ddot{\theta}=\frac{gsin(\theta)}{L}-\frac{c\dot{\theta}L}{m}&space;\&space;\&space;\&space;\&space;\theta<0\cup\dot{\theta}>0" title="\ddot{\theta}=\frac{gsin(\theta)}{L}-\frac{c\dot{\theta}^2 L}{m} \ \ \ \ \theta<0\cup\dot{\theta}>0" />
<img src="https://latex.codecogs.com/gif.latex?\ddot{\theta}=-\frac{gsin(\theta)}{L}&plus;\frac{c\dot{\theta}L}{m}&space;\&space;\&space;\&space;\&space;\theta>0\cup\dot{\theta}<0" title="\ddot{\theta}=-\frac{gsin(\theta)}{L}+\frac{c\dot{\theta}^2 L}{m} \ \ \ \ \theta>0\cup\dot{\theta}<0" />
<img src="https://latex.codecogs.com/gif.latex?\ddot{\theta}=-\frac{gsin(\theta)}{L}-\frac{c\dot{\theta}L}{m}&space;\&space;\&space;\&space;\&space;\theta>0\cup\dot{\theta}>0" title="\ddot{\theta}=-\frac{gsin(\theta)}{L}-\frac{c\dot{\theta}^2 L}{m} \ \ \ \ \theta>0\cup\dot{\theta}>0" />
