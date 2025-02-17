![Soundsurf logo](https://i.imgur.com/UENzbVk.png)

***

**Soundsurf** is a Java-based tool for modeling 3D rooms and simulating how speakers interact within those spaces. Designed for DIY speaker builders and audio enthusiasts, it helps **visualize how sound waves reflect, interfere, and blend in different environments**. By placing multiple speakers in a virtual room, users can **analyze phase interactions, reflections, and overall acoustics** to fine-tune their setups. Whether optimizing a home audio system or experimenting with speaker placement, Soundsurf provides an interactive way to explore and improve sound performance.


# Features
Soundsurf aims to provide a way to model the acoustic characteristics of three-dimensional spaces. In order to do so, an algorithm called *Finite Difference Time Domain* (or *FDTD*) is used. This algorithm can easily be parallelized, allowing the use of GPUs to speed up simulation time or increase accuracy. It requires the voxelization of the room geometry with respect to the acoustic properties of room boundaries and objects placed within the room.
