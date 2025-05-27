
# Water Cluster Cooling Simulation using LAMMPS

This project demonstrates molecular dynamics (MD) simulations of water molecules in both 3D periodic systems using LAMMPS. As the system cools, water molecules transition from a dispersed state to condensed clusters, mimicking phenomena such as condensation and early-stage freezing.

>  This project is currently in progress. Simulation input files, scripts, and results will be uploaded soon.

---

## Project Objectives

- Simulate water molecule motion using classical MD
- Apply gradual cooling to observe thermal behavior
- Visualize condensation and clustering
- Compare water behavior in 3D systems

---

## Methodology

| Feature       | Description                                          |
|---------------|------------------------------------------------------|
| Software      | LAMMPS                                               |
| Water Model   | TIP3P or SPC/E                                       |
| Box Setup     | Periodic boundary conditions 3D                      |
| Initialization| Random molecular positions                           |
| Thermostat    | Used to apply cooling                                |
| Output        | Dump files for visualization                         |
| Visualization | Ovito / VMD                                          |

---

## File Contents

| File           | Purpose                                          |
|----------------|--------------------------------------------------|
| `water.in`     | Main input script for LAMMPS                     |
| `data.water`   | Initial coordinates and topology                 |
| `log.lammps`   | Simulation log output                            |
| `dump.water`   | Atom trajectories for visualization              |
| `cooling_visual.mp4` | Optional video showing molecular clustering |
| `README.md`    | Project overview and instructions                |

---

## Author

**Handsome Gisubizo**  
MSE Chemical & Biomolecular Engineering  
Johns Hopkins University  
 [hgisubi1@jhu.edu](mailto:hgisubi1@jh.edu)  
 [@handsongisubizo](https://github.com/handsongisubizo)

---

## License

Released under the MIT License. Use and modification are allowed with attribution.

---

## Tags

`LAMMPS` `MolecularDynamics` `WaterSimulation` `Cooling` `TIP3P` `SPCE` `Ovito` `PhaseTransition `3D`
