# Approximation of a dust grain by an ellipsoid

The program creates a random dust grain from `N` connected balls. Then an ellipsoid is constructed, which should well approximate dust grain geometric shape.

You can visually select the most appropriate size of the ellipsoid by changing the parameter `n_sigma`. At the end, the lengths of the semi-axes of the ellipsoid will be displayed.


## Usage
To work with the program, use any convenient Jupyter-program. Or convert it to regular python-code and run:
```bash
python3 dust_ellipsoid_approximation.py
```

You can change the number of random balls `N` (the larger it is, the more difficult it will be for your computer to draw the picture) and the size of the ellipsoid `n_sigma` (linear size coefficient; the larger it is, the larger the ellipsoid).


## Additional information
- The following packages are required for the program to work:
	- **numpy**
	- **sklearn**
	- **mayavi**

- If you find an error, be sure to report it.

### You may copy, modify and distribute this code, but must provide attribution

