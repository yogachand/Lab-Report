Lab-Report
**Objective**

The aim of this laboratory was to model, analyze, and control a nonlinear seesaw system using MATLAB/Simulink. The work focused on deriving mathematical models, designing controllers, implementing observers, and validating results through both simulations and laboratory experiments. The project provided practical insights into the design of digital control systems for unstable and nonlinear dynamics.

**Key Tasks and Results**

Modeling and Linearization: Derived the nonlinear dynamics of the seesaw system using Euler–Lagrange equations. A linear state-space representation was obtained around the equilibrium point for control design.

System Comparison: Compared the behavior of nonlinear and linear models. Linearization proved valid for small deviations but less accurate under larger disturbances.

State-Feedback Control: Designed controllers with pole placement to stabilize the system. Verified improved stability in both linear and nonlinear simulations.

PI Control in Discrete-Time: Added integral action to reduce steady-state error. Implemented discrete-time PI controllers at sampling rates up to 8 kHz, showing effective disturbance rejection and stable performance at higher frequencies.

Observer Design: Designed and implemented a full-state observer to estimate unmeasured states. Demonstrated fast error convergence in both continuous and discrete implementations.

Observer-Based Control: Integrated observer with state-feedback and PI controllers. Demonstrated robust performance under varying initial conditions, disturbances, and parameter uncertainties.

**Conclusion**

This laboratory strengthened my skills in control theory, modeling, MATLAB/Simulink simulation, and digital implementation. It highlighted the importance of sampling rates, observer design, and robustness when controlling nonlinear systems. The experience is directly relevant to advanced robotics research, where flexible and tendon-driven actuators also require careful modeling, robust control, and experimental validation.
