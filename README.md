I am currently a post-doctoral researcher at the [Department of Earth and Planetary Science, UC Berkeley](https://eps.berkeley.edu), United States. Although I am intrigued by all sorts of data science works, my primary research interests are in Geophysics (mostly seismology), and Geodesy. I work on the tools that support data-intensive research and build open-source software tools. I am highly interested in geospatial big data, machine learning, and cloud computing.

## Current projects (Not open-source yet)
1. Developing a 3D elastic model of __deep structure beneath the Yellowstone hotspot__ (from surface to the Core-Mantle Boundary). This involves:
    1. Developing and finalizing codes for _full-waveform inversion using Normal-mode perturbation theory_
    2. Implementing _full-waveform inversion using the Adjoint method_
    3. Developing and running codes on supercomputing clusters, e.g., Texas Advanced Computing Center (TACC), National Energy Research Scientific Computing Center (NERSC)
    4. Developing codes that can be parallelized on CPUs and GPUs on any computing facilities (small clusters to supercomputing clusters).
    5. Visualizing tomographic results by rendering in 2D and 3D.
2. Development of a low-cost __structural health monitoring system__ - Quake Structural Integrity System (QSIS). This involves:
    1. Assembling a single board computing (SBC) system and sensors to build the client system
    2. Development of the _client software_ to record, process, store, and transmit the data in real-time
    3. Development of the _server softwares_ to run on the receiving end of the client software to retrieve the realtime data from multiple clients asynchronously through websocket connection, and post-process data. The server is also responsible for the computation of structural parameters like natural frequencies of the structures, S-wave velocity and damping parameters. It also send alerts to the users by emails or app notifications.

## Open-source projects
1. [dtwhaclustering: A python package to cluster geodetic time series](https://pypi.org/project/dtwhaclustering/)
2. [Voice-Plotter: A GUI application to visualize real-time ambient sounds](https://www.earthinversion.com/downloads/voice-plotter-application/)
3. [System-monitor: A GUI application to get real-time feedback on system runtime statistics](https://www.earthinversion.com/downloads/system-monitor-application-for-windows/)
4. [Miniseed2mat: Convert miniseed data format to MATLAB's native MAT format](https://pypi.org/project/miniseed2mat/)
5. [FerryMan: A web application to identify the "comfort" zone of different species based on their Ecological Index](https://github.com/earthinversion/FerryMan.git)


## Some Blog Posts
1. [Using dask Python library to read a huge global earthquake catalog file](https://www.earthinversion.com/utilities/using-dask-python-library-to-read-a-huge-global-earthquake-catalog-file/)
2. [How to plot earthquakes data on a three-dimensional topographic map](https://www.earthinversion.com/utilities/how-to-plot-the-earthquake-data-on-three-dimensional-topographic-map/)
3. [Convert any text to lifelike speech using Amazon Polly](https://www.earthinversion.com/blogging/convert-any-text-to-lifelike-speech-using-amazon-polly/)
4. [How to overlay shapefile data on PyGMT Maps](https://www.earthinversion.com/utilities/how-to-overlay-shapefiles-on-pygmt-maps/)
5. [How to plot Shear-wave splitting measurements using PyGMT](https://www.earthinversion.com/techniques/how-to-plot-shear-wave-splitting-measurements-using-pygmt/)
6. [How effective is the signal denoising using the MATLAB based wavelet analysis](https://www.earthinversion.com/techniques/how-effective-is-the-signal-denoising-using-the-matlab-based-wavelet-analysis/)
7. [Empirical Orthogonal Function analysis to inspect the spatial coherency in the geospatial data](https://www.earthinversion.com/geophysics/empirical-orthogonal-function-analysis-to-inspect-spatial-coherency-of-geospatial-data/)
8. [Signal denoising using Fourier Analysis in Python](https://www.earthinversion.com/techniques/signal-denoising-using-fast-fourier-transform/)
9. [Transfer learning applied on the unsplash data using alexnet pretrained network](https://www.earthinversion.com/machinelearning/transfer-learning-applied-on-unsplash-data-using-alexnet/)
10. [PyQt5 Application for visualizing ambient sound in real-time](https://www.earthinversion.com/desktopapps/pyqt5-application-for-visualizing-ambient-sound-in-real-time/)

For more info, visit my blog: [earthinversion.com](https://www.earthinversion.com)


![github stats](https://github-readme-stats.vercel.app/api?username=earthinversion&show_icons=true)
![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=earthinversion&langs_count=3&hide=javascript,go,html,css,tex)

![](https://komarev.com/ghpvc/?username=earthinversion&color=brightgreen)
