# Rayleigh-Taylor-Instability-using-InterIsoFoam
This repository contains the interIsoFoam solver setup for DNS of Rayleigh-Taylor Instability. The results are validated with another DNS simulation by LBM, showing similar growth and interfacial patterns. The minor delay of RTI in the OpenFoam result compared to the LBM solver is most likely due to the solvers' handling of buoyancy force differently and the temporal lag due to the coarser mesh size used in the earlier studies.


![image](https://github.com/user-attachments/assets/35b5f8e1-545c-4c22-a2e9-923b7153d94a)

The scaled positions of the spike and bubble are plotted over the dimensionless time and validated it Liang et al's result.

![image](https://github.com/user-attachments/assets/ada82b4c-c478-4ba3-8009-4da6f06c1a5a)

