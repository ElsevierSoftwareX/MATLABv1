# eRDF Analyser - MATLABv1

Latest release: v1.0 [06/03/2017]

eRDF Analyser is an interactive and integrated tool for electron reduced density function analysis. 
This tool allows users to input an electron diffraction pattern (obtained from a TEM) and guides them interactively through the process of fitting and extracting the reduced density function (RDF) for their material.

This tool is available as open source code and in executable form (both covered under the terms of the GNU General Public License version 3). Compatibility with versions of MATLAB other than R2015b is not guaranteed, although it has been tested on R2014a-R2016b on Windows/Mac OS.

The <b>source code</b> is available in the main repository, or see Release (https://github.com/eRDFAnalyser/MATLABv1/releases/tag/v1.0) for the package which includes:
- <i>.m</i> and <i>.fig</i> files for the GUI
- <i>Parameter_files</i> folder containing electron atomic scattering factors
- <i>Help</i> folder containing user manual documentation
- <i>Test_data</i> folder containing example diffraction data

The <b>standalone executable</b> (Windows only) package requires MATLAB Runtime version 9.0 (2015b). If you already have this runtime version, you can download and run the <i>eRDF_Analyser_web.exe</i> installer (https://github.com/eRDFAnalyser/MATLABv1/releases/tag/v1.0). If not, the runtime can be downloaded from http://www.mathworks.com/products/compiler/mcr.html and installed before running the abovementioned executable installer. You can also choose to download the <i>eRDF_Analyser_mcr.exe</i> installer instead - a bigger file which is packaged with the runtime.

<i>Note: Dependng on system specifications, launching of the software may be slow due to initialisation of the runtime environment (comparable to launching MATLAB).</i>

The <b>user manual</b> can be accessed online at https://erdfanalyser.github.io/MATLABv1/

Contact Information:

J Shanmugam (janaki.shanmugam@materials.ox.ac.uk), KB Borisenko (konstantin.borisenko@materials.ox.ac.uk),
Electron Image Analysis Group, Department of Materials, University of Oxford
