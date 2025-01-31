.. mvsim documentation master file, created by
   sphinx-quickstart on Sat May 30 11:36:10 2020.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.

MultiVehicle simulator (libmvsim)
=================================

.. toctree::
   :maxdepth: 3
   :hidden:

   Home <self>
   features
   install
   first-steps
   architecture
   world
   physics
   extending
   C++ API <doxygen/html/modules.html#http://>

.. (JLBC note: Do not remove the #http:// above, it's the only way I found to allow that link to be included in the TOC).


About
======
Lightweight, realistic dynamical simulator for 2D ("2.5D") vehicles and robots.
It is tailored to analysis of vehicle dynamics, wheel-ground contact forces and
accurate simulation of typical robot sensors (e.g. laser scanners).

This project includes a C++ library `mvsim`, a standalone app, and a ROS1 node.

Licensed under the permissive 3-clause BSD License.

If you want to cite MVSim in your work, please use:

.. code-block:: bibtex

 @misc{mvsim,
  doi = {10.48550/ARXIV.2302.11033},
  url = {https://arxiv.org/abs/2302.11033},
  author = {Blanco-Claraco, José-Luis and Tymchenko, Borys and Mañas-Alvarez, Francisco José and Cañadas-Aránega, Fernando and López-Gázquez, Ángel and Moreno, José Carlos},  
  title = {MultiVehicle Simulator (MVSim): lightweight dynamics simulator for multiagents and mobile robotics research},  
  publisher = {arXiv},
  year = {2023}
 }


.. figure:: https://mrpt.github.io/mvsim-models/anims/warehouse-demo-mvsim.gif
  :alt: MVSIM Simulating Jackal Robot in ROS2
  :target: first-steps.html

.. image:: https://img.youtube.com/vi/xMUMjEG8xlk/0.jpg
  :width: 400
  :alt: MvSim intro
  :target: https://www.youtube.com/watch?v=xMUMjEG8xlk

Documentation credits:

   - Borys Tymchenko `@spsancti <https://github.com/spsancti>`_
   - Jose Luis Blanco Claraco `@jlblancoc <https://github.com/jlblancoc>`_

Github repository: https://github.com/MRPT/mvsim

