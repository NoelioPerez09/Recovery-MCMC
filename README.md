# Recovery-MCMC
## Description
Bed Topography mapping of the Recovery Ice Stream using Sequential Gaussian Simulation (SGS) and the Metropolis–Hastings (Markov Chain Monte Carlo) algorithm.

## Note
Please download the images if you want to see them in fullscreen, don't use the "Open image in new tab" as GitHub doesn't handle .svg visualization in fullscreen well.

## Initial Topographies
![BedMachine](./figures/bedmachine.svg)

Topography of BedMachine3, the current benchmark for ice flux divergence loss and mass conservation residuals.

![SGS](./figures/sgs.svg)

Topography generated from a Sequential Gaussian Simulation, high level of detail and high resolution textures compared to BedMachine3, but does not abide by the law of mass conversation. Used as a starting point for the large scale MCMC simulation. 

## MCMC Topography 
![MCMC](./figures/Placeholder_image1.png)
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.

![Loss Function Graph](./figures/Placeholder_image.png)
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.

# Installation

Note: The following instructions are intended for UNIX-based Operating Systems (i.e. MacOS and Linux). If you are on Windows (not UNIX-based), you must download [Git Bash](https://git-scm.com/install/windows) or a similar UNIX command line interpreter to run this commands. Also, I used Python 3.12.3, but any Python version between 3.10 and 3.14 (inclusive) should work fine.

1. Clone the repository using ```git clone https://github.com/NoelioPerez09/Recovery-MCMC.git```.
2. Navigate to the downloaded directory using ```cd Recovery-MCMC```.
3. Create a ```venv``` virtual environment using ```python -m venv venv``` and activate it using ```source venv/bin/activate```.
4. Install all required libraries using ```pip install -r requirements.txt```
5. After this you can either use ```jupyter lab``` to use Jupyter's IDE or use any IDE of your liking. I personally used [Visual Studio Code](https://code.visualstudio.com/), but any IDE
that can run Python and Jupyter Notebook files should work.


# Tutorial
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.

## Poster
![Full Poster](./figures/poster.svg)
