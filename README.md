# HOMEWORK_5
For one dimension heat convection equation: ∂T/∂t+u*∂T/∂x=0;

its initial condition is the normal distribution: T0=Aexp(-(x-0.5L).^2/(0.1*L)^2 ) ;

the boundary condition is T(1,t)=T(n-1,t),T(n,t)=T(2,t);

L is the length we simulate;

u=0.1cm/s;

lambda=u*dt/dx, lambda is the courant number, and it must be smaller than 1;

the time step required by the CFD stability condition is bigger than assignment 4.

We compare the FTCS format and CTCS format in the big time step. As the photos show, the CTCS format becomes unstable very quickly and there are many peaks. In the contrast, the FTCS format is stable and the temperature keeps in the 1 in the end.
