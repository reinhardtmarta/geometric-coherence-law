# ​Harmony-Driven Quantum Control
Unifying Active Stabilization with Indefinite Coherence
​This repository introduces the Geometric Coherence Law—a novel principle for actively stabilizing quantum error correction (QEC) by managing correlated noise. We demonstrate that maximum stability is achieved not at minimum or maximum correlation, but at a specific Geometric Harmony Factor (\mathbf{\approx 0.695}), which minimizes the variance of QEC overhead.
​We prove that this active stabilization mechanism is the essential complement to passive protection protocols, showing how the Geometric Coherence Law maximizes the fidelity and longevity of the Multi-Commuting Subspace Projection (\text{MQIM}) method for Indefinite Coherence. This work is critical for achieving reliable, fault-tolerant quantum computing (FTQC).

## Key Finding: The Geometric Harmony Factor (\approx 0.695)

Statistical simulations demonstrate that the effective overhead of the QEC code, while largely stable in mean, exhibits extreme sensitivity to noise correlation variance (\text{std}), leading to periods of both high instability (Chaos) and maximum stability (Harmony).
​Maximum Stability (Harmonia): \mathbf{\text{CZ Factor} \approx 0.695}. This point minimizes the Standard Deviation of Overhead (\text{std}_{\text{overhead}}), representing the system's optimal operating point for predictability and resilience.
​Maximum Instability (Caos): The system exhibits catastrophic resonance near \mathbf{0.71} correlation, highlighting the critical need for precise calibration.

## The core demonstration is contained in the Jupyter Notebook:
Coherence_Stability_Test.ipynb: Contains the Monte Carlo simulation code, which incorporates the Cosmic Field Correlated Noise Model (derived from \phi Protocol-like geometric leakage) to calculate the mean and standard deviation of QEC overhead across varying CZ-gate correlation factors.
Instructions: Click the Google Colab badge to run the notebook and instantly reproduce the Geometric Harmony Factor plot.

​Critically, we demonstrate the synergy between this active stabilization mechanism and the passive protection afforded by the Multiple Commuting-Subspace Projection (\text{MQIM}) protocol. By feeding the \text{MQIM} protocol with CZ-gates calibrated at \mathbf{0.695}, we show a necessary precondition for maximizing \text{MQIM}'s fidelity and achieving its goal of Indefinite Coherence. The Geometric Coherence Law provides the required calibration for robust, scalable FTQC architecture.
