### 📦 eivpy: Errors-In-Variables Modeling for Python

eivpy is a lightweight Python library for fitting errors-in-variables (EIV) models and applying regression calibration techniques.
It provides statistically sound tools for linear regression when measurement error exists in explanatory variables, a common issue in epidemiology, physics, social sciences, and more.



### 🔍 Why use eivpy?

In standard regression, the explanatory variables are assumed to be measured without error. However, in many real-world cases, this assumption fails—leading to biased estimates and undercoverage. eivpy corrects for this by modeling the measurement process explicitly, using techniques such as:
	•	Regression calibration
	•	SIMEX (Simulation-Extrapolation)
	•	Instrumental variable adjustments (planned)
	•	Bayesian EIV modeling (planned)



### 🚀 Features
	•	RegressionCalibration: scikit-learn-style API for corrected regression
	•	Support for known or estimated measurement error variance
	•	Simulation-based inference (e.g., SIMEX)
	•	JAX-compatible core (planned) for fast differentiation & GPU acceleration
	•	Extensive documentation and statistical references


### 🔧 Installation (planned)
```bash
pip install eivpy
```

### 📚 References
	•	Carroll, R. J., et al. (2006). Measurement Error in Nonlinear Models: A Modern Perspective.
	•	Stefanski, L. A., & Cook, J. R. (1995). Simulation-extrapolation: The SIMEX method.
	•	Fuller, W. A. (1987). Measurement Error Models.
