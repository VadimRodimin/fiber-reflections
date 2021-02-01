# Fiber-reflections: reflected fiber-optics signals simulation
In order to understand the origin of various reflected signals  in the fiber optical scheme, we simulated reflections.

The project is related to fiber-optic circuits and networks. In complex, branched schemes, as, in particular, in go-and-return schemes, laser pulses undergo multiple reflections. This becomes especially critical when we work with very weak laser pulses. This is exactly what happens in the case of a quantum key distribution.

The typical value of reflections from FC/PC connectors and some of other extinction values of optical components is about 20 dB. As a result, many reflections of unclear origin are returned to the detectors. For easier identification of the working reflection and an effective adjustment of the setup it is very desirable to isolate it in time or/and essentially weaken the shading signals. Without much pain, one can clean and polish the connectors, replace FC/PC with APC ones, or even fusion splice the fiber. In order to understand the origin of various reflected signals on the reflectogram, we simulated reflections in the optical scheme.

Perhaps the most difficult and controversial part of the code is describing the optical circuit as a dictionary. The compilation of this dictionary requires care. To avoid mistakes, it is necessary to draw a detailed drawing with the coordinates of the optical components and the names of the branches. In our opinion, the best modification of the code would be to change the method for specifying the optical scheme. For example, it can be a table with the names of optical components, their coordinates, and connections. Further, the necessary dictionary will be generated from this table.

The code was developed by Vadim Rodimin vadim.rodimin@gmail.com, visualization in the form of graphs was added by Anton Bendersky loderan@ruservice.ru
