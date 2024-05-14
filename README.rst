ETA Factory Building Automation Base Classes
============================================

The *ETA Factory Building Automation Base Classes (ETA BABC)*, developed by the team of the `ETA-Fabrik <https://www.ptw.tu-darmstadt.de>`_ at Technical University of Darmstadt, is a novel Twincat 3 library, which aims at standardized implementation of the industrial energy supply system. Based on a generic data model this libary provides beside the data model implementation specific components like Grundfos Magna3 pumps, several energy counters and valves.

Library structure
-----------------

The library *ETA BABC* consists of two packages for DUTs and POUs. Both packages are structured in the following subpackages

- The **0 Base Classes** package implements the base classes for actuators, sensors and systems following the published, standardized data model.
- The **1 Actors** package holds exemplary implementations for a Grundfos Magna 3 pump, mixing and discrete valves including their local control functions. All components extend from the implementations in **0 Base Classess**.
- The **2 Sensors** package holds exemplary implementations for electricty, gas and heat meters as well as temperature and pressure sensors.
- The **3 Utilities** package holds utility functions like limiters or connectors for specific communication protocols (e.g. Profibus for Grundfos Magna 3 pump).

Citing this project
--------------------

Please cite this project using our publication:

.. code-block::

    Fuhrländer-Völker, Daniel ; Borst, Fabian ; Theisinger, Lukas ; Ranzau, Heiko ; Weigold, Matthias (2022): 
    Modular Data Model for Energy-Flexible Cyber-physical Production Systems. 
    In: Procedia CIRP, Vol: 107, pp. 215-220, Elsevier B.V., DOI: 10.1016/j.procir.2022.04.036
