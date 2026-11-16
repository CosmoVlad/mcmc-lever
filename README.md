# MCMC: A Lever to Move the World of Data

Tutorials and assignments for AS.171.322 *MCMC: A Lever to Move the World of Data*, a one-credit undergraduate course at Johns Hopkins University (Intersession 2023), designed and taught by Vladimir Strokov.

## Course description

MCMC (Markov chain Monte Carlo) is a simple, yet powerful algorithm with applications ranging from a straight-line fit to fitting theory to data from a-few-billion-dollar observational facilities. This course represents a series of introductory material seminars paired with hands-on coding tutorials. Necessary programming packages and techniques are introduced during the course, although basic programming knowledge is recommended as a prerequisite.

## Tutorials

| Notebook | Topics |
|---|---|
| [Preliminaries](Preliminaries.ipynb) | The course in a nutshell: sampling, probability distributions, and the plan of the tutorials |
| [1 - Toolbox](1%20-%20Toolbox.ipynb) | NumPy arrays, visualization, timing, quick fits, and root finding |
| [2 - Sampling](2%20-%20Sampling.ipynb) | Probability and cumulative distribution functions, inversion and rejection sampling, and Monte Carlo modeling |
| [3 - The Metropolis&ndash;Hastings algorithm](3%20-%20MetropolisHastings.ipynb) | Implementation and convergence tests (acceptance ratio, autocorrelation time) |
| [4 - Fitting a straight line](4%20-%20Fitting%20a%20straight%20line.ipynb) | Least squares, Bayes' rule, and an MCMC fit with corner plots |
| [5 - Modifications to the Metropolis&ndash;Hastings algorithm](5%20-%20Modifications%20to%20the%20MH%20algorithm.ipynb) | Difficult distributions such as the Rosenbrock density, ensemble samplers, and the `emcee` package |
| [6 - Fitting a gravitational wave](6%20-%20Fitting%20a%20gravitational%20wave.ipynb) | Fourier transforms, noise power spectra, the noise curve of the Laser Interferometer Space Antenna (LISA), and an MCMC fit of a gravitational-wave signal |

[Preamble](Preamble.ipynb) holds the standard imports and plot settings shared by the tutorials.

## Assignments

Each tutorial ends with exercises. Students submitted their solutions as Jupyter notebooks with explanations in Markdown. The [homework](homework) folder contains two sets of home exercises.

## Running the notebooks

The notebooks run either locally in a Python virtual environment or on Google Colab. [Installation](Installation.md) gives step-by-step instructions for both. The tutorials use `numpy`, `scipy`, `matplotlib`, and `jupyter`. Tutorials 4&ndash;6 also use `corner`, and tutorials 5&ndash;6 use `emcee`.
