# hnn_tep_modeling
Template code for modeling and plotting TMS Evoked Potentials in HNN. 

Please note that we are using a custom version of HNN in [Joyce's fork of hnn-core that includes NGF drives](https://github.com/xgao35/hnn-core/tree/feat/tms-ngfc). NGF cell drives come from aritificial cells that synapse onto L2 pyramidal apical tuft, L5 pyramidal apical tuft, and L2 Interneuron GABAa and GABAb receptors. The implementation in that repository is pretty scrappy, so if other lab members have cleaner implementations, or if these drives are included in a future offical hnn-core release, please use their versions instead. 

## Contents

`BETA9_80AMT_hand.ipynb` walks through the hand-tuning process for a single subject or group aggregate waveform \
`BETA9_80AMT_optimization.ipynb` walks through the optimization of the hand-tuned parameters \
`TEP_plotting.ipynb` plots the simulation, including dipoles, spiking, calcium dynamics, magnesium blocks, and NMDA current 


`MBD_Fig[x].ipynb` contains plots for Joyce's 2026 Mind Brain Day poster. This was ran on an older version of hnn-core, so the simulations may have issue running. However, this is kept in this repository since the plotting code may still be helpful.