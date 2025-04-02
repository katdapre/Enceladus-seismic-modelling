# Enceladus-seismic-modelling
Collection of scripts used to perform seismic wavefield modelling of Enceladus during my PhD.

Jupyter notebooks supplied help with building, running, processing, plotting, and interpreting AxiSEM and AxiSEM3D simulations for Enceladus as described in Dapré & Irving 2024, 2025.

Ray-theoretical TauP travel time predictions can be obtained using taupcurveplot.ipynb, tauppath_alldistances.ipynb, improved_tauppathplot.ipynb.

Conversion between 1D model files compatible with AxiSEM (.bm) and TauP (.nd) can be performed using taup-to-axisem.ipynb and axisem-to-taup.ipynb.

Interfacing with AxiSEM3D netcdf model files is demonstrated via plot_thickness.ipynb.

run_axisem.ipynb is a centralised way to perform an AxiSEM run that just incorporates all necessary shell commands and text file editing into one script.

Processing of raw output seismograms can be done using write_record_section.ipynb (for AxiSEM) or write_3D_record_section.ipynb (for AxiSEM3D).

Plotting and interpretation of global wavefield is made easier by plot_record_section.ipynb (for AxiSEM) or plot_3D_record_section (for AxiSEM3D).

Examples of single-station waveform processing is contained in spectrogram.ipynb.

Coming soon: MATLAB codes for constructing core models.
