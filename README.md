# Special Relativity with the Hamiltonian

This project is an educational tool that explores the dynamics of a relativistic particle using the Lagrangian and Hamiltonian formulations of classical mechanics. The goal is to derive the relativistic energy and analyze the equations of motion for a particle in special relativity, incorporating concepts like velocity, acceleration, momentum.

The project is implemented in Python using the _SymPy_ library for symbolic mathematics, making it easy to derive and manipulate complex equations.

## Features

- **Lagrangian Formulation**: Derives the relativistic Lagrangian for a particle and computes the equations of motion using the Euler-Lagrange equations.

- **Hamiltonian Formulation**: Converts the Lagrangian into the Hamiltonian framework, providing insights into the energy and momentum of the system.

- **Symbolic Computation**: Uses _SymPy_ to perform symbolic differentiation, substitution, and simplification of equations.

- **Velocity and Acceleration Analysis**: Computes the velocity and acceleration components in 3D space.

- **Momentum and Force Calculations**: Derives the momentum and force components from the Hamiltonian.

## Requirements

To run this project, you need the following:

**Python 3.x**: The code is written in Python.

**SymPy**: A Python library for symbolic mathematics. Install it using pip:

    pip install sympy 

## Usage
Running the Code

1. Clone the repository:

       git clone https://github.com/your-username/special-relativity-hamiltonian.git
       cd special-relativity-hamiltonian

2. Open the Jupyter Notebook:

       jupyter notebook Special_Relativity_w_Hamiltonian.ipynb

3. Run the cells in the notebook to see the derivations and results.


## Key Concepts

### Lagrangian Formulation

The Lagrangian $\mathcal{L}$ for a relativistic particle is given by,

$$\mathcal{L} = -mc\int ds$$

Where:
- $` ds = (cdt)^2 - dx^2 - dy^2 - dz^2`$
- $m$ is the mass of the particle, and
- $c$ is the speed of light.

The Euler-Lagrange equations are used to derive the equations of motion:

$$ \frac{\partial \mathcal{L}}{\partial q}-\frac{d}{dt}\frac{\partial \mathcal{L}}{\partial \dot{q}} = 0 $$

where $q$ represents the generalized coordinates (e.g., $ x(t), y(t), z(t) $.)

### Hamiltonian Formulation

The Hamiltonian H is derived from the Lagrangian using the Legendre transformation:

$$ H = \sum_i p_i \dot{q_i} - \mathcal{L} $$

where $p_i$ are the generalized momenta:

$$ p_i = \frac{\partial \mathcal{L}}{\partial \dot{q}} $$

The Hamiltonian represents the total energy of the system and is used to analyze the dynamics in phase space.

### Velocity and Acceleration

The velocity $v(t)$ and acceleration $a(t)$ are computed in 3D space:

$$ v(t) = (v_x(t), v_y(t), v_z(t)) $$
$$ a(t) = (a_x(t), a_y(t), a_z(t)) $$

### Momentum and Force

The generalized momenta $p(t)$ are derived from the Lagrangian:

$$ p(t) = (p_x(t), p_y(t), p_z(t)) $$

The force components are derived from the Hamiltonian:

$$ F = - \frac{\partial H}{\partial q} $$

## License

This project is licensed under the MIT License. See the LICENSE file for details.

## Acknowledgments

**SymPy**: For providing a powerful symbolic mathematics library.

## Contact

If you have any questions or feedback, feel free to reach out:

Email: miguel.a.estrada26@gmail.com

GitHub: github.com/Fisissist
