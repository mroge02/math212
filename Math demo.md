
# Math TeX demo

This is an ODE:
$${dy \over dx} = x^2y$$
This is an ODE with an equation number `\tag`:
$$y''+2xy=\arctan x \tag{1}$$

Alignment:

$$\begin{aligned}
A &= B \\
 &= C \\
\end{aligned}$$

Piecewise functions:

$$
|x| =
\begin{cases} % percent introduce a comment; rest of line ignored
-x & \text{if } x<0; \\ % note space between "if" and the brace
x & \text{if } x \ge 0. \\ % the last \\ may be omitted
\end{cases}$$

## Phase space
 
 The phase space of an autonomous ODE consists of all the possible values of the data that determines the state of the system at a given time. In other words, it consists of all possible (complete) initial conditions. For the second-order ODE $\ddot\theta = - \sin\theta$, phase space consists of a Cartesian plane of $(\theta, \dot\theta)$ pairs:
```mathematica
StreamPlot[{d\[Theta], -Sin[\[Theta]]}, {\[Theta], -8, 
  8}, {d\[Theta], -5, 5}, AspectRatio -> Automatic]
  ```
 
![
](https://lh3.googleusercontent.com/LwW0EHIP7y3nyNL4tjt-rRPTN5Fk4ppsplgu_kORQzR2njcCDe340jR3H9zKMCzgRhzGOxSf2DOX "Phase space of a pendulum")


> Written with [StackEdit](https://stackedit.io/).
<!--stackedit_data:
eyJoaXN0b3J5IjpbMTg1Nzk0ODQ0Nl19
-->