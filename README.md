# Antenna-Design-and-Ray-Tracing-with-FEKO

This project integrates antenna design and ray-tracing simulations using FEKO and its propagation analysis tools. The project includes the following key steps:

1. Antenna Design
Designed antennas for 300 GHz and 130 GHz frequencies in CADFEKO.
Parameters:
300 GHz Antenna: WR3 waveguide with a custom-designed flare.
130 GHz Antenna: WR7 waveguide with square horn dimensions.  
Simulated radiation patterns in POSTFEKO, generating 2D polar plots and 3D gain patterns.
Explored gain efficiency and effective area optimizations for high-frequency antennas.
2. Ray-Tracing Simulation
Modeled wave propagation in indoor and outdoor environments using WinProp tools like WallMan and ProMan.
Designed an indoor office environment in WallMan, setting material properties such as brick and wood for walls.
Compared propagation characteristics at 2.4 GHz (omnidirectional antenna) and 130 GHz (directional antenna):
Analyzed wall penetration, path loss, and coverage area differences.
Evaluated material impact and antenna height on signal strength and coverage.
Key Insights
Signal Propagation Obstacles:
Materials like metal caused higher losses, while brick had moderate impact.
Frequency Analysis:
Lower frequencies (2.4 GHz) exhibited better wall penetration and broader coverage, while higher frequencies (130 GHz) showed greater path loss but more directional precision.
Optimization:
Explored adjustments to antenna height and placement to improve coverage in specific scenarios.
