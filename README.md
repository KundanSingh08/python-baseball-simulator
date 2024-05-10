{
 "cells": [
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "# Simulating baseball in Python\n",
    "\n",
    "This notebook provides the methodology and code used in the blog post, [How much does batting order matter in Major League Baseball? A simulation approach](http://www.randalolson.com/2018/07/04/does-batting-order-matter-in-major-league-baseball-a-simulation-approach).\n",
    "\n",
    "### Notebook by [Randal S. Olson](http://www.randalolson.com)\n",
    "\n",
    "Please see the [repository README file](https://github.com/rhiever/Data-Analysis-and-Machine-Learning-Projects#license) for the licenses and usage terms for the instructional material and code in this notebook. In general, I have licensed this material so that it is as widely useable and shareable as possible.\n",
    "\n",
    "### Required Python libraries\n",
    "\n",
    "If you don't have Python on your computer, you can use the [Anaconda Python distribution](https://www.anaconda.com/download/) to install most of the Python packages you need. Anaconda provides a simple double-click installer for your convenience.\n",
    "\n",
    "This code uses base Python libraries except for `seaborn`, `tqdm`, and `joblib` packages. You can install these packages using `pip` by typing the following commands into your command line:\n",
    "\n",
    "> pip install seaborn tqdm joblib\n",
    "\n",
    "### Using the baseball simulator\n",
    "\n",
    "Below is the Python code used to simulate baseball in my blog post, run the simulations, and generate the data visualizations shown in my blog post. When I get more time, I plan to clean up and comment this code better than it currently is.\n",
    "\n",
    "For the data visualizations, you will need to place [this tableau10.mplstyle](https://gist.github.com/rhiever/d0a7332fe0beebfdc3d5) in your `~/.matplotlib/stylelib/` directory for the visualizations to show up as they do in my blog post. Otherwise, you will have to use [other matplotlib styles](https://matplotlib.org/users/style_sheets.html).\n",
    "\n",
    "If you have any comments or questions about this project, I prefer that you [file an issue](https://github.com/rhiever/Data-Analysis-and-Machine-Learning-Projects/issues/new) on this GitHub repository. If you don't feel comfortable with GitHub, feel free to [contact me by email](http://www.randalolson.com/contact/)."
   ]
  },
