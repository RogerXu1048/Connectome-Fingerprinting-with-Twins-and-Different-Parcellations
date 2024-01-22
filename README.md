# Connectome-Fingerprinting-with-Twins-with-Different-Parcellations
This project aims to investigate the identification accuracy of individuals using their resting-state fMRI scan data. We also explore the effect of using different brain parcellations on the identification accuracy. Twin data are also investigated to see whether twins can be identified based on the resting-state fMRI.

Code written in Matlab. To run the code:

networks_fc_and_snr.mlx (should be run first): calculate FC matrices and tSNR for each network. The outputs are saved and passed to functions in id_report.mlx

id_report.mlx: calculate whole brain FC matrices (when toggle variable is not set to load pre-saved results). Also runs identification report given the whole brain and network fc matrices

sigstar.m: code from MATLAB file exchange by Rob Campbell. Annotates identification rate bar charts with brackets/stars. Slightly modified for visualization on our bar plots.

Files needed to run the code are found in 'files to run scripts', 
along with HCP 7T dataset scans located on Vanderbilt Accre at /data1/datasets/hcp/<subjId> 
