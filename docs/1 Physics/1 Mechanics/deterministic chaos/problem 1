import numpy as np
import matplotlib.pyplot as plt

def logistic_map(r, x):
    """Logistic map equation - simple nonlinear system showing chaos"""
    return r * x * (1 - x)

def simulate_butterfly_effect():
    """Demonstrate sensitivity to initial conditions"""
    # System parameter
    r = 3.9  # Chaotic regime
    
    # Two very close initial conditions
    x0_a = 0.5
    x0_b = 0.500001  # Difference of 0.000001
    
    iterations = 50
    trajectory_a = [x0_a]
    trajectory_b = [x0_b]
    
    x_a = x0_a
    x_b = x0_b
    
    for i in range(iterations):
        x_a = logistic_map(r, x_a)
        x_b = logistic_map(r, x_b)
        trajectory_a.append(x_a)
        trajectory_b.append(x_b)
    
    return trajectory_a, trajectory_b

# Run simulation
traj_a, traj_b = simulate_butterfly_effect()

# Plot results
plt.figure(figsize=(12, 4))

plt.subplot(1, 2, 1)
plt.plot(traj_a, 'b-', label='x₀ = 0.5', alpha=0.7)
plt.plot(traj_b, 'r--', label='x₀ = 0.500001', alpha=0.7)
plt.title('Butterfly Effect in Logistic Map')
plt.xlabel('Iteration')
plt.ylabel('Population (x)')
plt.legend()
plt.grid(True, alpha=0.3)

plt.subplot(1, 2, 2)
difference = np.abs(np.array(traj_a) - np.array(traj_b))
plt.semilogy(difference, 'g-')
plt.title('Difference Between Trajectories (Log Scale)')
plt.xlabel('Iteration')
plt.ylabel('|Difference|')
plt.grid(True, alpha=0.3)

plt.tight_layout()
plt.show()